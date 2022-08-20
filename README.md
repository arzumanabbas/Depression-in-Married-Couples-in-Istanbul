# Depression-in-Married-Couples-in-Istanbul
<div class="cell markdown" id="ICjFq0o8kEgo">

<p style="text-align: center;"><strong><h1>ABOUT DATA</h1></strong></p>

<p>The data has been collected in Ä°stanbul via an online form. It is aimed to examine the depression scores of married people and the influence of demographic factors.<br>Demographic Questions and Beck Depression Inventory is used to collect data. Total Score of Scale must be calculated by the sum of items B1-B21. Codes reflecting the categories of demographic questions are as below.</p>

<p><br>Gender: 1-Female, 2-Male;&nbsp;</p>

<p>Education: 1-Primary, 2-High School, 3-Bachelor, 4-Msc or PhD;&nbsp;</p>

<p>Working Status: 1-Employed, 2-Unemployed;&nbsp;</p>

<p>Marriage Style : 1-Arranged Marriage, 2-Flirt Marriage;&nbsp;</p>

<p>Status of Having a Child: 1-Yes, 2-No&nbsp;</p>

</div>

<div class="cell markdown" id="w1N1QjWkk9Zf">

<strong><h1>Beck's Depression
Inventory<a href="https://www.kaggle.com/code/ayushmehar7/marital-depression-analysis#Beck's-Depression-Inventory" target="_self" rel=" noreferrer nofollow"></a></h1></strong>
<p>The Beck Depression Inventory (BDI), created by Aaron T. Beck, is a
21-question multiple-choice self-report inventory, one of the most
widely used psychometric tests for measuring the severity of depression.
Its development marked a shift among mental health professionals, who
had until then, viewed depression from a psychodynamic perspective,
instead of it being rooted in the patient's own thoughts.</p> <p>Each of
the 21 questions are 4 optioned questions having score from 0 to 3.
Minimum score being 0 and maximum being 63.The degree of depression is
directly proportional to the BDI score</p> <p>Some of the questions are
:</p> <ol> <li><br> <ul> <li>0 I do not feel sad</li> <li>1 I feel
sad</li> <li>2 I am sad all the time and I can't snap out of it.</li>
<li>3 I am so sad and unhappy that I can't stand it.</li> </ul> </li>
<li><br> <ul> <li>0 I am not particularly discouraged about the
future.</li> <li>1 I feel discouraged about the future.</li> <li>2 I
feel I have nothing to look forward to.</li> <li>3 I feel the future is
hopeless and that things cannot improve.</li> </ul> </li> </ol> <p>For
more details on the
questionsÂ <a href="https://www.ismanet.org/doctoryourspirit/pdfs/Beck-Depression-Inventory-BDI.pdf" rel=" noreferrer nofollow">visit
here</a></p> <h2>BDI
Score<a href="https://www.kaggle.com/code/ayushmehar7/marital-depression-analysis#BDI-Score" target="_self" rel=" noreferrer nofollow"></a></h2>
<p>Based on the BDI score, the patient is categorised as follows :</p>
<ul> <li>Below 10 : These ups and downs are considered normal</li>
<li>11-16 : Mild mood disturbance</li> <li>17-20 : Borderline clinical
depression</li> <li>21-30 : Moderate depression</li> <li>31-40 : Severe
depression</li> <li>Over 40 : Extreme depression</li> </ul>

</div>

<div class="cell markdown" id="NFw-3tsFtbPm">

## Importing Required Packages

</div>

<div class="cell code" data-execution_count="174" id="uGoARAk7MhKH">

``` python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```

</div>

<div class="cell markdown" id="pqke83T3tg31">

## Loading Data

</div>

<div class="cell code" data-execution_count="175" data-colab="{&quot;height&quot;:235,&quot;base_uri&quot;:&quot;https://localhost:8080/&quot;}" id="UXBFHZ9gNP5W" data-outputId="a2760387-17c6-4ee3-b420-5161f54109fe">

``` python
df = pd.read_csv('Dataset 1.csv')
df.head()
```

<div class="output execute_result" data-execution_count="175">

``` 
    No  Gender  Education  Working Status  Marriage Style  \
0  345       2          4               2               2   
1   73       2          3               2               2   
2  107       2          4               2               2   
3  131       2          4               2               2   
4    4       2          4               2               1   

   Status of Having a Child  B1  B2  B3  B4  ...  B12  B13  B14  B15  B16  \
0                         2   3   3   3   3  ...    3    3    3    3    3   
1                         1   1   1   1   1  ...    1    0    1    1    0   
2                         1   0   0   0   1  ...    1    0    1    0    0   
3                         1   0   1   0   1  ...    0    0    0    0    3   
4                         1   0   0   0   0  ...    0    0    0    0    0   

   B17  B18  B19  B20  B21  
0    3    3    3    3    3  
1    1    0    0    0    0  
2    1    0    0    0    1  
3    0    0    0    0    0  
4    0    0    0    0    0  

[5 rows x 27 columns]
```

