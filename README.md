<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kani Love</title>
    <style>
        body {
            background-color: #ffebee;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            font-family: 'Arial', sans-serif;
        }
        .container {
            text-align: center;
        }
        .heart {
            color: #e91e63;
            font-size: 100px;
            animation: beat 1s infinite;
        }
        @keyframes beat {
            0% { transform: scale(1); }
            50% { transform: scale(1.2); }
            100% { transform: scale(1); }
        }
        h1 {
            color: #ad1457;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="heart">❤️</div>
        <h1>Kani-Love Forever!</h1>
        <p>This site is live now.</p>
    </div>
</body>
</html>
