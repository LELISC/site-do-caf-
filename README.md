# site-do-caf-
site do café desenvolvido no html com o auxilio do tutorial do youutube

HTML5

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>complete responsive coffee shop website design</title>

    <!-- font awesome cdn link  -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">

    <!-- custom css file link  -->
    <link rel="stylesheet" href="css/style.css">

</head>
<body>
    
<!-- header section starts  -->

<header class="header">

    <a href="#" class="logo">
        <img src="images/logo.png" alt="">
    </a>

    <nav class="navbar">
        <a href="#home">home</a>
        <a href="#about">about</a>
        <a href="#menu">menu</a>
        <a href="#products">products</a>
        <a href="#review">review</a>
        <a href="#contact">contact</a>
        <a href="#blogs">blogs</a>
    </nav>

    <div class="icons">
        <div class="fas fa-search" id="search-btn"></div>
        <div class="fas fa-shopping-cart" id="cart-btn"></div>
        <div class="fas fa-bars" id="menu-btn"></div>
    </div>

    <div class="search-form">
        <input type="search" id="search-box" placeholder="search here...">
        <label for="search-box" class="fas fa-search"></label>
    </div>

    <div class="cart-items-container">
        <div class="cart-item">
            <span class="fas fa-times"></span>
            <img src="images/cart-item-1.png" alt="">
            <div class="content">
                <h3>cart item 01</h3>
                <div class="price">$15.99/-</div>
            </div>
        </div>
        <div class="cart-item">
            <span class="fas fa-times"></span>
            <img src="images/cart-item-2.png" alt="">
            <div class="content">
                <h3>cart item 02</h3>
                <div class="price">$15.99/-</div>
            </div>
        </div>
        <div class="cart-item">
            <span class="fas fa-times"></span>
            <img src="images/cart-item-3.png" alt="">
            <div class="content">
                <h3>cart item 03</h3>
                <div class="price">$15.99/-</div>
            </div>
        </div>
        <div class="cart-item">
            <span class="fas fa-times"></span>
            <img src="images/cart-item-4.png" alt="">
            <div class="content">
                <h3>cart item 04</h3>
                <div class="price">$15.99/-</div>
            </div>
        </div>
        <a href="#" class="btn">checkout now</a>
    </div>

</header>

<!-- header section ends -->

<!-- home section starts  -->

<section class="home" id="home">

    <div class="content">
        <h3>fresh coffee in the morning</h3>
        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Placeat labore, sint cupiditate distinctio tempora reiciendis.</p>
        <a href="#" class="btn">get yours now</a>
    </div>

</section>

<!-- home section ends -->

<!-- about section starts  -->

<section class="about" id="about">

    <h1 class="heading"> <span>about</span> us </h1>

    <div class="row">

        <div class="image">
            <img src="images/about-img.jpeg" alt="">
        </div>

        <div class="content">
            <h3>what makes our coffee special?</h3>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatibus qui ea ullam, enim tempora ipsum fuga alias quae ratione a officiis id temporibus autem? Quod nemo facilis cupiditate. Ex, vel?</p>
            <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Odit amet enim quod veritatis, nihil voluptas culpa! Neque consectetur obcaecati sapiente?</p>
            <a href="#" class="btn">learn more</a>
        </div>

    </div>

</section>

<!-- about section ends -->

<!-- menu section starts  -->