</div>

</div>

<div class="cell markdown" id="KIEfYk3Ctjjd">

## Data Manipulation

</div>

<div class="cell markdown" id="XDExo6TO2bvY">

***We'll need to make some small changes to make better visualizations,
make working with the data easier, and make the data more meaningful.***

</div>

<div class="cell code" data-execution_count="176" id="E5l5jGyGOHVy">

``` python
df['Gender'] = df['Gender'].replace(1, 'Female')
df['Gender'] = df['Gender'].replace(2, 'Male')
```

</div>

<div class="cell code" data-execution_count="177" data-colab="{&quot;height&quot;:235,&quot;base_uri&quot;:&quot;https://localhost:8080/&quot;}" id="jluetl7pO-ts" data-outputId="e2593fd6-405e-45d9-8e6a-dc4b19dfe348">

``` python
df.head()
```

<div class="output execute_result" data-execution_count="177">

``` 
    No Gender  Education  Working Status  Marriage Style  \
0  345   Male          4               2               2   
1   73   Male          3               2               2   
2  107   Male          4               2               2   
3  131   Male          4               2               2   
4    4   Male          4               2               1   

   Status of Having a Child  B1  B2  B3  B4  ...  B12  B13  B14  B15  B16  \
0                         2   3   3   3   3  ...    3    3    3    3    3   
1                         1   1   1   1   1  ...    1    0    1    1    0   
2                         1   0   0   0   1  ...    1    0    1    0    0   
3                         1   0   1   0   1  ...    0    0    0    0    3   
4                         1   0   0   0   0  ...    0    0    0    0    0   

   B17  B18  B19  B20  B21  
0    3    3    3    3    3  
1    1    0    0    0    0  
2    1    0    0    0    1  
3    0    0    0    0    0  
4    0    0    0    0    0  

[5 rows x 27 columns]
```

</div>

</div>

<div class="cell code" data-execution_count="178" id="xIJtS4jVPMTO">

``` python
df['Education'] = df['Education'].replace(1, 'Primary')
df['Education'] = df['Education'].replace(2, 'High School')
df['Education'] = df['Education'].replace(3, 'Bachelor')
df['Education'] = df['Education'].replace(4, 'Msc or PhD')
```

</div>

<div class="cell code" data-execution_count="179" data-colab="{&quot;height&quot;:235,&quot;base_uri&quot;:&quot;https://localhost:8080/&quot;}" id="ZU5nEbaNPuuf" data-outputId="ad8ca2f8-5623-44ce-97e3-46f5b0597623">

``` python
df.head()
```

<div class="output execute_result" data-execution_count="179">

``` 
    No Gender   Education  Working Status  Marriage Style  \
0  345   Male  Msc or PhD               2               2   
1   73   Male    Bachelor               2               2   
2  107   Male  Msc or PhD               2               2   
3  131   Male  Msc or PhD               2               2   
4    4   Male  Msc or PhD               2               1   

   Status of Having a Child  B1  B2  B3  B4  ...  B12  B13  B14  B15  B16  \
0                         2   3   3   3   3  ...    3    3    3    3    3   
1                         1   1   1   1   1  ...    1    0    1    1    0   
2                         1   0   0   0   1  ...    1    0    1    0    0   
3                         1   0   1   0   1  ...    0    0    0    0    3   
4                         1   0   0   0   0  ...    0    0    0    0    0   

   B17  B18  B19  B20  B21  
0    3    3    3    3    3  
1    1    0    0    0    0  
2    1    0    0    0    1  
3    0    0    0    0    0  
4    0    0    0    0    0  

[5 rows x 27 columns]
```

</div>

</div>

<div class="cell code" data-execution_count="180" id="Gm6EdonMP1Q2">

``` python
df['Working Status'] = df['Working Status'].replace(1, 'Employed')
df['Working Status'] = df['Working Status'].replace(2, 'Unemployed')
```

</div>

<div class="cell code" data-execution_count="181" data-colab="{&quot;height&quot;:235,&quot;base_uri&quot;:&quot;https://localhost:8080/&quot;}" id="HdlQE-hmQGkt" data-outputId="809d17c8-2f9a-4e71-b198-86cf5381fe8f">

``` python
df.head()
```

<div class="output execute_result" data-execution_count="181">

