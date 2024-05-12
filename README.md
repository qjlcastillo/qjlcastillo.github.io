<!DOCTYPE html>
<html>
<head>
  <title>File Display</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 20px;
      background-color: #f5f5f5;
    }
    .container {
      max-width: 800px;
      margin: 0 auto;
      background-color: #fff;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
      padding: 20px;
    }
    h1 {
      text-align: center;
      margin-top: 0;
    }
    .file-list {
      list-style: none;
      padding: 0;
      margin: 0;
    }
    .file-list li {
      margin-bottom: 10px;
      border-bottom: 1px solid #ddd;
      padding-bottom: 5px;
    }
    .file-list li:last-child {
      border-bottom: none;
    }
    .file-list li a {
      color: #337ab7;
      text-decoration: none;
    }
    .file-list li a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>File Display</h1>
    <ul class="file-list">
      <li><a href="example.jpg">Example Image</a></li>
      <li><a href="example.pdf">Example PDF</a></li>
      <li><a href="example.txt">Example Text File</a></li>
      <!-- Add more file links here -->
    </ul>
  </div>
</body>
</html>
