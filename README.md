# EX01 Developing a Simple Webserver
## Date: 25 / 11 / 2026

## AIM:
To develop a simple webserver to serve html pages and display the list of protocols in TCP/IP Protocol Suite.

## DESIGN STEPS:
### Step 1: 
HTML content creation.

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
<html>
<head>
    <title>Network Protocols</title>

    <style>
        body {
            font-family: Arial;
            background-color: #f0f4ff;
            margin: 30px;
        }

        h1 {
            text-align: center;
            color: #4527a0;
        }

        p {
            text-align: center;
            color: #555;
        }

        table {
            width: 90%;
            margin: auto;
            border-collapse: collapse;
            background-color: white;
        }

        th {
            background-color: #4527a0;
            color: white;
            padding: 12px;
        }

        td {
            padding: 10px;
            text-align: center;
            border: 1px solid #ccc;
        }

        tr:nth-child(even) {
            background-color: #e8eaf6;
        }

        tr:hover {
            background-color: #d1c4e9;
        }

        h2 {
            text-align: center;
            color: #303f9f;
        }
    </style>
</head>

<body>

    <h1>TCP/IP NETWORK PROTOCOLS</h1>

    <p>Study of Communication Protocols in Computer Networks</p>

    <hr>

    <h2>Protocol Details</h2>

    <table>
        <tr>
            <th>No.</th>
            <th>Protocol</th>
            <th>Layer</th>
            <th>Application</th>
        </tr>

        <tr>
            <td>1</td>
            <td>HTTP</td>
            <td>Application</td>
            <td>Web Browsing</td>
        </tr>

        <tr>
            <td>2</td>
            <td>DNS</td>
            <td>Application</td>
            <td>Name Resolution</td>
        </tr>

        <tr>
            <td>3</td>
            <td>FTP</td>
            <td>Application</td>
            <td>File Sharing</td>
        </tr>

        <tr>
            <td>4</td>
            <td>SMTP</td>
            <td>Application</td>
            <td>Email Sending</td>
        </tr>

        <tr>
            <td>5</td>
            <td>TCP</td>
            <td>Transport</td>
            <td>Reliable Delivery</td>
        </tr>

        <tr>
            <td>6</td>
            <td>UDP</td>
            <td>Transport</td>
            <td>Fast Communication</td>
        </tr>

        <tr>
            <td>7</td>
            <td>IP</td>
            <td>Internet</td>
            <td>Packet Routing</td>
        </tr>

        <tr>
            <td>8</td>
            <td>ICMP</td>
            <td>Internet</td>
            <td>Error Reporting</td>
        </tr>

        <tr>
            <td>9</td>
            <td>ARP</td>
            <td>Network Access</td>
            <td>Address Mapping</td>
        </tr>

        <tr>
            <td>10</td>
            <td>DHCP</td>
            <td>Application</td>
            <td>IP Assignment</td>
        </tr>

    </table>

    <br>

    <p>Designed using HTML and CSS</p>

</body>
</html>
```
## OUTPUT:
<img width="1865" height="875" alt="image" src="https://github.com/user-attachments/assets/826db4b2-7864-46ab-8287-104ac1e99637" />


## RESULT:
The program for implementing simple webserver is executed successfully.

