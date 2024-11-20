<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="contact.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/OwlCarousel2/2.3.4/assets/owl.carousel.min.css"
        integrity="sha512-tS3S5qG0BlhnQROyJXvNjeEM4UpMXHrQfTGmbQ1gKmelCxlSEBUaxhRBj/EFTzpbP4RVSrpEikbmdJobCvhE3g=="
        crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="stylesheet"
        href="https://cdnjs.cloudflare.com/ajax/libs/OwlCarousel2/2.3.4/assets/owl.theme.default.min.css"
        integrity="sha512-sMXtMNL1zRzolHYKEujM2AqCLUR9F2C4/05cdbxjjLSRvMQIciEPCQZo++nk7go3BtSuK9kfa/s+a4f4i5pLkw=="
        crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="stylesheet" href="https://unpkg.com/swiper/swiper-bundle.min.css" />
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.0.0/dist/css/bootstrap.min.css"
        integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.6.0/jquery.min.js"
        integrity="sha512-894YE6QWD5I59HgZOGReFYm4dnWc1Qt5NtvYSaNcOP+u1T9qYdvdihz0PPSiiqn/+/3e7Jo4EaG7TubfWGUrMQ=="
        crossorigin="anonymous" referrerpolicy="no-referrer"></script>
</head>

