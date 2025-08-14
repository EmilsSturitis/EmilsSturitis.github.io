---
layout: post
title: "Using Plotly in Jekyll"
---

<script src="https://cdn.plot.ly/plotly-latest.min.js"></script>

<div id="my-plot" style="width:100%;max-width:700px;"></div>

<script>
  var trace1 = {
    x: [1, 2, 3, 4],
    y: [10, 15, 13, 17],
    mode: 'markers'
  };

  var data = [trace1];

  var layout = {
    title: 'Basic Scatter Plot',
    xaxis: {
      title: 'X Axis'
    },
    yaxis: {
      title: 'Y Axis'
    }
  };

  Plotly.newPlot('my-plot', data, layout);
</script>