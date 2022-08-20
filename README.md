# Depression-in-Married-Couples-in-Istanbul
---
jupyter:
  colab:
    name: Depression in Married Couples in Ä°stanbul.ipynb
  kernelspec:
    display_name: Python 3
    name: python3
  language_info:
    name: python
  nbformat: 4
  nbformat_minor: 0
---

::: {.cell .markdown id="ICjFq0o8kEgo"}
```{=html}
<p style="text-align: center;"><strong><h1>ABOUT DATA</h1></strong></p>
```
```{=html}
<p>The data has been collected in Ä°stanbul via an online form. It is aimed to examine the depression scores of married people and the influence of demographic factors.<br>Demographic Questions and Beck Depression Inventory is used to collect data. Total Score of Scale must be calculated by the sum of items B1-B21. Codes reflecting the categories of demographic questions are as below.</p>
```
```{=html}
<p><br>Gender: 1-Female, 2-Male;&nbsp;</p>
```
```{=html}
<p>Education: 1-Primary, 2-High School, 3-Bachelor, 4-Msc or PhD;&nbsp;</p>
```
```{=html}
<p>Working Status: 1-Employed, 2-Unemployed;&nbsp;</p>
```
```{=html}
<p>Marriage Style : 1-Arranged Marriage, 2-Flirt Marriage;&nbsp;</p>
```
```{=html}
<p>Status of Having a Child: 1-Yes, 2-No&nbsp;</p>
```
:::

::: {.cell .markdown id="w1N1QjWkk9Zf"}
`<strong>`{=html}`<h1>`{=html}Beck\'s Depression
Inventory`<a href="https://www.kaggle.com/code/ayushmehar7/marital-depression-analysis#Beck's-Depression-Inventory" target="_self" rel=" noreferrer nofollow">`{=html}`</a>`{=html}`</h1>`{=html}`</strong>`{=html}
`<p>`{=html}The Beck Depression Inventory (BDI), created by Aaron T.
Beck, is a 21-question multiple-choice self-report inventory, one of the
most widely used psychometric tests for measuring the severity of
depression. Its development marked a shift among mental health
professionals, who had until then, viewed depression from a
psychodynamic perspective, instead of it being rooted in the patient\'s
own thoughts.`</p>`{=html} `<p>`{=html}Each of the 21 questions are 4
optioned questions having score from 0 to 3. Minimum score being 0 and
maximum being 63.The degree of depression is directly proportional to
the BDI score`</p>`{=html} `<p>`{=html}Some of the questions are
:`</p>`{=html} `<ol>`{=html} `<li>`{=html}`<br>`{=html} `<ul>`{=html}
`<li>`{=html}0 I do not feel sad`</li>`{=html} `<li>`{=html}1 I feel
sad`</li>`{=html} `<li>`{=html}2 I am sad all the time and I can\'t snap
out of it.`</li>`{=html} `<li>`{=html}3 I am so sad and unhappy that I
can\'t stand it.`</li>`{=html} `</ul>`{=html} `</li>`{=html}
`<li>`{=html}`<br>`{=html} `<ul>`{=html} `<li>`{=html}0 I am not
particularly discouraged about the future.`</li>`{=html} `<li>`{=html}1
I feel discouraged about the future.`</li>`{=html} `<li>`{=html}2 I feel
I have nothing to look forward to.`</li>`{=html} `<li>`{=html}3 I feel
the future is hopeless and that things cannot improve.`</li>`{=html}
`</ul>`{=html} `</li>`{=html} `</ol>`{=html} `<p>`{=html}For more
details on the
questionsÂ `<a href="https://www.ismanet.org/doctoryourspirit/pdfs/Beck-Depression-Inventory-BDI.pdf" rel=" noreferrer nofollow">`{=html}visit
here`</a>`{=html}`</p>`{=html} `<h2>`{=html}BDI
Score`<a href="https://www.kaggle.com/code/ayushmehar7/marital-depression-analysis#BDI-Score" target="_self" rel=" noreferrer nofollow">`{=html}`</a>`{=html}`</h2>`{=html}
`<p>`{=html}Based on the BDI score, the patient is categorised as
follows :`</p>`{=html} `<ul>`{=html} `<li>`{=html}Below 10 : These ups
and downs are considered normal`</li>`{=html} `<li>`{=html}11-16 : Mild
mood disturbance`</li>`{=html} `<li>`{=html}17-20 : Borderline clinical
depression`</li>`{=html} `<li>`{=html}21-30 : Moderate
depression`</li>`{=html} `<li>`{=html}31-40 : Severe
depression`</li>`{=html} `<li>`{=html}Over 40 : Extreme
depression`</li>`{=html} `</ul>`{=html}
:::

::: {.cell .markdown id="NFw-3tsFtbPm"}
## Importing Required Packages
:::

::: {.cell .code execution_count="174" id="uGoARAk7MhKH"}
``` {.python}
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```
:::

::: {.cell .markdown id="pqke83T3tg31"}
## Loading Data
:::

::: {.cell .code execution_count="175" colab="{\"height\":235,\"base_uri\":\"https://localhost:8080/\"}" id="UXBFHZ9gNP5W" outputId="a2760387-17c6-4ee3-b420-5161f54109fe"}
``` {.python}
df = pd.read_csv('Dataset 1.csv')
df.head()
```

::: {.output .execute_result execution_count="175"}
```{=html}
  <div id="df-39fb6db0-0027-48d7-bb7a-ea33c57b6b02">
    <div class="colab-df-container">
      <div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>No</th>
      <th>Gender</th>
      <th>Education</th>
      <th>Working Status</th>
      <th>Marriage Style</th>
      <th>Status of Having a Child</th>
      <th>B1</th>
      <th>B2</th>
      <th>B3</th>
      <th>B4</th>
      <th>...</th>
      <th>B12</th>
      <th>B13</th>
      <th>B14</th>
      <th>B15</th>
      <th>B16</th>
      <th>B17</th>
      <th>B18</th>
      <th>B19</th>
      <th>B20</th>
      <th>B21</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>345</td>
      <td>2</td>
      <td>4</td>
      <td>2</td>
      <td>2</td>
      <td>2</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>...</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
    </tr>
    <tr>
      <th>1</th>
      <td>73</td>
      <td>2</td>
      <td>3</td>
      <td>2</td>
      <td>2</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>...</td>
      <td>1</td>
      <td>0</td>
      <td>1</td>
      <td>1</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>2</th>
      <td>107</td>
      <td>2</td>
      <td>4</td>
      <td>2</td>
      <td>2</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>1</td>
      <td>...</td>
      <td>1</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>1</td>
    </tr>
    <tr>
      <th>3</th>
      <td>131</td>
      <td>2</td>
      <td>4</td>
      <td>2</td>
      <td>2</td>
      <td>1</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>1</td>
      <td>...</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>3</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>4</th>
      <td>4</td>
      <td>2</td>
      <td>4</td>
      <td>2</td>
      <td>1</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>...</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
  </tbody>
</table>
<p>5 rows Ã— 27 columns</p>
</div>
      <button class="colab-df-convert" onclick="convertToInteractive('df-39fb6db0-0027-48d7-bb7a-ea33c57b6b02')"
              title="Convert this dataframe to an interactive table."
              style="display:none;">
        
  <svg xmlns="http://www.w3.org/2000/svg" height="24px"viewBox="0 0 24 24"
       width="24px">
    <path d="M0 0h24v24H0V0z" fill="none"/>
    <path d="M18.56 5.44l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94zm-11 1L8.5 8.5l.94-2.06 2.06-.94-2.06-.94L8.5 2.5l-.94 2.06-2.06.94zm10 10l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94z"/><path d="M17.41 7.96l-1.37-1.37c-.4-.4-.92-.59-1.43-.59-.52 0-1.04.2-1.43.59L10.3 9.45l-7.72 7.72c-.78.78-.78 2.05 0 2.83L4 21.41c.39.39.9.59 1.41.59.51 0 1.02-.2 1.41-.59l7.78-7.78 2.81-2.81c.8-.78.8-2.07 0-2.86zM5.41 20L4 18.59l7.72-7.72 1.47 1.35L5.41 20z"/>
  </svg>
      </button>
      
  <style>
    .colab-df-container {
      display:flex;
      flex-wrap:wrap;
      gap: 12px;
    }

    .colab-df-convert {
      background-color: #E8F0FE;
      border: none;
      border-radius: 50%;
      cursor: pointer;
      display: none;
      fill: #1967D2;
      height: 32px;
      padding: 0 0 0 0;
      width: 32px;
    }

    .colab-df-convert:hover {
      background-color: #E2EBFA;
      box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
      fill: #174EA6;
    }

    [theme=dark] .colab-df-convert {
      background-color: #3B4455;
      fill: #D2E3FC;
    }

    [theme=dark] .colab-df-convert:hover {
      background-color: #434B5C;
      box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
      filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
      fill: #FFFFFF;
    }
  </style>

      <script>
        const buttonEl =
          document.querySelector('#df-39fb6db0-0027-48d7-bb7a-ea33c57b6b02 button.colab-df-convert');
        buttonEl.style.display =
          google.colab.kernel.accessAllowed ? 'block' : 'none';

        async function convertToInteractive(key) {
          const element = document.querySelector('#df-39fb6db0-0027-48d7-bb7a-ea33c57b6b02');
          const dataTable =
            await google.colab.kernel.invokeFunction('convertToInteractive',
                                                     [key], {});
          if (!dataTable) return;

          const docLinkHtml = 'Like what you see? Visit the ' +
            '<a target="_blank" href=https://colab.research.google.com/notebooks/data_table.ipynb>data table notebook</a>'
            + ' to learn more about interactive tables.';
          element.innerHTML = '';
          dataTable['output_type'] = 'display_data';
          await google.colab.output.renderOutput(dataTable, element);
          const docLink = document.createElement('div');
          docLink.innerHTML = docLinkHtml;
          element.appendChild(docLink);
        }
      </script>
    </div>
  </div>
  
```
:::
:::

