<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="./style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.1/css/all.min.css" integrity="sha512-KfkfwYDsLkIlwQp6LFnl8zNdLGxu9YAA1QvwINks4PhcElQSvqcyVLLD9aMhXd13uQjoXtEKNosOWaZqXgel0g==" crossorigin="anonymous" referrerpolicy="no-referrer" />
</head>
<body>
    <nav>
        <div class="logo">
            <img src="./img/logo-white.png" alt="">
        </div>
        <div class="menu">
            <div class="menu-item">
                <i class="fa-solid fa-magnifying-glass"></i>
            </div>
            <div class="menu-item">
                <i class="fa-solid fa-film"></i>
            </div>
            <div class="menu-item">
                <i class="fa-solid fa-bars"></i>
            </div>
        </div>
    </nav>
    <div class="big">
        <div class="deed">
            <div class="a1">
                <img src="./img/1.jpg" alt="">
            </div>
            <div class="a2">
                <img src="./img/2.jpg" alt="">
            </div>
            <div class="a3">
                <img src="./img/3.jpg" alt="">
            </div>
            <div class="a4">
                <img src="./img/4.jpg" alt="">
            </div>
        </div>
        <div class="dund">
            <div class="a1">
                <img src="./img/5.jpg" alt="">
            </div>
            <div class="a2">
                <img src="./img/6.jpg" alt="">
            </div>
            <div class="a3">
                <img src="./img/7.jpg" alt="">
            </div>
            <div class="a4">
                <img src="./img/8.png" alt="">
            </div>
        </div>
        <div class="dood">
            <div class="a1">
                <img src="./img/9.png" alt="">
            </div>
            <div class="a2">
                <img src="./img/10.jpg" alt="">
            </div>
            <div class="a3">
                <img src="./img/11.jpg" alt="">
            </div>
            <div class="a4">
                <img src="./img/12.jpg" alt="">
            </div>
        </div>
</body>
</html>
  ------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  css:
  *{
    margin: 0%;
    padding: 0%;
    box-sizing: border-box;
}
Body{
    background-color: #1d1d1d;
}
nav{
    width: 100%;
    height: 61px;
    display: flex;
    justify-content: space-between;
    border-bottom: 1px solid #393939 ;

}
nav .logo{
    width: 15%;
    height: 100%;
}
nav .logo img{
    width: 100%;
    height: 100%;
    object-fit: contain;
    margin-left: 10px;
}
nav .menu{
    width: 15%;
    height: 100%;
    display: flex;
}
nav .menu .menu-item{
    width: 33%;
    height:100%;
    display: flex;
    justify-content: center;
    align-items: center;
    border-left:1px solid #393939;
}
nav .menu .menu-item i{
    color: #666;
    font-size: 20px;
}
.big{
    width: 100%;
    height: 600px;
}
.big .deed{
    width: 100%;
    height: 200px;
    display: flex;
    gap: 10px;
    margin-top: 20px;
    margin-bottom: 20px;
    justify-content: space-around;
    align-items: center;
}
.big .deed .a1{
    width: 25%;
    height: 100%;
}
.big .deed .a2{
    width: 25%;
    height: 100%;
}
.big .deed .a3{
    width: 25%;
    height: 100%;
}
.big .deed .a4{
    width: 25%;
    height: 100%;
}
.big .deed .a1 img{
    width: 100%;
    height: 100%;
    object-fit: contain;
}
.big .deed .a2 img{
    width: 100%;
    height: 100%;
    object-fit: contain;
}
.big .deed .a3 img{
    width: 100%;
    height: 100%;
    object-fit: contain;
}
.big .deed .a4 img{
    width: 100%;
    height: 100%;
    object-fit: contain;
}
.big .dund{
    width: 100%;
    height: 200px;
    display: flex;
    gap: 10px;
    margin-top: 20px;
    margin-bottom: 20px;
    justify-content: space-around;
    align-items: center;
}
.big .dund .a1{
    width: 25%;
    height: 100%;
}
.big .dund .a2{
    width: 25%;
    height: 100%;
}
.big .dund .a3{
    width: 25%;
    height: 100%;
}
.big .dund .a4{
    width: 25%;
    height: 100%;
}
.big .dund .a1 img{
    width: 100%;
    height: 100%;
    object-fit: contain;
}
.big .dund .a2 img{
    width: 100%;
    height: 100%;
    object-fit: contain;
}
.big .dund .a3 img{
    width: 100%;
    height: 100%;
    object-fit: contain;
}
.big .dund .a4 img{
    width: 100%;
    height: 100%;
    object-fit: contain;
}
.big .dood{
    width: 100%;
    height: 200px;
    display: flex;
    gap: 10px;
    margin-top: 20px;
    justify-content: space-around;
    align-items: center;
}
.big .dood .a1{
    width: 25%;
    height: 100%;
}
.big .dood .a2{
    width: 25%;
    height: 100%;
}
.big .dood .a3{
    width: 25%;
    height: 100%;
}
.big .dood .a4{
    width: 25%;
    height: 100%;
}
.big .dood .a1 img{
    width: 100%;
    height: 100%;
    object-fit: contain;
}
.big .dood .a2 img{
    width: 100%;
    height: 100%;
    object-fit: contain;
}
.big .dood .a3 img{
    width: 100%;
    height: 100%;
    object-fit: contain;
}
.big .dood .a4 img{
    width: 100%;
    height: 100%;
    object-fit: contain;
}
