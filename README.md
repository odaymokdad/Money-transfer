<!DOCTYPE html>
<html>
<head>
    <title>Money Transfer Software</title>
    <style>
        /* Add your custom CSS styles here */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
        }
        
        h1 {
            text-align: center;
        }
        
        form {
            margin-top: 30px;
            text-align: center;
        }
        
        input[type="text"], input[type="number"] {
            padding: 10px;
            width: 300px;
            margin-bottom: 10px;
        }
        
        button {
            padding: 10px 20px;
            background-color: #4CAF50;
            color: white;
            border: none;
            cursor: pointer;
        }
        
        button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Money Transfer Software</h1>
        <form>
            <input type="text" placeholder="Sender" id="sender">
            <input type="text" placeholder="Receiver" id="receiver">
            <input type="number" placeholder="Amount" id="amount">
            <button onclick="transfer()">Transfer</button>
        </form>
        <div id="result"></div>
    </div>

    <script>
        function transfer() {
            var sender = document.getElementById("sender").value;
            var receiver = document.getElementById("receiver").value;
            var amount = document.getElementById("amount").value;

            // Add your JavaScript logic to send the transfer request to the server and handle the response

            // Example code to display the result
            var resultDiv = document.getElementById("result");
            resultDiv.innerHTML = "Transfer successful";
        }
    </script>
</body>
</html>
