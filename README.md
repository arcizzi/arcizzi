<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Ķīmijas Laboratorijas Uzskaites Sistēma</title>
</head>
<body>
    <div id="form1" class="form-container">
        <h2>Forma 1</h2>
        <!-- Ievietojiet šeit pirmās formas saturu -->
        <button onclick="showForm(2)">Nākamā forma</button>
        <button onclick="showForm(3)">Trešā forma</button>
    </div>

    <div id="form2" class="form-container">
        <h2>Forma 2</h2>
        <!-- Ievietojiet šeit otras formas saturu -->
        <button onclick="showForm(1)">Iepriekšējā forma</button>
        <button onclick="showForm(3)">Trešā forma</button>
    </div>

    <div id="form3" class="form-container">
        <h2>Forma 3</h2>
        <!-- Ievietojiet šeit trešās formas saturu -->
        <button onclick="showForm(1)">Iepriekšējā forma</button>
        <button onclick="showForm(2)">Nākamā forma</button>
    </div>

    <script src="script.js"></script>
</body>
</html>
