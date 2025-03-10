<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Example</title>
    <style>
        /* Body styles */
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }

        /* Header styles */
        header {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1em 0;
        }

        /* Main content styles */
        .content {
            padding: 20px;
            margin: 0 15px;
            background-color: white;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

      
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My First Webpage</title>
</head>
<body>
    <h1>Welcome to My Webpage</h1>
    <p>This is a paragraph of text that introduces my website.</p>

    <img src="https://via.placeholder.com/150" alt="Placeholder Image" />

    <button onclick="alert('Hello! You clicked the button!')">Click Me!</button>

    <footer>
        <p>&copy; 2025 My Website</p>
    </footer>
</body>
<
// Simple JavaScript program to greet the user
function greetUser() {
  // Prompt the user to enter their name
  let name = prompt("Please enter your name:");

  // Display a greeting message
  if (name) {
    alert("Hello, " + name + "! Welcome to the JavaScript world!");
  } else {
    alert("Hello! Welcome to the JavaScript world!");
  }
}

// Call the function to greet the user
greetUser();
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JavaScript Example</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            padding-top: 50px;
        }

        button {
            padding: 10px 20px;
            font-size: 16px;
            background-color: #4CAF50;
            color: white;
            border: none;
            cursor: pointer;
        }

        button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <h1 id="message">Hello, Welcome to My JavaScript Page!</h1>
    
    <button onclick="changeText()">Click to Change Text</button>
    <br><br>
    <button onclick="askName()">Click to Enter Your Name</button>

    <script>
        // Function to change the text content of the h1 element
        function changeText() {
            document.getElementById("message").innerHTML = "You clicked the button!";
        }

        // Function to prompt the user for their name and display a greeting
        function askName() {
            var name = prompt("What's your name?");
            if (name != null && name != "") {
                alert("Hello, " + name + "! Welcome to my page.");
            } else {
                alert("You didn't enter a name.");
            }
        }
    </script>
</body>
</html>