<body>
    <!-- <div id = "loader">

    </div> -->

    <header>

        <div class="header2">
            <div class="content1">
                <a href="">
                    <h1>Track your services </h1>
                </a>
                <span>|</span>
                <select name="" id="">
                    <option>English</option>
                    <option>Bangla</option>
                    <option>Arabic</option>
                </select>
                <span>|</span>
                <i class="fa fa-facebook" aria-hidden="true"></i>
                <i class="fa fa-twitter" aria-hidden="true"></i>
                <i class="fa fa-linkedin" aria-hidden="true"></i>
                <i class="fa fa-instagram" aria-hidden="true"></i>
            </div>
            <div class="content2">
                <i class="fa fa-phone" aria-hidden="true" id="ab"></i>
                <a href="">
                    <h2>03162542763</h2>
                </a>
                <span>|</span>
                <i class="fa fa-envelope" aria-hidden="true"></i>
                <a href="">
                    <h2>contact@gmail.com</h2>
                </a>
                <span>|</span>
                <i class="fa fa-user-o" aria-hidden="true"></i>
                <a href="login.html">
                    <h2>login/signup</h2>
                </a>
            </div>
        </div>
        <div class="header3">
            <div class="headerlogo1">
                <img src="images/logo.png" alt="">
            </div>
            <div class="headerlogo2">
              <ul>
                <a href="home1.html"> <li>HOME </li>  </a> 
               <a href="Aboutus.HTML"><li>ABOUT</li></a>  
               <a href="service.html"><li>SERVICES</li></a> 
               <a href="Shop.HTML"> <li>SHOP</li></a>
                <a href="contact.html"><li>CONTACT</li></a>
              </ul>
            </div>
            <div class="headerlogo3">
             <a href="appointment.html">   <button>MAKE AN APPOINTMENT</button></a>
                <!-- <button onclick="showSearchSection()">S</button> -->
                <img src="images/download__2_-removebg-preview.png" alt="" onclick="showSearchSection()" class="image3">
                <div class="searchSection" id="searchSection">
                    <div class="closeBtn" onclick="closeSearchSection()">
                        <!-- <button>X</button> -->
                        <img src="images/download-removebg-preview.png" alt="" class="image4">

                    </div>
                    <div class="searchBox">
                        <input type="text" placeholder="Search Here">
                        <!-- <a href=""><img src="download__2_-removebg-preview.png" alt=""></a> -->
                        <a href=""><button class="searchbtn">search</button></a>
                    </div>
                </div>

                <script>
                    function closeSearchSection() {
                        document.getElementById("searchSection").style.display = "none";
                    }
                    function showSearchSection() {
                        document.getElementById("searchSection").style.display = "flex";

                    }
                </script>




                <!-- <div class="navbar1">
                     <input type="checkbox" id="click1">
                <label for="click1">
                    <img src="download__2_-removebg-preview.png" alt="">
                </label>
                <nav class="nav">
                    <input type="checkbox" id="click1">
                <label for="click1">
                    <img src="download-removebg-preview.png" alt="" class="img">
                </label>
                <div class="txt">
                <input type="text">
                </div>
                </nav>
                <div class="input">
                    <input type="text" placeholder="Search Here...">
                </div>
            </div> -->
                <span>|</span>
                <!-- <img src="download__1_-removebg-preview.png" alt="" class="logo"> -->






                <div class="navbar">
                    <input type="checkbox" id="click">
                    <label for="click" class="menu-btn">
                        <img src="images/download__1_-removebg-preview.png" alt="" class="logo">
                    </label>
                    <nav>
                        <!-- <input type="text"> -->
                        <div class="content">
                            <input type="checkbox" id="click">
                            <label for="click" class="menu-btn">
                                <img src="images/download-removebg-preview.png" alt="" class="image1">
                                <!-- <i class="fa fa-times-circle" aria-hidden="true"></i> -->
                            </label>
                            <div class="content1">
                                <img src="images/logo.png" alt=""><br><br>
                                <p>Quickly recaptiualize real-time interfaces and timely models. Proactively exploit
                                    viral meta-services for interdependent customer service. Dynamically actualize
                                    bleeding-edge internal
                                <p>
                                <div class="icon">
                                    <img src="images/imgg4.jpg" alt="">
                                    <h1>03121233019</h1><br><br>
                                    <img src="images/img1 (1).png" alt="" class="img1">
                                    <h2>info@axivis.com</h2>
                                    <img src="images/img1 (2).png" alt="" class="img2">
                                    <h3>6265 Brockport NY 14420</h3>
                                    <br><br>
                                    <h4>RECENT POST</h4><br>
                                    <!-- <img src="recent post.jpg" alt=""> -->

                                </div>


                            </div>



                        </div>
                    </nav>
                </div>


            </div>
        </div>
    </header>
    <!-- banner section start -->
    <div class="banner">
        <h2>Contact US</h2>
    </div>
    <!-- banner sectionbn end -->

    <div class="buttons" id="btton">
        <button onclick="section1()" class="btn btn-1" data-filter="Nazimabad">Nazimabad Branch</button>
        <button onclick="section2()" class="btn btn-2" data-filter="Shahra e Faisal">Shahra e Faisal Branch</button>
        <button onclick="section3()" class="btn btn-3" data-filter="Korangi"> Korangi Branch </button>
    </div>


    <div class="cards-container" id="container1">
        <div class="card" style="width: 21rem; margin-left: 25px; margin-top: 40px;">
            <img class="card-img-top" src="images/oil=change.jpg" alt="Card image cap">
            <div class="card-body">
                <h3 style="color: gray; font-size: 15px;">Call us 24/7</h3>
                <h3 class="card-text" style="font-size:  25px;">+923162542763</h3>
            </div>
        </div>
        <div class="card" style="width: 21rem; margin-left: 25px;margin-top: 40px;">
            <img class="card-img-top" src="images/mechanic.jpg" alt="Card image cap">
            <div class="card-body">
                <h3 style="color: gray; font-size: 15px;">Make a Quote</h3>
                <h3 class="card-text" style="font-size:  25px;">Tabinda@gmail.com</h3>
            </div>
        </div>
        <div class="card" style="width: 21rem; margin-left: 25px;margin-top: 40px;">
            <img class="card-img-top" src="images/car washing.jpg" alt="Card image cap">
            <div class="card-body">
                <h3 style="color: gray; font-size: 15px;">service station</h3>
                <h3 class="card-text" style="font-size:  25px;">25 Hilton Street, Aus</h3>
            </div>
        </div>


    </div>
    <div class="cards-container" id="container2">
        <div class="card" style="width: 21rem; margin-left: 25px; margin-top: 40px;">
            <img class="card-img-top" src="images/cart4-img.jpg" alt="Card image cap">
            <div class="card-body">
                <h3 style="color: gray; font-size: 15px;">Call us 24/7</h3>
                <h3 class="card-text" style="font-size:  25px;">+923102142213</h3>
            </div>
        </div>
        <div class="card" style="width: 21rem; margin-left: 25px;margin-top: 40px;">
            <img class="card-img-top" src="images/oil=change.jpg" alt="Card image cap">
            <div class="card-body">
                <h3 style="color: gray; font-size: 15px;">Make a Quote</h3>
                <h3 class="card-text" style="font-size:  25px;">rhashir071@gmail.com</h3>
            </div>
        </div>
        <div class="card" style="width: 21rem; margin-left: 25px;margin-top: 40px;">
            <img class="card-img-top" src="images/cart6-img.jpg" alt="Card image cap">
            <div class="card-body">
                <h3 style="color: gray; font-size: 15px;">service station</h3>
                <h3 class="card-text" style="font-size:  25px;">25 Hilton Street, Aus</h3>
            </div>
        </div>


    </div>
    <div class="cards-container" id="container3">
        <div class="card" style="width: 21rem; margin-left: 25px; margin-top: 40px;">
            <img class="card-img-top" src="images/car washing.jpg" alt="Card image cap">
            <div class="card-body">
                <h3 style="color: gray; font-size: 15px;">Call us 24/7</h3>
                <h3 class="card-text" style="font-size:  25px;">+923102142213</h3>
            </div>
        </div>
        <div class="card" style="width: 21rem; margin-left: 25px;margin-top: 40px;">
            <img class="card-img-top" src="images/cart6-img.jpg" alt="Card image cap">
            <div class="card-body">
                <h3 style="color: gray; font-size: 15px;">Make a Quote </h3>
                <h3 class="card-text" style="font-size:  25px;">info123@gmail.com</h3>
            </div>
        </div>
        <div class="card" style="width: 21rem; margin-left: 25px;margin-top: 40px;">
            <img class="card-img-top" src="images/cart4-img.jpg" alt="Card image cap">
            <div class="card-body">
                <h3 style="color: gray; font-size: 15px;">Address</h3>
                <h3 class="card-text" style="font-size:  25px;">25 Hilton Street, Aus</h3>
            </div>
        </div>


    </div>  


    <!-- conatct section start -->

   


    <script>
        function section1()
        {
            document.getElementById("container1").style.display = "flex";
            document.getElementById("container2").style.display = "none";
            document.getElementById("container3").style.display = "none";
        }
        function section2()
        {
            document.getElementById("container1").style.display = "none";
            document.getElementById("container2").style.display = "flex";
            document.getElementById("container3").style.display = "none";
        }
        function section3()
        {
            document.getElementById("container1").style.display = "none";
            document.getElementById("container2").style.display = "none";
            document.getElementById("container3").style.display = "flex";
        }

    </script>


