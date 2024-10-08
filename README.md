<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Botones Simples</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #f0f0f0;
        }

        .button-container {
            display: flex;
            flex-direction: column;
            gap: 10px;
        }

        button {
            padding: 10px 20px;
            font-size: 16px;
            border-radius: 5px;
            border: none;
            cursor: pointer;
        }

        .primary {
            background-color: #007bff;
            color: white;
        }

        .secondary {
            background-color: #6c757d;
            color: white;
        }

        .success {
            background-color: #28a745;
            color: white;
        }

        .danger {
            background-color: #dc3545;
            color: white;
        }

        button:hover {
            opacity: 0.8;
        }
    </style>
</head>
<body>
    <div class="button-container">
        <button class="primary">Primary Button</button>
        <button class="secondary">Secondary Button</button>
        <button class="success">Success Button</button>
        <button class="danger">Danger Button</button>
    </div>
</body>
</html>