::: {.cell .markdown id="KIEfYk3Ctjjd"}
## Data Manipulation
:::

::: {.cell .markdown id="XDExo6TO2bvY"}
***We\'ll need to make some small changes to make better visualizations,
make working with the data easier, and make the data more meaningful.***
:::

::: {.cell .code execution_count="176" id="E5l5jGyGOHVy"}
``` {.python}
df['Gender'] = df['Gender'].replace(1, 'Female')
df['Gender'] = df['Gender'].replace(2, 'Male')
```
:::

::: {.cell .code execution_count="177" colab="{\"height\":235,\"base_uri\":\"https://localhost:8080/\"}" id="jluetl7pO-ts" outputId="e2593fd6-405e-45d9-8e6a-dc4b19dfe348"}
``` {.python}
df.head()
```

::: {.output .execute_result execution_count="177"}
```{=html}
  <div id="df-443d270d-7dad-4d15-9c0a-08ddaee66c93">
    <div class="colab-df-container">
      <div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>No</th>
      <th>Gender</th>
      <th>Education</th>
      <th>Working Status</th>
      <th>Marriage Style</th>
      <th>Status of Having a Child</th>
      <th>B1</th>
      <th>B2</th>
      <th>B3</th>
      <th>B4</th>
      <th>...</th>
      <th>B12</th>
      <th>B13</th>
      <th>B14</th>
      <th>B15</th>
      <th>B16</th>
      <th>B17</th>
      <th>B18</th>
      <th>B19</th>
      <th>B20</th>
      <th>B21</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>345</td>
      <td>Male</td>
      <td>4</td>
      <td>2</td>
      <td>2</td>
      <td>2</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>...</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
    </tr>
    <tr>
      <th>1</th>
      <td>73</td>
      <td>Male</td>
      <td>3</td>
      <td>2</td>
      <td>2</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>...</td>
      <td>1</td>
      <td>0</td>
      <td>1</td>
      <td>1</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>2</th>
      <td>107</td>
      <td>Male</td>
      <td>4</td>
      <td>2</td>
      <td>2</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>1</td>
      <td>...</td>
      <td>1</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>1</td>
    </tr>
    <tr>
      <th>3</th>
      <td>131</td>
      <td>Male</td>
      <td>4</td>
      <td>2</td>
      <td>2</td>
      <td>1</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>1</td>
      <td>...</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>3</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>4</th>
      <td>4</td>
      <td>Male</td>
      <td>4</td>
      <td>2</td>
      <td>1</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>...</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
  </tbody>
</table>
<p>5 rows Ã— 27 columns</p>
</div>
      <button class="colab-df-convert" onclick="convertToInteractive('df-443d270d-7dad-4d15-9c0a-08ddaee66c93')"
              title="Convert this dataframe to an interactive table."
              style="display:none;">
        
  <svg xmlns="http://www.w3.org/2000/svg" height="24px"viewBox="0 0 24 24"
       width="24px">
    <path d="M0 0h24v24H0V0z" fill="none"/>
    <path d="M18.56 5.44l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94zm-11 1L8.5 8.5l.94-2.06 2.06-.94-2.06-.94L8.5 2.5l-.94 2.06-2.06.94zm10 10l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94z"/><path d="M17.41 7.96l-1.37-1.37c-.4-.4-.92-.59-1.43-.59-.52 0-1.04.2-1.43.59L10.3 9.45l-7.72 7.72c-.78.78-.78 2.05 0 2.83L4 21.41c.39.39.9.59 1.41.59.51 0 1.02-.2 1.41-.59l7.78-7.78 2.81-2.81c.8-.78.8-2.07 0-2.86zM5.41 20L4 18.59l7.72-7.72 1.47 1.35L5.41 20z"/>
  </svg>
      </button>
      
  <style>
    .colab-df-container {
      display:flex;
      flex-wrap:wrap;
      gap: 12px;
    }

    .colab-df-convert {
      background-color: #E8F0FE;
      border: none;
      border-radius: 50%;
      cursor: pointer;
      display: none;
      fill: #1967D2;
      height: 32px;
      padding: 0 0 0 0;
      width: 32px;
    }

    .colab-df-convert:hover {
      background-color: #E2EBFA;
      box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
      fill: #174EA6;
    }

    [theme=dark] .colab-df-convert {
      background-color: #3B4455;
      fill: #D2E3FC;
    }

    [theme=dark] .colab-df-convert:hover {
      background-color: #434B5C;
      box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
      filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
      fill: #FFFFFF;
    }
  </style>

      <script>
        const buttonEl =
          document.querySelector('#df-443d270d-7dad-4d15-9c0a-08ddaee66c93 button.colab-df-convert');
        buttonEl.style.display =
          google.colab.kernel.accessAllowed ? 'block' : 'none';

        async function convertToInteractive(key) {
          const element = document.querySelector('#df-443d270d-7dad-4d15-9c0a-08ddaee66c93');
          const dataTable =
            await google.colab.kernel.invokeFunction('convertToInteractive',
                                                     [key], {});
          if (!dataTable) return;

          const docLinkHtml = 'Like what you see? Visit the ' +
            '<a target="_blank" href=https://colab.research.google.com/notebooks/data_table.ipynb>data table notebook</a>'
            + ' to learn more about interactive tables.';
          element.innerHTML = '';
          dataTable['output_type'] = 'display_data';
          await google.colab.output.renderOutput(dataTable, element);
          const docLink = document.createElement('div');
          docLink.innerHTML = docLinkHtml;
          element.appendChild(docLink);
        }
      </script>
    </div>
  </div>
  
```
:::
:::

::: {.cell .code execution_count="178" id="xIJtS4jVPMTO"}
``` {.python}
df['Education'] = df['Education'].replace(1, 'Primary')
df['Education'] = df['Education'].replace(2, 'High School')
df['Education'] = df['Education'].replace(3, 'Bachelor')
df['Education'] = df['Education'].replace(4, 'Msc or PhD')
```
:::

::: {.cell .code execution_count="179" colab="{\"height\":235,\"base_uri\":\"https://localhost:8080/\"}" id="ZU5nEbaNPuuf" outputId="ad8ca2f8-5623-44ce-97e3-46f5b0597623"}
``` {.python}
df.head()
```

::: {.output .execute_result execution_count="179"}
```{=html}
  <div id="df-4c9c1b2c-5960-4857-bd3b-7d72690598fe">
    <div class="colab-df-container">
      <div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>No</th>
      <th>Gender</th>
      <th>Education</th>
      <th>Working Status</th>
      <th>Marriage Style</th>
      <th>Status of Having a Child</th>
      <th>B1</th>
      <th>B2</th>
      <th>B3</th>
      <th>B4</th>
      <th>...</th>
      <th>B12</th>
      <th>B13</th>
      <th>B14</th>
      <th>B15</th>
      <th>B16</th>
      <th>B17</th>
      <th>B18</th>
      <th>B19</th>
      <th>B20</th>
      <th>B21</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>345</td>
      <td>Male</td>
      <td>Msc or PhD</td>
      <td>2</td>
      <td>2</td>
      <td>2</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>...</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
    </tr>
    <tr>
      <th>1</th>
      <td>73</td>
      <td>Male</td>
      <td>Bachelor</td>
      <td>2</td>
      <td>2</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>...</td>
      <td>1</td>
      <td>0</td>
      <td>1</td>
      <td>1</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>2</th>
      <td>107</td>
      <td>Male</td>
      <td>Msc or PhD</td>
      <td>2</td>
      <td>2</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>1</td>
      <td>...</td>
      <td>1</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>1</td>
    </tr>
    <tr>
      <th>3</th>
      <td>131</td>
      <td>Male</td>
      <td>Msc or PhD</td>
      <td>2</td>
      <td>2</td>
      <td>1</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>1</td>
      <td>...</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>3</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>4</th>
      <td>4</td>
      <td>Male</td>
      <td>Msc or PhD</td>
      <td>2</td>
      <td>1</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>...</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
  </tbody>
</table>
<p>5 rows Ã— 27 columns</p>
</div>
      <button class="colab-df-convert" onclick="convertToInteractive('df-4c9c1b2c-5960-4857-bd3b-7d72690598fe')"
              title="Convert this dataframe to an interactive table."
              style="display:none;">
        
  <svg xmlns="http://www.w3.org/2000/svg" height="24px"viewBox="0 0 24 24"
       width="24px">
    <path d="M0 0h24v24H0V0z" fill="none"/>
    <path d="M18.56 5.44l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94zm-11 1L8.5 8.5l.94-2.06 2.06-.94-2.06-.94L8.5 2.5l-.94 2.06-2.06.94zm10 10l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94z"/><path d="M17.41 7.96l-1.37-1.37c-.4-.4-.92-.59-1.43-.59-.52 0-1.04.2-1.43.59L10.3 9.45l-7.72 7.72c-.78.78-.78 2.05 0 2.83L4 21.41c.39.39.9.59 1.41.59.51 0 1.02-.2 1.41-.59l7.78-7.78 2.81-2.81c.8-.78.8-2.07 0-2.86zM5.41 20L4 18.59l7.72-7.72 1.47 1.35L5.41 20z"/>
  </svg>
      </button>
      
  <style>
    .colab-df-container {
      display:flex;
      flex-wrap:wrap;
      gap: 12px;
    }

    .colab-df-convert {
      background-color: #E8F0FE;
      border: none;
      border-radius: 50%;
      cursor: pointer;
      display: none;
      fill: #1967D2;
      height: 32px;
      padding: 0 0 0 0;
      width: 32px;
    }

    .colab-df-convert:hover {
      background-color: #E2EBFA;
      box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
      fill: #174EA6;
    }

    [theme=dark] .colab-df-convert {
      background-color: #3B4455;
      fill: #D2E3FC;
    }

    [theme=dark] .colab-df-convert:hover {
      background-color: #434B5C;
      box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
      filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
      fill: #FFFFFF;
    }
  </style>

      <script>
        const buttonEl =
          document.querySelector('#df-4c9c1b2c-5960-4857-bd3b-7d72690598fe button.colab-df-convert');
        buttonEl.style.display =
          google.colab.kernel.accessAllowed ? 'block' : 'none';

        async function convertToInteractive(key) {
          const element = document.querySelector('#df-4c9c1b2c-5960-4857-bd3b-7d72690598fe');
          const dataTable =
            await google.colab.kernel.invokeFunction('convertToInteractive',
                                                     [key], {});
          if (!dataTable) return;

          const docLinkHtml = 'Like what you see? Visit the ' +
            '<a target="_blank" href=https://colab.research.google.com/notebooks/data_table.ipynb>data table notebook</a>'
            + ' to learn more about interactive tables.';
          element.innerHTML = '';
          dataTable['output_type'] = 'display_data';
          await google.colab.output.renderOutput(dataTable, element);
          const docLink = document.createElement('div');
          docLink.innerHTML = docLinkHtml;
          element.appendChild(docLink);
        }
      </script>
    </div>
  </div>
  
```
:::
:::