<section class="menu" id="menu">

    <h1 class="heading"> our <span>menu</span> </h1>

    <div class="box-container">

        <div class="box">
            <img src="images/menu-1.png" alt="">
            <h3>tasty and healty</h3>
            <div class="price">$15.99 <span>20.99</span></div>
            <a href="#" class="btn">add to cart</a>
        </div>

        <div class="box">
            <img src="images/menu-2.png" alt="">
            <h3>tasty and healty</h3>
            <div class="price">$15.99 <span>20.99</span></div>
            <a href="#" class="btn">add to cart</a>
        </div>

        <div class="box">
            <img src="images/menu-3.png" alt="">
            <h3>tasty and healty</h3>
            <div class="price">$15.99 <span>20.99</span></div>
            <a href="#" class="btn">add to cart</a>
        </div>

        <div class="box">
            <img src="images/menu-4.png" alt="">
            <h3>tasty and healty</h3>
            <div class="price">$15.99 <span>20.99</span></div>
            <a href="#" class="btn">add to cart</a>
        </div>

        <div class="box">
            <img src="images/menu-5.png" alt="">
            <h3>tasty and healty</h3>
            <div class="price">$15.99 <span>20.99</span></div>
            <a href="#" class="btn">add to cart</a>
        </div>

        <div class="box">
            <img src="images/menu-6.png" alt="">
            <h3>tasty and healty</h3>
            <div class="price">$15.99 <span>20.99</span></div>
            <a href="#" class="btn">add to cart</a>
        </div>

    </div>

</section>

<!-- menu section ends -->

<section class="products" id="products">

    <h1 class="heading"> our <span>products</span> </h1>

    <div class="box-container">

        <div class="box">
            <div class="icons">
                <a href="#" class="fas fa-shopping-cart"></a>
                <a href="#" class="fas fa-heart"></a>
                <a href="#" class="fas fa-eye"></a>
            </div>
            <div class="image">
                <img src="images/product-1.png" alt="">
            </div>
            <div class="content">
                <h3>fresh coffee</h3>
                <div class="stars">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star-half-alt"></i>
                </div>
                <div class="price">$15.99 <span>$20.99</span></div>
            </div>
        </div>

        <div class="box">
            <div class="icons">
                <a href="#" class="fas fa-shopping-cart"></a>
                <a href="#" class="fas fa-heart"></a>
                <a href="#" class="fas fa-eye"></a>
            </div>
            <div class="image">
                <img src="images/product-2.png" alt="">
            </div>
            <div class="content">
                <h3>fresh coffee</h3>
                <div class="stars">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star-half-alt"></i>
                </div>
                <div class="price">$15.99 <span>$20.99</span></div>
            </div>
        </div>

        <div class="box">
            <div class="icons">
                <a href="#" class="fas fa-shopping-cart"></a>
                <a href="#" class="fas fa-heart"></a>
                <a href="#" class="fas fa-eye"></a>
            </div>
            <div class="image">
                <img src="images/product-3.png" alt="">
            </div>
            <div class="content">
                <h3>fresh coffee</h3>
                <div class="stars">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star-half-alt"></i>
                </div>
                <div class="price">$15.99 <span>$20.99</span></div>
            </div>
        </div>

    </div>

</section>

<!-- review section starts  -->

<section class="review" id="review">

    <h1 class="heading"> customer's <span>review</span> </h1>

    <div class="box-container">

        <div class="box">
            <img src="images/quote-img.png" alt="" class="quote">
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Animi nulla sit libero nemo fuga sequi nobis? Necessitatibus aut laborum, nisi quas eaque laudantium consequuntur iste ex aliquam minus vel? Nemo.</p>
            <img src="images/pic-1.png" class="user" alt="">
            <h3>john deo</h3>
            <div class="stars">
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star-half-alt"></i>
            </div>
        </div>

        <div class="box">
            <img src="images/quote-img.png" alt="" class="quote">
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Animi nulla sit libero nemo fuga sequi nobis? Necessitatibus aut laborum, nisi quas eaque laudantium consequuntur iste ex aliquam minus vel? Nemo.</p>
            <img src="images/pic-2.png" class="user" alt="">
            <h3>john deo</h3>
            <div class="stars">
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star-half-alt"></i>
            </div>
        </div>
        
        <div class="box">
            <img src="images/quote-img.png" alt="" class="quote">
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Animi nulla sit libero nemo fuga sequi nobis? Necessitatibus aut laborum, nisi quas eaque laudantium consequuntur iste ex aliquam minus vel? Nemo.</p>
            <img src="images/pic-3.png" class="user" alt="">
            <h3>john deo</h3>
            <div class="stars">
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star"></i>
                <i class="fas fa-star-half-alt"></i>
            </div>
        </div>

    </div>

