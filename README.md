<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personality Car Test</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>Personality Car Test</h1>
        <form id="personalityTest">
            <label for="q1">Question 1: What's your favorite color?</label><br>
            <input type="text" id="q1" name="q1"><br>

            <label for="q2">Question 2: What's your ideal weekend activity?</label><br>
            <input type="text" id="q2" name="q2"><br>

            <label for="q3">Question 3: What's your dream vacation spot?</label><br>
            <input type="text" id="q3" name="q3"><br>

            <button type="button" onclick="submitTest()">Submit</button>
        </form>

        <div id="result"></div>
    </div>
    <script src="script.js"></script>
</body>
</html>