::: {.cell .code execution_count="180" id="Gm6EdonMP1Q2"}
``` {.python}
df['Working Status'] = df['Working Status'].replace(1, 'Employed')
df['Working Status'] = df['Working Status'].replace(2, 'Unemployed')
```
:::

::: {.cell .code execution_count="181" colab="{\"height\":235,\"base_uri\":\"https://localhost:8080/\"}" id="HdlQE-hmQGkt" outputId="809d17c8-2f9a-4e71-b198-86cf5381fe8f"}
``` {.python}
df.head()
```

::: {.output .execute_result execution_count="181"}
```{=html}
  <div id="df-746e3425-a3d5-48cf-9784-07551376dad0">
    <div class="colab-df-container">
      <div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>No</th>
      <th>Gender</th>
      <th>Education</th>
      <th>Working Status</th>
      <th>Marriage Style</th>
      <th>Status of Having a Child</th>
      <th>B1</th>
      <th>B2</th>
      <th>B3</th>
      <th>B4</th>
      <th>...</th>
      <th>B12</th>
      <th>B13</th>
      <th>B14</th>
      <th>B15</th>
      <th>B16</th>
      <th>B17</th>
      <th>B18</th>
      <th>B19</th>
      <th>B20</th>
      <th>B21</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>345</td>
      <td>Male</td>
      <td>Msc or PhD</td>
      <td>Unemployed</td>
      <td>2</td>
      <td>2</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>...</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
    </tr>
    <tr>
      <th>1</th>
      <td>73</td>
      <td>Male</td>
      <td>Bachelor</td>
      <td>Unemployed</td>
      <td>2</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>...</td>
      <td>1</td>
      <td>0</td>
      <td>1</td>
      <td>1</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>2</th>
      <td>107</td>
      <td>Male</td>
      <td>Msc or PhD</td>
      <td>Unemployed</td>
      <td>2</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>1</td>
      <td>...</td>
      <td>1</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>1</td>
    </tr>
    <tr>
      <th>3</th>
      <td>131</td>
      <td>Male</td>
      <td>Msc or PhD</td>
      <td>Unemployed</td>
      <td>2</td>
      <td>1</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>1</td>
      <td>...</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>3</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>4</th>
      <td>4</td>
      <td>Male</td>
      <td>Msc or PhD</td>
      <td>Unemployed</td>
      <td>1</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>...</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
  </tbody>
</table>
<p>5 rows Ã— 27 columns</p>
</div>
      <button class="colab-df-convert" onclick="convertToInteractive('df-746e3425-a3d5-48cf-9784-07551376dad0')"
              title="Convert this dataframe to an interactive table."
              style="display:none;">
        
  <svg xmlns="http://www.w3.org/2000/svg" height="24px"viewBox="0 0 24 24"
       width="24px">
    <path d="M0 0h24v24H0V0z" fill="none"/>
    <path d="M18.56 5.44l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94zm-11 1L8.5 8.5l.94-2.06 2.06-.94-2.06-.94L8.5 2.5l-.94 2.06-2.06.94zm10 10l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94z"/><path d="M17.41 7.96l-1.37-1.37c-.4-.4-.92-.59-1.43-.59-.52 0-1.04.2-1.43.59L10.3 9.45l-7.72 7.72c-.78.78-.78 2.05 0 2.83L4 21.41c.39.39.9.59 1.41.59.51 0 1.02-.2 1.41-.59l7.78-7.78 2.81-2.81c.8-.78.8-2.07 0-2.86zM5.41 20L4 18.59l7.72-7.72 1.47 1.35L5.41 20z"/>
  </svg>
      </button>
      
  <style>
    .colab-df-container {
      display:flex;
      flex-wrap:wrap;
      gap: 12px;
    }

    .colab-df-convert {
      background-color: #E8F0FE;
      border: none;
      border-radius: 50%;
      cursor: pointer;
      display: none;
      fill: #1967D2;
      height: 32px;
      padding: 0 0 0 0;
      width: 32px;
    }

    .colab-df-convert:hover {
      background-color: #E2EBFA;
      box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
      fill: #174EA6;
    }

    [theme=dark] .colab-df-convert {
      background-color: #3B4455;
      fill: #D2E3FC;
    }

    [theme=dark] .colab-df-convert:hover {
      background-color: #434B5C;
      box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
      filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
      fill: #FFFFFF;
    }
  </style>

      <script>
        const buttonEl =
          document.querySelector('#df-746e3425-a3d5-48cf-9784-07551376dad0 button.colab-df-convert');
        buttonEl.style.display =
          google.colab.kernel.accessAllowed ? 'block' : 'none';

        async function convertToInteractive(key) {
          const element = document.querySelector('#df-746e3425-a3d5-48cf-9784-07551376dad0');
          const dataTable =
            await google.colab.kernel.invokeFunction('convertToInteractive',
                                                     [key], {});
          if (!dataTable) return;

          const docLinkHtml = 'Like what you see? Visit the ' +
            '<a target="_blank" href=https://colab.research.google.com/notebooks/data_table.ipynb>data table notebook</a>'
            + ' to learn more about interactive tables.';
          element.innerHTML = '';
          dataTable['output_type'] = 'display_data';
          await google.colab.output.renderOutput(dataTable, element);
          const docLink = document.createElement('div');
          docLink.innerHTML = docLinkHtml;
          element.appendChild(docLink);
        }
      </script>
    </div>
  </div>
  
```
:::
:::

::: {.cell .code execution_count="182" id="7SGobHLRQJZ-"}
``` {.python}
df['Marriage Style'] = df['Marriage Style'].replace(1, 'Arranged Marriage')
df['Marriage Style'] = df['Marriage Style'].replace(2, 'Flirt Marriage')
```
:::

::: {.cell .code execution_count="183" colab="{\"height\":235,\"base_uri\":\"https://localhost:8080/\"}" id="OvbqCqdRQi8A" outputId="8d058405-e2c7-4117-fa60-922bd6d39d1a"}
``` {.python}
df.head()
```