</section>

<!-- review section ends -->

<!-- contact section starts  -->

<section class="contact" id="contact">

    <h1 class="heading"> <span>contact</span> us </h1>

    <div class="row">

        <iframe class="map" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d30153.788252261566!2d72.82321484621745!3d19.141690214227783!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3be7b63aceef0c69%3A0x2aa80cf2287dfa3b!2sJogeshwari%20West%2C%20Mumbai%2C%20Maharashtra%20400047!5e0!3m2!1sen!2sin!4v1629452077891!5m2!1sen!2sin" allowfullscreen="" loading="lazy"></iframe>

        <form action="">
            <h3>get in touch</h3>
            <div class="inputBox">
                <span class="fas fa-user"></span>
                <input type="text" placeholder="name">
            </div>
            <div class="inputBox">
                <span class="fas fa-envelope"></span>
                <input type="email" placeholder="email">
            </div>
            <div class="inputBox">
                <span class="fas fa-phone"></span>
                <input type="number" placeholder="number">
            </div>
            <input type="submit" value="contact now" class="btn">
        </form>

    </div>

</section>

<!-- contact section ends -->

<!-- blogs section starts  -->

<section class="blogs" id="blogs">

    <h1 class="heading"> our <span>blogs</span> </h1>

    <div class="box-container">

        <div class="box">
            <div class="image">
                <img src="images/blog-1.jpeg" alt="">
            </div>
            <div class="content">
                <a href="#" class="title">tasty and refreshing coffee</a>
                <span>by admin / 21st may, 2021</span>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Non, dicta.</p>
                <a href="#" class="btn">read more</a>
            </div>
        </div>

        <div class="box">
            <div class="image">
                <img src="images/blog-2.jpeg" alt="">
            </div>
            <div class="content">
                <a href="#" class="title">tasty and refreshing coffee</a>
                <span>by admin / 21st may, 2021</span>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Non, dicta.</p>
                <a href="#" class="btn">read more</a>
            </div>
        </div>

        <div class="box">
            <div class="image">
                <img src="images/blog-3.jpeg" alt="">
            </div>
            <div class="content">
                <a href="#" class="title">tasty and refreshing coffee</a>
                <span>by admin / 21st may, 2021</span>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Non, dicta.</p>
                <a href="#" class="btn">read more</a>
            </div>
        </div>

    </div>

</section>

<!-- blogs section ends -->

<!-- footer section starts  -->

<section class="footer">

    <div class="share">
        <a href="#" class="fab fa-facebook-f"></a>
        <a href="#" class="fab fa-twitter"></a>
        <a href="#" class="fab fa-instagram"></a>
        <a href="#" class="fab fa-linkedin"></a>
        <a href="#" class="fab fa-pinterest"></a>
    </div>

    <div class="links">
        <a href="#">home</a>
        <a href="#">about</a>
        <a href="#">menu</a>
        <a href="#">products</a>
        <a href="#">review</a>
        <a href="#">contact</a>
        <a href="#">blogs</a>
    </div>

    <div class="credit">created by <span>mr. web designer</span> | all rights reserved</div>

</section>

<!-- footer section ends -->

















<!-- custom js file link  -->
<script src="js/script.js"></script>

</body>
</html>

JAVA SCRIPT

let navbar = document.querySelector('.navbar');

document.querySelector('#menu-btn').onclick = () =>{
    navbar.classList.toggle('active');
    searchForm.classList.remove('active');
    cartItem.classList.remove('active');
}

let searchForm = document.querySelector('.search-form');

