# class-part1
<!DOCTYPE html>
<html lang="ko">
<head>
<meta charset="UTF-8">
<title>relative 부모요소, absolute 자식요소</title>
<style type="text/css">
body{
   margin:0; color:white;
}
.parent{
   position: relative;
   //position: absolute;
   width:300px;
   height:300px;
   background-color:aqua;
   border:1px solid red;
   //margin:auto;
   //left:50%;
   //right:-50%;
}
.child{
   position:absolute;
   
   //position:fixed;
   //position:relative;
   width:50px;
   height:50px;
   
   background-color:blue;
   left:50%;
   bottom:-25px;
   transform:translatex(-50%);
   text-align:center;
}
</style>
</head>
<body>
   <div class="parent">
      <div class="child">CLASS</div>
      </div>
   
</body>
</html>
