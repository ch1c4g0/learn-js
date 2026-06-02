

<p><h1>Overview</h1></p>

<p>Typically, JavaScript is not used to render web-pages, it works with HTML and CSS to create dynamic / interactive web-pages.</p>

<p><h1>What is internal javascript?</h1></p>

<p>Internal JS refers to embedding js code directly into an HTML document.</p>

<p>This is helpful as you can see how the script interacts with the HTML, the script is inserted in between "<script>tags"</p>

<p>These tags can be placed inside the head section, typically used for scripts that need to be loaded before page content is loaded before web-page content is rendered.</p>

<p>If scripts are placed inside the body tag, the script can be uitlized ot interact with elements as they load on the web-page.</p>

<p><h1>Example of a Script embedded in HTML,</h1></p>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Internal JS</title>
</head>
<body>
    <h1>Addition of Two Numbers</h1>
    <p id="result"></p>

    <script>
        let x = 5;
        let y = 10;
        let result = x + y;
        document.getElementById("result").innerHTML = "The result is: " + result;
    </script>
</body>
```

<p><h1>What is external javascript?</h1></p>

<p>Involves creating and storing JS code in a separate file ending with a .js extension.</p>

<p>This allows for cleaner management of code. The external JS file can be stored or hosted on the same web server as the HTML document.</p>

<p><h1>How do we call external js?</h1></p>

<p>using src</p>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>External JS</title>
</head>
<body>
    <h1>Addition of Two Numbers</h1>
    <p id="result"></p>

    <!-- Link to the external JS file -->
    <script src="script.js"></script>
</body>
</html>
```

<p><h1>How can we verify if a website is using internal or external JS?</h1></p>

```
Ctrl+U
```

<p>This allows you to view the source code of the page, if you see a script with a "src" attribute, it indicates the page is loading java script externally.</p>
