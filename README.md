# d3-visualization
Basic demonstration of D3 script for creating graph using a JSON object.
  <div id="chart1" style="height:300px;"></div>
  <div class="chart2" style="height:150px;"></div>
  <div class="chart3" style="height:150px;"></div>

  
    var chart1 = c3.generate({
      bindto: '#chart1',
      data: {
        columns: [
          ['data1', 130, 210, 120, 440, 250, 350]
        ]
      }
    });
    var chart2 = c3.generate({
      bindto: '.chart2',
      data: {
        columns: [
          ['data1', 30, 200, 100, 400, 150, 250]
        ]
      }
    });
    var chart3 = c3.generate({
      bindto: document.getElementsByClassName('chart3')[0],
      data: {
        columns: [
          ['data1', 30, 200, 100, 400, 150, 250]
        ]
      }
    });
  