document.querySelector('#search-btn').onclick = () =>{
    searchForm.classList.toggle('active');
    navbar.classList.remove('active');
    cartItem.classList.remove('active');
}

let cartItem = document.querySelector('.cart-items-container');

document.querySelector('#cart-btn').onclick = () =>{
    cartItem.classList.toggle('active');
    navbar.classList.remove('active');
    searchForm.classList.remove('active');
}


css

window.onscroll = () =>{
    navbar.classList.remove('active');
    searchForm.classList.remove('active');
    cartItem.classList.remove('active');
}

@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@100;300;400;500;700&display=swap');

:root{
    --main-color:#d3ad7f;
    --black:#13131a;
    --bg:#010103;
    --border:.1rem solid rgba(255,255,255,.3);
}

*{
    font-family: 'Roboto', sans-serif;
    margin:0; padding:0;
    box-sizing: border-box;
    outline: none; border:none;
    text-decoration: none;
    text-transform: capitalize;
    transition: .2s linear;
}

html{
    font-size: 62.5%;
    overflow-x: hidden;
    scroll-padding-top: 9rem;
    scroll-behavior: smooth;
}

html::-webkit-scrollbar{
    width: .8rem;
}

html::-webkit-scrollbar-track{
    background: transparent;
}

html::-webkit-scrollbar-thumb{
    background: #fff;
    border-radius: 5rem;
}

body{
    background: var(--bg);
}

section{
    padding:2rem 7%;
}

.heading{
    text-align: center;
    color:#fff;
    text-transform: uppercase;
    padding-bottom: 3.5rem;
    font-size: 4rem;
}

.heading span{
    color:var(--main-color);
    text-transform: uppercase;
}

.btn{
    margin-top: 1rem;
    display: inline-block;
    padding:.9rem 3rem;
    font-size: 1.7rem;
    color:#fff;
    background: var(--main-color);
    cursor: pointer;
}

.btn:hover{
    letter-spacing: .2rem;
}

.header{
    background: var(--bg);
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding:1.5rem 7%;
    border-bottom: var(--border);
    position: fixed;
    top:0; left: 0; right: 0;
    z-index: 1000;
}

.header .logo img{
    height: 6rem;
}

.header .navbar a{
    margin:0 1rem;
    font-size: 1.6rem;
    color:#fff;
}

.header .navbar a:hover{
    color:var(--main-color);
    border-bottom: .1rem solid var(--main-color);
    padding-bottom: .5rem;
}

.header .icons div{
    color:#fff;
    cursor: pointer;
    font-size: 2.5rem;
    margin-left: 2rem;
}

.header .icons div:hover{
    color:var(--main-color);
}

#menu-btn{
    display: none;
}

.header .search-form{
    position: absolute;
    top:115%; right: 7%;
    background: #fff;
    width: 50rem;
    height: 5rem;
    display: flex;
    align-items: center;
    transform: scaleY(0);
    transform-origin: top;
}

.header .search-form.active{
    transform: scaleY(1);
}

.header .search-form input{
    height: 100%;
    width: 100%;
    font-size: 1.6rem;
    color:var(--black);
    padding:1rem;
    text-transform: none;
}

.header .search-form label{
    cursor: pointer;
    font-size: 2.2rem;
    margin-right: 1.5rem;
    color:var(--black);
}

.header .search-form label:hover{
    color:var(--main-color);
}

.header .cart-items-container{
    position: absolute;
    top:100%; right: -100%;
    height: calc(100vh - 9.5rem);
    width: 35rem;
    background: #fff;
    padding:0 1.5rem;
}

.header .cart-items-container.active{
    right: 0;
}

.header .cart-items-container .cart-item{
    position: relative;
    margin:2rem 0;
    display: flex;
    align-items: center;
    gap:1.5rem;
}

.header .cart-items-container .cart-item .fa-times{
    position: absolute;
    top:1rem; right: 1rem;
    font-size: 2rem;
    cursor: pointer;
    color: var(--black);
}

