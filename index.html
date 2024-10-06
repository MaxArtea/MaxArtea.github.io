<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Google Sheet Results</title>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/PapaParse/5.3.0/papaparse.min.js"></script>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 20px;
        }
        table {
            border-collapse: collapse;
            width: 100%;
        }
        th, td {
            border: 1px solid #ddd;
            padding: 8px;
            text-align: left;
        }
        th {
            background-color: #f2f2f2;
        }
    </style>
</head>
<body>
    <h1>Google Sheet Results</h1>
    <div id="results"></div>

    <script>
        // Replace this URL with your Google Sheet's published CSV URL
        const SHEET_URL = 'https://docs.google.com/spreadsheets/d/e/2PACX-1vT4-b_MyK1fCXKbiP2WvdF1tizjomqUKfmqksSYXRtmlIpX-CKACQJRnlISbK84SavJZpjNDW4Z762x/pub?output=csv';

        fetch(SHEET_URL)
            .then(response => response.text())
            .then(data => {
                const results = Papa.parse(data, { header: true });
                displayResults(results.data);
            })
            .catch(error => {
                console.error('Error:', error);
                document.getElementById('results').innerHTML = 'Error loading data. Please check the console for details.';
            });

        function displayResults(data) {
            const table = document.createElement('table');
            const headerRow = table.insertRow();

            // Create table header
            Object.keys(data[0]).forEach(key => {
                const th = document.createElement('th');
                th.textContent = key;
                headerRow.appendChild(th);
            });

            // Add data rows
            data.forEach(row => {
                const tr = table.insertRow();
                Object.values(row).forEach(value => {
                    const td = tr.insertCell();
                    td.textContent = value;
                });
            });

            document.getElementById('results').appendChild(table);
        }
    </script>
</body>
</html>