::: {.output .execute_result execution_count="183"}
```{=html}
  <div id="df-b3957f24-375c-4a28-8087-6097a8fc1fd1">
    <div class="colab-df-container">
      <div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>No</th>
      <th>Gender</th>
      <th>Education</th>
      <th>Working Status</th>
      <th>Marriage Style</th>
      <th>Status of Having a Child</th>
      <th>B1</th>
      <th>B2</th>
      <th>B3</th>
      <th>B4</th>
      <th>...</th>
      <th>B12</th>
      <th>B13</th>
      <th>B14</th>
      <th>B15</th>
      <th>B16</th>
      <th>B17</th>
      <th>B18</th>
      <th>B19</th>
      <th>B20</th>
      <th>B21</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>345</td>
      <td>Male</td>
      <td>Msc or PhD</td>
      <td>Unemployed</td>
      <td>Flirt Marriage</td>
      <td>2</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>...</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
    </tr>
    <tr>
      <th>1</th>
      <td>73</td>
      <td>Male</td>
      <td>Bachelor</td>
      <td>Unemployed</td>
      <td>Flirt Marriage</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>...</td>
      <td>1</td>
      <td>0</td>
      <td>1</td>
      <td>1</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>2</th>
      <td>107</td>
      <td>Male</td>
      <td>Msc or PhD</td>
      <td>Unemployed</td>
      <td>Flirt Marriage</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>1</td>
      <td>...</td>
      <td>1</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>1</td>
    </tr>
    <tr>
      <th>3</th>
      <td>131</td>
      <td>Male</td>
      <td>Msc or PhD</td>
      <td>Unemployed</td>
      <td>Flirt Marriage</td>
      <td>1</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>1</td>
      <td>...</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>3</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>4</th>
      <td>4</td>
      <td>Male</td>
      <td>Msc or PhD</td>
      <td>Unemployed</td>
      <td>Arranged Marriage</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>...</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
  </tbody>
</table>
<p>5 rows Ã— 27 columns</p>
</div>
      <button class="colab-df-convert" onclick="convertToInteractive('df-b3957f24-375c-4a28-8087-6097a8fc1fd1')"
              title="Convert this dataframe to an interactive table."
              style="display:none;">
        
  <svg xmlns="http://www.w3.org/2000/svg" height="24px"viewBox="0 0 24 24"
       width="24px">
    <path d="M0 0h24v24H0V0z" fill="none"/>
    <path d="M18.56 5.44l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94zm-11 1L8.5 8.5l.94-2.06 2.06-.94-2.06-.94L8.5 2.5l-.94 2.06-2.06.94zm10 10l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94z"/><path d="M17.41 7.96l-1.37-1.37c-.4-.4-.92-.59-1.43-.59-.52 0-1.04.2-1.43.59L10.3 9.45l-7.72 7.72c-.78.78-.78 2.05 0 2.83L4 21.41c.39.39.9.59 1.41.59.51 0 1.02-.2 1.41-.59l7.78-7.78 2.81-2.81c.8-.78.8-2.07 0-2.86zM5.41 20L4 18.59l7.72-7.72 1.47 1.35L5.41 20z"/>
  </svg>
      </button>
      
  <style>
    .colab-df-container {
      display:flex;
      flex-wrap:wrap;
      gap: 12px;
    }

    .colab-df-convert {
      background-color: #E8F0FE;
      border: none;
      border-radius: 50%;
      cursor: pointer;
      display: none;
      fill: #1967D2;
      height: 32px;
      padding: 0 0 0 0;
      width: 32px;
    }

    .colab-df-convert:hover {
      background-color: #E2EBFA;
      box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
      fill: #174EA6;
    }

    [theme=dark] .colab-df-convert {
      background-color: #3B4455;
      fill: #D2E3FC;
    }

    [theme=dark] .colab-df-convert:hover {
      background-color: #434B5C;
      box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
      filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
      fill: #FFFFFF;
    }
  </style>

      <script>
        const buttonEl =
          document.querySelector('#df-b3957f24-375c-4a28-8087-6097a8fc1fd1 button.colab-df-convert');
        buttonEl.style.display =
          google.colab.kernel.accessAllowed ? 'block' : 'none';

        async function convertToInteractive(key) {
          const element = document.querySelector('#df-b3957f24-375c-4a28-8087-6097a8fc1fd1');
          const dataTable =
            await google.colab.kernel.invokeFunction('convertToInteractive',
                                                     [key], {});
          if (!dataTable) return;

          const docLinkHtml = 'Like what you see? Visit the ' +
            '<a target="_blank" href=https://colab.research.google.com/notebooks/data_table.ipynb>data table notebook</a>'
            + ' to learn more about interactive tables.';
          element.innerHTML = '';
          dataTable['output_type'] = 'display_data';
          await google.colab.output.renderOutput(dataTable, element);
          const docLink = document.createElement('div');
          docLink.innerHTML = docLinkHtml;
          element.appendChild(docLink);
        }
      </script>
    </div>
  </div>
  
```
:::
:::

::: {.cell .code execution_count="184" colab="{\"height\":235,\"base_uri\":\"https://localhost:8080/\"}" id="WBIOrE6CQlSG" outputId="2e0c5ca0-0902-44e3-cb8d-60abacb134e9"}
``` {.python}
df['Status of Having a Child'] = df['Status of Having a Child'].replace(1, 'Yes')
df['Status of Having a Child'] = df['Status of Having a Child'].replace(2, 'No')
df.head()
```

::: {.output .execute_result execution_count="184"}
```{=html}
  <div id="df-7ab88c7f-a7bf-4c4d-9074-e4f34b69bf12">
    <div class="colab-df-container">
      <div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>No</th>
      <th>Gender</th>
      <th>Education</th>
      <th>Working Status</th>
      <th>Marriage Style</th>
      <th>Status of Having a Child</th>
      <th>B1</th>
      <th>B2</th>
      <th>B3</th>
      <th>B4</th>
      <th>...</th>
      <th>B12</th>
      <th>B13</th>
      <th>B14</th>
      <th>B15</th>
      <th>B16</th>
      <th>B17</th>
      <th>B18</th>
      <th>B19</th>
      <th>B20</th>
      <th>B21</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>345</td>
      <td>Male</td>
      <td>Msc or PhD</td>
      <td>Unemployed</td>
      <td>Flirt Marriage</td>
      <td>No</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>...</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
    </tr>
    <tr>
      <th>1</th>
      <td>73</td>
      <td>Male</td>
      <td>Bachelor</td>
      <td>Unemployed</td>
      <td>Flirt Marriage</td>
      <td>Yes</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>...</td>
      <td>1</td>
      <td>0</td>
      <td>1</td>
      <td>1</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>2</th>
      <td>107</td>
      <td>Male</td>
      <td>Msc or PhD</td>
      <td>Unemployed</td>
      <td>Flirt Marriage</td>
      <td>Yes</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>1</td>
      <td>...</td>
      <td>1</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>1</td>
    </tr>
    <tr>
      <th>3</th>
      <td>131</td>
      <td>Male</td>
      <td>Msc or PhD</td>
      <td>Unemployed</td>
      <td>Flirt Marriage</td>
      <td>Yes</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>1</td>
      <td>...</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>3</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>4</th>
      <td>4</td>
      <td>Male</td>
      <td>Msc or PhD</td>
      <td>Unemployed</td>
      <td>Arranged Marriage</td>
      <td>Yes</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>...</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
  </tbody>
</table>
<p>5 rows Ã— 27 columns</p>
</div>
      <button class="colab-df-convert" onclick="convertToInteractive('df-7ab88c7f-a7bf-4c4d-9074-e4f34b69bf12')"
              title="Convert this dataframe to an interactive table."
              style="display:none;">
        
  <svg xmlns="http://www.w3.org/2000/svg" height="24px"viewBox="0 0 24 24"
       width="24px">
    <path d="M0 0h24v24H0V0z" fill="none"/>
    <path d="M18.56 5.44l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94zm-11 1L8.5 8.5l.94-2.06 2.06-.94-2.06-.94L8.5 2.5l-.94 2.06-2.06.94zm10 10l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94z"/><path d="M17.41 7.96l-1.37-1.37c-.4-.4-.92-.59-1.43-.59-.52 0-1.04.2-1.43.59L10.3 9.45l-7.72 7.72c-.78.78-.78 2.05 0 2.83L4 21.41c.39.39.9.59 1.41.59.51 0 1.02-.2 1.41-.59l7.78-7.78 2.81-2.81c.8-.78.8-2.07 0-2.86zM5.41 20L4 18.59l7.72-7.72 1.47 1.35L5.41 20z"/>
  </svg>
      </button>
      
  <style>
    .colab-df-container {
      display:flex;
      flex-wrap:wrap;
      gap: 12px;
    }

    .colab-df-convert {
      background-color: #E8F0FE;
      border: none;
      border-radius: 50%;
      cursor: pointer;
      display: none;
      fill: #1967D2;
      height: 32px;
      padding: 0 0 0 0;
      width: 32px;
    }

    .colab-df-convert:hover {
      background-color: #E2EBFA;
      box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
      fill: #174EA6;
    }

    [theme=dark] .colab-df-convert {
      background-color: #3B4455;
      fill: #D2E3FC;
    }

    [theme=dark] .colab-df-convert:hover {
      background-color: #434B5C;
      box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
      filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
      fill: #FFFFFF;
    }
  </style>

      <script>
        const buttonEl =
          document.querySelector('#df-7ab88c7f-a7bf-4c4d-9074-e4f34b69bf12 button.colab-df-convert');
        buttonEl.style.display =
          google.colab.kernel.accessAllowed ? 'block' : 'none';

        async function convertToInteractive(key) {
          const element = document.querySelector('#df-7ab88c7f-a7bf-4c4d-9074-e4f34b69bf12');
          const dataTable =
            await google.colab.kernel.invokeFunction('convertToInteractive',
                                                     [key], {});
          if (!dataTable) return;

          const docLinkHtml = 'Like what you see? Visit the ' +
            '<a target="_blank" href=https://colab.research.google.com/notebooks/data_table.ipynb>data table notebook</a>'
            + ' to learn more about interactive tables.';
          element.innerHTML = '';
          dataTable['output_type'] = 'display_data';
          await google.colab.output.renderOutput(dataTable, element);
          const docLink = document.createElement('div');
          docLink.innerHTML = docLinkHtml;
          element.appendChild(docLink);
        }
      </script>
    </div>
  </div>
  
```
:::
:::

::: {.cell .markdown id="CpyX2LDWtv1W"}
## Data Cleaning
:::

::: {.cell .code execution_count="185" colab="{\"base_uri\":\"https://localhost:8080/\"}" id="z36BpI0Hs_S4" outputId="95ac8e19-1753-4ae6-939c-29022b5d080f"}
``` {.python}
df.isnull().sum()
```

::: {.output .execute_result execution_count="185"}
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
:::
:::

::: {.cell .markdown id="4-bsPuhz23yg"}
***We see that there are no null values â€‹â€‹in the data.***
:::

