<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login Page</title>
    <style>

        body {
            background-image: url(side.png);
            background-size: cover;
            background-repeat: no-repeat;
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        
        .login-container {
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            padding: 40px;
            width: 300px;
            text-align: center;
        }
        
        .login-container h1 {
            margin-bottom: 20px;
        }
        
        .login-container input[type="text"], 
        .login-container input[type="password"] {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        
        .login-container input[type="submit"] {
            width: 100%;
            padding: 10px;
            background-color: #007bff;
            border: none;
            border-radius: 5px;
            color: white;
            cursor: pointer;
            font-size: 16px;
        }
        
        .login-container input[type="submit"]:hover {
            background-color: #0056b3;
        }
        
        .login-container a {
            display: block;
            margin-top: 20px;
            color: #007bff;
            text-decoration: none;
        }
        
        .login-container a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
     <img src="logo2.png" alt="image added">

    <div class="login-container">
        <h1>Login</h1>
        <form action="#" method="post">
            <input type="text" placeholder="Username" required>
            <input type="password" placeholder="Password" required>
            <a href="http://127.0.0.1:5500/moneytalk.html#financial-dashboard">Login</a>
            <!-- <a href="http://127.0.0.1:5500/moneytalk.html#financial-dashboard">login</a> -->
        </form>
        <a href="#">Forgot your password?</a>
    </div>

</body>
</html>
