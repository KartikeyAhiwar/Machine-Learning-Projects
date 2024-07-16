<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSV-based Finance Tracker</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 20px;
            background-color: #f4f4f4;
            color: #333;
        }
        .container {
            max-width: 900px;
            margin: auto;
            padding: 20px;
            background: #fff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1 {
            text-align: center;
            padding-top: 20px;
        }
        p {
            margin: 20px 0;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>CSV-based Finance Tracker</h1>
        <p>
            This project is a simple finance tracker that stores transaction data in a CSV file. 
            It allows users to:
        </p>
        <ul>
            <li>Add new transactions with date, amount, category, and description.</li>
            <li>View transactions within a specified date range.</li>
            <li>See a summary of income, expenses, and net savings for the given period.</li>
            <li>Plot transactions over time to visualize income and expenses.</li>
        </ul>
        <p>
            The tracker uses the following main components:
        </p>
        <ul>
            <li><strong>CSV:</strong> A class to manage the CSV file operations, including initialization, adding entries, and fetching transactions.</li>
            <li><strong>get_date, get_amount, get_category, get_description:</strong> Functions to handle user input for transaction details.</li>
            <li><strong>plot_transactions:</strong> A function to visualize transactions over time using Matplotlib.</li>
            <li><strong>main:</strong> The main function to interact with the user, allowing them to add transactions, view summaries, and plot data.</li>
        </ul>
    </div>
</body>
</html>