``` 
    No Gender   Education Working Status  Marriage Style  \
0  345   Male  Msc or PhD     Unemployed               2   
1   73   Male    Bachelor     Unemployed               2   
2  107   Male  Msc or PhD     Unemployed               2   
3  131   Male  Msc or PhD     Unemployed               2   
4    4   Male  Msc or PhD     Unemployed               1   

   Status of Having a Child  B1  B2  B3  B4  ...  B12  B13  B14  B15  B16  \
0                         2   3   3   3   3  ...    3    3    3    3    3   
1                         1   1   1   1   1  ...    1    0    1    1    0   
2                         1   0   0   0   1  ...    1    0    1    0    0   
3                         1   0   1   0   1  ...    0    0    0    0    3   
4                         1   0   0   0   0  ...    0    0    0    0    0   

   B17  B18  B19  B20  B21  
0    3    3    3    3    3  
1    1    0    0    0    0  
2    1    0    0    0    1  
3    0    0    0    0    0  
4    0    0    0    0    0  

[5 rows x 27 columns]
```

</div>

</div>

<div class="cell code" data-execution_count="182" id="7SGobHLRQJZ-">

``` python
df['Marriage Style'] = df['Marriage Style'].replace(1, 'Arranged Marriage')
df['Marriage Style'] = df['Marriage Style'].replace(2, 'Flirt Marriage')
```

</div>

<div class="cell code" data-execution_count="183" data-colab="{&quot;height&quot;:235,&quot;base_uri&quot;:&quot;https://localhost:8080/&quot;}" id="OvbqCqdRQi8A" data-outputId="8d058405-e2c7-4117-fa60-922bd6d39d1a">

``` python
df.head()
```

<div class="output execute_result" data-execution_count="183">

``` 
    No Gender   Education Working Status     Marriage Style  \
0  345   Male  Msc or PhD     Unemployed     Flirt Marriage   
1   73   Male    Bachelor     Unemployed     Flirt Marriage   
2  107   Male  Msc or PhD     Unemployed     Flirt Marriage   
3  131   Male  Msc or PhD     Unemployed     Flirt Marriage   
4    4   Male  Msc or PhD     Unemployed  Arranged Marriage   

   Status of Having a Child  B1  B2  B3  B4  ...  B12  B13  B14  B15  B16  \
0                         2   3   3   3   3  ...    3    3    3    3    3   
1                         1   1   1   1   1  ...    1    0    1    1    0   
2                         1   0   0   0   1  ...    1    0    1    0    0   
3                         1   0   1   0   1  ...    0    0    0    0    3   
4                         1   0   0   0   0  ...    0    0    0    0    0   

   B17  B18  B19  B20  B21  
0    3    3    3    3    3  
1    1    0    0    0    0  
2    1    0    0    0    1  
3    0    0    0    0    0  
4    0    0    0    0    0  

[5 rows x 27 columns]
```

</div>

</div>

<div class="cell code" data-execution_count="184" data-colab="{&quot;height&quot;:235,&quot;base_uri&quot;:&quot;https://localhost:8080/&quot;}" id="WBIOrE6CQlSG" data-outputId="2e0c5ca0-0902-44e3-cb8d-60abacb134e9">

``` python
df['Status of Having a Child'] = df['Status of Having a Child'].replace(1, 'Yes')
df['Status of Having a Child'] = df['Status of Having a Child'].replace(2, 'No')
df.head()
```

<div class="output execute_result" data-execution_count="184">

``` 
    No Gender   Education Working Status     Marriage Style  \
0  345   Male  Msc or PhD     Unemployed     Flirt Marriage   
1   73   Male    Bachelor     Unemployed     Flirt Marriage   
2  107   Male  Msc or PhD     Unemployed     Flirt Marriage   
3  131   Male  Msc or PhD     Unemployed     Flirt Marriage   
4    4   Male  Msc or PhD     Unemployed  Arranged Marriage   

  Status of Having a Child  B1  B2  B3  B4  ...  B12  B13  B14  B15  B16  B17  \
0                       No   3   3   3   3  ...    3    3    3    3    3    3   
1                      Yes   1   1   1   1  ...    1    0    1    1    0    1   
2                      Yes   0   0   0   1  ...    1    0    1    0    0    1   
3                      Yes   0   1   0   1  ...    0    0    0    0    3    0   
4                      Yes   0   0   0   0  ...    0    0    0    0    0    0   

   B18  B19  B20  B21  
0    3    3    3    3  
1    0    0    0    0  
2    0    0    0    1  
3    0    0    0    0  
4    0    0    0    0  

[5 rows x 27 columns]
```

</div>

