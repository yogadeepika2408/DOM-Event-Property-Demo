# DOM-Event-Property-Demo
A simple webpage demonstrating DOM event handling using the onclick property.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h2>DOM-Model Event </h2>
    <button id="btn">Click Me</button>
    <p id="msg" class="out"></p>
    <script>
        document.getElementById("btn").onclick = function() {
            document.getElementById("msg").innerText =
            "Handled with DOM property";
        };
    </script>
</body>
</html>
