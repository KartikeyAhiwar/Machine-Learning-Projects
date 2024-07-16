<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSV-based Finance Tracker</title>
</head>
<body style="font-family: Arial, sans-serif; line-height: 1.6; margin: 0; padding: 20px; background-color: #f4f4f4; color: #333;">
    <div style="max-width: 900px; margin: auto; padding: 20px; background: #fff; box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);">
        <h1 style="text-align: center; padding-top: 20px;">CSV-based Finance Tracker</h1>
        <p>This project is a simple finance tracker that stores transaction data in a CSV file. It allows users to:</p>
        <ul style="list-style: none; padding: 0;">
            <li style="background: #e8e8e8; margin: 5px 0; padding: 10px; border-left: 3px solid #333;">Add new transactions with date, amount, category, and description.</li>
            <li style="background: #e8e8e8; margin: 5px 0; padding: 10px; border-left: 3px solid #333;">View transactions within a specified date range.</li>
            <li style="background: #e8e8e8; margin: 5px 0; padding: 10px; border-left: 3px solid #333;">See a summary of income, expenses, and net savings for the given period.</li>
            <li style="background: #e8e8e8; margin: 5px 0; padding: 10px; border-left: 3px solid #333;">Plot transactions over time to visualize income and expenses.</li>
        </ul>
        <p>The tracker uses the following main components:</p>
        <ul style="list-style: none; padding: 0;">
            <li style="background: #e8e8e8; margin: 5px 0; padding: 10px; border-left: 3px solid #333;"><strong>CSV:</strong> A class to manage the CSV file operations, including initialization, adding entries, and fetching transactions.</li>
            <li style="background: #e8e8e8; margin: 5px 0; padding: 10px; border-left: 3px solid #333;"><strong>get_date, get_amount, get_category, get_description:</strong> Functions to handle user input for transaction details.</li>
            <li style="background: #e8e8e8; margin: 5px 0; padding: 10px; border-left: 3px solid #333;"><strong>plot_transactions:</strong> A function to visualize transactions over time using Matplotlib.</li>
            <li style="background: #e8e8e8; margin: 5px 0; padding: 10px; border-left: 3px solid #333;"><strong>main:</strong> The main function to interact with the user, allowing them to add transactions, view summaries, and plot data.</li>
        </ul>
      <div style="display: flex; justify-content: space-around; flex-wrap: wrap;">
            <div style="width: 45%; margin: 20px 0;">
                <h2>Income vs Expenses</h2>
                <div style="display: block; width: 70%; background: linear-gradient(to right, #4caf50, #81c784); padding: 5px; margin: 5px 0; color: white; text-align: right; padding-right: 10px;">Income: $700</div>
                <div style="display: block; width: 50%; background: linear-gradient(to right, #f44336, #e57373); padding: 5px; margin: 5px 0; color: white; text-align: right; padding-right: 10px;">Expenses: $500</div>
            </div>
            <div style="width: 45%; margin: 20px 0;">
                <h2>Transactions Over Time</h2>
                <ul style="padding: 0;">
                    <li style="list-style: none; margin: 5px 0;"><span style="display: block; width: 60%; background: linear-gradient(to right, #4caf50, #81c784); padding: 5px; color: white; text-align: right; padding-right: 10px;">15-07-2024: $60</span></li>
                    <li style="list-style: none; margin: 5px 0;"><span style="display: block; width: 30%; background: linear-gradient(to right, #f44336, #e57373); padding: 5px; color: white; text-align: right; padding-right: 10px;">10-07-2024: $30</span></li>
                    <li style="list-style: none; margin: 5px 0;"><span style="display: block; width: 90%; background: linear-gradient(to right, #4caf50, #81c784); padding: 5px; color: white; text-align: right; padding-right: 10px;">05-07-2024: $90</span></li>
                    <li style="list-style: none; margin: 5px 0;"><span style="display: block; width: 40%; background: linear-gradient(to right, #f44336, #e57373); padding: 5px; color: white; text-align: right; padding-right: 10px;">01-07-2024: $40</span></li>
                </ul>
            </div>
        </div>
    </div>
</body>
</html>