</div>

<div class="cell markdown" id="CpyX2LDWtv1W">

## Data Cleaning

</div>

<div class="cell code" data-execution_count="185" data-colab="{&quot;base_uri&quot;:&quot;https://localhost:8080/&quot;}" id="z36BpI0Hs_S4" data-outputId="95ac8e19-1753-4ae6-939c-29022b5d080f">

``` python
df.isnull().sum()
```

<div class="output execute_result" data-execution_count="185">

    No                          0
    Gender                      0
    Education                   0
    Working Status              0
    Marriage Style              0
    Status of Having a Child    0
    B1                          0
    B2                          0
    B3                          0
    B4                          0
    B5                          0
    B6                          0
    B7                          0
    B8                          0
    B9                          0
    B10                         0
    B11                         0
    B12                         0
    B13                         0
    B14                         0
    B15                         0
    B16                         0
    B17                         0
    B18                         0
    B19                         0
    B20                         0
    B21                         0
    dtype: int64

</div>

</div>

<div class="cell markdown" id="4-bsPuhz23yg">

***We see that there are no null values â€‹â€‹in the data.***

</div>

<div class="cell code" data-execution_count="186" data-colab="{&quot;height&quot;:423,&quot;base_uri&quot;:&quot;https://localhost:8080/&quot;}" id="JzJRpNEg1V16" data-outputId="73a82033-f4b5-49a1-ca4e-4349d63ea2f8">

``` python
df.drop(columns=['No'])
```

<div class="output execute_result" data-execution_count="186">

``` 
     Gender    Education Working Status     Marriage Style  \
0      Male   Msc or PhD     Unemployed     Flirt Marriage   
1      Male     Bachelor     Unemployed     Flirt Marriage   
2      Male   Msc or PhD     Unemployed     Flirt Marriage   
3      Male   Msc or PhD     Unemployed     Flirt Marriage   
4      Male   Msc or PhD     Unemployed  Arranged Marriage   
..      ...          ...            ...                ...   
428  Female  High School       Employed  Arranged Marriage   
429  Female  High School       Employed  Arranged Marriage   
430  Female      Primary       Employed  Arranged Marriage   
431  Female     Bachelor       Employed     Flirt Marriage   
432  Female      Primary       Employed     Flirt Marriage   

    Status of Having a Child  B1  B2  B3  B4  B5  ...  B12  B13  B14  B15  \
0                         No   3   3   3   3   3  ...    3    3    3    3   
1                        Yes   1   1   1   1   1  ...    1    0    1    1   
2                        Yes   0   0   0   1   1  ...    1    0    1    0   
3                        Yes   0   1   0   1   1  ...    0    0    0    0   
4                        Yes   0   0   0   0   1  ...    0    0    0    0   
..                       ...  ..  ..  ..  ..  ..  ...  ...  ...  ...  ...   
428                      Yes   0   0   0   0   0  ...    0    0    0    0   
429                      Yes   0   0   0   1   0  ...    1    0    1    1   
430                      Yes   0   0   0   0   0  ...    1    2    1    1   
431                      Yes   0   0   0   0   0  ...    1    0    0    0   
432                      Yes   0   0   0   0   0  ...    0    0    0    0   

     B16  B17  B18  B19  B20  B21  
0      3    3    3    3    3    3  
1      0    1    0    0    0    0  
2      0    1    0    0    0    1  
3      3    0    0    0    0    0  
4      0    0    0    0    0    0  
..   ...  ...  ...  ...  ...  ...  
428    0    0    0    0    0    0  
429    0    1    0    0    1    2  
430    1    2    0    0    2    1  
431    0    0    0    0    0    0  
432    0    0    0    0    0    0  

[433 rows x 26 columns]
```

</div>

</div>

<div class="cell markdown" id="88bW8yYD3tBp">

***The numbering order is data we don't need. And we have to get rid of
it.***

</div>

<div class="cell markdown" id="cl79eytKt2bk">

## Basic Statistics

</div>

<div class="cell markdown" id="dQUpQV4t37lh">

***Let's see how many columns and rows there are.***

</div>

<div class="cell code" data-execution_count="187" data-colab="{&quot;base_uri&quot;:&quot;https://localhost:8080/&quot;}" id="KOPAIw0btJhh" data-outputId="d7f98889-be6f-4764-ea03-0c1945599965">

``` python
df.shape
```

<div class="output execute_result" data-execution_count="187">

    (433, 27)

</div>

</div>

<div class="cell markdown" id="sKgJ5nwx4Gx5">

***Let's look at some basic statistics like mean, median, standart
deviation and etc. about the data.***

</div>

