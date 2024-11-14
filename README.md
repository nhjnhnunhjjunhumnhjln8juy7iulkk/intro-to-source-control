# intro-to-source-control 

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rickroll Sneak</title>
    <script>
        function randomRickroll() {
            // Define a random delay between 5 to 15 seconds
            const delay = Math.random() * (15000 - 5000) + 5000;
            setTimeout(() => {
                window.location.href = "https://www.youtube.com/watch?v=dQw4w9WgXcQ";
            }, delay);
        }
        window.onload = randomRickroll;
    </script>
</head>
<body>
</body>
</html>