Least-Restrictive-Environment
=============================

This project is used for professional development the special education field's development of IEP's (Individual Education Programs).
<!DOCTYPE html>
<html>
    <head>
        <title>Let's Draw!</title>
        <link rel='stylesheet' type='text/css' href='stylesheet.css'/>
    </head>
    <body>
        <canvas id="canvas" width="200" height="200">
            This text is displayed if your browser does not support HTML5 Canvas.
        </canvas>
        <script type='text/javascript' src='script.js'></script>
    </body>
</html>

canvas {
    border: 1px dotted black;
}
var my_canvas = document.getElementById("canvas");
var context = my_canvas.getContext("2d");

context.beginPath();
context.arc(95, 85, 40, 0, 2*Math.PI);
context.stroke();
context.beginPath();
context.strokeRect(10, 10, 50, 20);
context.stroke();
context.fillRect(10, 10, 50, 20);
context.fillRect = "black";
context.fillStyle = "black";
context.font = "30px Garamond";
context.fillText("Hello!",15,175);