<div class="cell code" data-execution_count="188" data-colab="{&quot;height&quot;:393,&quot;base_uri&quot;:&quot;https://localhost:8080/&quot;}" id="QoimfFoDtPBU" data-outputId="87c5bdb6-5f74-4016-d61b-e696f10e98a3">

``` python
df.describe()
```

<div class="output execute_result" data-execution_count="188">

``` 
               No          B1          B2          B3          B4          B5  \
count  433.000000  433.000000  433.000000  433.000000  433.000000  433.000000   
mean   216.274827    0.397229    0.392610    0.450346    0.612009    0.678984   
std    125.181852    0.747955    0.741083    0.834974    0.668085    0.620593   
min      1.000000    0.000000    0.000000    0.000000    0.000000    0.000000   
25%    108.000000    0.000000    0.000000    0.000000    0.000000    0.000000   
50%    215.000000    0.000000    0.000000    0.000000    1.000000    1.000000   
75%    324.000000    1.000000    1.000000    0.000000    1.000000    1.000000   
max    435.000000    3.000000    3.000000    3.000000    3.000000    3.000000   

               B6          B7          B8          B9  ...         B12  \
count  433.000000  433.000000  433.000000  433.000000  ...  433.000000   
mean     0.568129    0.503464    0.515012    0.163972  ...    0.665127   
std      0.847436    0.642342    0.684065    0.474727  ...    0.776452   
min      0.000000    0.000000    0.000000    0.000000  ...    0.000000   
25%      0.000000    0.000000    0.000000    0.000000  ...    0.000000   
50%      0.000000    0.000000    0.000000    0.000000  ...    1.000000   
75%      1.000000    1.000000    1.000000    0.000000  ...    1.000000   
max      3.000000    3.000000    3.000000    3.000000  ...    3.000000   

              B13         B14         B15         B16         B17         B18  \
count  433.000000  433.000000  433.000000  433.000000  433.000000  433.000000   
mean     0.579677    0.418014    0.528868    0.551963    0.732102    0.244804   
std      0.759966    0.655001    0.790407    0.731375    0.721566    0.577452   
min      0.000000    0.000000    0.000000    0.000000    0.000000    0.000000   
25%      0.000000    0.000000    0.000000    0.000000    0.000000    0.000000   
50%      0.000000    0.000000    0.000000    0.000000    1.000000    0.000000   
75%      1.000000    1.000000    1.000000    1.000000    1.000000    0.000000   
max      3.000000    3.000000    3.000000    3.000000    3.000000    3.000000   

              B19         B20         B21  
count  433.000000  433.000000  433.000000  
mean     0.224018    0.429561    0.475751  
std      0.625963    0.694058    0.742237  
min      0.000000    0.000000    0.000000  
25%      0.000000    0.000000    0.000000  
50%      0.000000    0.000000    0.000000  
75%      0.000000    1.000000    1.000000  
max      3.000000    3.000000    3.000000  

[8 rows x 22 columns]
```

</div>

</div>

<div class="cell markdown" id="PxoKXPM84WuS">

***Let's have a quick idea about columns.***

</div>

<div class="cell code" data-execution_count="189" data-colab="{&quot;base_uri&quot;:&quot;https://localhost:8080/&quot;}" id="NoB9fA_9ntxh" data-outputId="1f98da28-3480-4926-ca89-193d2bd75e1a">

``` python
df.info()
```

<div class="output stream stdout">

    <class 'pandas.core.frame.DataFrame'>
    RangeIndex: 433 entries, 0 to 432
    Data columns (total 27 columns):
     #   Column                    Non-Null Count  Dtype 
    ---  ------                    --------------  ----- 
     0   No                        433 non-null    int64 
     1   Gender                    433 non-null    object
     2   Education                 433 non-null    object
     3   Working Status            433 non-null    object
     4   Marriage Style            433 non-null    object
     5   Status of Having a Child  433 non-null    object
     6   B1                        433 non-null    int64 
     7   B2                        433 non-null    int64 
     8   B3                        433 non-null    int64 
     9   B4                        433 non-null    int64 
     10  B5                        433 non-null    int64 
     11  B6                        433 non-null    int64 
     12  B7                        433 non-null    int64 
     13  B8                        433 non-null    int64 
     14  B9                        433 non-null    int64 
     15  B10                       433 non-null    int64 
     16  B11                       433 non-null    int64 
     17  B12                       433 non-null    int64 
     18  B13                       433 non-null    int64 
     19  B14                       433 non-null    int64 
     20  B15                       433 non-null    int64 
     21  B16                       433 non-null    int64 
     22  B17                       433 non-null    int64 
     23  B18                       433 non-null    int64 
     24  B19                       433 non-null    int64 
     25  B20                       433 non-null    int64 
     26  B21                       433 non-null    int64 
    dtypes: int64(22), object(5)
    memory usage: 91.5+ KB

