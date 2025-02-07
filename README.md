<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Valentine 💖</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #ffe4e1;
            text-align: center;
        }
        .container {
            max-width: 600px;
            margin: 50px auto;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }
        h1 {
            color: #ff1493;
        }
        img {
            max-width: 100%;
            border-radius: 10px;
        }
        .love-message {
            font-size: 18px;
            color: #d63384;
            margin-top: 20px;
        }
        .button {
            display: inline-block;
            padding: 10px 20px;
            background-color: #ff69b4;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            margin-top: 10px;
            cursor: pointer;
        }
        input {
            padding: 10px;
            width: 80%;
            margin-top: 10px;
            border-radius: 5px;
            border: 1px solid #ff69b4;
            text-align: center;
        }
    </style>
    <script>
        function checkCode() {
            var code = document.getElementById('code').value;
            if (code === '20072024') {
                window.location.href = 'verify.html';
            } else {
                alert('Wrong code! Try again.');
            }
        }
    </script>
</head>
<body>
    <div class="container">
        <h1>Happy Valentine 💕</h1>
        <img src="C:\Users\weZpeD\background" alt="Love Image">
        <p class="love-message">You are the best thing that ever happened to me. I love you! 💖</p>
        <input type="text" id="code" placeholder="Enter Anniversary Date (DD/MM/YYYY)">
        <button class="button" onclick="checkCode()">Submit</button>
    </div>
</body>
</html>