::: {.cell .code execution_count="186" colab="{\"height\":423,\"base_uri\":\"https://localhost:8080/\"}" id="JzJRpNEg1V16" outputId="73a82033-f4b5-49a1-ca4e-4349d63ea2f8"}
``` {.python}
df.drop(columns=['No'])
```

::: {.output .execute_result execution_count="186"}
```{=html}
  <div id="df-8c5bb15a-62e7-4ac0-94b2-a21f8dba40c0">
    <div class="colab-df-container">
      <div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>Gender</th>
      <th>Education</th>
      <th>Working Status</th>
      <th>Marriage Style</th>
      <th>Status of Having a Child</th>
      <th>B1</th>
      <th>B2</th>
      <th>B3</th>
      <th>B4</th>
      <th>B5</th>
      <th>...</th>
      <th>B12</th>
      <th>B13</th>
      <th>B14</th>
      <th>B15</th>
      <th>B16</th>
      <th>B17</th>
      <th>B18</th>
      <th>B19</th>
      <th>B20</th>
      <th>B21</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>Male</td>
      <td>Msc or PhD</td>
      <td>Unemployed</td>
      <td>Flirt Marriage</td>
      <td>No</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>...</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
    </tr>
    <tr>
      <th>1</th>
      <td>Male</td>
      <td>Bachelor</td>
      <td>Unemployed</td>
      <td>Flirt Marriage</td>
      <td>Yes</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>...</td>
      <td>1</td>
      <td>0</td>
      <td>1</td>
      <td>1</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>2</th>
      <td>Male</td>
      <td>Msc or PhD</td>
      <td>Unemployed</td>
      <td>Flirt Marriage</td>
      <td>Yes</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>1</td>
      <td>1</td>
      <td>...</td>
      <td>1</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>1</td>
    </tr>
    <tr>
      <th>3</th>
      <td>Male</td>
      <td>Msc or PhD</td>
      <td>Unemployed</td>
      <td>Flirt Marriage</td>
      <td>Yes</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>1</td>
      <td>1</td>
      <td>...</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>3</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>4</th>
      <td>Male</td>
      <td>Msc or PhD</td>
      <td>Unemployed</td>
      <td>Arranged Marriage</td>
      <td>Yes</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>1</td>
      <td>...</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>428</th>
      <td>Female</td>
      <td>High School</td>
      <td>Employed</td>
      <td>Arranged Marriage</td>
      <td>Yes</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>...</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>429</th>
      <td>Female</td>
      <td>High School</td>
      <td>Employed</td>
      <td>Arranged Marriage</td>
      <td>Yes</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>...</td>
      <td>1</td>
      <td>0</td>
      <td>1</td>
      <td>1</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>1</td>
      <td>2</td>
    </tr>
    <tr>
      <th>430</th>
      <td>Female</td>
      <td>Primary</td>
      <td>Employed</td>
      <td>Arranged Marriage</td>
      <td>Yes</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>...</td>
      <td>1</td>
      <td>2</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>2</td>
      <td>0</td>
      <td>0</td>
      <td>2</td>
      <td>1</td>
    </tr>
    <tr>
      <th>431</th>
      <td>Female</td>
      <td>Bachelor</td>
      <td>Employed</td>
      <td>Flirt Marriage</td>
      <td>Yes</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>...</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
    <tr>
      <th>432</th>
      <td>Female</td>
      <td>Primary</td>
      <td>Employed</td>
      <td>Flirt Marriage</td>
      <td>Yes</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>...</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
    </tr>
  </tbody>
</table>
<p>433 rows Ã— 26 columns</p>
</div>
      <button class="colab-df-convert" onclick="convertToInteractive('df-8c5bb15a-62e7-4ac0-94b2-a21f8dba40c0')"
              title="Convert this dataframe to an interactive table."
              style="display:none;">
        
  <svg xmlns="http://www.w3.org/2000/svg" height="24px"viewBox="0 0 24 24"
       width="24px">
    <path d="M0 0h24v24H0V0z" fill="none"/>
    <path d="M18.56 5.44l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94zm-11 1L8.5 8.5l.94-2.06 2.06-.94-2.06-.94L8.5 2.5l-.94 2.06-2.06.94zm10 10l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94z"/><path d="M17.41 7.96l-1.37-1.37c-.4-.4-.92-.59-1.43-.59-.52 0-1.04.2-1.43.59L10.3 9.45l-7.72 7.72c-.78.78-.78 2.05 0 2.83L4 21.41c.39.39.9.59 1.41.59.51 0 1.02-.2 1.41-.59l7.78-7.78 2.81-2.81c.8-.78.8-2.07 0-2.86zM5.41 20L4 18.59l7.72-7.72 1.47 1.35L5.41 20z"/>
  </svg>
      </button>
      
  <style>
    .colab-df-container {
      display:flex;
      flex-wrap:wrap;
      gap: 12px;
    }

    .colab-df-convert {
      background-color: #E8F0FE;
      border: none;
      border-radius: 50%;
      cursor: pointer;
      display: none;
      fill: #1967D2;
      height: 32px;
      padding: 0 0 0 0;
      width: 32px;
    }

    .colab-df-convert:hover {
      background-color: #E2EBFA;
      box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
      fill: #174EA6;
    }

    [theme=dark] .colab-df-convert {
      background-color: #3B4455;
      fill: #D2E3FC;
    }

    [theme=dark] .colab-df-convert:hover {
      background-color: #434B5C;
      box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
      filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
      fill: #FFFFFF;
    }
  </style>

      <script>
        const buttonEl =
          document.querySelector('#df-8c5bb15a-62e7-4ac0-94b2-a21f8dba40c0 button.colab-df-convert');
        buttonEl.style.display =
          google.colab.kernel.accessAllowed ? 'block' : 'none';

        async function convertToInteractive(key) {
          const element = document.querySelector('#df-8c5bb15a-62e7-4ac0-94b2-a21f8dba40c0');
          const dataTable =
            await google.colab.kernel.invokeFunction('convertToInteractive',
                                                     [key], {});
          if (!dataTable) return;

          const docLinkHtml = 'Like what you see? Visit the ' +
            '<a target="_blank" href=https://colab.research.google.com/notebooks/data_table.ipynb>data table notebook</a>'
            + ' to learn more about interactive tables.';
          element.innerHTML = '';
          dataTable['output_type'] = 'display_data';
          await google.colab.output.renderOutput(dataTable, element);
          const docLink = document.createElement('div');
          docLink.innerHTML = docLinkHtml;
          element.appendChild(docLink);
        }
      </script>
    </div>
  </div>
  
```
:::
:::

::: {.cell .markdown id="88bW8yYD3tBp"}
***The numbering order is data we don\'t need. And we have to get rid of
it.***
:::

::: {.cell .markdown id="cl79eytKt2bk"}
## Basic Statistics
:::

::: {.cell .markdown id="dQUpQV4t37lh"}
***Let\'s see how many columns and rows there are.***
:::

::: {.cell .code execution_count="187" colab="{\"base_uri\":\"https://localhost:8080/\"}" id="KOPAIw0btJhh" outputId="d7f98889-be6f-4764-ea03-0c1945599965"}
``` {.python}
df.shape
```

::: {.output .execute_result execution_count="187"}
    (433, 27)
:::
:::

::: {.cell .markdown id="sKgJ5nwx4Gx5"}
***Let\'s look at some basic statistics like mean, median, standart
deviation and etc. about the data.***
:::

::: {.cell .code execution_count="188" colab="{\"height\":393,\"base_uri\":\"https://localhost:8080/\"}" id="QoimfFoDtPBU" outputId="87c5bdb6-5f74-4016-d61b-e696f10e98a3"}
``` {.python}
df.describe()
```

