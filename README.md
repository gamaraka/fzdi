<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>صفحة دخول بخلفية سوداء</title>
    <style>
        body {
            background-color: black;
            color: white; /* لتحسين قراءة النص على الخلفية السوداء */
            font-family: Arial, sans-serif;
            height: 100vh;
            margin: 0;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .login-container {
            background-color: rgba(0, 0, 0, 0.7); /* خلفية مع تضليل لصندوق الادخال */
            padding: 20px;
            border-radius: 10px;
            text-align: center;
        }

        input {
            padding: 10px;
            margin: 10px 0;
            width: 100%;
            box-sizing: border-box;
        }

        h1 {
            text-align: center;
        }
    </style>
</head>
<body>

    <div class="login-container">
        <h1>تسجيل الدخول</h1>
        <form action="/login" method="post">
            <label for="password"> password Younes 7oubi🥺:</label>
            <input type="password" id="password" name="password" required>
            <br>
            <input type="submit" value="تسجيل الدخول">
        </form>
    </div>

</body>
</html>

