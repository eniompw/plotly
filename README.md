# Plotly

```
  <!DOCTYPE html>
  <html>
  <script src="https://cdn.plot.ly/plotly-latest.min.js"></script>
  <body>
  <div id="myPlot" style="width:100%;max-width:700px"></div>
  
  <script>
  const data = [{
    x:["Italy", "France", "Spain", "USA", "Argentina"],
    y:[55, 49, 44, 24, 15],
    type:"bar",
    marker: {color:"blue"}
  }];
  
  const layout = {title:"World Wide Wine Production"};
  Plotly.newPlot("myPlot", data, layout);
  </script>
  
  </body>
  </html>
```

[W3 Plotly](https://www.w3schools.com/js/tryit.asp?filename=tryplotly_bars)