::: {.output .execute_result execution_count="188"}
```{=html}
  <div id="df-a98724ef-cfbc-4732-9c57-18ca1ffbc36c">
    <div class="colab-df-container">
      <div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>No</th>
      <th>B1</th>
      <th>B2</th>
      <th>B3</th>
      <th>B4</th>
      <th>B5</th>
      <th>B6</th>
      <th>B7</th>
      <th>B8</th>
      <th>B9</th>
      <th>...</th>
      <th>B12</th>
      <th>B13</th>
      <th>B14</th>
      <th>B15</th>
      <th>B16</th>
      <th>B17</th>
      <th>B18</th>
      <th>B19</th>
      <th>B20</th>
      <th>B21</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>count</th>
      <td>433.000000</td>
      <td>433.000000</td>
      <td>433.000000</td>
      <td>433.000000</td>
      <td>433.000000</td>
      <td>433.000000</td>
      <td>433.000000</td>
      <td>433.000000</td>
      <td>433.000000</td>
      <td>433.000000</td>
      <td>...</td>
      <td>433.000000</td>
      <td>433.000000</td>
      <td>433.000000</td>
      <td>433.000000</td>
      <td>433.000000</td>
      <td>433.000000</td>
      <td>433.000000</td>
      <td>433.000000</td>
      <td>433.000000</td>
      <td>433.000000</td>
    </tr>
    <tr>
      <th>mean</th>
      <td>216.274827</td>
      <td>0.397229</td>
      <td>0.392610</td>
      <td>0.450346</td>
      <td>0.612009</td>
      <td>0.678984</td>
      <td>0.568129</td>
      <td>0.503464</td>
      <td>0.515012</td>
      <td>0.163972</td>
      <td>...</td>
      <td>0.665127</td>
      <td>0.579677</td>
      <td>0.418014</td>
      <td>0.528868</td>
      <td>0.551963</td>
      <td>0.732102</td>
      <td>0.244804</td>
      <td>0.224018</td>
      <td>0.429561</td>
      <td>0.475751</td>
    </tr>
    <tr>
      <th>std</th>
      <td>125.181852</td>
      <td>0.747955</td>
      <td>0.741083</td>
      <td>0.834974</td>
      <td>0.668085</td>
      <td>0.620593</td>
      <td>0.847436</td>
      <td>0.642342</td>
      <td>0.684065</td>
      <td>0.474727</td>
      <td>...</td>
      <td>0.776452</td>
      <td>0.759966</td>
      <td>0.655001</td>
      <td>0.790407</td>
      <td>0.731375</td>
      <td>0.721566</td>
      <td>0.577452</td>
      <td>0.625963</td>
      <td>0.694058</td>
      <td>0.742237</td>
    </tr>
    <tr>
      <th>min</th>
      <td>1.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>25%</th>
      <td>108.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>50%</th>
      <td>215.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>1.000000</td>
      <td>1.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>...</td>
      <td>1.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>1.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>75%</th>
      <td>324.000000</td>
      <td>1.000000</td>
      <td>1.000000</td>
      <td>0.000000</td>
      <td>1.000000</td>
      <td>1.000000</td>
      <td>1.000000</td>
      <td>1.000000</td>
      <td>1.000000</td>
      <td>0.000000</td>
      <td>...</td>
      <td>1.000000</td>
      <td>1.000000</td>
      <td>1.000000</td>
      <td>1.000000</td>
      <td>1.000000</td>
      <td>1.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>1.000000</td>
      <td>1.000000</td>
    </tr>
    <tr>
      <th>max</th>
      <td>435.000000</td>
      <td>3.000000</td>
      <td>3.000000</td>
      <td>3.000000</td>
      <td>3.000000</td>
      <td>3.000000</td>
      <td>3.000000</td>
      <td>3.000000</td>
      <td>3.000000</td>
      <td>3.000000</td>
      <td>...</td>
      <td>3.000000</td>
      <td>3.000000</td>
      <td>3.000000</td>
      <td>3.000000</td>
      <td>3.000000</td>
      <td>3.000000</td>
      <td>3.000000</td>
      <td>3.000000</td>
      <td>3.000000</td>
      <td>3.000000</td>
    </tr>
  </tbody>
</table>
<p>8 rows Ã— 22 columns</p>
</div>
      <button class="colab-df-convert" onclick="convertToInteractive('df-a98724ef-cfbc-4732-9c57-18ca1ffbc36c')"
              title="Convert this dataframe to an interactive table."
              style="display:none;">
        
  <svg xmlns="http://www.w3.org/2000/svg" height="24px"viewBox="0 0 24 24"
       width="24px">
    <path d="M0 0h24v24H0V0z" fill="none"/>
    <path d="M18.56 5.44l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94zm-11 1L8.5 8.5l.94-2.06 2.06-.94-2.06-.94L8.5 2.5l-.94 2.06-2.06.94zm10 10l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94z"/><path d="M17.41 7.96l-1.37-1.37c-.4-.4-.92-.59-1.43-.59-.52 0-1.04.2-1.43.59L10.3 9.45l-7.72 7.72c-.78.78-.78 2.05 0 2.83L4 21.41c.39.39.9.59 1.41.59.51 0 1.02-.2 1.41-.59l7.78-7.78 2.81-2.81c.8-.78.8-2.07 0-2.86zM5.41 20L4 18.59l7.72-7.72 1.47 1.35L5.41 20z"/>
  </svg>
      </button>
      
  <style>
    .colab-df-container {
      display:flex;
      flex-wrap:wrap;
      gap: 12px;
    }

    .colab-df-convert {
      background-color: #E8F0FE;
      border: none;
      border-radius: 50%;
      cursor: pointer;
      display: none;
      fill: #1967D2;
      height: 32px;
      padding: 0 0 0 0;
      width: 32px;
    }

    .colab-df-convert:hover {
      background-color: #E2EBFA;
      box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
      fill: #174EA6;
    }

    [theme=dark] .colab-df-convert {
      background-color: #3B4455;
      fill: #D2E3FC;
    }

    [theme=dark] .colab-df-convert:hover {
      background-color: #434B5C;
      box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
      filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
      fill: #FFFFFF;
    }
  </style>

      <script>
        const buttonEl =
          document.querySelector('#df-a98724ef-cfbc-4732-9c57-18ca1ffbc36c button.colab-df-convert');
        buttonEl.style.display =
          google.colab.kernel.accessAllowed ? 'block' : 'none';

        async function convertToInteractive(key) {
          const element = document.querySelector('#df-a98724ef-cfbc-4732-9c57-18ca1ffbc36c');
          const dataTable =
            await google.colab.kernel.invokeFunction('convertToInteractive',
                                                     [key], {});
          if (!dataTable) return;

          const docLinkHtml = 'Like what you see? Visit the ' +
            '<a target="_blank" href=https://colab.research.google.com/notebooks/data_table.ipynb>data table notebook</a>'
            + ' to learn more about interactive tables.';
          element.innerHTML = '';
          dataTable['output_type'] = 'display_data';
          await google.colab.output.renderOutput(dataTable, element);
          const docLink = document.createElement('div');
          docLink.innerHTML = docLinkHtml;
          element.appendChild(docLink);
        }
      </script>
    </div>
  </div>
  
```
:::
:::

::: {.cell .markdown id="PxoKXPM84WuS"}
***Let\'s have a quick idea about columns.***
:::

::: {.cell .code execution_count="189" colab="{\"base_uri\":\"https://localhost:8080/\"}" id="NoB9fA_9ntxh" outputId="1f98da28-3480-4926-ca89-193d2bd75e1a"}
``` {.python}
df.info()
```

::: {.output .stream .stdout}
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
:::
:::

::: {.cell .markdown id="8VGCSDnrrnkR"}
## Calculating sum of all BDI columns

for finding BDI Score
:::

::: {.cell .markdown id="lKpLoWJ_4osI"}
***As mentioned above, the BDI score is obtained from the sum of all
Bn-type columns. Now let\'s create a new column and add a dataframe by
collecting them.***
:::

::: {.cell .code execution_count="190" id="Hi_nwT2GxEmm"}
``` {.python}
def bdi(df):
    finalBDIScore = []
    for i in df:
        finalBDIScore.append(i.sum())
    return np.array(finalBDIScore)
```
:::

::: {.cell .code execution_count="191" id="lE5y_tDixQqY"}
``` {.python}
df['BDI Score'] = bdi(df.drop(labels = 'No\tGender\tEducation	Working Status	Marriage Style	Status of Having a Child'.split("\t"),axis = 1).values)
```
:::

::: {.cell .code execution_count="192" colab="{\"height\":235,\"base_uri\":\"https://localhost:8080/\"}" id="MtfwklaXxXBm" outputId="d6e72635-4c3c-4f77-9d22-a66ca809fbd2"}
``` {.python}
df.head()
```