</div>

</div>

<div class="cell markdown" id="8VGCSDnrrnkR">

## Calculating sum of all BDI columns

for finding BDI Score

</div>

<div class="cell markdown" id="lKpLoWJ_4osI">

***As mentioned above, the BDI score is obtained from the sum of all
Bn-type columns. Now let's create a new column and add a dataframe by
collecting them.***

</div>

<div class="cell code" data-execution_count="190" id="Hi_nwT2GxEmm">

``` python
def bdi(df):
    finalBDIScore = []
    for i in df:
        finalBDIScore.append(i.sum())
    return np.array(finalBDIScore)
```

</div>

<div class="cell code" data-execution_count="191" id="lE5y_tDixQqY">

``` python
df['BDI Score'] = bdi(df.drop(labels = 'No\tGender\tEducation	Working Status	Marriage Style	Status of Having a Child'.split("\t"),axis = 1).values)
```

</div>

<div class="cell code" data-execution_count="192" data-colab="{&quot;height&quot;:235,&quot;base_uri&quot;:&quot;https://localhost:8080/&quot;}" id="MtfwklaXxXBm" data-outputId="d6e72635-4c3c-4f77-9d22-a66ca809fbd2">

``` python
df.head()
```

<div class="output execute_result" data-execution_count="192">

``` 
    No Gender   Education Working Status     Marriage Style  \
0  345   Male  Msc or PhD     Unemployed     Flirt Marriage   
1   73   Male    Bachelor     Unemployed     Flirt Marriage   
2  107   Male  Msc or PhD     Unemployed     Flirt Marriage   
3  131   Male  Msc or PhD     Unemployed     Flirt Marriage   
4    4   Male  Msc or PhD     Unemployed  Arranged Marriage   

  Status of Having a Child  B1  B2  B3  B4  ...  B13  B14  B15  B16  B17  B18  \
0                       No   3   3   3   3  ...    3    3    3    3    3    3   
1                      Yes   1   1   1   1  ...    0    1    1    0    1    0   
2                      Yes   0   0   0   1  ...    0    1    0    0    1    0   
3                      Yes   0   1   0   1  ...    0    0    0    3    0    0   
4                      Yes   0   0   0   0  ...    0    0    0    0    0    0   

   B19  B20  B21  BDI Score  
0    3    3    3         61  
1    0    0    0         12  
2    0    0    1          8  
3    0    0    0          6  
4    0    0    0          1  

[5 rows x 28 columns]
```

</div>

</div>

<div class="cell markdown" id="r2pKOpy65FmJ">

***Columns of type Bn no longer have any meaning for us and we can
delete them.***

</div>

<div class="cell code" data-execution_count="193" data-colab="{&quot;height&quot;:442,&quot;base_uri&quot;:&quot;https://localhost:8080/&quot;}" id="ujPzNbvU1phh" data-outputId="43e9cca4-dfa8-4b85-d59f-af467f21d36f">

``` python
droplist = []
for i in range(21):
  droplist.append(f"B{i+1}")
print(droplist)
df.drop(columns=droplist)
```

<div class="output stream stdout">

    ['B1', 'B2', 'B3', 'B4', 'B5', 'B6', 'B7', 'B8', 'B9', 'B10', 'B11', 'B12', 'B13', 'B14', 'B15', 'B16', 'B17', 'B18', 'B19', 'B20', 'B21']

</div>

<div class="output execute_result" data-execution_count="193">

``` 
      No  Gender    Education Working Status     Marriage Style  \
0    345    Male   Msc or PhD     Unemployed     Flirt Marriage   
1     73    Male     Bachelor     Unemployed     Flirt Marriage   
2    107    Male   Msc or PhD     Unemployed     Flirt Marriage   
3    131    Male   Msc or PhD     Unemployed     Flirt Marriage   
4      4    Male   Msc or PhD     Unemployed  Arranged Marriage   
..   ...     ...          ...            ...                ...   
428  401  Female  High School       Employed  Arranged Marriage   
429  244  Female  High School       Employed  Arranged Marriage   
430  333  Female      Primary       Employed  Arranged Marriage   
431  350  Female     Bachelor       Employed     Flirt Marriage   
432  225  Female      Primary       Employed     Flirt Marriage   

    Status of Having a Child  BDI Score  
0                         No         61  
1                        Yes         12  
2                        Yes          8  
3                        Yes          6  
4                        Yes          1  
..                       ...        ...  
428                      Yes          0  
429                      Yes         10  
430                      Yes         12  
431                      Yes          2  
432                      Yes          0  

[433 rows x 7 columns]
```

