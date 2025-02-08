<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio Website</title>
    <style>
        button {
            padding: 10px 20px;
            font-size: 16px;
            background-color: #007BFF;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        button:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>

    <!-- Button using direct link -->
    <a href="https://anishnandamuri.com" target="_blank">
        <button>Visit My Website</button>
    </a>

    <!-- Alternative button using JavaScript -->
    <button id="redirectButton">Go to My Website</button>

    <script>
        document.getElementById("redirectButton").addEventListener("click", function() {
            window.location.href = "https://anishnandamuri.com";
        });
    </script>

</body>
</html>
