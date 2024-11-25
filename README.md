**index.html**

<!DOCTYPE html>
<html lang="en">
<head>
        <title>Simple Collaboration Demo Today</title>
    <link rel="stylesheet" href="style.css">
   </head>
<body>
    <h1>Hello, World!</h1>
    <h2>good morning </h2>
    <p id="message">Hi!How are you</p>
    <button id="changeMessage">Click Me!</button>
    <script src="script.js"></script>
</body>
</html>

**script.js**
document.getElementById("changeMessage").addEventListener("click", function() {
  document.getElementById("message").textContent = "You clicked the button!";
});

**style.css**
echo "body { font-family: Arial, sans-serif; background-color: #f0f0f0; } 
h1 { color: navy; }
