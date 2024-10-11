<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Free In-Game Tips for Diwali</title>
    <style>
        body {
            background: linear-gradient(135deg, #1d1f27, #1a2d5e);
            font-family: Arial, sans-serif;
            color: #fff;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }

        .container {
            background: #111;
            border-radius: 15px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.5);
            padding: 20px;
            max-width: 350px;
            width: 100%;
            text-align: center;
        }

        h1 {
            font-size: 24px;
            margin-bottom: 20px;
        }

        input[type="text"], input[type="email"] {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: none;
            border-radius: 5px;
        }

        input[type="submit"] {
            background: #1a73e8;
            color: #fff;
            padding: 10px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        input[type="submit"]:hover {
            background: #0a5ec5;
        }

        .note {
            margin-top: 20px;
            font-size: 12px;
            color: #bbb;
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>Free In-Game Tips for Diwali</h1>
        <form action="submit_form.php" method="POST">
            <input type="text" name="name" placeholder="Your Name" required><br>
            <input type="email" name="email" placeholder="Your Email" required><br>
            <input type="text" name="uid" placeholder="Game UID (Optional)"><br>
            <input type="text" name="favorite_item" placeholder="Favorite In-Game Item" required><br>
            <input type="submit" value="Submit">
        </form>
        <p class="note">This website is only for Diwali and will close after the celebration.</p>
    </div>

</body>
</html>