<div class="bg-img">
    <div class="contact-form">
        
            <h2>Contact Us Form</h2>
            <form method="POST">
             <div class="content">
                <div class="row100">
                    <div class="col">
                        <div class="inputBox">
                            <input name="fname" type="text" required="required">
                            <span class="text">First Name</span>
                            <span class="line"></span>
                        </div>
                    </div>
                    <div class="col">
                        <div class="inputBox">
                            <input name="lname" type="text" required="required">
                            <span class="text">Last Name</span>
                            <span class="line"></span>
                        </div>
                    </div>
                    <div class="col">
                        <div class="inputBox">
                            <input type="Email" name="email" required="required">
                            <span class="text">Email</span>
                            <span class="line"></span>
                        </div>
                    </div>
                </div>

                <div class="row100">
                    <div class="col">
                        <div class="inputBox">
                            <input type="password" name="pass" required="required">
                            <span class="text">Password</span>
                            <span class="line"></span>
                        </div>
                    </div>
                    <div class="col">
                        <div class="inputBox">
                            <input type="text" name="contact" required="required">
                            <span class="text">Phone Number</span>
                            <span class="line"></span>
                        </div>
                    </div>
                </div>

                <div class="row100">
                    <div class="col">
                        <div class="inputBox textarea">
                            <textarea name="message" required="required"></textarea>
                            <span class="text">Type Message</span>
                            <span class="line"></span>
                        </div>
                    </div>
                </div>

                <div class="row100">
                    <div class="col">
                        <button name="btnsubmit" type="submit">send message</button>
                    </div>
                </div>
             </div>
           </form>
    </div>
   