::: {.output .execute_result execution_count="192"}
```{=html}
  <div id="df-c6c8e5d1-03d8-4e7d-990f-fd2722bee8cb">
    <div class="colab-df-container">
      <div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>No</th>
      <th>Gender</th>
      <th>Education</th>
      <th>Working Status</th>
      <th>Marriage Style</th>
      <th>Status of Having a Child</th>
      <th>B1</th>
      <th>B2</th>
      <th>B3</th>
      <th>B4</th>
      <th>...</th>
      <th>B13</th>
      <th>B14</th>
      <th>B15</th>
      <th>B16</th>
      <th>B17</th>
      <th>B18</th>
      <th>B19</th>
      <th>B20</th>
      <th>B21</th>
      <th>BDI Score</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>345</td>
      <td>Male</td>
      <td>Msc or PhD</td>
      <td>Unemployed</td>
      <td>Flirt Marriage</td>
      <td>No</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>...</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>61</td>
    </tr>
    <tr>
      <th>1</th>
      <td>73</td>
      <td>Male</td>
      <td>Bachelor</td>
      <td>Unemployed</td>
      <td>Flirt Marriage</td>
      <td>Yes</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>...</td>
      <td>0</td>
      <td>1</td>
      <td>1</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>12</td>
    </tr>
    <tr>
      <th>2</th>
      <td>107</td>
      <td>Male</td>
      <td>Msc or PhD</td>
      <td>Unemployed</td>
      <td>Flirt Marriage</td>
      <td>Yes</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>1</td>
      <td>...</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>1</td>
      <td>8</td>
    </tr>
    <tr>
      <th>3</th>
      <td>131</td>
      <td>Male</td>
      <td>Msc or PhD</td>
      <td>Unemployed</td>
      <td>Flirt Marriage</td>
      <td>Yes</td>
      <td>0</td>
      <td>1</td>
      <td>0</td>
      <td>1</td>
      <td>...</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>3</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>6</td>
    </tr>
    <tr>
      <th>4</th>
      <td>4</td>
      <td>Male</td>
      <td>Msc or PhD</td>
      <td>Unemployed</td>
      <td>Arranged Marriage</td>
      <td>Yes</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>...</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>0</td>
      <td>1</td>
    </tr>
  </tbody>
</table>
<p>5 rows Ã— 28 columns</p>
</div>
      <button class="colab-df-convert" onclick="convertToInteractive('df-c6c8e5d1-03d8-4e7d-990f-fd2722bee8cb')"
              title="Convert this dataframe to an interactive table."
              style="display:none;">
        
  <svg xmlns="http://www.w3.org/2000/svg" height="24px"viewBox="0 0 24 24"
       width="24px">
    <path d="M0 0h24v24H0V0z" fill="none"/>
    <path d="M18.56 5.44l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94zm-11 1L8.5 8.5l.94-2.06 2.06-.94-2.06-.94L8.5 2.5l-.94 2.06-2.06.94zm10 10l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94z"/><path d="M17.41 7.96l-1.37-1.37c-.4-.4-.92-.59-1.43-.59-.52 0-1.04.2-1.43.59L10.3 9.45l-7.72 7.72c-.78.78-.78 2.05 0 2.83L4 21.41c.39.39.9.59 1.41.59.51 0 1.02-.2 1.41-.59l7.78-7.78 2.81-2.81c.8-.78.8-2.07 0-2.86zM5.41 20L4 18.59l7.72-7.72 1.47 1.35L5.41 20z"/>
  </svg>
      </button>
      
  <style>
    .colab-df-container {
      display:flex;
      flex-wrap:wrap;
      gap: 12px;
    }

    .colab-df-convert {
      background-color: #E8F0FE;
      border: none;
      border-radius: 50%;
      cursor: pointer;
      display: none;
      fill: #1967D2;
      height: 32px;
      padding: 0 0 0 0;
      width: 32px;
    }

    .colab-df-convert:hover {
      background-color: #E2EBFA;
      box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
      fill: #174EA6;
    }

    [theme=dark] .colab-df-convert {
      background-color: #3B4455;
      fill: #D2E3FC;
    }

    [theme=dark] .colab-df-convert:hover {
      background-color: #434B5C;
      box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
      filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
      fill: #FFFFFF;
    }
  </style>

      <script>
        const buttonEl =
          document.querySelector('#df-c6c8e5d1-03d8-4e7d-990f-fd2722bee8cb button.colab-df-convert');
        buttonEl.style.display =
          google.colab.kernel.accessAllowed ? 'block' : 'none';

        async function convertToInteractive(key) {
          const element = document.querySelector('#df-c6c8e5d1-03d8-4e7d-990f-fd2722bee8cb');
          const dataTable =
            await google.colab.kernel.invokeFunction('convertToInteractive',
                                                     [key], {});
          if (!dataTable) return;

          const docLinkHtml = 'Like what you see? Visit the ' +
            '<a target="_blank" href=https://colab.research.google.com/notebooks/data_table.ipynb>data table notebook</a>'
            + ' to learn more about interactive tables.';
          element.innerHTML = '';
          dataTable['output_type'] = 'display_data';
          await google.colab.output.renderOutput(dataTable, element);
          const docLink = document.createElement('div');
          docLink.innerHTML = docLinkHtml;
          element.appendChild(docLink);
        }
      </script>
    </div>
  </div>
  
```
:::
:::

::: {.cell .markdown id="r2pKOpy65FmJ"}
***Columns of type Bn no longer have any meaning for us and we can
delete them.***
:::

::: {.cell .code execution_count="193" colab="{\"height\":442,\"base_uri\":\"https://localhost:8080/\"}" id="ujPzNbvU1phh" outputId="43e9cca4-dfa8-4b85-d59f-af467f21d36f"}
``` {.python}
droplist = []
for i in range(21):
  droplist.append(f"B{i+1}")
print(droplist)
df.drop(columns=droplist)
```

::: {.output .stream .stdout}
    ['B1', 'B2', 'B3', 'B4', 'B5', 'B6', 'B7', 'B8', 'B9', 'B10', 'B11', 'B12', 'B13', 'B14', 'B15', 'B16', 'B17', 'B18', 'B19', 'B20', 'B21']
:::

::: {.output .execute_result execution_count="193"}
```{=html}
  <div id="df-b14a5163-4b6d-41a9-90c3-5866604ddf9c">
    <div class="colab-df-container">
      <div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>No</th>
      <th>Gender</th>
      <th>Education</th>
      <th>Working Status</th>
      <th>Marriage Style</th>
      <th>Status of Having a Child</th>
      <th>BDI Score</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>345</td>
      <td>Male</td>
      <td>Msc or PhD</td>
      <td>Unemployed</td>
      <td>Flirt Marriage</td>
      <td>No</td>
      <td>61</td>
    </tr>
    <tr>
      <th>1</th>
      <td>73</td>
      <td>Male</td>
      <td>Bachelor</td>
      <td>Unemployed</td>
      <td>Flirt Marriage</td>
      <td>Yes</td>
      <td>12</td>
    </tr>
    <tr>
      <th>2</th>
      <td>107</td>
      <td>Male</td>
      <td>Msc or PhD</td>
      <td>Unemployed</td>
      <td>Flirt Marriage</td>
      <td>Yes</td>
      <td>8</td>
    </tr>
    <tr>
      <th>3</th>
      <td>131</td>
      <td>Male</td>
      <td>Msc or PhD</td>
      <td>Unemployed</td>
      <td>Flirt Marriage</td>
      <td>Yes</td>
      <td>6</td>
    </tr>
    <tr>
      <th>4</th>
      <td>4</td>
      <td>Male</td>
      <td>Msc or PhD</td>
      <td>Unemployed</td>
      <td>Arranged Marriage</td>
      <td>Yes</td>
      <td>1</td>
    </tr>
    <tr>
      <th>...</th>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
      <td>...</td>
    </tr>
    <tr>
      <th>428</th>
      <td>401</td>
      <td>Female</td>
      <td>High School</td>
      <td>Employed</td>
      <td>Arranged Marriage</td>
      <td>Yes</td>
      <td>0</td>
    </tr>
    <tr>
      <th>429</th>
      <td>244</td>
      <td>Female</td>
      <td>High School</td>
      <td>Employed</td>
      <td>Arranged Marriage</td>
      <td>Yes</td>
      <td>10</td>
    </tr>
    <tr>
      <th>430</th>
      <td>333</td>
      <td>Female</td>
      <td>Primary</td>
      <td>Employed</td>
      <td>Arranged Marriage</td>
      <td>Yes</td>
      <td>12</td>
    </tr>
    <tr>
      <th>431</th>
      <td>350</td>
      <td>Female</td>
      <td>Bachelor</td>
      <td>Employed</td>
      <td>Flirt Marriage</td>
      <td>Yes</td>
      <td>2</td>
    </tr>
    <tr>
      <th>432</th>
      <td>225</td>
      <td>Female</td>
      <td>Primary</td>
      <td>Employed</td>
      <td>Flirt Marriage</td>
      <td>Yes</td>
      <td>0</td>
    </tr>
  </tbody>
</table>
<p>433 rows Ã— 7 columns</p>
</div>
      <button class="colab-df-convert" onclick="convertToInteractive('df-b14a5163-4b6d-41a9-90c3-5866604ddf9c')"
              title="Convert this dataframe to an interactive table."
              style="display:none;">
        
  <svg xmlns="http://www.w3.org/2000/svg" height="24px"viewBox="0 0 24 24"
       width="24px">
    <path d="M0 0h24v24H0V0z" fill="none"/>
    <path d="M18.56 5.44l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94zm-11 1L8.5 8.5l.94-2.06 2.06-.94-2.06-.94L8.5 2.5l-.94 2.06-2.06.94zm10 10l.94 2.06.94-2.06 2.06-.94-2.06-.94-.94-2.06-.94 2.06-2.06.94z"/><path d="M17.41 7.96l-1.37-1.37c-.4-.4-.92-.59-1.43-.59-.52 0-1.04.2-1.43.59L10.3 9.45l-7.72 7.72c-.78.78-.78 2.05 0 2.83L4 21.41c.39.39.9.59 1.41.59.51 0 1.02-.2 1.41-.59l7.78-7.78 2.81-2.81c.8-.78.8-2.07 0-2.86zM5.41 20L4 18.59l7.72-7.72 1.47 1.35L5.41 20z"/>
  </svg>
      </button>
      
  <style>
    .colab-df-container {
      display:flex;
      flex-wrap:wrap;
      gap: 12px;
    }

    .colab-df-convert {
      background-color: #E8F0FE;
      border: none;
      border-radius: 50%;
      cursor: pointer;
      display: none;
      fill: #1967D2;
      height: 32px;
      padding: 0 0 0 0;
      width: 32px;
    }

    .colab-df-convert:hover {
      background-color: #E2EBFA;
      box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15);
      fill: #174EA6;
    }

    [theme=dark] .colab-df-convert {
      background-color: #3B4455;
      fill: #D2E3FC;
    }

    [theme=dark] .colab-df-convert:hover {
      background-color: #434B5C;
      box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15);
      filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3));
      fill: #FFFFFF;
    }
  </style>

      <script>
        const buttonEl =
          document.querySelector('#df-b14a5163-4b6d-41a9-90c3-5866604ddf9c button.colab-df-convert');
        buttonEl.style.display =
          google.colab.kernel.accessAllowed ? 'block' : 'none';

        async function convertToInteractive(key) {
          const element = document.querySelector('#df-b14a5163-4b6d-41a9-90c3-5866604ddf9c');
          const dataTable =
            await google.colab.kernel.invokeFunction('convertToInteractive',
                                                     [key], {});
          if (!dataTable) return;

          const docLinkHtml = 'Like what you see? Visit the ' +
            '<a target="_blank" href=https://colab.research.google.com/notebooks/data_table.ipynb>data table notebook</a>'
            + ' to learn more about interactive tables.';
          element.innerHTML = '';
          dataTable['output_type'] = 'display_data';
          await google.colab.output.renderOutput(dataTable, element);
          const docLink = document.createElement('div');
          docLink.innerHTML = docLinkHtml;
          element.appendChild(docLink);
        }
      </script>
    </div>
  </div>
  
```
:::
:::

