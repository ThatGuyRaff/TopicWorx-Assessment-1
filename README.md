# TopicWorx-Assessment-1
Assessment:  Visualise the supplied data in a graph of some sort programmatically. 
You may use any tools or languages that you would like (please do not use Excel). 
When submitting your code, please provide a detailed explanation of how your code works. 
Also, please detail any external libraries that may be required for your code to work

///////////////////////////////////////////////////

The external libraries required for this code to work are:

Chart.js library: This library is used to create the chart. It can be added to the project by including the following script tag in the HTML file.

<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>

/////////////////////////////////////////////////////

This code creates a line chart using the Chart.js library. The data for the chart is provided in the form of an array of objects. Each object represents a day and contains the total number of confirmed cases, total deaths, and other relevant data points.

The code first defines the data array, which contains the data points. It then defines the chartData object, which is used to configure the chart. The labels property of the chartData object is set to an array containing the dates from the data. The data property of the chartData object is set to an array containing the total number of confirmed cases for each day. The backgroundColor and borderColor properties of the chartData object are set to define the colors of the chart.

The config object is then defined to configure the chart. The type property of the config object is set to 'line', indicating that a line chart should be created. The data property of the config object is set to the chartData object. The options property of the config object is set to an object that configures the chart. The scales property of the options object is set to an object that configures the y-axis of the chart. The beginAtZero property of the scales object is set to true, indicating that the y-axis should start at zero.

Finally, the chart object is created by passing the canvas element and the config object to the Chart constructor. This creates the chart and displays it on the web page.

/////////////////////////////////////////////////////
