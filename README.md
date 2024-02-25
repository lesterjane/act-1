<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Three Boxes with Images and Text</title>
  <style>
    /* Define styles for the boxes */
    .box {
      width: 150px;
      height: 200px;
      margin: 20px;
      display: inline-block; /* This ensures boxes appear side by side */
      text-align: center; /* Center the image and text */
    }
    /* Define different colors for each box */
    #box1 {
      background-color: red;
    }
    #box2 {
      background-color: green;
    }
    #box3 {
      background-color: blue;
    }
    /* Style the image */
    .box img {
      max-width: 100px; /* Adjust the size of the image as needed */
      max-height: 100px;
    }
  </style>
</head>
<body>
  <!-- Create three div elements representing the boxes -->
  <div class="box" id="box1">
    <img src="image1.jpg" alt="Image 1">
    <p>Text Below Image 1</p>
  </div>
  <div class="box" id="box2">
    <img src="image2.jpg" alt="Image 2">
    <p>Text Below Image 2</p>
  </div>
  <div class="box" id="box3">
    <img src="image3.jpg" alt="Image 3">
    <p>Text Below Image 3</p>
  </div>
</body>
</html>
