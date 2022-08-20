# Depression-in-Married-Couples-in-Istanbul
 Depression\_in\_Married\_Couples\_in\_İstanbul /\*! \* \* Twitter Bootstrap \* \*/ /\*! \* Bootstrap v3.3.7 (http://getbootstrap.com) \* Copyright 2011-2016 Twitter, Inc. \* Licensed under MIT (https://github.com/twbs/bootstrap/blob/master/LICENSE) \*/ /\*! normalize.css v3.0.3 | MIT License | github.com/necolas/normalize.css \*/ html { font-family: sans-serif; -ms-text-size-adjust: 100%; -webkit-text-size-adjust: 100%; } body { margin: 0; } article, aside, details, figcaption, figure, footer, header, hgroup, main, menu, nav, section, summary { display: block; } audio, canvas, progress, video { display: inline-block; vertical-align: baseline; } audio:not(\[controls\]) { display: none; height: 0; } \[hidden\], template { display: none; } a { background-color: transparent; } a:active, a:hover { outline: 0; } abbr\[title\] { border-bottom: 1px dotted; } b, strong { font-weight: bold; } dfn { font-style: italic; } h1 { font-size: 2em; margin: 0.67em 0; } mark { background: #ff0; color: #000; } small { font-size: 80%; } sub, sup { font-size: 75%; line-height: 0; position: relative; vertical-align: baseline; } sup { top: -0.5em; } sub { bottom: -0.25em; } img { border: 0; } svg:not(:root) { overflow: hidden; } figure { margin: 1em 40px; } hr { box-sizing: content-box; height: 0; } pre { overflow: auto; } code, kbd, pre, samp { font-family: monospace, monospace; font-size: 1em; } button, input, optgroup, select, textarea { color: inherit; font: inherit; margin: 0; } button { overflow: visible; } button, select { text-transform: none; } button, html input\[type="button"\], input\[type="reset"\], input\[type="submit"\] { -webkit-appearance: button; cursor: pointer; } button\[disabled\], html input\[disabled\] { cursor: default; } button::-moz-focus-inner, input::-moz-focus-inner { border: 0; padding: 0; } input { line-height: normal; } input\[type="checkbox"\], input\[type="radio"\] { box-sizing: border-box; padding: 0; } input\[type="number"\]::-webkit-inner-spin-button, input\[type="number"\]::-webkit-outer-spin-button { height: auto; } input\[type="search"\] { -webkit-appearance: textfield; box-sizing: content-box; } input\[type="search"\]::-webkit-search-cancel-button, input\[type="search"\]::-webkit-search-decoration { -webkit-appearance: none; } fieldset { border: 1px solid #c0c0c0; margin: 0 2px; padding: 0.35em 0.625em 0.75em; } legend { border: 0; padding: 0; } textarea { overflow: auto; } optgroup { font-weight: bold; } table { border-collapse: collapse; border-spacing: 0; } td, th { padding: 0; } /\*! Source: https://github.com/h5bp/html5-boilerplate/blob/master/src/css/main.css \*/ @media print { \*, \*:before, \*:after { background: transparent !important; box-shadow: none !important; text-shadow: none !important; } a, a:visited { text-decoration: underline; } a\[href\]:after { content: " (" attr(href) ")"; } abbr\[title\]:after { content: " (" attr(title) ")"; } a\[href^="#"\]:after, a\[href^="javascript:"\]:after { content: ""; } pre, blockquote { border: 1px solid #999; page-break-inside: avoid; } thead { display: table-header-group; } tr, img { page-break-inside: avoid; } img { max-width: 100% !important; } p, h2, h3 { orphans: 3; widows: 3; } h2, h3 { page-break-after: avoid; } .navbar { display: none; } .btn > .caret, .dropup > .btn > .caret { border-top-color: #000 !important; } .label { border: 1px solid #000; } .table { border-collapse: collapse !important; } .table td, .table th { background-color: #fff !important; } .table-bordered th, .table-bordered td { border: 1px solid #ddd !important; } } @font-face { font-family: 'Glyphicons Halflings'; src: url('../components/bootstrap/fonts/glyphicons-halflings-regular.eot'); src: url('../components/bootstrap/fonts/glyphicons-halflings-regular.eot?#iefix') format('embedded-opentype'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.woff2') format('woff2'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.woff') format('woff'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.ttf') format('truetype'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.svg#glyphicons\_halflingsregular') format('svg'); } .glyphicon { position: relative; top: 1px; display: inline-block; font-family: 'Glyphicons Halflings'; font-style: normal; font-weight: normal; line-height: 1; -webkit-font-smoothing: antialiased; -moz-osx-font-smoothing: grayscale; } .glyphicon-asterisk:before { content: "\\002a"; } .glyphicon-plus:before { content: "\\002b"; } .glyphicon-euro:before, .glyphicon-eur:before { content: "\\20ac"; } .glyphicon-minus:before { content: "\\2212"; } .glyphicon-cloud:before { content: "\\2601"; } .glyphicon-envelope:before { content: "\\2709"; } .glyphicon-pencil:before { content: "\\270f"; } .glyphicon-glass:before { content: "\\e001"; } .glyphicon-music:before { content: "\\e002"; } .glyphicon-search:before { content: "\\e003"; } .glyphicon-heart:before { content: "\\e005"; } .glyphicon-star:before { content: "\\e006"; } .glyphicon-star-empty:before { content: "\\e007"; } .glyphicon-user:before { content: "\\e008"; } .glyphicon-film:before { content: "\\e009"; } .glyphicon-th-large:before { content: "\\e010"; } .glyphicon-th:before { content: "\\e011"; } .glyphicon-th-list:before { content: "\\e012"; } .glyphicon-ok:before { content: "\\e013"; } .glyphicon-remove:before { content: "\\e014"; } .glyphicon-zoom-in:before { content: "\\e015"; } .glyphicon-zoom-out:before { content: "\\e016"; } .glyphicon-off:before { content: "\\e017"; } .glyphicon-signal:before { content: "\\e018"; } .glyphicon-cog:before { content: "\\e019"; } .glyphicon-trash:before { content: "\\e020"; } .glyphicon-home:before { content: "\\e021"; } .glyphicon-file:before { content: "\\e022"; } .glyphicon-time:before { content: "\\e023"; } .glyphicon-road:before { content: "\\e024"; } .glyphicon-download-alt:before { content: "\\e025"; } .glyphicon-download:before { content: "\\e026"; } .glyphicon-upload:before { content: "\\e027"; } .glyphicon-inbox:before { content: "\\e028"; } .glyphicon-play-circle:before { content: "\\e029"; } .glyphicon-repeat:before { content: "\\e030"; } .glyphicon-refresh:before { content: "\\e031"; } .glyphicon-list-alt:before { content: "\\e032"; } .glyphicon-lock:before { content: "\\e033"; } .glyphicon-flag:before { content: "\\e034"; } .glyphicon-headphones:before { content: "\\e035"; } .glyphicon-volume-off:before { content: "\\e036"; } .glyphicon-volume-down:before { content: "\\e037"; } .glyphicon-volume-up:before { content: "\\e038"; } .glyphicon-qrcode:before { content: "\\e039"; } .glyphicon-barcode:before { content: "\\e040"; } .glyphicon-tag:before { content: "\\e041"; } .glyphicon-tags:before { content: "\\e042"; } .glyphicon-book:before { content: "\\e043"; } .glyphicon-bookmark:before { content: "\\e044"; } .glyphicon-print:before { content: "\\e045"; } .glyphicon-camera:before { content: "\\e046"; } .glyphicon-font:before { content: "\\e047"; } .glyphicon-bold:before { content: "\\e048"; } .glyphicon-italic:before { content: "\\e049"; } .glyphicon-text-height:before { content: "\\e050"; } .glyphicon-text-width:before { content: "\\e051"; } .glyphicon-align-left:before { content: "\\e052"; } .glyphicon-align-center:before { content: "\\e053"; } .glyphicon-align-right:before { content: "\\e054"; } .glyphicon-align-justify:before { content: "\\e055"; } .glyphicon-list:before { content: "\\e056"; } .glyphicon-indent-left:before { content: "\\e057"; } .glyphicon-indent-right:before { content: "\\e058"; } .glyphicon-facetime-video:before { content: "\\e059"; } .glyphicon-picture:before { content: "\\e060"; } .glyphicon-map-marker:before { content: "\\e062"; } .glyphicon-adjust:before { content: "\\e063"; } .glyphicon-tint:before { content: "\\e064"; } .glyphicon-edit:before { content: "\\e065"; } .glyphicon-share:before { content: "\\e066"; } .glyphicon-check:before { content: "\\e067"; } .glyphicon-move:before { content: "\\e068"; } .glyphicon-step-backward:before { content: "\\e069"; } .glyphicon-fast-backward:before { content: "\\e070"; } .glyphicon-backward:before { content: "\\e071"; } .glyphicon-play:before { content: "\\e072"; } .glyphicon-pause:before { content: "\\e073"; } .glyphicon-stop:before { content: "\\e074"; } .glyphicon-forward:before { content: "\\e075"; } .glyphicon-fast-forward:before { content: "\\e076"; } .glyphicon-step-forward:before { content: "\\e077"; } .glyphicon-eject:before { content: "\\e078"; } .glyphicon-chevron-left:before { content: "\\e079"; } .glyphicon-chevron-right:before { content: "\\e080"; } .glyphicon-plus-sign:before { content: "\\e081"; } .glyphicon-minus-sign:before { content: "\\e082"; } .glyphicon-remove-sign:before { content: "\\e083"; } .glyphicon-ok-sign:before { content: "\\e084"; } .glyphicon-question-sign:before { content: "\\e085"; } .glyphicon-info-sign:before { content: "\\e086"; } .glyphicon-screenshot:before { content: "\\e087"; } .glyphicon-remove-circle:before { content: "\\e088"; } .glyphicon-ok-circle:before { content: "\\e089"; } .glyphicon-ban-circle:before { content: "\\e090"; } .glyphicon-arrow-left:before { content: "\\e091"; } .glyphicon-arrow-right:before { content: "\\e092"; } .glyphicon-arrow-up:before { content: "\\e093"; } .glyphicon-arrow-down:before { content: "\\e094"; } .glyphicon-share-alt:before { content: "\\e095"; } .glyphicon-resize-full:before { content: "\\e096"; } .glyphicon-resize-small:before { content: "\\e097"; } .glyphicon-exclamation-sign:before { content: "\\e101"; } .glyphicon-gift:before { content: "\\e102"; } .glyphicon-leaf:before { content: "\\e103"; } .glyphicon-fire:before { content: "\\e104"; } .glyphicon-eye-open:before { content: "\\e105"; } .glyphicon-eye-close:before { content: "\\e106"; } .glyphicon-warning-sign:before { content: "\\e107"; } .glyphicon-plane:before { content: "\\e108"; } .glyphicon-calendar:before { content: "\\e109"; } .glyphicon-random:before { content: "\\e110"; } .glyphicon-comment:before { content: "\\e111"; } .glyphicon-magnet:before { content: "\\e112"; } .glyphicon-chevron-up:before { content: "\\e113"; } .glyphicon-chevron-down:before { content: "\\e114"; } .glyphicon-retweet:before { content: "\\e115"; } .glyphicon-shopping-cart:before { content: "\\e116"; } .glyphicon-folder-close:before { content: "\\e117"; } .glyphicon-folder-open:before { content: "\\e118"; } .glyphicon-resize-vertical:before { content: "\\e119"; } .glyphicon-resize-horizontal:before { content: "\\e120"; } .glyphicon-hdd:before { content: "\\e121"; } .glyphicon-bullhorn:before { content: "\\e122"; } .glyphicon-bell:before { content: "\\e123"; } .glyphicon-certificate:before { content: "\\e124"; } .glyphicon-thumbs-up:before { content: "\\e125"; } .glyphicon-thumbs-down:before { content: "\\e126"; } .glyphicon-hand-right:before { content: "\\e127"; } .glyphicon-hand-left:before { content: "\\e128"; } .glyphicon-hand-up:before { content: "\\e129"; } .glyphicon-hand-down:before { content: "\\e130"; } .glyphicon-circle-arrow-right:before { content: "\\e131"; } .glyphicon-circle-arrow-left:before { content: "\\e132"; } .glyphicon-circle-arrow-up:before { content: "\\e133"; } .glyphicon-circle-arrow-down:before { content: "\\e134"; } .glyphicon-globe:before { content: "\\e135"; } .glyphicon-wrench:before { content: "\\e136"; } .glyphicon-tasks:before { content: "\\e137"; } .glyphicon-filter:before { content: "\\e138"; } .glyphicon-briefcase:before { content: "\\e139"; } .glyphicon-fullscreen:before { content: "\\e140"; } .glyphicon-dashboard:before { content: "\\e141"; } .glyphicon-paperclip:before { content: "\\e142"; } .glyphicon-heart-empty:before { content: "\\e143"; } .glyphicon-link:before { content: "\\e144"; } .glyphicon-phone:before { content: "\\e145"; } .glyphicon-pushpin:before { content: "\\e146"; } .glyphicon-usd:before { content: "\\e148"; } .glyphicon-gbp:before { content: "\\e149"; } .glyphicon-sort:before { content: "\\e150"; } .glyphicon-sort-by-alphabet:before { content: "\\e151"; } .glyphicon-sort-by-alphabet-alt:before { content: "\\e152"; } .glyphicon-sort-by-order:before { content: "\\e153"; } .glyphicon-sort-by-order-alt:before { content: "\\e154"; } .glyphicon-sort-by-attributes:before { content: "\\e155"; } .glyphicon-sort-by-attributes-alt:before { content: "\\e156"; } .glyphicon-unchecked:before { content: "\\e157"; } .glyphicon-expand:before { content: "\\e158"; } .glyphicon-collapse-down:before { content: "\\e159"; } .glyphicon-collapse-up:before { content: "\\e160"; } .glyphicon-log-in:before { content: "\\e161"; } .glyphicon-flash:before { content: "\\e162"; } .glyphicon-log-out:before { content: "\\e163"; } .glyphicon-new-window:before { content: "\\e164"; } .glyphicon-record:before { content: "\\e165"; } .glyphicon-save:before { content: "\\e166"; } .glyphicon-open:before { content: "\\e167"; } .glyphicon-saved:before { content: "\\e168"; } .glyphicon-import:before { content: "\\e169"; } .glyphicon-export:before { content: "\\e170"; } .glyphicon-send:before { content: "\\e171"; } .glyphicon-floppy-disk:before { content: "\\e172"; } .glyphicon-floppy-saved:before { content: "\\e173"; } .glyphicon-floppy-remove:before { content: "\\e174"; } .glyphicon-floppy-save:before { content: "\\e175"; } .glyphicon-floppy-open:before { content: "\\e176"; } .glyphicon-credit-card:before { content: "\\e177"; } .glyphicon-transfer:before { content: "\\e178"; } .glyphicon-cutlery:before { content: "\\e179"; } .glyphicon-header:before { content: "\\e180"; } .glyphicon-compressed:before { content: "\\e181"; } .glyphicon-earphone:before { content: "\\e182"; } .glyphicon-phone-alt:before { content: "\\e183"; } .glyphicon-tower:before { content: "\\e184"; } .glyphicon-stats:before { content: "\\e185"; } .glyphicon-sd-video:before { content: "\\e186"; } .glyphicon-hd-video:before { content: "\\e187"; } .glyphicon-subtitles:before { content: "\\e188"; } .glyphicon-sound-stereo:before { content: "\\e189"; } .glyphicon-sound-dolby:before { content: "\\e190"; } .glyphicon-sound-5-1:before { content: "\\e191"; } .glyphicon-sound-6-1:before { content: "\\e192"; } .glyphicon-sound-7-1:before { content: "\\e193"; } .glyphicon-copyright-mark:before { content: "\\e194"; } .glyphicon-registration-mark:before { content: "\\e195"; } .glyphicon-cloud-download:before { content: "\\e197"; } .glyphicon-cloud-upload:before { content: "\\e198"; } .glyphicon-tree-conifer:before { content: "\\e199"; } .glyphicon-tree-deciduous:before { content: "\\e200"; } .glyphicon-cd:before { content: "\\e201"; } .glyphicon-save-file:before { content: "\\e202"; } .glyphicon-open-file:before { content: "\\e203"; } .glyphicon-level-up:before { content: "\\e204"; } .glyphicon-copy:before { content: "\\e205"; } .glyphicon-paste:before { content: "\\e206"; } .glyphicon-alert:before { content: "\\e209"; } .glyphicon-equalizer:before { content: "\\e210"; } .glyphicon-king:before { content: "\\e211"; } .glyphicon-queen:before { content: "\\e212"; } .glyphicon-pawn:before { content: "\\e213"; } .glyphicon-bishop:before { content: "\\e214"; } .glyphicon-knight:before { content: "\\e215"; } .glyphicon-baby-formula:before { content: "\\e216"; } .glyphicon-tent:before { content: "\\26fa"; } .glyphicon-blackboard:before { content: "\\e218"; } .glyphicon-bed:before { content: "\\e219"; } .glyphicon-apple:before { content: "\\f8ff"; } .glyphicon-erase:before { content: "\\e221"; } .glyphicon-hourglass:before { content: "\\231b"; } .glyphicon-lamp:before { content: "\\e223"; } .glyphicon-duplicate:before { content: "\\e224"; } .glyphicon-piggy-bank:before { content: "\\e225"; } .glyphicon-scissors:before { content: "\\e226"; } .glyphicon-bitcoin:before { content: "\\e227"; } .glyphicon-btc:before { content: "\\e227"; } .glyphicon-xbt:before { content: "\\e227"; } .glyphicon-yen:before { content: "\\00a5"; } .glyphicon-jpy:before { content: "\\00a5"; } .glyphicon-ruble:before { content: "\\20bd"; } .glyphicon-rub:before { content: "\\20bd"; } .glyphicon-scale:before { content: "\\e230"; } .glyphicon-ice-lolly:before { content: "\\e231"; } .glyphicon-ice-lolly-tasted:before { content: "\\e232"; } .glyphicon-education:before { content: "\\e233"; } .glyphicon-option-horizontal:before { content: "\\e234"; } .glyphicon-option-vertical:before { content: "\\e235"; } .glyphicon-menu-hamburger:before { content: "\\e236"; } .glyphicon-modal-window:before { content: "\\e237"; } .glyphicon-oil:before { content: "\\e238"; } .glyphicon-grain:before { content: "\\e239"; } .glyphicon-sunglasses:before { content: "\\e240"; } .glyphicon-text-size:before { content: "\\e241"; } .glyphicon-text-color:before { content: "\\e242"; } .glyphicon-text-background:before { content: "\\e243"; } .glyphicon-object-align-top:before { content: "\\e244"; } .glyphicon-object-align-bottom:before { content: "\\e245"; } .glyphicon-object-align-horizontal:before { content: "\\e246"; } .glyphicon-object-align-left:before { content: "\\e247"; } .glyphicon-object-align-vertical:before { content: "\\e248"; } .glyphicon-object-align-right:before { content: "\\e249"; } .glyphicon-triangle-right:before { content: "\\e250"; } .glyphicon-triangle-left:before { content: "\\e251"; } .glyphicon-triangle-bottom:before { content: "\\e252"; } .glyphicon-triangle-top:before { content: "\\e253"; } .glyphicon-console:before { content: "\\e254"; } .glyphicon-superscript:before { content: "\\e255"; } .glyphicon-subscript:before { content: "\\e256"; } .glyphicon-menu-left:before { content: "\\e257"; } .glyphicon-menu-right:before { content: "\\e258"; } .glyphicon-menu-down:before { content: "\\e259"; } .glyphicon-menu-up:before { content: "\\e260"; } \* { -webkit-box-sizing: border-box; -moz-box-sizing: border-box; box-sizing: border-box; } \*:before, \*:after { -webkit-box-sizing: border-box; -moz-box-sizing: border-box; box-sizing: border-box; } html { font-size: 10px; -webkit-tap-highlight-color: rgba(0, 0, 0, 0); } body { font-family: "Helvetica Neue", Helvetica, Arial, sans-serif; font-size: 13px; line-height: 1.42857143; color: #000; background-color: #fff; } input, button, select, textarea { font-family: inherit; font-size: inherit; line-height: inherit; } a { color: #337ab7; text-decoration: none; } a:hover, a:focus { color: #23527c; text-decoration: underline; } a:focus { outline: 5px auto -webkit-focus-ring-color; outline-offset: -2px; } figure { margin: 0; } img { vertical-align: middle; } .img-responsive, .thumbnail > img, .thumbnail a > img, .carousel-inner > .item > img, .carousel-inner > .item > a > img { display: block; max-width: 100%; height: auto; } .img-rounded { border-radius: 3px; } .img-thumbnail { padding: 4px; line-height: 1.42857143; background-color: #fff; border: 1px solid #ddd; border-radius: 2px; -webkit-transition: all 0.2s ease-in-out; -o-transition: all 0.2s ease-in-out; transition: all 0.2s ease-in-out; display: inline-block; max-width: 100%; height: auto; } .img-circle { border-radius: 50%; } hr { margin-top: 18px; margin-bottom: 18px; border: 0; border-top: 1px solid #eeeeee; } .sr-only { position: absolute; width: 1px; height: 1px; margin: -1px; padding: 0; overflow: hidden; clip: rect(0, 0, 0, 0); border: 0; } .sr-only-focusable:active, .sr-only-focusable:focus { position: static; width: auto; height: auto; margin: 0; overflow: visible; clip: auto; } \[role="button"\] { cursor: pointer; } h1, h2, h3, h4, h5, h6, .h1, .h2, .h3, .h4, .h5, .h6 { font-family: inherit; font-weight: 500; line-height: 1.1; color: inherit; } h1 small, h2 small, h3 small, h4 small, h5 small, h6 small, .h1 small, .h2 small, .h3 small, .h4 small, .h5 small, .h6 small, h1 .small, h2 .small, h3 .small, h4 .small, h5 .small, h6 .small, .h1 .small, .h2 .small, .h3 .small, .h4 .small, .h5 .small, .h6 .small { font-weight: normal; line-height: 1; color: #777777; } h1, .h1, h2, .h2, h3, .h3 { margin-top: 18px; margin-bottom: 9px; } h1 small, .h1 small, h2 small, .h2 small, h3 small, .h3 small, h1 .small, .h1 .small, h2 .small, .h2 .small, h3 .small, .h3 .small { font-size: 65%; } h4, .h4, h5, .h5, h6, .h6 { margin-top: 9px; margin-bottom: 9px; } h4 small, .h4 small, h5 small, .h5 small, h6 small, .h6 small, h4 .small, .h4 .small, h5 .small, .h5 .small, h6 .small, .h6 .small { font-size: 75%; } h1, .h1 { font-size: 33px; } h2, .h2 { font-size: 27px; } h3, .h3 { font-size: 23px; } h4, .h4 { font-size: 17px; } h5, .h5 { font-size: 13px; } h6, .h6 { font-size: 12px; } p { margin: 0 0 9px; } .lead { margin-bottom: 18px; font-size: 14px; font-weight: 300; line-height: 1.4; } @media (min-width: 768px) { .lead { font-size: 19.5px; } } small, .small { font-size: 92%; } mark, .mark { background-color: #fcf8e3; padding: .2em; } .text-left { text-align: left; } .text-right { text-align: right; } .text-center { text-align: center; } .text-justify { text-align: justify; } .text-nowrap { white-space: nowrap; } .text-lowercase { text-transform: lowercase; } .text-uppercase { text-transform: uppercase; } .text-capitalize { text-transform: capitalize; } .text-muted { color: #777777; } .text-primary { color: #337ab7; } a.text-primary:hover, a.text-primary:focus { color: #286090; } .text-success { color: #3c763d; } a.text-success:hover, a.text-success:focus { color: #2b542c; } .text-info { color: #31708f; } a.text-info:hover, a.text-info:focus { color: #245269; } .text-warning { color: #8a6d3b; } a.text-warning:hover, a.text-warning:focus { color: #66512c; } .text-danger { color: #a94442; } a.text-danger:hover, a.text-danger:focus { color: #843534; } .bg-primary { color: #fff; background-color: #337ab7; } a.bg-primary:hover, a.bg-primary:focus { background-color: #286090; } .bg-success { background-color: #dff0d8; } a.bg-success:hover, a.bg-success:focus { background-color: #c1e2b3; } .bg-info { background-color: #d9edf7; } a.bg-info:hover, a.bg-info:focus { background-color: #afd9ee; } .bg-warning { background-color: #fcf8e3; } a.bg-warning:hover, a.bg-warning:focus { background-color: #f7ecb5; } .bg-danger { background-color: #f2dede; } a.bg-danger:hover, a.bg-danger:focus { background-color: #e4b9b9; } .page-header { padding-bottom: 8px; margin: 36px 0 18px; border-bottom: 1px solid #eeeeee; } ul, ol { margin-top: 0; margin-bottom: 9px; } ul ul, ol ul, ul ol, ol ol { margin-bottom: 0; } .list-unstyled { padding-left: 0; list-style: none; } .list-inline { padding-left: 0; list-style: none; margin-left: -5px; } .list-inline > li { display: inline-block; padding-left: 5px; padding-right: 5px; } dl { margin-top: 0; margin-bottom: 18px; } dt, dd { line-height: 1.42857143; } dt { font-weight: bold; } dd { margin-left: 0; } @media (min-width: 541px) { .dl-horizontal dt { float: left; width: 160px; clear: left; text-align: right; overflow: hidden; text-overflow: ellipsis; white-space: nowrap; } .dl-horizontal dd { margin-left: 180px; } } abbr\[title\], abbr\[data-original-title\] { cursor: help; border-bottom: 1px dotted #777777; } .initialism { font-size: 90%; text-transform: uppercase; } blockquote { padding: 9px 18px; margin: 0 0 18px; font-size: inherit; border-left: 5px solid #eeeeee; } blockquote p:last-child, blockquote ul:last-child, blockquote ol:last-child { margin-bottom: 0; } blockquote footer, blockquote small, blockquote .small { display: block; font-size: 80%; line-height: 1.42857143; color: #777777; } blockquote footer:before, blockquote small:before, blockquote .small:before { content: '\\2014 \\00A0'; } .blockquote-reverse, blockquote.pull-right { padding-right: 15px; padding-left: 0; border-right: 5px solid #eeeeee; border-left: 0; text-align: right; } .blockquote-reverse footer:before, blockquote.pull-right footer:before, .blockquote-reverse small:before, blockquote.pull-right small:before, .blockquote-reverse .small:before, blockquote.pull-right .small:before { content: ''; } .blockquote-reverse footer:after, blockquote.pull-right footer:after, .blockquote-reverse small:after, blockquote.pull-right small:after, .blockquote-reverse .small:after, blockquote.pull-right .small:after { content: '\\00A0 \\2014'; } address { margin-bottom: 18px; font-style: normal; line-height: 1.42857143; } code, kbd, pre, samp { font-family: monospace; } code { padding: 2px 4px; font-size: 90%; color: #c7254e; background-color: #f9f2f4; border-radius: 2px; } kbd { padding: 2px 4px; font-size: 90%; color: #888; background-color: transparent; border-radius: 1px; box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.25); } kbd kbd { padding: 0; font-size: 100%; font-weight: bold; box-shadow: none; } pre { display: block; padding: 8.5px; margin: 0 0 9px; font-size: 12px; line-height: 1.42857143; word-break: break-all; word-wrap: break-word; color: #333333; background-color: #f5f5f5; border: 1px solid #ccc; border-radius: 2px; } pre code { padding: 0; font-size: inherit; color: inherit; white-space: pre-wrap; background-color: transparent; border-radius: 0; } .pre-scrollable { max-height: 340px; overflow-y: scroll; } .container { margin-right: auto; margin-left: auto; padding-left: 0px; padding-right: 0px; } @media (min-width: 768px) { .container { width: 768px; } } @media (min-width: 992px) { .container { width: 940px; } } @media (min-width: 1200px) { .container { width: 1140px; } } .container-fluid { margin-right: auto; margin-left: auto; padding-left: 0px; padding-right: 0px; } .row { margin-left: 0px; margin-right: 0px; } .col-xs-1, .col-sm-1, .col-md-1, .col-lg-1, .col-xs-2, .col-sm-2, .col-md-2, .col-lg-2, .col-xs-3, .col-sm-3, .col-md-3, .col-lg-3, .col-xs-4, .col-sm-4, .col-md-4, .col-lg-4, .col-xs-5, .col-sm-5, .col-md-5, .col-lg-5, .col-xs-6, .col-sm-6, .col-md-6, .col-lg-6, .col-xs-7, .col-sm-7, .col-md-7, .col-lg-7, .col-xs-8, .col-sm-8, .col-md-8, .col-lg-8, .col-xs-9, .col-sm-9, .col-md-9, .col-lg-9, .col-xs-10, .col-sm-10, .col-md-10, .col-lg-10, .col-xs-11, .col-sm-11, .col-md-11, .col-lg-11, .col-xs-12, .col-sm-12, .col-md-12, .col-lg-12 { position: relative; min-height: 1px; padding-left: 0px; padding-right: 0px; } .col-xs-1, .col-xs-2, .col-xs-3, .col-xs-4, .col-xs-5, .col-xs-6, .col-xs-7, .col-xs-8, .col-xs-9, .col-xs-10, .col-xs-11, .col-xs-12 { float: left; } .col-xs-12 { width: 100%; } .col-xs-11 { width: 91.66666667%; } .col-xs-10 { width: 83.33333333%; } .col-xs-9 { width: 75%; } .col-xs-8 { width: 66.66666667%; } .col-xs-7 { width: 58.33333333%; } .col-xs-6 { width: 50%; } .col-xs-5 { width: 41.66666667%; } .col-xs-4 { width: 33.33333333%; } .col-xs-3 { width: 25%; } .col-xs-2 { width: 16.66666667%; } .col-xs-1 { width: 8.33333333%; } .col-xs-pull-12 { right: 100%; } .col-xs-pull-11 { right: 91.66666667%; } .col-xs-pull-10 { right: 83.33333333%; } .col-xs-pull-9 { right: 75%; } .col-xs-pull-8 { right: 66.66666667%; } .col-xs-pull-7 { right: 58.33333333%; } .col-xs-pull-6 { right: 50%; } .col-xs-pull-5 { right: 41.66666667%; } .col-xs-pull-4 { right: 33.33333333%; } .col-xs-pull-3 { right: 25%; } .col-xs-pull-2 { right: 16.66666667%; } .col-xs-pull-1 { right: 8.33333333%; } .col-xs-pull-0 { right: auto; } .col-xs-push-12 { left: 100%; } .col-xs-push-11 { left: 91.66666667%; } .col-xs-push-10 { left: 83.33333333%; } .col-xs-push-9 { left: 75%; } .col-xs-push-8 { left: 66.66666667%; } .col-xs-push-7 { left: 58.33333333%; } .col-xs-push-6 { left: 50%; } .col-xs-push-5 { left: 41.66666667%; } .col-xs-push-4 { left: 33.33333333%; } .col-xs-push-3 { left: 25%; } .col-xs-push-2 { left: 16.66666667%; } .col-xs-push-1 { left: 8.33333333%; } .col-xs-push-0 { left: auto; } .col-xs-offset-12 { margin-left: 100%; } .col-xs-offset-11 { margin-left: 91.66666667%; } .col-xs-offset-10 { margin-left: 83.33333333%; } .col-xs-offset-9 { margin-left: 75%; } .col-xs-offset-8 { margin-left: 66.66666667%; } .col-xs-offset-7 { margin-left: 58.33333333%; } .col-xs-offset-6 { margin-left: 50%; } .col-xs-offset-5 { margin-left: 41.66666667%; } .col-xs-offset-4 { margin-left: 33.33333333%; } .col-xs-offset-3 { margin-left: 25%; } .col-xs-offset-2 { margin-left: 16.66666667%; } .col-xs-offset-1 { margin-left: 8.33333333%; } .col-xs-offset-0 { margin-left: 0%; } @media (min-width: 768px) { .col-sm-1, .col-sm-2, .col-sm-3, .col-sm-4, .col-sm-5, .col-sm-6, .col-sm-7, .col-sm-8, .col-sm-9, .col-sm-10, .col-sm-11, .col-sm-12 { float: left; } .col-sm-12 { width: 100%; } .col-sm-11 { width: 91.66666667%; } .col-sm-10 { width: 83.33333333%; } .col-sm-9 { width: 75%; } .col-sm-8 { width: 66.66666667%; } .col-sm-7 { width: 58.33333333%; } .col-sm-6 { width: 50%; } .col-sm-5 { width: 41.66666667%; } .col-sm-4 { width: 33.33333333%; } .col-sm-3 { width: 25%; } .col-sm-2 { width: 16.66666667%; } .col-sm-1 { width: 8.33333333%; } .col-sm-pull-12 { right: 100%; } .col-sm-pull-11 { right: 91.66666667%; } .col-sm-pull-10 { right: 83.33333333%; } .col-sm-pull-9 { right: 75%; } .col-sm-pull-8 { right: 66.66666667%; } .col-sm-pull-7 { right: 58.33333333%; } .col-sm-pull-6 { right: 50%; } .col-sm-pull-5 { right: 41.66666667%; } .col-sm-pull-4 { right: 33.33333333%; } .col-sm-pull-3 { right: 25%; } .col-sm-pull-2 { right: 16.66666667%; } .col-sm-pull-1 { right: 8.33333333%; } .col-sm-pull-0 { right: auto; } .col-sm-push-12 { left: 100%; } .col-sm-push-11 { left: 91.66666667%; } .col-sm-push-10 { left: 83.33333333%; } .col-sm-push-9 { left: 75%; } .col-sm-push-8 { left: 66.66666667%; } .col-sm-push-7 { left: 58.33333333%; } .col-sm-push-6 { left: 50%; } .col-sm-push-5 { left: 41.66666667%; } .col-sm-push-4 { left: 33.33333333%; } .col-sm-push-3 { left: 25%; } .col-sm-push-2 { left: 16.66666667%; } .col-sm-push-1 { left: 8.33333333%; } .col-sm-push-0 { left: auto; } .col-sm-offset-12 { margin-left: 100%; } .col-sm-offset-11 { margin-left: 91.66666667%; } .col-sm-offset-10 { margin-left: 83.33333333%; } .col-sm-offset-9 { margin-left: 75%; } .col-sm-offset-8 { margin-left: 66.66666667%; } .col-sm-offset-7 { margin-left: 58.33333333%; } .col-sm-offset-6 { margin-left: 50%; } .col-sm-offset-5 { margin-left: 41.66666667%; } .col-sm-offset-4 { margin-left: 33.33333333%; } .col-sm-offset-3 { margin-left: 25%; } .col-sm-offset-2 { margin-left: 16.66666667%; } .col-sm-offset-1 { margin-left: 8.33333333%; } .col-sm-offset-0 { margin-left: 0%; } } @media (min-width: 992px) { .col-md-1, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-md-6, .col-md-7, .col-md-8, .col-md-9, .col-md-10, .col-md-11, .col-md-12 { float: left; } .col-md-12 { width: 100%; } .col-md-11 { width: 91.66666667%; } .col-md-10 { width: 83.33333333%; } .col-md-9 { width: 75%; } .col-md-8 { width: 66.66666667%; } .col-md-7 { width: 58.33333333%; } .col-md-6 { width: 50%; } .col-md-5 { width: 41.66666667%; } .col-md-4 { width: 33.33333333%; } .col-md-3 { width: 25%; } .col-md-2 { width: 16.66666667%; } .col-md-1 { width: 8.33333333%; } .col-md-pull-12 { right: 100%; } .col-md-pull-11 { right: 91.66666667%; } .col-md-pull-10 { right: 83.33333333%; } .col-md-pull-9 { right: 75%; } .col-md-pull-8 { right: 66.66666667%; } .col-md-pull-7 { right: 58.33333333%; } .col-md-pull-6 { right: 50%; } .col-md-pull-5 { right: 41.66666667%; } .col-md-pull-4 { right: 33.33333333%; } .col-md-pull-3 { right: 25%; } .col-md-pull-2 { right: 16.66666667%; } .col-md-pull-1 { right: 8.33333333%; } .col-md-pull-0 { right: auto; } .col-md-push-12 { left: 100%; } .col-md-push-11 { left: 91.66666667%; } .col-md-push-10 { left: 83.33333333%; } .col-md-push-9 { left: 75%; } .col-md-push-8 { left: 66.66666667%; } .col-md-push-7 { left: 58.33333333%; } .col-md-push-6 { left: 50%; } .col-md-push-5 { left: 41.66666667%; } .col-md-push-4 { left: 33.33333333%; } .col-md-push-3 { left: 25%; } .col-md-push-2 { left: 16.66666667%; } .col-md-push-1 { left: 8.33333333%; } .col-md-push-0 { left: auto; } .col-md-offset-12 { margin-left: 100%; } .col-md-offset-11 { margin-left: 91.66666667%; } .col-md-offset-10 { margin-left: 83.33333333%; } .col-md-offset-9 { margin-left: 75%; } .col-md-offset-8 { margin-left: 66.66666667%; } .col-md-offset-7 { margin-left: 58.33333333%; } .col-md-offset-6 { margin-left: 50%; } .col-md-offset-5 { margin-left: 41.66666667%; } .col-md-offset-4 { margin-left: 33.33333333%; } .col-md-offset-3 { margin-left: 25%; } .col-md-offset-2 { margin-left: 16.66666667%; } .col-md-offset-1 { margin-left: 8.33333333%; } .col-md-offset-0 { margin-left: 0%; } } @media (min-width: 1200px) { .col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-10, .col-lg-11, .col-lg-12 { float: left; } .col-lg-12 { width: 100%; } .col-lg-11 { width: 91.66666667%; } .col-lg-10 { width: 83.33333333%; } .col-lg-9 { width: 75%; } .col-lg-8 { width: 66.66666667%; } .col-lg-7 { width: 58.33333333%; } .col-lg-6 { width: 50%; } .col-lg-5 { width: 41.66666667%; } .col-lg-4 { width: 33.33333333%; } .col-lg-3 { width: 25%; } .col-lg-2 { width: 16.66666667%; } .col-lg-1 { width: 8.33333333%; } .col-lg-pull-12 { right: 100%; } .col-lg-pull-11 { right: 91.66666667%; } .col-lg-pull-10 { right: 83.33333333%; } .col-lg-pull-9 { right: 75%; } .col-lg-pull-8 { right: 66.66666667%; } .col-lg-pull-7 { right: 58.33333333%; } .col-lg-pull-6 { right: 50%; } .col-lg-pull-5 { right: 41.66666667%; } .col-lg-pull-4 { right: 33.33333333%; } .col-lg-pull-3 { right: 25%; } .col-lg-pull-2 { right: 16.66666667%; } .col-lg-pull-1 { right: 8.33333333%; } .col-lg-pull-0 { right: auto; } .col-lg-push-12 { left: 100%; } .col-lg-push-11 { left: 91.66666667%; } .col-lg-push-10 { left: 83.33333333%; } .col-lg-push-9 { left: 75%; } .col-lg-push-8 { left: 66.66666667%; } .col-lg-push-7 { left: 58.33333333%; } .col-lg-push-6 { left: 50%; } .col-lg-push-5 { left: 41.66666667%; } .col-lg-push-4 { left: 33.33333333%; } .col-lg-push-3 { left: 25%; } .col-lg-push-2 { left: 16.66666667%; } .col-lg-push-1 { left: 8.33333333%; } .col-lg-push-0 { left: auto; } .col-lg-offset-12 { margin-left: 100%; } .col-lg-offset-11 { margin-left: 91.66666667%; } .col-lg-offset-10 { margin-left: 83.33333333%; } .col-lg-offset-9 { margin-left: 75%; } .col-lg-offset-8 { margin-left: 66.66666667%; } .col-lg-offset-7 { margin-left: 58.33333333%; } .col-lg-offset-6 { margin-left: 50%; } .col-lg-offset-5 { margin-left: 41.66666667%; } .col-lg-offset-4 { margin-left: 33.33333333%; } .col-lg-offset-3 { margin-left: 25%; } .col-lg-offset-2 { margin-left: 16.66666667%; } .col-lg-offset-1 { margin-left: 8.33333333%; } .col-lg-offset-0 { margin-left: 0%; } } table { background-color: transparent; } caption { padding-top: 8px; padding-bottom: 8px; color: #777777; text-align: left; } th { text-align: left; } .table { width: 100%; max-width: 100%; margin-bottom: 18px; } .table > thead > tr > th, .table > tbody > tr > th, .table > tfoot > tr > th, .table > thead > tr > td, .table > tbody > tr > td, .table > tfoot > tr > td { padding: 8px; line-height: 1.42857143; vertical-align: top; border-top: 1px solid #ddd; } .table > thead > tr > th { vertical-align: bottom; border-bottom: 2px solid #ddd; } .table > caption + thead > tr:first-child > th, .table > colgroup + thead > tr:first-child > th, .table > thead:first-child > tr:first-child > th, .table > caption + thead > tr:first-child > td, .table > colgroup + thead > tr:first-child > td, .table > thead:first-child > tr:first-child > td { border-top: 0; } .table > tbody + tbody { border-top: 2px solid #ddd; } .table .table { background-color: #fff; } .table-condensed > thead > tr > th, .table-condensed > tbody > tr > th, .table-condensed > tfoot > tr > th, .table-condensed > thead > tr > td, .table-condensed > tbody > tr > td, .table-condensed > tfoot > tr > td { padding: 5px; } .table-bordered { border: 1px solid #ddd; } .table-bordered > thead > tr > th, .table-bordered > tbody > tr > th, .table-bordered > tfoot > tr > th, .table-bordered > thead > tr > td, .table-bordered > tbody > tr > td, .table-bordered > tfoot > tr > td { border: 1px solid #ddd; } .table-bordered > thead > tr > th, .table-bordered > thead > tr > td { border-bottom-width: 2px; } .table-striped > tbody > tr:nth-of-type(odd) { background-color: #f9f9f9; } .table-hover > tbody > tr:hover { background-color: #f5f5f5; } table col\[class\*="col-"\] { position: static; float: none; display: table-column; } table td\[class\*="col-"\], table th\[class\*="col-"\] { position: static; float: none; display: table-cell; } .table > thead > tr > td.active, .table > tbody > tr > td.active, .table > tfoot > tr > td.active, .table > thead > tr > th.active, .table > tbody > tr > th.active, .table > tfoot > tr > th.active, .table > thead > tr.active > td, .table > tbody > tr.active > td, .table > tfoot > tr.active > td, .table > thead > tr.active > th, .table > tbody > tr.active > th, .table > tfoot > tr.active > th { background-color: #f5f5f5; } .table-hover > tbody > tr > td.active:hover, .table-hover > tbody > tr > th.active:hover, .table-hover > tbody > tr.active:hover > td, .table-hover > tbody > tr:hover > .active, .table-hover > tbody > tr.active:hover > th { background-color: #e8e8e8; } .table > thead > tr > td.success, .table > tbody > tr > td.success, .table > tfoot > tr > td.success, .table > thead > tr > th.success, .table > tbody > tr > th.success, .table > tfoot > tr > th.success, .table > thead > tr.success > td, .table > tbody > tr.success > td, .table > tfoot > tr.success > td, .table > thead > tr.success > th, .table > tbody > tr.success > th, .table > tfoot > tr.success > th { background-color: #dff0d8; } .table-hover > tbody > tr > td.success:hover, .table-hover > tbody > tr > th.success:hover, .table-hover > tbody > tr.success:hover > td, .table-hover > tbody > tr:hover > .success, .table-hover > tbody > tr.success:hover > th { background-color: #d0e9c6; } .table > thead > tr > td.info, .table > tbody > tr > td.info, .table > tfoot > tr > td.info, .table > thead > tr > th.info, .table > tbody > tr > th.info, .table > tfoot > tr > th.info, .table > thead > tr.info > td, .table > tbody > tr.info > td, .table > tfoot > tr.info > td, .table > thead > tr.info > th, .table > tbody > tr.info > th, .table > tfoot > tr.info > th { background-color: #d9edf7; } .table-hover > tbody > tr > td.info:hover, .table-hover > tbody > tr > th.info:hover, .table-hover > tbody > tr.info:hover > td, .table-hover > tbody > tr:hover > .info, .table-hover > tbody > tr.info:hover > th { background-color: #c4e3f3; } .table > thead > tr > td.warning, .table > tbody > tr > td.warning, .table > tfoot > tr > td.warning, .table > thead > tr > th.warning, .table > tbody > tr > th.warning, .table > tfoot > tr > th.warning, .table > thead > tr.warning > td, .table > tbody > tr.warning > td, .table > tfoot > tr.warning > td, .table > thead > tr.warning > th, .table > tbody > tr.warning > th, .table > tfoot > tr.warning > th { background-color: #fcf8e3; } .table-hover > tbody > tr > td.warning:hover, .table-hover > tbody > tr > th.warning:hover, .table-hover > tbody > tr.warning:hover > td, .table-hover > tbody > tr:hover > .warning, .table-hover > tbody > tr.warning:hover > th { background-color: #faf2cc; } .table > thead > tr > td.danger, .table > tbody > tr > td.danger, .table > tfoot > tr > td.danger, .table > thead > tr > th.danger, .table > tbody > tr > th.danger, .table > tfoot > tr > th.danger, .table > thead > tr.danger > td, .table > tbody > tr.danger > td, .table > tfoot > tr.danger > td, .table > thead > tr.danger > th, .table > tbody > tr.danger > th, .table > tfoot > tr.danger > th { background-color: #f2dede; } .table-hover > tbody > tr > td.danger:hover, .table-hover > tbody > tr > th.danger:hover, .table-hover > tbody > tr.danger:hover > td, .table-hover > tbody > tr:hover > .danger, .table-hover > tbody > tr.danger:hover > th { background-color: #ebcccc; } .table-responsive { overflow-x: auto; min-height: 0.01%; } @media screen and (max-width: 767px) { .table-responsive { width: 100%; margin-bottom: 13.5px; overflow-y: hidden; -ms-overflow-style: -ms-autohiding-scrollbar; border: 1px solid #ddd; } .table-responsive > .table { margin-bottom: 0; } .table-responsive > .table > thead > tr > th, .table-responsive > .table > tbody > tr > th, .table-responsive > .table > tfoot > tr > th, .table-responsive > .table > thead > tr > td, .table-responsive > .table > tbody > tr > td, .table-responsive > .table > tfoot > tr > td { white-space: nowrap; } .table-responsive > .table-bordered { border: 0; } .table-responsive > .table-bordered > thead > tr > th:first-child, .table-responsive > .table-bordered > tbody > tr > th:first-child, .table-responsive > .table-bordered > tfoot > tr > th:first-child, .table-responsive > .table-bordered > thead > tr > td:first-child, .table-responsive > .table-bordered > tbody > tr > td:first-child, .table-responsive > .table-bordered > tfoot > tr > td:first-child { border-left: 0; } .table-responsive > .table-bordered > thead > tr > th:last-child, .table-responsive > .table-bordered > tbody > tr > th:last-child, .table-responsive > .table-bordered > tfoot > tr > th:last-child, .table-responsive > .table-bordered > thead > tr > td:last-child, .table-responsive > .table-bordered > tbody > tr > td:last-child, .table-responsive > .table-bordered > tfoot > tr > td:last-child { border-right: 0; } .table-responsive > .table-bordered > tbody > tr:last-child > th, .table-responsive > .table-bordered > tfoot > tr:last-child > th, .table-responsive > .table-bordered > tbody > tr:last-child > td, .table-responsive > .table-bordered > tfoot > tr:last-child > td { border-bottom: 0; } } fieldset { padding: 0; margin: 0; border: 0; min-width: 0; } legend { display: block; width: 100%; padding: 0; margin-bottom: 18px; font-size: 19.5px; line-height: inherit; color: #333333; border: 0; border-bottom: 1px solid #e5e5e5; } label { display: inline-block; max-width: 100%; margin-bottom: 5px; font-weight: bold; } input\[type="search"\] { -webkit-box-sizing: border-box; -moz-box-sizing: border-box; box-sizing: border-box; } input\[type="radio"\], input\[type="checkbox"\] { margin: 4px 0 0; margin-top: 1px \\9; line-height: normal; } input\[type="file"\] { display: block; } input\[type="range"\] { display: block; width: 100%; } select\[multiple\], select\[size\] { height: auto; } input\[type="file"\]:focus, input\[type="radio"\]:focus, input\[type="checkbox"\]:focus { outline: 5px auto -webkit-focus-ring-color; outline-offset: -2px; } output { display: block; padding-top: 7px; font-size: 13px; line-height: 1.42857143; color: #555555; } .form-control { display: block; width: 100%; height: 32px; padding: 6px 12px; font-size: 13px; line-height: 1.42857143; color: #555555; background-color: #fff; background-image: none; border: 1px solid #ccc; border-radius: 2px; -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075); box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075); -webkit-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s; -o-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s; transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s; } .form-control:focus { border-color: #66afe9; outline: 0; -webkit-box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6); box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6); } .form-control::-moz-placeholder { color: #999; opacity: 1; } .form-control:-ms-input-placeholder { color: #999; } .form-control::-webkit-input-placeholder { color: #999; } .form-control::-ms-expand { border: 0; background-color: transparent; } .form-control\[disabled\], .form-control\[readonly\], fieldset\[disabled\] .form-control { background-color: #eeeeee; opacity: 1; } .form-control\[disabled\], fieldset\[disabled\] .form-control { cursor: not-allowed; } textarea.form-control { height: auto; } input\[type="search"\] { -webkit-appearance: none; } @media screen and (-webkit-min-device-pixel-ratio: 0) { input\[type="date"\].form-control, input\[type="time"\].form-control, input\[type="datetime-local"\].form-control, input\[type="month"\].form-control { line-height: 32px; } input\[type="date"\].input-sm, input\[type="time"\].input-sm, input\[type="datetime-local"\].input-sm, input\[type="month"\].input-sm, .input-group-sm input\[type="date"\], .input-group-sm input\[type="time"\], .input-group-sm input\[type="datetime-local"\], .input-group-sm input\[type="month"\] { line-height: 30px; } input\[type="date"\].input-lg, input\[type="time"\].input-lg, input\[type="datetime-local"\].input-lg, input\[type="month"\].input-lg, .input-group-lg input\[type="date"\], .input-group-lg input\[type="time"\], .input-group-lg input\[type="datetime-local"\], .input-group-lg input\[type="month"\] { line-height: 45px; } } .form-group { margin-bottom: 15px; } .radio, .checkbox { position: relative; display: block; margin-top: 10px; margin-bottom: 10px; } .radio label, .checkbox label { min-height: 18px; padding-left: 20px; margin-bottom: 0; font-weight: normal; cursor: pointer; } .radio input\[type="radio"\], .radio-inline input\[type="radio"\], .checkbox input\[type="checkbox"\], .checkbox-inline input\[type="checkbox"\] { position: absolute; margin-left: -20px; margin-top: 4px \\9; } .radio + .radio, .checkbox + .checkbox { margin-top: -5px; } .radio-inline, .checkbox-inline { position: relative; display: inline-block; padding-left: 20px; margin-bottom: 0; vertical-align: middle; font-weight: normal; cursor: pointer; } .radio-inline + .radio-inline, .checkbox-inline + .checkbox-inline { margin-top: 0; margin-left: 10px; } input\[type="radio"\]\[disabled\], input\[type="checkbox"\]\[disabled\], input\[type="radio"\].disabled, input\[type="checkbox"\].disabled, fieldset\[disabled\] input\[type="radio"\], fieldset\[disabled\] input\[type="checkbox"\] { cursor: not-allowed; } .radio-inline.disabled, .checkbox-inline.disabled, fieldset\[disabled\] .radio-inline, fieldset\[disabled\] .checkbox-inline { cursor: not-allowed; } .radio.disabled label, .checkbox.disabled label, fieldset\[disabled\] .radio label, fieldset\[disabled\] .checkbox label { cursor: not-allowed; } .form-control-static { padding-top: 7px; padding-bottom: 7px; margin-bottom: 0; min-height: 31px; } .form-control-static.input-lg, .form-control-static.input-sm { padding-left: 0; padding-right: 0; } .input-sm { height: 30px; padding: 5px 10px; font-size: 12px; line-height: 1.5; border-radius: 1px; } select.input-sm { height: 30px; line-height: 30px; } textarea.input-sm, select\[multiple\].input-sm { height: auto; } .form-group-sm .form-control { height: 30px; padding: 5px 10px; font-size: 12px; line-height: 1.5; border-radius: 1px; } .form-group-sm select.form-control { height: 30px; line-height: 30px; } .form-group-sm textarea.form-control, .form-group-sm select\[multiple\].form-control { height: auto; } .form-group-sm .form-control-static { height: 30px; min-height: 30px; padding: 6px 10px; font-size: 12px; line-height: 1.5; } .input-lg { height: 45px; padding: 10px 16px; font-size: 17px; line-height: 1.3333333; border-radius: 3px; } select.input-lg { height: 45px; line-height: 45px; } textarea.input-lg, select\[multiple\].input-lg { height: auto; } .form-group-lg .form-control { height: 45px; padding: 10px 16px; font-size: 17px; line-height: 1.3333333; border-radius: 3px; } .form-group-lg select.form-control { height: 45px; line-height: 45px; } .form-group-lg textarea.form-control, .form-group-lg select\[multiple\].form-control { height: auto; } .form-group-lg .form-control-static { height: 45px; min-height: 35px; padding: 11px 16px; font-size: 17px; line-height: 1.3333333; } .has-feedback { position: relative; } .has-feedback .form-control { padding-right: 40px; } .form-control-feedback { position: absolute; top: 0; right: 0; z-index: 2; display: block; width: 32px; height: 32px; line-height: 32px; text-align: center; pointer-events: none; } .input-lg + .form-control-feedback, .input-group-lg + .form-control-feedback, .form-group-lg .form-control + .form-control-feedback { width: 45px; height: 45px; line-height: 45px; } .input-sm + .form-control-feedback, .input-group-sm + .form-control-feedback, .form-group-sm .form-control + .form-control-feedback { width: 30px; height: 30px; line-height: 30px; } .has-success .help-block, .has-success .control-label, .has-success .radio, .has-success .checkbox, .has-success .radio-inline, .has-success .checkbox-inline, .has-success.radio label, .has-success.checkbox label, .has-success.radio-inline label, .has-success.checkbox-inline label { color: #3c763d; } .has-success .form-control { border-color: #3c763d; -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075); box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075); } .has-success .form-control:focus { border-color: #2b542c; -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #67b168; box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #67b168; } .has-success .input-group-addon { color: #3c763d; border-color: #3c763d; background-color: #dff0d8; } .has-success .form-control-feedback { color: #3c763d; } .has-warning .help-block, .has-warning .control-label, .has-warning .radio, .has-warning .checkbox, .has-warning .radio-inline, .has-warning .checkbox-inline, .has-warning.radio label, .has-warning.checkbox label, .has-warning.radio-inline label, .has-warning.checkbox-inline label { color: #8a6d3b; } .has-warning .form-control { border-color: #8a6d3b; -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075); box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075); } .has-warning .form-control:focus { border-color: #66512c; -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #c0a16b; box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #c0a16b; } .has-warning .input-group-addon { color: #8a6d3b; border-color: #8a6d3b; background-color: #fcf8e3; } .has-warning .form-control-feedback { color: #8a6d3b; } .has-error .help-block, .has-error .control-label, .has-error .radio, .has-error .checkbox, .has-error .radio-inline, .has-error .checkbox-inline, .has-error.radio label, .has-error.checkbox label, .has-error.radio-inline label, .has-error.checkbox-inline label { color: #a94442; } .has-error .form-control { border-color: #a94442; -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075); box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075); } .has-error .form-control:focus { border-color: #843534; -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #ce8483; box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #ce8483; } .has-error .input-group-addon { color: #a94442; border-color: #a94442; background-color: #f2dede; } .has-error .form-control-feedback { color: #a94442; } .has-feedback label ~ .form-control-feedback { top: 23px; } .has-feedback label.sr-only ~ .form-control-feedback { top: 0; } .help-block { display: block; margin-top: 5px; margin-bottom: 10px; color: #404040; } @media (min-width: 768px) { .form-inline .form-group { display: inline-block; margin-bottom: 0; vertical-align: middle; } .form-inline .form-control { display: inline-block; width: auto; vertical-align: middle; } .form-inline .form-control-static { display: inline-block; } .form-inline .input-group { display: inline-table; vertical-align: middle; } .form-inline .input-group .input-group-addon, .form-inline .input-group .input-group-btn, .form-inline .input-group .form-control { width: auto; } .form-inline .input-group > .form-control { width: 100%; } .form-inline .control-label { margin-bottom: 0; vertical-align: middle; } .form-inline .radio, .form-inline .checkbox { display: inline-block; margin-top: 0; margin-bottom: 0; vertical-align: middle; } .form-inline .radio label, .form-inline .checkbox label { padding-left: 0; } .form-inline .radio input\[type="radio"\], .form-inline .checkbox input\[type="checkbox"\] { position: relative; margin-left: 0; } .form-inline .has-feedback .form-control-feedback { top: 0; } } .form-horizontal .radio, .form-horizontal .checkbox, .form-horizontal .radio-inline, .form-horizontal .checkbox-inline { margin-top: 0; margin-bottom: 0; padding-top: 7px; } .form-horizontal .radio, .form-horizontal .checkbox { min-height: 25px; } .form-horizontal .form-group { margin-left: 0px; margin-right: 0px; } @media (min-width: 768px) { .form-horizontal .control-label { text-align: right; margin-bottom: 0; padding-top: 7px; } } .form-horizontal .has-feedback .form-control-feedback { right: 0px; } @media (min-width: 768px) { .form-horizontal .form-group-lg .control-label { padding-top: 11px; font-size: 17px; } } @media (min-width: 768px) { .form-horizontal .form-group-sm .control-label { padding-top: 6px; font-size: 12px; } } .btn { display: inline-block; margin-bottom: 0; font-weight: normal; text-align: center; vertical-align: middle; touch-action: manipulation; cursor: pointer; background-image: none; border: 1px solid transparent; white-space: nowrap; padding: 6px 12px; font-size: 13px; line-height: 1.42857143; border-radius: 2px; -webkit-user-select: none; -moz-user-select: none; -ms-user-select: none; user-select: none; } .btn:focus, .btn:active:focus, .btn.active:focus, .btn.focus, .btn:active.focus, .btn.active.focus { outline: 5px auto -webkit-focus-ring-color; outline-offset: -2px; } .btn:hover, .btn:focus, .btn.focus { color: #333; text-decoration: none; } .btn:active, .btn.active { outline: 0; background-image: none; -webkit-box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125); box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125); } .btn.disabled, .btn\[disabled\], fieldset\[disabled\] .btn { cursor: not-allowed; opacity: 0.65; filter: alpha(opacity=65); -webkit-box-shadow: none; box-shadow: none; } a.btn.disabled, fieldset\[disabled\] a.btn { pointer-events: none; } .btn-default { color: #333; background-color: #fff; border-color: #ccc; } .btn-default:focus, .btn-default.focus { color: #333; background-color: #e6e6e6; border-color: #8c8c8c; } .btn-default:hover { color: #333; background-color: #e6e6e6; border-color: #adadad; } .btn-default:active, .btn-default.active, .open > .dropdown-toggle.btn-default { color: #333; background-color: #e6e6e6; border-color: #adadad; } .btn-default:active:hover, .btn-default.active:hover, .open > .dropdown-toggle.btn-default:hover, .btn-default:active:focus, .btn-default.active:focus, .open > .dropdown-toggle.btn-default:focus, .btn-default:active.focus, .btn-default.active.focus, .open > .dropdown-toggle.btn-default.focus { color: #333; background-color: #d4d4d4; border-color: #8c8c8c; } .btn-default:active, .btn-default.active, .open > .dropdown-toggle.btn-default { background-image: none; } .btn-default.disabled:hover, .btn-default\[disabled\]:hover, fieldset\[disabled\] .btn-default:hover, .btn-default.disabled:focus, .btn-default\[disabled\]:focus, fieldset\[disabled\] .btn-default:focus, .btn-default.disabled.focus, .btn-default\[disabled\].focus, fieldset\[disabled\] .btn-default.focus { background-color: #fff; border-color: #ccc; } .btn-default .badge { color: #fff; background-color: #333; } .btn-primary { color: #fff; background-color: #337ab7; border-color: #2e6da4; } .btn-primary:focus, .btn-primary.focus { color: #fff; background-color: #286090; border-color: #122b40; } .btn-primary:hover { color: #fff; background-color: #286090; border-color: #204d74; } .btn-primary:active, .btn-primary.active, .open > .dropdown-toggle.btn-primary { color: #fff; background-color: #286090; border-color: #204d74; } .btn-primary:active:hover, .btn-primary.active:hover, .open > .dropdown-toggle.btn-primary:hover, .btn-primary:active:focus, .btn-primary.active:focus, .open > .dropdown-toggle.btn-primary:focus, .btn-primary:active.focus, .btn-primary.active.focus, .open > .dropdown-toggle.btn-primary.focus { color: #fff; background-color: #204d74; border-color: #122b40; } .btn-primary:active, .btn-primary.active, .open > .dropdown-toggle.btn-primary { background-image: none; } .btn-primary.disabled:hover, .btn-primary\[disabled\]:hover, fieldset\[disabled\] .btn-primary:hover, .btn-primary.disabled:focus, .btn-primary\[disabled\]:focus, fieldset\[disabled\] .btn-primary:focus, .btn-primary.disabled.focus, .btn-primary\[disabled\].focus, fieldset\[disabled\] .btn-primary.focus { background-color: #337ab7; border-color: #2e6da4; } .btn-primary .badge { color: #337ab7; background-color: #fff; } .btn-success { color: #fff; background-color: #5cb85c; border-color: #4cae4c; } .btn-success:focus, .btn-success.focus { color: #fff; background-color: #449d44; border-color: #255625; } .btn-success:hover { color: #fff; background-color: #449d44; border-color: #398439; } .btn-success:active, .btn-success.active, .open > .dropdown-toggle.btn-success { color: #fff; background-color: #449d44; border-color: #398439; } .btn-success:active:hover, .btn-success.active:hover, .open > .dropdown-toggle.btn-success:hover, .btn-success:active:focus, .btn-success.active:focus, .open > .dropdown-toggle.btn-success:focus, .btn-success:active.focus, .btn-success.active.focus, .open > .dropdown-toggle.btn-success.focus { color: #fff; background-color: #398439; border-color: #255625; } .btn-success:active, .btn-success.active, .open > .dropdown-toggle.btn-success { background-image: none; } .btn-success.disabled:hover, .btn-success\[disabled\]:hover, fieldset\[disabled\] .btn-success:hover, .btn-success.disabled:focus, .btn-success\[disabled\]:focus, fieldset\[disabled\] .btn-success:focus, .btn-success.disabled.focus, .btn-success\[disabled\].focus, fieldset\[disabled\] .btn-success.focus { background-color: #5cb85c; border-color: #4cae4c; } .btn-success .badge { color: #5cb85c; background-color: #fff; } .btn-info { color: #fff; background-color: #5bc0de; border-color: #46b8da; } .btn-info:focus, .btn-info.focus { color: #fff; background-color: #31b0d5; border-color: #1b6d85; } .btn-info:hover { color: #fff; background-color: #31b0d5; border-color: #269abc; } .btn-info:active, .btn-info.active, .open > .dropdown-toggle.btn-info { color: #fff; background-color: #31b0d5; border-color: #269abc; } .btn-info:active:hover, .btn-info.active:hover, .open > .dropdown-toggle.btn-info:hover, .btn-info:active:focus, .btn-info.active:focus, .open > .dropdown-toggle.btn-info:focus, .btn-info:active.focus, .btn-info.active.focus, .open > .dropdown-toggle.btn-info.focus { color: #fff; background-color: #269abc; border-color: #1b6d85; } .btn-info:active, .btn-info.active, .open > .dropdown-toggle.btn-info { background-image: none; } .btn-info.disabled:hover, .btn-info\[disabled\]:hover, fieldset\[disabled\] .btn-info:hover, .btn-info.disabled:focus, .btn-info\[disabled\]:focus, fieldset\[disabled\] .btn-info:focus, .btn-info.disabled.focus, .btn-info\[disabled\].focus, fieldset\[disabled\] .btn-info.focus { background-color: #5bc0de; border-color: #46b8da; } .btn-info .badge { color: #5bc0de; background-color: #fff; } .btn-warning { color: #fff; background-color: #f0ad4e; border-color: #eea236; } .btn-warning:focus, .btn-warning.focus { color: #fff; background-color: #ec971f; border-color: #985f0d; } .btn-warning:hover { color: #fff; background-color: #ec971f; border-color: #d58512; } .btn-warning:active, .btn-warning.active, .open > .dropdown-toggle.btn-warning { color: #fff; background-color: #ec971f; border-color: #d58512; } .btn-warning:active:hover, .btn-warning.active:hover, .open > .dropdown-toggle.btn-warning:hover, .btn-warning:active:focus, .btn-warning.active:focus, .open > .dropdown-toggle.btn-warning:focus, .btn-warning:active.focus, .btn-warning.active.focus, .open > .dropdown-toggle.btn-warning.focus { color: #fff; background-color: #d58512; border-color: #985f0d; } .btn-warning:active, .btn-warning.active, .open > .dropdown-toggle.btn-warning { background-image: none; } .btn-warning.disabled:hover, .btn-warning\[disabled\]:hover, fieldset\[disabled\] .btn-warning:hover, .btn-warning.disabled:focus, .btn-warning\[disabled\]:focus, fieldset\[disabled\] .btn-warning:focus, .btn-warning.disabled.focus, .btn-warning\[disabled\].focus, fieldset\[disabled\] .btn-warning.focus { background-color: #f0ad4e; border-color: #eea236; } .btn-warning .badge { color: #f0ad4e; background-color: #fff; } .btn-danger { color: #fff; background-color: #d9534f; border-color: #d43f3a; } .btn-danger:focus, .btn-danger.focus { color: #fff; background-color: #c9302c; border-color: #761c19; } .btn-danger:hover { color: #fff; background-color: #c9302c; border-color: #ac2925; } .btn-danger:active, .btn-danger.active, .open > .dropdown-toggle.btn-danger { color: #fff; background-color: #c9302c; border-color: #ac2925; } .btn-danger:active:hover, .btn-danger.active:hover, .open > .dropdown-toggle.btn-danger:hover, .btn-danger:active:focus, .btn-danger.active:focus, .open > .dropdown-toggle.btn-danger:focus, .btn-danger:active.focus, .btn-danger.active.focus, .open > .dropdown-toggle.btn-danger.focus { color: #fff; background-color: #ac2925; border-color: #761c19; } .btn-danger:active, .btn-danger.active, .open > .dropdown-toggle.btn-danger { background-image: none; } .btn-danger.disabled:hover, .btn-danger\[disabled\]:hover, fieldset\[disabled\] .btn-danger:hover, .btn-danger.disabled:focus, .btn-danger\[disabled\]:focus, fieldset\[disabled\] .btn-danger:focus, .btn-danger.disabled.focus, .btn-danger\[disabled\].focus, fieldset\[disabled\] .btn-danger.focus { background-color: #d9534f; border-color: #d43f3a; } .btn-danger .badge { color: #d9534f; background-color: #fff; } .btn-link { color: #337ab7; font-weight: normal; border-radius: 0; } .btn-link, .btn-link:active, .btn-link.active, .btn-link\[disabled\], fieldset\[disabled\] .btn-link { background-color: transparent; -webkit-box-shadow: none; box-shadow: none; } .btn-link, .btn-link:hover, .btn-link:focus, .btn-link:active { border-color: transparent; } .btn-link:hover, .btn-link:focus { color: #23527c; text-decoration: underline; background-color: transparent; } .btn-link\[disabled\]:hover, fieldset\[disabled\] .btn-link:hover, .btn-link\[disabled\]:focus, fieldset\[disabled\] .btn-link:focus { color: #777777; text-decoration: none; } .btn-lg, .btn-group-lg > .btn { padding: 10px 16px; font-size: 17px; line-height: 1.3333333; border-radius: 3px; } .btn-sm, .btn-group-sm > .btn { padding: 5px 10px; font-size: 12px; line-height: 1.5; border-radius: 1px; } .btn-xs, .btn-group-xs > .btn { padding: 1px 5px; font-size: 12px; line-height: 1.5; border-radius: 1px; } .btn-block { display: block; width: 100%; } .btn-block + .btn-block { margin-top: 5px; } input\[type="submit"\].btn-block, input\[type="reset"\].btn-block, input\[type="button"\].btn-block { width: 100%; } .fade { opacity: 0; -webkit-transition: opacity 0.15s linear; -o-transition: opacity 0.15s linear; transition: opacity 0.15s linear; } .fade.in { opacity: 1; } .collapse { display: none; } .collapse.in { display: block; } tr.collapse.in { display: table-row; } tbody.collapse.in { display: table-row-group; } .collapsing { position: relative; height: 0; overflow: hidden; -webkit-transition-property: height, visibility; transition-property: height, visibility; -webkit-transition-duration: 0.35s; transition-duration: 0.35s; -webkit-transition-timing-function: ease; transition-timing-function: ease; } .caret { display: inline-block; width: 0; height: 0; margin-left: 2px; vertical-align: middle; border-top: 4px dashed; border-top: 4px solid \\9; border-right: 4px solid transparent; border-left: 4px solid transparent; } .dropup, .dropdown { position: relative; } .dropdown-toggle:focus { outline: 0; } .dropdown-menu { position: absolute; top: 100%; left: 0; z-index: 1000; display: none; float: left; min-width: 160px; padding: 5px 0; margin: 2px 0 0; list-style: none; font-size: 13px; text-align: left; background-color: #fff; border: 1px solid #ccc; border: 1px solid rgba(0, 0, 0, 0.15); border-radius: 2px; -webkit-box-shadow: 0 6px 12px rgba(0, 0, 0, 0.175); box-shadow: 0 6px 12px rgba(0, 0, 0, 0.175); background-clip: padding-box; } .dropdown-menu.pull-right { right: 0; left: auto; } .dropdown-menu .divider { height: 1px; margin: 8px 0; overflow: hidden; background-color: #e5e5e5; } .dropdown-menu > li > a { display: block; padding: 3px 20px; clear: both; font-weight: normal; line-height: 1.42857143; color: #333333; white-space: nowrap; } .dropdown-menu > li > a:hover, .dropdown-menu > li > a:focus { text-decoration: none; color: #262626; background-color: #f5f5f5; } .dropdown-menu > .active > a, .dropdown-menu > .active > a:hover, .dropdown-menu > .active > a:focus { color: #fff; text-decoration: none; outline: 0; background-color: #337ab7; } .dropdown-menu > .disabled > a, .dropdown-menu > .disabled > a:hover, .dropdown-menu > .disabled > a:focus { color: #777777; } .dropdown-menu > .disabled > a:hover, .dropdown-menu > .disabled > a:focus { text-decoration: none; background-color: transparent; background-image: none; filter: progid:DXImageTransform.Microsoft.gradient(enabled = false); cursor: not-allowed; } .open > .dropdown-menu { display: block; } .open > a { outline: 0; } .dropdown-menu-right { left: auto; right: 0; } .dropdown-menu-left { left: 0; right: auto; } .dropdown-header { display: block; padding: 3px 20px; font-size: 12px; line-height: 1.42857143; color: #777777; white-space: nowrap; } .dropdown-backdrop { position: fixed; left: 0; right: 0; bottom: 0; top: 0; z-index: 990; } .pull-right > .dropdown-menu { right: 0; left: auto; } .dropup .caret, .navbar-fixed-bottom .dropdown .caret { border-top: 0; border-bottom: 4px dashed; border-bottom: 4px solid \\9; content: ""; } .dropup .dropdown-menu, .navbar-fixed-bottom .dropdown .dropdown-menu { top: auto; bottom: 100%; margin-bottom: 2px; } @media (min-width: 541px) { .navbar-right .dropdown-menu { left: auto; right: 0; } .navbar-right .dropdown-menu-left { left: 0; right: auto; } } .btn-group, .btn-group-vertical { position: relative; display: inline-block; vertical-align: middle; } .btn-group > .btn, .btn-group-vertical > .btn { position: relative; float: left; } .btn-group > .btn:hover, .btn-group-vertical > .btn:hover, .btn-group > .btn:focus, .btn-group-vertical > .btn:focus, .btn-group > .btn:active, .btn-group-vertical > .btn:active, .btn-group > .btn.active, .btn-group-vertical > .btn.active { z-index: 2; } .btn-group .btn + .btn, .btn-group .btn + .btn-group, .btn-group .btn-group + .btn, .btn-group .btn-group + .btn-group { margin-left: -1px; } .btn-toolbar { margin-left: -5px; } .btn-toolbar .btn, .btn-toolbar .btn-group, .btn-toolbar .input-group { float: left; } .btn-toolbar > .btn, .btn-toolbar > .btn-group, .btn-toolbar > .input-group { margin-left: 5px; } .btn-group > .btn:not(:first-child):not(:last-child):not(.dropdown-toggle) { border-radius: 0; } .btn-group > .btn:first-child { margin-left: 0; } .btn-group > .btn:first-child:not(:last-child):not(.dropdown-toggle) { border-bottom-right-radius: 0; border-top-right-radius: 0; } .btn-group > .btn:last-child:not(:first-child), .btn-group > .dropdown-toggle:not(:first-child) { border-bottom-left-radius: 0; border-top-left-radius: 0; } .btn-group > .btn-group { float: left; } .btn-group > .btn-group:not(:first-child):not(:last-child) > .btn { border-radius: 0; } .btn-group > .btn-group:first-child:not(:last-child) > .btn:last-child, .btn-group > .btn-group:first-child:not(:last-child) > .dropdown-toggle { border-bottom-right-radius: 0; border-top-right-radius: 0; } .btn-group > .btn-group:last-child:not(:first-child) > .btn:first-child { border-bottom-left-radius: 0; border-top-left-radius: 0; } .btn-group .dropdown-toggle:active, .btn-group.open .dropdown-toggle { outline: 0; } .btn-group > .btn + .dropdown-toggle { padding-left: 8px; padding-right: 8px; } .btn-group > .btn-lg + .dropdown-toggle { padding-left: 12px; padding-right: 12px; } .btn-group.open .dropdown-toggle { -webkit-box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125); box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125); } .btn-group.open .dropdown-toggle.btn-link { -webkit-box-shadow: none; box-shadow: none; } .btn .caret { margin-left: 0; } .btn-lg .caret { border-width: 5px 5px 0; border-bottom-width: 0; } .dropup .btn-lg .caret { border-width: 0 5px 5px; } .btn-group-vertical > .btn, .btn-group-vertical > .btn-group, .btn-group-vertical > .btn-group > .btn { display: block; float: none; width: 100%; max-width: 100%; } .btn-group-vertical > .btn-group > .btn { float: none; } .btn-group-vertical > .btn + .btn, .btn-group-vertical > .btn + .btn-group, .btn-group-vertical > .btn-group + .btn, .btn-group-vertical > .btn-group + .btn-group { margin-top: -1px; margin-left: 0; } .btn-group-vertical > .btn:not(:first-child):not(:last-child) { border-radius: 0; } .btn-group-vertical > .btn:first-child:not(:last-child) { border-top-right-radius: 2px; border-top-left-radius: 2px; border-bottom-right-radius: 0; border-bottom-left-radius: 0; } .btn-group-vertical > .btn:last-child:not(:first-child) { border-top-right-radius: 0; border-top-left-radius: 0; border-bottom-right-radius: 2px; border-bottom-left-radius: 2px; } .btn-group-vertical > .btn-group:not(:first-child):not(:last-child) > .btn { border-radius: 0; } .btn-group-vertical > .btn-group:first-child:not(:last-child) > .btn:last-child, .btn-group-vertical > .btn-group:first-child:not(:last-child) > .dropdown-toggle { border-bottom-right-radius: 0; border-bottom-left-radius: 0; } .btn-group-vertical > .btn-group:last-child:not(:first-child) > .btn:first-child { border-top-right-radius: 0; border-top-left-radius: 0; } .btn-group-justified { display: table; width: 100%; table-layout: fixed; border-collapse: separate; } .btn-group-justified > .btn, .btn-group-justified > .btn-group { float: none; display: table-cell; width: 1%; } .btn-group-justified > .btn-group .btn { width: 100%; } .btn-group-justified > .btn-group .dropdown-menu { left: auto; } \[data-toggle="buttons"\] > .btn input\[type="radio"\], \[data-toggle="buttons"\] > .btn-group > .btn input\[type="radio"\], \[data-toggle="buttons"\] > .btn input\[type="checkbox"\], \[data-toggle="buttons"\] > .btn-group > .btn input\[type="checkbox"\] { position: absolute; clip: rect(0, 0, 0, 0); pointer-events: none; } .input-group { position: relative; display: table; border-collapse: separate; } .input-group\[class\*="col-"\] { float: none; padding-left: 0; padding-right: 0; } .input-group .form-control { position: relative; z-index: 2; float: left; width: 100%; margin-bottom: 0; } .input-group .form-control:focus { z-index: 3; } .input-group-lg > .form-control, .input-group-lg > .input-group-addon, .input-group-lg > .input-group-btn > .btn { height: 45px; padding: 10px 16px; font-size: 17px; line-height: 1.3333333; border-radius: 3px; } select.input-group-lg > .form-control, select.input-group-lg > .input-group-addon, select.input-group-lg > .input-group-btn > .btn { height: 45px; line-height: 45px; } textarea.input-group-lg > .form-control, textarea.input-group-lg > .input-group-addon, textarea.input-group-lg > .input-group-btn > .btn, select\[multiple\].input-group-lg > .form-control, select\[multiple\].input-group-lg > .input-group-addon, select\[multiple\].input-group-lg > .input-group-btn > .btn { height: auto; } .input-group-sm > .form-control, .input-group-sm > .input-group-addon, .input-group-sm > .input-group-btn > .btn { height: 30px; padding: 5px 10px; font-size: 12px; line-height: 1.5; border-radius: 1px; } select.input-group-sm > .form-control, select.input-group-sm > .input-group-addon, select.input-group-sm > .input-group-btn > .btn { height: 30px; line-height: 30px; } textarea.input-group-sm > .form-control, textarea.input-group-sm > .input-group-addon, textarea.input-group-sm > .input-group-btn > .btn, select\[multiple\].input-group-sm > .form-control, select\[multiple\].input-group-sm > .input-group-addon, select\[multiple\].input-group-sm > .input-group-btn > .btn { height: auto; } .input-group-addon, .input-group-btn, .input-group .form-control { display: table-cell; } .input-group-addon:not(:first-child):not(:last-child), .input-group-btn:not(:first-child):not(:last-child), .input-group .form-control:not(:first-child):not(:last-child) { border-radius: 0; } .input-group-addon, .input-group-btn { width: 1%; white-space: nowrap; vertical-align: middle; } .input-group-addon { padding: 6px 12px; font-size: 13px; font-weight: normal; line-height: 1; color: #555555; text-align: center; background-color: #eeeeee; border: 1px solid #ccc; border-radius: 2px; } .input-group-addon.input-sm { padding: 5px 10px; font-size: 12px; border-radius: 1px; } .input-group-addon.input-lg { padding: 10px 16px; font-size: 17px; border-radius: 3px; } .input-group-addon input\[type="radio"\], .input-group-addon input\[type="checkbox"\] { margin-top: 0; } .input-group .form-control:first-child, .input-group-addon:first-child, .input-group-btn:first-child > .btn, .input-group-btn:first-child > .btn-group > .btn, .input-group-btn:first-child > .dropdown-toggle, .input-group-btn:last-child > .btn:not(:last-child):not(.dropdown-toggle), .input-group-btn:last-child > .btn-group:not(:last-child) > .btn { border-bottom-right-radius: 0; border-top-right-radius: 0; } .input-group-addon:first-child { border-right: 0; } .input-group .form-control:last-child, .input-group-addon:last-child, .input-group-btn:last-child > .btn, .input-group-btn:last-child > .btn-group > .btn, .input-group-btn:last-child > .dropdown-toggle, .input-group-btn:first-child > .btn:not(:first-child), .input-group-btn:first-child > .btn-group:not(:first-child) > .btn { border-bottom-left-radius: 0; border-top-left-radius: 0; } .input-group-addon:last-child { border-left: 0; } .input-group-btn { position: relative; font-size: 0; white-space: nowrap; } .input-group-btn > .btn { position: relative; } .input-group-btn > .btn + .btn { margin-left: -1px; } .input-group-btn > .btn:hover, .input-group-btn > .btn:focus, .input-group-btn > .btn:active { z-index: 2; } .input-group-btn:first-child > .btn, .input-group-btn:first-child > .btn-group { margin-right: -1px; } .input-group-btn:last-child > .btn, .input-group-btn:last-child > .btn-group { z-index: 2; margin-left: -1px; } .nav { margin-bottom: 0; padding-left: 0; list-style: none; } .nav > li { position: relative; display: block; } .nav > li > a { position: relative; display: block; padding: 10px 15px; } .nav > li > a:hover, .nav > li > a:focus { text-decoration: none; background-color: #eeeeee; } .nav > li.disabled > a { color: #777777; } .nav > li.disabled > a:hover, .nav > li.disabled > a:focus { color: #777777; text-decoration: none; background-color: transparent; cursor: not-allowed; } .nav .open > a, .nav .open > a:hover, .nav .open > a:focus { background-color: #eeeeee; border-color: #337ab7; } .nav .nav-divider { height: 1px; margin: 8px 0; overflow: hidden; background-color: #e5e5e5; } .nav > li > a > img { max-width: none; } .nav-tabs { border-bottom: 1px solid #ddd; } .nav-tabs > li { float: left; margin-bottom: -1px; } .nav-tabs > li > a { margin-right: 2px; line-height: 1.42857143; border: 1px solid transparent; border-radius: 2px 2px 0 0; } .nav-tabs > li > a:hover { border-color: #eeeeee #eeeeee #ddd; } .nav-tabs > li.active > a, .nav-tabs > li.active > a:hover, .nav-tabs > li.active > a:focus { color: #555555; background-color: #fff; border: 1px solid #ddd; border-bottom-color: transparent; cursor: default; } .nav-tabs.nav-justified { width: 100%; border-bottom: 0; } .nav-tabs.nav-justified > li { float: none; } .nav-tabs.nav-justified > li > a { text-align: center; margin-bottom: 5px; } .nav-tabs.nav-justified > .dropdown .dropdown-menu { top: auto; left: auto; } @media (min-width: 768px) { .nav-tabs.nav-justified > li { display: table-cell; width: 1%; } .nav-tabs.nav-justified > li > a { margin-bottom: 0; } } .nav-tabs.nav-justified > li > a { margin-right: 0; border-radius: 2px; } .nav-tabs.nav-justified > .active > a, .nav-tabs.nav-justified > .active > a:hover, .nav-tabs.nav-justified > .active > a:focus { border: 1px solid #ddd; } @media (min-width: 768px) { .nav-tabs.nav-justified > li > a { border-bottom: 1px solid #ddd; border-radius: 2px 2px 0 0; } .nav-tabs.nav-justified > .active > a, .nav-tabs.nav-justified > .active > a:hover, .nav-tabs.nav-justified > .active > a:focus { border-bottom-color: #fff; } } .nav-pills > li { float: left; } .nav-pills > li > a { border-radius: 2px; } .nav-pills > li + li { margin-left: 2px; } .nav-pills > li.active > a, .nav-pills > li.active > a:hover, .nav-pills > li.active > a:focus { color: #fff; background-color: #337ab7; } .nav-stacked > li { float: none; } .nav-stacked > li + li { margin-top: 2px; margin-left: 0; } .nav-justified { width: 100%; } .nav-justified > li { float: none; } .nav-justified > li > a { text-align: center; margin-bottom: 5px; } .nav-justified > .dropdown .dropdown-menu { top: auto; left: auto; } @media (min-width: 768px) { .nav-justified > li { display: table-cell; width: 1%; } .nav-justified > li > a { margin-bottom: 0; } } .nav-tabs-justified { border-bottom: 0; } .nav-tabs-justified > li > a { margin-right: 0; border-radius: 2px; } .nav-tabs-justified > .active > a, .nav-tabs-justified > .active > a:hover, .nav-tabs-justified > .active > a:focus { border: 1px solid #ddd; } @media (min-width: 768px) { .nav-tabs-justified > li > a { border-bottom: 1px solid #ddd; border-radius: 2px 2px 0 0; } .nav-tabs-justified > .active > a, .nav-tabs-justified > .active > a:hover, .nav-tabs-justified > .active > a:focus { border-bottom-color: #fff; } } .tab-content > .tab-pane { display: none; } .tab-content > .active { display: block; } .nav-tabs .dropdown-menu { margin-top: -1px; border-top-right-radius: 0; border-top-left-radius: 0; } .navbar { position: relative; min-height: 30px; margin-bottom: 18px; border: 1px solid transparent; } @media (min-width: 541px) { .navbar { border-radius: 2px; } } @media (min-width: 541px) { .navbar-header { float: left; } } .navbar-collapse { overflow-x: visible; padding-right: 0px; padding-left: 0px; border-top: 1px solid transparent; box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1); -webkit-overflow-scrolling: touch; } .navbar-collapse.in { overflow-y: auto; } @media (min-width: 541px) { .navbar-collapse { width: auto; border-top: 0; box-shadow: none; } .navbar-collapse.collapse { display: block !important; height: auto !important; padding-bottom: 0; overflow: visible !important; } .navbar-collapse.in { overflow-y: visible; } .navbar-fixed-top .navbar-collapse, .navbar-static-top .navbar-collapse, .navbar-fixed-bottom .navbar-collapse { padding-left: 0; padding-right: 0; } } .navbar-fixed-top .navbar-collapse, .navbar-fixed-bottom .navbar-collapse { max-height: 340px; } @media (max-device-width: 540px) and (orientation: landscape) { .navbar-fixed-top .navbar-collapse, .navbar-fixed-bottom .navbar-collapse { max-height: 200px; } } .container > .navbar-header, .container-fluid > .navbar-header, .container > .navbar-collapse, .container-fluid > .navbar-collapse { margin-right: 0px; margin-left: 0px; } @media (min-width: 541px) { .container > .navbar-header, .container-fluid > .navbar-header, .container > .navbar-collapse, .container-fluid > .navbar-collapse { margin-right: 0; margin-left: 0; } } .navbar-static-top { z-index: 1000; border-width: 0 0 1px; } @media (min-width: 541px) { .navbar-static-top { border-radius: 0; } } .navbar-fixed-top, .navbar-fixed-bottom { position: fixed; right: 0; left: 0; z-index: 1030; } @media (min-width: 541px) { .navbar-fixed-top, .navbar-fixed-bottom { border-radius: 0; } } .navbar-fixed-top { top: 0; border-width: 0 0 1px; } .navbar-fixed-bottom { bottom: 0; margin-bottom: 0; border-width: 1px 0 0; } .navbar-brand { float: left; padding: 6px 0px; font-size: 17px; line-height: 18px; height: 30px; } .navbar-brand:hover, .navbar-brand:focus { text-decoration: none; } .navbar-brand > img { display: block; } @media (min-width: 541px) { .navbar > .container .navbar-brand, .navbar > .container-fluid .navbar-brand { margin-left: 0px; } } .navbar-toggle { position: relative; float: right; margin-right: 0px; padding: 9px 10px; margin-top: -2px; margin-bottom: -2px; background-color: transparent; background-image: none; border: 1px solid transparent; border-radius: 2px; } .navbar-toggle:focus { outline: 0; } .navbar-toggle .icon-bar { display: block; width: 22px; height: 2px; border-radius: 1px; } .navbar-toggle .icon-bar + .icon-bar { margin-top: 4px; } @media (min-width: 541px) { .navbar-toggle { display: none; } } .navbar-nav { margin: 3px 0px; } .navbar-nav > li > a { padding-top: 10px; padding-bottom: 10px; line-height: 18px; } @media (max-width: 540px) { .navbar-nav .open .dropdown-menu { position: static; float: none; width: auto; margin-top: 0; background-color: transparent; border: 0; box-shadow: none; } .navbar-nav .open .dropdown-menu > li > a, .navbar-nav .open .dropdown-menu .dropdown-header { padding: 5px 15px 5px 25px; } .navbar-nav .open .dropdown-menu > li > a { line-height: 18px; } .navbar-nav .open .dropdown-menu > li > a:hover, .navbar-nav .open .dropdown-menu > li > a:focus { background-image: none; } } @media (min-width: 541px) { .navbar-nav { float: left; margin: 0; } .navbar-nav > li { float: left; } .navbar-nav > li > a { padding-top: 6px; padding-bottom: 6px; } } .navbar-form { margin-left: 0px; margin-right: 0px; padding: 10px 0px; border-top: 1px solid transparent; border-bottom: 1px solid transparent; -webkit-box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1), 0 1px 0 rgba(255, 255, 255, 0.1); box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1), 0 1px 0 rgba(255, 255, 255, 0.1); margin-top: -1px; margin-bottom: -1px; } @media (min-width: 768px) { .navbar-form .form-group { display: inline-block; margin-bottom: 0; vertical-align: middle; } .navbar-form .form-control { display: inline-block; width: auto; vertical-align: middle; } .navbar-form .form-control-static { display: inline-block; } .navbar-form .input-group { display: inline-table; vertical-align: middle; } .navbar-form .input-group .input-group-addon, .navbar-form .input-group .input-group-btn, .navbar-form .input-group .form-control { width: auto; } .navbar-form .input-group > .form-control { width: 100%; } .navbar-form .control-label { margin-bottom: 0; vertical-align: middle; } .navbar-form .radio, .navbar-form .checkbox { display: inline-block; margin-top: 0; margin-bottom: 0; vertical-align: middle; } .navbar-form .radio label, .navbar-form .checkbox label { padding-left: 0; } .navbar-form .radio input\[type="radio"\], .navbar-form .checkbox input\[type="checkbox"\] { position: relative; margin-left: 0; } .navbar-form .has-feedback .form-control-feedback { top: 0; } } @media (max-width: 540px) { .navbar-form .form-group { margin-bottom: 5px; } .navbar-form .form-group:last-child { margin-bottom: 0; } } @media (min-width: 541px) { .navbar-form { width: auto; border: 0; margin-left: 0; margin-right: 0; padding-top: 0; padding-bottom: 0; -webkit-box-shadow: none; box-shadow: none; } } .navbar-nav > li > .dropdown-menu { margin-top: 0; border-top-right-radius: 0; border-top-left-radius: 0; } .navbar-fixed-bottom .navbar-nav > li > .dropdown-menu { margin-bottom: 0; border-top-right-radius: 2px; border-top-left-radius: 2px; border-bottom-right-radius: 0; border-bottom-left-radius: 0; } .navbar-btn { margin-top: -1px; margin-bottom: -1px; } .navbar-btn.btn-sm { margin-top: 0px; margin-bottom: 0px; } .navbar-btn.btn-xs { margin-top: 4px; margin-bottom: 4px; } .navbar-text { margin-top: 6px; margin-bottom: 6px; } @media (min-width: 541px) { .navbar-text { float: left; margin-left: 0px; margin-right: 0px; } } @media (min-width: 541px) { .navbar-left { float: left !important; float: left; } .navbar-right { float: right !important; float: right; margin-right: 0px; } .navbar-right ~ .navbar-right { margin-right: 0; } } .navbar-default { background-color: #f8f8f8; border-color: #e7e7e7; } .navbar-default .navbar-brand { color: #777; } .navbar-default .navbar-brand:hover, .navbar-default .navbar-brand:focus { color: #5e5e5e; background-color: transparent; } .navbar-default .navbar-text { color: #777; } .navbar-default .navbar-nav > li > a { color: #777; } .navbar-default .navbar-nav > li > a:hover, .navbar-default .navbar-nav > li > a:focus { color: #333; background-color: transparent; } .navbar-default .navbar-nav > .active > a, .navbar-default .navbar-nav > .active > a:hover, .navbar-default .navbar-nav > .active > a:focus { color: #555; background-color: #e7e7e7; } .navbar-default .navbar-nav > .disabled > a, .navbar-default .navbar-nav > .disabled > a:hover, .navbar-default .navbar-nav > .disabled > a:focus { color: #ccc; background-color: transparent; } .navbar-default .navbar-toggle { border-color: #ddd; } .navbar-default .navbar-toggle:hover, .navbar-default .navbar-toggle:focus { background-color: #ddd; } .navbar-default .navbar-toggle .icon-bar { background-color: #888; } .navbar-default .navbar-collapse, .navbar-default .navbar-form { border-color: #e7e7e7; } .navbar-default .navbar-nav > .open > a, .navbar-default .navbar-nav > .open > a:hover, .navbar-default .navbar-nav > .open > a:focus { background-color: #e7e7e7; color: #555; } @media (max-width: 540px) { .navbar-default .navbar-nav .open .dropdown-menu > li > a { color: #777; } .navbar-default .navbar-nav .open .dropdown-menu > li > a:hover, .navbar-default .navbar-nav .open .dropdown-menu > li > a:focus { color: #333; background-color: transparent; } .navbar-default .navbar-nav .open .dropdown-menu > .active > a, .navbar-default .navbar-nav .open .dropdown-menu > .active > a:hover, .navbar-default .navbar-nav .open .dropdown-menu > .active > a:focus { color: #555; background-color: #e7e7e7; } .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a, .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a:hover, .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a:focus { color: #ccc; background-color: transparent; } } .navbar-default .navbar-link { color: #777; } .navbar-default .navbar-link:hover { color: #333; } .navbar-default .btn-link { color: #777; } .navbar-default .btn-link:hover, .navbar-default .btn-link:focus { color: #333; } .navbar-default .btn-link\[disabled\]:hover, fieldset\[disabled\] .navbar-default .btn-link:hover, .navbar-default .btn-link\[disabled\]:focus, fieldset\[disabled\] .navbar-default .btn-link:focus { color: #ccc; } .navbar-inverse { background-color: #222; border-color: #080808; } .navbar-inverse .navbar-brand { color: #9d9d9d; } .navbar-inverse .navbar-brand:hover, .navbar-inverse .navbar-brand:focus { color: #fff; background-color: transparent; } .navbar-inverse .navbar-text { color: #9d9d9d; } .navbar-inverse .navbar-nav > li > a { color: #9d9d9d; } .navbar-inverse .navbar-nav > li > a:hover, .navbar-inverse .navbar-nav > li > a:focus { color: #fff; background-color: transparent; } .navbar-inverse .navbar-nav > .active > a, .navbar-inverse .navbar-nav > .active > a:hover, .navbar-inverse .navbar-nav > .active > a:focus { color: #fff; background-color: #080808; } .navbar-inverse .navbar-nav > .disabled > a, .navbar-inverse .navbar-nav > .disabled > a:hover, .navbar-inverse .navbar-nav > .disabled > a:focus { color: #444; background-color: transparent; } .navbar-inverse .navbar-toggle { border-color: #333; } .navbar-inverse .navbar-toggle:hover, .navbar-inverse .navbar-toggle:focus { background-color: #333; } .navbar-inverse .navbar-toggle .icon-bar { background-color: #fff; } .navbar-inverse .navbar-collapse, .navbar-inverse .navbar-form { border-color: #101010; } .navbar-inverse .navbar-nav > .open > a, .navbar-inverse .navbar-nav > .open > a:hover, .navbar-inverse .navbar-nav > .open > a:focus { background-color: #080808; color: #fff; } @media (max-width: 540px) { .navbar-inverse .navbar-nav .open .dropdown-menu > .dropdown-header { border-color: #080808; } .navbar-inverse .navbar-nav .open .dropdown-menu .divider { background-color: #080808; } .navbar-inverse .navbar-nav .open .dropdown-menu > li > a { color: #9d9d9d; } .navbar-inverse .navbar-nav .open .dropdown-menu > li > a:hover, .navbar-inverse .navbar-nav .open .dropdown-menu > li > a:focus { color: #fff; background-color: transparent; } .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a, .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a:hover, .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a:focus { color: #fff; background-color: #080808; } .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a, .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a:hover, .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a:focus { color: #444; background-color: transparent; } } .navbar-inverse .navbar-link { color: #9d9d9d; } .navbar-inverse .navbar-link:hover { color: #fff; } .navbar-inverse .btn-link { color: #9d9d9d; } .navbar-inverse .btn-link:hover, .navbar-inverse .btn-link:focus { color: #fff; } .navbar-inverse .btn-link\[disabled\]:hover, fieldset\[disabled\] .navbar-inverse .btn-link:hover, .navbar-inverse .btn-link\[disabled\]:focus, fieldset\[disabled\] .navbar-inverse .btn-link:focus { color: #444; } .breadcrumb { padding: 8px 15px; margin-bottom: 18px; list-style: none; background-color: #f5f5f5; border-radius: 2px; } .breadcrumb > li { display: inline-block; } .breadcrumb > li + li:before { content: "/\\00a0"; padding: 0 5px; color: #5e5e5e; } .breadcrumb > .active { color: #777777; } .pagination { display: inline-block; padding-left: 0; margin: 18px 0; border-radius: 2px; } .pagination > li { display: inline; } .pagination > li > a, .pagination > li > span { position: relative; float: left; padding: 6px 12px; line-height: 1.42857143; text-decoration: none; color: #337ab7; background-color: #fff; border: 1px solid #ddd; margin-left: -1px; } .pagination > li:first-child > a, .pagination > li:first-child > span { margin-left: 0; border-bottom-left-radius: 2px; border-top-left-radius: 2px; } .pagination > li:last-child > a, .pagination > li:last-child > span { border-bottom-right-radius: 2px; border-top-right-radius: 2px; } .pagination > li > a:hover, .pagination > li > span:hover, .pagination > li > a:focus, .pagination > li > span:focus { z-index: 2; color: #23527c; background-color: #eeeeee; border-color: #ddd; } .pagination > .active > a, .pagination > .active > span, .pagination > .active > a:hover, .pagination > .active > span:hover, .pagination > .active > a:focus, .pagination > .active > span:focus { z-index: 3; color: #fff; background-color: #337ab7; border-color: #337ab7; cursor: default; } .pagination > .disabled > span, .pagination > .disabled > span:hover, .pagination > .disabled > span:focus, .pagination > .disabled > a, .pagination > .disabled > a:hover, .pagination > .disabled > a:focus { color: #777777; background-color: #fff; border-color: #ddd; cursor: not-allowed; } .pagination-lg > li > a, .pagination-lg > li > span { padding: 10px 16px; font-size: 17px; line-height: 1.3333333; } .pagination-lg > li:first-child > a, .pagination-lg > li:first-child > span { border-bottom-left-radius: 3px; border-top-left-radius: 3px; } .pagination-lg > li:last-child > a, .pagination-lg > li:last-child > span { border-bottom-right-radius: 3px; border-top-right-radius: 3px; } .pagination-sm > li > a, .pagination-sm > li > span { padding: 5px 10px; font-size: 12px; line-height: 1.5; } .pagination-sm > li:first-child > a, .pagination-sm > li:first-child > span { border-bottom-left-radius: 1px; border-top-left-radius: 1px; } .pagination-sm > li:last-child > a, .pagination-sm > li:last-child > span { border-bottom-right-radius: 1px; border-top-right-radius: 1px; } .pager { padding-left: 0; margin: 18px 0; list-style: none; text-align: center; } .pager li { display: inline; } .pager li > a, .pager li > span { display: inline-block; padding: 5px 14px; background-color: #fff; border: 1px solid #ddd; border-radius: 15px; } .pager li > a:hover, .pager li > a:focus { text-decoration: none; background-color: #eeeeee; } .pager .next > a, .pager .next > span { float: right; } .pager .previous > a, .pager .previous > span { float: left; } .pager .disabled > a, .pager .disabled > a:hover, .pager .disabled > a:focus, .pager .disabled > span { color: #777777; background-color: #fff; cursor: not-allowed; } .label { display: inline; padding: .2em .6em .3em; font-size: 75%; font-weight: bold; line-height: 1; color: #fff; text-align: center; white-space: nowrap; vertical-align: baseline; border-radius: .25em; } a.label:hover, a.label:focus { color: #fff; text-decoration: none; cursor: pointer; } .label:empty { display: none; } .btn .label { position: relative; top: -1px; } .label-default { background-color: #777777; } .label-default\[href\]:hover, .label-default\[href\]:focus { background-color: #5e5e5e; } .label-primary { background-color: #337ab7; } .label-primary\[href\]:hover, .label-primary\[href\]:focus { background-color: #286090; } .label-success { background-color: #5cb85c; } .label-success\[href\]:hover, .label-success\[href\]:focus { background-color: #449d44; } .label-info { background-color: #5bc0de; } .label-info\[href\]:hover, .label-info\[href\]:focus { background-color: #31b0d5; } .label-warning { background-color: #f0ad4e; } .label-warning\[href\]:hover, .label-warning\[href\]:focus { background-color: #ec971f; } .label-danger { background-color: #d9534f; } .label-danger\[href\]:hover, .label-danger\[href\]:focus { background-color: #c9302c; } .badge { display: inline-block; min-width: 10px; padding: 3px 7px; font-size: 12px; font-weight: bold; color: #fff; line-height: 1; vertical-align: middle; white-space: nowrap; text-align: center; background-color: #777777; border-radius: 10px; } .badge:empty { display: none; } .btn .badge { position: relative; top: -1px; } .btn-xs .badge, .btn-group-xs > .btn .badge { top: 0; padding: 1px 5px; } a.badge:hover, a.badge:focus { color: #fff; text-decoration: none; cursor: pointer; } .list-group-item.active > .badge, .nav-pills > .active > a > .badge { color: #337ab7; background-color: #fff; } .list-group-item > .badge { float: right; } .list-group-item > .badge + .badge { margin-right: 5px; } .nav-pills > li > a > .badge { margin-left: 3px; } .jumbotron { padding-top: 30px; padding-bottom: 30px; margin-bottom: 30px; color: inherit; background-color: #eeeeee; } .jumbotron h1, .jumbotron .h1 { color: inherit; } .jumbotron p { margin-bottom: 15px; font-size: 20px; font-weight: 200; } .jumbotron > hr { border-top-color: #d5d5d5; } .container .jumbotron, .container-fluid .jumbotron { border-radius: 3px; padding-left: 0px; padding-right: 0px; } .jumbotron .container { max-width: 100%; } @media screen and (min-width: 768px) { .jumbotron { padding-top: 48px; padding-bottom: 48px; } .container .jumbotron, .container-fluid .jumbotron { padding-left: 60px; padding-right: 60px; } .jumbotron h1, .jumbotron .h1 { font-size: 59px; } } .thumbnail { display: block; padding: 4px; margin-bottom: 18px; line-height: 1.42857143; background-color: #fff; border: 1px solid #ddd; border-radius: 2px; -webkit-transition: border 0.2s ease-in-out; -o-transition: border 0.2s ease-in-out; transition: border 0.2s ease-in-out; } .thumbnail > img, .thumbnail a > img { margin-left: auto; margin-right: auto; } a.thumbnail:hover, a.thumbnail:focus, a.thumbnail.active { border-color: #337ab7; } .thumbnail .caption { padding: 9px; color: #000; } .alert { padding: 15px; margin-bottom: 18px; border: 1px solid transparent; border-radius: 2px; } .alert h4 { margin-top: 0; color: inherit; } .alert .alert-link { font-weight: bold; } .alert > p, .alert > ul { margin-bottom: 0; } .alert > p + p { margin-top: 5px; } .alert-dismissable, .alert-dismissible { padding-right: 35px; } .alert-dismissable .close, .alert-dismissible .close { position: relative; top: -2px; right: -21px; color: inherit; } .alert-success { background-color: #dff0d8; border-color: #d6e9c6; color: #3c763d; } .alert-success hr { border-top-color: #c9e2b3; } .alert-success .alert-link { color: #2b542c; } .alert-info { background-color: #d9edf7; border-color: #bce8f1; color: #31708f; } .alert-info hr { border-top-color: #a6e1ec; } .alert-info .alert-link { color: #245269; } .alert-warning { background-color: #fcf8e3; border-color: #faebcc; color: #8a6d3b; } .alert-warning hr { border-top-color: #f7e1b5; } .alert-warning .alert-link { color: #66512c; } .alert-danger { background-color: #f2dede; border-color: #ebccd1; color: #a94442; } .alert-danger hr { border-top-color: #e4b9c0; } .alert-danger .alert-link { color: #843534; } @-webkit-keyframes progress-bar-stripes { from { background-position: 40px 0; } to { background-position: 0 0; } } @keyframes progress-bar-stripes { from { background-position: 40px 0; } to { background-position: 0 0; } } .progress { overflow: hidden; height: 18px; margin-bottom: 18px; background-color: #f5f5f5; border-radius: 2px; -webkit-box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.1); box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.1); } .progress-bar { float: left; width: 0%; height: 100%; font-size: 12px; line-height: 18px; color: #fff; text-align: center; background-color: #337ab7; -webkit-box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.15); box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.15); -webkit-transition: width 0.6s ease; -o-transition: width 0.6s ease; transition: width 0.6s ease; } .progress-striped .progress-bar, .progress-bar-striped { background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent); background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent); background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent); background-size: 40px 40px; } .progress.active .progress-bar, .progress-bar.active { -webkit-animation: progress-bar-stripes 2s linear infinite; -o-animation: progress-bar-stripes 2s linear infinite; animation: progress-bar-stripes 2s linear infinite; } .progress-bar-success { background-color: #5cb85c; } .progress-striped .progress-bar-success { background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent); background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent); background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent); } .progress-bar-info { background-color: #5bc0de; } .progress-striped .progress-bar-info { background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent); background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent); background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent); } .progress-bar-warning { background-color: #f0ad4e; } .progress-striped .progress-bar-warning { background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent); background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent); background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent); } .progress-bar-danger { background-color: #d9534f; } .progress-striped .progress-bar-danger { background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent); background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent); background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent); } .media { margin-top: 15px; } .media:first-child { margin-top: 0; } .media, .media-body { zoom: 1; overflow: hidden; } .media-body { width: 10000px; } .media-object { display: block; } .media-object.img-thumbnail { max-width: none; } .media-right, .media > .pull-right { padding-left: 10px; } .media-left, .media > .pull-left { padding-right: 10px; } .media-left, .media-right, .media-body { display: table-cell; vertical-align: top; } .media-middle { vertical-align: middle; } .media-bottom { vertical-align: bottom; } .media-heading { margin-top: 0; margin-bottom: 5px; } .media-list { padding-left: 0; list-style: none; } .list-group { margin-bottom: 20px; padding-left: 0; } .list-group-item { position: relative; display: block; padding: 10px 15px; margin-bottom: -1px; background-color: #fff; border: 1px solid #ddd; } .list-group-item:first-child { border-top-right-radius: 2px; border-top-left-radius: 2px; } .list-group-item:last-child { margin-bottom: 0; border-bottom-right-radius: 2px; border-bottom-left-radius: 2px; } a.list-group-item, button.list-group-item { color: #555; } a.list-group-item .list-group-item-heading, button.list-group-item .list-group-item-heading { color: #333; } a.list-group-item:hover, button.list-group-item:hover, a.list-group-item:focus, button.list-group-item:focus { text-decoration: none; color: #555; background-color: #f5f5f5; } button.list-group-item { width: 100%; text-align: left; } .list-group-item.disabled, .list-group-item.disabled:hover, .list-group-item.disabled:focus { background-color: #eeeeee; color: #777777; cursor: not-allowed; } .list-group-item.disabled .list-group-item-heading, .list-group-item.disabled:hover .list-group-item-heading, .list-group-item.disabled:focus .list-group-item-heading { color: inherit; } .list-group-item.disabled .list-group-item-text, .list-group-item.disabled:hover .list-group-item-text, .list-group-item.disabled:focus .list-group-item-text { color: #777777; } .list-group-item.active, .list-group-item.active:hover, .list-group-item.active:focus { z-index: 2; color: #fff; background-color: #337ab7; border-color: #337ab7; } .list-group-item.active .list-group-item-heading, .list-group-item.active:hover .list-group-item-heading, .list-group-item.active:focus .list-group-item-heading, .list-group-item.active .list-group-item-heading > small, .list-group-item.active:hover .list-group-item-heading > small, .list-group-item.active:focus .list-group-item-heading > small, .list-group-item.active .list-group-item-heading > .small, .list-group-item.active:hover .list-group-item-heading > .small, .list-group-item.active:focus .list-group-item-heading > .small { color: inherit; } .list-group-item.active .list-group-item-text, .list-group-item.active:hover .list-group-item-text, .list-group-item.active:focus .list-group-item-text { color: #c7ddef; } .list-group-item-success { color: #3c763d; background-color: #dff0d8; } a.list-group-item-success, button.list-group-item-success { color: #3c763d; } a.list-group-item-success .list-group-item-heading, button.list-group-item-success .list-group-item-heading { color: inherit; } a.list-group-item-success:hover, button.list-group-item-success:hover, a.list-group-item-success:focus, button.list-group-item-success:focus { color: #3c763d; background-color: #d0e9c6; } a.list-group-item-success.active, button.list-group-item-success.active, a.list-group-item-success.active:hover, button.list-group-item-success.active:hover, a.list-group-item-success.active:focus, button.list-group-item-success.active:focus { color: #fff; background-color: #3c763d; border-color: #3c763d; } .list-group-item-info { color: #31708f; background-color: #d9edf7; } a.list-group-item-info, button.list-group-item-info { color: #31708f; } a.list-group-item-info .list-group-item-heading, button.list-group-item-info .list-group-item-heading { color: inherit; } a.list-group-item-info:hover, button.list-group-item-info:hover, a.list-group-item-info:focus, button.list-group-item-info:focus { color: #31708f; background-color: #c4e3f3; } a.list-group-item-info.active, button.list-group-item-info.active, a.list-group-item-info.active:hover, button.list-group-item-info.active:hover, a.list-group-item-info.active:focus, button.list-group-item-info.active:focus { color: #fff; background-color: #31708f; border-color: #31708f; } .list-group-item-warning { color: #8a6d3b; background-color: #fcf8e3; } a.list-group-item-warning, button.list-group-item-warning { color: #8a6d3b; } a.list-group-item-warning .list-group-item-heading, button.list-group-item-warning .list-group-item-heading { color: inherit; } a.list-group-item-warning:hover, button.list-group-item-warning:hover, a.list-group-item-warning:focus, button.list-group-item-warning:focus { color: #8a6d3b; background-color: #faf2cc; } a.list-group-item-warning.active, button.list-group-item-warning.active, a.list-group-item-warning.active:hover, button.list-group-item-warning.active:hover, a.list-group-item-warning.active:focus, button.list-group-item-warning.active:focus { color: #fff; background-color: #8a6d3b; border-color: #8a6d3b; } .list-group-item-danger { color: #a94442; background-color: #f2dede; } a.list-group-item-danger, button.list-group-item-danger { color: #a94442; } a.list-group-item-danger .list-group-item-heading, button.list-group-item-danger .list-group-item-heading { color: inherit; } a.list-group-item-danger:hover, button.list-group-item-danger:hover, a.list-group-item-danger:focus, button.list-group-item-danger:focus { color: #a94442; background-color: #ebcccc; } a.list-group-item-danger.active, button.list-group-item-danger.active, a.list-group-item-danger.active:hover, button.list-group-item-danger.active:hover, a.list-group-item-danger.active:focus, button.list-group-item-danger.active:focus { color: #fff; background-color: #a94442; border-color: #a94442; } .list-group-item-heading { margin-top: 0; margin-bottom: 5px; } .list-group-item-text { margin-bottom: 0; line-height: 1.3; } .panel { margin-bottom: 18px; background-color: #fff; border: 1px solid transparent; border-radius: 2px; -webkit-box-shadow: 0 1px 1px rgba(0, 0, 0, 0.05); box-shadow: 0 1px 1px rgba(0, 0, 0, 0.05); } .panel-body { padding: 15px; } .panel-heading { padding: 10px 15px; border-bottom: 1px solid transparent; border-top-right-radius: 1px; border-top-left-radius: 1px; } .panel-heading > .dropdown .dropdown-toggle { color: inherit; } .panel-title { margin-top: 0; margin-bottom: 0; font-size: 15px; color: inherit; } .panel-title > a, .panel-title > small, .panel-title > .small, .panel-title > small > a, .panel-title > .small > a { color: inherit; } .panel-footer { padding: 10px 15px; background-color: #f5f5f5; border-top: 1px solid #ddd; border-bottom-right-radius: 1px; border-bottom-left-radius: 1px; } .panel > .list-group, .panel > .panel-collapse > .list-group { margin-bottom: 0; } .panel > .list-group .list-group-item, .panel > .panel-collapse > .list-group .list-group-item { border-width: 1px 0; border-radius: 0; } .panel > .list-group:first-child .list-group-item:first-child, .panel > .panel-collapse > .list-group:first-child .list-group-item:first-child { border-top: 0; border-top-right-radius: 1px; border-top-left-radius: 1px; } .panel > .list-group:last-child .list-group-item:last-child, .panel > .panel-collapse > .list-group:last-child .list-group-item:last-child { border-bottom: 0; border-bottom-right-radius: 1px; border-bottom-left-radius: 1px; } .panel > .panel-heading + .panel-collapse > .list-group .list-group-item:first-child { border-top-right-radius: 0; border-top-left-radius: 0; } .panel-heading + .list-group .list-group-item:first-child { border-top-width: 0; } .list-group + .panel-footer { border-top-width: 0; } .panel > .table, .panel > .table-responsive > .table, .panel > .panel-collapse > .table { margin-bottom: 0; } .panel > .table caption, .panel > .table-responsive > .table caption, .panel > .panel-collapse > .table caption { padding-left: 15px; padding-right: 15px; } .panel > .table:first-child, .panel > .table-responsive:first-child > .table:first-child { border-top-right-radius: 1px; border-top-left-radius: 1px; } .panel > .table:first-child > thead:first-child > tr:first-child, .panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child, .panel > .table:first-child > tbody:first-child > tr:first-child, .panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child { border-top-left-radius: 1px; border-top-right-radius: 1px; } .panel > .table:first-child > thead:first-child > tr:first-child td:first-child, .panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child td:first-child, .panel > .table:first-child > tbody:first-child > tr:first-child td:first-child, .panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child td:first-child, .panel > .table:first-child > thead:first-child > tr:first-child th:first-child, .panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child th:first-child, .panel > .table:first-child > tbody:first-child > tr:first-child th:first-child, .panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child th:first-child { border-top-left-radius: 1px; } .panel > .table:first-child > thead:first-child > tr:first-child td:last-child, .panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child td:last-child, .panel > .table:first-child > tbody:first-child > tr:first-child td:last-child, .panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child td:last-child, .panel > .table:first-child > thead:first-child > tr:first-child th:last-child, .panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child th:last-child, .panel > .table:first-child > tbody:first-child > tr:first-child th:last-child, .panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child th:last-child { border-top-right-radius: 1px; } .panel > .table:last-child, .panel > .table-responsive:last-child > .table:last-child { border-bottom-right-radius: 1px; border-bottom-left-radius: 1px; } .panel > .table:last-child > tbody:last-child > tr:last-child, .panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child, .panel > .table:last-child > tfoot:last-child > tr:last-child, .panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child { border-bottom-left-radius: 1px; border-bottom-right-radius: 1px; } .panel > .table:last-child > tbody:last-child > tr:last-child td:first-child, .panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child td:first-child, .panel > .table:last-child > tfoot:last-child > tr:last-child td:first-child, .panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child td:first-child, .panel > .table:last-child > tbody:last-child > tr:last-child th:first-child, .panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child th:first-child, .panel > .table:last-child > tfoot:last-child > tr:last-child th:first-child, .panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child th:first-child { border-bottom-left-radius: 1px; } .panel > .table:last-child > tbody:last-child > tr:last-child td:last-child, .panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child td:last-child, .panel > .table:last-child > tfoot:last-child > tr:last-child td:last-child, .panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child td:last-child, .panel > .table:last-child > tbody:last-child > tr:last-child th:last-child, .panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child th:last-child, .panel > .table:last-child > tfoot:last-child > tr:last-child th:last-child, .panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child th:last-child { border-bottom-right-radius: 1px; } .panel > .panel-body + .table, .panel > .panel-body + .table-responsive, .panel > .table + .panel-body, .panel > .table-responsive + .panel-body { border-top: 1px solid #ddd; } .panel > .table > tbody:first-child > tr:first-child th, .panel > .table > tbody:first-child > tr:first-child td { border-top: 0; } .panel > .table-bordered, .panel > .table-responsive > .table-bordered { border: 0; } .panel > .table-bordered > thead > tr > th:first-child, .panel > .table-responsive > .table-bordered > thead > tr > th:first-child, .panel > .table-bordered > tbody > tr > th:first-child, .panel > .table-responsive > .table-bordered > tbody > tr > th:first-child, .panel > .table-bordered > tfoot > tr > th:first-child, .panel > .table-responsive > .table-bordered > tfoot > tr > th:first-child, .panel > .table-bordered > thead > tr > td:first-child, .panel > .table-responsive > .table-bordered > thead > tr > td:first-child, .panel > .table-bordered > tbody > tr > td:first-child, .panel > .table-responsive > .table-bordered > tbody > tr > td:first-child, .panel > .table-bordered > tfoot > tr > td:first-child, .panel > .table-responsive > .table-bordered > tfoot > tr > td:first-child { border-left: 0; } .panel > .table-bordered > thead > tr > th:last-child, .panel > .table-responsive > .table-bordered > thead > tr > th:last-child, .panel > .table-bordered > tbody > tr > th:last-child, .panel > .table-responsive > .table-bordered > tbody > tr > th:last-child, .panel > .table-bordered > tfoot > tr > th:last-child, .panel > .table-responsive > .table-bordered > tfoot > tr > th:last-child, .panel > .table-bordered > thead > tr > td:last-child, .panel > .table-responsive > .table-bordered > thead > tr > td:last-child, .panel > .table-bordered > tbody > tr > td:last-child, .panel > .table-responsive > .table-bordered > tbody > tr > td:last-child, .panel > .table-bordered > tfoot > tr > td:last-child, .panel > .table-responsive > .table-bordered > tfoot > tr > td:last-child { border-right: 0; } .panel > .table-bordered > thead > tr:first-child > td, .panel > .table-responsive > .table-bordered > thead > tr:first-child > td, .panel > .table-bordered > tbody > tr:first-child > td, .panel > .table-responsive > .table-bordered > tbody > tr:first-child > td, .panel > .table-bordered > thead > tr:first-child > th, .panel > .table-responsive > .table-bordered > thead > tr:first-child > th, .panel > .table-bordered > tbody > tr:first-child > th, .panel > .table-responsive > .table-bordered > tbody > tr:first-child > th { border-bottom: 0; } .panel > .table-bordered > tbody > tr:last-child > td, .panel > .table-responsive > .table-bordered > tbody > tr:last-child > td, .panel > .table-bordered > tfoot > tr:last-child > td, .panel > .table-responsive > .table-bordered > tfoot > tr:last-child > td, .panel > .table-bordered > tbody > tr:last-child > th, .panel > .table-responsive > .table-bordered > tbody > tr:last-child > th, .panel > .table-bordered > tfoot > tr:last-child > th, .panel > .table-responsive > .table-bordered > tfoot > tr:last-child > th { border-bottom: 0; } .panel > .table-responsive { border: 0; margin-bottom: 0; } .panel-group { margin-bottom: 18px; } .panel-group .panel { margin-bottom: 0; border-radius: 2px; } .panel-group .panel + .panel { margin-top: 5px; } .panel-group .panel-heading { border-bottom: 0; } .panel-group .panel-heading + .panel-collapse > .panel-body, .panel-group .panel-heading + .panel-collapse > .list-group { border-top: 1px solid #ddd; } .panel-group .panel-footer { border-top: 0; } .panel-group .panel-footer + .panel-collapse .panel-body { border-bottom: 1px solid #ddd; } .panel-default { border-color: #ddd; } .panel-default > .panel-heading { color: #333333; background-color: #f5f5f5; border-color: #ddd; } .panel-default > .panel-heading + .panel-collapse > .panel-body { border-top-color: #ddd; } .panel-default > .panel-heading .badge { color: #f5f5f5; background-color: #333333; } .panel-default > .panel-footer + .panel-collapse > .panel-body { border-bottom-color: #ddd; } .panel-primary { border-color: #337ab7; } .panel-primary > .panel-heading { color: #fff; background-color: #337ab7; border-color: #337ab7; } .panel-primary > .panel-heading + .panel-collapse > .panel-body { border-top-color: #337ab7; } .panel-primary > .panel-heading .badge { color: #337ab7; background-color: #fff; } .panel-primary > .panel-footer + .panel-collapse > .panel-body { border-bottom-color: #337ab7; } .panel-success { border-color: #d6e9c6; } .panel-success > .panel-heading { color: #3c763d; background-color: #dff0d8; border-color: #d6e9c6; } .panel-success > .panel-heading + .panel-collapse > .panel-body { border-top-color: #d6e9c6; } .panel-success > .panel-heading .badge { color: #dff0d8; background-color: #3c763d; } .panel-success > .panel-footer + .panel-collapse > .panel-body { border-bottom-color: #d6e9c6; } .panel-info { border-color: #bce8f1; } .panel-info > .panel-heading { color: #31708f; background-color: #d9edf7; border-color: #bce8f1; } .panel-info > .panel-heading + .panel-collapse > .panel-body { border-top-color: #bce8f1; } .panel-info > .panel-heading .badge { color: #d9edf7; background-color: #31708f; } .panel-info > .panel-footer + .panel-collapse > .panel-body { border-bottom-color: #bce8f1; } .panel-warning { border-color: #faebcc; } .panel-warning > .panel-heading { color: #8a6d3b; background-color: #fcf8e3; border-color: #faebcc; } .panel-warning > .panel-heading + .panel-collapse > .panel-body { border-top-color: #faebcc; } .panel-warning > .panel-heading .badge { color: #fcf8e3; background-color: #8a6d3b; } .panel-warning > .panel-footer + .panel-collapse > .panel-body { border-bottom-color: #faebcc; } .panel-danger { border-color: #ebccd1; } .panel-danger > .panel-heading { color: #a94442; background-color: #f2dede; border-color: #ebccd1; } .panel-danger > .panel-heading + .panel-collapse > .panel-body { border-top-color: #ebccd1; } .panel-danger > .panel-heading .badge { color: #f2dede; background-color: #a94442; } .panel-danger > .panel-footer + .panel-collapse > .panel-body { border-bottom-color: #ebccd1; } .embed-responsive { position: relative; display: block; height: 0; padding: 0; overflow: hidden; } .embed-responsive .embed-responsive-item, .embed-responsive iframe, .embed-responsive embed, .embed-responsive object, .embed-responsive video { position: absolute; top: 0; left: 0; bottom: 0; height: 100%; width: 100%; border: 0; } .embed-responsive-16by9 { padding-bottom: 56.25%; } .embed-responsive-4by3 { padding-bottom: 75%; } .well { min-height: 20px; padding: 19px; margin-bottom: 20px; background-color: #f5f5f5; border: 1px solid #e3e3e3; border-radius: 2px; -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.05); box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.05); } .well blockquote { border-color: #ddd; border-color: rgba(0, 0, 0, 0.15); } .well-lg { padding: 24px; border-radius: 3px; } .well-sm { padding: 9px; border-radius: 1px; } .close { float: right; font-size: 19.5px; font-weight: bold; line-height: 1; color: #000; text-shadow: 0 1px 0 #fff; opacity: 0.2; filter: alpha(opacity=20); } .close:hover, .close:focus { color: #000; text-decoration: none; cursor: pointer; opacity: 0.5; filter: alpha(opacity=50); } button.close { padding: 0; cursor: pointer; background: transparent; border: 0; -webkit-appearance: none; } .modal-open { overflow: hidden; } .modal { display: none; overflow: hidden; position: fixed; top: 0; right: 0; bottom: 0; left: 0; z-index: 1050; -webkit-overflow-scrolling: touch; outline: 0; } .modal.fade .modal-dialog { -webkit-transform: translate(0, -25%); -ms-transform: translate(0, -25%); -o-transform: translate(0, -25%); transform: translate(0, -25%); -webkit-transition: -webkit-transform 0.3s ease-out; -moz-transition: -moz-transform 0.3s ease-out; -o-transition: -o-transform 0.3s ease-out; transition: transform 0.3s ease-out; } .modal.in .modal-dialog { -webkit-transform: translate(0, 0); -ms-transform: translate(0, 0); -o-transform: translate(0, 0); transform: translate(0, 0); } .modal-open .modal { overflow-x: hidden; overflow-y: auto; } .modal-dialog { position: relative; width: auto; margin: 10px; } .modal-content { position: relative; background-color: #fff; border: 1px solid #999; border: 1px solid rgba(0, 0, 0, 0.2); border-radius: 3px; -webkit-box-shadow: 0 3px 9px rgba(0, 0, 0, 0.5); box-shadow: 0 3px 9px rgba(0, 0, 0, 0.5); background-clip: padding-box; outline: 0; } .modal-backdrop { position: fixed; top: 0; right: 0; bottom: 0; left: 0; z-index: 1040; background-color: #000; } .modal-backdrop.fade { opacity: 0; filter: alpha(opacity=0); } .modal-backdrop.in { opacity: 0.5; filter: alpha(opacity=50); } .modal-header { padding: 15px; border-bottom: 1px solid #e5e5e5; } .modal-header .close { margin-top: -2px; } .modal-title { margin: 0; line-height: 1.42857143; } .modal-body { position: relative; padding: 15px; } .modal-footer { padding: 15px; text-align: right; border-top: 1px solid #e5e5e5; } .modal-footer .btn + .btn { margin-left: 5px; margin-bottom: 0; } .modal-footer .btn-group .btn + .btn { margin-left: -1px; } .modal-footer .btn-block + .btn-block { margin-left: 0; } .modal-scrollbar-measure { position: absolute; top: -9999px; width: 50px; height: 50px; overflow: scroll; } @media (min-width: 768px) { .modal-dialog { width: 600px; margin: 30px auto; } .modal-content { -webkit-box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5); box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5); } .modal-sm { width: 300px; } } @media (min-width: 992px) { .modal-lg { width: 900px; } } .tooltip { position: absolute; z-index: 1070; display: block; font-family: "Helvetica Neue", Helvetica, Arial, sans-serif; font-style: normal; font-weight: normal; letter-spacing: normal; line-break: auto; line-height: 1.42857143; text-align: left; text-align: start; text-decoration: none; text-shadow: none; text-transform: none; white-space: normal; word-break: normal; word-spacing: normal; word-wrap: normal; font-size: 12px; opacity: 0; filter: alpha(opacity=0); } .tooltip.in { opacity: 0.9; filter: alpha(opacity=90); } .tooltip.top { margin-top: -3px; padding: 5px 0; } .tooltip.right { margin-left: 3px; padding: 0 5px; } .tooltip.bottom { margin-top: 3px; padding: 5px 0; } .tooltip.left { margin-left: -3px; padding: 0 5px; } .tooltip-inner { max-width: 200px; padding: 3px 8px; color: #fff; text-align: center; background-color: #000; border-radius: 2px; } .tooltip-arrow { position: absolute; width: 0; height: 0; border-color: transparent; border-style: solid; } .tooltip.top .tooltip-arrow { bottom: 0; left: 50%; margin-left: -5px; border-width: 5px 5px 0; border-top-color: #000; } .tooltip.top-left .tooltip-arrow { bottom: 0; right: 5px; margin-bottom: -5px; border-width: 5px 5px 0; border-top-color: #000; } .tooltip.top-right .tooltip-arrow { bottom: 0; left: 5px; margin-bottom: -5px; border-width: 5px 5px 0; border-top-color: #000; } .tooltip.right .tooltip-arrow { top: 50%; left: 0; margin-top: -5px; border-width: 5px 5px 5px 0; border-right-color: #000; } .tooltip.left .tooltip-arrow { top: 50%; right: 0; margin-top: -5px; border-width: 5px 0 5px 5px; border-left-color: #000; } .tooltip.bottom .tooltip-arrow { top: 0; left: 50%; margin-left: -5px; border-width: 0 5px 5px; border-bottom-color: #000; } .tooltip.bottom-left .tooltip-arrow { top: 0; right: 5px; margin-top: -5px; border-width: 0 5px 5px; border-bottom-color: #000; } .tooltip.bottom-right .tooltip-arrow { top: 0; left: 5px; margin-top: -5px; border-width: 0 5px 5px; border-bottom-color: #000; } .popover { position: absolute; top: 0; left: 0; z-index: 1060; display: none; max-width: 276px; padding: 1px; font-family: "Helvetica Neue", Helvetica, Arial, sans-serif; font-style: normal; font-weight: normal; letter-spacing: normal; line-break: auto; line-height: 1.42857143; text-align: left; text-align: start; text-decoration: none; text-shadow: none; text-transform: none; white-space: normal; word-break: normal; word-spacing: normal; word-wrap: normal; font-size: 13px; background-color: #fff; background-clip: padding-box; border: 1px solid #ccc; border: 1px solid rgba(0, 0, 0, 0.2); border-radius: 3px; -webkit-box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2); box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2); } .popover.top { margin-top: -10px; } .popover.right { margin-left: 10px; } .popover.bottom { margin-top: 10px; } .popover.left { margin-left: -10px; } .popover-title { margin: 0; padding: 8px 14px; font-size: 13px; background-color: #f7f7f7; border-bottom: 1px solid #ebebeb; border-radius: 2px 2px 0 0; } .popover-content { padding: 9px 14px; } .popover > .arrow, .popover > .arrow:after { position: absolute; display: block; width: 0; height: 0; border-color: transparent; border-style: solid; } .popover > .arrow { border-width: 11px; } .popover > .arrow:after { border-width: 10px; content: ""; } .popover.top > .arrow { left: 50%; margin-left: -11px; border-bottom-width: 0; border-top-color: #999999; border-top-color: rgba(0, 0, 0, 0.25); bottom: -11px; } .popover.top > .arrow:after { content: " "; bottom: 1px; margin-left: -10px; border-bottom-width: 0; border-top-color: #fff; } .popover.right > .arrow { top: 50%; left: -11px; margin-top: -11px; border-left-width: 0; border-right-color: #999999; border-right-color: rgba(0, 0, 0, 0.25); } .popover.right > .arrow:after { content: " "; left: 1px; bottom: -10px; border-left-width: 0; border-right-color: #fff; } .popover.bottom > .arrow { left: 50%; margin-left: -11px; border-top-width: 0; border-bottom-color: #999999; border-bottom-color: rgba(0, 0, 0, 0.25); top: -11px; } .popover.bottom > .arrow:after { content: " "; top: 1px; margin-left: -10px; border-top-width: 0; border-bottom-color: #fff; } .popover.left > .arrow { top: 50%; right: -11px; margin-top: -11px; border-right-width: 0; border-left-color: #999999; border-left-color: rgba(0, 0, 0, 0.25); } .popover.left > .arrow:after { content: " "; right: 1px; border-right-width: 0; border-left-color: #fff; bottom: -10px; } .carousel { position: relative; } .carousel-inner { position: relative; overflow: hidden; width: 100%; } .carousel-inner > .item { display: none; position: relative; -webkit-transition: 0.6s ease-in-out left; -o-transition: 0.6s ease-in-out left; transition: 0.6s ease-in-out left; } .carousel-inner > .item > img, .carousel-inner > .item > a > img { line-height: 1; } @media all and (transform-3d), (-webkit-transform-3d) { .carousel-inner > .item { -webkit-transition: -webkit-transform 0.6s ease-in-out; -moz-transition: -moz-transform 0.6s ease-in-out; -o-transition: -o-transform 0.6s ease-in-out; transition: transform 0.6s ease-in-out; -webkit-backface-visibility: hidden; -moz-backface-visibility: hidden; backface-visibility: hidden; -webkit-perspective: 1000px; -moz-perspective: 1000px; perspective: 1000px; } .carousel-inner > .item.next, .carousel-inner > .item.active.right { -webkit-transform: translate3d(100%, 0, 0); transform: translate3d(100%, 0, 0); left: 0; } .carousel-inner > .item.prev, .carousel-inner > .item.active.left { -webkit-transform: translate3d(-100%, 0, 0); transform: translate3d(-100%, 0, 0); left: 0; } .carousel-inner > .item.next.left, .carousel-inner > .item.prev.right, .carousel-inner > .item.active { -webkit-transform: translate3d(0, 0, 0); transform: translate3d(0, 0, 0); left: 0; } } .carousel-inner > .active, .carousel-inner > .next, .carousel-inner > .prev { display: block; } .carousel-inner > .active { left: 0; } .carousel-inner > .next, .carousel-inner > .prev { position: absolute; top: 0; width: 100%; } .carousel-inner > .next { left: 100%; } .carousel-inner > .prev { left: -100%; } .carousel-inner > .next.left, .carousel-inner > .prev.right { left: 0; } .carousel-inner > .active.left { left: -100%; } .carousel-inner > .active.right { left: 100%; } .carousel-control { position: absolute; top: 0; left: 0; bottom: 0; width: 15%; opacity: 0.5; filter: alpha(opacity=50); font-size: 20px; color: #fff; text-align: center; text-shadow: 0 1px 2px rgba(0, 0, 0, 0.6); background-color: rgba(0, 0, 0, 0); } .carousel-control.left { background-image: -webkit-linear-gradient(left, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%); background-image: -o-linear-gradient(left, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%); background-image: linear-gradient(to right, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%); background-repeat: repeat-x; filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#80000000', endColorstr='#00000000', GradientType=1); } .carousel-control.right { left: auto; right: 0; background-image: -webkit-linear-gradient(left, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%); background-image: -o-linear-gradient(left, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%); background-image: linear-gradient(to right, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%); background-repeat: repeat-x; filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#00000000', endColorstr='#80000000', GradientType=1); } .carousel-control:hover, .carousel-control:focus { outline: 0; color: #fff; text-decoration: none; opacity: 0.9; filter: alpha(opacity=90); } .carousel-control .icon-prev, .carousel-control .icon-next, .carousel-control .glyphicon-chevron-left, .carousel-control .glyphicon-chevron-right { position: absolute; top: 50%; margin-top: -10px; z-index: 5; display: inline-block; } .carousel-control .icon-prev, .carousel-control .glyphicon-chevron-left { left: 50%; margin-left: -10px; } .carousel-control .icon-next, .carousel-control .glyphicon-chevron-right { right: 50%; margin-right: -10px; } .carousel-control .icon-prev, .carousel-control .icon-next { width: 20px; height: 20px; line-height: 1; font-family: serif; } .carousel-control .icon-prev:before { content: '\\2039'; } .carousel-control .icon-next:before { content: '\\203a'; } .carousel-indicators { position: absolute; bottom: 10px; left: 50%; z-index: 15; width: 60%; margin-left: -30%; padding-left: 0; list-style: none; text-align: center; } .carousel-indicators li { display: inline-block; width: 10px; height: 10px; margin: 1px; text-indent: -999px; border: 1px solid #fff; border-radius: 10px; cursor: pointer; background-color: #000 \\9; background-color: rgba(0, 0, 0, 0); } .carousel-indicators .active { margin: 0; width: 12px; height: 12px; background-color: #fff; } .carousel-caption { position: absolute; left: 15%; right: 15%; bottom: 20px; z-index: 10; padding-top: 20px; padding-bottom: 20px; color: #fff; text-align: center; text-shadow: 0 1px 2px rgba(0, 0, 0, 0.6); } .carousel-caption .btn { text-shadow: none; } @media screen and (min-width: 768px) { .carousel-control .glyphicon-chevron-left, .carousel-control .glyphicon-chevron-right, .carousel-control .icon-prev, .carousel-control .icon-next { width: 30px; height: 30px; margin-top: -10px; font-size: 30px; } .carousel-control .glyphicon-chevron-left, .carousel-control .icon-prev { margin-left: -10px; } .carousel-control .glyphicon-chevron-right, .carousel-control .icon-next { margin-right: -10px; } .carousel-caption { left: 20%; right: 20%; padding-bottom: 30px; } .carousel-indicators { bottom: 20px; } } .clearfix:before, .clearfix:after, .dl-horizontal dd:before, .dl-horizontal dd:after, .container:before, .container:after, .container-fluid:before, .container-fluid:after, .row:before, .row:after, .form-horizontal .form-group:before, .form-horizontal .form-group:after, .btn-toolbar:before, .btn-toolbar:after, .btn-group-vertical > .btn-group:before, .btn-group-vertical > .btn-group:after, .nav:before, .nav:after, .navbar:before, .navbar:after, .navbar-header:before, .navbar-header:after, .navbar-collapse:before, .navbar-collapse:after, .pager:before, .pager:after, .panel-body:before, .panel-body:after, .modal-header:before, .modal-header:after, .modal-footer:before, .modal-footer:after, .item\_buttons:before, .item\_buttons:after { content: " "; display: table; } .clearfix:after, .dl-horizontal dd:after, .container:after, .container-fluid:after, .row:after, .form-horizontal .form-group:after, .btn-toolbar:after, .btn-group-vertical > .btn-group:after, .nav:after, .navbar:after, .navbar-header:after, .navbar-collapse:after, .pager:after, .panel-body:after, .modal-header:after, .modal-footer:after, .item\_buttons:after { clear: both; } .center-block { display: block; margin-left: auto; margin-right: auto; } .pull-right { float: right !important; } .pull-left { float: left !important; } .hide { display: none !important; } .show { display: block !important; } .invisible { visibility: hidden; } .text-hide { font: 0/0 a; color: transparent; text-shadow: none; background-color: transparent; border: 0; } .hidden { display: none !important; } .affix { position: fixed; } @-ms-viewport { width: device-width; } .visible-xs, .visible-sm, .visible-md, .visible-lg { display: none !important; } .visible-xs-block, .visible-xs-inline, .visible-xs-inline-block, .visible-sm-block, .visible-sm-inline, .visible-sm-inline-block, .visible-md-block, .visible-md-inline, .visible-md-inline-block, .visible-lg-block, .visible-lg-inline, .visible-lg-inline-block { display: none !important; } @media (max-width: 767px) { .visible-xs { display: block !important; } table.visible-xs { display: table !important; } tr.visible-xs { display: table-row !important; } th.visible-xs, td.visible-xs { display: table-cell !important; } } @media (max-width: 767px) { .visible-xs-block { display: block !important; } } @media (max-width: 767px) { .visible-xs-inline { display: inline !important; } } @media (max-width: 767px) { .visible-xs-inline-block { display: inline-block !important; } } @media (min-width: 768px) and (max-width: 991px) { .visible-sm { display: block !important; } table.visible-sm { display: table !important; } tr.visible-sm { display: table-row !important; } th.visible-sm, td.visible-sm { display: table-cell !important; } } @media (min-width: 768px) and (max-width: 991px) { .visible-sm-block { display: block !important; } } @media (min-width: 768px) and (max-width: 991px) { .visible-sm-inline { display: inline !important; } } @media (min-width: 768px) and (max-width: 991px) { .visible-sm-inline-block { display: inline-block !important; } } @media (min-width: 992px) and (max-width: 1199px) { .visible-md { display: block !important; } table.visible-md { display: table !important; } tr.visible-md { display: table-row !important; } th.visible-md, td.visible-md { display: table-cell !important; } } @media (min-width: 992px) and (max-width: 1199px) { .visible-md-block { display: block !important; } } @media (min-width: 992px) and (max-width: 1199px) { .visible-md-inline { display: inline !important; } } @media (min-width: 992px) and (max-width: 1199px) { .visible-md-inline-block { display: inline-block !important; } } @media (min-width: 1200px) { .visible-lg { display: block !important; } table.visible-lg { display: table !important; } tr.visible-lg { display: table-row !important; } th.visible-lg, td.visible-lg { display: table-cell !important; } } @media (min-width: 1200px) { .visible-lg-block { display: block !important; } } @media (min-width: 1200px) { .visible-lg-inline { display: inline !important; } } @media (min-width: 1200px) { .visible-lg-inline-block { display: inline-block !important; } } @media (max-width: 767px) { .hidden-xs { display: none !important; } } @media (min-width: 768px) and (max-width: 991px) { .hidden-sm { display: none !important; } } @media (min-width: 992px) and (max-width: 1199px) { .hidden-md { display: none !important; } } @media (min-width: 1200px) { .hidden-lg { display: none !important; } } .visible-print { display: none !important; } @media print { .visible-print { display: block !important; } table.visible-print { display: table !important; } tr.visible-print { display: table-row !important; } th.visible-print, td.visible-print { display: table-cell !important; } } .visible-print-block { display: none !important; } @media print { .visible-print-block { display: block !important; } } .visible-print-inline { display: none !important; } @media print { .visible-print-inline { display: inline !important; } } .visible-print-inline-block { display: none !important; } @media print { .visible-print-inline-block { display: inline-block !important; } } @media print { .hidden-print { display: none !important; } } /\*! \* \* Font Awesome \* \*/ /\*! \* Font Awesome 4.7.0 by @davegandy - http://fontawesome.io - @fontawesome \* License - http://fontawesome.io/license (Font: SIL OFL 1.1, CSS: MIT License) \*/ /\* FONT PATH \* -------------------------- \*/ @font-face { font-family: 'FontAwesome'; src: url('../components/font-awesome/fonts/fontawesome-webfont.eot?v=4.7.0'); src: url('../components/font-awesome/fonts/fontawesome-webfont.eot?#iefix&v=4.7.0') format('embedded-opentype'), url('../components/font-awesome/fonts/fontawesome-webfont.woff2?v=4.7.0') format('woff2'), url('../components/font-awesome/fonts/fontawesome-webfont.woff?v=4.7.0') format('woff'), url('../components/font-awesome/fonts/fontawesome-webfont.ttf?v=4.7.0') format('truetype'), url('../components/font-awesome/fonts/fontawesome-webfont.svg?v=4.7.0#fontawesomeregular') format('svg'); font-weight: normal; font-style: normal; } .fa { display: inline-block; font: normal normal normal 14px/1 FontAwesome; font-size: inherit; text-rendering: auto; -webkit-font-smoothing: antialiased; -moz-osx-font-smoothing: grayscale; } /\* makes the font 33% larger relative to the icon container \*/ .fa-lg { font-size: 1.33333333em; line-height: 0.75em; vertical-align: -15%; } .fa-2x { font-size: 2em; } .fa-3x { font-size: 3em; } .fa-4x { font-size: 4em; } .fa-5x { font-size: 5em; } .fa-fw { width: 1.28571429em; text-align: center; } .fa-ul { padding-left: 0; margin-left: 2.14285714em; list-style-type: none; } .fa-ul > li { position: relative; } .fa-li { position: absolute; left: -2.14285714em; width: 2.14285714em; top: 0.14285714em; text-align: center; } .fa-li.fa-lg { left: -1.85714286em; } .fa-border { padding: .2em .25em .15em; border: solid 0.08em #eee; border-radius: .1em; } .fa-pull-left { float: left; } .fa-pull-right { float: right; } .fa.fa-pull-left { margin-right: .3em; } .fa.fa-pull-right { margin-left: .3em; } /\* Deprecated as of 4.4.0 \*/ .pull-right { float: right; } .pull-left { float: left; } .fa.pull-left { margin-right: .3em; } .fa.pull-right { margin-left: .3em; } .fa-spin { -webkit-animation: fa-spin 2s infinite linear; animation: fa-spin 2s infinite linear; } .fa-pulse { -webkit-animation: fa-spin 1s infinite steps(8); animation: fa-spin 1s infinite steps(8); } @-webkit-keyframes fa-spin { 0% { -webkit-transform: rotate(0deg); transform: rotate(0deg); } 100% { -webkit-transform: rotate(359deg); transform: rotate(359deg); } } @keyframes fa-spin { 0% { -webkit-transform: rotate(0deg); transform: rotate(0deg); } 100% { -webkit-transform: rotate(359deg); transform: rotate(359deg); } } .fa-rotate-90 { -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=1)"; -webkit-transform: rotate(90deg); -ms-transform: rotate(90deg); transform: rotate(90deg); } .fa-rotate-180 { -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=2)"; -webkit-transform: rotate(180deg); -ms-transform: rotate(180deg); transform: rotate(180deg); } .fa-rotate-270 { -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=3)"; -webkit-transform: rotate(270deg); -ms-transform: rotate(270deg); transform: rotate(270deg); } .fa-flip-horizontal { -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=0, mirror=1)"; -webkit-transform: scale(-1, 1); -ms-transform: scale(-1, 1); transform: scale(-1, 1); } .fa-flip-vertical { -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=2, mirror=1)"; -webkit-transform: scale(1, -1); -ms-transform: scale(1, -1); transform: scale(1, -1); } :root .fa-rotate-90, :root .fa-rotate-180, :root .fa-rotate-270, :root .fa-flip-horizontal, :root .fa-flip-vertical { filter: none; } .fa-stack { position: relative; display: inline-block; width: 2em; height: 2em; line-height: 2em; vertical-align: middle; } .fa-stack-1x, .fa-stack-2x { position: absolute; left: 0; width: 100%; text-align: center; } .fa-stack-1x { line-height: inherit; } .fa-stack-2x { font-size: 2em; } .fa-inverse { color: #fff; } /\* Font Awesome uses the Unicode Private Use Area (PUA) to ensure screen readers do not read off random characters that represent icons \*/ .fa-glass:before { content: "\\f000"; } .fa-music:before { content: "\\f001"; } .fa-search:before { content: "\\f002"; } .fa-envelope-o:before { content: "\\f003"; } .fa-heart:before { content: "\\f004"; } .fa-star:before { content: "\\f005"; } .fa-star-o:before { content: "\\f006"; } .fa-user:before { content: "\\f007"; } .fa-film:before { content: "\\f008"; } .fa-th-large:before { content: "\\f009"; } .fa-th:before { content: "\\f00a"; } .fa-th-list:before { content: "\\f00b"; } .fa-check:before { content: "\\f00c"; } .fa-remove:before, .fa-close:before, .fa-times:before { content: "\\f00d"; } .fa-search-plus:before { content: "\\f00e"; } .fa-search-minus:before { content: "\\f010"; } .fa-power-off:before { content: "\\f011"; } .fa-signal:before { content: "\\f012"; } .fa-gear:before, .fa-cog:before { content: "\\f013"; } .fa-trash-o:before { content: "\\f014"; } .fa-home:before { content: "\\f015"; } .fa-file-o:before { content: "\\f016"; } .fa-clock-o:before { content: "\\f017"; } .fa-road:before { content: "\\f018"; } .fa-download:before { content: "\\f019"; } .fa-arrow-circle-o-down:before { content: "\\f01a"; } .fa-arrow-circle-o-up:before { content: "\\f01b"; } .fa-inbox:before { content: "\\f01c"; } .fa-play-circle-o:before { content: "\\f01d"; } .fa-rotate-right:before, .fa-repeat:before { content: "\\f01e"; } .fa-refresh:before { content: "\\f021"; } .fa-list-alt:before { content: "\\f022"; } .fa-lock:before { content: "\\f023"; } .fa-flag:before { content: "\\f024"; } .fa-headphones:before { content: "\\f025"; } .fa-volume-off:before { content: "\\f026"; } .fa-volume-down:before { content: "\\f027"; } .fa-volume-up:before { content: "\\f028"; } .fa-qrcode:before { content: "\\f029"; } .fa-barcode:before { content: "\\f02a"; } .fa-tag:before { content: "\\f02b"; } .fa-tags:before { content: "\\f02c"; } .fa-book:before { content: "\\f02d"; } .fa-bookmark:before { content: "\\f02e"; } .fa-print:before { content: "\\f02f"; } .fa-camera:before { content: "\\f030"; } .fa-font:before { content: "\\f031"; } .fa-bold:before { content: "\\f032"; } .fa-italic:before { content: "\\f033"; } .fa-text-height:before { content: "\\f034"; } .fa-text-width:before { content: "\\f035"; } .fa-align-left:before { content: "\\f036"; } .fa-align-center:before { content: "\\f037"; } .fa-align-right:before { content: "\\f038"; } .fa-align-justify:before { content: "\\f039"; } .fa-list:before { content: "\\f03a"; } .fa-dedent:before, .fa-outdent:before { content: "\\f03b"; } .fa-indent:before { content: "\\f03c"; } .fa-video-camera:before { content: "\\f03d"; } .fa-photo:before, .fa-image:before, .fa-picture-o:before { content: "\\f03e"; } .fa-pencil:before { content: "\\f040"; } .fa-map-marker:before { content: "\\f041"; } .fa-adjust:before { content: "\\f042"; } .fa-tint:before { content: "\\f043"; } .fa-edit:before, .fa-pencil-square-o:before { content: "\\f044"; } .fa-share-square-o:before { content: "\\f045"; } .fa-check-square-o:before { content: "\\f046"; } .fa-arrows:before { content: "\\f047"; } .fa-step-backward:before { content: "\\f048"; } .fa-fast-backward:before { content: "\\f049"; } .fa-backward:before { content: "\\f04a"; } .fa-play:before { content: "\\f04b"; } .fa-pause:before { content: "\\f04c"; } .fa-stop:before { content: "\\f04d"; } .fa-forward:before { content: "\\f04e"; } .fa-fast-forward:before { content: "\\f050"; } .fa-step-forward:before { content: "\\f051"; } .fa-eject:before { content: "\\f052"; } .fa-chevron-left:before { content: "\\f053"; } .fa-chevron-right:before { content: "\\f054"; } .fa-plus-circle:before { content: "\\f055"; } .fa-minus-circle:before { content: "\\f056"; } .fa-times-circle:before { content: "\\f057"; } .fa-check-circle:before { content: "\\f058"; } .fa-question-circle:before { content: "\\f059"; } .fa-info-circle:before { content: "\\f05a"; } .fa-crosshairs:before { content: "\\f05b"; } .fa-times-circle-o:before { content: "\\f05c"; } .fa-check-circle-o:before { content: "\\f05d"; } .fa-ban:before { content: "\\f05e"; } .fa-arrow-left:before { content: "\\f060"; } .fa-arrow-right:before { content: "\\f061"; } .fa-arrow-up:before { content: "\\f062"; } .fa-arrow-down:before { content: "\\f063"; } .fa-mail-forward:before, .fa-share:before { content: "\\f064"; } .fa-expand:before { content: "\\f065"; } .fa-compress:before { content: "\\f066"; } .fa-plus:before { content: "\\f067"; } .fa-minus:before { content: "\\f068"; } .fa-asterisk:before { content: "\\f069"; } .fa-exclamation-circle:before { content: "\\f06a"; } .fa-gift:before { content: "\\f06b"; } .fa-leaf:before { content: "\\f06c"; } .fa-fire:before { content: "\\f06d"; } .fa-eye:before { content: "\\f06e"; } .fa-eye-slash:before { content: "\\f070"; } .fa-warning:before, .fa-exclamation-triangle:before { content: "\\f071"; } .fa-plane:before { content: "\\f072"; } .fa-calendar:before { content: "\\f073"; } .fa-random:before { content: "\\f074"; } .fa-comment:before { content: "\\f075"; } .fa-magnet:before { content: "\\f076"; } .fa-chevron-up:before { content: "\\f077"; } .fa-chevron-down:before { content: "\\f078"; } .fa-retweet:before { content: "\\f079"; } .fa-shopping-cart:before { content: "\\f07a"; } .fa-folder:before { content: "\\f07b"; } .fa-folder-open:before { content: "\\f07c"; } .fa-arrows-v:before { content: "\\f07d"; } .fa-arrows-h:before { content: "\\f07e"; } .fa-bar-chart-o:before, .fa-bar-chart:before { content: "\\f080"; } .fa-twitter-square:before { content: "\\f081"; } .fa-facebook-square:before { content: "\\f082"; } .fa-camera-retro:before { content: "\\f083"; } .fa-key:before { content: "\\f084"; } .fa-gears:before, .fa-cogs:before { content: "\\f085"; } .fa-comments:before { content: "\\f086"; } .fa-thumbs-o-up:before { content: "\\f087"; } .fa-thumbs-o-down:before { content: "\\f088"; } .fa-star-half:before { content: "\\f089"; } .fa-heart-o:before { content: "\\f08a"; } .fa-sign-out:before { content: "\\f08b"; } .fa-linkedin-square:before { content: "\\f08c"; } .fa-thumb-tack:before { content: "\\f08d"; } .fa-external-link:before { content: "\\f08e"; } .fa-sign-in:before { content: "\\f090"; } .fa-trophy:before { content: "\\f091"; } .fa-github-square:before { content: "\\f092"; } .fa-upload:before { content: "\\f093"; } .fa-lemon-o:before { content: "\\f094"; } .fa-phone:before { content: "\\f095"; } .fa-square-o:before { content: "\\f096"; } .fa-bookmark-o:before { content: "\\f097"; } .fa-phone-square:before { content: "\\f098"; } .fa-twitter:before { content: "\\f099"; } .fa-facebook-f:before, .fa-facebook:before { content: "\\f09a"; } .fa-github:before { content: "\\f09b"; } .fa-unlock:before { content: "\\f09c"; } .fa-credit-card:before { content: "\\f09d"; } .fa-feed:before, .fa-rss:before { content: "\\f09e"; } .fa-hdd-o:before { content: "\\f0a0"; } .fa-bullhorn:before { content: "\\f0a1"; } .fa-bell:before { content: "\\f0f3"; } .fa-certificate:before { content: "\\f0a3"; } .fa-hand-o-right:before { content: "\\f0a4"; } .fa-hand-o-left:before { content: "\\f0a5"; } .fa-hand-o-up:before { content: "\\f0a6"; } .fa-hand-o-down:before { content: "\\f0a7"; } .fa-arrow-circle-left:before { content: "\\f0a8"; } .fa-arrow-circle-right:before { content: "\\f0a9"; } .fa-arrow-circle-up:before { content: "\\f0aa"; } .fa-arrow-circle-down:before { content: "\\f0ab"; } .fa-globe:before { content: "\\f0ac"; } .fa-wrench:before { content: "\\f0ad"; } .fa-tasks:before { content: "\\f0ae"; } .fa-filter:before { content: "\\f0b0"; } .fa-briefcase:before { content: "\\f0b1"; } .fa-arrows-alt:before { content: "\\f0b2"; } .fa-group:before, .fa-users:before { content: "\\f0c0"; } .fa-chain:before, .fa-link:before { content: "\\f0c1"; } .fa-cloud:before { content: "\\f0c2"; } .fa-flask:before { content: "\\f0c3"; } .fa-cut:before, .fa-scissors:before { content: "\\f0c4"; } .fa-copy:before, .fa-files-o:before { content: "\\f0c5"; } .fa-paperclip:before { content: "\\f0c6"; } .fa-save:before, .fa-floppy-o:before { content: "\\f0c7"; } .fa-square:before { content: "\\f0c8"; } .fa-navicon:before, .fa-reorder:before, .fa-bars:before { content: "\\f0c9"; } .fa-list-ul:before { content: "\\f0ca"; } .fa-list-ol:before { content: "\\f0cb"; } .fa-strikethrough:before { content: "\\f0cc"; } .fa-underline:before { content: "\\f0cd"; } .fa-table:before { content: "\\f0ce"; } .fa-magic:before { content: "\\f0d0"; } .fa-truck:before { content: "\\f0d1"; } .fa-pinterest:before { content: "\\f0d2"; } .fa-pinterest-square:before { content: "\\f0d3"; } .fa-google-plus-square:before { content: "\\f0d4"; } .fa-google-plus:before { content: "\\f0d5"; } .fa-money:before { content: "\\f0d6"; } .fa-caret-down:before { content: "\\f0d7"; } .fa-caret-up:before { content: "\\f0d8"; } .fa-caret-left:before { content: "\\f0d9"; } .fa-caret-right:before { content: "\\f0da"; } .fa-columns:before { content: "\\f0db"; } .fa-unsorted:before, .fa-sort:before { content: "\\f0dc"; } .fa-sort-down:before, .fa-sort-desc:before { content: "\\f0dd"; } .fa-sort-up:before, .fa-sort-asc:before { content: "\\f0de"; } .fa-envelope:before { content: "\\f0e0"; } .fa-linkedin:before { content: "\\f0e1"; } .fa-rotate-left:before, .fa-undo:before { content: "\\f0e2"; } .fa-legal:before, .fa-gavel:before { content: "\\f0e3"; } .fa-dashboard:before, .fa-tachometer:before { content: "\\f0e4"; } .fa-comment-o:before { content: "\\f0e5"; } .fa-comments-o:before { content: "\\f0e6"; } .fa-flash:before, .fa-bolt:before { content: "\\f0e7"; } .fa-sitemap:before { content: "\\f0e8"; } .fa-umbrella:before { content: "\\f0e9"; } .fa-paste:before, .fa-clipboard:before { content: "\\f0ea"; } .fa-lightbulb-o:before { content: "\\f0eb"; } .fa-exchange:before { content: "\\f0ec"; } .fa-cloud-download:before { content: "\\f0ed"; } .fa-cloud-upload:before { content: "\\f0ee"; } .fa-user-md:before { content: "\\f0f0"; } .fa-stethoscope:before { content: "\\f0f1"; } .fa-suitcase:before { content: "\\f0f2"; } .fa-bell-o:before { content: "\\f0a2"; } .fa-coffee:before { content: "\\f0f4"; } .fa-cutlery:before { content: "\\f0f5"; } .fa-file-text-o:before { content: "\\f0f6"; } .fa-building-o:before { content: "\\f0f7"; } .fa-hospital-o:before { content: "\\f0f8"; } .fa-ambulance:before { content: "\\f0f9"; } .fa-medkit:before { content: "\\f0fa"; } .fa-fighter-jet:before { content: "\\f0fb"; } .fa-beer:before { content: "\\f0fc"; } .fa-h-square:before { content: "\\f0fd"; } .fa-plus-square:before { content: "\\f0fe"; } .fa-angle-double-left:before { content: "\\f100"; } .fa-angle-double-right:before { content: "\\f101"; } .fa-angle-double-up:before { content: "\\f102"; } .fa-angle-double-down:before { content: "\\f103"; } .fa-angle-left:before { content: "\\f104"; } .fa-angle-right:before { content: "\\f105"; } .fa-angle-up:before { content: "\\f106"; } .fa-angle-down:before { content: "\\f107"; } .fa-desktop:before { content: "\\f108"; } .fa-laptop:before { content: "\\f109"; } .fa-tablet:before { content: "\\f10a"; } .fa-mobile-phone:before, .fa-mobile:before { content: "\\f10b"; } .fa-circle-o:before { content: "\\f10c"; } .fa-quote-left:before { content: "\\f10d"; } .fa-quote-right:before { content: "\\f10e"; } .fa-spinner:before { content: "\\f110"; } .fa-circle:before { content: "\\f111"; } .fa-mail-reply:before, .fa-reply:before { content: "\\f112"; } .fa-github-alt:before { content: "\\f113"; } .fa-folder-o:before { content: "\\f114"; } .fa-folder-open-o:before { content: "\\f115"; } .fa-smile-o:before { content: "\\f118"; } .fa-frown-o:before { content: "\\f119"; } .fa-meh-o:before { content: "\\f11a"; } .fa-gamepad:before { content: "\\f11b"; } .fa-keyboard-o:before { content: "\\f11c"; } .fa-flag-o:before { content: "\\f11d"; } .fa-flag-checkered:before { content: "\\f11e"; } .fa-terminal:before { content: "\\f120"; } .fa-code:before { content: "\\f121"; } .fa-mail-reply-all:before, .fa-reply-all:before { content: "\\f122"; } .fa-star-half-empty:before, .fa-star-half-full:before, .fa-star-half-o:before { content: "\\f123"; } .fa-location-arrow:before { content: "\\f124"; } .fa-crop:before { content: "\\f125"; } .fa-code-fork:before { content: "\\f126"; } .fa-unlink:before, .fa-chain-broken:before { content: "\\f127"; } .fa-question:before { content: "\\f128"; } .fa-info:before { content: "\\f129"; } .fa-exclamation:before { content: "\\f12a"; } .fa-superscript:before { content: "\\f12b"; } .fa-subscript:before { content: "\\f12c"; } .fa-eraser:before { content: "\\f12d"; } .fa-puzzle-piece:before { content: "\\f12e"; } .fa-microphone:before { content: "\\f130"; } .fa-microphone-slash:before { content: "\\f131"; } .fa-shield:before { content: "\\f132"; } .fa-calendar-o:before { content: "\\f133"; } .fa-fire-extinguisher:before { content: "\\f134"; } .fa-rocket:before { content: "\\f135"; } .fa-maxcdn:before { content: "\\f136"; } .fa-chevron-circle-left:before { content: "\\f137"; } .fa-chevron-circle-right:before { content: "\\f138"; } .fa-chevron-circle-up:before { content: "\\f139"; } .fa-chevron-circle-down:before { content: "\\f13a"; } .fa-html5:before { content: "\\f13b"; } .fa-css3:before { content: "\\f13c"; } .fa-anchor:before { content: "\\f13d"; } .fa-unlock-alt:before { content: "\\f13e"; } .fa-bullseye:before { content: "\\f140"; } .fa-ellipsis-h:before { content: "\\f141"; } .fa-ellipsis-v:before { content: "\\f142"; } .fa-rss-square:before { content: "\\f143"; } .fa-play-circle:before { content: "\\f144"; } .fa-ticket:before { content: "\\f145"; } .fa-minus-square:before { content: "\\f146"; } .fa-minus-square-o:before { content: "\\f147"; } .fa-level-up:before { content: "\\f148"; } .fa-level-down:before { content: "\\f149"; } .fa-check-square:before { content: "\\f14a"; } .fa-pencil-square:before { content: "\\f14b"; } .fa-external-link-square:before { content: "\\f14c"; } .fa-share-square:before { content: "\\f14d"; } .fa-compass:before { content: "\\f14e"; } .fa-toggle-down:before, .fa-caret-square-o-down:before { content: "\\f150"; } .fa-toggle-up:before, .fa-caret-square-o-up:before { content: "\\f151"; } .fa-toggle-right:before, .fa-caret-square-o-right:before { content: "\\f152"; } .fa-euro:before, .fa-eur:before { content: "\\f153"; } .fa-gbp:before { content: "\\f154"; } .fa-dollar:before, .fa-usd:before { content: "\\f155"; } .fa-rupee:before, .fa-inr:before { content: "\\f156"; } .fa-cny:before, .fa-rmb:before, .fa-yen:before, .fa-jpy:before { content: "\\f157"; } .fa-ruble:before, .fa-rouble:before, .fa-rub:before { content: "\\f158"; } .fa-won:before, .fa-krw:before { content: "\\f159"; } .fa-bitcoin:before, .fa-btc:before { content: "\\f15a"; } .fa-file:before { content: "\\f15b"; } .fa-file-text:before { content: "\\f15c"; } .fa-sort-alpha-asc:before { content: "\\f15d"; } .fa-sort-alpha-desc:before { content: "\\f15e"; } .fa-sort-amount-asc:before { content: "\\f160"; } .fa-sort-amount-desc:before { content: "\\f161"; } .fa-sort-numeric-asc:before { content: "\\f162"; } .fa-sort-numeric-desc:before { content: "\\f163"; } .fa-thumbs-up:before { content: "\\f164"; } .fa-thumbs-down:before { content: "\\f165"; } .fa-youtube-square:before { content: "\\f166"; } .fa-youtube:before { content: "\\f167"; } .fa-xing:before { content: "\\f168"; } .fa-xing-square:before { content: "\\f169"; } .fa-youtube-play:before { content: "\\f16a"; } .fa-dropbox:before { content: "\\f16b"; } .fa-stack-overflow:before { content: "\\f16c"; } .fa-instagram:before { content: "\\f16d"; } .fa-flickr:before { content: "\\f16e"; } .fa-adn:before { content: "\\f170"; } .fa-bitbucket:before { content: "\\f171"; } .fa-bitbucket-square:before { content: "\\f172"; } .fa-tumblr:before { content: "\\f173"; } .fa-tumblr-square:before { content: "\\f174"; } .fa-long-arrow-down:before { content: "\\f175"; } .fa-long-arrow-up:before { content: "\\f176"; } .fa-long-arrow-left:before { content: "\\f177"; } .fa-long-arrow-right:before { content: "\\f178"; } .fa-apple:before { content: "\\f179"; } .fa-windows:before { content: "\\f17a"; } .fa-android:before { content: "\\f17b"; } .fa-linux:before { content: "\\f17c"; } .fa-dribbble:before { content: "\\f17d"; } .fa-skype:before { content: "\\f17e"; } .fa-foursquare:before { content: "\\f180"; } .fa-trello:before { content: "\\f181"; } .fa-female:before { content: "\\f182"; } .fa-male:before { content: "\\f183"; } .fa-gittip:before, .fa-gratipay:before { content: "\\f184"; } .fa-sun-o:before { content: "\\f185"; } .fa-moon-o:before { content: "\\f186"; } .fa-archive:before { content: "\\f187"; } .fa-bug:before { content: "\\f188"; } .fa-vk:before { content: "\\f189"; } .fa-weibo:before { content: "\\f18a"; } .fa-renren:before { content: "\\f18b"; } .fa-pagelines:before { content: "\\f18c"; } .fa-stack-exchange:before { content: "\\f18d"; } .fa-arrow-circle-o-right:before { content: "\\f18e"; } .fa-arrow-circle-o-left:before { content: "\\f190"; } .fa-toggle-left:before, .fa-caret-square-o-left:before { content: "\\f191"; } .fa-dot-circle-o:before { content: "\\f192"; } .fa-wheelchair:before { content: "\\f193"; } .fa-vimeo-square:before { content: "\\f194"; } .fa-turkish-lira:before, .fa-try:before { content: "\\f195"; } .fa-plus-square-o:before { content: "\\f196"; } .fa-space-shuttle:before { content: "\\f197"; } .fa-slack:before { content: "\\f198"; } .fa-envelope-square:before { content: "\\f199"; } .fa-wordpress:before { content: "\\f19a"; } .fa-openid:before { content: "\\f19b"; } .fa-institution:before, .fa-bank:before, .fa-university:before { content: "\\f19c"; } .fa-mortar-board:before, .fa-graduation-cap:before { content: "\\f19d"; } .fa-yahoo:before { content: "\\f19e"; } .fa-google:before { content: "\\f1a0"; } .fa-reddit:before { content: "\\f1a1"; } .fa-reddit-square:before { content: "\\f1a2"; } .fa-stumbleupon-circle:before { content: "\\f1a3"; } .fa-stumbleupon:before { content: "\\f1a4"; } .fa-delicious:before { content: "\\f1a5"; } .fa-digg:before { content: "\\f1a6"; } .fa-pied-piper-pp:before { content: "\\f1a7"; } .fa-pied-piper-alt:before { content: "\\f1a8"; } .fa-drupal:before { content: "\\f1a9"; } .fa-joomla:before { content: "\\f1aa"; } .fa-language:before { content: "\\f1ab"; } .fa-fax:before { content: "\\f1ac"; } .fa-building:before { content: "\\f1ad"; } .fa-child:before { content: "\\f1ae"; } .fa-paw:before { content: "\\f1b0"; } .fa-spoon:before { content: "\\f1b1"; } .fa-cube:before { content: "\\f1b2"; } .fa-cubes:before { content: "\\f1b3"; } .fa-behance:before { content: "\\f1b4"; } .fa-behance-square:before { content: "\\f1b5"; } .fa-steam:before { content: "\\f1b6"; } .fa-steam-square:before { content: "\\f1b7"; } .fa-recycle:before { content: "\\f1b8"; } .fa-automobile:before, .fa-car:before { content: "\\f1b9"; } .fa-cab:before, .fa-taxi:before { content: "\\f1ba"; } .fa-tree:before { content: "\\f1bb"; } .fa-spotify:before { content: "\\f1bc"; } .fa-deviantart:before { content: "\\f1bd"; } .fa-soundcloud:before { content: "\\f1be"; } .fa-database:before { content: "\\f1c0"; } .fa-file-pdf-o:before { content: "\\f1c1"; } .fa-file-word-o:before { content: "\\f1c2"; } .fa-file-excel-o:before { content: "\\f1c3"; } .fa-file-powerpoint-o:before { content: "\\f1c4"; } .fa-file-photo-o:before, .fa-file-picture-o:before, .fa-file-image-o:before { content: "\\f1c5"; } .fa-file-zip-o:before, .fa-file-archive-o:before { content: "\\f1c6"; } .fa-file-sound-o:before, .fa-file-audio-o:before { content: "\\f1c7"; } .fa-file-movie-o:before, .fa-file-video-o:before { content: "\\f1c8"; } .fa-file-code-o:before { content: "\\f1c9"; } .fa-vine:before { content: "\\f1ca"; } .fa-codepen:before { content: "\\f1cb"; } .fa-jsfiddle:before { content: "\\f1cc"; } .fa-life-bouy:before, .fa-life-buoy:before, .fa-life-saver:before, .fa-support:before, .fa-life-ring:before { content: "\\f1cd"; } .fa-circle-o-notch:before { content: "\\f1ce"; } .fa-ra:before, .fa-resistance:before, .fa-rebel:before { content: "\\f1d0"; } .fa-ge:before, .fa-empire:before { content: "\\f1d1"; } .fa-git-square:before { content: "\\f1d2"; } .fa-git:before { content: "\\f1d3"; } .fa-y-combinator-square:before, .fa-yc-square:before, .fa-hacker-news:before { content: "\\f1d4"; } .fa-tencent-weibo:before { content: "\\f1d5"; } .fa-qq:before { content: "\\f1d6"; } .fa-wechat:before, .fa-weixin:before { content: "\\f1d7"; } .fa-send:before, .fa-paper-plane:before { content: "\\f1d8"; } .fa-send-o:before, .fa-paper-plane-o:before { content: "\\f1d9"; } .fa-history:before { content: "\\f1da"; } .fa-circle-thin:before { content: "\\f1db"; } .fa-header:before { content: "\\f1dc"; } .fa-paragraph:before { content: "\\f1dd"; } .fa-sliders:before { content: "\\f1de"; } .fa-share-alt:before { content: "\\f1e0"; } .fa-share-alt-square:before { content: "\\f1e1"; } .fa-bomb:before { content: "\\f1e2"; } .fa-soccer-ball-o:before, .fa-futbol-o:before { content: "\\f1e3"; } .fa-tty:before { content: "\\f1e4"; } .fa-binoculars:before { content: "\\f1e5"; } .fa-plug:before { content: "\\f1e6"; } .fa-slideshare:before { content: "\\f1e7"; } .fa-twitch:before { content: "\\f1e8"; } .fa-yelp:before { content: "\\f1e9"; } .fa-newspaper-o:before { content: "\\f1ea"; } .fa-wifi:before { content: "\\f1eb"; } .fa-calculator:before { content: "\\f1ec"; } .fa-paypal:before { content: "\\f1ed"; } .fa-google-wallet:before { content: "\\f1ee"; } .fa-cc-visa:before { content: "\\f1f0"; } .fa-cc-mastercard:before { content: "\\f1f1"; } .fa-cc-discover:before { content: "\\f1f2"; } .fa-cc-amex:before { content: "\\f1f3"; } .fa-cc-paypal:before { content: "\\f1f4"; } .fa-cc-stripe:before { content: "\\f1f5"; } .fa-bell-slash:before { content: "\\f1f6"; } .fa-bell-slash-o:before { content: "\\f1f7"; } .fa-trash:before { content: "\\f1f8"; } .fa-copyright:before { content: "\\f1f9"; } .fa-at:before { content: "\\f1fa"; } .fa-eyedropper:before { content: "\\f1fb"; } .fa-paint-brush:before { content: "\\f1fc"; } .fa-birthday-cake:before { content: "\\f1fd"; } .fa-area-chart:before { content: "\\f1fe"; } .fa-pie-chart:before { content: "\\f200"; } .fa-line-chart:before { content: "\\f201"; } .fa-lastfm:before { content: "\\f202"; } .fa-lastfm-square:before { content: "\\f203"; } .fa-toggle-off:before { content: "\\f204"; } .fa-toggle-on:before { content: "\\f205"; } .fa-bicycle:before { content: "\\f206"; } .fa-bus:before { content: "\\f207"; } .fa-ioxhost:before { content: "\\f208"; } .fa-angellist:before { content: "\\f209"; } .fa-cc:before { content: "\\f20a"; } .fa-shekel:before, .fa-sheqel:before, .fa-ils:before { content: "\\f20b"; } .fa-meanpath:before { content: "\\f20c"; } .fa-buysellads:before { content: "\\f20d"; } .fa-connectdevelop:before { content: "\\f20e"; } .fa-dashcube:before { content: "\\f210"; } .fa-forumbee:before { content: "\\f211"; } .fa-leanpub:before { content: "\\f212"; } .fa-sellsy:before { content: "\\f213"; } .fa-shirtsinbulk:before { content: "\\f214"; } .fa-simplybuilt:before { content: "\\f215"; } .fa-skyatlas:before { content: "\\f216"; } .fa-cart-plus:before { content: "\\f217"; } .fa-cart-arrow-down:before { content: "\\f218"; } .fa-diamond:before { content: "\\f219"; } .fa-ship:before { content: "\\f21a"; } .fa-user-secret:before { content: "\\f21b"; } .fa-motorcycle:before { content: "\\f21c"; } .fa-street-view:before { content: "\\f21d"; } .fa-heartbeat:before { content: "\\f21e"; } .fa-venus:before { content: "\\f221"; } .fa-mars:before { content: "\\f222"; } .fa-mercury:before { content: "\\f223"; } .fa-intersex:before, .fa-transgender:before { content: "\\f224"; } .fa-transgender-alt:before { content: "\\f225"; } .fa-venus-double:before { content: "\\f226"; } .fa-mars-double:before { content: "\\f227"; } .fa-venus-mars:before { content: "\\f228"; } .fa-mars-stroke:before { content: "\\f229"; } .fa-mars-stroke-v:before { content: "\\f22a"; } .fa-mars-stroke-h:before { content: "\\f22b"; } .fa-neuter:before { content: "\\f22c"; } .fa-genderless:before { content: "\\f22d"; } .fa-facebook-official:before { content: "\\f230"; } .fa-pinterest-p:before { content: "\\f231"; } .fa-whatsapp:before { content: "\\f232"; } .fa-server:before { content: "\\f233"; } .fa-user-plus:before { content: "\\f234"; } .fa-user-times:before { content: "\\f235"; } .fa-hotel:before, .fa-bed:before { content: "\\f236"; } .fa-viacoin:before { content: "\\f237"; } .fa-train:before { content: "\\f238"; } .fa-subway:before { content: "\\f239"; } .fa-medium:before { content: "\\f23a"; } .fa-yc:before, .fa-y-combinator:before { content: "\\f23b"; } .fa-optin-monster:before { content: "\\f23c"; } .fa-opencart:before { content: "\\f23d"; } .fa-expeditedssl:before { content: "\\f23e"; } .fa-battery-4:before, .fa-battery:before, .fa-battery-full:before { content: "\\f240"; } .fa-battery-3:before, .fa-battery-three-quarters:before { content: "\\f241"; } .fa-battery-2:before, .fa-battery-half:before { content: "\\f242"; } .fa-battery-1:before, .fa-battery-quarter:before { content: "\\f243"; } .fa-battery-0:before, .fa-battery-empty:before { content: "\\f244"; } .fa-mouse-pointer:before { content: "\\f245"; } .fa-i-cursor:before { content: "\\f246"; } .fa-object-group:before { content: "\\f247"; } .fa-object-ungroup:before { content: "\\f248"; } .fa-sticky-note:before { content: "\\f249"; } .fa-sticky-note-o:before { content: "\\f24a"; } .fa-cc-jcb:before { content: "\\f24b"; } .fa-cc-diners-club:before { content: "\\f24c"; } .fa-clone:before { content: "\\f24d"; } .fa-balance-scale:before { content: "\\f24e"; } .fa-hourglass-o:before { content: "\\f250"; } .fa-hourglass-1:before, .fa-hourglass-start:before { content: "\\f251"; } .fa-hourglass-2:before, .fa-hourglass-half:before { content: "\\f252"; } .fa-hourglass-3:before, .fa-hourglass-end:before { content: "\\f253"; } .fa-hourglass:before { content: "\\f254"; } .fa-hand-grab-o:before, .fa-hand-rock-o:before { content: "\\f255"; } .fa-hand-stop-o:before, .fa-hand-paper-o:before { content: "\\f256"; } .fa-hand-scissors-o:before { content: "\\f257"; } .fa-hand-lizard-o:before { content: "\\f258"; } .fa-hand-spock-o:before { content: "\\f259"; } .fa-hand-pointer-o:before { content: "\\f25a"; } .fa-hand-peace-o:before { content: "\\f25b"; } .fa-trademark:before { content: "\\f25c"; } .fa-registered:before { content: "\\f25d"; } .fa-creative-commons:before { content: "\\f25e"; } .fa-gg:before { content: "\\f260"; } .fa-gg-circle:before { content: "\\f261"; } .fa-tripadvisor:before { content: "\\f262"; } .fa-odnoklassniki:before { content: "\\f263"; } .fa-odnoklassniki-square:before { content: "\\f264"; } .fa-get-pocket:before { content: "\\f265"; } .fa-wikipedia-w:before { content: "\\f266"; } .fa-safari:before { content: "\\f267"; } .fa-chrome:before { content: "\\f268"; } .fa-firefox:before { content: "\\f269"; } .fa-opera:before { content: "\\f26a"; } .fa-internet-explorer:before { content: "\\f26b"; } .fa-tv:before, .fa-television:before { content: "\\f26c"; } .fa-contao:before { content: "\\f26d"; } .fa-500px:before { content: "\\f26e"; } .fa-amazon:before { content: "\\f270"; } .fa-calendar-plus-o:before { content: "\\f271"; } .fa-calendar-minus-o:before { content: "\\f272"; } .fa-calendar-times-o:before { content: "\\f273"; } .fa-calendar-check-o:before { content: "\\f274"; } .fa-industry:before { content: "\\f275"; } .fa-map-pin:before { content: "\\f276"; } .fa-map-signs:before { content: "\\f277"; } .fa-map-o:before { content: "\\f278"; } .fa-map:before { content: "\\f279"; } .fa-commenting:before { content: "\\f27a"; } .fa-commenting-o:before { content: "\\f27b"; } .fa-houzz:before { content: "\\f27c"; } .fa-vimeo:before { content: "\\f27d"; } .fa-black-tie:before { content: "\\f27e"; } .fa-fonticons:before { content: "\\f280"; } .fa-reddit-alien:before { content: "\\f281"; } .fa-edge:before { content: "\\f282"; } .fa-credit-card-alt:before { content: "\\f283"; } .fa-codiepie:before { content: "\\f284"; } .fa-modx:before { content: "\\f285"; } .fa-fort-awesome:before { content: "\\f286"; } .fa-usb:before { content: "\\f287"; } .fa-product-hunt:before { content: "\\f288"; } .fa-mixcloud:before { content: "\\f289"; } .fa-scribd:before { content: "\\f28a"; } .fa-pause-circle:before { content: "\\f28b"; } .fa-pause-circle-o:before { content: "\\f28c"; } .fa-stop-circle:before { content: "\\f28d"; } .fa-stop-circle-o:before { content: "\\f28e"; } .fa-shopping-bag:before { content: "\\f290"; } .fa-shopping-basket:before { content: "\\f291"; } .fa-hashtag:before { content: "\\f292"; } .fa-bluetooth:before { content: "\\f293"; } .fa-bluetooth-b:before { content: "\\f294"; } .fa-percent:before { content: "\\f295"; } .fa-gitlab:before { content: "\\f296"; } .fa-wpbeginner:before { content: "\\f297"; } .fa-wpforms:before { content: "\\f298"; } .fa-envira:before { content: "\\f299"; } .fa-universal-access:before { content: "\\f29a"; } .fa-wheelchair-alt:before { content: "\\f29b"; } .fa-question-circle-o:before { content: "\\f29c"; } .fa-blind:before { content: "\\f29d"; } .fa-audio-description:before { content: "\\f29e"; } .fa-volume-control-phone:before { content: "\\f2a0"; } .fa-braille:before { content: "\\f2a1"; } .fa-assistive-listening-systems:before { content: "\\f2a2"; } .fa-asl-interpreting:before, .fa-american-sign-language-interpreting:before { content: "\\f2a3"; } .fa-deafness:before, .fa-hard-of-hearing:before, .fa-deaf:before { content: "\\f2a4"; } .fa-glide:before { content: "\\f2a5"; } .fa-glide-g:before { content: "\\f2a6"; } .fa-signing:before, .fa-sign-language:before { content: "\\f2a7"; } .fa-low-vision:before { content: "\\f2a8"; } .fa-viadeo:before { content: "\\f2a9"; } .fa-viadeo-square:before { content: "\\f2aa"; } .fa-snapchat:before { content: "\\f2ab"; } .fa-snapchat-ghost:before { content: "\\f2ac"; } .fa-snapchat-square:before { content: "\\f2ad"; } .fa-pied-piper:before { content: "\\f2ae"; } .fa-first-order:before { content: "\\f2b0"; } .fa-yoast:before { content: "\\f2b1"; } .fa-themeisle:before { content: "\\f2b2"; } .fa-google-plus-circle:before, .fa-google-plus-official:before { content: "\\f2b3"; } .fa-fa:before, .fa-font-awesome:before { content: "\\f2b4"; } .fa-handshake-o:before { content: "\\f2b5"; } .fa-envelope-open:before { content: "\\f2b6"; } .fa-envelope-open-o:before { content: "\\f2b7"; } .fa-linode:before { content: "\\f2b8"; } .fa-address-book:before { content: "\\f2b9"; } .fa-address-book-o:before { content: "\\f2ba"; } .fa-vcard:before, .fa-address-card:before { content: "\\f2bb"; } .fa-vcard-o:before, .fa-address-card-o:before { content: "\\f2bc"; } .fa-user-circle:before { content: "\\f2bd"; } .fa-user-circle-o:before { content: "\\f2be"; } .fa-user-o:before { content: "\\f2c0"; } .fa-id-badge:before { content: "\\f2c1"; } .fa-drivers-license:before, .fa-id-card:before { content: "\\f2c2"; } .fa-drivers-license-o:before, .fa-id-card-o:before { content: "\\f2c3"; } .fa-quora:before { content: "\\f2c4"; } .fa-free-code-camp:before { content: "\\f2c5"; } .fa-telegram:before { content: "\\f2c6"; } .fa-thermometer-4:before, .fa-thermometer:before, .fa-thermometer-full:before { content: "\\f2c7"; } .fa-thermometer-3:before, .fa-thermometer-three-quarters:before { content: "\\f2c8"; } .fa-thermometer-2:before, .fa-thermometer-half:before { content: "\\f2c9"; } .fa-thermometer-1:before, .fa-thermometer-quarter:before { content: "\\f2ca"; } .fa-thermometer-0:before, .fa-thermometer-empty:before { content: "\\f2cb"; } .fa-shower:before { content: "\\f2cc"; } .fa-bathtub:before, .fa-s15:before, .fa-bath:before { content: "\\f2cd"; } .fa-podcast:before { content: "\\f2ce"; } .fa-window-maximize:before { content: "\\f2d0"; } .fa-window-minimize:before { content: "\\f2d1"; } .fa-window-restore:before { content: "\\f2d2"; } .fa-times-rectangle:before, .fa-window-close:before { content: "\\f2d3"; } .fa-times-rectangle-o:before, .fa-window-close-o:before { content: "\\f2d4"; } .fa-bandcamp:before { content: "\\f2d5"; } .fa-grav:before { content: "\\f2d6"; } .fa-etsy:before { content: "\\f2d7"; } .fa-imdb:before { content: "\\f2d8"; } .fa-ravelry:before { content: "\\f2d9"; } .fa-eercast:before { content: "\\f2da"; } .fa-microchip:before { content: "\\f2db"; } .fa-snowflake-o:before { content: "\\f2dc"; } .fa-superpowers:before { content: "\\f2dd"; } .fa-wpexplorer:before { content: "\\f2de"; } .fa-meetup:before { content: "\\f2e0"; } .sr-only { position: absolute; width: 1px; height: 1px; padding: 0; margin: -1px; overflow: hidden; clip: rect(0, 0, 0, 0); border: 0; } .sr-only-focusable:active, .sr-only-focusable:focus { position: static; width: auto; height: auto; margin: 0; overflow: visible; clip: auto; } .sr-only-focusable:active, .sr-only-focusable:focus { position: static; width: auto; height: auto; margin: 0; overflow: visible; clip: auto; } /\*! \* \* IPython base \* \*/ .modal.fade .modal-dialog { -webkit-transform: translate(0, 0); -ms-transform: translate(0, 0); -o-transform: translate(0, 0); transform: translate(0, 0); } code { color: #000; } pre { font-size: inherit; line-height: inherit; } label { font-weight: normal; } /\* Make the page background atleast 100% the height of the view port \*/ /\* Make the page itself atleast 70% the height of the view port \*/ .border-box-sizing { box-sizing: border-box; -moz-box-sizing: border-box; -webkit-box-sizing: border-box; } .corner-all { border-radius: 2px; } .no-padding { padding: 0px; } /\* Flexible box model classes \*/ /\* Taken from Alex Russell http://infrequently.org/2009/08/css-3-progress/ \*/ /\* This file is a compatability layer. It allows the usage of flexible box model layouts accross multiple browsers, including older browsers. The newest, universal implementation of the flexible box model is used when available (see \`Modern browsers\` comments below). Browsers that are known to implement this new spec completely include: Firefox 28.0+ Chrome 29.0+ Internet Explorer 11+ Opera 17.0+ Browsers not listed, including Safari, are supported via the styling under the \`Old browsers\` comments below. \*/ .hbox { /\* Old browsers \*/ display: -webkit-box; -webkit-box-orient: horizontal; -webkit-box-align: stretch; display: -moz-box; -moz-box-orient: horizontal; -moz-box-align: stretch; display: box; box-orient: horizontal; box-align: stretch; /\* Modern browsers \*/ display: flex; flex-direction: row; align-items: stretch; } .hbox > \* { /\* Old browsers \*/ -webkit-box-flex: 0; -moz-box-flex: 0; box-flex: 0; /\* Modern browsers \*/ flex: none; } .vbox { /\* Old browsers \*/ display: -webkit-box; -webkit-box-orient: vertical; -webkit-box-align: stretch; display: -moz-box; -moz-box-orient: vertical; -moz-box-align: stretch; display: box; box-orient: vertical; box-align: stretch; /\* Modern browsers \*/ display: flex; flex-direction: column; align-items: stretch; } .vbox > \* { /\* Old browsers \*/ -webkit-box-flex: 0; -moz-box-flex: 0; box-flex: 0; /\* Modern browsers \*/ flex: none; } .hbox.reverse, .vbox.reverse, .reverse { /\* Old browsers \*/ -webkit-box-direction: reverse; -moz-box-direction: reverse; box-direction: reverse; /\* Modern browsers \*/ flex-direction: row-reverse; } .hbox.box-flex0, .vbox.box-flex0, .box-flex0 { /\* Old browsers \*/ -webkit-box-flex: 0; -moz-box-flex: 0; box-flex: 0; /\* Modern browsers \*/ flex: none; width: auto; } .hbox.box-flex1, .vbox.box-flex1, .box-flex1 { /\* Old browsers \*/ -webkit-box-flex: 1; -moz-box-flex: 1; box-flex: 1; /\* Modern browsers \*/ flex: 1; } .hbox.box-flex, .vbox.box-flex, .box-flex { /\* Old browsers \*/ /\* Old browsers \*/ -webkit-box-flex: 1; -moz-box-flex: 1; box-flex: 1; /\* Modern browsers \*/ flex: 1; } .hbox.box-flex2, .vbox.box-flex2, .box-flex2 { /\* Old browsers \*/ -webkit-box-flex: 2; -moz-box-flex: 2; box-flex: 2; /\* Modern browsers \*/ flex: 2; } .box-group1 { /\* Deprecated \*/ -webkit-box-flex-group: 1; -moz-box-flex-group: 1; box-flex-group: 1; } .box-group2 { /\* Deprecated \*/ -webkit-box-flex-group: 2; -moz-box-flex-group: 2; box-flex-group: 2; } .hbox.start, .vbox.start, .start { /\* Old browsers \*/ -webkit-box-pack: start; -moz-box-pack: start; box-pack: start; /\* Modern browsers \*/ justify-content: flex-start; } .hbox.end, .vbox.end, .end { /\* Old browsers \*/ -webkit-box-pack: end; -moz-box-pack: end; box-pack: end; /\* Modern browsers \*/ justify-content: flex-end; } .hbox.center, .vbox.center, .center { /\* Old browsers \*/ -webkit-box-pack: center; -moz-box-pack: center; box-pack: center; /\* Modern browsers \*/ justify-content: center; } .hbox.baseline, .vbox.baseline, .baseline { /\* Old browsers \*/ -webkit-box-pack: baseline; -moz-box-pack: baseline; box-pack: baseline; /\* Modern browsers \*/ justify-content: baseline; } .hbox.stretch, .vbox.stretch, .stretch { /\* Old browsers \*/ -webkit-box-pack: stretch; -moz-box-pack: stretch; box-pack: stretch; /\* Modern browsers \*/ justify-content: stretch; } .hbox.align-start, .vbox.align-start, .align-start { /\* Old browsers \*/ -webkit-box-align: start; -moz-box-align: start; box-align: start; /\* Modern browsers \*/ align-items: flex-start; } .hbox.align-end, .vbox.align-end, .align-end { /\* Old browsers \*/ -webkit-box-align: end; -moz-box-align: end; box-align: end; /\* Modern browsers \*/ align-items: flex-end; } .hbox.align-center, .vbox.align-center, .align-center { /\* Old browsers \*/ -webkit-box-align: center; -moz-box-align: center; box-align: center; /\* Modern browsers \*/ align-items: center; } .hbox.align-baseline, .vbox.align-baseline, .align-baseline { /\* Old browsers \*/ -webkit-box-align: baseline; -moz-box-align: baseline; box-align: baseline; /\* Modern browsers \*/ align-items: baseline; } .hbox.align-stretch, .vbox.align-stretch, .align-stretch { /\* Old browsers \*/ -webkit-box-align: stretch; -moz-box-align: stretch; box-align: stretch; /\* Modern browsers \*/ align-items: stretch; } div.error { margin: 2em; text-align: center; } div.error > h1 { font-size: 500%; line-height: normal; } div.error > p { font-size: 200%; line-height: normal; } div.traceback-wrapper { text-align: left; max-width: 800px; margin: auto; } div.traceback-wrapper pre.traceback { max-height: 600px; overflow: auto; } /\*\* \* Primary styles \* \* Author: Jupyter Development Team \*/ body { background-color: #fff; /\* This makes sure that the body covers the entire window and needs to be in a different element than the display: box in wrapper below \*/ position: absolute; left: 0px; right: 0px; top: 0px; bottom: 0px; overflow: visible; } body > #header { /\* Initially hidden to prevent FLOUC \*/ display: none; background-color: #fff; /\* Display over codemirror \*/ position: relative; z-index: 100; } body > #header #header-container { display: flex; flex-direction: row; justify-content: space-between; padding: 5px; padding-bottom: 5px; padding-top: 5px; box-sizing: border-box; -moz-box-sizing: border-box; -webkit-box-sizing: border-box; } body > #header .header-bar { width: 100%; height: 1px; background: #e7e7e7; margin-bottom: -1px; } @media print { body > #header { display: none !important; } } #header-spacer { width: 100%; visibility: hidden; } @media print { #header-spacer { display: none; } } #ipython\_notebook { padding-left: 0px; padding-top: 1px; padding-bottom: 1px; } \[dir="rtl"\] #ipython\_notebook { margin-right: 10px; margin-left: 0; } \[dir="rtl"\] #ipython\_notebook.pull-left { float: right !important; float: right; } .flex-spacer { flex: 1; } #noscript { width: auto; padding-top: 16px; padding-bottom: 16px; text-align: center; font-size: 22px; color: red; font-weight: bold; } #ipython\_notebook img { height: 28px; } #site { width: 100%; display: none; box-sizing: border-box; -moz-box-sizing: border-box; -webkit-box-sizing: border-box; overflow: auto; } @media print { #site { height: auto !important; } } /\* Smaller buttons \*/ .ui-button .ui-button-text { padding: 0.2em 0.8em; font-size: 77%; } input.ui-button { padding: 0.3em 0.9em; } span#kernel\_logo\_widget { margin: 0 10px; } span#login\_widget { float: right; } \[dir="rtl"\] span#login\_widget { float: left; } span#login\_widget > .button, #logout { color: #333; background-color: #fff; border-color: #ccc; } span#login\_widget > .button:focus, #logout:focus, span#login\_widget > .button.focus, #logout.focus { color: #333; background-color: #e6e6e6; border-color: #8c8c8c; } span#login\_widget > .button:hover, #logout:hover { color: #333; background-color: #e6e6e6; border-color: #adadad; } span#login\_widget > .button:active, #logout:active, span#login\_widget > .button.active, #logout.active, .open > .dropdown-togglespan#login\_widget > .button, .open > .dropdown-toggle#logout { color: #333; background-color: #e6e6e6; border-color: #adadad; } span#login\_widget > .button:active:hover, #logout:active:hover, span#login\_widget > .button.active:hover, #logout.active:hover, .open > .dropdown-togglespan#login\_widget > .button:hover, .open > .dropdown-toggle#logout:hover, span#login\_widget > .button:active:focus, #logout:active:focus, span#login\_widget > .button.active:focus, #logout.active:focus, .open > .dropdown-togglespan#login\_widget > .button:focus, .open > .dropdown-toggle#logout:focus, span#login\_widget > .button:active.focus, #logout:active.focus, span#login\_widget > .button.active.focus, #logout.active.focus, .open > .dropdown-togglespan#login\_widget > .button.focus, .open > .dropdown-toggle#logout.focus { color: #333; background-color: #d4d4d4; border-color: #8c8c8c; } span#login\_widget > .button:active, #logout:active, span#login\_widget > .button.active, #logout.active, .open > .dropdown-togglespan#login\_widget > .button, .open > .dropdown-toggle#logout { background-image: none; } span#login\_widget > .button.disabled:hover, #logout.disabled:hover, span#login\_widget > .button\[disabled\]:hover, #logout\[disabled\]:hover, fieldset\[disabled\] span#login\_widget > .button:hover, fieldset\[disabled\] #logout:hover, span#login\_widget > .button.disabled:focus, #logout.disabled:focus, span#login\_widget > .button\[disabled\]:focus, #logout\[disabled\]:focus, fieldset\[disabled\] span#login\_widget > .button:focus, fieldset\[disabled\] #logout:focus, span#login\_widget > .button.disabled.focus, #logout.disabled.focus, span#login\_widget > .button\[disabled\].focus, #logout\[disabled\].focus, fieldset\[disabled\] span#login\_widget > .button.focus, fieldset\[disabled\] #logout.focus { background-color: #fff; border-color: #ccc; } span#login\_widget > .button .badge, #logout .badge { color: #fff; background-color: #333; } .nav-header { text-transform: none; } #header > span { margin-top: 10px; } .modal\_stretch .modal-dialog { /\* Old browsers \*/ display: -webkit-box; -webkit-box-orient: vertical; -webkit-box-align: stretch; display: -moz-box; -moz-box-orient: vertical; -moz-box-align: stretch; display: box; box-orient: vertical; box-align: stretch; /\* Modern browsers \*/ display: flex; flex-direction: column; align-items: stretch; min-height: 80vh; } .modal\_stretch .modal-dialog .modal-body { max-height: calc(100vh - 200px); overflow: auto; flex: 1; } .modal-header { cursor: move; } @media (min-width: 768px) { .modal .modal-dialog { width: 700px; } } @media (min-width: 768px) { select.form-control { margin-left: 12px; margin-right: 12px; } } /\*! \* \* IPython auth \* \*/ .center-nav { display: inline-block; margin-bottom: -4px; } \[dir="rtl"\] .center-nav form.pull-left { float: right !important; float: right; } \[dir="rtl"\] .center-nav .navbar-text { float: right; } \[dir="rtl"\] .navbar-inner { text-align: right; } \[dir="rtl"\] div.text-left { text-align: right; } /\*! \* \* IPython tree view \* \*/ /\* We need an invisible input field on top of the sentense\*/ /\* "Drag file onto the list ..." \*/ .alternate\_upload { background-color: none; display: inline; } .alternate\_upload.form { padding: 0; margin: 0; } .alternate\_upload input.fileinput { position: absolute; display: block; width: 100%; height: 100%; overflow: hidden; cursor: pointer; opacity: 0; z-index: 2; } .alternate\_upload .btn-xs > input.fileinput { margin: -1px -5px; } .alternate\_upload .btn-upload { position: relative; height: 22px; } ::-webkit-file-upload-button { cursor: pointer; } /\*\* \* Primary styles \* \* Author: Jupyter Development Team \*/ ul#tabs { margin-bottom: 4px; } ul#tabs a { padding-top: 6px; padding-bottom: 4px; } \[dir="rtl"\] ul#tabs.nav-tabs > li { float: right; } \[dir="rtl"\] ul#tabs.nav.nav-tabs { padding-right: 0; } ul.breadcrumb a:focus, ul.breadcrumb a:hover { text-decoration: none; } ul.breadcrumb i.icon-home { font-size: 16px; margin-right: 4px; } ul.breadcrumb span { color: #5e5e5e; } .list\_toolbar { padding: 4px 0 4px 0; vertical-align: middle; } .list\_toolbar .tree-buttons { padding-top: 1px; } \[dir="rtl"\] .list\_toolbar .tree-buttons .pull-right { float: left !important; float: left; } \[dir="rtl"\] .list\_toolbar .col-sm-4, \[dir="rtl"\] .list\_toolbar .col-sm-8 { float: right; } .dynamic-buttons { padding-top: 3px; display: inline-block; } .list\_toolbar \[class\*="span"\] { min-height: 24px; } .list\_header { font-weight: bold; background-color: #EEE; } .list\_placeholder { font-weight: bold; padding-top: 4px; padding-bottom: 4px; padding-left: 7px; padding-right: 7px; } .list\_container { margin-top: 4px; margin-bottom: 20px; border: 1px solid #ddd; border-radius: 2px; } .list\_container > div { border-bottom: 1px solid #ddd; } .list\_container > div:hover .list-item { background-color: red; } .list\_container > div:last-child { border: none; } .list\_item:hover .list\_item { background-color: #ddd; } .list\_item a { text-decoration: none; } .list\_item:hover { background-color: #fafafa; } .list\_header > div, .list\_item > div { padding-top: 4px; padding-bottom: 4px; padding-left: 7px; padding-right: 7px; line-height: 22px; } .list\_header > div input, .list\_item > div input { margin-right: 7px; margin-left: 14px; vertical-align: text-bottom; line-height: 22px; position: relative; top: -1px; } .list\_header > div .item\_link, .list\_item > div .item\_link { margin-left: -1px; vertical-align: baseline; line-height: 22px; } \[dir="rtl"\] .list\_item > div input { margin-right: 0; } .new-file input\[type=checkbox\] { visibility: hidden; } .item\_name { line-height: 22px; height: 24px; } .item\_icon { font-size: 14px; color: #5e5e5e; margin-right: 7px; margin-left: 7px; line-height: 22px; vertical-align: baseline; } .item\_modified { margin-right: 7px; margin-left: 7px; } \[dir="rtl"\] .item\_modified.pull-right { float: left !important; float: left; } .item\_buttons { line-height: 1em; margin-left: -5px; } .item\_buttons .btn, .item\_buttons .btn-group, .item\_buttons .input-group { float: left; } .item\_buttons > .btn, .item\_buttons > .btn-group, .item\_buttons > .input-group { margin-left: 5px; } .item\_buttons .btn { min-width: 13ex; } .item\_buttons .running-indicator { padding-top: 4px; color: #5cb85c; } .item\_buttons .kernel-name { padding-top: 4px; color: #5bc0de; margin-right: 7px; float: left; } \[dir="rtl"\] .item\_buttons.pull-right { float: left !important; float: left; } \[dir="rtl"\] .item\_buttons .kernel-name { margin-left: 7px; float: right; } .toolbar\_info { height: 24px; line-height: 24px; } .list\_item input:not(\[type=checkbox\]) { padding-top: 3px; padding-bottom: 3px; height: 22px; line-height: 14px; margin: 0px; } .highlight\_text { color: blue; } #project\_name { display: inline-block; padding-left: 7px; margin-left: -2px; } #project\_name > .breadcrumb { padding: 0px; margin-bottom: 0px; background-color: transparent; font-weight: bold; } .sort\_button { display: inline-block; padding-left: 7px; } \[dir="rtl"\] .sort\_button.pull-right { float: left !important; float: left; } #tree-selector { padding-right: 0px; } #button-select-all { min-width: 50px; } \[dir="rtl"\] #button-select-all.btn { float: right ; } #select-all { margin-left: 7px; margin-right: 2px; margin-top: 2px; height: 16px; } \[dir="rtl"\] #select-all.pull-left { float: right !important; float: right; } .menu\_icon { margin-right: 2px; } .tab-content .row { margin-left: 0px; margin-right: 0px; } .folder\_icon:before { display: inline-block; font: normal normal normal 14px/1 FontAwesome; font-size: inherit; text-rendering: auto; -webkit-font-smoothing: antialiased; -moz-osx-font-smoothing: grayscale; content: "\\f114"; } .folder\_icon:before.fa-pull-left { margin-right: .3em; } .folder\_icon:before.fa-pull-right { margin-left: .3em; } .folder\_icon:before.pull-left { margin-right: .3em; } .folder\_icon:before.pull-right { margin-left: .3em; } .notebook\_icon:before { display: inline-block; font: normal normal normal 14px/1 FontAwesome; font-size: inherit; text-rendering: auto; -webkit-font-smoothing: antialiased; -moz-osx-font-smoothing: grayscale; content: "\\f02d"; position: relative; top: -1px; } .notebook\_icon:before.fa-pull-left { margin-right: .3em; } .notebook\_icon:before.fa-pull-right { margin-left: .3em; } .notebook\_icon:before.pull-left { margin-right: .3em; } .notebook\_icon:before.pull-right { margin-left: .3em; } .running\_notebook\_icon:before { display: inline-block; font: normal normal normal 14px/1 FontAwesome; font-size: inherit; text-rendering: auto; -webkit-font-smoothing: antialiased; -moz-osx-font-smoothing: grayscale; content: "\\f02d"; position: relative; top: -1px; color: #5cb85c; } .running\_notebook\_icon:before.fa-pull-left { margin-right: .3em; } .running\_notebook\_icon:before.fa-pull-right { margin-left: .3em; } .running\_notebook\_icon:before.pull-left { margin-right: .3em; } .running\_notebook\_icon:before.pull-right { margin-left: .3em; } .file\_icon:before { display: inline-block; font: normal normal normal 14px/1 FontAwesome; font-size: inherit; text-rendering: auto; -webkit-font-smoothing: antialiased; -moz-osx-font-smoothing: grayscale; content: "\\f016"; position: relative; top: -2px; } .file\_icon:before.fa-pull-left { margin-right: .3em; } .file\_icon:before.fa-pull-right { margin-left: .3em; } .file\_icon:before.pull-left { margin-right: .3em; } .file\_icon:before.pull-right { margin-left: .3em; } #notebook\_toolbar .pull-right { padding-top: 0px; margin-right: -1px; } ul#new-menu { left: auto; right: 0; } #new-menu .dropdown-header { font-size: 10px; border-bottom: 1px solid #e5e5e5; padding: 0 0 3px; margin: -3px 20px 0; } .kernel-menu-icon { padding-right: 12px; width: 24px; content: "\\f096"; } .kernel-menu-icon:before { content: "\\f096"; } .kernel-menu-icon-current:before { content: "\\f00c"; } #tab\_content { padding-top: 20px; } #running .panel-group .panel { margin-top: 3px; margin-bottom: 1em; } #running .panel-group .panel .panel-heading { background-color: #EEE; padding-top: 4px; padding-bottom: 4px; padding-left: 7px; padding-right: 7px; line-height: 22px; } #running .panel-group .panel .panel-heading a:focus, #running .panel-group .panel .panel-heading a:hover { text-decoration: none; } #running .panel-group .panel .panel-body { padding: 0px; } #running .panel-group .panel .panel-body .list\_container { margin-top: 0px; margin-bottom: 0px; border: 0px; border-radius: 0px; } #running .panel-group .panel .panel-body .list\_container .list\_item { border-bottom: 1px solid #ddd; } #running .panel-group .panel .panel-body .list\_container .list\_item:last-child { border-bottom: 0px; } .delete-button { display: none; } .duplicate-button { display: none; } .rename-button { display: none; } .move-button { display: none; } .download-button { display: none; } .shutdown-button { display: none; } .dynamic-instructions { display: inline-block; padding-top: 4px; } /\*! \* \* IPython text editor webapp \* \*/ .selected-keymap i.fa { padding: 0px 5px; } .selected-keymap i.fa:before { content: "\\f00c"; } #mode-menu { overflow: auto; max-height: 20em; } .edit\_app #header { -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2); box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2); } .edit\_app #menubar .navbar { /\* Use a negative 1 bottom margin, so the border overlaps the border of the header \*/ margin-bottom: -1px; } .dirty-indicator { display: inline-block; font: normal normal normal 14px/1 FontAwesome; font-size: inherit; text-rendering: auto; -webkit-font-smoothing: antialiased; -moz-osx-font-smoothing: grayscale; width: 20px; } .dirty-indicator.fa-pull-left { margin-right: .3em; } .dirty-indicator.fa-pull-right { margin-left: .3em; } .dirty-indicator.pull-left { margin-right: .3em; } .dirty-indicator.pull-right { margin-left: .3em; } .dirty-indicator-dirty { display: inline-block; font: normal normal normal 14px/1 FontAwesome; font-size: inherit; text-rendering: auto; -webkit-font-smoothing: antialiased; -moz-osx-font-smoothing: grayscale; width: 20px; } .dirty-indicator-dirty.fa-pull-left { margin-right: .3em; } .dirty-indicator-dirty.fa-pull-right { margin-left: .3em; } .dirty-indicator-dirty.pull-left { margin-right: .3em; } .dirty-indicator-dirty.pull-right { margin-left: .3em; } .dirty-indicator-clean { display: inline-block; font: normal normal normal 14px/1 FontAwesome; font-size: inherit; text-rendering: auto; -webkit-font-smoothing: antialiased; -moz-osx-font-smoothing: grayscale; width: 20px; } .dirty-indicator-clean.fa-pull-left { margin-right: .3em; } .dirty-indicator-clean.fa-pull-right { margin-left: .3em; } .dirty-indicator-clean.pull-left { margin-right: .3em; } .dirty-indicator-clean.pull-right { margin-left: .3em; } .dirty-indicator-clean:before { display: inline-block; font: normal normal normal 14px/1 FontAwesome; font-size: inherit; text-rendering: auto; -webkit-font-smoothing: antialiased; -moz-osx-font-smoothing: grayscale; content: "\\f00c"; } .dirty-indicator-clean:before.fa-pull-left { margin-right: .3em; } .dirty-indicator-clean:before.fa-pull-right { margin-left: .3em; } .dirty-indicator-clean:before.pull-left { margin-right: .3em; } .dirty-indicator-clean:before.pull-right { margin-left: .3em; } #filename { font-size: 16pt; display: table; padding: 0px 5px; } #current-mode { padding-left: 5px; padding-right: 5px; } #texteditor-backdrop { padding-top: 20px; padding-bottom: 20px; } @media not print { #texteditor-backdrop { background-color: #EEE; } } @media print { #texteditor-backdrop #texteditor-container .CodeMirror-gutter, #texteditor-backdrop #texteditor-container .CodeMirror-gutters { background-color: #fff; } } @media not print { #texteditor-backdrop #texteditor-container .CodeMirror-gutter, #texteditor-backdrop #texteditor-container .CodeMirror-gutters { background-color: #fff; } } @media not print { #texteditor-backdrop #texteditor-container { padding: 0px; background-color: #fff; -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2); box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2); } } .CodeMirror-dialog { background-color: #fff; } /\*! \* \* IPython notebook \* \*/ /\* CSS font colors for translated ANSI escape sequences \*/ /\* The color values are a mix of http://www.xcolors.net/dl/baskerville-ivorylight and http://www.xcolors.net/dl/euphrasia \*/ .ansi-black-fg { color: #3E424D; } .ansi-black-bg { background-color: #3E424D; } .ansi-black-intense-fg { color: #282C36; } .ansi-black-intense-bg { background-color: #282C36; } .ansi-red-fg { color: #E75C58; } .ansi-red-bg { background-color: #E75C58; } .ansi-red-intense-fg { color: #B22B31; } .ansi-red-intense-bg { background-color: #B22B31; } .ansi-green-fg { color: #00A250; } .ansi-green-bg { background-color: #00A250; } .ansi-green-intense-fg { color: #007427; } .ansi-green-intense-bg { background-color: #007427; } .ansi-yellow-fg { color: #DDB62B; } .ansi-yellow-bg { background-color: #DDB62B; } .ansi-yellow-intense-fg { color: #B27D12; } .ansi-yellow-intense-bg { background-color: #B27D12; } .ansi-blue-fg { color: #208FFB; } .ansi-blue-bg { background-color: #208FFB; } .ansi-blue-intense-fg { color: #0065CA; } .ansi-blue-intense-bg { background-color: #0065CA; } .ansi-magenta-fg { color: #D160C4; } .ansi-magenta-bg { background-color: #D160C4; } .ansi-magenta-intense-fg { color: #A03196; } .ansi-magenta-intense-bg { background-color: #A03196; } .ansi-cyan-fg { color: #60C6C8; } .ansi-cyan-bg { background-color: #60C6C8; } .ansi-cyan-intense-fg { color: #258F8F; } .ansi-cyan-intense-bg { background-color: #258F8F; } .ansi-white-fg { color: #C5C1B4; } .ansi-white-bg { background-color: #C5C1B4; } .ansi-white-intense-fg { color: #A1A6B2; } .ansi-white-intense-bg { background-color: #A1A6B2; } .ansi-default-inverse-fg { color: #FFFFFF; } .ansi-default-inverse-bg { background-color: #000000; } .ansi-bold { font-weight: bold; } .ansi-underline { text-decoration: underline; } /\* The following styles are deprecated an will be removed in a future version \*/ .ansibold { font-weight: bold; } .ansi-inverse { outline: 0.5px dotted; } /\* use dark versions for foreground, to improve visibility \*/ .ansiblack { color: black; } .ansired { color: darkred; } .ansigreen { color: darkgreen; } .ansiyellow { color: #c4a000; } .ansiblue { color: darkblue; } .ansipurple { color: darkviolet; } .ansicyan { color: steelblue; } .ansigray { color: gray; } /\* and light for background, for the same reason \*/ .ansibgblack { background-color: black; } .ansibgred { background-color: red; } .ansibggreen { background-color: green; } .ansibgyellow { background-color: yellow; } .ansibgblue { background-color: blue; } .ansibgpurple { background-color: magenta; } .ansibgcyan { background-color: cyan; } .ansibggray { background-color: gray; } div.cell { /\* Old browsers \*/ display: -webkit-box; -webkit-box-orient: vertical; -webkit-box-align: stretch; display: -moz-box; -moz-box-orient: vertical; -moz-box-align: stretch; display: box; box-orient: vertical; box-align: stretch; /\* Modern browsers \*/ display: flex; flex-direction: column; align-items: stretch; border-radius: 2px; box-sizing: border-box; -moz-box-sizing: border-box; -webkit-box-sizing: border-box; border-width: 1px; border-style: solid; border-color: transparent; width: 100%; padding: 5px; /\* This acts as a spacer between cells, that is outside the border \*/ margin: 0px; outline: none; position: relative; overflow: visible; } div.cell:before { position: absolute; display: block; top: -1px; left: -1px; width: 5px; height: calc(100% + 2px); content: ''; background: transparent; } div.cell.jupyter-soft-selected { border-left-color: #E3F2FD; border-left-width: 1px; padding-left: 5px; border-right-color: #E3F2FD; border-right-width: 1px; background: #E3F2FD; } @media print { div.cell.jupyter-soft-selected { border-color: transparent; } } div.cell.selected, div.cell.selected.jupyter-soft-selected { border-color: #ababab; } div.cell.selected:before, div.cell.selected.jupyter-soft-selected:before { position: absolute; display: block; top: -1px; left: -1px; width: 5px; height: calc(100% + 2px); content: ''; background: #42A5F5; } @media print { div.cell.selected, div.cell.selected.jupyter-soft-selected { border-color: transparent; } } .edit\_mode div.cell.selected { border-color: #66BB6A; } .edit\_mode div.cell.selected:before { position: absolute; display: block; top: -1px; left: -1px; width: 5px; height: calc(100% + 2px); content: ''; background: #66BB6A; } @media print { .edit\_mode div.cell.selected { border-color: transparent; } } .prompt { /\* This needs to be wide enough for 3 digit prompt numbers: In\[100\]: \*/ min-width: 14ex; /\* This padding is tuned to match the padding on the CodeMirror editor. \*/ padding: 0.4em; margin: 0px; font-family: monospace; text-align: right; /\* This has to match that of the the CodeMirror class line-height below \*/ line-height: 1.21429em; /\* Don't highlight prompt number selection \*/ -webkit-touch-callout: none; -webkit-user-select: none; -khtml-user-select: none; -moz-user-select: none; -ms-user-select: none; user-select: none; /\* Use default cursor \*/ cursor: default; } @media (max-width: 540px) { .prompt { text-align: left; } } div.inner\_cell { min-width: 0; /\* Old browsers \*/ display: -webkit-box; -webkit-box-orient: vertical; -webkit-box-align: stretch; display: -moz-box; -moz-box-orient: vertical; -moz-box-align: stretch; display: box; box-orient: vertical; box-align: stretch; /\* Modern browsers \*/ display: flex; flex-direction: column; align-items: stretch; /\* Old browsers \*/ -webkit-box-flex: 1; -moz-box-flex: 1; box-flex: 1; /\* Modern browsers \*/ flex: 1; } /\* input\_area and input\_prompt must match in top border and margin for alignment \*/ div.input\_area { border: 1px solid #cfcfcf; border-radius: 2px; background: #f7f7f7; line-height: 1.21429em; } /\* This is needed so that empty prompt areas can collapse to zero height when there is no content in the output\_subarea and the prompt. The main purpose of this is to make sure that empty JavaScript output\_subareas have no height. \*/ div.prompt:empty { padding-top: 0; padding-bottom: 0; } div.unrecognized\_cell { padding: 5px 5px 5px 0px; /\* Old browsers \*/ display: -webkit-box; -webkit-box-orient: horizontal; -webkit-box-align: stretch; display: -moz-box; -moz-box-orient: horizontal; -moz-box-align: stretch; display: box; box-orient: horizontal; box-align: stretch; /\* Modern browsers \*/ display: flex; flex-direction: row; align-items: stretch; } div.unrecognized\_cell .inner\_cell { border-radius: 2px; padding: 5px; font-weight: bold; color: red; border: 1px solid #cfcfcf; background: #eaeaea; } div.unrecognized\_cell .inner\_cell a { color: inherit; text-decoration: none; } div.unrecognized\_cell .inner\_cell a:hover { color: inherit; text-decoration: none; } @media (max-width: 540px) { div.unrecognized\_cell > div.prompt { display: none; } } div.code\_cell { /\* avoid page breaking on code cells when printing \*/ } @media print { div.code\_cell { page-break-inside: avoid; } } /\* any special styling for code cells that are currently running goes here \*/ div.input { page-break-inside: avoid; /\* Old browsers \*/ display: -webkit-box; -webkit-box-orient: horizontal; -webkit-box-align: stretch; display: -moz-box; -moz-box-orient: horizontal; -moz-box-align: stretch; display: box; box-orient: horizontal; box-align: stretch; /\* Modern browsers \*/ display: flex; flex-direction: row; align-items: stretch; } @media (max-width: 540px) { div.input { /\* Old browsers \*/ display: -webkit-box; -webkit-box-orient: vertical; -webkit-box-align: stretch; display: -moz-box; -moz-box-orient: vertical; -moz-box-align: stretch; display: box; box-orient: vertical; box-align: stretch; /\* Modern browsers \*/ display: flex; flex-direction: column; align-items: stretch; } } /\* input\_area and input\_prompt must match in top border and margin for alignment \*/ div.input\_prompt { color: #303F9F; border-top: 1px solid transparent; } div.input\_area > div.highlight { margin: 0.4em; border: none; padding: 0px; background-color: transparent; } div.input\_area > div.highlight > pre { margin: 0px; border: none; padding: 0px; background-color: transparent; } /\* The following gets added to the <head> if it is detected that the user has a \* monospace font with inconsistent normal/bold/italic height. See \* notebookmain.js. Such fonts will have keywords vertically offset with \* respect to the rest of the text. The user should select a better font. \* See: https://github.com/ipython/ipython/issues/1503 \* \* .CodeMirror span { \* vertical-align: bottom; \* } \*/ .CodeMirror { line-height: 1.21429em; /\* Changed from 1em to our global default \*/ font-size: 14px; height: auto; /\* Changed to auto to autogrow \*/ background: none; /\* Changed from white to allow our bg to show through \*/ } .CodeMirror-scroll { /\* The CodeMirror docs are a bit fuzzy on if overflow-y should be hidden or visible.\*/ /\* We have found that if it is visible, vertical scrollbars appear with font size changes.\*/ overflow-y: hidden; overflow-x: auto; } .CodeMirror-lines { /\* In CM2, this used to be 0.4em, but in CM3 it went to 4px. We need the em value because \*/ /\* we have set a different line-height and want this to scale with that. \*/ /\* Note that this should set vertical padding only, since CodeMirror assumes that horizontal padding will be set on CodeMirror pre \*/ padding: 0.4em 0; } .CodeMirror-linenumber { padding: 0 8px 0 4px; } .CodeMirror-gutters { border-bottom-left-radius: 2px; border-top-left-radius: 2px; } .CodeMirror pre { /\* In CM3 this went to 4px from 0 in CM2. This sets horizontal padding only, use .CodeMirror-lines for vertical \*/ padding: 0 0.4em; border: 0; border-radius: 0; } .CodeMirror-cursor { border-left: 1.4px solid black; } @media screen and (min-width: 2138px) and (max-width: 4319px) { .CodeMirror-cursor { border-left: 2px solid black; } } @media screen and (min-width: 4320px) { .CodeMirror-cursor { border-left: 4px solid black; } } /\* Original style from softwaremaniacs.org (c) Ivan Sagalaev <Maniac@SoftwareManiacs.Org> Adapted from GitHub theme \*/ .highlight-base { color: #000; } .highlight-variable { color: #000; } .highlight-variable-2 { color: #1a1a1a; } .highlight-variable-3 { color: #333333; } .highlight-string { color: #BA2121; } .highlight-comment { color: #408080; font-style: italic; } .highlight-number { color: #080; } .highlight-atom { color: #88F; } .highlight-keyword { color: #008000; font-weight: bold; } .highlight-builtin { color: #008000; } .highlight-error { color: #f00; } .highlight-operator { color: #AA22FF; font-weight: bold; } .highlight-meta { color: #AA22FF; } /\* previously not defined, copying from default codemirror \*/ .highlight-def { color: #00f; } .highlight-string-2 { color: #f50; } .highlight-qualifier { color: #555; } .highlight-bracket { color: #997; } .highlight-tag { color: #170; } .highlight-attribute { color: #00c; } .highlight-header { color: blue; } .highlight-quote { color: #090; } .highlight-link { color: #00c; } /\* apply the same style to codemirror \*/ .cm-s-ipython span.cm-keyword { color: #008000; font-weight: bold; } .cm-s-ipython span.cm-atom { color: #88F; } .cm-s-ipython span.cm-number { color: #080; } .cm-s-ipython span.cm-def { color: #00f; } .cm-s-ipython span.cm-variable { color: #000; } .cm-s-ipython span.cm-operator { color: #AA22FF; font-weight: bold; } .cm-s-ipython span.cm-variable-2 { color: #1a1a1a; } .cm-s-ipython span.cm-variable-3 { color: #333333; } .cm-s-ipython span.cm-comment { color: #408080; font-style: italic; } .cm-s-ipython span.cm-string { color: #BA2121; } .cm-s-ipython span.cm-string-2 { color: #f50; } .cm-s-ipython span.cm-meta { color: #AA22FF; } .cm-s-ipython span.cm-qualifier { color: #555; } .cm-s-ipython span.cm-builtin { color: #008000; } .cm-s-ipython span.cm-bracket { color: #997; } .cm-s-ipython span.cm-tag { color: #170; } .cm-s-ipython span.cm-attribute { color: #00c; } .cm-s-ipython span.cm-header { color: blue; } .cm-s-ipython span.cm-quote { color: #090; } .cm-s-ipython span.cm-link { color: #00c; } .cm-s-ipython span.cm-error { color: #f00; } .cm-s-ipython span.cm-tab { background: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADAAAAAMCAYAAAAkuj5RAAAAAXNSR0IArs4c6QAAAGFJREFUSMft1LsRQFAQheHPowAKoACx3IgEKtaEHujDjORSgWTH/ZOdnZOcM/sgk/kFFWY0qV8foQwS4MKBCS3qR6ixBJvElOobYAtivseIE120FaowJPN75GMu8j/LfMwNjh4HUpwg4LUAAAAASUVORK5CYII=); background-position: right; background-repeat: no-repeat; } div.output\_wrapper { /\* this position must be relative to enable descendents to be absolute within it \*/ position: relative; /\* Old browsers \*/ display: -webkit-box; -webkit-box-orient: vertical; -webkit-box-align: stretch; display: -moz-box; -moz-box-orient: vertical; -moz-box-align: stretch; display: box; box-orient: vertical; box-align: stretch; /\* Modern browsers \*/ display: flex; flex-direction: column; align-items: stretch; z-index: 1; } /\* class for the output area when it should be height-limited \*/ div.output\_scroll { /\* ideally, this would be max-height, but FF barfs all over that \*/ height: 24em; /\* FF needs this \*and the wrapper\* to specify full width, or it will shrinkwrap \*/ width: 100%; overflow: auto; border-radius: 2px; -webkit-box-shadow: inset 0 2px 8px rgba(0, 0, 0, 0.8); box-shadow: inset 0 2px 8px rgba(0, 0, 0, 0.8); display: block; } /\* output div while it is collapsed \*/ div.output\_collapsed { margin: 0px; padding: 0px; /\* Old browsers \*/ display: -webkit-box; -webkit-box-orient: vertical; -webkit-box-align: stretch; display: -moz-box; -moz-box-orient: vertical; -moz-box-align: stretch; display: box; box-orient: vertical; box-align: stretch; /\* Modern browsers \*/ display: flex; flex-direction: column; align-items: stretch; } div.out\_prompt\_overlay { height: 100%; padding: 0px 0.4em; position: absolute; border-radius: 2px; } div.out\_prompt\_overlay:hover { /\* use inner shadow to get border that is computed the same on WebKit/FF \*/ -webkit-box-shadow: inset 0 0 1px #000; box-shadow: inset 0 0 1px #000; background: rgba(240, 240, 240, 0.5); } div.output\_prompt { color: #D84315; } /\* This class is the outer container of all output sections. \*/ div.output\_area { padding: 0px; page-break-inside: avoid; /\* Old browsers \*/ display: -webkit-box; -webkit-box-orient: horizontal; -webkit-box-align: stretch; display: -moz-box; -moz-box-orient: horizontal; -moz-box-align: stretch; display: box; box-orient: horizontal; box-align: stretch; /\* Modern browsers \*/ display: flex; flex-direction: row; align-items: stretch; } div.output\_area .MathJax\_Display { text-align: left !important; } div.output\_area .rendered\_html table { margin-left: 0; margin-right: 0; } div.output\_area .rendered\_html img { margin-left: 0; margin-right: 0; } div.output\_area img, div.output\_area svg { max-width: 100%; height: auto; } div.output\_area img.unconfined, div.output\_area svg.unconfined { max-width: none; } div.output\_area .mglyph > img { max-width: none; } /\* This is needed to protect the pre formating from global settings such as that of bootstrap \*/ .output { /\* Old browsers \*/ display: -webkit-box; -webkit-box-orient: vertical; -webkit-box-align: stretch; display: -moz-box; -moz-box-orient: vertical; -moz-box-align: stretch; display: box; box-orient: vertical; box-align: stretch; /\* Modern browsers \*/ display: flex; flex-direction: column; align-items: stretch; } @media (max-width: 540px) { div.output\_area { /\* Old browsers \*/ display: -webkit-box; -webkit-box-orient: vertical; -webkit-box-align: stretch; display: -moz-box; -moz-box-orient: vertical; -moz-box-align: stretch; display: box; box-orient: vertical; box-align: stretch; /\* Modern browsers \*/ display: flex; flex-direction: column; align-items: stretch; } } div.output\_area pre { margin: 0; padding: 1px 0 1px 0; border: 0; vertical-align: baseline; color: black; background-color: transparent; border-radius: 0; } /\* This class is for the output subarea inside the output\_area and after the prompt div. \*/ div.output\_subarea { overflow-x: auto; padding: 0.4em; /\* Old browsers \*/ -webkit-box-flex: 1; -moz-box-flex: 1; box-flex: 1; /\* Modern browsers \*/ flex: 1; max-width: calc(100% - 14ex); } div.output\_scroll div.output\_subarea { overflow-x: visible; } /\* The rest of the output\_\* classes are for special styling of the different output types \*/ /\* all text output has this class: \*/ div.output\_text { text-align: left; color: #000; /\* This has to match that of the the CodeMirror class line-height below \*/ line-height: 1.21429em; } /\* stdout/stderr are 'text' as well as 'stream', but execute\_result/error are \*not\* streams \*/ div.output\_stderr { background: #fdd; /\* very light red background for stderr \*/ } div.output\_latex { text-align: left; } /\* Empty output\_javascript divs should have no height \*/ div.output\_javascript:empty { padding: 0; } .js-error { color: darkred; } /\* raw\_input styles \*/ div.raw\_input\_container { line-height: 1.21429em; padding-top: 5px; } pre.raw\_input\_prompt { /\* nothing needed here. \*/ } input.raw\_input { font-family: monospace; font-size: inherit; color: inherit; width: auto; /\* make sure input baseline aligns with prompt \*/ vertical-align: baseline; /\* padding + margin = 0.5em between prompt and cursor \*/ padding: 0em 0.25em; margin: 0em 0.25em; } input.raw\_input:focus { box-shadow: none; } p.p-space { margin-bottom: 10px; } div.output\_unrecognized { padding: 5px; font-weight: bold; color: red; } div.output\_unrecognized a { color: inherit; text-decoration: none; } div.output\_unrecognized a:hover { color: inherit; text-decoration: none; } .rendered\_html { color: #000; /\* any extras will just be numbers: \*/ } .rendered\_html em { font-style: italic; } .rendered\_html strong { font-weight: bold; } .rendered\_html u { text-decoration: underline; } .rendered\_html :link { text-decoration: underline; } .rendered\_html :visited { text-decoration: underline; } .rendered\_html h1 { font-size: 185.7%; margin: 1.08em 0 0 0; font-weight: bold; line-height: 1.0; } .rendered\_html h2 { font-size: 157.1%; margin: 1.27em 0 0 0; font-weight: bold; line-height: 1.0; } .rendered\_html h3 { font-size: 128.6%; margin: 1.55em 0 0 0; font-weight: bold; line-height: 1.0; } .rendered\_html h4 { font-size: 100%; margin: 2em 0 0 0; font-weight: bold; line-height: 1.0; } .rendered\_html h5 { font-size: 100%; margin: 2em 0 0 0; font-weight: bold; line-height: 1.0; font-style: italic; } .rendered\_html h6 { font-size: 100%; margin: 2em 0 0 0; font-weight: bold; line-height: 1.0; font-style: italic; } .rendered\_html h1:first-child { margin-top: 0.538em; } .rendered\_html h2:first-child { margin-top: 0.636em; } .rendered\_html h3:first-child { margin-top: 0.777em; } .rendered\_html h4:first-child { margin-top: 1em; } .rendered\_html h5:first-child { margin-top: 1em; } .rendered\_html h6:first-child { margin-top: 1em; } .rendered\_html ul:not(.list-inline), .rendered\_html ol:not(.list-inline) { padding-left: 2em; } .rendered\_html ul { list-style: disc; } .rendered\_html ul ul { list-style: square; margin-top: 0; } .rendered\_html ul ul ul { list-style: circle; } .rendered\_html ol { list-style: decimal; } .rendered\_html ol ol { list-style: upper-alpha; margin-top: 0; } .rendered\_html ol ol ol { list-style: lower-alpha; } .rendered\_html ol ol ol ol { list-style: lower-roman; } .rendered\_html ol ol ol ol ol { list-style: decimal; } .rendered\_html \* + ul { margin-top: 1em; } .rendered\_html \* + ol { margin-top: 1em; } .rendered\_html hr { color: black; background-color: black; } .rendered\_html pre { margin: 1em 2em; padding: 0px; background-color: #fff; } .rendered\_html code { background-color: #eff0f1; } .rendered\_html p code { padding: 1px 5px; } .rendered\_html pre code { background-color: #fff; } .rendered\_html pre, .rendered\_html code { border: 0; color: #000; font-size: 100%; } .rendered\_html blockquote { margin: 1em 2em; } .rendered\_html table { margin-left: auto; margin-right: auto; border: none; border-collapse: collapse; border-spacing: 0; color: black; font-size: 12px; table-layout: fixed; } .rendered\_html thead { border-bottom: 1px solid black; vertical-align: bottom; } .rendered\_html tr, .rendered\_html th, .rendered\_html td { text-align: right; vertical-align: middle; padding: 0.5em 0.5em; line-height: normal; white-space: normal; max-width: none; border: none; } .rendered\_html th { font-weight: bold; } .rendered\_html tbody tr:nth-child(odd) { background: #f5f5f5; } .rendered\_html tbody tr:hover { background: rgba(66, 165, 245, 0.2); } .rendered\_html \* + table { margin-top: 1em; } .rendered\_html p { text-align: left; } .rendered\_html \* + p { margin-top: 1em; } .rendered\_html img { display: block; margin-left: auto; margin-right: auto; } .rendered\_html \* + img { margin-top: 1em; } .rendered\_html img, .rendered\_html svg { max-width: 100%; height: auto; } .rendered\_html img.unconfined, .rendered\_html svg.unconfined { max-width: none; } .rendered\_html .alert { margin-bottom: initial; } .rendered\_html \* + .alert { margin-top: 1em; } \[dir="rtl"\] .rendered\_html p { text-align: right; } div.text\_cell { /\* Old browsers \*/ display: -webkit-box; -webkit-box-orient: horizontal; -webkit-box-align: stretch; display: -moz-box; -moz-box-orient: horizontal; -moz-box-align: stretch; display: box; box-orient: horizontal; box-align: stretch; /\* Modern browsers \*/ display: flex; flex-direction: row; align-items: stretch; } @media (max-width: 540px) { div.text\_cell > div.prompt { display: none; } } div.text\_cell\_render { /\*font-family: "Helvetica Neue", Arial, Helvetica, Geneva, sans-serif;\*/ outline: none; resize: none; width: inherit; border-style: none; padding: 0.5em 0.5em 0.5em 0.4em; color: #000; box-sizing: border-box; -moz-box-sizing: border-box; -webkit-box-sizing: border-box; } a.anchor-link:link { text-decoration: none; padding: 0px 20px; visibility: hidden; } h1:hover .anchor-link, h2:hover .anchor-link, h3:hover .anchor-link, h4:hover .anchor-link, h5:hover .anchor-link, h6:hover .anchor-link { visibility: visible; } .text\_cell.rendered .input\_area { display: none; } .text\_cell.rendered .rendered\_html { overflow-x: auto; overflow-y: hidden; } .text\_cell.rendered .rendered\_html tr, .text\_cell.rendered .rendered\_html th, .text\_cell.rendered .rendered\_html td { max-width: none; } .text\_cell.unrendered .text\_cell\_render { display: none; } .text\_cell .dropzone .input\_area { border: 2px dashed #bababa; margin: -1px; } .cm-header-1, .cm-header-2, .cm-header-3, .cm-header-4, .cm-header-5, .cm-header-6 { font-weight: bold; font-family: "Helvetica Neue", Helvetica, Arial, sans-serif; } .cm-header-1 { font-size: 185.7%; } .cm-header-2 { font-size: 157.1%; } .cm-header-3 { font-size: 128.6%; } .cm-header-4 { font-size: 110%; } .cm-header-5 { font-size: 100%; font-style: italic; } .cm-header-6 { font-size: 100%; font-style: italic; } /\*! \* \* IPython notebook webapp \* \*/ @media (max-width: 767px) { .notebook\_app { padding-left: 0px; padding-right: 0px; } } #ipython-main-app { box-sizing: border-box; -moz-box-sizing: border-box; -webkit-box-sizing: border-box; height: 100%; } div#notebook\_panel { margin: 0px; padding: 0px; box-sizing: border-box; -moz-box-sizing: border-box; -webkit-box-sizing: border-box; height: 100%; } div#notebook { font-size: 14px; line-height: 20px; overflow-y: hidden; overflow-x: auto; width: 100%; /\* This spaces the page away from the edge of the notebook area \*/ padding-top: 20px; margin: 0px; outline: none; box-sizing: border-box; -moz-box-sizing: border-box; -webkit-box-sizing: border-box; min-height: 100%; } @media not print { #notebook-container { padding: 15px; background-color: #fff; min-height: 0; -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2); box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2); } } @media print { #notebook-container { width: 100%; } } div.ui-widget-content { border: 1px solid #ababab; outline: none; } pre.dialog { background-color: #f7f7f7; border: 1px solid #ddd; border-radius: 2px; padding: 0.4em; padding-left: 2em; } p.dialog { padding: 0.2em; } /\* Word-wrap output correctly. This is the CSS3 spelling, though Firefox seems to not honor it correctly. Webkit browsers (Chrome, rekonq, Safari) do. \*/ pre, code, kbd, samp { white-space: pre-wrap; } #fonttest { font-family: monospace; } p { margin-bottom: 0; } .end\_space { min-height: 100px; transition: height .2s ease; } .notebook\_app > #header { -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2); box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2); } @media not print { .notebook\_app { background-color: #EEE; } } kbd { border-style: solid; border-width: 1px; box-shadow: none; margin: 2px; padding-left: 2px; padding-right: 2px; padding-top: 1px; padding-bottom: 1px; } .jupyter-keybindings { padding: 1px; line-height: 24px; border-bottom: 1px solid gray; } .jupyter-keybindings input { margin: 0; padding: 0; border: none; } .jupyter-keybindings i { padding: 6px; } .well code { background-color: #ffffff; border-color: #ababab; border-width: 1px; border-style: solid; padding: 2px; padding-top: 1px; padding-bottom: 1px; } /\* CSS for the cell toolbar \*/ .celltoolbar { border: thin solid #CFCFCF; border-bottom: none; background: #EEE; border-radius: 2px 2px 0px 0px; width: 100%; height: 29px; padding-right: 4px; /\* Old browsers \*/ display: -webkit-box; -webkit-box-orient: horizontal; -webkit-box-align: stretch; display: -moz-box; -moz-box-orient: horizontal; -moz-box-align: stretch; display: box; box-orient: horizontal; box-align: stretch; /\* Modern browsers \*/ display: flex; flex-direction: row; align-items: stretch; /\* Old browsers \*/ -webkit-box-pack: end; -moz-box-pack: end; box-pack: end; /\* Modern browsers \*/ justify-content: flex-end; display: -webkit-flex; } @media print { .celltoolbar { display: none; } } .ctb\_hideshow { display: none; vertical-align: bottom; } /\* ctb\_show is added to the ctb\_hideshow div to show the cell toolbar. Cell toolbars are only shown when the ctb\_global\_show class is also set. \*/ .ctb\_global\_show .ctb\_show.ctb\_hideshow { display: block; } .ctb\_global\_show .ctb\_show + .input\_area, .ctb\_global\_show .ctb\_show + div.text\_cell\_input, .ctb\_global\_show .ctb\_show ~ div.text\_cell\_render { border-top-right-radius: 0px; border-top-left-radius: 0px; } .ctb\_global\_show .ctb\_show ~ div.text\_cell\_render { border: 1px solid #cfcfcf; } .celltoolbar { font-size: 87%; padding-top: 3px; } .celltoolbar select { display: block; width: 100%; height: 32px; padding: 6px 12px; font-size: 13px; line-height: 1.42857143; color: #555555; background-color: #fff; background-image: none; border: 1px solid #ccc; border-radius: 2px; -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075); box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075); -webkit-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s; -o-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s; transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s; height: 30px; padding: 5px 10px; font-size: 12px; line-height: 1.5; border-radius: 1px; width: inherit; font-size: inherit; height: 22px; padding: 0px; display: inline-block; } .celltoolbar select:focus { border-color: #66afe9; outline: 0; -webkit-box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6); box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6); } .celltoolbar select::-moz-placeholder { color: #999; opacity: 1; } .celltoolbar select:-ms-input-placeholder { color: #999; } .celltoolbar select::-webkit-input-placeholder { color: #999; } .celltoolbar select::-ms-expand { border: 0; background-color: transparent; } .celltoolbar select\[disabled\], .celltoolbar select\[readonly\], fieldset\[disabled\] .celltoolbar select { background-color: #eeeeee; opacity: 1; } .celltoolbar select\[disabled\], fieldset\[disabled\] .celltoolbar select { cursor: not-allowed; } textarea.celltoolbar select { height: auto; } select.celltoolbar select { height: 30px; line-height: 30px; } textarea.celltoolbar select, select\[multiple\].celltoolbar select { height: auto; } .celltoolbar label { margin-left: 5px; margin-right: 5px; } .tags\_button\_container { width: 100%; display: flex; } .tag-container { display: flex; flex-direction: row; flex-grow: 1; overflow: hidden; position: relative; } .tag-container > \* { margin: 0 4px; } .remove-tag-btn { margin-left: 4px; } .tags-input { display: flex; } .cell-tag:last-child:after { content: ""; position: absolute; right: 0; width: 40px; height: 100%; /\* Fade to background color of cell toolbar \*/ background: linear-gradient(to right, rgba(0, 0, 0, 0), #EEE); } .tags-input > \* { margin-left: 4px; } .cell-tag, .tags-input input, .tags-input button { display: block; width: 100%; height: 32px; padding: 6px 12px; font-size: 13px; line-height: 1.42857143; color: #555555; background-color: #fff; background-image: none; border: 1px solid #ccc; border-radius: 2px; -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075); box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075); -webkit-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s; -o-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s; transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s; height: 30px; padding: 5px 10px; font-size: 12px; line-height: 1.5; border-radius: 1px; box-shadow: none; width: inherit; font-size: inherit; height: 22px; line-height: 22px; padding: 0px 4px; display: inline-block; } .cell-tag:focus, .tags-input input:focus, .tags-input button:focus { border-color: #66afe9; outline: 0; -webkit-box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6); box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6); } .cell-tag::-moz-placeholder, .tags-input input::-moz-placeholder, .tags-input button::-moz-placeholder { color: #999; opacity: 1; } .cell-tag:-ms-input-placeholder, .tags-input input:-ms-input-placeholder, .tags-input button:-ms-input-placeholder { color: #999; } .cell-tag::-webkit-input-placeholder, .tags-input input::-webkit-input-placeholder, .tags-input button::-webkit-input-placeholder { color: #999; } .cell-tag::-ms-expand, .tags-input input::-ms-expand, .tags-input button::-ms-expand { border: 0; background-color: transparent; } .cell-tag\[disabled\], .tags-input input\[disabled\], .tags-input button\[disabled\], .cell-tag\[readonly\], .tags-input input\[readonly\], .tags-input button\[readonly\], fieldset\[disabled\] .cell-tag, fieldset\[disabled\] .tags-input input, fieldset\[disabled\] .tags-input button { background-color: #eeeeee; opacity: 1; } .cell-tag\[disabled\], .tags-input input\[disabled\], .tags-input button\[disabled\], fieldset\[disabled\] .cell-tag, fieldset\[disabled\] .tags-input input, fieldset\[disabled\] .tags-input button { cursor: not-allowed; } textarea.cell-tag, textarea.tags-input input, textarea.tags-input button { height: auto; } select.cell-tag, select.tags-input input, select.tags-input button { height: 30px; line-height: 30px; } textarea.cell-tag, textarea.tags-input input, textarea.tags-input button, select\[multiple\].cell-tag, select\[multiple\].tags-input input, select\[multiple\].tags-input button { height: auto; } .cell-tag, .tags-input button { padding: 0px 4px; } .cell-tag { background-color: #fff; white-space: nowrap; } .tags-input input\[type=text\]:focus { outline: none; box-shadow: none; border-color: #ccc; } .completions { position: absolute; z-index: 110; overflow: hidden; border: 1px solid #ababab; border-radius: 2px; -webkit-box-shadow: 0px 6px 10px -1px #adadad; box-shadow: 0px 6px 10px -1px #adadad; line-height: 1; } .completions select { background: white; outline: none; border: none; padding: 0px; margin: 0px; overflow: auto; font-family: monospace; font-size: 110%; color: #000; width: auto; } .completions select option.context { color: #286090; } #kernel\_logo\_widget .current\_kernel\_logo { display: none; margin-top: -1px; margin-bottom: -1px; width: 32px; height: 32px; } \[dir="rtl"\] #kernel\_logo\_widget { float: left !important; float: left; } .modal .modal-body .move-path { display: flex; flex-direction: row; justify-content: space; align-items: center; } .modal .modal-body .move-path .server-root { padding-right: 20px; } .modal .modal-body .move-path .path-input { flex: 1; } #menubar { box-sizing: border-box; -moz-box-sizing: border-box; -webkit-box-sizing: border-box; margin-top: 1px; } #menubar .navbar { border-top: 1px; border-radius: 0px 0px 2px 2px; margin-bottom: 0px; } #menubar .navbar-toggle { float: left; padding-top: 7px; padding-bottom: 7px; border: none; } #menubar .navbar-collapse { clear: left; } \[dir="rtl"\] #menubar .navbar-toggle { float: right; } \[dir="rtl"\] #menubar .navbar-collapse { clear: right; } \[dir="rtl"\] #menubar .navbar-nav { float: right; } \[dir="rtl"\] #menubar .nav { padding-right: 0px; } \[dir="rtl"\] #menubar .navbar-nav > li { float: right; } \[dir="rtl"\] #menubar .navbar-right { float: left !important; } \[dir="rtl"\] ul.dropdown-menu { text-align: right; left: auto; } \[dir="rtl"\] ul#new-menu.dropdown-menu { right: auto; left: 0; } .nav-wrapper { border-bottom: 1px solid #e7e7e7; } i.menu-icon { padding-top: 4px; } \[dir="rtl"\] i.menu-icon.pull-right { float: left !important; float: left; } ul#help\_menu li a { overflow: hidden; padding-right: 2.2em; } ul#help\_menu li a i { margin-right: -1.2em; } \[dir="rtl"\] ul#help\_menu li a { padding-left: 2.2em; } \[dir="rtl"\] ul#help\_menu li a i { margin-right: 0; margin-left: -1.2em; } \[dir="rtl"\] ul#help\_menu li a i.pull-right { float: left !important; float: left; } .dropdown-submenu { position: relative; } .dropdown-submenu > .dropdown-menu { top: 0; left: 100%; margin-top: -6px; margin-left: -1px; } \[dir="rtl"\] .dropdown-submenu > .dropdown-menu { right: 100%; margin-right: -1px; } .dropdown-submenu:hover > .dropdown-menu { display: block; } .dropdown-submenu > a:after { display: inline-block; font: normal normal normal 14px/1 FontAwesome; font-size: inherit; text-rendering: auto; -webkit-font-smoothing: antialiased; -moz-osx-font-smoothing: grayscale; display: block; content: "\\f0da"; float: right; color: #333333; margin-top: 2px; margin-right: -10px; } .dropdown-submenu > a:after.fa-pull-left { margin-right: .3em; } .dropdown-submenu > a:after.fa-pull-right { margin-left: .3em; } .dropdown-submenu > a:after.pull-left { margin-right: .3em; } .dropdown-submenu > a:after.pull-right { margin-left: .3em; } \[dir="rtl"\] .dropdown-submenu > a:after { float: left; content: "\\f0d9"; margin-right: 0; margin-left: -10px; } .dropdown-submenu:hover > a:after { color: #262626; } .dropdown-submenu.pull-left { float: none; } .dropdown-submenu.pull-left > .dropdown-menu { left: -100%; margin-left: 10px; } #notification\_area { float: right !important; float: right; z-index: 10; } \[dir="rtl"\] #notification\_area { float: left !important; float: left; } .indicator\_area { float: right !important; float: right; color: #777; margin-left: 5px; margin-right: 5px; width: 11px; z-index: 10; text-align: center; width: auto; } \[dir="rtl"\] .indicator\_area { float: left !important; float: left; } #kernel\_indicator { float: right !important; float: right; color: #777; margin-left: 5px; margin-right: 5px; width: 11px; z-index: 10; text-align: center; width: auto; border-left: 1px solid; } #kernel\_indicator .kernel\_indicator\_name { padding-left: 5px; padding-right: 5px; } \[dir="rtl"\] #kernel\_indicator { float: left !important; float: left; border-left: 0; border-right: 1px solid; } #modal\_indicator { float: right !important; float: right; color: #777; margin-left: 5px; margin-right: 5px; width: 11px; z-index: 10; text-align: center; width: auto; } \[dir="rtl"\] #modal\_indicator { float: left !important; float: left; } #readonly-indicator { float: right !important; float: right; color: #777; margin-left: 5px; margin-right: 5px; width: 11px; z-index: 10; text-align: center; width: auto; margin-top: 2px; margin-bottom: 0px; margin-left: 0px; margin-right: 0px; display: none; } .modal\_indicator:before { width: 1.28571429em; text-align: center; } .edit\_mode .modal\_indicator:before { display: inline-block; font: normal normal normal 14px/1 FontAwesome; font-size: inherit; text-rendering: auto; -webkit-font-smoothing: antialiased; -moz-osx-font-smoothing: grayscale; content: "\\f040"; } .edit\_mode .modal\_indicator:before.fa-pull-left { margin-right: .3em; } .edit\_mode .modal\_indicator:before.fa-pull-right { margin-left: .3em; } .edit\_mode .modal\_indicator:before.pull-left { margin-right: .3em; } .edit\_mode .modal\_indicator:before.pull-right { margin-left: .3em; } .command\_mode .modal\_indicator:before { display: inline-block; font: normal normal normal 14px/1 FontAwesome; font-size: inherit; text-rendering: auto; -webkit-font-smoothing: antialiased; -moz-osx-font-smoothing: grayscale; content: ' '; } .command\_mode .modal\_indicator:before.fa-pull-left { margin-right: .3em; } .command\_mode .modal\_indicator:before.fa-pull-right { margin-left: .3em; } .command\_mode .modal\_indicator:before.pull-left { margin-right: .3em; } .command\_mode .modal\_indicator:before.pull-right { margin-left: .3em; } .kernel\_idle\_icon:before { display: inline-block; font: normal normal normal 14px/1 FontAwesome; font-size: inherit; text-rendering: auto; -webkit-font-smoothing: antialiased; -moz-osx-font-smoothing: grayscale; content: "\\f10c"; } .kernel\_idle\_icon:before.fa-pull-left { margin-right: .3em; } .kernel\_idle\_icon:before.fa-pull-right { margin-left: .3em; } .kernel\_idle\_icon:before.pull-left { margin-right: .3em; } .kernel\_idle\_icon:before.pull-right { margin-left: .3em; } .kernel\_busy\_icon:before { display: inline-block; font: normal normal normal 14px/1 FontAwesome; font-size: inherit; text-rendering: auto; -webkit-font-smoothing: antialiased; -moz-osx-font-smoothing: grayscale; content: "\\f111"; } .kernel\_busy\_icon:before.fa-pull-left { margin-right: .3em; } .kernel\_busy\_icon:before.fa-pull-right { margin-left: .3em; } .kernel\_busy\_icon:before.pull-left { margin-right: .3em; } .kernel\_busy\_icon:before.pull-right { margin-left: .3em; } .kernel\_dead\_icon:before { display: inline-block; font: normal normal normal 14px/1 FontAwesome; font-size: inherit; text-rendering: auto; -webkit-font-smoothing: antialiased; -moz-osx-font-smoothing: grayscale; content: "\\f1e2"; } .kernel\_dead\_icon:before.fa-pull-left { margin-right: .3em; } .kernel\_dead\_icon:before.fa-pull-right { margin-left: .3em; } .kernel\_dead\_icon:before.pull-left { margin-right: .3em; } .kernel\_dead\_icon:before.pull-right { margin-left: .3em; } .kernel\_disconnected\_icon:before { display: inline-block; font: normal normal normal 14px/1 FontAwesome; font-size: inherit; text-rendering: auto; -webkit-font-smoothing: antialiased; -moz-osx-font-smoothing: grayscale; content: "\\f127"; } .kernel\_disconnected\_icon:before.fa-pull-left { margin-right: .3em; } .kernel\_disconnected\_icon:before.fa-pull-right { margin-left: .3em; } .kernel\_disconnected\_icon:before.pull-left { margin-right: .3em; } .kernel\_disconnected\_icon:before.pull-right { margin-left: .3em; } .notification\_widget { color: #777; z-index: 10; background: rgba(240, 240, 240, 0.5); margin-right: 4px; color: #333; background-color: #fff; border-color: #ccc; } .notification\_widget:focus, .notification\_widget.focus { color: #333; background-color: #e6e6e6; border-color: #8c8c8c; } .notification\_widget:hover { color: #333; background-color: #e6e6e6; border-color: #adadad; } .notification\_widget:active, .notification\_widget.active, .open > .dropdown-toggle.notification\_widget { color: #333; background-color: #e6e6e6; border-color: #adadad; } .notification\_widget:active:hover, .notification\_widget.active:hover, .open > .dropdown-toggle.notification\_widget:hover, .notification\_widget:active:focus, .notification\_widget.active:focus, .open > .dropdown-toggle.notification\_widget:focus, .notification\_widget:active.focus, .notification\_widget.active.focus, .open > .dropdown-toggle.notification\_widget.focus { color: #333; background-color: #d4d4d4; border-color: #8c8c8c; } .notification\_widget:active, .notification\_widget.active, .open > .dropdown-toggle.notification\_widget { background-image: none; } .notification\_widget.disabled:hover, .notification\_widget\[disabled\]:hover, fieldset\[disabled\] .notification\_widget:hover, .notification\_widget.disabled:focus, .notification\_widget\[disabled\]:focus, fieldset\[disabled\] .notification\_widget:focus, .notification\_widget.disabled.focus, .notification\_widget\[disabled\].focus, fieldset\[disabled\] .notification\_widget.focus { background-color: #fff; border-color: #ccc; } .notification\_widget .badge { color: #fff; background-color: #333; } .notification\_widget.warning { color: #fff; background-color: #f0ad4e; border-color: #eea236; } .notification\_widget.warning:focus, .notification\_widget.warning.focus { color: #fff; background-color: #ec971f; border-color: #985f0d; } .notification\_widget.warning:hover { color: #fff; background-color: #ec971f; border-color: #d58512; } .notification\_widget.warning:active, .notification\_widget.warning.active, .open > .dropdown-toggle.notification\_widget.warning { color: #fff; background-color: #ec971f; border-color: #d58512; } .notification\_widget.warning:active:hover, .notification\_widget.warning.active:hover, .open > .dropdown-toggle.notification\_widget.warning:hover, .notification\_widget.warning:active:focus, .notification\_widget.warning.active:focus, .open > .dropdown-toggle.notification\_widget.warning:focus, .notification\_widget.warning:active.focus, .notification\_widget.warning.active.focus, .open > .dropdown-toggle.notification\_widget.warning.focus { color: #fff; background-color: #d58512; border-color: #985f0d; } .notification\_widget.warning:active, .notification\_widget.warning.active, .open > .dropdown-toggle.notification\_widget.warning { background-image: none; } .notification\_widget.warning.disabled:hover, .notification\_widget.warning\[disabled\]:hover, fieldset\[disabled\] .notification\_widget.warning:hover, .notification\_widget.warning.disabled:focus, .notification\_widget.warning\[disabled\]:focus, fieldset\[disabled\] .notification\_widget.warning:focus, .notification\_widget.warning.disabled.focus, .notification\_widget.warning\[disabled\].focus, fieldset\[disabled\] .notification\_widget.warning.focus { background-color: #f0ad4e; border-color: #eea236; } .notification\_widget.warning .badge { color: #f0ad4e; background-color: #fff; } .notification\_widget.success { color: #fff; background-color: #5cb85c; border-color: #4cae4c; } .notification\_widget.success:focus, .notification\_widget.success.focus { color: #fff; background-color: #449d44; border-color: #255625; } .notification\_widget.success:hover { color: #fff; background-color: #449d44; border-color: #398439; } .notification\_widget.success:active, .notification\_widget.success.active, .open > .dropdown-toggle.notification\_widget.success { color: #fff; background-color: #449d44; border-color: #398439; } .notification\_widget.success:active:hover, .notification\_widget.success.active:hover, .open > .dropdown-toggle.notification\_widget.success:hover, .notification\_widget.success:active:focus, .notification\_widget.success.active:focus, .open > .dropdown-toggle.notification\_widget.success:focus, .notification\_widget.success:active.focus, .notification\_widget.success.active.focus, .open > .dropdown-toggle.notification\_widget.success.focus { color: #fff; background-color: #398439; border-color: #255625; } .notification\_widget.success:active, .notification\_widget.success.active, .open > .dropdown-toggle.notification\_widget.success { background-image: none; } .notification\_widget.success.disabled:hover, .notification\_widget.success\[disabled\]:hover, fieldset\[disabled\] .notification\_widget.success:hover, .notification\_widget.success.disabled:focus, .notification\_widget.success\[disabled\]:focus, fieldset\[disabled\] .notification\_widget.success:focus, .notification\_widget.success.disabled.focus, .notification\_widget.success\[disabled\].focus, fieldset\[disabled\] .notification\_widget.success.focus { background-color: #5cb85c; border-color: #4cae4c; } .notification\_widget.success .badge { color: #5cb85c; background-color: #fff; } .notification\_widget.info { color: #fff; background-color: #5bc0de; border-color: #46b8da; } .notification\_widget.info:focus, .notification\_widget.info.focus { color: #fff; background-color: #31b0d5; border-color: #1b6d85; } .notification\_widget.info:hover { color: #fff; background-color: #31b0d5; border-color: #269abc; } .notification\_widget.info:active, .notification\_widget.info.active, .open > .dropdown-toggle.notification\_widget.info { color: #fff; background-color: #31b0d5; border-color: #269abc; } .notification\_widget.info:active:hover, .notification\_widget.info.active:hover, .open > .dropdown-toggle.notification\_widget.info:hover, .notification\_widget.info:active:focus, .notification\_widget.info.active:focus, .open > .dropdown-toggle.notification\_widget.info:focus, .notification\_widget.info:active.focus, .notification\_widget.info.active.focus, .open > .dropdown-toggle.notification\_widget.info.focus { color: #fff; background-color: #269abc; border-color: #1b6d85; } .notification\_widget.info:active, .notification\_widget.info.active, .open > .dropdown-toggle.notification\_widget.info { background-image: none; } .notification\_widget.info.disabled:hover, .notification\_widget.info\[disabled\]:hover, fieldset\[disabled\] .notification\_widget.info:hover, .notification\_widget.info.disabled:focus, .notification\_widget.info\[disabled\]:focus, fieldset\[disabled\] .notification\_widget.info:focus, .notification\_widget.info.disabled.focus, .notification\_widget.info\[disabled\].focus, fieldset\[disabled\] .notification\_widget.info.focus { background-color: #5bc0de; border-color: #46b8da; } .notification\_widget.info .badge { color: #5bc0de; background-color: #fff; } .notification\_widget.danger { color: #fff; background-color: #d9534f; border-color: #d43f3a; } .notification\_widget.danger:focus, .notification\_widget.danger.focus { color: #fff; background-color: #c9302c; border-color: #761c19; } .notification\_widget.danger:hover { color: #fff; background-color: #c9302c; border-color: #ac2925; } .notification\_widget.danger:active, .notification\_widget.danger.active, .open > .dropdown-toggle.notification\_widget.danger { color: #fff; background-color: #c9302c; border-color: #ac2925; } .notification\_widget.danger:active:hover, .notification\_widget.danger.active:hover, .open > .dropdown-toggle.notification\_widget.danger:hover, .notification\_widget.danger:active:focus, .notification\_widget.danger.active:focus, .open > .dropdown-toggle.notification\_widget.danger:focus, .notification\_widget.danger:active.focus, .notification\_widget.danger.active.focus, .open > .dropdown-toggle.notification\_widget.danger.focus { color: #fff; background-color: #ac2925; border-color: #761c19; } .notification\_widget.danger:active, .notification\_widget.danger.active, .open > .dropdown-toggle.notification\_widget.danger { background-image: none; } .notification\_widget.danger.disabled:hover, .notification\_widget.danger\[disabled\]:hover, fieldset\[disabled\] .notification\_widget.danger:hover, .notification\_widget.danger.disabled:focus, .notification\_widget.danger\[disabled\]:focus, fieldset\[disabled\] .notification\_widget.danger:focus, .notification\_widget.danger.disabled.focus, .notification\_widget.danger\[disabled\].focus, fieldset\[disabled\] .notification\_widget.danger.focus { background-color: #d9534f; border-color: #d43f3a; } .notification\_widget.danger .badge { color: #d9534f; background-color: #fff; } div#pager { background-color: #fff; font-size: 14px; line-height: 20px; overflow: hidden; display: none; position: fixed; bottom: 0px; width: 100%; max-height: 50%; padding-top: 8px; -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2); box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2); /\* Display over codemirror \*/ z-index: 100; /\* Hack which prevents jquery ui resizable from changing top. \*/ top: auto !important; } div#pager pre { line-height: 1.21429em; color: #000; background-color: #f7f7f7; padding: 0.4em; } div#pager #pager-button-area { position: absolute; top: 8px; right: 20px; } div#pager #pager-contents { position: relative; overflow: auto; width: 100%; height: 100%; } div#pager #pager-contents #pager-container { position: relative; padding: 15px 0px; box-sizing: border-box; -moz-box-sizing: border-box; -webkit-box-sizing: border-box; } div#pager .ui-resizable-handle { top: 0px; height: 8px; background: #f7f7f7; border-top: 1px solid #cfcfcf; border-bottom: 1px solid #cfcfcf; /\* This injects handle bars (a short, wide = symbol) for the resize handle. \*/ } div#pager .ui-resizable-handle::after { content: ''; top: 2px; left: 50%; height: 3px; width: 30px; margin-left: -15px; position: absolute; border-top: 1px solid #cfcfcf; } .quickhelp { /\* Old browsers \*/ display: -webkit-box; -webkit-box-orient: horizontal; -webkit-box-align: stretch; display: -moz-box; -moz-box-orient: horizontal; -moz-box-align: stretch; display: box; box-orient: horizontal; box-align: stretch; /\* Modern browsers \*/ display: flex; flex-direction: row; align-items: stretch; line-height: 1.8em; } .shortcut\_key { display: inline-block; width: 21ex; text-align: right; font-family: monospace; } .shortcut\_descr { display: inline-block; /\* Old browsers \*/ -webkit-box-flex: 1; -moz-box-flex: 1; box-flex: 1; /\* Modern browsers \*/ flex: 1; } span.save\_widget { height: 30px; margin-top: 4px; display: flex; justify-content: flex-start; align-items: baseline; width: 50%; flex: 1; } span.save\_widget span.filename { height: 100%; line-height: 1em; margin-left: 16px; border: none; font-size: 146.5%; text-overflow: ellipsis; overflow: hidden; white-space: nowrap; border-radius: 2px; } span.save\_widget span.filename:hover { background-color: #e6e6e6; } \[dir="rtl"\] span.save\_widget.pull-left { float: right !important; float: right; } \[dir="rtl"\] span.save\_widget span.filename { margin-left: 0; margin-right: 16px; } span.checkpoint\_status, span.autosave\_status { font-size: small; white-space: nowrap; padding: 0 5px; } @media (max-width: 767px) { span.save\_widget { font-size: small; padding: 0 0 0 5px; } span.checkpoint\_status, span.autosave\_status { display: none; } } @media (min-width: 768px) and (max-width: 991px) { span.checkpoint\_status { display: none; } span.autosave\_status { font-size: x-small; } } .toolbar { padding: 0px; margin-left: -5px; margin-top: 2px; margin-bottom: 5px; box-sizing: border-box; -moz-box-sizing: border-box; -webkit-box-sizing: border-box; } .toolbar select, .toolbar label { width: auto; vertical-align: middle; margin-right: 2px; margin-bottom: 0px; display: inline; font-size: 92%; margin-left: 0.3em; margin-right: 0.3em; padding: 0px; padding-top: 3px; } .toolbar .btn { padding: 2px 8px; } .toolbar .btn-group { margin-top: 0px; margin-left: 5px; } .toolbar-btn-label { margin-left: 6px; } #maintoolbar { margin-bottom: -3px; margin-top: -8px; border: 0px; min-height: 27px; margin-left: 0px; padding-top: 11px; padding-bottom: 3px; } #maintoolbar .navbar-text { float: none; vertical-align: middle; text-align: right; margin-left: 5px; margin-right: 0px; margin-top: 0px; } .select-xs { height: 24px; } \[dir="rtl"\] .btn-group > .btn, .btn-group-vertical > .btn { float: right; } .pulse, .dropdown-menu > li > a.pulse, li.pulse > a.dropdown-toggle, li.pulse.open > a.dropdown-toggle { background-color: #F37626; color: white; } /\*\* \* Primary styles \* \* Author: Jupyter Development Team \*/ /\*\* WARNING IF YOU ARE EDITTING THIS FILE, if this is a .css file, It has a lot \* of chance of beeing generated from the ../less/\[samename\].less file, you can \* try to get back the less file by reverting somme commit in history \*\*/ /\* \* We'll try to get something pretty, so we \* have some strange css to have the scroll bar on \* the left with fix button on the top right of the tooltip \*/ @-moz-keyframes fadeOut { from { opacity: 1; } to { opacity: 0; } } @-webkit-keyframes fadeOut { from { opacity: 1; } to { opacity: 0; } } @-moz-keyframes fadeIn { from { opacity: 0; } to { opacity: 1; } } @-webkit-keyframes fadeIn { from { opacity: 0; } to { opacity: 1; } } /\*properties of tooltip after "expand"\*/ .bigtooltip { overflow: auto; height: 200px; -webkit-transition-property: height; -webkit-transition-duration: 500ms; -moz-transition-property: height; -moz-transition-duration: 500ms; transition-property: height; transition-duration: 500ms; } /\*properties of tooltip before "expand"\*/ .smalltooltip { -webkit-transition-property: height; -webkit-transition-duration: 500ms; -moz-transition-property: height; -moz-transition-duration: 500ms; transition-property: height; transition-duration: 500ms; text-overflow: ellipsis; overflow: hidden; height: 80px; } .tooltipbuttons { position: absolute; padding-right: 15px; top: 0px; right: 0px; } .tooltiptext { /\*avoid the button to overlap on some docstring\*/ padding-right: 30px; } .ipython\_tooltip { max-width: 700px; /\*fade-in animation when inserted\*/ -webkit-animation: fadeOut 400ms; -moz-animation: fadeOut 400ms; animation: fadeOut 400ms; -webkit-animation: fadeIn 400ms; -moz-animation: fadeIn 400ms; animation: fadeIn 400ms; vertical-align: middle; background-color: #f7f7f7; overflow: visible; border: #ababab 1px solid; outline: none; padding: 3px; margin: 0px; padding-left: 7px; font-family: monospace; min-height: 50px; -moz-box-shadow: 0px 6px 10px -1px #adadad; -webkit-box-shadow: 0px 6px 10px -1px #adadad; box-shadow: 0px 6px 10px -1px #adadad; border-radius: 2px; position: absolute; z-index: 1000; } .ipython\_tooltip a { float: right; } .ipython\_tooltip .tooltiptext pre { border: 0; border-radius: 0; font-size: 100%; background-color: #f7f7f7; } .pretooltiparrow { left: 0px; margin: 0px; top: -16px; width: 40px; height: 16px; overflow: hidden; position: absolute; } .pretooltiparrow:before { background-color: #f7f7f7; border: 1px #ababab solid; z-index: 11; content: ""; position: absolute; left: 15px; top: 10px; width: 25px; height: 25px; -webkit-transform: rotate(45deg); -moz-transform: rotate(45deg); -ms-transform: rotate(45deg); -o-transform: rotate(45deg); } ul.typeahead-list i { margin-left: -10px; width: 18px; } \[dir="rtl"\] ul.typeahead-list i { margin-left: 0; margin-right: -10px; } ul.typeahead-list { max-height: 80vh; overflow: auto; } ul.typeahead-list > li > a { /\*\* Firefox bug \*\*/ /\* see https://github.com/jupyter/notebook/issues/559 \*/ white-space: normal; } ul.typeahead-list > li > a.pull-right { float: left !important; float: left; } \[dir="rtl"\] .typeahead-list { text-align: right; } .cmd-palette .modal-body { padding: 7px; } .cmd-palette form { background: white; } .cmd-palette input { outline: none; } .no-shortcut { min-width: 20px; color: transparent; } \[dir="rtl"\] .no-shortcut.pull-right { float: left !important; float: left; } \[dir="rtl"\] .command-shortcut.pull-right { float: left !important; float: left; } .command-shortcut:before { content: "(command mode)"; padding-right: 3px; color: #777777; } .edit-shortcut:before { content: "(edit)"; padding-right: 3px; color: #777777; } \[dir="rtl"\] .edit-shortcut.pull-right { float: left !important; float: left; } #find-and-replace #replace-preview .match, #find-and-replace #replace-preview .insert { background-color: #BBDEFB; border-color: #90CAF9; border-style: solid; border-width: 1px; border-radius: 0px; } \[dir="ltr"\] #find-and-replace .input-group-btn + .form-control { border-left: none; } \[dir="rtl"\] #find-and-replace .input-group-btn + .form-control { border-right: none; } #find-and-replace #replace-preview .replace .match { background-color: #FFCDD2; border-color: #EF9A9A; border-radius: 0px; } #find-and-replace #replace-preview .replace .insert { background-color: #C8E6C9; border-color: #A5D6A7; border-radius: 0px; } #find-and-replace #replace-preview { max-height: 60vh; overflow: auto; } #find-and-replace #replace-preview pre { padding: 5px 10px; } .terminal-app { background: #EEE; } .terminal-app #header { background: #fff; -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2); box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2); } .terminal-app .terminal { width: 100%; float: left; font-family: monospace; color: white; background: black; padding: 0.4em; border-radius: 2px; -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.4); box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.4); } .terminal-app .terminal, .terminal-app .terminal dummy-screen { line-height: 1em; font-size: 14px; } .terminal-app .terminal .xterm-rows { padding: 10px; } .terminal-app .terminal-cursor { color: black; background: white; } .terminal-app #terminado-container { margin-top: 20px; } /\*# sourceMappingURL=style.min.css.map \*/ .highlight .hll { background-color: #ffffcc } .highlight { background: #f8f8f8; } .highlight .c { color: #408080; font-style: italic } /\* Comment \*/ .highlight .err { border: 1px solid #FF0000 } /\* Error \*/ .highlight .k { color: #008000; font-weight: bold } /\* Keyword \*/ .highlight .o { color: #666666 } /\* Operator \*/ .highlight .ch { color: #408080; font-style: italic } /\* Comment.Hashbang \*/ .highlight .cm { color: #408080; font-style: italic } /\* Comment.Multiline \*/ .highlight .cp { color: #BC7A00 } /\* Comment.Preproc \*/ .highlight .cpf { color: #408080; font-style: italic } /\* Comment.PreprocFile \*/ .highlight .c1 { color: #408080; font-style: italic } /\* Comment.Single \*/ .highlight .cs { color: #408080; font-style: italic } /\* Comment.Special \*/ .highlight .gd { color: #A00000 } /\* Generic.Deleted \*/ .highlight .ge { font-style: italic } /\* Generic.Emph \*/ .highlight .gr { color: #FF0000 } /\* Generic.Error \*/ .highlight .gh { color: #000080; font-weight: bold } /\* Generic.Heading \*/ .highlight .gi { color: #00A000 } /\* Generic.Inserted \*/ .highlight .go { color: #888888 } /\* Generic.Output \*/ .highlight .gp { color: #000080; font-weight: bold } /\* Generic.Prompt \*/ .highlight .gs { font-weight: bold } /\* Generic.Strong \*/ .highlight .gu { color: #800080; font-weight: bold } /\* Generic.Subheading \*/ .highlight .gt { color: #0044DD } /\* Generic.Traceback \*/ .highlight .kc { color: #008000; font-weight: bold } /\* Keyword.Constant \*/ .highlight .kd { color: #008000; font-weight: bold } /\* Keyword.Declaration \*/ .highlight .kn { color: #008000; font-weight: bold } /\* Keyword.Namespace \*/ .highlight .kp { color: #008000 } /\* Keyword.Pseudo \*/ .highlight .kr { color: #008000; font-weight: bold } /\* Keyword.Reserved \*/ .highlight .kt { color: #B00040 } /\* Keyword.Type \*/ .highlight .m { color: #666666 } /\* Literal.Number \*/ .highlight .s { color: #BA2121 } /\* Literal.String \*/ .highlight .na { color: #7D9029 } /\* Name.Attribute \*/ .highlight .nb { color: #008000 } /\* Name.Builtin \*/ .highlight .nc { color: #0000FF; font-weight: bold } /\* Name.Class \*/ .highlight .no { color: #880000 } /\* Name.Constant \*/ .highlight .nd { color: #AA22FF } /\* Name.Decorator \*/ .highlight .ni { color: #999999; font-weight: bold } /\* Name.Entity \*/ .highlight .ne { color: #D2413A; font-weight: bold } /\* Name.Exception \*/ .highlight .nf { color: #0000FF } /\* Name.Function \*/ .highlight .nl { color: #A0A000 } /\* Name.Label \*/ .highlight .nn { color: #0000FF; font-weight: bold } /\* Name.Namespace \*/ .highlight .nt { color: #008000; font-weight: bold } /\* Name.Tag \*/ .highlight .nv { color: #19177C } /\* Name.Variable \*/ .highlight .ow { color: #AA22FF; font-weight: bold } /\* Operator.Word \*/ .highlight .w { color: #bbbbbb } /\* Text.Whitespace \*/ .highlight .mb { color: #666666 } /\* Literal.Number.Bin \*/ .highlight .mf { color: #666666 } /\* Literal.Number.Float \*/ .highlight .mh { color: #666666 } /\* Literal.Number.Hex \*/ .highlight .mi { color: #666666 } /\* Literal.Number.Integer \*/ .highlight .mo { color: #666666 } /\* Literal.Number.Oct \*/ .highlight .sa { color: #BA2121 } /\* Literal.String.Affix \*/ .highlight .sb { color: #BA2121 } /\* Literal.String.Backtick \*/ .highlight .sc { color: #BA2121 } /\* Literal.String.Char \*/ .highlight .dl { color: #BA2121 } /\* Literal.String.Delimiter \*/ .highlight .sd { color: #BA2121; font-style: italic } /\* Literal.String.Doc \*/ .highlight .s2 { color: #BA2121 } /\* Literal.String.Double \*/ .highlight .se { color: #BB6622; font-weight: bold } /\* Literal.String.Escape \*/ .highlight .sh { color: #BA2121 } /\* Literal.String.Heredoc \*/ .highlight .si { color: #BB6688; font-weight: bold } /\* Literal.String.Interpol \*/ .highlight .sx { color: #008000 } /\* Literal.String.Other \*/ .highlight .sr { color: #BB6688 } /\* Literal.String.Regex \*/ .highlight .s1 { color: #BA2121 } /\* Literal.String.Single \*/ .highlight .ss { color: #19177C } /\* Literal.String.Symbol \*/ .highlight .bp { color: #008000 } /\* Name.Builtin.Pseudo \*/ .highlight .fm { color: #0000FF } /\* Name.Function.Magic \*/ .highlight .vc { color: #19177C } /\* Name.Variable.Class \*/ .highlight .vg { color: #19177C } /\* Name.Variable.Global \*/ .highlight .vi { color: #19177C } /\* Name.Variable.Instance \*/ .highlight .vm { color: #19177C } /\* Name.Variable.Magic \*/ .highlight .il { color: #666666 } /\* Literal.Number.Integer.Long \*/ /\* Overrides of notebook CSS for static HTML export \*/ body { overflow: visible; padding: 8px; } div#notebook { overflow: visible; border-top: none; }@media print { div.cell { display: block; page-break-inside: avoid; } div.output\_wrapper { display: block; page-break-inside: avoid; } div.output { display: block; page-break-inside: avoid; } }    MathJax.Hub.Config({ tex2jax: { inlineMath: \[ \['$','$'\], \["\\\\(","\\\\)"\] \], displayMath: \[ \['$$','$$'\], \["\\\\\[","\\\\\]"\] \], processEscapes: true, processEnvironments: true }, // Center justify equations in code and markdown cells. Elsewhere // we use CSS to left justify single line equations in code cells. displayAlign: 'center', "HTML-CSS": { styles: {'.MathJax\_Display': {"margin": 0}}, linebreaks: { automatic: true } } });

**ABOUT DATA**
==============

The data has been collected in İstanbul via an online form. It is aimed to examine the depression scores of married people and the influence of demographic factors.  
Demographic Questions and Beck Depression Inventory is used to collect data. Total Score of Scale must be calculated by the sum of items B1-B21. Codes reflecting the categories of demographic questions are as below.

  
Gender: 1-Female, 2-Male; 

Education: 1-Primary, 2-High School, 3-Bachelor, 4-Msc or PhD; 

Working Status: 1-Employed, 2-Unemployed; 

Marriage Style : 1-Arranged Marriage, 2-Flirt Marriage; 

Status of Having a Child: 1-Yes, 2-No 

**Beck's Depression Inventory[](https://www.kaggle.com/code/ayushmehar7/marital-depression-analysis#Beck's-Depression-Inventory)**
==================================================================================================================================

The Beck Depression Inventory (BDI), created by Aaron T. Beck, is a 21-question multiple-choice self-report inventory, one of the most widely used psychometric tests for measuring the severity of depression. Its development marked a shift among mental health professionals, who had until then, viewed depression from a psychodynamic perspective, instead of it being rooted in the patient's own thoughts.

Each of the 21 questions are 4 optioned questions having score from 0 to 3. Minimum score being 0 and maximum being 63.The degree of depression is directly proportional to the BDI score

Some of the questions are :

1.    
    *   0 I do not feel sad
    *   1 I feel sad
    *   2 I am sad all the time and I can't snap out of it.
    *   3 I am so sad and unhappy that I can't stand it.
2.    
    *   0 I am not particularly discouraged about the future.
    *   1 I feel discouraged about the future.
    *   2 I feel I have nothing to look forward to.
    *   3 I feel the future is hopeless and that things cannot improve.

For more details on the questions [visit here](https://www.ismanet.org/doctoryourspirit/pdfs/Beck-Depression-Inventory-BDI.pdf)

BDI Score[](https://www.kaggle.com/code/ayushmehar7/marital-depression-analysis#BDI-Score)
------------------------------------------------------------------------------------------

Based on the BDI score, the patient is categorised as follows :

*   Below 10 : These ups and downs are considered normal
*   11-16 : Mild mood disturbance
*   17-20 : Borderline clinical depression
*   21-30 : Moderate depression
*   31-40 : Severe depression
*   Over 40 : Extreme depression

Importing Required Packages[¶](#Importing-Required-Packages)
------------------------------------------------------------

In \[ \]:

import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns

Loading Data[¶](#Loading-Data)
------------------------------

In \[ \]:

df \= pd.read\_csv('Dataset 1.csv')
df.head()

Out\[ \]:

.dataframe tbody tr th:only-of-type { vertical-align: middle; } .dataframe tbody tr th { vertical-align: top; } .dataframe thead th { text-align: right; }

No

Gender

Education

Working Status

Marriage Style

Status of Having a Child

B1

B2

B3

B4

...

B12

B13

B14

B15

B16

B17

B18

B19

B20

B21

0

345

2

4

2

2

2

3

3

3

3

...

3

3

3

3

3

3

3

3

3

3

1

73

2

3

2

2

1

1

1

1

1

...

1

0

1

1

0

1

0

0

0

0

2

107

2

4

2

2

1

0

0

0

1

...

1

0

1

0

0

1

0

0

0

1

3

131

2

4

2

2

1

0

1

0

1

...

0

0

0

0

3

0

0

0

0

0

4

4

2

4

2

1

1

0

0

0

0

...

0

0

0

0

0

0

0

0

0

0

5 rows × 27 columns

.colab-df-container { display:flex; flex-wrap:wrap; gap: 12px; } .colab-df-convert { background-color: #E8F0FE; border: none; border-radius: 50%; cursor: pointer; display: none; fill: #1967D2; height: 32px; padding: 0 0 0 0; width: 32px; } .colab-df-convert:hover { background-color: #E2EBFA; box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15); fill: #174EA6; } \[theme=dark\] .colab-df-convert { background-color: #3B4455; fill: #D2E3FC; } \[theme=dark\] .colab-df-convert:hover { background-color: #434B5C; box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15); filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3)); fill: #FFFFFF; } const buttonEl = document.querySelector('#df-39fb6db0-0027-48d7-bb7a-ea33c57b6b02 button.colab-df-convert'); buttonEl.style.display = google.colab.kernel.accessAllowed ? 'block' : 'none'; async function convertToInteractive(key) { const element = document.querySelector('#df-39fb6db0-0027-48d7-bb7a-ea33c57b6b02'); const dataTable = await google.colab.kernel.invokeFunction('convertToInteractive', \[key\], {}); if (!dataTable) return; const docLinkHtml = 'Like what you see? Visit the ' + '<a target="\_blank" href=https://colab.research.google.com/notebooks/data\_table.ipynb>data table notebook</a>' + ' to learn more about interactive tables.'; element.innerHTML = ''; dataTable\['output\_type'\] = 'display\_data'; await google.colab.output.renderOutput(dataTable, element); const docLink = document.createElement('div'); docLink.innerHTML = docLinkHtml; element.appendChild(docLink); }

Data Manipulation[¶](#Data-Manipulation)
----------------------------------------

**_We'll need to make some small changes to make better visualizations, make working with the data easier, and make the data more meaningful._**

In \[ \]:

df\['Gender'\] \= df\['Gender'\].replace(1, 'Female')
df\['Gender'\] \= df\['Gender'\].replace(2, 'Male')

In \[ \]:

df.head()

Out\[ \]:

.dataframe tbody tr th:only-of-type { vertical-align: middle; } .dataframe tbody tr th { vertical-align: top; } .dataframe thead th { text-align: right; }

No

Gender

Education

Working Status

Marriage Style

Status of Having a Child

B1

B2

B3

B4

...

B12

B13

B14

B15

B16

B17

B18

B19

B20

B21

0

345

Male

4

2

2

2

3

3

3

3

...

3

3

3

3

3

3

3

3

3

3

1

73

Male

3

2

2

1

1

1

1

1

...

1

0

1

1

0

1

0

0

0

0

2

107

Male

4

2

2

1

0

0

0

1

...

1

0

1

0

0

1

0

0

0

1

3

131

Male

4

2

2

1

0

1

0

1

...

0

0

0

0

3

0

0

0

0

0

4

4

Male

4

2

1

1

0

0

0

0

...

0

0

0

0

0

0

0

0

0

0

5 rows × 27 columns

.colab-df-container { display:flex; flex-wrap:wrap; gap: 12px; } .colab-df-convert { background-color: #E8F0FE; border: none; border-radius: 50%; cursor: pointer; display: none; fill: #1967D2; height: 32px; padding: 0 0 0 0; width: 32px; } .colab-df-convert:hover { background-color: #E2EBFA; box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15); fill: #174EA6; } \[theme=dark\] .colab-df-convert { background-color: #3B4455; fill: #D2E3FC; } \[theme=dark\] .colab-df-convert:hover { background-color: #434B5C; box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15); filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3)); fill: #FFFFFF; } const buttonEl = document.querySelector('#df-443d270d-7dad-4d15-9c0a-08ddaee66c93 button.colab-df-convert'); buttonEl.style.display = google.colab.kernel.accessAllowed ? 'block' : 'none'; async function convertToInteractive(key) { const element = document.querySelector('#df-443d270d-7dad-4d15-9c0a-08ddaee66c93'); const dataTable = await google.colab.kernel.invokeFunction('convertToInteractive', \[key\], {}); if (!dataTable) return; const docLinkHtml = 'Like what you see? Visit the ' + '<a target="\_blank" href=https://colab.research.google.com/notebooks/data\_table.ipynb>data table notebook</a>' + ' to learn more about interactive tables.'; element.innerHTML = ''; dataTable\['output\_type'\] = 'display\_data'; await google.colab.output.renderOutput(dataTable, element); const docLink = document.createElement('div'); docLink.innerHTML = docLinkHtml; element.appendChild(docLink); }

In \[ \]:

df\['Education'\] \= df\['Education'\].replace(1, 'Primary')
df\['Education'\] \= df\['Education'\].replace(2, 'High School')
df\['Education'\] \= df\['Education'\].replace(3, 'Bachelor')
df\['Education'\] \= df\['Education'\].replace(4, 'Msc or PhD')

In \[ \]:

df.head()

Out\[ \]:

.dataframe tbody tr th:only-of-type { vertical-align: middle; } .dataframe tbody tr th { vertical-align: top; } .dataframe thead th { text-align: right; }

No

Gender

Education

Working Status

Marriage Style

Status of Having a Child

B1

B2

B3

B4

...

B12

B13

B14

B15

B16

B17

B18

B19

B20

B21

0

345

Male

Msc or PhD

2

2

2

3

3

3

3

...

3

3

3

3

3

3

3

3

3

3

1

73

Male

Bachelor

2

2

1

1

1

1

1

...

1

0

1

1

0

1

0

0

0

0

2

107

Male

Msc or PhD

2

2

1

0

0

0

1

...

1

0

1

0

0

1

0

0

0

1

3

131

Male

Msc or PhD

2

2

1

0

1

0

1

...

0

0

0

0

3

0

0

0

0

0

4

4

Male

Msc or PhD

2

1

1

0

0

0

0

...

0

0

0

0

0

0

0

0

0

0

5 rows × 27 columns

.colab-df-container { display:flex; flex-wrap:wrap; gap: 12px; } .colab-df-convert { background-color: #E8F0FE; border: none; border-radius: 50%; cursor: pointer; display: none; fill: #1967D2; height: 32px; padding: 0 0 0 0; width: 32px; } .colab-df-convert:hover { background-color: #E2EBFA; box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15); fill: #174EA6; } \[theme=dark\] .colab-df-convert { background-color: #3B4455; fill: #D2E3FC; } \[theme=dark\] .colab-df-convert:hover { background-color: #434B5C; box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15); filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3)); fill: #FFFFFF; } const buttonEl = document.querySelector('#df-4c9c1b2c-5960-4857-bd3b-7d72690598fe button.colab-df-convert'); buttonEl.style.display = google.colab.kernel.accessAllowed ? 'block' : 'none'; async function convertToInteractive(key) { const element = document.querySelector('#df-4c9c1b2c-5960-4857-bd3b-7d72690598fe'); const dataTable = await google.colab.kernel.invokeFunction('convertToInteractive', \[key\], {}); if (!dataTable) return; const docLinkHtml = 'Like what you see? Visit the ' + '<a target="\_blank" href=https://colab.research.google.com/notebooks/data\_table.ipynb>data table notebook</a>' + ' to learn more about interactive tables.'; element.innerHTML = ''; dataTable\['output\_type'\] = 'display\_data'; await google.colab.output.renderOutput(dataTable, element); const docLink = document.createElement('div'); docLink.innerHTML = docLinkHtml; element.appendChild(docLink); }

In \[ \]:

df\['Working Status'\] \= df\['Working Status'\].replace(1, 'Employed')
df\['Working Status'\] \= df\['Working Status'\].replace(2, 'Unemployed')

In \[ \]:

df.head()

Out\[ \]:

.dataframe tbody tr th:only-of-type { vertical-align: middle; } .dataframe tbody tr th { vertical-align: top; } .dataframe thead th { text-align: right; }

No

Gender

Education

Working Status

Marriage Style

Status of Having a Child

B1

B2

B3

B4

...

B12

B13

B14

B15

B16

B17

B18

B19

B20

B21

0

345

Male

Msc or PhD

Unemployed

2

2

3

3

3

3

...

3

3

3

3

3

3

3

3

3

3

1

73

Male

Bachelor

Unemployed

2

1

1

1

1

1

...

1

0

1

1

0

1

0

0

0

0

2

107

Male

Msc or PhD

Unemployed

2

1

0

0

0

1

...

1

0

1

0

0

1

0

0

0

1

3

131

Male

Msc or PhD

Unemployed

2

1

0

1

0

1

...

0

0

0

0

3

0

0

0

0

0

4

4

Male

Msc or PhD

Unemployed

1

1

0

0

0

0

...

0

0

0

0

0

0

0

0

0

0

5 rows × 27 columns

.colab-df-container { display:flex; flex-wrap:wrap; gap: 12px; } .colab-df-convert { background-color: #E8F0FE; border: none; border-radius: 50%; cursor: pointer; display: none; fill: #1967D2; height: 32px; padding: 0 0 0 0; width: 32px; } .colab-df-convert:hover { background-color: #E2EBFA; box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15); fill: #174EA6; } \[theme=dark\] .colab-df-convert { background-color: #3B4455; fill: #D2E3FC; } \[theme=dark\] .colab-df-convert:hover { background-color: #434B5C; box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15); filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3)); fill: #FFFFFF; } const buttonEl = document.querySelector('#df-746e3425-a3d5-48cf-9784-07551376dad0 button.colab-df-convert'); buttonEl.style.display = google.colab.kernel.accessAllowed ? 'block' : 'none'; async function convertToInteractive(key) { const element = document.querySelector('#df-746e3425-a3d5-48cf-9784-07551376dad0'); const dataTable = await google.colab.kernel.invokeFunction('convertToInteractive', \[key\], {}); if (!dataTable) return; const docLinkHtml = 'Like what you see? Visit the ' + '<a target="\_blank" href=https://colab.research.google.com/notebooks/data\_table.ipynb>data table notebook</a>' + ' to learn more about interactive tables.'; element.innerHTML = ''; dataTable\['output\_type'\] = 'display\_data'; await google.colab.output.renderOutput(dataTable, element); const docLink = document.createElement('div'); docLink.innerHTML = docLinkHtml; element.appendChild(docLink); }

In \[ \]:

df\['Marriage Style'\] \= df\['Marriage Style'\].replace(1, 'Arranged Marriage')
df\['Marriage Style'\] \= df\['Marriage Style'\].replace(2, 'Flirt Marriage')

In \[ \]:

df.head()

Out\[ \]:

.dataframe tbody tr th:only-of-type { vertical-align: middle; } .dataframe tbody tr th { vertical-align: top; } .dataframe thead th { text-align: right; }

No

Gender

Education

Working Status

Marriage Style

Status of Having a Child

B1

B2

B3

B4

...

B12

B13

B14

B15

B16

B17

B18

B19

B20

B21

0

345

Male

Msc or PhD

Unemployed

Flirt Marriage

2

3

3

3

3

...

3

3

3

3

3

3

3

3

3

3

1

73

Male

Bachelor

Unemployed

Flirt Marriage

1

1

1

1

1

...

1

0

1

1

0

1

0

0

0

0

2

107

Male

Msc or PhD

Unemployed

Flirt Marriage

1

0

0

0

1

...

1

0

1

0

0

1

0

0

0

1

3

131

Male

Msc or PhD

Unemployed

Flirt Marriage

1

0

1

0

1

...

0

0

0

0

3

0

0

0

0

0

4

4

Male

Msc or PhD

Unemployed

Arranged Marriage

1

0

0

0

0

...

0

0

0

0

0

0

0

0

0

0

5 rows × 27 columns

.colab-df-container { display:flex; flex-wrap:wrap; gap: 12px; } .colab-df-convert { background-color: #E8F0FE; border: none; border-radius: 50%; cursor: pointer; display: none; fill: #1967D2; height: 32px; padding: 0 0 0 0; width: 32px; } .colab-df-convert:hover { background-color: #E2EBFA; box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15); fill: #174EA6; } \[theme=dark\] .colab-df-convert { background-color: #3B4455; fill: #D2E3FC; } \[theme=dark\] .colab-df-convert:hover { background-color: #434B5C; box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15); filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3)); fill: #FFFFFF; } const buttonEl = document.querySelector('#df-b3957f24-375c-4a28-8087-6097a8fc1fd1 button.colab-df-convert'); buttonEl.style.display = google.colab.kernel.accessAllowed ? 'block' : 'none'; async function convertToInteractive(key) { const element = document.querySelector('#df-b3957f24-375c-4a28-8087-6097a8fc1fd1'); const dataTable = await google.colab.kernel.invokeFunction('convertToInteractive', \[key\], {}); if (!dataTable) return; const docLinkHtml = 'Like what you see? Visit the ' + '<a target="\_blank" href=https://colab.research.google.com/notebooks/data\_table.ipynb>data table notebook</a>' + ' to learn more about interactive tables.'; element.innerHTML = ''; dataTable\['output\_type'\] = 'display\_data'; await google.colab.output.renderOutput(dataTable, element); const docLink = document.createElement('div'); docLink.innerHTML = docLinkHtml; element.appendChild(docLink); }

In \[ \]:

df\['Status of Having a Child'\] \= df\['Status of Having a Child'\].replace(1, 'Yes')
df\['Status of Having a Child'\] \= df\['Status of Having a Child'\].replace(2, 'No')
df.head()

Out\[ \]:

.dataframe tbody tr th:only-of-type { vertical-align: middle; } .dataframe tbody tr th { vertical-align: top; } .dataframe thead th { text-align: right; }

No

Gender

Education

Working Status

Marriage Style

Status of Having a Child

B1

B2

B3

B4

...

B12

B13

B14

B15

B16

B17

B18

B19

B20

B21

0

345

Male

Msc or PhD

Unemployed

Flirt Marriage

No

3

3

3

3

...

3

3

3

3

3

3

3

3

3

3

1

73

Male

Bachelor

Unemployed

Flirt Marriage

Yes

1

1

1

1

...

1

0

1

1

0

1

0

0

0

0

2

107

Male

Msc or PhD

Unemployed

Flirt Marriage

Yes

0

0

0

1

...

1

0

1

0

0

1

0

0

0

1

3

131

Male

Msc or PhD

Unemployed

Flirt Marriage

Yes

0

1

0

1

...

0

0

0

0

3

0

0

0

0

0

4

4

Male

Msc or PhD

Unemployed

Arranged Marriage

Yes

0

0

0

0

...

0

0

0

0

0

0

0

0

0

0

5 rows × 27 columns

.colab-df-container { display:flex; flex-wrap:wrap; gap: 12px; } .colab-df-convert { background-color: #E8F0FE; border: none; border-radius: 50%; cursor: pointer; display: none; fill: #1967D2; height: 32px; padding: 0 0 0 0; width: 32px; } .colab-df-convert:hover { background-color: #E2EBFA; box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15); fill: #174EA6; } \[theme=dark\] .colab-df-convert { background-color: #3B4455; fill: #D2E3FC; } \[theme=dark\] .colab-df-convert:hover { background-color: #434B5C; box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15); filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3)); fill: #FFFFFF; } const buttonEl = document.querySelector('#df-7ab88c7f-a7bf-4c4d-9074-e4f34b69bf12 button.colab-df-convert'); buttonEl.style.display = google.colab.kernel.accessAllowed ? 'block' : 'none'; async function convertToInteractive(key) { const element = document.querySelector('#df-7ab88c7f-a7bf-4c4d-9074-e4f34b69bf12'); const dataTable = await google.colab.kernel.invokeFunction('convertToInteractive', \[key\], {}); if (!dataTable) return; const docLinkHtml = 'Like what you see? Visit the ' + '<a target="\_blank" href=https://colab.research.google.com/notebooks/data\_table.ipynb>data table notebook</a>' + ' to learn more about interactive tables.'; element.innerHTML = ''; dataTable\['output\_type'\] = 'display\_data'; await google.colab.output.renderOutput(dataTable, element); const docLink = document.createElement('div'); docLink.innerHTML = docLinkHtml; element.appendChild(docLink); }

Data Cleaning[¶](#Data-Cleaning)
--------------------------------

In \[ \]:

df.isnull().sum()

Out\[ \]:

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

**_We see that there are no null values ​​in the data._**

In \[ \]:

df.drop(columns\=\['No'\])

Out\[ \]:

.dataframe tbody tr th:only-of-type { vertical-align: middle; } .dataframe tbody tr th { vertical-align: top; } .dataframe thead th { text-align: right; }

Gender

Education

Working Status

Marriage Style

Status of Having a Child

B1

B2

B3

B4

B5

...

B12

B13

B14

B15

B16

B17

B18

B19

B20

B21

0

Male

Msc or PhD

Unemployed

Flirt Marriage

No

3

3

3

3

3

...

3

3

3

3

3

3

3

3

3

3

1

Male

Bachelor

Unemployed

Flirt Marriage

Yes

1

1

1

1

1

...

1

0

1

1

0

1

0

0

0

0

2

Male

Msc or PhD

Unemployed

Flirt Marriage

Yes

0

0

0

1

1

...

1

0

1

0

0

1

0

0

0

1

3

Male

Msc or PhD

Unemployed

Flirt Marriage

Yes

0

1

0

1

1

...

0

0

0

0

3

0

0

0

0

0

4

Male

Msc or PhD

Unemployed

Arranged Marriage

Yes

0

0

0

0

1

...

0

0

0

0

0

0

0

0

0

0

...

...

...

...

...

...

...

...

...

...

...

...

...

...

...

...

...

...

...

...

...

...

428

Female

High School

Employed

Arranged Marriage

Yes

0

0

0

0

0

...

0

0

0

0

0

0

0

0

0

0

429

Female

High School

Employed

Arranged Marriage

Yes

0

0

0

1

0

...

1

0

1

1

0

1

0

0

1

2

430

Female

Primary

Employed

Arranged Marriage

Yes

0

0

0

0

0

...

1

2

1

1

1

2

0

0

2

1

431

Female

Bachelor

Employed

Flirt Marriage

Yes

0

0

0

0

0

...

1

0

0

0

0

0

0

0

0

0

432

Female

Primary

Employed

Flirt Marriage

Yes

0

0

0

0

0

...

0

0

0

0

0

0

0

0

0

0

433 rows × 26 columns

.colab-df-container { display:flex; flex-wrap:wrap; gap: 12px; } .colab-df-convert { background-color: #E8F0FE; border: none; border-radius: 50%; cursor: pointer; display: none; fill: #1967D2; height: 32px; padding: 0 0 0 0; width: 32px; } .colab-df-convert:hover { background-color: #E2EBFA; box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15); fill: #174EA6; } \[theme=dark\] .colab-df-convert { background-color: #3B4455; fill: #D2E3FC; } \[theme=dark\] .colab-df-convert:hover { background-color: #434B5C; box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15); filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3)); fill: #FFFFFF; } const buttonEl = document.querySelector('#df-8c5bb15a-62e7-4ac0-94b2-a21f8dba40c0 button.colab-df-convert'); buttonEl.style.display = google.colab.kernel.accessAllowed ? 'block' : 'none'; async function convertToInteractive(key) { const element = document.querySelector('#df-8c5bb15a-62e7-4ac0-94b2-a21f8dba40c0'); const dataTable = await google.colab.kernel.invokeFunction('convertToInteractive', \[key\], {}); if (!dataTable) return; const docLinkHtml = 'Like what you see? Visit the ' + '<a target="\_blank" href=https://colab.research.google.com/notebooks/data\_table.ipynb>data table notebook</a>' + ' to learn more about interactive tables.'; element.innerHTML = ''; dataTable\['output\_type'\] = 'display\_data'; await google.colab.output.renderOutput(dataTable, element); const docLink = document.createElement('div'); docLink.innerHTML = docLinkHtml; element.appendChild(docLink); }

**_The numbering order is data we don't need. And we have to get rid of it._**

Basic Statistics[¶](#Basic-Statistics)
--------------------------------------

**_Let's see how many columns and rows there are._**

In \[ \]:

df.shape

Out\[ \]:

(433, 27)

**_Let's look at some basic statistics like mean, median, standart deviation and etc. about the data._**

In \[ \]:

df.describe()

Out\[ \]:

.dataframe tbody tr th:only-of-type { vertical-align: middle; } .dataframe tbody tr th { vertical-align: top; } .dataframe thead th { text-align: right; }

No

B1

B2

B3

B4

B5

B6

B7

B8

B9

...

B12

B13

B14

B15

B16

B17

B18

B19

B20

B21

count

433.000000

433.000000

433.000000

433.000000

433.000000

433.000000

433.000000

433.000000

433.000000

433.000000

...

433.000000

433.000000

433.000000

433.000000

433.000000

433.000000

433.000000

433.000000

433.000000

433.000000

mean

216.274827

0.397229

0.392610

0.450346

0.612009

0.678984

0.568129

0.503464

0.515012

0.163972

...

0.665127

0.579677

0.418014

0.528868

0.551963

0.732102

0.244804

0.224018

0.429561

0.475751

std

125.181852

0.747955

0.741083

0.834974

0.668085

0.620593

0.847436

0.642342

0.684065

0.474727

...

0.776452

0.759966

0.655001

0.790407

0.731375

0.721566

0.577452

0.625963

0.694058

0.742237

min

1.000000

0.000000

0.000000

0.000000

0.000000

0.000000

0.000000

0.000000

0.000000

0.000000

...

0.000000

0.000000

0.000000

0.000000

0.000000

0.000000

0.000000

0.000000

0.000000

0.000000

25%

108.000000

0.000000

0.000000

0.000000

0.000000

0.000000

0.000000

0.000000

0.000000

0.000000

...

0.000000

0.000000

0.000000

0.000000

0.000000

0.000000

0.000000

0.000000

0.000000

0.000000

50%

215.000000

0.000000

0.000000

0.000000

1.000000

1.000000

0.000000

0.000000

0.000000

0.000000

...

1.000000

0.000000

0.000000

0.000000

0.000000

1.000000

0.000000

0.000000

0.000000

0.000000

75%

324.000000

1.000000

1.000000

0.000000

1.000000

1.000000

1.000000

1.000000

1.000000

0.000000

...

1.000000

1.000000

1.000000

1.000000

1.000000

1.000000

0.000000

0.000000

1.000000

1.000000

max

435.000000

3.000000

3.000000

3.000000

3.000000

3.000000

3.000000

3.000000

3.000000

3.000000

...

3.000000

3.000000

3.000000

3.000000

3.000000

3.000000

3.000000

3.000000

3.000000

3.000000

8 rows × 22 columns

.colab-df-container { display:flex; flex-wrap:wrap; gap: 12px; } .colab-df-convert { background-color: #E8F0FE; border: none; border-radius: 50%; cursor: pointer; display: none; fill: #1967D2; height: 32px; padding: 0 0 0 0; width: 32px; } .colab-df-convert:hover { background-color: #E2EBFA; box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15); fill: #174EA6; } \[theme=dark\] .colab-df-convert { background-color: #3B4455; fill: #D2E3FC; } \[theme=dark\] .colab-df-convert:hover { background-color: #434B5C; box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15); filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3)); fill: #FFFFFF; } const buttonEl = document.querySelector('#df-a98724ef-cfbc-4732-9c57-18ca1ffbc36c button.colab-df-convert'); buttonEl.style.display = google.colab.kernel.accessAllowed ? 'block' : 'none'; async function convertToInteractive(key) { const element = document.querySelector('#df-a98724ef-cfbc-4732-9c57-18ca1ffbc36c'); const dataTable = await google.colab.kernel.invokeFunction('convertToInteractive', \[key\], {}); if (!dataTable) return; const docLinkHtml = 'Like what you see? Visit the ' + '<a target="\_blank" href=https://colab.research.google.com/notebooks/data\_table.ipynb>data table notebook</a>' + ' to learn more about interactive tables.'; element.innerHTML = ''; dataTable\['output\_type'\] = 'display\_data'; await google.colab.output.renderOutput(dataTable, element); const docLink = document.createElement('div'); docLink.innerHTML = docLinkHtml; element.appendChild(docLink); }

**_Let's have a quick idea about columns._**

In \[ \]:

df.info()

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

Calculating sum of all BDI columns[¶](#Calculating-sum-of-all-BDI-columns)
--------------------------------------------------------------------------

for finding BDI Score

**_As mentioned above, the BDI score is obtained from the sum of all Bn-type columns. Now let's create a new column and add a dataframe by collecting them._**

In \[ \]:

def bdi(df):
    finalBDIScore \= \[\]
    for i in df:
        finalBDIScore.append(i.sum())
    return np.array(finalBDIScore)

In \[ \]:

df\['BDI Score'\] \= bdi(df.drop(labels \= 'No\\tGender\\tEducation	Working Status	Marriage Style	Status of Having a Child'.split("\\t"),axis \= 1).values)

In \[ \]:

df.head()

Out\[ \]:

.dataframe tbody tr th:only-of-type { vertical-align: middle; } .dataframe tbody tr th { vertical-align: top; } .dataframe thead th { text-align: right; }

No

Gender

Education

Working Status

Marriage Style

Status of Having a Child

B1

B2

B3

B4

...

B13

B14

B15

B16

B17

B18

B19

B20

B21

BDI Score

0

345

Male

Msc or PhD

Unemployed

Flirt Marriage

No

3

3

3

3

...

3

3

3

3

3

3

3

3

3

61

1

73

Male

Bachelor

Unemployed

Flirt Marriage

Yes

1

1

1

1

...

0

1

1

0

1

0

0

0

0

12

2

107

Male

Msc or PhD

Unemployed

Flirt Marriage

Yes

0

0

0

1

...

0

1

0

0

1

0

0

0

1

8

3

131

Male

Msc or PhD

Unemployed

Flirt Marriage

Yes

0

1

0

1

...

0

0

0

3

0

0

0

0

0

6

4

4

Male

Msc or PhD

Unemployed

Arranged Marriage

Yes

0

0

0

0

...

0

0

0

0

0

0

0

0

0

1

5 rows × 28 columns

.colab-df-container { display:flex; flex-wrap:wrap; gap: 12px; } .colab-df-convert { background-color: #E8F0FE; border: none; border-radius: 50%; cursor: pointer; display: none; fill: #1967D2; height: 32px; padding: 0 0 0 0; width: 32px; } .colab-df-convert:hover { background-color: #E2EBFA; box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15); fill: #174EA6; } \[theme=dark\] .colab-df-convert { background-color: #3B4455; fill: #D2E3FC; } \[theme=dark\] .colab-df-convert:hover { background-color: #434B5C; box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15); filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3)); fill: #FFFFFF; } const buttonEl = document.querySelector('#df-c6c8e5d1-03d8-4e7d-990f-fd2722bee8cb button.colab-df-convert'); buttonEl.style.display = google.colab.kernel.accessAllowed ? 'block' : 'none'; async function convertToInteractive(key) { const element = document.querySelector('#df-c6c8e5d1-03d8-4e7d-990f-fd2722bee8cb'); const dataTable = await google.colab.kernel.invokeFunction('convertToInteractive', \[key\], {}); if (!dataTable) return; const docLinkHtml = 'Like what you see? Visit the ' + '<a target="\_blank" href=https://colab.research.google.com/notebooks/data\_table.ipynb>data table notebook</a>' + ' to learn more about interactive tables.'; element.innerHTML = ''; dataTable\['output\_type'\] = 'display\_data'; await google.colab.output.renderOutput(dataTable, element); const docLink = document.createElement('div'); docLink.innerHTML = docLinkHtml; element.appendChild(docLink); }

**_Columns of type Bn no longer have any meaning for us and we can delete them._**

In \[ \]:

droplist \= \[\]
for i in range(21):
  droplist.append(f"B{i+1}")
print(droplist)
df.drop(columns\=droplist)

\['B1', 'B2', 'B3', 'B4', 'B5', 'B6', 'B7', 'B8', 'B9', 'B10', 'B11', 'B12', 'B13', 'B14', 'B15', 'B16', 'B17', 'B18', 'B19', 'B20', 'B21'\]

Out\[ \]:

.dataframe tbody tr th:only-of-type { vertical-align: middle; } .dataframe tbody tr th { vertical-align: top; } .dataframe thead th { text-align: right; }

No

Gender

Education

Working Status

Marriage Style

Status of Having a Child

BDI Score

0

345

Male

Msc or PhD

Unemployed

Flirt Marriage

No

61

1

73

Male

Bachelor

Unemployed

Flirt Marriage

Yes

12

2

107

Male

Msc or PhD

Unemployed

Flirt Marriage

Yes

8

3

131

Male

Msc or PhD

Unemployed

Flirt Marriage

Yes

6

4

4

Male

Msc or PhD

Unemployed

Arranged Marriage

Yes

1

...

...

...

...

...

...

...

...

428

401

Female

High School

Employed

Arranged Marriage

Yes

0

429

244

Female

High School

Employed

Arranged Marriage

Yes

10

430

333

Female

Primary

Employed

Arranged Marriage

Yes

12

431

350

Female

Bachelor

Employed

Flirt Marriage

Yes

2

432

225

Female

Primary

Employed

Flirt Marriage

Yes

0

433 rows × 7 columns

.colab-df-container { display:flex; flex-wrap:wrap; gap: 12px; } .colab-df-convert { background-color: #E8F0FE; border: none; border-radius: 50%; cursor: pointer; display: none; fill: #1967D2; height: 32px; padding: 0 0 0 0; width: 32px; } .colab-df-convert:hover { background-color: #E2EBFA; box-shadow: 0px 1px 2px rgba(60, 64, 67, 0.3), 0px 1px 3px 1px rgba(60, 64, 67, 0.15); fill: #174EA6; } \[theme=dark\] .colab-df-convert { background-color: #3B4455; fill: #D2E3FC; } \[theme=dark\] .colab-df-convert:hover { background-color: #434B5C; box-shadow: 0px 1px 3px 1px rgba(0, 0, 0, 0.15); filter: drop-shadow(0px 1px 2px rgba(0, 0, 0, 0.3)); fill: #FFFFFF; } const buttonEl = document.querySelector('#df-b14a5163-4b6d-41a9-90c3-5866604ddf9c button.colab-df-convert'); buttonEl.style.display = google.colab.kernel.accessAllowed ? 'block' : 'none'; async function convertToInteractive(key) { const element = document.querySelector('#df-b14a5163-4b6d-41a9-90c3-5866604ddf9c'); const dataTable = await google.colab.kernel.invokeFunction('convertToInteractive', \[key\], {}); if (!dataTable) return; const docLinkHtml = 'Like what you see? Visit the ' + '<a target="\_blank" href=https://colab.research.google.com/notebooks/data\_table.ipynb>data table notebook</a>' + ' to learn more about interactive tables.'; element.innerHTML = ''; dataTable\['output\_type'\] = 'display\_data'; await google.colab.output.renderOutput(dataTable, element); const docLink = document.createElement('div'); docLink.innerHTML = docLinkHtml; element.appendChild(docLink); }

Explarotary Data Analysis[¶](#Explarotary-Data-Analysis)
--------------------------------------------------------

In \[ \]:

sns.catplot(x \= 'Gender', y \= 'BDI Score',data \= df, 
            palette\="Blues").set(title\="BDI Score by Genders");

![](data:image/png;base64,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nTuXMWPG3NZ51q5dy8qVK0lNTWXGjBmkpaVF3G/r1q1s3ryZhx56CACLxcLGjRs7ND30FVIPVwghokSaFIQQIkokcIUQIkokcIUQIkokcIUQIkokcIUQIkokcIW4iZ07d7J8+fJY34boBWQcrohbZWVl/PKXv+TLL78kKSmJwYMHs3DhQh577DEURYn17QnRibzhirj09ttvs3HjRr73ve9x8OBBDh06xPr16zl+/Hi4elVP0L5msRASuCLuOBwOXn31VdatW8fcuXOxWq0oisKoUaP48Y9/jNlsxufzsWXLFmbPns20adN44YUX8Hg8ABw5coSZM2fy9ttvM3XqVAoLC9mxY0f4/DabjRUrVjBx4kS++c1vUlVV1eH6FRUVfOc732HKlCkUFxfz+9//PvzZmjVrWLduHU888QTjx4/nyJEj0fmmiLgggSvizokTJ/D5fMyZM6fLfbZu3UplZSW7d+9m//79NDQ08MYbb4Q/b2xsxOFwcODAATZu3MiGDRuw2+0AbNiwgYSEBA4ePMimTZs6hLHL5eK73/0uCxYs4NChQ/zkJz9h/fr1nD17NrzP3r17WbFiBcePH2fSpEnd8B0Q8UoCV8Qdm81Geno6RuO1LohHH32UyZMnc99993H06FHee+89SktLSUtLw2q18uSTT1JWVhbe32g08tRTT2EymZg1axbJyclUVlaiaRr79+/n6aefJjk5meHDh7No0aLwcR9//DG5ubksWbIEo9HIqFGjKC4uZt++feF95syZw6RJkzAYDB0qbQkhnWYi7qSlpWGz2QgEAuHQbSuePXPmTBobG3G73SxevDh8jK7rBIPBDudoH9hJSUm4XC6am5sJBALk5OSEPxs0aFD435cuXaK8vJzJkyeHt2maxsMPPxz+uv2xQrQngSvizoQJEzCbzXzwwQcUFxd3+jw9PZ3ExETKyspuu6B6RkYGRqOR2tpahg4dCoTKCbbJycmhoKAgXLRdiNshTQoi7qSkpPDUU0+xfv169u3bh9PpJBgMcvr0adxuNwaDgaVLl7Jp0yaampoAqK+v589//vNNz62qKg8++CCvv/46brebs2fPsmvXrvDns2fP5vz58+zevRu/34/f76e8vJyKiopue17Re8gbrohLTzzxBNnZ2bz11lusXr2apKQk8vLyeP7555kwYQLjx4/njTfe4JFHHsFms5Gdnc3y5cuZMWPGTc/9wgsvsHbtWqZPn86QIUNYvHhxeLSB1Wrl5z//OS+99BIvvfQSuq4zYsQI1q5d292PLHoBqYcrhBBRIk0KQggRJRK4QggRJRK4QggRJRK4QggRJRK4QggRJRK4QggRJRK4QggRJRK4QggRJRK4QggRJf8PGP88aVh9w/UAAAAASUVORK5CYII=
)

**_We see that women have a higher average rate of marital depression than men._**

In \[ \]:

sns.set\_theme(style\="whitegrid")
sns.barplot(x\="Working Status", y\="BDI Score", data\=df, 
            palette\="Blues").set(title\="Working Status and BDI Score");

![](data:image/png;base64,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
)

**_It is clear that unemployed people experience less marital depression than employed people._**

In \[ \]:

plt.figure(figsize\=(10,6))
bxp \= sns.boxplot(y \= 'Education', x \= 'BDI Score',data \= df, 
                  palette\="Blues").set(title\="Education Level and BDI Score");

![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAApgAAAGJCAYAAAAuU0NqAAAABHNCSVQICAgIfAhkiAAAAAlwSFlzAAALEgAACxIB0t1+/AAAADh0RVh0U29mdHdhcmUAbWF0cGxvdGxpYiB2ZXJzaW9uMy4yLjIsIGh0dHA6Ly9tYXRwbG90bGliLm9yZy+WH4yJAAAgAElEQVR4nO3deVhVBeL/8Q87CbiAoriWCy41mOKS2jeNSkRAEKdRK8ul1HKjtMmsX6XmVtbg1tCmzphT+U2CUUDLXBoXUNE0yxJMXFJBURQ31vv7w8f7jXFDPJdzkffreXyee/bPOZzb8+mcc+91sFgsFgEAAAAGcTQ7AAAAAO4sFEwAAAAYioIJAAAAQ1EwAQAAYCgKJgAAAAxFwQQAAIChKJgA7N6RI0fUsmVLFRUVVeh2//3vf2vo0KEVuk1badmypQ4ePGjz7cTFxWngwIE23w4A++ZsdgAAVVNQUJBOnjwpJycn67i+ffvqjTfeMCXPkSNH9Mgjj+inn36Ss/Pl/zT26dNHffr0MXxbqampevnll/X9998bvm57duUYV6tWTZJ01113qWfPnnrttdfk4uIiqfR54eTkpObNmysiIkL9+/eXo+PlayITJ05U3bp19eKLL15zO7GxsVq2bJlOnz4tLy8vtW/fXjExMRWzkwAkUTABmCg2NlZdu3Y1OwYq2LZt2+Ts7KycnBwNGzZMS5cu1eDBg63Tr5wXeXl52rp1q6ZNm6bdu3drxowZN133119/rYSEBC1evFiNGzfWiRMntHbtWkPzFxUVWf8nBMC1cYscgN0pLi7WrFmz1LlzZz3yyCPasGFDqelBQUHavHmzdXjevHmaMGGCdXj79u0aMGCAOnTooO7duysuLk6StH79ekVGRqp9+/bq3r275s2bZ13mqaeekiR17NhR7dq1086dO6+63btjxw7169dPgYGB6tevn3bs2GGdNmjQIMXExGjAgAFq166dhg4dqlOnTt3yvmdlZWnMmDF64IEHFBQUpH/+85/W8QEBAcrNzbXO+/PPP6tz584qLCyUJH311VcKCQlRx44dNWzYMP3+++9l2uby5csVEhKidu3a6ZFHHtEXX3xhnZaamqqHHnpICxcuVJcuXfTggw9q+fLl1umnT5/WyJEj1b59e/35z3/WoUOHyryvPj4+6tq1q/bv33/N6V5eXnrkkUcUExOjr7/+Wvv27bvpOn/88Uc9+OCDaty4sSSpTp066t+/v3V6bm6uXn31VT344IPq2LGjXnjhBeu0ZcuW6bHHHlOnTp00cuRIZWVlWae1bNlSS5cuVc+ePdWzZ09J0rp16xQREaEOHTpowIAB+uWXX8q878CdjoIJwO4sW7ZM69atU3x8vJYvX65Vq1aVednff/9dzz33nJ566ilt2bJF8fHxat26taTLt2RnzZql7du368MPP9Tnn3+uNWvWSJI+++wzSZevru3cuVPt2rUrtd7c3FyNGDFCgwYNUmpqqoYMGaIRI0bo9OnT1nlWrlypGTNmaMuWLSosLNTChQtvab9LSkr0/PPPq2XLlvr+++/1j3/8Q//4xz/0n//8R3Xr1tX999+vb775xjr/ihUrFBwcLBcXF61Zs0Yffvih5s+fry1btigwMFDjx48v03Z9fHz04YcfaseOHZoxY4ZmzJihn376yTr95MmTysvL0/fff69p06ZpypQpOnPmjCRpypQpcnNz08aNGzV9+vRS5fNmsrKytHHjRrVt2/aG8wUEBKhevXravn37TdfZtm1bJSQk6JNPPtGPP/6o4uLiUtP/+te/6uLFi0pMTNTmzZutV063bNmi9957TzExMdq4caMaNGigl156qdSya9as0bJly5SUlKSff/5ZkyZN0pQpU5Samqr+/fvrhRdeUEFBQZn3H7iTUTABmGbUqFHq0KGD9d+yZcskScnJyXrmmWfk5+enmjVrasSIEWVe58qVK9W1a1eFhYXJxcVFtWrVshbMzp07q2XLlnJ0dFSrVq0UGhqqrVu3lmm969evV5MmTRQZGSlnZ2eFhYWpadOmWrdunXWeqKgo3XPPPXJ3d1evXr20d+/eWzgal6++nTp1SqNHj5arq6saNWqkv/zlL0pKSpIkhYeHa+XKlZIki8WipKQkhYeHS5K++OILDR8+XM2aNZOzs7NGjhypvXv3lukqZo8ePdS4cWM5ODioU6dO6tatW6ky5+zsrFGjRsnFxUXdu3dXtWrVdODAARUXF+ubb77R2LFjVa1aNfn7+6tv37433d4DDzygDh066KGHHlK1atXUq1evmy7j6+trLbU3EhERoddff10bN27UoEGD1LVrV3300UeSpOzsbH3//feaPHmyatSoIRcXF3Xq1EnS5bLer18/3Xvv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
)

**_Increasing people's level of education leads to psychologically healthier family life. In short, education brings peace._**

In \[ \]:

sns.barplot(x\="BDI Score", y\="Status of Having a Child", data\=df, 
            palette\="Blues").set(title\="Status of having a child and BDI Score");

![](data:image/png;base64,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GwMGDMDIkSNhbGwMPz8/XecjIiI90qokZs+erbk9duxYtGnTBjk5OejcubPOghERkf5p/RHY17m5uVV2DiIiMkD8Mh0REUliSRARkSSWBBERSWJJEBGRJK1OXHt5eUEmkxWbbmpqivr168PX1xdDhw6FsXGFzoMTEZGB0uqvelBQEI4cOYKgoCDY2toiLS0N//73v9G9e3fUqFEDu3btQlpaGr7++mtd5yUiondIq5I4ePAgdu7cifr162umdenSBWPGjMGxY8fg6emJ0aNHsySIiKoYrc5JPHjwAFZWVkWmWVhYIDMzEwDw6aef4unTp5WfjoiI9EqrPQlvb29MnDgREydORP369ZGRkYGtW7fC29sbABAfH4/GjRvrNCgREb17WpXEwoULsWHDBsydOxeZmZmwsbFBjx49MHnyZADARx99hK1bt+o0KBERvXtalYSZmRlCQ0MRGhpa4nwbG5tKDUVERIZB68+s3rlzBzdv3iw2PPjAgQMrPRQRERkGrUoiLCwMmzZtgoODA8zNzTXTZTIZS4KIqArTqiT+/ve/48CBA3BwcNB1HiIiMiBafQTW3NwcdnZ2us5CREQGRquSCAkJwTfffIPMzEyo1eoi/4iIqOrS6nDTjBkzAAAHDhzQTBNCQCaT4caNG7pJRkREeqdVSURGRuo6BxERGSCtSqJRo0a6zlGpfFp9BDMzM33HIKL3kEqthpGcV1F4RbIk5syZg0WLFgEAvvrqqxKHCgeAFStW6CbZB+7y5ctwdXXVd4xKwW0xPFVlO4DK3xYWRFGSJfH6WExNmjR5J2GIiMiwSJbEl19+qbkdHBz8TsIQEZFh0Wq/qk+fPti+fTvS09N1nYeIiAyIViURHByMa9euoUePHhgxYgT27duH7OxsXWcjIiI906okPv/8c6xbtw7nz5/HgAED8P3336Nr166YMGGCrvMREZEeaT0KLABYW1vD398f1apVQ0FBAX788Udd5SIiIgOgVUkIIXDp0iUcPXoUZ86cQcOGDeHv74/ly5frOh8REemRViXRuXNnWFpaomfPnti7dy+aNm2q61xERGQAtCqJzZs3w9nZWddZiIjIwGhVEq8K4vnz58jKyioy76OPPqr8VEREZBC0Konbt28jNDQUN2/ehEwm04wAC4CjwBIRVWFafQR2wYIF8PT0RExMDKytrREbG4vBgwdj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
)

**_Individuals in families with children experience less marital depression on average. We will examine this topic separately for genders in the future_**

In \[ \]:

sns.barplot(x \= "Marriage Style", y \= "BDI Score", data \= df, 
            palette \= "Blues").set(title\="Marriage Style and BDI Score");

![](data:image/png;base64,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
)

**_Marital style may not appear to affect marital depression at first glance, but when we examine it, we will see both negative and positive effects of this topic depending on gender._**

Explarotary Data Analysis by Gender[¶](#Explarotary-Data-Analysis-by-Gender)
----------------------------------------------------------------------------

In \[ \]:

male \= df.where(df\['Gender'\] \== "Male").groupby(by \= "Working Status").mean()
male \= male\['BDI Score'\]
male \= np.array(male)
plt.bar(\['Employed', 'Unemployed'\], male,  color\=("Blue", "Red"))
plt.title("BDI Score and Working Status for Males")
plt.show()

![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAXQAAAELCAYAAADJF31HAAAABHNCSVQICAgIfAhkiAAAAAlwSFlzAAALEgAACxIB0t1+/AAAADh0RVh0U29mdHdhcmUAbWF0cGxvdGxpYiB2ZXJzaW9uMy4yLjIsIGh0dHA6Ly9tYXRwbG90bGliLm9yZy+WH4yJAAAgAElEQVR4nO3de1xUdf4/8NfAwAAScUmUEDTdBi+EDFdvaZKJ+OCSuruYiq5oapsppV/lUWYKhtG6iiu2yENzq3WzTMJUWsx7apJcCidN46asFxSEAjQY4Pz+8MH5Ocp9BtGPr+fj4ePhnDPnc95n5sPrfOYzZ2YUkiRJICKih55JVxdARETGwUAnIhIEA52ISBAMdCIiQTDQiYgEwUAnIhIEA526VEpKCl566aUu2XdERAR27NjR5LrZs2fjyy+/vM8VPVgKCgoQFhYGjUaDjz/+uKvLkbX0vD3qGOgGCAgIgIeHBzQaDXx9fTFnzhxcuXJFXh8dHQ13d3doNBpoNBoEBwfj73//OyorK+X7tBZo+/fvR1hYGLy8vODv74/p06ejuLi4U4/rQTFr1iwkJyfLt0tKSuDm5tbksuvXrxt135s3b8aECROM2majpKQkBAQEQKPRYOTIkYiKipLXtTesNmzYgMWLF3dGmdi8eTP8/f2Rk5OD6dOnG9zehg0b4Obmho8++khv+UcffQQ3Nzds2LDB4H086hjoBkpKSkJOTg6OHTsGBwcHxMbG6q2fNWsWcnJycPLkScTFxeGHH37ASy+9hJs3b7ba9oULF7B06VJER0cjKysLBw4cwNSpU2Fqamq0+iVJQkNDg9HaMyYfHx9kZmbKt0+dOoW+ffves6xPnz7o3r17m9vtymP+8ssvsWvXLvzrX/9CTk4Odu7ciaFDh3ZJLa25fPkynn766Q5tW1dX1+TyPn36YNeuXXrLUlNT0adPnw7th/Qx0I1EpVJh3LhxyM/Pb3a9h4cH/vnPf6KiogIpKSmttnn27Fn06tULQ4cOhUKhgLW1NQIDA/Hkk08CAOrr65GUlIQxY8ZAo9Fg4sSJ8iuE7OxsTJo0Cd7e3pg0aRKys7PldiMiIrBu3TpMnjwZgwcPRnFxMfLz8zFz5kz4+fkhMDAQaWlpzda1c+dOBAUFQaPR4Pnnn8f27dvldRkZGRg5ciQ+/PBDDB06FCNGjMDOnTvl9eXl5Zg3bx68vLzwxz/+ERcvXmx2P76+vsjOzpbDNzMzEzNmzIBWq9Vb5uPj06FjvtO1a9cQEhKCzZs3y/dvHCk3voqKj4+Hr68vAgICcOTIEXnb4uJiTJ06FRqNBn/5y1+wcuXKZkfNp0+fxogRI+Dq6goA6N69O8LDwwEA69atQ2ZmJmJiYqDRaBATEwMAWLVqFUaNGgUvLy9MnDhRPqEdPXoUmzZtwtdffw2NRoPQ0FAAt185njhxQt7nnaP4mpoaLF68GP7+/vDx8cGkSZNQWlp6T53Tp09HRkaGXEthYSEqKyuxZMkSDBkyBKNHj8YHH3wgPw8pKSmYPHky4uLi4O/v3+xo+5lnnsGtW7fwyy+/AAB++eUX1NTU4JlnnpHv8+uvv2Lu3LkYMmQIfH19MXfuXFy9erXJ9gDgiy++QFBQEHx9fTFr1ixcunQJwO0Td1xcHIYOHQovLy+EhITg/PnzzbYjAga6kdy6dQtpaWkYPHhwi/eztrbGsGHD9EaZzRk0aBAKCgoQFxeHkydPorq6Wm/91q1bsXfvXiQnJyM7OxtxcXGwsLBARUUF5s6di4iICGRkZGDmzJmYO3cuysvL5W137dqF2NhYZGdnw97eHpGRkQgODsaJEyewbt06rFy5Enl5eU3W5eDggE2bNiE7OxurV6/G6tWr8dNPP8nrS0tLUVlZiaNHj+Ldd99FTEwMfv31VwBATEwMVCoVjh07hri4OL2wv5uHhwdqa2vx888/A7gd3sOHD4erq6veMl9f33Yfc+NJEbgdyBEREZg2bRpmz57dZC25ubl46qmncPLkScyePRtvvfUWGr81Y/HixfDw8EBGRgbmz59/zwj0ToMHD8auXbuwefNmnD59GvX19fK6119/HT4+Pli+fDlycnKwfPlyALdDMDU1Fd9//z2Cg4OxcOFC1NTUYOTIkZg7dy6CgoKQk5ODr776qtn9Nvryyy9RVVWFw4cPIyMjAytXroSFhcU99/v444/1annqqacQGxuLyspK7N+/H5988gl27dql9/zl5ubCxcUFx48fxyuvvNJsDWFhYUhNTZXrCQsL01vf0NCAiRMn4tChQzh06BBUKpV8crvb/v37sWnTJiQmJuK7776Dt7c3Fi1aBAA4duwYMjMzkZ6ejqysLCQkJMDW1rbVx+hhxkA30KuvvgofHx/4+Pjg+PHjmDVrVqvbODo6ygHXEhcXF3zyyScoKSlBVFQUhgwZgujoaDnYd+zYgYULF6Jv375QKBTo378/7OzscPjwYfTu3RsvvvgilEolgoOD0bdvXxw6dEhue8KECXj66aehVCrx7bffwtnZGZMmTYJSqcTAgQMRGBiI//73v03W9dxzz8HV1RUKhQJ+fn4YPny43glKqVTi1VdfhZmZGUaNGgUrKysUFhaivr4e+/btw4IFC2BlZQW1Wt3iPLW5uTkGDx6MU6dOoaKiApWVlXBxcYGPj4+8LC8vD76+vu0+ZjMzMwBAXl4eZsyYgddee00eKTflySefxJ///GeYmppiwoQJuH79OkpLS3H58mWcPn0aCxYsgLm5OXx8fBAQENBsO2FhYVi2bBmOHTuGiIgIDBs2TO89gea2sbOzg1KpRGRkJGpra1FYWNjiNs1RKpWoqKjAhQsXYGpqCnd3d1hbW7e6XX19PdLS0rBo0SJYW1ujV69emDlzpt5JxNHREREREVAqlU2eJBqFhoZi79690Ol0SEtLk19ZNLKzs0NgYCAsLS1hbW2NV155BadOnWqyre3bt2POnDno168flEol5s2bh7Nnz+LSpUtQKpWorq5GQUEBJElCv3794Ojo2MZH6uGk7OoCHnYbN27EsGHDUF9fjwMHDiAiIgJ79+5tcU63pKQEjz/+eJva9/T0xPr16wHcHgG9/vrrSEpKwqJFi3D16lX5pfudrl27pjcCBW4HUklJiXzbyclJ/v+lS5eQm5srT10At/+A7/5Da3TkyBFs3LgRRUVFaGhowO+//w61Wi2vt7W1hVL5/7uWpaUlbt68iRs3bqCurk5v33fXebfGeXRnZ2d4eXkBALy9vZGSkgJnZ2c4OTnB2dkZe/fubdcxN9q9ezdcXV0RGBjYYh1PPPGE3vEAwM2bN1FeXo7HH39cXta4nzvfHL9baGgoQkNDodPpsH//fvzf//0fBgwYgGeffbbJ+2/ZsgVffPEFrl27BoVCgaqqKr1XHu0RFhaGq1ev4o033sBvv/2G0NBQvP766/IJrjnl5eXQ6XR6j/Hdj2/Pnj3bVMOTTz4JV1dXrF27Fr17977nebl16xZWr16Nb7/9Vh74VFdXo76+/p73jy5fvoy4uDjEx8fLyyRJQklJCYYOHYqpU6ciJiYGly5dwtixY7F06dI2ncAeVhyhG4mpqSnGjh0LExMTZGVlNXu/6upqfPfdd3rh2VYeHh4YO3asPP/Ys2fPJuegHR0dcfnyZb1lV65cQY8ePeTbCoVC/r+TkxN8fX2RmZkp/8vJycHKlSvvabu2thYLFixAZGQkjh8/jszMTIwcORJt+dJOe3t7KJVKvbBrKfgA6NXV+Jh5eXkhOztbb1l7j7nR/PnzYWdnh0WLFulNf7RV9+7d8euvv+LWrVttPqZGZmZmCAoKglqtlp/Tu2VmZmLz5s1ISEjAqVOnkJmZiccee0x+vJs6JktLS7167rwCyMzMDPPnz0daWhq2b9+Ow4cPy9MfLbGzs4OZmZneY9yWx7c5L774IrZu3YoXX3zxnnUffvghCgsL8fnnnyM7Oxvbtm0DgCb7mJOTE1auXKnXd3Nzc+WT//Tp05GSkoK0tDQUFRXJ75GIioFuJJIkYf/+/fjtt9/Qr1+/e9bX1tZCq9Xi1VdfhY2NDSZOnNhqm5mZmfj8889RVlYGAMjPz8fBgwflefo//elPWL9+PYqKiiBJEn7++WeUl5dj1KhRKCoqwu7du1FXV4e0tDTk5eXhueeea3I/zz33HIqKipCamgqdTgedTofc3Nwm3+Ctra1FbW2tHM5HjhzB8ePH2/QYmZqa4oUXXkBiYiJu3bqFvLy8Vq/19vT0RGVlJb766it4e3sDAB5//HHY29vjq6++gq+vLwC0+5gbmZmZYf369bh16xaWLFnS7qtfnJ2d4e7ujg0bNqC2thY5OTl60zx3S0lJweHDh1FVVYWGhgYcOXIEeXl58PDwAHD7lcCdb9hWV1fD1NQU9vb2qKurQ2JiIqqqquT1Dg4OuHTpkl7d/fv3R1paGnQ6HU6fPo309HR53cmTJ3Hu3DnU19fD2toaSqUSJiatx4CpqSnGjRuHdevWoaqqCpcuXcLWrVubfRXXmvHjx+PDDz9EUFDQPeuqq6uhUqlgY2ODiooKJCYmNtvO5MmTkZycLJ8QKysr8fXXXwO4/Yr2xx9/hE6ng6WlJczNzdt0rA8zsY/uPpg3bx40Gg28vLyQkJCA9957T+9Sry1btkCj0cDf3x9Lly7FoEGDsH37dlhZWbXato2NDQ4ePIiQkBBoNBq8/PLLGDNmjPzG3cyZMxEUFITIyEh4eXnhrbfeQk1NDezs7JCUlIStW7fC398fmzdvRlJSEuzt7Zvcj7W1NbZs2YK0tDQ8++yzGDFiBNasWYPa2tom77ts2TJERUXB19cXe/bsaXHO+G7Lly/HzZs3MXz4cERHR7d6YrOyssKgQYOg0+n0pnW8vb1RVlYmj9Dbe8x3Mjc3R2JiIsrKyvDmm2+2O9TXrFmDH374Af7+/khISMD48eNhbm7e5H2tra2RlJSE0aNHw8fHB2vWrMGKFSvk45g+fTrS09Ph6+uLVatWYcSIEXj22WcRGBiIgIAAqFQqvSmKcePGAQD8/f3l9yOioqJw8eJF+Pn5YcOGDQgJCZHvX1paigULFsDb2xvjx4+Hn5/fPW9KNuftt9+GpaUlxowZgylTpiA4OBiTJk1q12PVyMLCAsOGDWtyrn3GjBmoqanBkCFDEB4e3uxUFAC88MILmD17Nt544w14eXkhODgYR48eBXD7xLBs2TL4+flh9OjRsLW1bdN7XA8zBX/ggsi4oqKi0LdvXyxYsKCrS6FHDEfoRAbKzc3FxYsX0dDQgKNHj+LAgQMYM2ZMV5dFjyBe5UJkoNLSUrz22muoqKhAz549sWLFCgwcOLCry6JHEKdciIgEwSkXIiJBdNmUS0NDA6qrq2FmZtau61eJiB5lkiRBp9OhW7du91yG2WWBXl1dLfwX5RARdRa1Wo3HHntMb1mXBXrjR43VanWz1+xS22m1Wri7u3d1GUTNYh81jtraWpw/f77Jr2voskBvnGYxNzeHSqXqqjKEwseRHnTso8bT1FQ13xQlIhIEA52ISBAMdCIiQTDQiYgEwUAnIhIEA52ISBAMdCIiQTy0gf77711dwYOl8dd8iH2DHl0P7dfnWlgA/AoYagq/P5QeVQ/tCJ2IiPQx0ImIBMFAJyISBAOdiEgQDHQiIkEw0ImIBMFAJyISBAOdiEgQDHQiIkEw0ImIBMFAJyISBAOdiEgQDHQiIkEw0ImIBNGmQI+Pj0dAQADc3Nxw/vx5AEB5eTlefvllBAYGIiQkBPPnz8eNGzc6tVgiImpemwL9+eefx7Zt2+Ds7CwvUygUmD17NtLT07F79264uLhgzZo1nVYoERG1rE2B7uPjAycnJ71ltra28Pf3l297enri8uXLxq2OiIjazChz6A0NDfj0008REBBgjOaIiKgDjPITdLGxsbCyssK0adPava1Wq+3QPvkbmtSSrKysri6BmsDnpXMZHOjx8fG4cOECkpKSYGLS/gG/u7s7VCqVoWUQ6eEJ/8GTlZXF58UIampqmh0IGxToa9euhVarRXJyMszNzQ1pioiIDNSmQF+1ahX27duH0tJSzJw5E7a2tkhISMCmTZvQp08fTJ48GQDQq1cvbNy4sVMLJiKiprUp0JctW4Zly5bds/zcuXNGL4iIiDqGnxQlIhIEA52ISBAMdCIiQTDQiYgEwUAnIhIEA52ISBAMdCIiQTDQiYgEwUAnIhIEA52ISBAMdCIiQTDQiYgEwUAnIhIEA52ISBAMdCIiQTDQiYgEwUAnIhIEA52ISBAMdCIiQTDQiYgEwUAnIhIEA52ISBAMdCIiQbQa6PHx8QgICICbmxvOnz8vLy8sLER4eDgCAwMRHh6OoqKizqyTiIha0WqgP//889i2bRucnZ31lr/zzjuYMmUK0tPTMWXKFCxfvrzTiiQiota1Gug+Pj5wcnLSW1ZWVoYzZ84gODgYABAcHIwzZ87gxo0bnVMlERG1StmRja5cuYIePXrA1NQUAGBqagpHR0dcuXIF9vb27WpLq9V2pAR4e3t3aDt6NGRlZXV1CdQEPi+dq0OBbkzu7u5QqVRdXQYJhif8B09WVhafFyOoqalpdiDcoatcnJycUFJSgvr6egBAfX09rl27ds/UDBER3T8dCnQHBwcMGDAAe/bsAQDs2bMHAwYMaPd0CxERGU+rUy6rVq3Cvn37UFpaipkzZ8LW1hZ79+7FihUrEB0djQ8++AA2NjaIj4+/H/USEVEzFJIkSV2x48Z5IEPm0BUKIxdFQuiaHk2t4Ry6cbSUnfykKBGRIBjoRJ3l99+7uoIHCkfnd+ikvtHlly0SCcvCgvOC1LROmhfkCJ2ISBAMdCIiQTDQiYgEwUAnIhIEA52ISBAMdCIiQTDQiYgEwUAnIhIEA52ISBAMdCIiQTDQiYgEwUAnIhIEA52ISBAMdCIiQTDQiYgEwUAnIhIEA52ISBAMdCIiQTDQiYgEYfBvih46dAjr16+HJEmQJAnz58/H2LFjjVEbERG1g0GBLkkSlixZgm3btkGtVuPnn3/GSy+9hDFjxsDEhIN/IqL7yeDUNTExQWVlJQCgsrISjo6ODHMioi5g0AhdoVAgISEBf/3rX2FlZYXq6mokJye3qw2tVtuhfXt7e3doO3o0ZGVldXUJ7KPUos7oowYFel1dHTZt2oQPPvgA3t7eyMrKQlRUFPbu3Ytu3bq1qQ13d3eoVCpDyiC6B8OUHnQd7aM1NTXNDoQNmhs5e/Ysrl27Jhfm7e0NS0tL5OfnG9IsERF1gEGB3rNnT1y9ehUFBQUAgPz8fJSVlcHV1dUoxRERUdsZNOXSvXt3rFixAgsXLoRCoQAAxMXFwdbW1ijFERFR2xl8HXpoaChCQ0ONUQsRERmA1xcSEQmCgU5EJAgGOhGRIBjoRESCYKATEQmCgU5EJAgGOhGRIBjoRESCYKATEQmCgU5EJAgGOhGRIBjoRESCYKATEQmCgU5EJAgGOhGRIBjoRESCYKATEQmCgU5EJAgGOhGRIBjoRESCYKATEQmCgU5EJAiloQ3U1NQgLi4O3333HVQqFTw9PREbG2uM2oiIqB0MDvS//e1vUKlUSE9Ph0KhQGlpqTHqIiKidjIo0Kurq5GamoojR45AoVAAAJ544gmjFEZERO1j0Bx6cXExbG1tkZiYiIkTJyIiIgKZmZnGqo2IiNrBoBF6fX09iouLMXDgQCxduhQ//vgj5s2bh2+++QbW1tZtakOr1XZo397e3h3ajh4NWVlZXV0C+yi1qDP6qEGB7uTkBKVSieDgYADA4MGDYWdnh8LCQjzzzDNtasPd3R0qlcqQMojuwTClB11H+2hNTU2zA2GDplzs7e3h7++P48ePAwAKCwtRVlaG3r17G9IsERF1gMFXuaxcuRJvvvkm4uPjoVQq8f7778PGxsYYtRERUTsYHOguLi745JNPjFELEREZgJ8UJSISBAOdiEgQDHQiIkEw0ImIBMFAJyISBAOdiEgQDHQiIkEw0ImIBMFAJyISBAOdiEgQDHQiIkEw0ImIBMFAJyISBAOdiEgQDHQiIkEw0ImIBMFAJyISBAOdiEgQDHQiIkEw0ImIBMFAJyISBAOdiEgQRgv0xMREuLm54fz588ZqkoiI2sEogf7TTz/hhx9+gLOzszGaIyKiDjA40GtraxETE4MVK1YYoRwiIuoogwN9/fr1CA0NRa9evYxRDxERdZDSkI1zcnKg1WqxePHiDreh1Wo7tJ23t3eH90niy8rK6uoS2EepRZ3RRxWSJEkd3Tg5ORkff/wxzM3NAQBXr16Fg4MDVq9ejREjRrS4bU1NDbRaLdzd3aFSqTq0f4WiQ5uR4DreozsBOyk1xYBO2lJ2GjRCnzNnDubMmSPfDggIQFJSEtRqtSHNEhFRB/A6dCIiQRg0Qr/bwYMHjdkcERG1A0foRESCYKATEQmCgU5EJAgGOhGRIBjoRESCYKATEQmCgU5EJAgGOhGRIBjoRESCYKATEQmCgU5EJAgGOhGRIBjoRESCYKATEQmCgU5EJAgGOhGRIBjoRESCYKATEQmCgU5EJAgGOhGRIBjoRESCYKATEQlCacjG5eXlWLJkCS5evAhzc3P07t0bMTExsLe3N1Z9RETURgaN0BUKBWbPno309HTs3r0bLi4uWLNmjbFqIyKidjAo0G1tbeHv7y/f9vT0xOXLlw0uioiI2s9oc+gNDQ349NNPERAQYKwmiYioHQyaQ79TbGwsrKysMG3atHZtp9VqO7Q/b2/vDm1Hj4asrKyuLoF9lFrUGX3UKIEeHx+PCxcuICkpCSYm7Rv0u7u7Q6VSGaMMIhnDlB50He2jNTU1zQ6EDQ70tWvXQqvVIjk5Gebm5oY2R0REHWRQoP/yyy/YtGkT+vTpg8mTJwMAevXqhY0bNxqlOCIiajuDAv3pp5/GuXPnjFULEREZgJ8UJSISBAOdiEgQDHQiIkEw0ImIBMFAJyISBAOdiEgQDHQiIkEw0ImIBMFAJyISBAOdiEgQDHQiIkEw0ImIBMFAJyISBAOdiEgQDHQiIkEw0ImIBMFAJyISBAOdiEgQDHQiIkEw0ImIBMFAJyISBAOdiEgQDHQiIkEYHOiFhYUIDw9HYGAgwsPDUVRUZISyiIiovQwO9HfeeQdTpkxBeno6pkyZguXLlxujLiIiaielIRuXlZXhzJkz2Lp1KwAgODgYsbGxuHHjBuzt7VvcVpIkAEBtbW2H9+/k1OFNSWA1NV1dwR3YSakpBnTSxsxszNA7GRToV65cQY8ePWBqagoAMDU1haOjI65cudJqoOt0OgDA+fPnO7z/3bs7vCkJTKvt6gruwE5KTTFCJ9XpdLCwsNBbZlCgG6Jbt25Qq9UwMzODQqHoqjKIiB4qkiRBp9OhW7du96wzKNCdnJxQUlKC+vp6mJqaor6+HteuXYNTG15mmpiY4LHHHjNk90REj6S7R+aNDHpT1MHBAQMGDMCePXsAAHv27MGAAQNanW4hIiLjU0hNzay3Q35+PqKjo/Hbb7/BxsYG8fHx6Nu3r7HqIyKiNjI40ImI6MHAT4oSEQmCgU5EJAgGOhGRIBjoRESCYKB3ooCAAIwbNw5hYWHyv//9739GaTsjIwMTJ040Sltt4ebmhurq6vu2PzKepp47f39/o/VFQ7AfG1eXfVL0UfGPf/wDarW6q8sgokcAA70LuLm5ISoqCvv370dFRQVWrVqFEydO4Ntvv0VdXR3Wr1+Pfv36ISMjA++++y769++Pn376CZaWlnjvvffwhz/84Z42U1NTsWXLFgCAq6srYmJi4ODggODgYMTFxcHDwwMAsHXrVhQUFCA2NhYFBQWIi4tDeXk5dDodZsyYgUmTJgEA9u3bh7Vr10KlUmHs2LH378Gh+y4gIABhYWE4ceIErl+/jsjISEybNg0AWuwj7McPIIk6zejRo6XAwEApNDRUCg0NlSZMmCBJkiSp1Wrp3//+tyRJkpSWliZ5enpKBw8elCRJkpKTk6VFixZJkiRJJ0+elNRqtZSRkSFJkiSlpKTIbZw8eVL+/7lz56Thw4dLJSUlkiRJ0rp166SFCxdKkiRJ//nPf6To6GhJkiSpoaFBeuGFF6SzZ89KOp1OmjBhgpSXlydJkiRVVlZKY8eOlfLy8qTr169Lfn5+Un5+vlyTWq2WqqqqOvcBo07R1HPn5+cnFRcXS5J0u5++9957kiRJUnFxseTp6SlVVVW12Eca22U/frBwhN7JmptyCQoKAgAMGjQIADB69GgAgLu7O7755hv5fr1794afnx8AICwsDG+//Taqqqr02srIyMCoUaPg6OgIAJg8eTLCwsLkbTZu3IiKigrk5ubCwcEB/fv3R15eHvLz8/HGG2/I7eh0OhQUFMDExAQDBw6UP/EbHh6ONWvWGOXxoAfHnV+KN378eABAr169YGNjg6tXr0KSpGb7SL9+/QCwHz9oGOhdRKVSAbj9JWXm5ubychMTE9TV1RltP1ZWVggJCUFKSgq+//57TJ06FcDtb2yzs7PDrl277tnmwIEDRts/dT17e3tUVFTI385XV1eHqqoqve9cauyPAOQv2lMoFM32kbu3Yz9+MPAqlwfcxYsXkZmZCQDYvXs31Go1rK2t9e7j7++PI0eO4Pr16wCAzz//HMOGDZPXT5kyBR999BG0Wq08j/jUU0/BwsICqamp8v3y8/NRVVUFT09PnDlzRv45wR07dnTmIVInGzZsGD777DP59meffYbBgwfD0tKyxe1a6iPtxX58f3CE3skWLFigN/pZtWpVu7ZXq9XYsWMHVqxYAQsLC7z//vtN3mfx4sWIjIwEALi4uCAmJkZe7+Ligr59+8LDw0MeRSmVSiQlJSEuLg5btmxBQ0MDHBwckJCQAAcHB8TGxmLevHmwsLB4NN5MEthbb72Fd999FyEhITAxMYGTk1OT/ehuLfWR9mI/vj/45VwPsIyMDMTHxyMlJcWgdqqqqjBu3Djs3LkTPXr0MFJ1RG3Dfnz/cMpFcJ9++inGjx+PyMhI/hHQQ4v9uG04QiciEgRH6EREgmCgExEJgoFORCQIBjoRkSAY6EREgmCgExEJ4v8BH6/Pw2AAAAADSURBVIgp/3+odPwAAAAASUVORK5CYII=
)

In \[ \]:

female \= df.where(df\['Gender'\] \== "Female").groupby(by\= "Working Status").mean()
female \= female\['BDI Score'\]
female \= np.array(female)
plt.title("BDI Score and Working Status for Females")
plt.bar(\['Employed', 'Unemployed'\], female, color\=("Blue", "Red"))
plt.show()

![](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAXQAAAELCAYAAADJF31HAAAABHNCSVQICAgIfAhkiAAAAAlwSFlzAAALEgAACxIB0t1+/AAAADh0RVh0U29mdHdhcmUAbWF0cGxvdGxpYiB2ZXJzaW9uMy4yLjIsIGh0dHA6Ly9tYXRwbG90bGliLm9yZy+WH4yJAAAgAElEQVR4nO3de1xUZf4H8M/AAIJoXBIjRFtcR1EWGa7e0iQDcRFW3Q3yul4y2wopb7zKWgUjaV3F1BZJc7fW1TTRUilMTS1LVpDCUZNAENYLCoJyMRjg+f3Ri/mJchmYQfDx8369fL2ac+Y8z/ecefjMM2fOnBRCCAEiInrgmXR0AUREZBwMdCIiSTDQiYgkwUAnIpIEA52ISBIMdCIiSTDQqd0lJSXhueee65C+p02bhp07dza6bs6cOdi9e/d9rqhzuXDhAkJDQ6FWq/HRRx91dDlG0dxrLjsGegv8/f3h7u4OtVoNHx8fzJ07F1euXNGtj4qKgpubG9RqNdRqNYKDg/H3v/8dZWVluue0FGgHDx5EaGgoPD094efnh+nTp6OgoKBd96uzmD17NhITE3WPCwsL0b9//0aXXb9+3ah9b9q0CRMmTDBqm/USEhLg7+8PtVqNkSNHIjIyUreutYGzbt06LFy4sD3KxKZNm+Dn54eMjAxMnz7d4PbWrVuHQYMG6f4e1Go1PvjgAyNUSvpgoOshISEBGRkZ+Pbbb2Fvb4+YmJgG62fPno2MjAycOHECsbGx+OGHH/Dcc8+hsrKyxbYvXryIJUuWICoqCunp6Th06BCmTJkCU1NTo9UvhEBdXZ3R2jMmb29vpKWl6R6fPHkSLi4u9yx74okn0KNHD73b7ch93r17Nz777DP885//REZGBnbt2oWhQ4d2SC0tuXz5Mvr169embWtqahpdHhQUhIyMDN2/559/3pASqRUY6K1gYWGBsWPHIicnp8n17u7u+Mc//oHS0lIkJSW12Oa5c+fQq1cvDB06FAqFAtbW1ggMDMTjjz8OAKitrUVCQgLGjBkDtVqNiRMn6j4hnDp1CpMmTYKXlxcmTZqEU6dO6dqdNm0a1qxZg/DwcAwePBgFBQXIycnBzJkz4evri8DAQCQnJzdZ165duxAUFAS1Wo2nn34a27dv161LTU3FyJEj8eGHH2Lo0KEYMWIEdu3apVtfUlKCefPmwdPTE3/84x+Rn5/fZD8+Pj44deqULnzT0tIwY8YMaDSaBsu8vb3btM93unbtGsaPH49Nmzbpnl8/U67/FBUXFwcfHx/4+/vj6NGjum0LCgowZcoUqNVq/PnPf8by5cubnDWfPn0aI0aMQO/evQEAPXr0QFhYGABgzZo1SEtLQ3R0NNRqNaKjowEAK1aswKhRo+Dp6YmJEyfq3tCOHTuGjRs34osvvoBarUZISAiAXz85fvfdd7o+75zFV1VVYeHChfDz84O3tzcmTZqEoqKie+qcPn06UlNTdbXk5uairKwMixcvxpAhQzB69Gi8//77utchKSkJ4eHhiI2NhZ+fH9atW9fk69qYTz/9FEFBQfDx8cHs2bNx6dIl3br+/ftj69atCAgIgFqtRnx8PPLz8xEeHg5PT0/Mnz8f1dXVAICbN2/ihRdewJAhQ+Dj44MXXngBV69ebXW/QgjExsZi6NCh8PT0xPjx45GVldWqfep0BDVr9OjR4vjx40IIISorK8XixYvFokWLdOuXLFkiVq9efc92ixYtEvPnzxdCCLFr1y4RHh7eaPv5+fnCzc1NvP322+L7778X5eXlDdZ/8MEHIjg4WOTk5Ii6ujpx7tw5cePGDVFSUiK8vb3F7t27hVarFXv37hXe3t7ixo0bQgghpk6dKkaNGiWysrKEVqsVt27dEiNHjhSffvqp0Gq14syZM8LX11f8/PPPjdb19ddfi4sXL4q6ujqRmpoq3N3dhUajEUIIceLECeHq6iri4+NFdXW1OHLkiHB3dxelpaVCCCEiIyNFRESEqKioEOfPnxcjRoxocv+rqqrE7373O3HmzBkhhBC///3vRX5+vggLC2uwbPfu3a3e5+rqajF16lSxY8cOkZ+fLwICAsT27dt1fdevq3+NBg4cKD755BNRU1Mjtm7dKoYPHy7q6uqEEEI8++yzYuXKlaKqqkqcPHlSqNVqsWDBgkb3ac+ePcLHx0d88MEHIjMzU9TU1DRYf2e/d25z48YNodVqxebNm8WwYcPEL7/8IoQQ4r333runrzvH5d3P2bZtm3jhhRdEZWWlqKmpEadPnxZlZWWN1np3LYsWLRLz5s0TZWVloqCgQAQEBDQ4Rq6uruKjjz4SWq1W3L59+572GqtVCCG++uorMWbMGJGdnS20Wq3YsGGDCAsL061XqVS6frOyssSgQYPE9OnTRX5+vrh165YICgoSSUlJQgghbty4Ib788ktRWVkpysrKxCuvvCJefPHFRvepuX6PHTsmJkyYIG7evCnq6upEdna2KCwsbPQ4PSg4Q9fDSy+9BG9vb3h7e+P48eOYPXt2i9s4ODjg5s2bLT7P2dkZH3/8MQoLCxEZGYkhQ4YgKioKFRUVAICdO3di/vz5cHFxgUKhwIABA2Bra4sjR46gT58++MMf/gClUong4GC4uLjg66+/1rU9YcIE9OvXD0qlEt988w2cnJwwadIkKJVKDBw4EIGBgfjyyy8breupp55C7969oVAo4Ovri+HDhzc4DaJUKvHSSy/BzMwMo0aNgpWVFXJzc1FbW4sDBw4gIiICVlZWUKlUzZ6nNjc3x+DBg3Hy5EmUlpairKwMzs7O8Pb21i3Lzs6Gj49Pq/fZzMwMAJCdnY0ZM2bglVde0c2UG/P444/j2WefhampKSZMmIDr16+jqKgIly9fxunTpxEREQFzc3N4e3vD39+/yXZCQ0OxdOlSfPvtt5g2bRqGDRvW4DuBpraxtbWFUqnErFmzUF1djdzc3Ga3aYpSqURpaSkuXrwIU1NTuLm5wdrausXtamtrkZycjAULFsDa2hq9evXCzJkz8fnnn+ue4+DggGnTpkGpVKJLly6NtvPll1/q/l68vb1RWFiI7du3Y+7cuejbty+USiXmzZuHc+fONZilz5kzB9bW1ujXrx9UKhWGDx8OZ2dndOvWDSNHjsTZs2cBALa2tggMDISlpSWsra3x4osv4uTJk43W0ly/SqUSFRUVuHDhAoQQ6Nu3LxwcHFpzqDsdZUcX8CDYsGEDhg0bhtraWhw6dAjTpk3D/v37mz2nW1hYiEceeUSv9j08PLB27VoAQGZmJl599VUkJCRgwYIFuHr1qu6j+52uXbumOy1T7/HHH0dhYaHusaOjo+6/L126hMzMTN2pC+DXP+D6j/B3O3r0KDZs2IC8vDzU1dXhl19+gUql0q23sbGBUvn/w8fS0hKVlZW4ceMGampqGvR9d513qz+P7uTkBE9PTwCAl5cXkpKS4OTkBEdHRzg5OWH//v2t2ud6e/fuRe/evREYGNhsHY8++miD/QGAyspKlJSU4JFHHtEtq+/nzi/H7xYSEoKQkBBotVocPHgQixYtgqurK5588slGn79582Z8+umnuHbtGhQKBcrLy1FSUtJsvU0JDQ3F1atX8dprr+HWrVsICQnBq6++qnuDa0pJSQm0Wm2DY3z38X3sscda7H/s2LFYtWpVg2WXL19GbGws4uLidMuEECgsLISTkxOAhsffwsLinsf1p41u376Nd955B998841u0lRRUYHa2tp7vntqrt+hQ4diypQpiI6OxqVLlxAQEIAlS5bo9ebXWXGG3gqmpqYICAiAiYkJ0tPTm3xeRUUFvv/++wbhqS93d3cEBATg559/BvDrH1Bj56AdHBxw+fLlBsuuXLmCnj176h4rFArdfzs6OsLHxwdpaWm6fxkZGVi+fPk9bVdXVyMiIgKzZs3C8ePHkZaWhpEjR0LocWNOOzs7KJXKBmHXXPABaFBX/THz9PTEqVOnGixr7T7Xe/nll2Fra4sFCxagtra2xX24W48ePXDz5k3cvn1b732qZ2ZmhqCgIKhUKt1rere0tDRs2rQJ8fHxOHnyJNLS0tCtWzfd8W5snywtLRvUc+cVQGZmZnj55ZeRnJyM7du348iRI9izZ0+Ltdra2sLMzKzBMdbn+OrD0dERy5cvbzD+MjMzdW/grfHhhx8iNzcXO3bswKlTp7B161YAaHR8ttTv9OnTkZSUhOTkZOTl5em+X3lQMdBbQQiBgwcP4tatW+jbt+8966urq6HRaPDSSy+he/fumDhxYottpqWlYceOHSguLgYA5OTk4PDhwxg8eDAA4E9/+hPWrl2LvLw8CCHw008/oaSkBKNGjUJeXh727t2LmpoaJCcnIzs7G0899VSj/Tz11FPIy8vDnj17oNVqodVqkZmZ2egXvNXV1aiurtaF89GjR3H8+HG9jpGpqSmeeeYZrF+/Hrdv30Z2dnaL13p7eHigrKwMn3/+Oby8vAAAjzzyCOzs7PD555/Dx8cHAFq9z/XMzMywdu1a3L59G4sXL2711S9OTk5wc3PDunXrUF1djYyMjAanee6WlJSEI0eOoLy8HHV1dTh69Ciys7Ph7u4O4NeZ6J1f2FZUVMDU1BR2dnaoqanB+vXrUV5erltvb2+PS5cuNah7wIABSE5OhlarxenTp5GSkqJbd+LECZw/fx61tbWwtraGUqmEiUnLf+qmpqYYO3Ys1qxZg/Lycly6dAlbtmxp8lNca4SHhyMxMVH3plZWVoYvvviiTW1VVFTAwsIC3bt3R2lpKdavX9+mfjMzM/Hjjz9Cq9XC0tIS5ubmeh2nzuzBrv4+mTdvHtRqNTw9PREfH4+VK1c2uNRr8+bNUKvV8PPzw5IlSzBo0CBs374dVlZWLbbdvXt3HD58GOPHj4darcbzzz+PMWPGYM6cOQCAmTNnIigoCLNmzYKnpyfeeOMNVFVVwdbWFgkJCdiyZQv8/PywadMmJCQkwM7OrtF+rK2tsXnzZiQnJ+PJJ5/EiBEjsGrVKt2VA3c/d+nSpYiMjISPjw/27dvX7Dnju7311luorKzE8OHDERUV1eIbm5WVFQYNGgStVtvgtI6XlxeKi4t1M/TW7vOdzM3NsX79ehQXF+P1119vdaivWrUKP/zwA/z8/BAfH49x48bB3Ny80edaW1sjISEBo0ePhre3N1atWoVly5bp9mP69OlISUmBj48PVqxYgREjRuDJJ59EYGAg/P39YWFh0eDU0dixYwEAfn5+uu8jIiMjkZ+fD19fX6xbtw7jx4/XPb+oqAgRERHw8vLCuHHj4Ovri9DQUL32880334SlpSXGjBmDyZMnIzg4GJMmTWrVsWrMM888gzlz5uC1116Dp6cngoODcezYsTa1NWPGDFRVVWHIkCEICwtr8jRWS/1WVFRg6dKl8PX1xejRo2FjY6PX92OdmULo8zmaiBqIjIyEi4sLIiIiOroUIh3O0In0kJmZifz8fNTV1eHYsWM4dOgQxowZ09FlETXAq1yI9FBUVIRXXnkFpaWleOyxx7Bs2TIMHDiwo8siaoCnXIiIJMFTLkREktDrlEtcXBxSUlJw6dIl7N27FyqVCiUlJVi8eDHy8/Nhbm6OPn36IDo6Wq8rDgCgrq4OFRUVMDMza/O1rUREDxshBLRaLbp27XrPZZZ6nXKp/xXflClTkJCQAJVKhdLSUpw/fx5+fn4Afg39mzdvIjY2Vq+iysrKHvwb4RARdRCVSoVu3bo1WKbXDL2xXzza2Njowhz49cch27Zt07uY+p8hq1SqJq/nJf1pNBq4ubl1dBlETeIYNY7q6mpkZWU1eisHo1zlUldXh23btrXqxyf1p1nMzc1hYWFhjDIeejyO1NlxjBpPY6eqjRLoMTExsLKywtSpU1u9rUajMUYJBDR7fxmizoBjtH0ZHOhxcXG4ePEiEhIS2nQfBDc3N75rG0F6erruPihEnRHHqHFUVVU1ORE2KNBXr14NjUaDxMREngcnIupgegX6ihUrcODAARQVFWHmzJmwsbFBfHw8Nm7ciCeeeALh4eEAgF69emHDhg3tWjARETVOr0BfunQpli5des/y8+fPG70gIiJqG/5SlIhIEgx0IiJJPLCB/ssvHV1B58KrB/4fxwY9rB7Y2+d26QLwFjDUGN4/lB5WD+wMnYiIGmKgExFJgoFORCQJBjoRkSQY6EREkmCgExFJgoFORCQJBjoRkSQY6EREkmCgExFJgoFORCQJBjoRkSQY6EREkmCgExFJgoFORCQJBjoRkSQY6EREkmCgExFJgoFORCQJBjoRkSQY6EREkmCgExFJgoFORCSJFgM9Li4O/v7+6N+/P7KysnTLc3NzERYWhsDAQISFhSEvL6896yQioha0GOhPP/00tm7dCicnpwbL//rXv2Ly5MlISUnB5MmT8dZbb7VbkURE1LIWA93b2xuOjo4NlhUXF+Ps2bMIDg4GAAQHB+Ps2bO4ceNG+1RJREQtatM59CtXrqBnz54wNTUFAJiamsLBwQFXrlwxanFERKQ/ZUcXoNFo2rSdl5eXkSshmaSnp3d0CdQIvi7tq02B7ujoiMLCQtTW1sLU1BS1tbW4du3aPadm9OHm5gYLC4u2lEHUJL7hdz7p6el8XYygqqqqyYlwm0652Nvbw9XVFfv27QMA7Nu3D66urrCzs2t7lUREZBCFEEI094QVK1bgwIEDKCoqgq2tLWxsbLB//37k5OQgKioKt27dQvfu3REXFwcXFxe9O65/lzFkhq5QtGkzklzzI/o++uUXoEuXjq6COiMDxkZz2dlioLcXBjq1l04T6AAHKTXOgEHaXHbyl6JERJJgoBMRSYKBTkQkCQY6EZEkGOhERJJgoBMRSYKBTkQkCQY6EZEkGOhERJJgoBMRSYKBTkQkCQY6EZEkGOhERJJgoBMRSYKBTkQkCQY6EZEkGOhERJJgoBMRSYKBTkQkCQY6EZEkGOhERJJgoBMRSYKBTkQkCQY6EZEkGOhERJJgoBMRSYKBTkQkCaWhDXz99ddYu3YthBAQQuDll19GQECAMWojIqJWMCjQhRBYvHgxtm7dCpVKhZ9++gnPPfccxowZAxMTTv6JiO4ng1PXxMQEZWVlAICysjI4ODgwzImIOoBBM3SFQoH4+Hj85S9/gZWVFSoqKpCYmNiqNjQaTZv69vLyatN29HBIT0/v6BI4RqlZ7TFGDQr0mpoabNy4Ee+//z68vLyQnp6OyMhI7N+/H127dtWrDTc3N1hYWBhSBtE9GKbU2bV1jFZVVTU5ETbo3Mi5c+dw7do1XWFeXl6wtLRETk6OIc0SEVEbGBTojz32GK5evYoLFy4AAHJyclBcXIzevXsbpTgiItKfQadcevTogWXLlmH+/PlQKBQAgNjYWNjY2BilOCIi0p/B16GHhIQgJCTEGLUQEZEBeH0hEZEkGOhERJJgoBMRSYKBTkQkCQY6EZEkGOhERJJgoBMRSYKBTkQkCQY6EZEkGOhERJJgoBMRSYKBTkQkCQY6EZEkGOhERJJgoBMRSYKBTkQkCQY6EZEkGOhERJJgoBMRSYKBTkQkCQY6EZEkGOhERJJgoBMRSYKBTkQkCQY6EZEkGOhERJJgoBMRSUJpaANVVVWIjY3F999/DwsLC3h4eCAmJsYYtRERUSsYHOh/+9vfYGFhgZSUFCgUChQVFRmjLiIiaiWDAr2iogJ79uzB0aNHoVAoAACPPvqoUQojIqLWMSjQCwoKYGNjg/Xr1yM1NRVdu3bF/Pnz4e3trXcbGo2mTX17eXm1aTt6OKSnp3d0CRyj1Kz2GKMGBXptbS0KCgowcOBALFmyBD/++CPmzZuHr776CtbW1nq14ebmBgsLC0PKILoHw5Q6u7aO0aqqqiYnwgZd5eLo6AilUong4GAAwODBg2Fra4vc3FxDmiUiojYwKNDt7Ozg5+eH48ePAwByc3NRXFyMPn36GKU4IiLSn8FXuSxfvhyvv/464uLioFQq8e6776J79+7GqI2IiFrB4EB3dnbGxx9/bIxaiIjIAPylKBGRJBjoRESSYKATEUmCgU5EJAkGOhGRJBjoRESSYKATEUmCgU5EJAkGOhGRJBjoRESSYKATEUmCgU5EJAkGOhGRJBjoRESSYKATEUmCgU5EJAkGOhGRJBjoRESSYKATEUmCgU5EJAkGOhGRJBjoRESSYKATEUmCgU5EJAkGOhGRJBjoRESSMFqgr1+/Hv3790dWVpaxmiQiolYwSqCfOXMGP/zwA5ycnIzRHBERtYHBgV5dXY3o6GgsW7bMCOUQEVFbGRzoa9euRUhICHr16mWMeoiIqI2UhmyckZEBjUaDhQsXtrkNjUbTpu28vLza3CfJLz09vaNL4BilZrXHGFUIIURbN05MTMRHH30Ec3NzAMDVq1dhb2+Pd955ByNGjGh226qqKmg0Gri5ucHCwqJN/SsUbdqMJNf2Ed0OOEipMQYM0uay06AZ+ty5czF37lzdY39/fyQkJEClUhnSLBERtQGvQycikoRBM/S7HT582JjNERFRK3CGTkQkCQY6EZEkGOhERJJgoBMRSYKBTkQkCQY6EZEkGOhERJJgoBMRSYKBTkQkCQY6EZEkGOhERJJgoBMRSYKBTkQkCQY6EZEkGOhERJJgoBMRSYKBTkQkCQY6EZEkGOhERJJgoBMRSYKBTkQkCQY6EZEkGOhERJJgoBMRSYKBTkQkCQY6EZEkGOhERJJQGrJxSUkJFi9ejPz8fJibm6NPnz6Ijo6GnZ2dseojIiI9GTRDVygUmDNnDlJSUrB37144Oztj1apVxqqNiIhawaBAt7GxgZ+fn+6xh4cHLl++bHBRRETUekY7h15XV4dt27bB39/fWE0SEVErGHQO/U4xMTGwsrLC1KlTW7WdRqNpU39eXl5t2o4eDunp6R1dAscoNas9xqhRAj0uLg4XL15EQkICTExaN+l3c3ODhYWFMcog0mGYUmfX1jFaVVXV5ETY4EBfvXo1NBoNEhMTYW5ubmhzRETURgYF+s8//4yNGzfiiSeeQHh4OACgV69e2LBhg1GKIyIi/RkU6P369cP58+eNVQsRERmAvxQlIpIEA52ISBIMdCIiSTDQiYgkwUAnIpIEA52ISBIMdCIiSTDQiYgkwUAnIpIEA52ISBIMdCIiSTDQiYgkwUAnIpIEA52ISBIMdCIiSTDQiYgkwUAnIpIEA52ISBIMdCIiSTDQiYgkwUAnIpIEA52ISBIMdCIiSTDQiYgkwUAnIpIEA52ISBIMdCIiSRgc6Lm5uQgLC0NgYCDCwsKQl5dnhLKIiKi1DA70v/71r5g8eTJSUlIwefJkvPXWW8aoi4iIWklpyMbFxcU4e/YstmzZAgAIDg5GTEwMbty4ATs7u2a3FUIAAKqrq9vcv6NjmzcliVVVdXQFd+AgpcYYMEjrM7M+Q+9kUKBfuXIFPXv2hKmpKQDA1NQUDg4OuHLlSouBrtVqAQBZWVlt7n/v3jZvShLTaDq6gjtwkFJjjDBItVotunTp0mCZQYFuiK5du0KlUsHMzAwKhaKjyiAieqAIIaDVatG1a9d71hkU6I6OjigsLERtbS1MTU1RW1uLa9euwVGPj5kmJibo1q2bId0TET2U7p6Z1zPoS1F7e3u4urpi3759AIB9+/bB1dW1xdMtRERkfArR2Jn1VsjJyUFUVBRu3bqF7t27Iy4uDi4uLsaqj4iI9GRwoBMRUefAX4oSEUmCgU5EJAkGOhGRJBjoRESSYKC3I39/f4wdOxahoaG6f//73/+M0nZqaiomTpxolLb00b9/f1RUVNy3/sh4Gnvt/Pz8jDYWDcFxbFwd9kvRh8V7770HlUrV0WUQ0UOAgd4B+vfvj8jISBw8eBClpaVYsWIFvvvuO3zzzTeoqanB2rVr0bdvX6SmpuLtt9/GgAEDcObMGVhaWmLlypX47W9/e0+be/bswebNmwEAvXv3RnR0NOzt7REcHIzY2Fi4u7sDALZs2YILFy4gJiYGFy5cQGxsLEpKSqDVajFjxgxMmjQJAHDgwAGsXr0aFhYWCAgIuH8Hh+47f39/hIaG4rvvvsP169cxa9YsTJ06FQCaHSMcx52QoHYzevRoERgYKEJCQkRISIiYMGGCEEIIlUol/v3vfwshhEhOThYeHh7i8OHDQgghEhMTxYIFC4QQQpw4cUKoVCqRmpoqhBAiKSlJ18aJEyd0/33+/HkxfPhwUVhYKIQQYs2aNWL+/PlCCCH+85//iKioKCGEEHV1deKZZ54R586dE1qtVkyYMEFkZ2cLIYQoKysTAQEBIjs7W1y/fl34+vqKnJwcXU0qlUqUl5e37wGjdtHYa+fr6ysKCgqEEL+O05UrVwohhCgoKBAeHh6ivLy82TFS3y7HcefCGXo7a+qUS1BQEABg0KBBAIDRo0cDANzc3PDVV1/pntenTx/4+voCAEJDQ/Hmm2+ivLy8QVupqakYNWoUHBwcAADh4eEIDQ3VbbNhwwaUlpYiMzMT9vb2GDBgALKzs5GTk4PXXntN145Wq8WFCxdgYmKCgQMH6n7xGxYWhlWrVhnleFDncedN8caNGwcA6NWrF7p3746rV69CCNHkGOnbty8AjuPOhoHeQSwsLAD8epMyc3Nz3XITExPU1NQYrR8rKyuMHz8eSUlJ+O9//4spU6YA+PWObba2tvjss8/u2ebQoUNG6586np2dHUpLS3V356upqUF5eXmDey7Vj0cAuhvtKRSKJsfI3dtxHHcOvMqlk8vPz0daWhoAYO/evVCpVLC2tm7wHD8/Pxw9ehTXr18HAOzYsQPDhg3TrZ88eTL+9a9/QaPR6M4j/uY3v0GXLl2wZ88e3fNycnJQXl4ODw8PnD17Vve/E9y5c2d77iK1s2HDhuGTTz7RPf7kk08wePBgWFpaNrtdc2OktTiO7w/O0NtZREREg9nPihUrWrW9SqXCzp07sWzZMnTp0gXvvvtuo89ZuHAhZs2aBQBwdnZGdHS0br2zszNcXFzg7u6um0UplUokJCQgNjYWmzdvRl1dHezt7REfHw97e3vExMRg3rx56NKly8PxZZLE3njjDbz99tsYP348TExM4Ojo2Og4ulgzNUgAAABzSURBVFtzY6S1OI7vD96cqxNLTU1FXFwckpKSDGqnvLwcY8eOxa5du9CzZ08jVUekH47j+4enXCS3bds2jBs3DrNmzeIfAT2wOI71wxk6EZEkOEMnIpIEA52ISBIMdCIiSTDQiYgkwUAnIpIEA52ISBL/B7dRkRR6+y7lAAAAAElFTkSuQmCC
)

**_It is clear that unemployed people experience less marital depression than employed people. And it is not depend on any gender_**

In \[ \]:

male \= df.where(df\['Gender'\] \== "Male").groupby(by \= "Marriage Style").mean()
male \= male\['BDI Score'\]
male \= np.array(male)
plt.title("BDI Score and Marriage Style for Females")
plt.bar(\['Arranged Marriage', 'Flirt Marriage'\], male, color\=("Blue", "Pink"))
plt.show()

![](data:image/png;base64,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
)

In \[ \]:

female \= df.where(df\['Gender'\] \== "Male").groupby(by \= "Marriage Style").mean()
female \= female\['BDI Score'\]
female \= np.array(female)
plt.title("BDI Score and Marriage Style for Females")
plt.bar(\['Arranged Marriage', 'Flirt Marriage'\], female, color\=("Blue", "Pink"))
plt.show()

![](data:image/png;base64,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
)

**_Average depression threshold is higher in arranged marriages, but relatively lower in flirtatious marriages._**

In \[ \]:

sns.catplot(x\="Gender", y\="BDI Score",
                hue\="Education",
                data\=df, kind\="box",
                palette \= "Blues", 
                height\=7, aspect\=.7).set(title\='Education and BDI Score by Genders');

![](data:image/png;base64,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
)

**_Education has a positive effect on both sexes, but in women, the average level of marital depression decreases with the increase in the level of education._**

In \[ \]:

sns.catplot(x\="Gender", y\="BDI Score",
                hue\="Status of Having a Child",
                data\=df, kind\="bar",
                height\=7, palette\="Blues",
                aspect\=.8).set(title\="Status of Having Childrens and BDI Score by Genders");

![](data:image/png;base64,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vn3GAw88YBw6dMgwDMN45513jMcee8z466+/jFOnThmRkZFGq1at8qx74cKFxsMPP5znvCv3ISgoyNi1a5eRlZVlDB061Hj55Zdt8z09PY2jR49es78bN240WrRoYfz222/GhQsXjKFDh16zrJ+fn7Fjxw7DarUa6enpRteuXY0ZM2YYGRkZxu+//26EhoYasbGxtmPg7e1tbNiwwcjOzjamTp1q9OzZ0zAMw0hMTDRat25tJCUl2Y7RsWPH8tyfwvSvgo5tnz59jLNnzxonT540IiIi8j22Vx+bv/76y3j66aeN6dOn2+Y//vjjxhdffHHNen379jXefvtt235f2b+vtH37duPBBx803nvvPWPHjh1GRkZGrvljx441Hn/8cSMpKcnIzs424uLijIyMDOPw4cNG06ZNjU2bNhmZmZlGTEyM0bZtW9v6bdq0MaKiooyTJ08aFy9eNJKSkoygoCBjw4YNhtVqNTZt2mQEBQUZZ86cybOuNm3aGBEREcbJkyeNs2fPGr169bL1i5iYGGPIkCG2ZdetW2dERkbmuZ2XX37ZGD58eJ7zLrtw4YLRunVr46uvvjKysrKMvXv3GkFBQcbBgwcNwyi4/545c8bw8fExVq9ebWRmZhrz5s0zGjVqZPuerFu3zmjbtq1x6NAhIysry5g1a5bRq1cvW9uenp5Gv379jLNnzxoXL140YmNjja5duxrnzp0zcnJyjEOHDhnJyckF1g+UpDI/UlGpUiUtXLhQFotFr7/+ulq0aKHo6GidPn0633WaNWsmLy8vOTg4qGHDhoqIiNC2bdtuuAYHBwcdPHhQly5dUo0aNXT//ffnudzy5cs1aNAg3XHHHapWrZoGDRqU76hGfpo3b66AgADbvxUrVuSa36NHD1WqVEnOzs568cUXtX//fqWlpUmSIiIibMufP39esbGxioiIyLetwYMHq2LFimrYsKEaNmyo/fv3S5JWr16t559/XlWqVFGtWrUKHFn566+/VL169evuV9u2bdWkSRM5OTkpKipK+/btu+46q1evVrdu3eTp6Sk3NzcNHjz4mmXCwsLk7+8vBwcHHThwQKmpqRo8eLCcnZ1Vr149Pfroo7n+6vT391dISIgcHR3VuXNn2z47OjoqMzNTiYmJysrKUt26dXXXXXflWVdh+ldBxzY6Olru7u7y8PDQE088cd3j0LVr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xIkTFRISIj8/P3Xr1k07duzId9m3335bXbp00YABA1StWjVZLBZ5e3vrvffey7Xc3Llz1aJFCwUHB+f6UEVBpzR+/fVXde3aVb6+vnr55ZeVkZGRbx15KVSoGDhwoJKSknJNS0pK0uDBg4vUGACg5N17771ydHTU8OHDtXHjRp07d842r0GDBho3bpx8fHwUHx9v+2Xm6uqqKVOmaMeOHZozZ44WLVqk77//XpL03//+V5K0fft2xcfHy9fXt8D209PTNXHiRH300UeKj4/X4sWL1ahRozyX/fDDD7Vr1y598803+vbbb7Vnzx598MEHuvfee7VixQpbu5999tkNH4/WrVvru+++0+bNm9W4cWNbUGjatKlcXV21ZcsW27LLly+3hYq8xMXFac2aNfr00081a9YsJSYmSpJmzpypP/74Q99//73mzZuXb4i67MEHH9TXX3+tbdu2KTIyUkOGDMnzF/rFixe1c+dOhYeHF7i906dPKy0tTbGxsZo0aZLGjx+f6/uel8zMTA0aNEidO3fWtm3b1KFDB61du7bAda5W6E9/eHl55Zrm5eWlw4cPF6kxAEDJq1SpkhYuXCiLxaLXX39dLVq0UHR0tE6fPp3vOs2aNZOXl5ccHBzUsGFDRUREXPOohqJwcHDQwYMHdenSJdWoUUP3339/nsstX75cgwYN0h133KFq1app0KBB1/2FfLXmzZsrICDA9u9yGLmsR48eqlSpkpydnfXiiy9q//79SktLkyRFRETYlj9//rxiY2Nz3U7haoMHD1bFihXVsGFDNWzYUPv375ckrV69Ws8//7yqVKmiWrVqXXdkpXPnzqpataqcnJz0zDPP2EZnrvb3338rJydH1atXL3B7Tk5OGjRokCpUqKCQkBC5ubld98Ggu3btUlZWlp566ilVqFBBHTp00IMPPljgOlcrVKioVq2ajh07lmvasWPHuKYCAMqIBg0a6K233lJsbKyWL1+ulJQUTZ48Od/ld+3apSeeeELNmzeXv7+/Fi9efMOftnBzc9O0adO0ePFiBQcHa8CAAba/6K+WkpKi2rVr217Xrl1bKSkpRWpvy5Yt2rFjh+1fZGSkbZ7VatXUqVPVtm1b+fn5KTQ0VJJs+9apUyetW7dOmZmZWrdunRo3bqw6derk29add95p+7+rq6vS09Nt++Hh4WGbV6tWrQJr/uST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xbrtttts0y9cuKDBgwcrJiaGR58DAIpVUX/xm73dH3/8Mdfr4cOHa/jw4bbXn376qal1lWUFHtH169fr1VdfzRUoJOm2227TsGHDtH79+mItDgAAlB0FhoqTJ0/K09Mzz3menp76448/iqUoAABQ9lx37MfZ2Tnf6de7hwUAACg/CrymIiMjQ++9916+86++sxgAACi/CgwVnTp1UlJSUr7zIyMjTS8IAACUTQWGijfffLOk6gAAAGVckT+nc+bMGa1du1aJiYnFUQ8AALlkZlvttt3XXntN77zzTq5p/fr108KFC4ulprKuwJGKpKQkTZgwQYmJifL19dUzzzyjxx9/XA4ODkpLS9OUKVMUERFRUrUCAMohZydHdZz0tenbXT2qy3WXGTlypDp37qz27duradOmWrx4sSwWi/r06WN6PbeCAkcqxo4dqypVqui1116TYRjq37+/Jk6cqM2bN2v69OmaPXt2SdUJAECJu/322zVhwgS99tprOnLkiD788ENNnDhRQ4YMUY8ePdSpUyfb78KcnByNHTtWHTp0UFRUlHr37m3n6ktegSMV8fHx+t///idnZ2cFBQUpMDBQbdu2lSS1bds21x3FAAC4FbVs2VKBgYHq0aOHXnvtNY0ePVoDBw5UYGCgMjMz1a9fPz344IOqWrWqtm7dqlWrVsnBwUHnzp2zd+klrsBQkZWVZbtPhaurq9zc3HLdm8IwjOKtDgCAUqB///5avXq1HnnkEY0ZM0apqam2eRcuXFBiYqK6du2q7OxsjRo1Ss2aNVObNm3sWLF9FBgqrFartmzZYgsP2dnZuV7n5OQUf4UAANiZg4ODLBaLcnJyZLFY9NVXX6lChQrXLLdy5Upt3bpVP//8s6ZOnaply5apevXqdqjYPgoMFXfccYdGjhxpe+3u7p7rdXl+EhsAoPypVKmS/P39FRMTo0GDBkmSTp06JScnJzk6OsrR0VGtWrXSQw89pA0bNuj48eOEisuufjIbAADl3dSpU/Xmm2+qU6dOkv55yOakSZN06dIlvf7668rOzpbValXr1q3l4+Nj52pLVoGhoqRkZGRo8uTJ2rx5s1xcXOTj46MJEybYuywAQCmQmW0t1Mc/b2S7zk6OhVq2bt262rp1qySpevXqevfdd/NcbunSpabVVxaVilDxzjvvyMXFRd99950sFotOnz5t75IAAKVEYX/xl5btlmd2DxUXLlzQ119/rY0bN9o+WXLnnXfauSoAAFBURb5Nt9mOHz8ud3d3zZw5U926ddMTTzyhHTt22LssAABQRHYfqbBarTp+/LgaN26s4cOHa9euXYqOjta6detUqVKlQm0jISHhhtv39/e/4XVx64iLi7Nr+/RDSDfXD+lDKA3sHio8PDzk5ORke4x606ZNVbVqVR05ckQPPvhgobbh7e0tFxeX4iwTtzjekFEa0A9R1tn99Ee1atXUrFkz/fTTT5KkI0eO6MyZM7r77rvtXBkAACgKu49USNK4ceM0cuRITZkyRU5OTnr77bdVuXJle5cFAACKoFSEinr16unzzz+3dxkAAOAm2P30BwAAuDUQKgAAgCkIFQAAwBSECgAAYApCBQAAMAWhAgAAmIJQAQAATEGoAAAApiBUAAAAUxAqAACAKQgVAADAFIQKAABgCkIFAAAwBaECAACYglABAABMQagAAACmIFQAAABTECoAAIApCBUAAMAUhAoAAGAKQgUAADAFoQIAAJiCUAEAAExBqAAAAKYgVAAAAFMQKgAAgCkIFQAAwBSECgAAYApCBQAAMAWhAgAAmIJQAQAATEGoAAAApiBUAAAAUxAqAACAKQgVAADAFIQKAABgCkIFAAAwBaECAACYglABAABMQagAAACmIFQAAABTECoAAIApCBUAAMAUhAoAAGAKQgUAADAFoQIAAJiCUAEAAExBqAAAAKYgVAAAAFMQKgAAgCkIFQAAwBSECgAAYApCBQAAMAWhAgAAmKJUhYqZM2fKy8tLBw4csHcpAACgiEpNqNi7d6927typOnXq2LsUAABwA0pFqMjMzNT48eM1duxYe5cCAABukJO9C5Ck9957T1FRUapbt+4NrZ+QkHDDbfv7+9/wurh1xMXF2bV9+iGkm+uH9CGUBnYPFfHx8UpISNArr7xyw9vw9vaWi4uLiVWhvOENGaUB/RBlnd1Pf2zfvl2JiYkKCwtTaGiokpKS1L9/f23atMnepQEAgCKw+0jFgAEDNGDAANvr0NBQzZ49W56ennasCgAAFJXdRyoAAMCtwe4jFVf78ccf7V0CAAC4AYxUAAAAUxAqAACAKQgVAADAFIQKAABgCkIFAAAwBaECAACYglABAABMQagAAACmIFQAAABTECoAAIApCBUAAMAUhAoAAGAKQgUAADAFoQIAAJiCUAEAAExBqAAAAKYgVAAAAFMQKgAAgCkIFQAAwBSECgAAYApCBQAAMAWhAgAAmIJQAQAATEGoAAAApiBUAAAAUxAqAACAKQgVAADAFIQKAABgCkIFAAAwBaECAACYglABAABMQagAAACmIFQAAABTECoAAIApCBUAAMAUhAoAAGAKQgUAADAFoQIAAJiCUAEAAExBqAAAAKYgVAAAAFMQKgAAgCkIFQAAwBSECgAAYApCBQAAMAWhAgAAmIJQAQAATEGoAAAApiBUAAAAUxAqAACAKQgVAADAFIQKAABgCkIFAAAwhZO9Czh79qxeffVV/f7773J2dtbdd9+t8ePHq1q1avYuDQAAFIHdRyosFoueffZZfffdd1q+fLnq1aunqVOn2rssAABQRHYPFe7u7mrWrJnttY+Pj06ePGnHigAAwI2w++mPK+Xk5GjRokUKDQ0t0noJCQk33Ka/v/8Nr4tbR1xcnF3bpx9Curl+SB9CaVCqQsWECRPk5uamxx9/vEjreXt7y8XFpZiqQnnAGzJKA/ohyrpSEyqmTJmiY8eOafbs2XJwsPtZGQAAUESlIlS8++67SkhIUExMjJydne1dDgAAuAF2DxUHDx7UnDlzdM8996h3796SpLp162rWrFl2rgwAABSF3UPF/fffr99++83eZQAAgJvExQsAAMAUhAoAAGAKQgUAADAFoQIAAJiCUAEAAExBqAAAAKYgVAAAAFMQKgAAgCkIFQAAwBSECgAAYApCBQAAMAWhAgAAmIJQAQAATEGoAAAApiBUAAAAUxAqAACAKQgVAADAFIQKAABgCkIFAAAwBaECAACYglABAABMQagAAACmIFQAAABTECoAAIApCBUAAMAUhAoAAGAKQgUAADAFoQIAAJiCUAEAAExBqAAAAKYgVAAAAFMQKgAAgCkIFQAAwBSECgAAYApCBQAAMAWhAgAAmIJQAQAATEGoAAAApiBUAAAAUxAqAACAKQgVAADAFIQKAABgCkIFAAAwBaECAACYglABAABMQagAAACmIFQAAABTECoAAIApCBUAAMAUhAoAAGAKQgUAADAFoQIAAJiCUAEAAExRKkLFkSNH1KtXL4WHh6tXr146evSovUsCAABFVCpCxZgxY9S3b19999136tu3r9544w17lwQAAIrIyd4FnDlzRr/++qvmzZsnSYqMjNSECROUmpqqatWqFbiuYRiSpMzMzJuqwdGw3tT6ZV1GRobcXR3tXYbdZGRk2LsESeW7H5b3PiiZ0w+dnZ1lsVhMqAa4MXYPFadOnVLNmjXl6PjPG4qjo6Nq1KihU6dOXTdUZGVlSZIOHDhwUzXUuKm1y76EhHN6JaS2vcuwm4SEBHuXIKl898Py3gclc/qht7e3XFxcTKgGuDF2DxU347bbbpOnp6cqVKhAOgdQ7jk7O9u7BJRzdg8VHh4eSk5OltVqlaOjo6xWq1JSUuTh4XHddR0cHHT77beXQJUAAOB67H6h5h133KFGjRppxYoVkqQVK1aoUaNG1z31AQAASheLcflqRztKTEzUiBEj9Pfff6ty5cqaMmWK6tevb++yAABAEZSKUAEAAMo+u5/+AAAAtwZCBQAAMAWhAgAAmIJQAQAATEGouAWFhoYqODhYVuv/v+3z0qVL5eXlpf/+978FrvvEE09o/fr1xV0ibhGhoaHq0KGDOnfurM6dO2vy5Mkl0ubN3kUXQPGw+82vUDxq1KihTZs2KSQkRJK0bNkyPfDAA3auCrei999/X56envYuA0ApQKi4RXXt2lVLly5VSEiIjh8/rvT0dNsb/+bNmzV9+nRlZGTIarUqOjpaERER12zj/PnzevPNN/Xbb78pIyNDzZo102uvvWZ7TguQl2XLlmnhwoWyWq2qVKmSxo4dq/r162vp0qVasWKFbr/9dv3222+qWbOmXn/9dU2ZMkW///67vL29NXXqVFksFi1fvlyfffaZ7fk+w4cPV4sWLa5pKyUlRRMnTtTJkyeVkZGhiIgIRUdHl/QuA/g/hIpbVFBQkBYuXKhz585p2bJl6tKli/bu3StJaty4sRYuXChHR0edPn1a3bp1U3BwsKpUqZJrG2+++aYCAwM1adIk5eTk6JVXXtGSJUv06KOP2mOXUEq99NJLtodYtWvXTrt379aCBQvk7OysjRs3auTIkVq8eLEkac+ePVq+fLlq1aql559/XsOGDdPnn38uNzc3de3aVZs3b9ZDDz2k4OBgRUZGymKx6PDhw+rXr59iY2OvaXv48OEaOHCgAgMDlZmZqX79+unBBx9Uy5YtS/QYAPgHoeIWZbFY1LFjR61cuVIrV67U4sWLbaEiNTVVI0eO1LFjx+To6Khz587pyJEj8vHxybWNH3/8Ubt377Y9lv7SpUuqWbNmie8LSrcrT3+8/fbb2r9/v3r27ClJMgxDf//9t21ZPz8/1apVS5LUqFEj1alTR5UrV5YkNWzYUMeOHdNDDz2k48ePa9iwYUpOTpaTk5NOnz6tP//8U9WrV7dtKz09Xdu2bVNqaqpt2oULF5SYmEioAOyEUHEL69q1q3r27KnAwEBVrVrVNn3s2LEKDQ3VzJkzZbFYFB4eroyMjGvWNwxDH3zwgerVq1eSZaMMMwxD3bt315AhQ/Kcf+VjuR0dHa95ffni4qFDh2rEiBFq27atcnJy1LRp02v6aE5OjiwWi7766itVqFChGPYGQFHx6Y9bWL169fSvf/1LAwcOzDU9LS1NderUkcVi0U8//aRjx47luX5oaKhiYmJsb/Spqak6fvx4sdeNsis0NFTffPONkpKSJElWq1UJCQlF3k5aWprq1q0rSVqyZIkyMzOvWaZSpUry9/dXTEyMbdqpU6f0559/3mD1AG4WIxW3uF69el0zbdiwYRo3bpxmzJihBx98UF5eXnmuO3LkSL3zzjvq3LmzLBaLKlSooJEjRzJygXwFBgbq5Zdf1gsvvCCr1aqsrCx16NBB3t7eRdrOa6+9poEDB6pKlSpq1aqV3N3d81xu6tSpevPNN9WpUydJ0m233aZJkyblOk0CoOTwQDEAAGAKTn8AAABTECoAAIApCBUAAMAUhAoAAGAKQgUAADAFoQIoRkuXLlWfPn3sXQYAlAjuU4FyaeXKlZo/f74OHjwoV1dX1a1bV126dFHfvn1lsVjsXR4AlEmMVKDcmTt3riZNmqT+/ftr06ZN+vnnnzVu3Dj98ssvtqdilgaX72QKAGUFoQLlSlpamt5//32NGTNGHTp0UKVKlWSxWNS4cWP95z//kbOzszIzMzVlyhQ9/PDDeuihh/TGG2/o0qVLkqStW7eqdevWmjt3rlq0aKHg4GAtWbLEtv2zZ88qOjpafn5+6tGjh37//fdc7ScmJurpp59WUFCQwsPDtWrVKtu8ESNGaMyYMXruuefk4+OjrVu3lsxBAQCTECpQrsTHxyszM1NhYWH5LjN16lQdOXJEX3/9tdauXauUlBTNmjXLNv/06dNKS0tTbGysJk2apPHjx+vcuXOSpPHjx8vFxUWbNm3S5MmTcwWO9PR0PfPMM4qMjNTPP/+sadOmady4cTp06JBtmRUrVig6Olq//PKL/P39i+EIAEDxIVSgXDl79qyqVq0qJ6f/fzlR7969FRAQoCZNmmjbtm364osvNHLkSLm7u6tSpUp6/vnntXLlStvyTk5OGjRokCpUqKCQkBC5ubnpyJEjslqtWrt2rV566SW5ubnJ09NTXbt2ta23YcMG1alTR927d5eTk5MaN26s8PBwrVmzxrZMWFiY/P395eDgkOsJngBQFnChJsoVd3d3nT17VtnZ2bZgsXjxYklS69b/r727V00kjMI4/qyKRBDBNIOCjRa2CqYSF5tgZyEoeAFWtoLYCDbiBWineAmxEdJYeQc2NgZsRAQ1jWQKPybFskOWLcKyk+wG/79qZg7v4T3dw7wM813b7VamaapQKNhrLMvS5XL5pcfbUOLz+fTy8qL9fq/T6aRQKGTXwuGwfb1arTSbzZRKpexn5/NZ+Xzevn+7FgC+GkIFrkoyvCOAVAAAAUFJREFUmZTX69VkMlEul/utHgwGdXNzo/F4LMMw/qj37e2tPB6P1uu1YrGYpB+/4v4pFArp7u5Ow+Hw74YAgP8Uxx+4KoFAQNVqVa1WS4+PjzocDrpcLprP5zJNUy6XS8ViUe12W7vdTpK02Ww0nU7f7e12u3V/f69utyvTNLVYLPTw8GDXs9mslsulRqORjsejjsejZrOZnp6ePmxeAPhMvKnA1alUKjIMQ/1+X/V6XT6fT5FIRLVaTclkUolEQr1eT6VSSc/PzzIMQ+VyWZlM5t3ezWZTjUZD6XRa0WhUhULB/orD7/drMBio0+mo0+nIsizF43E1Go2PHhkAPsU3y7Ksf70JAADw9XH8AQAAHEGoAAAAjiBUAAAARxAqAACAIwgVAADAEYQKAADgCEIFAABwBKECAAA4glABAAAc8QriMAXI7fHhQAAAAABJRU5ErkJggg==
)

**_Towards the end, we make an interesting discovery :) So, although the presence of children at home does not affect men as much, the feeling of being a mother causes a decrease in the level of depression in women. Simply put, children heal their mothers._**
