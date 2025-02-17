
<!DOCTYPE html>
<!-- saved from url=(0075)file:///C:/Users/Priyanka%20Kundu/OneDrive/Desktop/office%202024/index.html -->
<html lang="en"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
    
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bus.com - Sign In</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f4f4f4;
        }
        .container {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            width: 300px;
            text-align: center;
        }
        h2, h3 {
            margin: 0;
        }
        .input-box {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .sign-in-btn, .sign-up-btn {
            width: 100%;
            padding: 10px;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
            margin-top: 10px;
        }
        .sign-in-btn {
            background: #0073b1;
        }
        .sign-up-btn {
            background: #28a745;
        }
    </style>
<style type="text/css" id="operaUserStyle"></style></head>
<body>

    <div class="container">
        <h2>Welcome to</h2>
        <h3>Bus.com</h3>
        <p>Stay updated on your professional world</p>
        
        <input type="text" class="input-box" placeholder="Email or Phone">
        <input type="password" class="input-box" placeholder="Password">
        
        <button class="sign-in-btn" onclick="redirectToSignIn()">Sign In</button>
        <button class="sign-up-btn" onclick="redirectToSignUp()">Sign Up</button>
    </div>

    <script>
        function redirectToSignIn() {
            window.location.href = "welcome.html"; // Redirect after successful sign-in
        }

        function redirectToSignUp() {
            window.location.href = "register.html";
        }
    </script>



</body></html>
