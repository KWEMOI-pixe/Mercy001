<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Love Message for Mercy</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #f0f0f0;
        }
        .container {
            text-align: center;
            background-color: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        .login {
            margin-bottom: 20px;
        }
        .message {
            display: none;
        }
        input {
            padding: 5px;
            margin: 5px;
        }
        button {
            padding: 8px 15px;
            background-color: #ff4444;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #cc0000;
        }
        img {
            max-width: 300px;
            border-radius: 10px;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="login" id="loginSection">
            <h2>Please Log In</h2>
            <input type="password" id="password" placeholder="Enter password">
            <br>
            <button onclick="checkPassword()">Login</button>
        </div>
        <div class="message" id="messageSection">
            <h1>My Dearest Mercy Cherop</h1>
            <p>I love you more than words can express, Mercy Cherop. You are my everything.</p>
            <p>With all my heart,<br>Isaac Kwemoi Chelasha</p>
            <!-- Replace the src with the actual path to Mercy's photo -->
            <img src="mercy.jpg" alt="Mercy Cherop">
        </div>
    </div>

    <script>
        function checkPassword() {
            const password = document.getElementById('password').value;
            // You can change this to any password you want to share with Mercy
            if (password === "isaaclovesmercy") {
                document.getElementById('loginSection').style.display = 'none';
                document.getElementById('messageSection').style.display = 'block';
            } else {
                alert('Please enter the correct password!');
            }
        }
    </script>
</body>
</html>