</div>

</div>

<div class="cell markdown" id="nw7BjnGKryjV">

## Explarotary Data Analysis

</div>

<div class="cell code" data-execution_count="194" data-colab="{&quot;height&quot;:381,&quot;base_uri&quot;:&quot;https://localhost:8080/&quot;}" id="O8WV9V7ftTn7" data-outputId="e89dc405-8385-4e82-87bc-d63441e0170d">

``` python
sns.catplot(x = 'Gender', y = 'BDI Score',data = df, 
            palette="Blues").set(title="BDI Score by Genders");
```

<div class="output display_data">

![](d2cc5cab36256fd4d721cab8b44335f7e39f2952.png)

</div>

</div>

<div class="cell markdown" id="mvtCNaXC5W9a">

***We see that women have a higher average rate of marital depression
than men.***

</div>

<div class="cell code" data-execution_count="195" data-colab="{&quot;height&quot;:301,&quot;base_uri&quot;:&quot;https://localhost:8080/&quot;}" id="vPj4P_RQuVeV" data-outputId="04ec0b0c-adb4-44c5-a4ae-2b0cc756bc28">

``` python
sns.set_theme(style="whitegrid")
sns.barplot(x="Working Status", y="BDI Score", data=df, 
            palette="Blues").set(title="Working Status and BDI Score");
```

<div class="output display_data">

![](edb93a7a856c6e31326b08506572250159e76b3c.png)

</div>

</div>

<div class="cell markdown" id="Qv5TWXmt5oeQ">

***It is clear that unemployed people experience less marital depression
than employed people.***

</div>

<div class="cell code" data-execution_count="196" data-colab="{&quot;height&quot;:410,&quot;base_uri&quot;:&quot;https://localhost:8080/&quot;}" id="Rjpaks8751vD" data-outputId="2b7aacef-b238-4b5e-c821-a4bcf0f56456">

``` python
plt.figure(figsize=(10,6))
bxp = sns.boxplot(y = 'Education', x = 'BDI Score',data = df, 
                  palette="Blues").set(title="Education Level and BDI Score");
```

<div class="output display_data">

![](61bbe46115bc0e19088e66b9bd4bf0e412414842.png)

</div>

</div>

<div class="cell markdown" id="yL-VjXEy55oZ">

***Increasing people's level of education leads to psychologically
healthier family life. In short, education brings peace.***

</div>

<div class="cell code" data-execution_count="197" data-colab="{&quot;height&quot;:301,&quot;base_uri&quot;:&quot;https://localhost:8080/&quot;}" id="vM39E_Xl6F96" data-outputId="d612d864-b5d5-4730-effd-f1dc0642b5c7">

``` python
sns.barplot(x="BDI Score", y="Status of Having a Child", data=df, 
            palette="Blues").set(title="Status of having a child and BDI Score");
```

<div class="output display_data">

![](4b447122359ac464abb0284d82dfee6729b11b37.png)

</div>

</div>

<div class="cell markdown" id="l2lmMRlm6RmZ">

***Individuals in families with children experience less marital
depression on average. We will examine this topic separately for genders
in the future***

</div>

<div class="cell code" data-execution_count="198" data-colab="{&quot;height&quot;:301,&quot;base_uri&quot;:&quot;https://localhost:8080/&quot;}" id="CBtn8mrb69AZ" data-outputId="9d099822-ba86-48d2-d750-81d54ba41acf">

``` python
sns.barplot(x = "Marriage Style", y = "BDI Score", data = df, 
            palette = "Blues").set(title="Marriage Style and BDI Score");
```

<div class="output display_data">

![](7c06594f7b708b87ee876457402a8a4b74cedd08.png)

</div>

</div>

<div class="cell markdown" id="6JvS_qSA6xC5">

***Marital style may not appear to affect marital depression at first
glance, but when we examine it, we will see both negative and positive
effects of this topic depending on gender.***

</div>

<div class="cell markdown" id="vo2HtiAhadJl">

## Explarotary Data Analysis by Gender

</div>

<div class="cell code" data-execution_count="199" data-colab="{&quot;height&quot;:284,&quot;base_uri&quot;:&quot;https://localhost:8080/&quot;}" id="X0cDxlIaaoY6" data-outputId="02ab10c2-b92f-42a6-8636-641fd3c15419">

``` python
male = df.where(df['Gender'] == "Male").groupby(by = "Working Status").mean()
male = male['BDI Score']
male = np.array(male)
plt.bar(['Employed', 'Unemployed'], male,  color=("Blue", "Red"))
plt.title("BDI Score and Working Status for Males")
plt.show()
```

