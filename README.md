# EX01 Developing a Simple Webserver
## Date: 26-08-2025

## Name: HARI PRASATH E
## REG NO: 25007799
## AIM:
To develop a simple webserver to serve html pages and display the Device Specifications of your Laptop.

## DESIGN STEPS:
### Step 1: 
HTML content creation

### Step 2:
Design of webserver workflow.

### Step 3:
Implementation using Python code.

### Step 4:
Import the necessary modules.

### Step 5:
Define a custom request handler.

### Step 6:
Start an HTTP server on a specific port.

### Step 7:
Run the Python script to serve web pages.

### Step 8:
Serve the HTML pages.

### Step 9:
Start the server script and check for errors.

### Step 10:
Open a browser and navigate to http://127.0.0.1:8000 (or the assigned port).

## PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bio-Data - Hari</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background: #b7c53a;
            margin: 20px;
        }
        h1 {
            text-align: center;
            color: #0066cc;
        }
        table {
            width: 70%;
            margin: 20px auto;
            border-collapse: collapse;
            border: 3px double #e9e3e3;
            background: #044f9f;
        }
        th, td {
            border: 2px double #b3ccde;
            padding: 10px;
            text-align: left;
        }
        th {
            background: #cac4e8;
            text-align: center;
        }
    </style>
</head>
<body>
    <h1>Biodata</h1>
    <table>
        <tr>
            <th colspan="2">Personal Information</th>
        </tr>
        <tr>
            <td><strong>Name</strong></td>
            <td>Hari Prasath E </td>
        </tr>
        <tr>
            <td><strong>Role</strong></td>
            <td>Student</td>
        </tr>
        <tr>
            <td><strong>DOB</strong></td>
            <td>01/11/2007</td>
        </tr>
        <tr>
            <td><strong>Address</strong></td>
            <td>Chennai</td>
        </tr>

        <tr>
            <th colspan="2">Education</th>
        </tr>
        <tr>
            <td><strong>College</strong></td>
            <td>Saveetha Engineering College</td>
        </tr>
        <tr>
            <td><strong>Course</strong></td>
            <td>B.E COMPUTER SCIENCE ENGINEERING</td>
        </tr>
        <tr>
            <td><strong>Year</strong></td>
            <td>Pursuing 1st Year</td>
        </tr>
    </table>
</body>
</html>



```

## OUTPUT:
<img width="1908" height="993" alt="image" src="https://github.com/user-attachments/assets/df6e9583-bf33-40ed-8e3e-d7d21e9c8751" />
<img width="1903" height="973" alt="image" src="https://github.com/user-attachments/assets/cba02670-1632-49b9-8dcc-f235b6b284da" />



## RESULT:
The program for implementing simple webserver is executed successfully.
