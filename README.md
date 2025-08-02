<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Muhammad Ali</title>
</head>
<body bgcolor="lightpink">
    <center>
        <button>
            <a href="/">Home</a>
        </button>
    </center>
    <center>
        <button>
            <a href="/chapter12-13">chapter12-13</a>
        </button>
    </center>
    <!-- Program 1: City Name -->
    <div class="section">
        <h2>1. City Name Check</h2>
        <input type="text" id="cityInput" placeholder="Enter city name">
        <button onclick="checkCity()">Check City</button>
        <div id="cityResult" class="result"></div>
    </div>

    <!-- Program 2: Gender Greeting -->
    <div class="section">
        <h2>2. Gender Greeting</h2>
        <input type="text" id="genderInput" placeholder="Enter gender (male/female)">
        <button onclick="greetUser()">Greet</button>
        <div id="genderResult" class="result"></div>
    </div>

    <!-- Program 3: Traffic Signal -->
    <div class="section">
        <h2>3. Traffic Signal Message</h2>
        <input type="text" id="signalInput" placeholder="Enter signal color">
        <button onclick="checkSignal()">Check Signal</button>
        <div id="signalResult" class="result"></div>
    </div>

    <!-- Program 4: Fuel Check -->
    <div class="section">
        <h2>4. Fuel Level Check</h2>
        <input type="number" id="fuelInput" placeholder="Enter fuel in litres" step="0.01">
        <button onclick="checkFuel()">Check Fuel</button>
        <div id="fuelResult" class="result"></div>
    </div>

    <!-- Program 5: Alert Script Outputs -->
    <div class="section">
        <h2>5. Alert Script Outputs</h2>
        <button onclick="runAlertScripts()">Run Alert Scripts</button>
        <div id="alertResult" class="result"></div>
    </div>

    <!-- Program 6: Grade Calculator -->
    <div class="section">
        <h2>6. Grade Calculator</h2>
        <input type="number" id="marks1" placeholder="Marks in subject 1">
        <input type="number" id="marks2" placeholder="Marks in subject 2">
        <input type="number" id="marks3" placeholder="Marks in subject 3">
        <input type="number" id="totalMarks" placeholder="Total marks">
        <button onclick="calculateGrade()">Calculate Grade</button>
        <div id="gradeResult" class="result"></div>
    </div>

    <!-- Program 7: Guess Game -->
    <div class="section">
        <h2>7. Guess the Number</h2>
        <input type="number" id="guessInput" placeholder="Guess a number (1-10)">
        <button onclick="guessNumber()">Guess</button>
        <div id="guessResult" class="result"></div>
    </div>

    <!-- Program 8: Divisible by 3 -->
    <div class="section">
        <h2>8. Divisible by 3 Check</h2>
        <input type="number" id="divisibleInput" placeholder="Enter a number">
        <button onclick="checkDivisible()">Check</button>
        <div id="divisibleResult" class="result"></div>
    </div>

    <!-- Program 9: Even or Odd -->
    <div class="section">
        <h2>9. Even or Odd Check</h2>
        <input type="number" id="evenOddInput" placeholder="Enter a number">
        <button onclick="checkEvenOdd()">Check</button>
        <div id="evenOddResult" class="result"></div>
    </div>

    <!-- Program 10: Temperature Message -->
    <div class="section">
        <h2>10. Temperature Check</h2>
        <input type="number" id="tempInput" placeholder="Enter temperature">
        <button onclick="checkTemperature()">Check</button>
        <div id="tempResult" class="result"></div>
    </div>

    <!-- Program 11: Calculator -->
    <div class="section">
        <h2>11. Calculator</h2>
        <input type="number" id="num1" placeholder="First number">
        <input type="number" id="num2" placeholder="Second number">
        <input type="text" id="operation" placeholder="Operation (+, -, *, /, %)">
        <button onclick="calculate()">Calculate</button>
        <div id="calcResult" class="result"></div>
    </div>
    <script src="app.js"></script>
</body>
</html>
