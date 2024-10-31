<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Automatic Multiple Link Click Test</title>
</head>
<body>
    <h1>Automatic Link Click Test Page</h1>
    <p>This page will automatically click the links below when you open it.</p>

    <!-- Target links that will be clicked automatically -->
    <a href="https://youtube.com" class="auto-click-link" target="_blank">Go to YouTube</a><br>
    <a href="https://example.com" class="auto-click-link" target="_blank">Go to Example.com</a><br>
    <a href="https://google.com" class="auto-click-link" target="_blank">Go to Google</a><br>
    <a href="https://facebook.com" class="auto-click-link" target="_blank">Go to Facebook</a><br>
    <a href="https://twitter.com" class="auto-click-link" target="_blank">Go to Twitter</a><br>
    <a href="https://instagram.com" class="auto-click-link" target="_blank">Go to Instagram</a><br>
    <a href="https://linkedin.com" class="auto-click-link" target="_blank">Go to LinkedIn</a><br>
    <a href="https://github.com" class="auto-click-link" target="_blank">Go to GitHub</a><br>
    <a href="https://reddit.com" class="auto-click-link" target="_blank">Go to Reddit</a><br>
    <a href="https://stackoverflow.com" class="auto-click-link" target="_blank">Go to Stack Overflow</a><br>

    <script>
        window.onload = function() {
            setTimeout(function() {
                // Get all links with the class 'auto-click-link'
                let linksToClick = document.querySelectorAll("a.auto-click-link");

                // Function to click links sequentially with delay
                let clickIndex = 0;
                function clickNextLink() {
                    if (clickIndex < linksToClick.length) {
                        linksToClick[clickIndex].click(); // Click the current link
                        clickIndex++;
                        setTimeout(clickNextLink, 2000); // Click the next link after 2 seconds
                    }
                }

                clickNextLink(); // Start clicking links
            }, 1000); // Initial delay before starting clicks
        };
    </script>
</body>
</html>

