# Product Table
## Date:
## Objective:

To create a structured HTML table that displays product-related information, including product names, prices, and descriptions, useful for catalogs, listings, or e-commerce prototypes.

## Tasks:

### 1. Set Up the Basic HTML Structure:

Use ```<!DOCTYPE html>```, ```<html>```, ```<head>```, and ```<body>``` tags to define the document layout.

Include a ```<title>``` such as "Product Table".

### 2. Create a Table Element:

Use the ```<table>``` tag to begin the product table.

### 3. Add a Table Header:

Use the ```<thead>``` section with a ```<tr>``` row and three ```<th>``` elements:

Product Name

Product Price

Description

### 4. Insert Table Body Rows:

Use the ```<tbody>``` section with multiple ```<tr>``` rows.

In each row, use three ```<td>``` cells for:

The name of the product (e.g., Laptop, Phone)

The price (e.g., ₹45,000, $499)

A short description (e.g., "High-speed performance", "Budget-friendly")

### 5. Ensure Semantic Structure:

Include ```<caption>``` if needed to describe the table purpose.

Use meaningful text inside the table for clarity.

### 6. No CSS or JavaScript:

Keep the table design strictly in HTML for simplicity.
## HTML Code:
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Product Table</title>
</head>
<body>
    <h1>Product Table</h1>
    <table border="3">
        <caption>Electronic Store</caption>
        <thead>
            <tr>
                <th>Product Name</th>
                <th>Product Price</th>
                <th>Description</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Laptop</td>
                <td>$680</td>
                <td>High-performance</td>
            </tr>
            <tr>
                <td>Smart Phone</td>
                <td>$460</td>
                <td>Gaming Phone</td>
            </tr>
            <tr>
                <td>Earbuds</td>
                <td>$180</td>
                <td>Budget Friendly</td>
            </tr>
        </tbody>
    </table>
</body>
</html>
```

## CSS Code:
```css
body{
    background-color: rgb(38, 244, 154);
    font-family: Verdana, Geneva, Tahoma, sans-serif;
}
table{
    border-collapse: collapse;
    margin: auto;
    width: 60%;
}
th{
    background-color: #b5b521;
    color: aliceblue;
    padding: auto;
}
td{
    border: 1px solid rgb(165, 21, 149);
    padding: 1%;
}
tr:nth-child(odd) td:nth-child(even),
tr:nth-child(even) td:nth-child(odd) {
    background-color: #14789c;
    color: white;
}

td:hover{
    background-color: rgb(209, 92, 8);
    color: azure;
}
caption{
    font-weight: bold;
    margin: 3% auto auto;
}
```

## Output:
![image](https://github.com/user-attachments/assets/3ff1e774-9ff7-4312-90e3-c2f7f9a293e6)

## Result:
A structured HTML table that displays product-related information, including product names, prices, and descriptions, useful for catalogs, listings, or e-commerce prototypes is created successfully.
