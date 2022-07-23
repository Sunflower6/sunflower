<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
    <div class="header">
        <h3>OUR MENU</h3>
        <h1>Discover Our Menu</h1>
    </div>

   <div class="lists">
    <div>
        <ul>
            <li><a href="">Pizza</a></li>
            <li><a href="">Calories</a></li>
            <li><a href="">Wraps</a></li>
            <li><a href="">Salads</a></li>
            <li><a href="">Sides</a></li>
            <li><a href="">Pasta Drivers</a></li>
        </ul>
    </div>

    <div>
        <ul>
            <li><a href="">Diners</a></li>
            <li><a href="">Grill $ seafood</a></li>
            <li><a href="">Ice Cream</a></li>
            <li><a href="">Kids</a></li>
        </ul>
    </div>
   </div>

    <div class="pizzaDiv">
        <div>
            <img src="images/images (1).jpg" alt="">
            <h3>Little Caesars Veggie Pizza</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Earum iure vero, sapiente soluta assumenda accusantium distinctio! Cupiditate, ea quasi ducimus voluptates doloribus debitis vel perferendis aut esse, placeat numquam quo!</p>
            <input type="submit" value="order now">
        </div>

        <div>
            <img src="images/images (3).jpg" alt="" >
            <h3>Fratelli Pizza</h3>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Assumenda pariatur, rem odio a, ipsum molestias non aspernatur suscipit nostrum iusto hic dolores totam alias placeat nesciunt minus accusantium maiores incidunt.</p>
            <input type="submit" value="order now">
        </div>

        <div>
            <img src="images/images.jpg" alt="">
            <h3>Pepperoni Pizza</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ab in deleniti odio dolorem iusto fugiat inventore explicabo voluptas sequi natus repudiandae, officiis incidunt modi architecto dolorum, unde quod placeat nostrum!</p>
            <input type="submit" value="order now">
        </div>

        <div>
            <img src="images/istockphoto-182148711-612x612.jpg" alt="">
            <h3>Dodo Pizza</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Non nihil illum a cupiditate iusto veritatis dolores itaque magnam culpa molestias neque totam explicabo adipisci possimus deserunt, sit aliquid id harum.</p>
            <input type="submit" value="order now">
        </div>
    </div>
    
</body>
</html>

<style>
  *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
:root{
    --primary: hsla(247, 87%, -24%, 0.1);
    --secondary: hsla(268, 148%, -54%, 3.575);
}
body{
    margin-left: auto;
    margin-right: auto;
    width: 85%;
    background-image:linear-gradient(135deg, var(--primary), var(--secondary)),
     url(../images/pizza-wood-table-service.jpg);
    background-repeat: no-repeat;
    background-size: cover;
}
.header{
    text-align: center;
    padding: 15px;
}
.header>h3{
    color: orange;

}
.header>h1{
    color: white;
}
.lists ul >li{
    background-color: orange;
    padding: 10px;
    border-radius: 25px;
    list-style: none;
}
.lists ul >li:hover{
    background-color: white;
}
.lists ul >li a:hover{
    color: #f5a107;
}
.lists ul >li a{
    color: white;
    font-size: 25px;
    text-decoration: none;
}
.lists div:nth-child(1) ul {
    display: flex;
    justify-content: space-between;
    margin-left: auto;
    margin-right: auto;
    width: 70%;
}
.lists div:nth-child(2) ul{
    display: flex;
    justify-content: space-between;
    margin-left: auto;
    margin-right: auto;
    width: 70%;
    margin-top: 10px;
}
.pizzaDiv div >img{
    height: 40%;
    width: 75%;
} 
.pizzaDiv{
    display: flex;
    margin-top: 10%;
    margin-left: auto;
    margin-right: auto;
    width: 90%;
    justify-content: space-between;
}
.pizzaDiv div{
    background-color: white;
    width: 20%;
    border: 1px solid lightgray;
    box-shadow: 1px 2px 1px 1px;
    padding: 10px;
    height: 60vh;
    border-radius: 10px;
}
.pizzaDiv div> h3{
    color: #f5a107;
    font-size: 27px;
}
.pizzaDiv div>p{
    color: black;
    font-size: 18px;
    font-weight: 400;
}
.pizzaDiv div>input{
    padding: 5px;
    border-radius: 20px;
    color: white;
    background-color: black;
    font-size: 15px;
    font-weight: 700;
}
  
  </style>
