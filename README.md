
Sentence generation app
<!DOCTYPE html>
<html>
<head>
  <title>Generator</title>
  <style>
    /* Add some basic styling */
    body {
      text-align: center;
      margin-top: 100px;
    }
    input {
      padding: 10px;
      font-size: 16px;
    }
    button {
      padding: 10px 20px;
      font-size: 16px;
    }
  </style>
</head>
<body>
  <h1>Generate Page</h1>
  <form>
    <input type="text" id="inputText" placeholder="Enter text">
    <br><br>
    <button type="button" onclick="generateText()">Generate</button>
  </form>

  <script>
    function generateText() {
      var input = document.getElementById("inputText").value;
      // Add your generate logic here
      
      // Example: Display generated text in console
      console.log("Generated Text:", input);
    }
  </script>
</body>
</html>
