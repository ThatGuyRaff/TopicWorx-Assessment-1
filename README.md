# TopicWorx-Assessment-1
Assessment:  Visualise the supplied data in a graph of some sort programmatically. You may use any tools or languages that you would like (please do not use Excel). When submitting your code, please provide a detailed explanation of how your code works. Also, please detail any external libraries that may be required for your code to work

The external libraries required for this code to work are:

Chart.js library: This library is used to create the chart. It can be added to the project by including the following script tag in the HTML file.

<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>

Here is the complete code with the data included:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>COVID-19 Chart</title>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
</head>
<body>
    <canvas id="chart"></canvas>
    <script>
        const data = [
            {
                "Date": "2020/03/05",
                "Total Confirmed Cases": 1,
                "Total Deaths": 0,
                "Total Recovered": 0,
                "Active Cases": 1,
                "Daily Confirmed Cases": 0,
                "Daily  deaths": 0
            },
            {
                "Date": "2
