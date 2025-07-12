<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Scrollable Full Page Image</title>
  <style>
    html, body {
      margin: 0;
      padding: 0;
      height: 100%;
    }

    body {
      background: url('menu.jpg') no-repeat center top;
      background-size: cover;
      background-attachment: scroll; /* Make background scrollable */
      min-height: 250vh; /* Add vertical height to enable scrolling */
    }
  </style>
</head>
<body>
</body>
</html>
