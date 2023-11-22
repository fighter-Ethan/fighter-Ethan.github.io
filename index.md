<!-- index.html -->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <title>Am I HTML already?</title>
Yes,<br>I am!
<style>
.button{
    position: relative;
    border: none;
    transition: .4s ease-in;
    z-index: 1;
  }
.button::before,
.button::after{
    position: absolute;
    content: "";
    z-index: -1;
  }
.btn-1:hover {
    border: 2px solid #ff96ad;
    color: #ff96ad;
    background-color: #17181c;
  }
</style>
</head>
<body>
<button class="btn-1">Button 1</button>
</body>
</html>
