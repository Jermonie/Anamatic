<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AnaMatic.Inc</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0; /* Set your background color here */
        }
        .container {
            text-align: center;
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
        }
        h1 {
            color: #ffffff; /* White text color */
            font-size: 36px;
        }
        button {
            padding: 10px 20px;
            font-size: 18px;
            background-color: #007bff; /* Blue button color */
            color: #ffffff;
            border: none;
            cursor: pointer;
            transition: background-color 0.3s;
        }
        button:hover {
            background-color: #0056b3; /* Darker blue on hover */
        }
        input[type="email"] {
            padding: 10px;
            font-size: 16px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Watch Epic Shows And Movies</h1>
        <button onclick="redirect()">Sign Up</button>
    </div>

    <script>
        function redirect() {
            var email = prompt("Please enter your email:");
            if (email !== null && email !== "") {
                window.location.href = "https://AnaMatic.Inc/Shows/325/?email=" + encodeURIComponent(email);
            }
        }
    </script>
</body>
</html>
