# htan234.github.io

<html><head><meta http-equiv="Content-Type" content="text/html; charset=utf-8"/><title>Andy H. Tan’s Portfolio</title><style>
/* cspell:disable-file */
/* webkit printing magic: print all background colors */
html {
	-webkit-print-color-adjust: exact;
}
* {
	box-sizing: border-box;
	-webkit-print-color-adjust: exact;
}

html,
body {
	margin: 0;
	padding: 0;
}
@media only screen {
	body {
		margin: 2em auto;
		max-width: 900px;
		color: rgb(55, 53, 47);
	}
}

body {
	line-height: 1.5;
	white-space: pre-wrap;
}

a,
a.visited {
	color: inherit;
	text-decoration: underline;
}

.pdf-relative-link-path {
	font-size: 80%;
	color: #444;
}

h1,
h2,
h3 {
	letter-spacing: -0.01em;
	line-height: 1.2;
	font-weight: 600;
	margin-bottom: 0;
}

.page-title {
	font-size: 2.5rem;
	font-weight: 700;
	margin-top: 0;
	margin-bottom: 0.75em;
}

h1 {
	font-size: 1.875rem;
	margin-top: 1.875rem;
}

h2 {
	font-size: 1.5rem;
	margin-top: 1.5rem;
}

h3 {
	font-size: 1.25rem;
	margin-top: 1.25rem;
}

.source {
	border: 1px solid #ddd;
	border-radius: 3px;
	padding: 1.5em;
	word-break: break-all;
}

.callout {
	border-radius: 3px;
	padding: 1rem;
}

figure {
	margin: 1.25em 0;
	page-break-inside: avoid;
}

figcaption {
	opacity: 0.5;
	font-size: 85%;
	margin-top: 0.5em;
}

mark {
	background-color: transparent;
}

.indented {
	padding-left: 1.5em;
}

hr {
	background: transparent;
	display: block;
	width: 100%;
	height: 1px;
	visibility: visible;
	border: none;
	border-bottom: 1px solid rgba(55, 53, 47, 0.09);
}

img {
	max-width: 100%;
}

@media only print {
	img {
		max-height: 100vh;
		object-fit: contain;
	}
}

@page {
	margin: 1in;
}

.collection-content {
	font-size: 0.875rem;
}

.column-list {
	display: flex;
	justify-content: space-between;
}

.column {
	padding: 0 1em;
}

.column:first-child {
	padding-left: 0;
}

.column:last-child {
	padding-right: 0;
}

.table_of_contents-item {
	display: block;
	font-size: 0.875rem;
	line-height: 1.3;
	padding: 0.125rem;
}

.table_of_contents-indent-1 {
	margin-left: 1.5rem;
}

.table_of_contents-indent-2 {
	margin-left: 3rem;
}

.table_of_contents-indent-3 {
	margin-left: 4.5rem;
}

.table_of_contents-link {
	text-decoration: none;
	opacity: 0.7;
	border-bottom: 1px solid rgba(55, 53, 47, 0.18);
}

table,
th,
td {
	border: 1px solid rgba(55, 53, 47, 0.09);
	border-collapse: collapse;
}

table {
	border-left: none;
	border-right: none;
}

th,
td {
	font-weight: normal;
	padding: 0.25em 0.5em;
	line-height: 1.5;
	min-height: 1.5em;
	text-align: left;
}

th {
	color: rgba(55, 53, 47, 0.6);
}

ol,
ul {
	margin: 0;
	margin-block-start: 0.6em;
	margin-block-end: 0.6em;
}

li > ol:first-child,
li > ul:first-child {
	margin-block-start: 0.6em;
}

ul > li {
	list-style: disc;
}

ul.to-do-list {
	text-indent: -1.7em;
}

ul.to-do-list > li {
	list-style: none;
}

.to-do-children-checked {
	text-decoration: line-through;
	opacity: 0.375;
}

ul.toggle > li {
	list-style: none;
}

