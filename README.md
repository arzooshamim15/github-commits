# github-commits


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="./style.css">
    <title>Document</title>
</head>
<body>
    <div class="container">
    <div class="box box1">box1</div>
    <div class="box box2">box2</div>
    <div class="box box3">box3</div>
    <div class="box box4">box 4</div>
    <div class="box box5">box 5</div>
</body>
</html>


.container{
    border: 2px solid black;
    display: grid;
    grid-template-columns: 120px 100px;
    grid-template-rows: 100px 100px 100px;
}
.box{
    border: 2px solid red;
    width: 55px;
    height: 55px;
}
.box3{
    grid-column: 2/1;
    
}
