<head>
    ...
    <link rel="stylesheet" href="style.css">
</head>
body {
    font-family: Arial, sans-serif;
    background-color: #f5f5f5;
    padding: 20px;
}

h1 {
    text-align: center;
    margin-bottom: 30px;
    color: #333;
}

.converter {
    display: flex;
    gap: 10px;
    justify-content: center;
    margin-bottom: 25px;
    flex-wrap: wrap;
}

.converter input,
.converter select {
    padding: 8px;
    font-size: 16px;
    border: 1px solid #ccc;
    border-radius: 5px;
}

.rates-table {
    width: 100%;
    border-collapse: collapse;
    background-color: white;
    box-shadow: 0 2px 8px rgba(0, 0, 0, 0.05);
}

.rates-table th, .rates-table td {
    padding: 12px;
    text-align: center;
    border-bottom: 1px solid #eee;
}

.rates-table th {
    background-color: #2c3e50;
    color: white;
}

.rates-table tr:hover {
    background-color: #f9f9f9;
}

.up {
    color: green;
    font-weight: bold;
}

.down {
    color: red;
    font-weight: bold;
}
