<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
  body {
    margin: 0;
    padding: 0;
    font-family: Arial, sans-serif;
    background-color: black;
    color: white;
  }

  header {
    background-color: red;
    text-align: center;
    padding: 20px;
  }

  h1 {
    margin: 0;
  }

  main {
    padding: 20px;
  }

  .download-section {
    display: flex;
    justify-content: space-around;
    margin-top: 20px;
  }

  .download-item {
    text-align: center;
    background-color: red;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.5);
    transition: transform 0.3s ease;
  }

  .download-item:hover {
    transform: scale(1.05);
  }

  .download-button {
    display: inline-block;
    padding: 10px 20px;
    background-color: black;
    color: white;
    text-decoration: none;
    border-radius: 5px;
    transition: background-color 0.3s ease;
  }

  .download-button:hover {
    background-color: #333;
  }
</style>
<title>Red and Black Downloads</title>
</head>
<body>
  <header>
    <h1>Red and Black Downloads</h1>
  </header>
  <main>
    <div class="download-section">
      <div class="download-item">
        <h2>Download File 1</h2>
        <a href="#" class="download-button">Download</a>
      </div>
      <div class="download-item">
        <h2>Download File 2</h2>
        <a href="#" class="download-button">Download</a>
      </div>
    </div>
  </main>
</body>
</html>
