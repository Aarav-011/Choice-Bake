<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">

</head>
<body>

  <script>
    const totalPages = 12; // 👈 Change this if you have more pages
    for (let i = 1; i <= totalPages; i++) {
      const img = document.createElement("img");
      img.src = `menu${i}.jpg`; // Or .png if that's what you exported
      img.alt = `Menu Page ${i}`;
      document.body.appendChild(img);
    }
  </script>

</body>
</html>
