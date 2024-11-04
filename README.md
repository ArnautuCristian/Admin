<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tema: Administrarea repozitoriului. Sarcini cu administrarea repozitoriului.</title>
    <style>
        .container {
            width: 1300px;
            height: 500px;
            margin: 100px auto;
            background-color: rgb(68, 68, 68);
            display: flex;
            gap: 20px;
            justify-content: center;
            border-radius: 5px;
        }

        .block {
            background-color: grey;
            color: white;
            width: 100px;
            height: 100px;
            font-size: 80px;
            text-align: center;
            margin-top: 100px;
            border-radius: 10px;

        }

        .block:hover {
            cursor: pointer;
            transition: ease .4s;
            transform: rotate(360deg);
            color: grey;
            background-color: rgb(29, 29, 29);
        }
    </style>
</head>

<body>
    <div class="container">
        <div class="block">1</div>
        <div class="block">2</div>
        <div class="block">3</div>
        <div class="block">4</div>
        <div class="block">5</div>
    </div>
</body>

</html>
