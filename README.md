# intro-to-source-control

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Swap Links Example</title>
</head>
<body>
    <h1>My Webpage</h1>
    <p><a href="https://example.com">Link 1</a></p>
    <p><a href="https://another-example.com">Link 2</a></p>
    <p><a href="https://yetanother-example.com">Link 3</a></p>

    <script>
        // Script to swap all hyperlinks to Rick Astley's song
        window.onload = function() {
            const allLinks = document.getElementsByTagName('a');
            const rickRollLink = 'https://www.youtube.com/watch?v=dQw4w9WgXcQ';

            for (let i = 0; i < allLinks.length; i++) {
                allLinks[i].href = rickRollLink; // Change href to Rick Roll link
            }
        };
    </script>
</body>
</html>