Chart.js is an free JavaScript library for making HTML-based charts. It is one of the simplest visualization libraries for JavaScript, and comes with the many built-in chart types:

Scatter Plot
Line Chart
Bar Chart
Pie Chart
Donut Chart
Bubble Chart
Area Chart
Radar Chart
Mixed Chart

How to Use Chart.js?
1. Add a link to the providing CDN (Content Delivery Network):

<script
src="https://cdnjs.cloudflare.com/ajax/libs/Chart.js/2.9.4/Chart.js">
</script>
2. Add a <canvas> to where in the HTML you want to draw the chart:

<canvas id="myChart" style="width:100%;max-width:700px"></canvas>
The canvas element must have a unique id.

Typical Bar Chart Syntax:
const myChart = new Chart("myChart", {
  type: "bar",
  data: {},
  options: {}
});


Typical Line Chart Syntax:
const myChart = new Chart("myChart", {
  type: "line",
  data: {},
  options: {}
});