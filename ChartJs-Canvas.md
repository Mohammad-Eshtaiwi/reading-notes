# Canvas

\<canvas> tag used to create an element that can be used to draw graphs,shapes, or any graphical stuff you need and it mainly used the the 2d graphics

```
const canvas = document.getElementById('canvas');
const ctx = canvas.getContext('2d');

ctx.fillStyle = 'green';
ctx.fillRect(10, 10, 150, 100);
```

This code will create a canvas that has a green rectangle in it.

first 2 parameters of fillRect specify how far from the x and y the shape will be and the last 2 parameters will define the width and the hight of our rectangle

# ChartJs

it is a JavaScript plugin that used to display your data by modern way.

```
<canvas id="buyers" width="600" height="400"></canvas>
<script>
            var buyerData = {
                labels : ["January","February","March","April","May","June"],
                datasets : [
                {
                    fillColor : "rgba(172,194,132,0.4)",
                    strokeColor : "#ACC26D",
                    pointColor : "#fff",
                    pointStrokeColor : "#9DB86D",
                    data : [203,156,99,251,305,247]
                }
            ]
            }
            // get line chart canvas
            var buyers = document.getElementById('buyers').getContext('2d');
            // draw line chart
            new Chart(buyers).Line(buyerData);</script>
```

we need to add a canvas to our html page then using the ChartJs we create a new chart and pass the element and the data then our data will appear.
