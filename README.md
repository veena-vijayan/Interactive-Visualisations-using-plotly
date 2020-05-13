# Interactive-Visualisations-using-plotly
Interactive Visualisation using Plotly in python

The [plotly](https://plotly.com/python/getting-started/) Python library is an interactive, open-source plotting library that supports over 40 unique chart types covering a wide range of statistical, financial, geographic, scientific, and 3-dimensional use-cases.

![Alt Text](https://miro.medium.com/max/1600/1*K6LaqTMhc46R8QQuEIczxw.gif)

----------------------------------------------------------------------------------------

Plotly figures are interactive when viewed in a web browser - you can hover over data points, pan and zoom axes, and show and hide traces by clicking or double-clicking on the legend.

The aim of this notebook are:<br />
<ol type=I>
<li>Plot various charts using plotly.</li>
<li>Adding dropdowns and axis sliders to the charts.</li>
<li>Save the visualisations as html as stand-alone interactive visualisations.</li>
<li>Add multiple plots (subplots) to the same space.</li>
</ol>

Python 3.7.6 is used to develop the code.

A sample sales dataset is created with two columns:
<ol type=a>
<li><strong><em>date</em></strong>: date of purchase of a particular category.</li>
<li><strong><em>category</em></strong>: category of purchase – there are three category of purchase CategoryA, CategoryB and CategoryC.</li>
</ol>

This dataset will help us plot most of the charts. 

The notebook is divided into four sections each covering the topics mentioned previously. The major charts plotted are:
<ol>
  <li>Pie and Donut chart</li>
  <li>Bar chart</li>
  <li>Line chart</li>
  <li>Table</li>
  <li>Histogram and Distplots</li>
  <li>Box Plot</li>
  <li>Heat Map</li>
  <li>World Map</li>
</ol>

This will enable you to easily replicate most of the charts in short span of time. Adding subplots to the graph are also worked out here. 

Another major use case of plotly is that you can export figures either to static image file formats like PNG, JEPG, SVG or PDF or you can export them to HTML files which can be opened in a browser. The HTML formats help us retain the interactive element of the plotly graph. This is also addressed in this notebook.