::: {.cell .markdown id="nw7BjnGKryjV"}
## Explarotary Data Analysis
:::

::: {.cell .code execution_count="194" colab="{\"height\":381,\"base_uri\":\"https://localhost:8080/\"}" id="O8WV9V7ftTn7" outputId="e89dc405-8385-4e82-87bc-d63441e0170d"}
``` {.python}
sns.catplot(x = 'Gender', y = 'BDI Score',data = df, 
            palette="Blues").set(title="BDI Score by Genders");
```

::: {.output .display_data}
![](vertopal_872ca716d1ce4022a34fb701fc2d0d73/d2cc5cab36256fd4d721cab8b44335f7e39f2952.png)
:::
:::

::: {.cell .markdown id="mvtCNaXC5W9a"}
***We see that women have a higher average rate of marital depression
than men.***
:::

::: {.cell .code execution_count="195" colab="{\"height\":301,\"base_uri\":\"https://localhost:8080/\"}" id="vPj4P_RQuVeV" outputId="04ec0b0c-adb4-44c5-a4ae-2b0cc756bc28"}
``` {.python}
sns.set_theme(style="whitegrid")
sns.barplot(x="Working Status", y="BDI Score", data=df, 
            palette="Blues").set(title="Working Status and BDI Score");
```

::: {.output .display_data}
![](vertopal_872ca716d1ce4022a34fb701fc2d0d73/edb93a7a856c6e31326b08506572250159e76b3c.png)
:::
:::

::: {.cell .markdown id="Qv5TWXmt5oeQ"}
***It is clear that unemployed people experience less marital depression
than employed people.***
:::

::: {.cell .code execution_count="196" colab="{\"height\":410,\"base_uri\":\"https://localhost:8080/\"}" id="Rjpaks8751vD" outputId="2b7aacef-b238-4b5e-c821-a4bcf0f56456"}
``` {.python}
plt.figure(figsize=(10,6))
bxp = sns.boxplot(y = 'Education', x = 'BDI Score',data = df, 
                  palette="Blues").set(title="Education Level and BDI Score");
```

::: {.output .display_data}
![](vertopal_872ca716d1ce4022a34fb701fc2d0d73/61bbe46115bc0e19088e66b9bd4bf0e412414842.png)
:::
:::

::: {.cell .markdown id="yL-VjXEy55oZ"}
***Increasing people\'s level of education leads to psychologically
healthier family life. In short, education brings peace.***
:::

::: {.cell .code execution_count="197" colab="{\"height\":301,\"base_uri\":\"https://localhost:8080/\"}" id="vM39E_Xl6F96" outputId="d612d864-b5d5-4730-effd-f1dc0642b5c7"}
``` {.python}
sns.barplot(x="BDI Score", y="Status of Having a Child", data=df, 
            palette="Blues").set(title="Status of having a child and BDI Score");
```

::: {.output .display_data}
![](vertopal_872ca716d1ce4022a34fb701fc2d0d73/4b447122359ac464abb0284d82dfee6729b11b37.png)
:::
:::

::: {.cell .markdown id="l2lmMRlm6RmZ"}
***Individuals in families with children experience less marital
depression on average. We will examine this topic separately for genders
in the future***
:::

::: {.cell .code execution_count="198" colab="{\"height\":301,\"base_uri\":\"https://localhost:8080/\"}" id="CBtn8mrb69AZ" outputId="9d099822-ba86-48d2-d750-81d54ba41acf"}
``` {.python}
sns.barplot(x = "Marriage Style", y = "BDI Score", data = df, 
            palette = "Blues").set(title="Marriage Style and BDI Score");
```

::: {.output .display_data}
![](vertopal_872ca716d1ce4022a34fb701fc2d0d73/7c06594f7b708b87ee876457402a8a4b74cedd08.png)
:::
:::

::: {.cell .markdown id="6JvS_qSA6xC5"}
***Marital style may not appear to affect marital depression at first
glance, but when we examine it, we will see both negative and positive
effects of this topic depending on gender.***
:::

::: {.cell .markdown id="vo2HtiAhadJl"}
## Explarotary Data Analysis by Gender
:::

::: {.cell .code execution_count="199" colab="{\"height\":284,\"base_uri\":\"https://localhost:8080/\"}" id="X0cDxlIaaoY6" outputId="02ab10c2-b92f-42a6-8636-641fd3c15419"}
``` {.python}
male = df.where(df['Gender'] == "Male").groupby(by = "Working Status").mean()
male = male['BDI Score']
male = np.array(male)
plt.bar(['Employed', 'Unemployed'], male,  color=("Blue", "Red"))
plt.title("BDI Score and Working Status for Males")
plt.show()
```

::: {.output .display_data}
![](vertopal_872ca716d1ce4022a34fb701fc2d0d73/55290c80fea09cc6cb910d7df66c10a505b1a891.png)
:::
:::

::: {.cell .code execution_count="200" colab="{\"height\":284,\"base_uri\":\"https://localhost:8080/\"}" id="civ07PyHbYBL" outputId="fcf759ef-53c5-4085-854d-2fda029f3235"}
``` {.python}
female = df.where(df['Gender'] == "Female").groupby(by= "Working Status").mean()
female = female['BDI Score']
female = np.array(female)
plt.title("BDI Score and Working Status for Females")
plt.bar(['Employed', 'Unemployed'], female, color=("Blue", "Red"))
plt.show()
```

::: {.output .display_data}
![](vertopal_872ca716d1ce4022a34fb701fc2d0d73/66350c27c6a88a9c52542edc8a72f3d2e59c0f96.png)
:::
:::

::: {.cell .markdown id="NWd4J7V87ZsB"}
***It is clear that unemployed people experience less marital depression
than employed people. And it is not depend on any gender***
:::

::: {.cell .code execution_count="201" colab="{\"height\":284,\"base_uri\":\"https://localhost:8080/\"}" id="3zj7xlIGgBEw" outputId="513608e7-ef06-4e43-f6f4-87c6a5b4e72f"}
``` {.python}
male = df.where(df['Gender'] == "Male").groupby(by = "Marriage Style").mean()
male = male['BDI Score']
male = np.array(male)
plt.title("BDI Score and Marriage Style for Females")
plt.bar(['Arranged Marriage', 'Flirt Marriage'], male, color=("Blue", "Pink"))
plt.show()
```

::: {.output .display_data}
![](vertopal_872ca716d1ce4022a34fb701fc2d0d73/2c068d25ccc7a2fa4d59219ed06f4ea2ecf7587f.png)
:::
:::

::: {.cell .code execution_count="202" colab="{\"height\":284,\"base_uri\":\"https://localhost:8080/\"}" id="npSf8THHgTMx" outputId="18b4c854-c963-4d01-f97e-ce403da6d07b"}
``` {.python}
female = df.where(df['Gender'] == "Male").groupby(by = "Marriage Style").mean()
female = female['BDI Score']
female = np.array(female)
plt.title("BDI Score and Marriage Style for Females")
plt.bar(['Arranged Marriage', 'Flirt Marriage'], female, color=("Blue", "Pink"))
plt.show()
```

::: {.output .display_data}
![](vertopal_872ca716d1ce4022a34fb701fc2d0d73/2c068d25ccc7a2fa4d59219ed06f4ea2ecf7587f.png)
:::
:::

::: {.cell .markdown id="4_h3n1jI7y6g"}
***Average depression threshold is higher in arranged marriages, but
relatively lower in flirtatious marriages.***
:::

::: {.cell .code execution_count="203" colab="{\"height\":525,\"base_uri\":\"https://localhost:8080/\"}" id="VrNxWwjSghyS" outputId="9eed761c-4ad3-4808-80f7-0ee66c675b24"}
``` {.python}
sns.catplot(x="Gender", y="BDI Score",
                hue="Education",
                data=df, kind="box",
                palette = "Blues", 
                height=7, aspect=.7).set(title='Education and BDI Score by Genders');
```

::: {.output .display_data}
![](vertopal_872ca716d1ce4022a34fb701fc2d0d73/972bd6853a4c8913d5f2ce4e7d6129dd779e3d42.png)
:::
:::

::: {.cell .markdown id="5oHParib8KeJ"}
***Education has a positive effect on both sexes, but in women, the
average level of marital depression decreases with the increase in the
level of education.***
:::

::: {.cell .code execution_count="204" colab="{\"height\":525,\"base_uri\":\"https://localhost:8080/\"}" id="s_9JhABfjmJQ" outputId="fa950f1c-059a-4539-95b5-6381aee6cbb7"}
``` {.python}
sns.catplot(x="Gender", y="BDI Score",
                hue="Status of Having a Child",
                data=df, kind="bar",
                height=7, palette="Blues",
                aspect=.8).set(title="Status of Having Childrens and BDI Score by Genders");
```

::: {.output .display_data}
![](vertopal_872ca716d1ce4022a34fb701fc2d0d73/41dac14b3e21ea6507f628ca93cb2f6d42f7a46c.png)
:::
:::

::: {.cell .markdown id="24lVLZwO8kRp"}
***Towards the end, we make an interesting discovery :) So, although the
presence of children at home does not affect men as much, the feeling of
being a mother causes a decrease in the level of depression in women.
Simply put, children heal their mothers.***
:::