</div>

<div class="contact-map">
    <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d115828.83195512393!2d67.03123066250001!3d24.875766699999993!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3eb3398b715a4ced%3A0xa199ce20c3645db9!2sBismillah%20Auto%20Workshop!5e0!3m2!1sen!2s!4v1658141719347!5m2!1sen!2s" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
</div>

<footer>
        <img src="images/body-image-5.png" alt="" style="width: 150px; height:30%;">
        <img src="images/logo-h4.png" alt="" class="img1">
        <img src="images/body-image-6.png" alt="" class="img2" style="width:150px ;height:30%; margin-top: 330px;margin-left: 88%;">
        <div class="link"><p>Conveniently create economically sound e-tailers after high-quality collaboration and idea-sharing. Efficiently negotiate 24/365.</p><br>
            <i class="fa fa-map-marker" aria-hidden="true"><span>14/A, Brown Tower, New Your, US</span></i><br><br>
            <i class="fa fa-phone" aria-hidden="true" id="ab"></i> <span>052 (699) 256 - 693</span><br><br>
            <i class="fa fa-envelope" aria-hidden="true"><span class="span">contact@admin.com</span></i>


        </div>
       <div class="info">
        <div class="account"> <h3> My Account</h3>
        <span>_______</span><br><br><br>
        <h4>My Account</h4>
        <h4>Order History</h4>
        <h4>Returns</h4>
        <h4>Advanced Search</h4>
        <h4>Customer Service</h4>
        <h4>Specials</h4>
        </div>
        <div class="account"><h3>Quick Links</h3>
            <span>_______</span><br><br><br>
            <h4>Our Services</h4>
            <h4>About Us</h4>
            <h4>Our Projects</h4>
            <h4>FAQ Page</h4>
            <h4>Blogs</h4>
            <h4>Contact Us</h4>
        </div>
        <div class="account"><h3>Services</h3>
            <span>_______</span><br><br><br>
            <h4>Engine Repair</h4>
            <h4>Tire Replacement</h4>
            <h4>Batteries</h4>
            <h4>Break Repair</h4>
            <h4>Trandmission</h4>
            <h4>Oil Change</h4>
        </div>
        <div class="account"><h3>Company Info</h3>
            <span>_______</span><br><br><br>
            <h5>Monday: <span class="span">	8am - 8pm</span></h5>
            <h5>Tuesday:	<span class="span">	8am - 8pm</span></h5>
            <h5>Wednesday:	<span class="span">	8am - 8pm</span></h5>
            <h5>Thursday:	<span class="span">	8am - 8pm</span></h5>
            <h5>Fri - Sat: <span class="span">9am - 7pm</span>	</h5>
            <h5>Sunday: <span class="span"> Closed</span></h5>
        </div>
       </div>
        <div class="footer2">
            <h3>© 2024 <span>Axivis.  All Rights Reserved By </span>Inshal </h3>
                
                <div class="icons">
                <i class="fa fa-facebook" aria-hidden="true" ></i>
                    <i class="fa fa-twitter" aria-hidden="true"></i>
                    <i class="fa fa-instagram" aria-hidden="true"></i>
                    <i class="fa fa-pinterest-p" aria-hidden="true"></i>
            </div>
        </div>

      </footer>
