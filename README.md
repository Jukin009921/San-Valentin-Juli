<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>¿Quieres ser mi San Valentín? 💖</title>
    <style>
        body {
            background-color: pink;
            text-align: center;
            font-family: Arial, sans-serif;
        }
        .container {
            margin-top: 100px;
        }
        .hidden {
            display: none;
        }
        .btn {
            background-color: red;
            color: white;
            padding: 10px 20px;
            border: none;
            font-size: 20px;
            cursor: pointer;
            margin: 10px;
            border-radius: 10px;
        }
        .btn:hover {
            background-color: darkred;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Hola, hermosa ❤️</h1>
        <p>Tengo una pregunta muy especial para ti...</p>
        <button class="btn" onclick="showQuestion()">Haz clic aquí</button>
        
        <div id="question" class="hidden">
            <h2>¿Quieres ser mi San Valentín? 💘</h2>
            <button class="btn" onclick="showLove()">Sí</button>
            <button class="btn" onclick="showLove()">Por supuesto</button>
        </div>

        <h2 id="response" class="hidden">Sabía que dirías que sí! 😍💖</h2>
    </div>

    <script>
        function showQuestion() {
            document.getElementById("question").classList.remove("hidden");
        }
        function showLove() {
            document.getElementById("response").classList.remove("hidden");
        }
    </script>
</body>
</html>

