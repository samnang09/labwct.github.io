<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="Index.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.2.1/css/all.min.css">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/swiper@8/swiper-bundle.min.css"/>
    <link rel="stylesheet" href="https://drive.google.com/uc?id=1dn1iQkkzBoN2TNyHXVnWntiRIo0SHLIi">
    <title>Sport And Hobby</title>
</head>
<body>
        <div class="header">
            <!--Nav-->
            <nav class="navbar">
                <div class="logo">
                    <a href="Index.html"><img src="Image/logo.jpg"></a> 
                </div>
                <div class="responsive-nav">
                    <!--Nav center-->
                        <div class="nav-center">
                            <div class="search-box">
                                <input type="text" placeholder="Search">
                                <i class="fa-solid fa-magnifying-glass"></i>
                            </div>
                        </div>
                    <!--end of Nav center-->
                    <!--Nav right-->
                        <ul class="nav-right">
                            <li><a href="store.html"store">Store</a></li>                       
                            <li><a href="Contact.html" id="help">Contact us</a></li>
                            <li><a href="User.html" id="user"><i class="fa-solid fa-user"></i></a></li>
                            <li><a href="" id="cart"><i class="fa-solid fa-cart-shopping"></i></a></li>
                        </ul>
                    <!--end of Nav right-->
                </div>
                <div class="hambuger">
                    <i class="fa-solid fa-bars"></i>
                </div>
            </nav> 
        </div>
        <div class="img-header">
            <div class="swiper">
                <div class="swiper-wrapper">
                    <!-- Slides -->
                    <div class="swiper-slide"><img src="Image/border.jpg"></div>
                    <div class="swiper-slide"><img src="Image/border.jpg"></div>
                    <div class="swiper-slide"><img src="Image/border.jpg"></div>
                    
                </div>
                 <!-- If we need pagination -->
                <div class="swiper-pagination"></div>
                <!-- If we need navigation buttons -->
                <div class="swiper-button-prev"></div>
                <div class="swiper-button-next"></div>
            </div>
        </div>
        <script src="https://cdn.jsdelivr.net/npm/swiper@8/swiper-bundle.min.js"></script>
        <script>
            const swiper = new Swiper('.swiper', {
                autoplay:{
                    delay: 2000,
                    disableonineraction: false,
                },
             loop: true,
            pagination: {
                el: '.swiper-pagination',
                clickable: true,
             },
            navigation: {
                nextEl: '.swiper-button-next',
                prevEl: '.swiper-button-prev',
            },
            });
        </script>
        <div class="mid">
            <div class="textfor">
                <h1>WHO ARE YOU SHOPPING FOR?</h1>
            </div>
            <div class="imgfor1">
                <li><a href="for.html" id="forher"><img src="Image/border3.jpg" ></a></li>
                <li><a href="for2.html" id="forhim"><img src="Image/border4.jpg" ></a></li>
                <li><a href="for3.html" id="forkids"><img src="Image/border5.jpg" ></a></li>
            </div>
            <div class="imgfor2">
                <li><a href="#"><img src="Image/border2.jpg"></a></li>
            </div>
            }
        </div>
        <div class="mid2">
            <div class="top">
                <h1>TOP SPORTS</h1>
            </div>
            <div class="gallery">
                <li><a href="sport2.html" id="sport"><img src="Image/sport1.jpg" ></a></li>
            </div>
            <div class="gallery">
                <li><a href="sport3.html" id="sport"><img src="Image/sport2.jpg" ></a></li>
            </div>
            <div class="gallery">
                <li><a href="sport.html" id="sport"><img src="Image/sport3.jpg" ></a></li>
            </div>
            <div class="gallery">
                <li><a href="sport2.html" id="sport"><img src="Image/sport4.jpg" ></a></li>
            </div>
            <div class="gallery">
                <li><a href="sport3.html" id="sport"><img src="Image/sport5.jpg" ></a></li>
            </div>
            <div class="gallery">
                <li><a href="sport3.html" id="sport"><img src="Image/sport6.jpg" ></a></li>
            </div>
            <div class="gallery">
                <li><a href="sport2.html" id="sport"><img src="Image/sport7.jpg" ></a></li>
            </div>
            <div class="gallery">
                <li><a href="sport.html" id="sport"><img src="Image/sport8.jpg" ></a></li>
            </div>
            <div class="gallery">
                <li><a href="sport3.html" id="sport"><img src="Image/sport9.jpg" ></a></li>
            </div>
        </div>
        <footer>
            <div class="container">
                <div class="row">
                    <div class="footer-col">
                        <h4>OUR SERVICE</h4>
                        <ul>
                            <li><a href="#">Our Delivery Service</a></li>
                            <li><a href="#">Click & Collect</a></li>
                            <li><a href="#">How to Order</a></li>
                            <li><a href="#">Gift Card</a></li>
                            <li><a href="#">Add-on Service</a></li>
                            <li><a href="#">ADecathlon B2B</a></li>
                            <li><a href="#">Warranty</a></li>
                        </ul>
                    </div>
                    <div class="footer-col">
                        <h4>ABOUT DECATHLON</h4>
                        <ul>
                            <li><a href="#">FAQ</a></li>
                            <li><a href="#">Passion Brands</a></li>
                            <li><a href="#">About us</a></li>
                            <li><a href="#">Membership</a></li>
                            <li><a href="#">Decathlon United</a></li>
                            <li><a href="#">Careers</a></li>
                            <li><a href="#">Our location</a></li>
                            <li><a href="#">Sports Blog</a></li>
                           
                        </ul>
                    </div>
                    <div class="footer-col">
                        <h4>LEGAL</h4>
                        <ul>
                            <li><a href="#">Privacy Policy</a></li>
                            <li><a href="#">Return Policy</a></li>
                            <li><a href="#">Terms & Conditions</a></li>
                            <li><a href="#">Product Recall</a></li>
                        </ul>
                    </div>
                    <div class="footer-col">
                        <h4>follow us</h4>
                        <div class="social-links">
                            <a href="#"><i class="fab fa-facebook-f"></i></a>
                            <a href="#"><i class="fab fa-twitter"></i></a>
                            <a href="#"><i class="fab fa-instagram"></i></a>
                            <a href="#"><i class="fa-brands fa-youtube"></i></a>
                        </div>
                    </div>
                </div>
                <div class="text-footer">
                    © 2023 Decathlon™. All rights reserved.
                </div>
            </div>
        </footer>
        <script src="https://drive.google.com/uc?id=17ECLD52osd74gEBVDW-7U6XFbS04qree"></script>
</body>
