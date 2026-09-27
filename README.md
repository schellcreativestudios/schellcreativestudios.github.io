# schellcreativestudios.github.io
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Website</title>

  <style>
    body {
      font-family: Arial, sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
      background: #f4f4f4;
    }

    .container {
      text-align: center;
      background: white;
      padding: 30px;
      border-radius: 12px;
      box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
    }

    input {
      padding: 12px;
      width: 300px;
      font-size: 16px;
      border: 1px solid #ccc;
      border-radius: 6px;
    }
  </style>
</head>

<body>

  <div class="container">
    <h1>Change the Tab Name</h1>

    <input
      type="text"
      id="pageName"
      placeholder="Enter a page name..."
    >
  </div>

  <script>
    const input = document.getElementById("pageName");

    input.addEventListener("input", function () {
      document.title = input.value || "My Website";
    });
  </script>

</body>
</html>
