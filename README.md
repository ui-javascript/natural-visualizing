
特点优势
============

>1. ECharts，一个  <mark> 纯Javascript</mark> 的图表库，可以流畅的运行在 PC 和移动设备上，兼容当前<mark>绝大部分浏览器</mark>（IE8/9/10/11，Chrome，Firefox，Safari等），底层依赖轻量级的 Canvas 类库 ZRender
>2. 提供直观，生动，可交互，可高度<mark>个性化定制</mark>的数据可视化图表
>3. ECharts 3 中更是加入了更多丰富的交互功能以及更多的可视化效果，并且对<mark>移动端</mark>做了深度的优化


代办事项
============

- [ ] JS导出EXCEL的功能，官方好像并没有给出，github上面找了一个，但还需要调整


导出插件
============

tableExport.jquery.plugin

<h3>Export HTML Table to</h3>
<ul>
<li> JSON
<li> XML
<li> PNG
<li> CSV
<li> TXT
<li> SQL
<li> MS-Word
<li> Ms-Excel
<li> Ms-Powerpoint
<li> PDF
</ul>

Installation
============
jquery Plugin<BR>
&lt;script type="text/javascript" src="tableExport.js"><BR>
&lt;script type="text/javascript" src="jquery.base64.js"><BR>
<BR>
PNG Export
==========
&lt;script type="text/javascript" src="html2canvas.js">

PDF Export
==========
&lt;script type="text/javascript" src="jspdf/libs/sprintf.js"><BR>
&lt;script type="text/javascript" src="jspdf/jspdf.js"><BR>
&lt;script type="text/javascript" src="jspdf/libs/base64.js"><BR>

Usage
======
onClick ="$('#tableID').tableExport({type:'pdf',escape:'false'});"<BR>

Options
=======
separator: ','<BR>
ignoreColumn: [2,3],<BR>
tableName:'yourTableName'<BR>
type:'csv'<BR>
pdfFontSize:14<BR>
pdfLeftMargin:20<BR>
escape:'true'<BR>
htmlContent:'false'<BR>
consoleLog:'false' <BR>
