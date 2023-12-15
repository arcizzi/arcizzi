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
        <form action="#">
            <label for="chemical1">Ķīmiskais vienums 1:</label>
            <input type="text" id="chemical1" name="chemical1">
            <br>
            <label for="quantity1">Daudzums:</label>
            <input type="number" id="quantity1" name="quantity1" min="0">
            <br>
            <button type="button" onclick="showForm(2)">Nākamā forma</button>
            <button type="button" onclick="showForm(3)">Trešā forma</button>
        </form>
    </div>

    <div id="form2" class="form-container">
        <h2>Forma 2</h2>
        <form action="#">
            <label for="chemical2">Ķīmiskais vienums 2:</label>
            <input type="text" id="chemical2" name="chemical2">
            <br>
            <label for="quantity2">Daudzums:</label>
            <input type="number" id="quantity2" name="quantity2" min="0">
            <br>
            <button type="button" onclick="showForm(1)">Iepriekšējā forma</button>
            <button type="button" onclick="showForm(3)">Trešā forma</button>
        </form>
    </div>

    <div id="form3" class="form-container">
        <h2>Forma 3</h2>
        <form action="#">
            <label for="chemical3">Ķīmiskais vienums 3:</label>
            <input type="text" id="chemical3" name="chemical3">
            <br>
            <label for="quantity3">Daudzums:</label>
            <input type="number" id="quantity3" name="quantity3" min="0">
            <br>
            <button type="button" onclick="showForm(1)">Iepriekšējā forma</button>
            <button type="button" onclick="showForm(2)">Nākamā forma</button>
        </form>
    </div>

    <script src="script.js"></script>
</body>
</html>