.header .cart-items-container .cart-item .fa-times:hover{
    color:var(--main-color);
}

.header .cart-items-container .cart-item img{
    height: 7rem;
}

.header .cart-items-container .cart-item .content h3{
    font-size: 2rem;
    color:var(--black);
    padding-bottom: .5rem;
}

.header .cart-items-container .cart-item .content .price{
    font-size: 1.5rem;
    color:var(--main-color);
}

.header .cart-items-container .btn{
    width: 100%;
    text-align: center;
}

.home{
    min-height: 100vh;
    display: flex;
    align-items: center;
    background:url(../images/home-img.jpeg) no-repeat;
    background-size: cover;
    background-position: center;
}

.home .content{
    max-width: 60rem;
}

.home .content h3{
    font-size: 6rem;
    text-transform: uppercase;
    color:#fff;
}

.home .content p{
    font-size: 2rem;
    font-weight: lighter;
    line-height: 1.8;
    padding:1rem 0;
    color:#eee;
}

.about .row{
    display: flex;
    align-items: center;
    background:var(--black);
    flex-wrap: wrap;
}

.about .row .image{
    flex:1 1 45rem;
}

.about .row .image img{
    width: 100%;
}
.about .row .content{
    flex:1 1 45rem;
    padding:2rem;
}

.about .row .content h3{
    font-size: 3rem;
    color:#fff;
}

.about .row .content p{
    font-size: 1.6rem;
    color:#ccc;
    padding:1rem 0;
    line-height: 1.8;
}

.menu .box-container{
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(30rem, 1fr));
    gap:1.5rem;
}

.menu .box-container .box{
    padding:5rem;
    text-align: center;
    border:var(--border);    
}

.menu .box-container .box img{
    height: 10rem;
}

.menu .box-container .box h3{
    color: #fff;
    font-size: 2rem;
    padding:1rem 0;
}

.menu .box-container .box .price{
    color: #fff;
    font-size: 2.5rem;
    padding:.5rem 0;
}

.menu .box-container .box .price span{
    font-size: 1.5rem;
    text-decoration: line-through;
    font-weight: lighter;
}

.menu .box-container .box:hover{
    background:#fff;
}

.menu .box-container .box:hover > *{
    color:var(--black);
}

.products .box-container{
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(30rem, 1fr));
    gap:1.5rem;
}

.products .box-container .box{
    text-align: center;
    border:var(--border);
    padding: 2rem;
}

.products .box-container .box .icons a{
    height: 5rem;
    width: 5rem;
    line-height: 5rem;
    font-size: 2rem;
    border:var(--border);
    color:#fff;
    margin:.3rem;
}

.products .box-container .box .icons a:hover{
    background:var(--main-color);
}

.products .box-container .box .image{
    padding: 2.5rem 0;
}

.products .box-container .box .image img{
    height: 25rem;
}

.products .box-container .box .content h3{
    color:#fff;
    font-size: 2.5rem;
}

.products .box-container .box .content .stars{
    padding: 1.5rem;
}

.products .box-container .box .content .stars i{
    font-size: 1.7rem;
    color: var(--main-color);
}

.products .box-container .box .content .price{
    color:#fff;
    font-size: 2.5rem;
}

.products .box-container .box .content .price span{
    text-decoration: line-through;
    font-weight: lighter;
    font-size: 1.5rem;
}

.review .box-container{
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(30rem, 1fr));
    gap:1.5rem;
}

.review .box-container .box{
    border:var(--border);
    text-align: center;
    padding:3rem 2rem;
}

.review .box-container .box p{
    font-size: 1.5rem;
    line-height: 1.8;
    color:#ccc;
    padding:2rem 0;
}

.review .box-container .box .user{
    height: 7rem;
    width: 7rem;
    border-radius: 50%;
    object-fit: cover;
}

.review .box-container .box h3{
    padding:1rem 0;
    font-size: 2rem;
    color:#fff;
}

