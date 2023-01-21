
<html>
<head>
    <script type="text/javascript">
        var canvas;
        var ctx;
        var sinBtn;
        var cosBtn;
        var clearBtn;

        function drawSin() {
            ctx.beginPath();
            ctx.moveTo(0, canvas.height/2);
            for (var x = 0; x < canvas.width; x++) {
                ctx.lineTo(x, canvas.height/2 - Math.sin(x/10)*canvas.height/2);
            }
            ctx.stroke();
        }

        function drawCos() {
            ctx.beginPath();
            ctx.moveTo(0, canvas.height/2);
            for (var x = 0; x < canvas.width; x++) {
                ctx.lineTo(x, canvas.height/2 - Math.cos(x/10)*canvas.height/2);
            }
            ctx.stroke();
        }

        function drawAxes() {
            ctx.strokeStyle = "black";
            ctx.beginPath();
            ctx.moveTo(0, canvas.height/2);
            ctx.lineTo(canvas.width, canvas.height/2);
            ctx.moveTo(canvas.width/2, 0);
            ctx.lineTo(canvas.width/2, canvas.height);
            ctx.stroke();
        }

        function clearCanvas() {
            ctx.clearRect(0, 0, canvas.width, canvas.height);
            drawAxes();
        }

        function init() {
            canvas = document.getElementById("graph");
            ctx = canvas.getContext("2d");
            sinBtn = document.getElementById("sinBtn");
            cosBtn = document.getElementById("cosBtn");
            clearBtn = document.getElementById("clearBtn");
            sinBtn.addEventListener("click", drawSin);
            cosBtn.addEventListener("click", drawCos);
            clearBtn.addEventListener("click", clearCanvas);
            drawAxes();
        }

        window.onload = init;
    </script>
</head>
<body>
    <canvas id="graph" width="500" height="500"></canvas>
    <br>
    <button id="sinBtn">Tracer Sinus</button>
    <button id="cosBtn">Tracer Cosinus</button>
    <button id="clearBtn">Effacer</button>
    
      <footer>
        <p>Copyright © [2023] [Lakbir Elmadani]</p>
      </footer>
</body>
</html>

