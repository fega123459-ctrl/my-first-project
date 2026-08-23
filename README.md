# my-first-project
My first coding project
<!DOCTYPE html>
<html>
<head>
    <title>My First Website</title>
</head>

<body>
    <h1>Hello! I'm Maxwell 👋</h1>

    <p>I'm learning how to code.</p>

    <button onclick="sayHello()">Click Me</button>

    <p id="message"></p>

    <script>
        function sayHello() {
            document.getElementById("message").textContent =
                "🎉 You just made your first interactive webpage!";
        }
    </script>
</body>
</html>