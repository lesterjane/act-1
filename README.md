
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Three Boxes with Images and Text</title>
  <style>
     {
      width: 200px;
      height: 250px;
      margin: 20px;
      display: inline-block; 
      text-align: center; 
      border: 1px solid #ccc; 
      padding: 10px;
    }
 {
      background-color: #ff9999; 
    }
    #box2 {
      background-color: #99ff99;
    }
    #box3 {
      background-color: #9999ff; 
    }
 {
      max-width: 150px; 
      max-height: 150px;
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

