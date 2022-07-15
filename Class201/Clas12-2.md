# Drawing Shapes with Canvas  
[Drawing Shapes with Canvas](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_shapes)  

**The grid** allows one to draw various shapes

<details><summary>Rectangles & Squares</summary><p>


`fillRect(x, y, width, height)`
*Filled*

`strokeRect(x, y, width, height)`
*Outline*

`clearRect(x, y, width, height)`
*Transparent*


*Example*
```javascript
function draw() {
  var canvas = document.getElementById('canvas');
  if (canvas.getContext) {
    var ctx = canvas.getContext('2d');

    ctx.fillRect(25, 25, 100, 100);
    ctx.clearRect(45, 45, 60, 60);
    ctx.strokeRect(50, 50, 50, 50);
  }
}
```
</p></details> 
<details><summary>Paths</summary><p>

A **Path** is a list of points, connected by segments of lines 

1. Create the path.
  `beginPath()`
2. Use drawing commands to draw into path 
  `Path methods`
  `closePath()`
3. Render by stroke or fill  
  `stroke()`
  `fill()`
  </p></details>
  
  and more...
