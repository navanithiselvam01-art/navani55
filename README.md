<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AWS Test Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin-top: 100px;
            background-color: #f4f4f4;
        }
        .container {
            background: white;
            padding: 30px;
            width: 50%;
            margin: auto;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0,0,0,0.2);
        }
        h1 {
            color: green;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>🚀 AWS EC2 Web Server is Running!</h1>
        <p>Hello from AWS.</p>
        <p>Server Time: <span id="time"></span></p>
    </div>

    <script>
        document.getElementById("time").innerHTML =
            new Date().toLocaleString();
    </script>
</body>
</html>
