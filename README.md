<html lang="en">

<head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Simple Interest Calculator</title>
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500&display=swap" rel="stylesheet" />
    <!-- Stylesheet -->
    <link rel="stylesheet" href="style.css" />
</head>
<style>
    body {
        background-image: linear-gradient(to right, #49dddf, #00bffa, #6296f7, #b65cc0, #cd075f);
    }
</style>

<body>
    <div class="container">
        <div class="input-wrapper">
            <div class="wrapper">
                <label for="principal">Principal:</label>
                <input type="number" id="principal" />
            </div>
            <div class="wrapper">
                <label for="rate">Rate:</label>
                <input type="number" id="rate" />
            </div>
        </div>
        <label for="time">Time:</label>
        <div class="time-wrapper">
            <input type="number" id="time" />
            <select name="duration" id="duration">
          <option value="year">Year</option>
          <option value="month">Month</option>
        </select>
        </div>
        <button id="calculate-btn">Calculate</button>
        <div id="result"></div>
    </div>
    <!-- Script -->
    <script src="script.js"></script>
</body>

</html>
