# WeatherPredictionModel
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Weather Prediction App</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        h1 {
            color: #333;
        }
        p {
            color: #666;
        }
        input[type=text] {
            padding: 10px;
            border-radius: 5px;
            border: 1px solid #ccc;
        }
        button {
            padding: 10px 20px;
            background-color: #007bff;
            color: #fff;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
    <h1>Welcome to the Weather Prediction App!</h1>
    <p>This app allows you to predict weather based on your input data.</p>
    
    <input type="text" id="inputData" placeholder="Enter your input data...">
    <button onclick="predictWeather()">Predict</button>

    <div id="predictionResult"></div>

    <script>
        function predictWeather() {
            var inputData = document.getElementById("inputData").value;

            // Perform prediction based on inputData
            // Replace this with your actual prediction logic

            var prediction = "Sunny"; // Example prediction

            // Display prediction result
            document.getElementById("predictionResult").innerHTML = "<p>Weather Prediction: " + prediction + "</p>";
        }
    </script>
</body>
</html>