<div class="output display_data">

![](55290c80fea09cc6cb910d7df66c10a505b1a891.png)

</div>

</div>

<div class="cell code" data-execution_count="200" data-colab="{&quot;height&quot;:284,&quot;base_uri&quot;:&quot;https://localhost:8080/&quot;}" id="civ07PyHbYBL" data-outputId="fcf759ef-53c5-4085-854d-2fda029f3235">

``` python
female = df.where(df['Gender'] == "Female").groupby(by= "Working Status").mean()
female = female['BDI Score']
female = np.array(female)
plt.title("BDI Score and Working Status for Females")
plt.bar(['Employed', 'Unemployed'], female, color=("Blue", "Red"))
plt.show()
```

<div class="output display_data">

![](66350c27c6a88a9c52542edc8a72f3d2e59c0f96.png)

</div>

</div>

<div class="cell markdown" id="NWd4J7V87ZsB">

***It is clear that unemployed people experience less marital depression
than employed people. And it is not depend on any gender***

</div>

<div class="cell code" data-execution_count="201" data-colab="{&quot;height&quot;:284,&quot;base_uri&quot;:&quot;https://localhost:8080/&quot;}" id="3zj7xlIGgBEw" data-outputId="513608e7-ef06-4e43-f6f4-87c6a5b4e72f">

``` python
male = df.where(df['Gender'] == "Male").groupby(by = "Marriage Style").mean()
male = male['BDI Score']
male = np.array(male)
plt.title("BDI Score and Marriage Style for Females")
plt.bar(['Arranged Marriage', 'Flirt Marriage'], male, color=("Blue", "Pink"))
plt.show()
```

<div class="output display_data">

![](2c068d25ccc7a2fa4d59219ed06f4ea2ecf7587f.png)

</div>

</div>

<div class="cell code" data-execution_count="202" data-colab="{&quot;height&quot;:284,&quot;base_uri&quot;:&quot;https://localhost:8080/&quot;}" id="npSf8THHgTMx" data-outputId="18b4c854-c963-4d01-f97e-ce403da6d07b">

``` python
female = df.where(df['Gender'] == "Male").groupby(by = "Marriage Style").mean()
female = female['BDI Score']
female = np.array(female)
plt.title("BDI Score and Marriage Style for Females")
plt.bar(['Arranged Marriage', 'Flirt Marriage'], female, color=("Blue", "Pink"))
plt.show()
```

<div class="output display_data">

![](2c068d25ccc7a2fa4d59219ed06f4ea2ecf7587f.png)

</div>

</div>

<div class="cell markdown" id="4_h3n1jI7y6g">

***Average depression threshold is higher in arranged marriages, but
relatively lower in flirtatious marriages.***

</div>

<div class="cell code" data-execution_count="203" data-colab="{&quot;height&quot;:525,&quot;base_uri&quot;:&quot;https://localhost:8080/&quot;}" id="VrNxWwjSghyS" data-outputId="9eed761c-4ad3-4808-80f7-0ee66c675b24">

``` python
sns.catplot(x="Gender", y="BDI Score",
                hue="Education",
                data=df, kind="box",
                palette = "Blues", 
                height=7, aspect=.7).set(title='Education and BDI Score by Genders');
```

<div class="output display_data">

![](972bd6853a4c8913d5f2ce4e7d6129dd779e3d42.png)

</div>

</div>

<div class="cell markdown" id="5oHParib8KeJ">

***Education has a positive effect on both sexes, but in women, the
average level of marital depression decreases with the increase in the
level of education.***

</div>

<div class="cell code" data-execution_count="204" data-colab="{&quot;height&quot;:525,&quot;base_uri&quot;:&quot;https://localhost:8080/&quot;}" id="s_9JhABfjmJQ" data-outputId="fa950f1c-059a-4539-95b5-6381aee6cbb7">

``` python
sns.catplot(x="Gender", y="BDI Score",
                hue="Status of Having a Child",
                data=df, kind="bar",
                height=7, palette="Blues",
                aspect=.8).set(title="Status of Having Childrens and BDI Score by Genders");
```

<div class="output display_data">

![](41dac14b3e21ea6507f628ca93cb2f6d42f7a46c.png)

</div>

</div>

<div class="cell markdown" id="24lVLZwO8kRp">

***Towards the end, we make an interesting discovery :) So, although the
presence of children at home does not affect men as much, the feeling of
being a mother causes a decrease in the level of depression in women.
Simply put, children heal their mothers.***

</div>
