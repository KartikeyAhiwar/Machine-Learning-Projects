<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Finance Tracker</title>
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
        h1, h2, h3 {
            color: #333;
        }
        h1 {
            text-align: center;
            padding-top: 20px;
        }
        h2 {
            border-bottom: 2px solid #333;
            padding-bottom: 10px;
        }
        p {
            margin: 20px 0;
        }
        ul {
            list-style: none;
            padding: 0;
        }
        ul li {
            background: #e8e8e8;
            margin: 5px 0;
            padding: 10px;
            border-left: 3px solid #333;
        }
        code {
            background: #e8e8e8;
            padding: 2px 5px;
            border-radius: 4px;
        }
        pre {
            background: #333;
            color: #fff;
            padding: 10px;
            border-radius: 4px;
            overflow-x: auto;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>CSV-based Finance Tracker</h1>

        <h2>Project Description</h2>
        <p>This project is a simple finance tracker that stores transaction data in a CSV file. It allows users to:</p>
        <ul>
            <li>Add new transactions with date, amount, category, and description.</li>
            <li>View transactions within a specified date range.</li>
            <li>See a summary of income, expenses, and net savings for the given period.</li>
            <li>Plot transactions over time to visualize income and expenses.</li>
        </ul>

        <h2>Getting Started</h2>
        <p>Follow the instructions below to set up and run the project.</p>

        <h3>Prerequisites</h3>
        <ul>
            <li>Python 3.8+</li>
            <li>Pandas</li>
            <li>Matplotlib</li>
        </ul>

        <h3>Installation</h3>
        <pre><code>git clone https://github.com/your_username/finance-tracker.git
cd finance-tracker
pip install -r requirements.txt
</code></pre>

        <h2>Usage</h2>
        <p>Run the main script to start the finance tracker:</p>
        <pre><code>python main.py</code></pre>
        <p>You will be prompted to add transactions or view existing ones within a date range.</p>

        <h3>Example Usage</h3>
        <p>Adding a new transaction:</p>
        <pre><code>
1. Enter the date of the transaction (dd-mm-yyyy) or enter for today's date: 15-07-2024
2. Enter the amount: 100
3. Enter the category ('I' for Income or 'E' for Expense): I
4. Enter a description (optional): Salary
</code></pre>

        <p>Viewing transactions and summary within a date range:</p>
        <pre><code>
Enter the start date (dd-mm-yyyy): 01-07-2024
Enter the end date (dd-mm-yyyy): 15-07-2024
Transaction from 01-07-2024 to 15-07-2024
 date      amount  category  description
01-07-2024   50.0   Expense      Groceries
10-07-2024  200.0    Income        Bonus
15-07-2024  100.0    Income       Salary

Summary:
Total Income: $300.00
Total Expense: $50.00
Net Savings: $250.00
</code></pre>

        <h2>Contributing</h2>
        <p>Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are <strong>greatly appreciated</strong>.</p>

        <h3>How to Contribute</h3>
        <ul>
            <li>Fork the Project</li>
            <li>Create your Feature Branch (<code>git checkout -b feature/AmazingFeature</code>)</li>
            <li>Commit your Changes (<code>git commit -m 'Add some AmazingFeature'</code>)</li>
            <li>Push to the Branch (<code>git push origin feature/AmazingFeature</code>)</li>
            <li>Open a Pull Request</li>
        </ul>

        <h2>License</h2>
        <p>Distributed under the MIT License. See <a href="LICENSE.txt">LICENSE</a> for more information.</p>

        <h2>Contact</h2>
        <p>Your Name - <a href="mailto:your.email@example.com">your.email@example.com</a></p>
        <p>Project Link: <a href="https://github.com/your_username/finance-tracker">https://github.com/your_username/finance-tracker</a></p>

        <h2>Acknowledgments</h2>
        <ul>
            <li><a href="https://pandas.pydata.org/">Pandas</a></li>
            <li><a href="https://matplotlib.org/">Matplotlib</a></li>
        </ul>
    </div>
</body>
</html>
