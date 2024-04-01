<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Register Here</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f2f2f2;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        
        .container {
            background-color: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        
        h1 {
            text-align: center;
        }
        
        label {
            font-weight: bold;
            display: block;
            margin-bottom: 5px;
        }
        
        input[type="text"],
        input[type="number"],
        input[type="email"],
        input[type="date"],
        button[type="submit"] {
            width: 100%;
            padding: 8px;
            margin-bottom: 15px;
            border: 1px solid #ccc;
            border-radius: 4px;
            box-sizing: border-box;
        }
        
        button[type="submit"] {
            background-color: #4caf50;
            color: #fff;
            cursor: pointer;
        }
        
        button[type="submit"]:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Register Here</h1>
        <form action="">
            <label for="fname">First Name:</label>
            <input type="text" name="fname" required>
            <label for="lname">Last Name:</label>
            <input type="text" name="lname" required>
            <label for="phone">Phone:</label>
            <input type="number" name="phone" required>
            <label for="email">E-mail:</label>
            <input type="email" name="email" required>
            <label for="dob">DOB:</label>
            <input type="date" name="dob" required>
            <button type="submit">Submit</button>
        </form>
    </div>
</body>
</html>
