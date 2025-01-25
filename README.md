<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mon Jeu</title>
    <style>
        body {
            background-color: #f0f0f0;
            font-family: Arial, sans-serif;
            text-align: center;
            padding: 50px;
        }

        h1 {
            color: #333;
        }

        p {
            font-size: 20px;
            color: #666;
        }
    </style>
</head>
<body>
    <h1>Bienvenue dans mon jeu !</h1>
    <p>Cliquez n'importe où pour démarrer.</p>
    
    <script>
        document.body.addEventListener('click', function() {
            alert("Tu as cliqué sur l'écran !");
        });
    </script>
</body>
</html>
