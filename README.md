# Jntuh-1-1-R22-Results-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Results</title>
    <style>
        body { font-family: Arial, sans-serif; text-align: center; margin: 50px; }
        input { padding: 10px; margin: 10px; width: 200px; }
        button { padding: 10px; cursor: pointer; }
        #result { font-size: 20px; font-weight: bold; margin-top: 20px; color: red; }
    </style>
</head>
<body>
    <h2>Enter Your Hall Ticket Number</h2>
    <input type="text" id="hallTicket" placeholder="Enter Hall Ticket">
    <button onclick="showResult()">Check Result</button>
    <p id="result"></p>

    <script>
        function showResult() {
            let hallTicket = document.getElementById("hallTicket").value;
            if (hallTicket.trim() !== "") {
                document.getElementById("result").innerHTML = "Result: FAIL";
            } else {
                alert("Please enter a valid Hall Ticket Number.");
            }
        }
    </script>
</body>
</html>
