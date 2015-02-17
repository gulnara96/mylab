# mylab
<html>
<head>
<title>Canvas</title>
<meta charset="utf-8">
</head>
<body>
<em><h2>Мухаметшина Гульнара</h2></em>
</body>
<canvas id="myCanvas" width="700" height="700">
<p>
<script type="text/javascript">
var myCanvas = document.getElementById('myCanvas');
var ctx = myCanvas.getContext('2d');
ctx.beginPath();
//Рисуем прямоугольник
ctx.fillStyle = '#000000'; 
ctx.strokeStyle = '#FFFFFF'; 
ctx.lineWidth = 4;
ctx.fillRect (50, 50, 250, 250);
ctx.strokeRect(50, 50, 250, 250);
ctx.strokeStyle = 'black'; 
ctx.lineWidth = 5;
//Рисуем окружность
ctx.arc(175, 180, 30, 0, Math.PI*2, true);
ctx.closePath();
ctx.fillStyle = 'white';
ctx.fill();
ctx.stroke();
ctx.fillStyle = '#FFFFFF'; 
ctx.strokeStyle = '#000000'; 
ctx.lineWidth = 4;

ctx.beginPath();
ctx.scale(1,2);
ctx.strokeStyle = '#000000';
ctx.lineWidth = 4;
ctx.arc(175, 125, 10, 0, Math.PI*2, true);
ctx.fillStyle = 'white';
ctx.fill();
ctx.stroke();
ctx.fillStyle = '#FFFFFF'; 
ctx.strokeStyle = '#000000'; 
ctx.lineWidth = 4;
ctx.resetTransform();
ctx.closePath();

ctx.fillRect (80, 80, 100, 30);
ctx.strokeRect(80, 80, 100, 30);
ctx.strokeStyle = 'black'; 
ctx.lineWidth = 5;

ctx.fillStyle = '#FFFFFF'; 
ctx.strokeStyle = '#FFFFFF'; 
ctx.lineWidth = 4;
ctx.fillRect (280, 120, 20, 10);
ctx.strokeRect(280, 120, 20, 10);
ctx.strokeStyle = 'black'; 
ctx.lineWidth = 5;

ctx.beginPath();
ctx.moveTo(280,50);
ctx.lineTo(300,50);
ctx.lineTo(300,70);
ctx.fillStyle = 'white';
ctx.fill();ctx.closePath();


</script>
</script>

</p>
</canvas>
</body>
</html>