.review .box-container .box .stars i{
    font-size: 1.5rem;
    color:var(--main-color);
}

.contact .row{
    display: flex;
    background:var(--black);
    flex-wrap: wrap;
    gap:1rem;
}

.contact .row .map{
    flex:1 1 45rem;
    width: 100%;
    object-fit: cover;
}

.contact .row form{
    flex:1 1 45rem;
    padding:5rem 2rem;
    text-align: center;
}

.contact .row form h3{
    text-transform: uppercase;
    font-size: 3.5rem;
    color:#fff;
}

.contact .row form .inputBox{
    display: flex;
    align-items: center;
    margin-top: 2rem;
    margin-bottom: 2rem;
    background:var(--bg);
    border:var(--border);
}

.contact .row form .inputBox span{
    color:#fff;
    font-size: 2rem;
    padding-left: 2rem;
}

.contact .row form .inputBox input{
    width: 100%;
    padding:2rem;
    font-size: 1.7rem;
    color:#fff;
    text-transform: none;
    background:none;
}

.blogs .box-container{
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(30rem, 1fr));
    gap:1.5rem;
}

.blogs .box-container .box{
    border:var(--border);    
}

.blogs .box-container .box .image{
    height: 25rem;
    overflow:hidden;
    width: 100%;
}

.blogs .box-container .box .image img{
    height: 100%;
    object-fit: cover;
    width: 100%;
}

.blogs .box-container .box:hover .image img{
    transform: scale(1.2);
}

.blogs .box-container .box .content{
    padding:2rem;
}

.blogs .box-container .box .content .title{
    font-size: 2.5rem;
    line-height: 1.5;
    color:#fff;
}

.blogs .box-container .box .content .title:hover{
    color:var(--main-color);
}

.blogs .box-container .box .content span{
    color:var(--main-color);
    display: block;
    padding-top: 1rem;
    font-size: 2rem;
}

.blogs .box-container .box .content p{
    font-size: 1.6rem;
    line-height: 1.8;
    color:#ccc;
    padding:1rem 0;
}

.footer{
    background:var(--black);
    text-align: center;
}

.footer .share{
    padding:1rem 0;
}

.footer .share a{
    height: 5rem;
    width: 5rem;
    line-height: 5rem;
    font-size: 2rem;
    color:#fff;
    border:var(--border);
    margin:.3rem;
    border-radius: 50%;
}

.footer .share a:hover{
    background-color: var(--main-color);
}

.footer .links{
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    padding:2rem 0;
    gap:1rem;
}

.footer .links a{
    padding:.7rem 2rem;
    color:#fff;
    border:var(--border);
    font-size: 2rem;
}

.footer .links a:hover{
    background:var(--main-color);
}

.footer .credit{
    font-size: 2rem;
    color:#fff;
    font-weight: lighter;
    padding:1.5rem;
}

.footer .credit span{
    color:var(--main-color);
}













/* media queries  */
@media (max-width:991px){

    html{
        font-size: 55%;
    }

    .header{
        padding:1.5rem 2rem;
    }

    section{
        padding:2rem;
    }

}

@media (max-width:768px){

    #menu-btn{
        display: inline-block;
    }

    .header .navbar{
        position: absolute;
        top:100%; right: -100%;
        background: #fff;
        width: 30rem;
        height: calc(100vh - 9.5rem);
    }

    .header .navbar.active{
        right:0;
    }

    .header .navbar a{
        color:var(--black);
        display: block;
        margin:1.5rem;
        padding:.5rem;
        font-size: 2rem;
    }

    .header .search-form{
        width: 90%;
        right: 2rem;
    }

    .home{
        background-position: left;
        justify-content: center;
        text-align: center;
    }

    .home .content h3{
        font-size: 4.5rem;
    }

    .home .content p{
        font-size: 1.5rem;
    }

}

@media (max-width:450px){

    html{
        font-size: 50%;
    }

}