ul {
	padding-inline-start: 1.7em;
}

ul > li {
	padding-left: 0.1em;
}

ol {
	padding-inline-start: 1.6em;
}

ol > li {
	padding-left: 0.2em;
}

.mono ol {
	padding-inline-start: 2em;
}

.mono ol > li {
	text-indent: -0.4em;
}

.toggle {
	padding-inline-start: 0em;
	list-style-type: none;
}

/* Indent toggle children */
.toggle > li > details {
	padding-left: 1.7em;
}

.toggle > li > details > summary {
	margin-left: -1.1em;
}

.selected-value {
	display: inline-block;
	padding: 0 0.5em;
	background: rgba(206, 205, 202, 0.5);
	border-radius: 3px;
	margin-right: 0.5em;
	margin-top: 0.3em;
	margin-bottom: 0.3em;
	white-space: nowrap;
}

.collection-title {
	display: inline-block;
	margin-right: 1em;
}

.simple-table {
	margin-top: 1em;
	font-size: 0.875rem;
	empty-cells: show;
}
.simple-table td {
	height: 29px;
	min-width: 120px;
}

.simple-table th {
	height: 29px;
	min-width: 120px;
}

.simple-table-header-color {
	background: rgb(247, 246, 243);
	color: black;
}
.simple-table-header {
	font-weight: 500;
}

time {
	opacity: 0.5;
}

.icon {
	display: inline-block;
	max-width: 1.2em;
	max-height: 1.2em;
	text-decoration: none;
	vertical-align: text-bottom;
	margin-right: 0.5em;
}

img.icon {
	border-radius: 3px;
}

.user-icon {
	width: 1.5em;
	height: 1.5em;
	border-radius: 100%;
	margin-right: 0.5rem;
}

.user-icon-inner {
	font-size: 0.8em;
}

.text-icon {
	border: 1px solid #000;
	text-align: center;
}

.page-cover-image {
	display: block;
	object-fit: cover;
	width: 100%;
	max-height: 30vh;
}

.page-header-icon {
	font-size: 3rem;
	margin-bottom: 1rem;
}

.page-header-icon-with-cover {
	margin-top: -0.72em;
	margin-left: 0.07em;
}

.page-header-icon img {
	border-radius: 3px;
}

.link-to-page {
	margin: 1em 0;
	padding: 0;
	border: none;
	font-weight: 500;
}

p > .user {
	opacity: 0.5;
}

td > .user,
td > time {
	white-space: nowrap;
}

input[type="checkbox"] {
	transform: scale(1.5);
	margin-right: 0.6em;
	vertical-align: middle;
}

p {
	margin-top: 0.5em;
	margin-bottom: 0.5em;
}

.image {
	border: none;
	margin: 1.5em 0;
	padding: 0;
	border-radius: 0;
	text-align: center;
}

.code,
code {
	background: rgba(135, 131, 120, 0.15);
	border-radius: 3px;
	padding: 0.2em 0.4em;
	border-radius: 3px;
	font-size: 85%;
	tab-size: 2;
}

code {
	color: #eb5757;
}

.code {
	padding: 1.5em 1em;
}

.code-wrap {
	white-space: pre-wrap;
	word-break: break-all;
}

.code > code {
	background: none;
	padding: 0;
	font-size: 100%;
	color: inherit;
}

blockquote {
	font-size: 1.25em;
	margin: 1em 0;
	padding-left: 1em;
	border-left: 3px solid rgb(55, 53, 47);
}

.bookmark {
	text-decoration: none;
	max-height: 8em;
	padding: 0;
	display: flex;
	width: 100%;
	align-items: stretch;
}

.bookmark-title {
	font-size: 0.85em;
	overflow: hidden;
	text-overflow: ellipsis;
	height: 1.75em;
	white-space: nowrap;
}

.bookmark-text {
	display: flex;
	flex-direction: column;
}

