From simple line charts to complex hierarchical tree maps, the Google Chart gallery provides a large number of ready-to-use chart types:

Scatter Chart
Line Chart
Bar / Column Chart
Area Chart
Pie Chart
Donut Chart
Org Chart
Map / Geo Chart


How to Use Google Chart?
1. Add a <div> element (with a unique id) in the HTML where you want to display the chart:

<div id="myChart" style="max-width:700px; height:400px"></div>
2. Add a link to the charts loader:

<script src="https://www.gstatic.com/charts/loader.js"></script>
3. Load the Graph API, and add the function to run when the API is loaded:

<script>
google.charts.load('current',{packages:['corechart']});
google.charts.setOnLoadCallback(drawChart);

// Your Function
function drawChart() {
...
}
</script>