# balamurugan
hello guys welcome to balamurugan website
<!DOCTYPE html>
<html>
<head>
  <title>BMW Car Animation</title>
  <style>
    body {
      background-color: black;
      overflow: hidden;
      margin: 0;
    }

    .road {
      width: 100%;
      height: 100vh;
      position: relative;
    }

    .car {
      width: 200px;
      position: absolute;
      bottom: 50px;
      left: -250px;
      animation: drive 5s linear infinite;
    }

    @keyframes drive {
      0% { left: -250px; }
      100% { left: 100%; }
    }
  </style>
</head>
<body>
  <div class="road">
    <img class="car" src="https://i.ibb.co/6Rf7JvT/bmw-car.png" alt="

