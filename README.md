# HTML page

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta name="robots" content="noindex, nofollow">
    <title>A web page</title>
    <link rel="icon" href="https://www.debian.org/favicon.ico" type="image/x-icon">
</head>
<body>
    <main>
        <p>Content.</p>
    </main>
</body>
</html>
```

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta name="description" content="Semantic web page">
    <meta name="robots" content="noindex, nofollow">
    <title>Semantic web page</title>
    <link rel="icon" href="https://www.debian.org/favicon.ico" type="image/x-icon">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/normalize/8.0.1/normalize.css">
    <style>
        body {
            background: white;
            color: darkblue;
        }
    </style>
    <script src="https://ajax.googleapis.com/ajax/libs/d3js/7.9.0/d3.min.js"></script> 
    <script>
        window.echo = function (msg) {
            console.log(msg);
        }
        window.onload = function () {
            echo('Start.');
        }
    </script>
</head>
<body>
    <header>
        <h1>Title</h1>
    </header>
  
    <main>
        <article>
            <h2>An Article</h2>
            <p>Content.</p>
            <section>
                <h3>A Section Within the Article</h3>
                <p>Provides more detailed information.</p>
            </section>
        </article>
    </main>
  
    <footer>
        <p>&copy; 2025 Company</p>
        <p><a href="https://browsehappy.com/">Update your browser for a better experience.</a></p>
    </footer>
</body>
</html>
```