.bookmark-info {
	flex: 4 1 180px;
	padding: 12px 14px 14px;
	display: flex;
	flex-direction: column;
	justify-content: space-between;
}

.bookmark-image {
	width: 33%;
	flex: 1 1 180px;
	display: block;
	position: relative;
	object-fit: cover;
	border-radius: 1px;
}

.bookmark-description {
	color: rgba(55, 53, 47, 0.6);
	font-size: 0.75em;
	overflow: hidden;
	max-height: 4.5em;
	word-break: break-word;
}

.bookmark-href {
	font-size: 0.75em;
	margin-top: 0.25em;
}

.sans { font-family: ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol"; }
.code { font-family: "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace; }
.serif { font-family: Lyon-Text, Georgia, ui-serif, serif; }
.mono { font-family: iawriter-mono, Nitti, Menlo, Courier, monospace; }
.pdf .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK JP'; }
.pdf:lang(zh-CN) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK SC'; }
.pdf:lang(zh-TW) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK TC'; }
.pdf:lang(ko-KR) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK KR'; }
.pdf .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK JP'; }
.pdf:lang(zh-CN) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC'; }
.pdf:lang(zh-TW) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK TC'; }
.pdf:lang(ko-KR) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK KR'; }
.pdf .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK JP'; }
.pdf:lang(zh-CN) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK SC'; }
.pdf:lang(zh-TW) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK TC'; }
.pdf:lang(ko-KR) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK KR'; }
.pdf .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK JP'; }
.pdf:lang(zh-CN) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC'; }
.pdf:lang(zh-TW) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK TC'; }
.pdf:lang(ko-KR) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK KR'; }
.highlight-default {
	color: rgba(55, 53, 47, 1);
}
.highlight-gray {
	color: rgba(120, 119, 116, 1);
	fill: rgba(120, 119, 116, 1);
}
.highlight-brown {
	color: rgba(159, 107, 83, 1);
	fill: rgba(159, 107, 83, 1);
}
.highlight-orange {
	color: rgba(217, 115, 13, 1);
	fill: rgba(217, 115, 13, 1);
}
.highlight-yellow {
	color: rgba(203, 145, 47, 1);
	fill: rgba(203, 145, 47, 1);
}
.highlight-teal {
	color: rgba(68, 131, 97, 1);
	fill: rgba(68, 131, 97, 1);
}
.highlight-blue {
	color: rgba(51, 126, 169, 1);
	fill: rgba(51, 126, 169, 1);
}
.highlight-purple {
	color: rgba(144, 101, 176, 1);
	fill: rgba(144, 101, 176, 1);
}
.highlight-pink {
	color: rgba(193, 76, 138, 1);
	fill: rgba(193, 76, 138, 1);
}
.highlight-red {
	color: rgba(212, 76, 71, 1);
	fill: rgba(212, 76, 71, 1);
}
.highlight-gray_background {
	background: rgba(241, 241, 239, 1);
}
.highlight-brown_background {
	background: rgba(244, 238, 238, 1);
}
.highlight-orange_background {
	background: rgba(251, 236, 221, 1);
}
.highlight-yellow_background {
	background: rgba(251, 243, 219, 1);
}
.highlight-teal_background {
	background: rgba(237, 243, 236, 1);
}
.highlight-blue_background {
	background: rgba(231, 243, 248, 1);
}
.highlight-purple_background {
	background: rgba(244, 240, 247, 0.8);
}
.highlight-pink_background {
	background: rgba(249, 238, 243, 0.8);
}
.highlight-red_background {
	background: rgba(253, 235, 236, 1);
}
.block-color-default {
	color: inherit;
	fill: inherit;
}
.block-color-gray {
	color: rgba(120, 119, 116, 1);
	fill: rgba(120, 119, 116, 1);
}
.block-color-brown {
	color: rgba(159, 107, 83, 1);
	fill: rgba(159, 107, 83, 1);
}
.block-color-orange {
	color: rgba(217, 115, 13, 1);
	fill: rgba(217, 115, 13, 1);
}
.block-color-yellow {
	color: rgba(203, 145, 47, 1);
	fill: rgba(203, 145, 47, 1);
}
.block-color-teal {
	color: rgba(68, 131, 97, 1);
	fill: rgba(68, 131, 97, 1);
}
.block-color-blue {
	color: rgba(51, 126, 169, 1);
	fill: rgba(51, 126, 169, 1);
}
.block-color-purple {
	color: rgba(144, 101, 176, 1);
	fill: rgba(144, 101, 176, 1);
}
.block-color-pink {
	color: rgba(193, 76, 138, 1);
	fill: rgba(193, 76, 138, 1);
}
.block-color-red {
	color: rgba(212, 76, 71, 1);
	fill: rgba(212, 76, 71, 1);
}
.block-color-gray_background {
	background: rgba(241, 241, 239, 1);
}
.block-color-brown_background {
	background: rgba(244, 238, 238, 1);
}
.block-color-orange_background {
	background: rgba(251, 236, 221, 1);
}
.block-color-yellow_background {
	background: rgba(251, 243, 219, 1);
}
.block-color-teal_background {
	background: rgba(237, 243, 236, 1);
}
.block-color-blue_background {
	background: rgba(231, 243, 248, 1);
}
.block-color-purple_background {
	background: rgba(244, 240, 247, 0.8);
}
.block-color-pink_background {
	background: rgba(249, 238, 243, 0.8);
}
.block-color-red_background {
	background: rgba(253, 235, 236, 1);
}
.select-value-color-pink { background-color: rgba(245, 224, 233, 1); }
.select-value-color-purple { background-color: rgba(232, 222, 238, 1); }
.select-value-color-green { background-color: rgba(219, 237, 219, 1); }
.select-value-color-gray { background-color: rgba(227, 226, 224, 1); }
.select-value-color-opaquegray { background-color: rgba(255, 255, 255, 0.0375); }
.select-value-color-orange { background-color: rgba(250, 222, 201, 1); }
.select-value-color-brown { background-color: rgba(238, 224, 218, 1); }
.select-value-color-red { background-color: rgba(255, 226, 221, 1); }
.select-value-color-yellow { background-color: rgba(253, 236, 200, 1); }
.select-value-color-blue { background-color: rgba(211, 229, 239, 1); }

.checkbox {
	display: inline-flex;
	vertical-align: text-bottom;
	width: 16;
	height: 16;
	background-size: 16px;
	margin-left: 2px;
	margin-right: 5px;
}

.checkbox-on {
	background-image: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%2216%22%20height%3D%2216%22%20viewBox%3D%220%200%2016%2016%22%20fill%3D%22none%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%3Crect%20width%3D%2216%22%20height%3D%2216%22%20fill%3D%22%2358A9D7%22%2F%3E%0A%3Cpath%20d%3D%22M6.71429%2012.2852L14%204.9995L12.7143%203.71436L6.71429%209.71378L3.28571%206.2831L2%207.57092L6.71429%2012.2852Z%22%20fill%3D%22white%22%2F%3E%0A%3C%2Fsvg%3E");
}

.checkbox-off {
	background-image: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%2216%22%20height%3D%2216%22%20viewBox%3D%220%200%2016%2016%22%20fill%3D%22none%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%3Crect%20x%3D%220.75%22%20y%3D%220.75%22%20width%3D%2214.5%22%20height%3D%2214.5%22%20fill%3D%22white%22%20stroke%3D%22%2336352F%22%20stroke-width%3D%221.5%22%2F%3E%0A%3C%2Fsvg%3E");
}
	
</style></head><body><article id="9b8f1559-db4d-4254-9d95-31f3571c1de0" class="page sans"><header><img class="page-cover-image" src="https://www.notion.so/images/page-cover/gradients_10.jpg" style="object-position:center 40%"/><div class="page-header-icon page-header-icon-with-cover"><span class="icon">💡</span></div><h1 class="page-title">Andy H. Tan’s Portfolio</h1></header><div class="page-body"><p id="dc1f8efc-5759-44b3-a6b0-ab42bacfbd51" class="">
</p><figure id="e13fe278-c577-4a50-be74-8bc641863ffd" class="image"><a href="Andy%20H%20Tan%E2%80%99s%20Portfolio%20e13fe278c5774a50be748bc641863ffd/Cover.png"><img style="width:1184px" src="Andy%20H%20Tan%E2%80%99s%20Portfolio%20e13fe278c5774a50be748bc641863ffd/Cover.png"/></a></figure><p id="e1446cff-4978-47e6-a415-9e239a571800" class="">
</p><hr id="eb08b226-20c1-4a5a-9d6d-37b8934c17d5"/><h3 id="6590afe5-330c-44b9-a109-5577aa11d794" class="">Click on any of the toggles ⬇ below to view more details about my experience! 😄</h3><hr id="23939c86-489a-46bd-b95a-47dccdb94670"/><h2 id="14dd5592-1328-4810-8bed-8742f41e3fce" class="">💼 Work Experience </h2><ul id="40a93156-31b6-4e53-b2e9-06fc004ddfa5" class="toggle"><li><details open=""><summary><strong>Data Analyst, Analytics &amp; Data Governance</strong> @Barton Associates, Inc.</summary><p id="f3196f2d-8723-4c01-b725-79c6f0e31795" class=""><em>June 2021 - Present</em></p><h3 id="4dfd4583-f0b9-41a1-a7a0-81ab644ff8ef" class="">Description</h3><p id="0590ab4b-1e57-4703-9a45-9296d379ff6d" class="">At Barton, we work together to bridge the national healthcare staffing shortage by connecting health facilities with the right clinicians through domain knowledge and technology excellence. </p><p id="5e133abe-12c2-4ae2-8f21-9b3863c5b9f6" class="">I am collaborating with 10+ departments across the organization, including Marketing, Finance, Sales, Risk &amp; Legal to initiate various data projects and facilitate ongoing data needs. As a member of the Data Strategy team, I am providing ad-hoc and periodic analysis on current sales performance, financial/metrics performance on our day-to-day sales operations. I’ve also created company-wide data best-practice standards to facilitate historical data projects and future data-initiatives.</p><h3 id="e0bc18d8-b57a-4c02-b8c7-17b54dc213b3" class="">About</h3><blockquote id="2236ac40-b982-4886-98ec-e30ff8c2e476" class=""><mark class="highlight-gray"><em>Barton &amp; Associates, Inc. is the Locum Tenens jobs and staffing experts for healthcare professionals/organizations. </em></mark></blockquote><p id="2df31e51-34d5-42a0-8d23-f3eb158eb3c6" class="">
</p></details></li></ul><ul id="7afdfc09-fda6-4b83-b861-ee6de9f1fa32" class="toggle"><li><details open=""><summary><strong>Client Project, Business Research</strong> @Grubhub</summary><p id="1e8e81f7-1383-4fa8-adf7-85e6329c8a88" class=""><em>January 2021 - May 2021</em></p><h3 id="2624ab22-b371-4f3d-b288-dfe3610b54c2" class=""><strong>Description</strong></h3><p id="c234c88d-6a4b-46e6-b103-05162de3e435" class="">Business Research &amp; Methods is a Suffolk-exclusive curricular courses, where the Marketing Department brought in industry leading companies, including Pandora, TJMaxx to help Suffolk Rams gain real-world exposures in business research and data analysis.</p><p id="de426658-8f6a-4e42-adc4-7546c7dc0121" class="">During the curricular, me and our team work closely with our instructor and the Grubhub research team to define research thesis: How can Grubhub differentiate itself from major competitors and how can Grubhub explore new business targets &amp; retain existing customers. I served as the team lead to our group,  finalized our 1-1 interview questions set, analyzed over 500 survey results using SPSS &amp; Excel. After spending over 100 hours in research, survey, analysis, business proposal drafting, we made it through 5 rounds of selection among 100 teams. We had successfully been selected as the 5 finalist to present to Grubhub, and won the second-ranking. </p><h3 id="8debbb52-bbea-4f40-b08a-48f3075feceb" class="">About</h3><blockquote id="e65bbdaf-fbd8-4626-9a51-0564a537e240" class=""><mark class="highlight-gray"><em>Grubhub (Now part of Just Eat </em></mark><mark class="highlight-gray"><em><a href="http://Takeaway.com">Takeaway.com</a></em></mark><mark class="highlight-gray"><em>) is a global online food delivery marketplace, featuring more than 320,000 restaurant partners in over 4,000 U.S. cities. </em></mark></blockquote><p id="aad2b2b9-eab4-485c-abda-d86482b256f9" class="">
</p></details></li></ul><ul id="2528fb29-059a-49f5-acc2-828316fb0a46" class="toggle"><li><details open=""><summary><strong>Business Analysis, Product Management</strong> @Agero, Inc.</summary><p id="661957be-cad4-4593-91ee-3e3347ce2be9" class=""><em>June 2021 - August 2021</em></p><h3 id="afaba52b-043b-49d8-9a65-8f8902d3f6e9" class=""><strong>Description</strong></h3><p id="c9349267-bb4e-421e-881d-c8b75af9cc16" class="">During my time at Agero, I worked under the product management director as an interdisciplinary liaison, translating business needs into technical scopes. I&#x27;ve conducted 20+ ad-hoc analysis using Snowflake and Excel to explore potential tow star-end destinations to solicitate potential service providers. I interviewed more than 10 service agents to observe potential data needs and streamlined existing logging procedures, resulting in a 15% increase of log time proficiency. I&#x27;ve also researched the existing roadside statistics to make recommendations on product feature improvements.</p><h3 id="115b5663-09e1-464b-a7c4-dc00f3913d07" class="">About</h3><blockquote id="6aa015bb-e236-431f-8dd6-5a74323be6ae" class=""><mark class="highlight-gray"><em>Powered by Swoop, Agero is the nation’s largest wholesale provider of roadside service, the leading force of solution digitalization, driver assistance, consumer affair research &amp; incident management, servicing over 115 million drivers every year with a daily volume of 30k dispatches.</em></mark></blockquote><p id="278ee1a8-5b52-4a76-be9b-3b177617d2e9" class="">
</p></details></li></ul><ul id="85ebf723-223d-4ff2-b30a-7dcfe24c9385" class="toggle"><li><details open=""><summary><strong>Assistant Business Analyst, Enrollment Management</strong> @Bunker Hill Community College</summary><p id="4067f8ee-a783-4860-8044-423f9c69e1f6" class=""><em>September 2019 - May 2020</em></p><h3 id="01c5f8f4-12b9-482c-ac60-85f668554098" class="">Description</h3><p id="0a416323-3c47-4a9e-b61c-6d6e55fd5190" class="">Enrollment Management is the central office for BHCC&#x27;s strategic planning on academic recruitment, student retention and institution research.</p><p id="0b602cf6-5c9a-4db1-a765-32ad71dab7ad" class="">After working at the Registrar’s office at Bunker Hill Community College, I further explored my passion in data and strategic planning by joining Enrollment Management. We’ve improved the student engage rate to 83% by coded the CRM communication plan (email + text services) for academic services. I’ve also worked on 25+ analysis on student engagement research, delivered our enrollment goal to 90% by surveying, interviewing students and staff members. We work together with a holistic approach, joining forces from various divisions, including Advising, Financial Service, Institution Research to improve the overall experience for both students and faculties. </p><h3 id="50b2da13-046e-497d-bffe-b3ca5aae74df" class="">About</h3><blockquote id="b5bc7617-22fe-4a35-a588-1043415adcc2" class=""><mark class="highlight-gray"><em>Bunker Hill Community College (BHCC) is the largest community college in Massachusetts, serving more than 19,000 students annually. Member of the New England Association of Schools and Colleges (NEASC).</em></mark></blockquote></details></li></ul><p id="512fe67f-5a72-4b32-ac7a-f79c9bd93a88" class="">
</p><hr id="c89e1e4c-b890-4f6b-8185-afb24162c55f"/><h2 id="10018327-ebeb-4723-a0a9-07c9f8292514" class="">📖 Education</h2><ul id="00a8e55d-9ab6-43b7-87ea-9c312d2c0ac2" class="toggle"><li><details open=""><summary><strong>BSBA, Big Data &amp; Business Analytics</strong> @Suffolk University</summary><p id="164b33e5-bc65-4c8a-b78a-8548d8737410" class="">Bachelors Degree of Science and Business Administration, <em>September 2019 - May 2021</em></p><p id="c8831825-1227-4bc1-b283-6619d18fbb0a" class="">Honors: Dean’s List for all semesters attended; Summa Cumme laude</p><p id="54695a8c-5377-468c-ac41-20f004fe12b7" class="">
</p></details></li></ul><ul id="d6a7debd-6e86-4d36-a2a0-c68952c6a688" class="toggle"><li><details open=""><summary><strong>AS, Finance &amp; Information Technology</strong> @Bunker Hill Community College</summary><p id="f6cd7dbe-9344-4e17-8b35-31de9ca03e39" class="">Associate Degree in Science, <em>September 2016 - May 2019</em></p><p id="c650f2af-b31a-47fe-b75e-b430b924eb43" class="">Honors: Dean’s List for all semesters attended. </p></details></li></ul><p id="0d4e0db9-0ace-4ebc-9a68-0977c94910f6" class="">
</p><hr id="c589c662-4c9b-4739-9908-9c131ed631d3"/><h2 id="302b6629-0d78-44d9-9464-00cdca0d4b04" class=""><strong>🛠</strong> Projects (Under Construction..)</h2><ul id="d883bc39-007c-4234-9d70-aa1d32f259d3" class="toggle"><li><details open=""><summary>COVID-19 Dashboard @Tableau</summary><figure id="918b3800-66cc-4a01-ab99-d9df58e34aaa"><a href="https://public.tableau.com/app/profile/andy.tan2390/viz/Test-Book1_16468373273590/U_S_Dashboard" class="bookmark source"><div class="bookmark-info"><div class="bookmark-text"><div class="bookmark-title"></div></div><div class="bookmark-href"><img src="https://public.tableau.com/app/favicon.ico" class="icon bookmark-icon"/>https://public.tableau.com/app/profile/andy.tan2390/viz/Test-Book1_16468373273590/U_S_Dashboard</div></div></a></figure></details></li></ul><p id="aaa616ba-d19d-4ce0-b2c0-90edb956ddb9" class="">
</p><hr id="d4762c9b-b423-4f7f-ba07-36e79d20586d"/><h2 id="1ce43ad5-e736-4ca0-8740-9a38217d78e6" class="">☎️ Contact</h2><p id="56abd3c9-d1c9-41bb-84a0-817a90d3eb83" class="">📧 Email: <a href="mailto:haijie.tan-work@hotmail.com">haijie.tan-work@hotmail.com</a></p><p id="a8db974b-127e-4d5b-9587-dfc8a9bc7b71" class="">🖇️ LinkedIn: <a href="https://www.linkedin.com/in/haijie-tan/">https://www.linkedin.com/in/haijie-tan/</a> </p><p id="100d7d24-4f94-4d75-af43-2466e824ab24" class="">📊 Tableau: <a href="https://public.tableau.com/app/profile/andy.tan2390">https://public.tableau.com/app/profile/andy.tan2390</a></p><p id="86780bcf-fb9c-4166-83f6-637a9d4046bc" class="">
</p></div></article></body></html>
