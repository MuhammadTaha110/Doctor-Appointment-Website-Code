# Doctor-Appointment-Website-Code
#HTML

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Healtcare</title>
    <link rel="icon" type="image/x-icon" href="imgs/favicon.ico">


    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css">  
    <link rel="stylesheet" href="style.css">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN" crossorigin="anonymous">

    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">


</head>

<body>

    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js">


    <!--***********************____NavbarStart____****************************-->


    <nav class="navbar navbar-expand-lg bg-body-tertiary">
        <div class="container-fluid">
            <a class="navbar-brand" href="#">
                <img class="logo" src="imgs/Logo.png" alt="Clinic Logo">
            </a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
                data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false"
                aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                    <li class="nav-item-1 nav-item">
                        <a class="nav-link active" aria-current="page" href="#home">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#ourservices">Service</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Contact Us</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#ourteam">Help</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#">Blogs</a>
                    </li>
                </ul>
                <form class="d-flex" role="search">
                    <button class="signup-btn btn-outline-success" type="submit">Sign Up</button>
                    <button class="login-btn btn btn-outline-success" type="submit">Log In</button>

                </form>
            </div>
        </div>
    </nav>
    <!--***********************NavbarEnd****************************-->


    <!--*****************______Home__Section_____****************************-->

    <section id="home" class="home">
        <div class="home-heading">
            <h1>Providing Quality <span class="first-span">Healthcare</span> for a <span class="second-span">
                    Brighter</span> and <span class="second-span">Healthy</span> Future
            </h1>
            <p>At our hospital, we are dedicated to providing exceptional medical care to our patients
                and their families. Our experienced team of medical professionals, cutting-edge
                technology, and compassionate approach make us a leader in the healthcare industry
            </p>
        </div>
        <div class="home-img">
            <img class="home-bg" src="imgs/Vector.png" alt="background-vector">
            <img class="doctor-img" src="imgs/Doctor.png" alt="doctor-image">
            <img class="tag-24-7" src="imgs/24_7.png" alt="24/7-Tag">
            <img class="tag-professionals" src="imgs/Professionals.png" alt="Professionals-Tag">
        </div>
    </section>

    <!--******______Find A Doctor Form_____********-->

    <section class="find-doctor">
        <div class="find-doctor-heading">
            <h3>Find A Doctor</h3>
        </div>
        <div class="find-doctor-form">
            <form class="d-flex" role="search">
                <input class="form1 form-control me-2" type="search" placeholder="Name" aria-label="Search">
                <input class="form2 form-control me-2" type="search" placeholder="Speciality" aria-label="Search">
                <div class="container mt-4">
                    <div class="checkbox custom-control custom-switch">
                        <input type="checkbox" class="custom-control-input" id="customSwitch1">
                        <label class="custom-control-label" for="customSwitch1">Availability</label>
                    </div>
                </div>
                <button class="search-btn btn btn-outline-success">Search</button>
        </div>
    </section>

    <!--******______Find A Doctor Form End_____********-->

    <!--*****************______Our Results_____****************************-->

    <section class="our-results">
        <h3>Our results in numbers</h3>
        <div class="our-results-inner-div">
            <div class="result-div">
                <h6>99<span>%</span></h6>
                <h5>Customer Satisfactions</h5>
            </div>
            <div class="result-div">
                <h6>15<span>k</span></h6>
                <h5>Online Patients</h5>
            </div>
            <div class="result-div">
                <h6>12<span>k</span></h6>
                <h5>Patients Recovered</h5>
            </div>
            <div class="result-div">
                <h6>240<span>%</span></h6>
                <h5>Company Growth</h5>
            </div>
        </div>

        <div class="our-results-inner-div-2">
            <div class="our-results-inner-div-2-content">
                <h3>You have lots of reasons to choose us</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipiscing eli
                    mattis sit phasellus mollis sit aliquam sit nullam.</p>
                <button class="started-btn btn btn-outline-success">Get Started</button>
                <button class="talk-btn btn btn-outline-success">Talk to Sales</button>
            </div>
            <div class="our-results-inner-div-2-img">
                <img src="imgs/Container.png" alt="healthcare-image">
            </div>
        </div>
    </section>

    <!--*****************______Our Services_____****************************-->
    <section id="ourservices" class="ourservices">
        <div class="ourservices-heading">
            <h3>Services we provide </h3>
        </div>
        <div class="ourservices-paragraph">
            <p>Lorem ipsum dolor sit amet consectetur adipiscing elit semper dalar elementum tempus hac tellus libero
                accumsan. </p>
        </div>

        <div class="ourservices-cards-div">
            <div class="ourservices-cards"> 
                <img src="imgs/Container (1).png" alt="Dental Treatment"> 
                <div class="ourservices-cards-heading"><h3>Dental Treatment</h3></div>
                <div class="ourservices-cards-paragraph"><p>Lorem ipsum dolor sit amet consecte tur adipiscing elit semper dalaracc lacus vel facilisis volutpat est velitolm.</p></div>
                <a href=""><div class="ourservices-cards-heading"><h6>Learn more</h6><i class="icon fa-solid fa-arrow-right"></i></div></a>
            
            </div>
            <div class="ourservices-cards"> 
                <img src="imgs/Container (2).png" alt="Dental Treatment"> 
                <div class="ourservices-cards-heading"><h3>Dental Treatment</h3></div>
                <div class="ourservices-cards-paragraph"><p>Lorem ipsum dolor sit amet consecte tur adipiscing elit semper dalaracc lacus vel facilisis volutpat est velitolm.</p></div>
                <a href=""><div class="ourservices-cards-heading"><h6>Learn more</h6><i class="icon fa-solid fa-arrow-right"></i></div></a>
            
            </div>
            <div class="ourservices-cards"> 
                <img src="imgs/Container(4).png" alt="Dental Treatment"> 
                <div class="ourservices-cards-heading"><h3>Dental Treatment</h3></div>
                <div class="ourservices-cards-paragraph"><p>Lorem ipsum dolor sit amet consecte tur adipiscing elit semper dalaracc lacus vel facilisis volutpat est velitolm.</p></div>
                <a href=""><div class="ourservices-cards-heading"><h6>Learn more</h6><i class="icon fa-solid fa-arrow-right"></i></div></a>

            </div>
        </div>

        <div class="ourservices-cards-div">
            <div class="ourservices-cards"> 
                <img src="imgs/operation.png" alt="Dental Treatment"> 
                <div class="ourservices-cards-heading"><h3>Dental Treatment</h3></div>
                <div class="ourservices-cards-paragraph"><p>Lorem ipsum dolor sit amet consecte tur adipiscing elit semper dalaracc lacus vel facilisis volutpat est velitolm.</p></div>
                <a href=""><div class="ourservices-cards-heading"><h6>Learn more</h6><i class="icon fa-solid fa-arrow-right"></i></div></a>
            
            </div>
            <div class="ourservices-cards"> 
                <img src="imgs/Container (2).png" alt="Dental Treatment"> 
                <div class="ourservices-cards-heading"><h3>Dental Treatment</h3></div>
                <div class="ourservices-cards-paragraph"><p>Lorem ipsum dolor sit amet consecte tur adipiscing elit semper dalaracc lacus vel facilisis volutpat est velitolm.</p></div>
                <a href=""><div class="ourservices-cards-heading"><h6>Learn more</h6><i class="icon fa-solid fa-arrow-right"></i></div></a>

            </div>
            <div class="ourservices-cards"> 
                <img src="imgs/Container(4).png" alt="Dental Treatment"> 
                <div class="ourservices-cards-heading"><h3>Dental Treatment</h3></div>
                <div class="ourservices-cards-paragraph"><p>Lorem ipsum dolor sit amet consecte tur adipiscing elit semper dalaracc lacus vel facilisis volutpat est velitolm.</p></div>
                <a href=""><div class="ourservices-cards-heading"><h6>Learn more</h6><i class="icon fa-solid fa-arrow-right"></i></div></a>
            </div>
        </div>

    </section>

    <!--*****************______Our Team Members_____****************************-->
    <section id="ourteam" class="ourteam">
        <div class="ourteam-heading">
            <h3>Meet our team members</h3>
        </div>
        <div class="ourteam-paragraph">
            <p>Lorem ipsum dolor sit amet consectetur adipiscing elit semper dalar elementum tempus hac tellus libero
                accumsan. </p>
        </div>

        <div class="ourteam-cards-div">
            <div class="ourteam-cards"> 
                <img src="imgs/BG.png" alt="Dental Treatment"> 
                <div class="ourteam-cards-heading"><h3>John Carter</h3></div>
                <div class="ourteam-cards-heading"><h6>CEO & Co-Founder</h6></div>
                <div class="ourteam-cards-paragraph"><p>Lorem ipsum dolor sit amet consecte tur adipiscing elit semper dalaracc lacus vel facilisis volutpat est velitolm.</p></div>
                <div class="ourteam-cards-icons-div">
                    <a href="#"><i class="fa-brands fa-square-facebook"></i></a>
                    <a href="#"><i class="fa-brands fa-square-twitter"></i></a>
                    <a href="#"><i class="fa-brands fa-square-instagram"></i></a>
                    <a href="#"><i class="fa-brands fa-linkedin"></i></a>
                </div>
            
            </div>
            <div class="ourteam-cards"> 
                <img src="imgs/team (1).png" alt="Dental Treatment"> 
                <div class="ourteam-cards-heading"><h3>John Carter</h3></div>
                <div class="ourteam-cards-heading"><h6>CEO & Co-Founder</h6></div>
                <div class="ourteam-cards-paragraph"><p>Lorem ipsum dolor sit amet consecte tur adipiscing elit semper dalaracc lacus vel facilisis volutpat est velitolm.</p></div>
                <div class="ourteam-cards-icons-div">
                    <a href="#"><i class="fa-brands fa-square-facebook"></i></a>
                    <a href="#"><i class="fa-brands fa-square-twitter"></i></a>
                    <a href="#"><i class="fa-brands fa-square-instagram"></i></a>
                    <a href="#"><i class="fa-brands fa-linkedin"></i></a>
                </div>
            
            </div> <div class="ourteam-cards"> 
                <img src="imgs/Image Placeholder (1).png" alt="Dental Treatment"> 
                <div class="ourteam-cards-heading"><h3>John Carter</h3></div>
                <div class="ourteam-cards-heading"><h6>CEO & Co-Founder</h6></div>
                <div class="ourteam-cards-paragraph"><p>Lorem ipsum dolor sit amet consecte tur adipiscing elit semper dalaracc lacus vel facilisis volutpat est velitolm.</p></div>
                <div class="ourteam-cards-icons-div">
                    <a href="#"><i class="fa-brands fa-square-facebook"></i></a>
                    <a href="#"><i class="fa-brands fa-square-twitter"></i></a>
                    <a href="#"><i class="fa-brands fa-square-instagram"></i></a>
                    <a href="#"><i class="fa-brands fa-linkedin"></i></a>
                </div>
            
            </div>
        </div>

        <div class="ourteam-cards-div">
            <div class="ourteam-cards"> 
                <img src="imgs/team (2).png" alt="Dental Treatment"> 
                <div class="ourteam-cards-heading"><h3>John Carter</h3></div>
                <div class="ourteam-cards-heading"><h6>CEO & Co-Founder</h6></div>
                <div class="ourteam-cards-paragraph"><p>Lorem ipsum dolor sit amet consecte tur adipiscing elit semper dalaracc lacus vel facilisis volutpat est velitolm.</p></div>
                <div class="ourteam-cards-icons-div">
                    <a href="#"><i class="fa-brands fa-square-facebook"></i></a>
                    <a href="#"><i class="fa-brands fa-square-twitter"></i></a>
                    <a href="#"><i class="fa-brands fa-square-instagram"></i></a>
                    <a href="#"><i class="fa-brands fa-linkedin"></i></a>
                </div>
            
            </div>
            <div class="ourteam-cards"> 
                <img src="imgs/BG (2).png" alt="Dental Treatment"> 
                <div class="ourteam-cards-heading"><h3>John Carter</h3></div>
                <div class="ourteam-cards-heading"><h6>CEO & Co-Founder</h6></div>
                <div class="ourteam-cards-paragraph"><p>Lorem ipsum dolor sit amet consecte tur adipiscing elit semper dalaracc lacus vel facilisis volutpat est velitolm.</p></div>
                <div class="ourteam-cards-icons-div">
                    <a href="#"><i class="fa-brands fa-square-facebook"></i></a>
                    <a href="#"><i class="fa-brands fa-square-twitter"></i></a>
                    <a href="#"><i class="fa-brands fa-square-instagram"></i></a>
                    <a href="#"><i class="fa-brands fa-linkedin"></i></a>
                </div>
            
            </div> <div class="ourteam-cards"> 
                <img src="imgs/BG (3).png" alt="Dental Treatment"> 
                <div class="ourteam-cards-heading"><h3>John Carter</h3></div>
                <div class="ourteam-cards-heading"><h6>CEO & Co-Founder</h6></div>
                <div class="ourteam-cards-paragraph"><p>Lorem ipsum dolor sit amet consecte tur adipiscing elit semper dalaracc lacus vel facilisis volutpat est velitolm.</p></div>
                <div class="ourteam-cards-icons-div">
                    <a href="#"><i class="fa-brands fa-square-facebook"></i></a>
                    <a href="#"><i class="fa-brands fa-square-twitter"></i></a>
                    <a href="#"><i class="fa-brands fa-square-instagram"></i></a>
                    <a href="#"><i class="fa-brands fa-linkedin"></i></a>
                </div>
            
            </div>
        </div>

    </section>
</body>

</html>




#CSS

@font-face {
    font-family: Poppins;
    src: url(fonts/Poppins-Regular.ttf);
}

@font-face {
    font-family: PoppinsBold;
    src: url(fonts/Poppins-Black.ttf);
}

:root{
    --bg-color:#fdfdfd;
    --text-color:#333;
    --heading-color:#000000;
    --main-color: #004953;
    --btn-txt-color:#fdfdfd;
    --gradient-color:#03C03C;
    --shadow-color:rgba(0,0,0,.2);
    --regular:Poppins;
    --bold:PoppinsBold
}

*{
    font-family: var(--regular);
}


/*_______________Navbar____________*/


nav{
    box-shadow: rgba(0, 0, 0, 0.15) 0px 15px 25px, rgba(0, 0, 0, 0.05) 0px 5px 10px;
}

.navbar{
    position: fixed;
}

nav a{
    font-family: Poppins;
}

nav .logo{
    width: 180px;
}

nav ul{
   margin-left: auto;
   margin-right: auto;
}

nav .login-btn{
    background-color: var(--main-color) ;
    color: var(--btn-txt-color);
    border: none;
    width: 80px;
    font-family: var(--font);
    margin-top: -5px;
    border-radius: 5px;
}

nav .signup-btn{
    background-color: transparent;
    color: var(--main-color);
    border: none;
    width: 80px;
    font-family: var(--regular);
    margin-right: 20px;
    margin-top: -5px;
    border-radius: 5px;
}

/*_______________Home____________*/

.home{
    display: flex;
    width: 100%;
}

.home .home-heading{
    width: 60%;
    height: 400px;
    position: relative;
}

.home .home-heading h1{
    font-size: 28px;
    font-weight: 600;
    position: absolute;
    top: 120px;
    left: 50px;
}

.home .home-heading .first-span{
    color: var(--main-color);
}

.home .home-heading .second-span{
    color: var(--gradient-color);
}

.home .home-heading p{
    width: 72%;
    font-size: 14px;
    position: absolute;
    top: 210px;
    left: 50px;
}


.home .home-img{
    width: 40%;
    height: 400px;
    position: relative;
}

.home .home-img .home-bg{
    position: absolute;
    top: 60px;
    left: 20px;
    z-index: -1;
}

.home .home-img .doctor-img{
    position: absolute;
    top: 10px;
    left: 10px;
}

.home .home-img .tag-24-7{
    padding: 2px 5px;
    position: absolute;
    top: 100px;
    left: 240px;
    background-color: #F8F8F8;
    border-radius: 5px;
    border: 2px solid #ECECEC;
}

.home .home-img .tag-professionals{
    padding: 2px 5px;
    position: absolute;
    top: 280px;
    left: -40px;

}

/*_______________Find A Doctor____________*/

.find-doctor{
    margin-top: 20px;
    display: flex;
    border-radius: 12px;
    width: 90%;
    height: 120px;
    margin-left: auto;
    margin-right: auto;
    position: relative;
    box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px;
}

.find-doctor .find-doctor-heading h3{
    font-family: var(--bolds);
    color: var(--heading-color);
    font-size: 24px;
    margin-left: 20px;
    margin-top: 10px;
}

.find-doctor .find-doctor-form .search-btn{
    background-color: var(--main-color) ;
    color: var(--btn-txt-color);
    border: none;
    border-radius: 8px;
    width: 120px;
    width: 18%;

    font-family: var(--font);
    font-size: 20px;
    margin-top: -5px;
    position: absolute;
    top: 60px;
    left: 80%;
}


.find-doctor .find-doctor-form .form1 , 
.find-doctor .find-doctor-form .form2{
    position: absolute;
    top: 58px;
    width: 22%;
    border: 2px solid var(--main-color);
}

.find-doctor .find-doctor-form .form1{
    left: 5%;
}

.find-doctor .find-doctor-form .form2{
    left: 30%;
}

.find-doctor .find-doctor-form .checkbox{
    position: absolute;
    top: 65px;
    left: 55%;
}

/*_______________Our Results In Number____________*/

.our-results h3{
    margin-top: 15px;
    margin-bottom: 30px;
    padding-top: 60px;
    color: var(--main-color);
    text-align: center;
    font-weight: 600;
    font-size: 25px;
}

.our-results .our-results-inner-div{
    text-align: center;
    display: flex;
    justify-content: space-around;
    width: 85%;
    margin-left: auto;
    margin-right: auto;
    margin-top: 30px;
    margin-bottom: 80px;
}

.our-results .our-results-inner-div h6{
    font-size: 30px;
    font-weight: 700;
    color: var(--main-color);
}

.our-results .our-results-inner-div span{
   color:var(--gradient-color);
}

.our-results .our-results-inner-div h5{
    font-weight: 700;
}

.our-results .our-results-inner-div-2{
    width: 95%;
    margin-left: auto;
    margin-right: auto;
    display: flex;
}

.our-results .our-results-inner-div-2 .our-results-inner-div-2-content h3{
    font-size: 25px;
    text-align: left;
    margin-top: -12px;
    margin-bottom: 15px;
    width: 55%;
}

.our-results .our-results-inner-div-2 .our-results-inner-div-2-content p{
  width: 75%;
}

.our-results .our-results-inner-div-2 .our-results-inner-div-2-content{
    width: 60%;
    text-align: left;
}

.our-results .our-results-inner-div-2 .started-btn{
    background-color: var(--main-color);
    color: var(--bg-color);
    margin-right: 10px;
    border: none;
    border: 1px solid var(--main-color);
    border-radius: 12px;
}

.our-results .our-results-inner-div-2 .talk-btn{
    background-color: var(--bg-color);
    color: var(--main-color);
    border: 1px solid var(--main-color);
    border-radius: 12px;
}

/*______________Our Services____________*/
.ourservices{
    width: 100%;
    text-align: center;
    margin-top: 80px;
}

.ourservices h3{
    color: var(--main-color);
    font-weight: 600;
    font-size: 25px;
}

.ourservices p{
    width: 60%;
    margin-left: auto;
    margin-right: auto;
    font-size: 16px;
}

.ourservices .ourservices-cards-div{
    width: 100%;
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    margin-top: 20px;
}

.ourservices .ourservices-cards{
    margin-top: 20px;
    width: 30%;
    height: 350%;
    border-radius: 12px;
    box-shadow: rgba(0, 0, 0, 0.3) 0px 2px 4px 0px,  rgba(0, 0, 0, 0.22) 0px 2px 16px 0px;
}

.ourservices .ourservices-cards .ourservices-cards-heading{
    width: 90%;
    margin-left: auto;
    margin-right: auto;
    position: relative;
}

.ourservices .ourservices-cards img{
    margin-top: 15px;
    margin-left: auto;
    margin-right: auto;
    width: 90%;
}

.ourservices .ourservices-cards h3{
    margin-top: 20px;
    font-size: 20px;
    text-align: left;
}

.ourservices .ourservices-cards .ourservices-cards-paragraph p{
    font-size: 11px;
    text-align: left;
    width: 90%;
    margin-left: auto;
    margin-right: auto;
}

.ourservices .ourservices-cards h6{
    text-align: left;
    font-size: 15px;
    color: var(--main-color);
}

.ourservices .ourservices-cards .ourservices-cards-heading i{
    font-size: 15px;
    text-align: right;
    position: absolute;
    top: 2px;
    left: 100px;
    color: var(--main-color);
}


/*______________Our Team Members____________*/
.ourteam{
    width: 100%;
    text-align: center;
    margin-top: 80px;
}

.ourteam h3{
    color: var(--main-color);
    font-weight: 600;
    font-size: 25px;
}

.ourteam p{
    width: 60%;
    margin-left: auto;
    margin-right: auto;
    font-size: 16px;
}

.ourteam .ourteam-cards-div{
    width: 100%;
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    margin-top: 20px;
}

.ourteam .ourteam-cards{
    margin-top: 20px;
    width: 30%;
    height: 350px;
    border-radius: 12px;
    box-shadow: rgba(0, 0, 0, 0.3) 0px 2px 4px 0px,  rgba(0, 0, 0, 0.22) 0px 2px 16px 0px;
}

.ourteam .ourteam-cards .ourteam-cards-heading{
    width: 90%;
    margin-left: auto;
    margin-right: auto;
}

.ourteam .ourteam-cards img{
    margin-top: 15px;
    margin-left: auto;
    margin-right: auto;
    width: 50%;
}

.ourteam .ourteam-cards h3{
    margin-top: 20px;
    font-size: 20px;
    text-align: center;
}

.ourteam .ourteam-cards h6{
    text-align: center;
    font-size: 15px;
    color: var(--text-color);
}

.ourteam .ourteam-cards .ourteam-cards-paragraph p{
    font-size: 11px;
    text-align: center;
    width: 70%;
    margin-left: auto;
    margin-right: auto;
}

.ourteam .ourteam-cards .ourteam-cards-icons-div {
    width: 70%;
    display: flex;
    justify-content: space-around;
    margin-left: auto;
    margin-right: auto;
}
.ourteam .ourteam-cards .ourteam-cards-icons-div i{
    font-size: 25px;
    text-align: right;
    color: var(--main-color);
}






/* Custom CSS for switch button with #004953 color */
.custom-switch .custom-control-label::before {
    background-color: gray; /* Background color for default state */
  }

  .custom-switch .custom-control-input:checked ~ .custom-control-label::before {
    background-color:var(--main-color); /* Background color for checked state */
  }

/********************************************************/


/*____________*****************Break_____Points*********____________*/

@media(max-width:850px){
    /*_______________Home____________*/


.home .home-heading h1{
    font-size: 22px;
}


.home .home-heading p{
    font-size: 12px;
}

.home .home-img .home-bg{
    width: 87%;
    height: 80%;
}

.home .home-img .doctor-img{
    width: 95%;
    height: 90%;
    top: 19px;
    left: 2px;
}

.home .home-img .tag-24-7{
    padding: 2px 5px;
    position: absolute;
    top: 100px;
    left: 190px;
    background-color: #F8F8F8;
    border-radius: 5px;
    border: 2px solid #ECECEC;
}

.home .home-img .tag-professionals{
    padding: 2px 5px;
    position: absolute;
    top: 280px;
    left: -40px;
}

/*_______________Our Results In Number____________*/

.our-results .our-results-inner-div-2 .our-results-inner-div-2-content{
    margin-top: -35px;
    width: 60%;
    text-align: left;
}

}

@media(max-width:730px){
    .home .home-img .tag-24-7{
        left: 165px;
        width: 28%;
    }
}

@media(max-width:705px){
    /*_______________Our Results In Number____________*/

.our-results .our-results-inner-div-2 .our-results-inner-div-2-content h3{
    font-size: 22px;
}

.our-results .our-results-inner-div-2 .our-results-inner-div-2-content p{
    font-size: 12px;
    width: 90%;
}
}

@media(max-width:660px){
/*_______________Home____________*/


.home .home-heading h1{
    margin-top: 0px;
}


.home .home-heading p{
    margin-top: 0px;
}

.home .home-img .home-bg{
    width: 79%;
    height: 72%;
    margin-top: 12px;
}

.home .home-img .doctor-img{
    width: 87%;
    height: 82%;
    top: 31px;
    left: 8px;
}

.home .home-img .tag-24-7{
    padding: 2px 5px;
    position: absolute;
    top: 280px;
    left: -20px;
}   

.home .home-img .tag-professionals{
    display: none;}


/*_______________Our Results In Number____________*/

.our-results h3{
    font-size: 20px;
}

.our-results .our-results-inner-div h6{
    font-size: 25px;
}

.our-results .our-results-inner-div h5{
    font-weight: 700;
    font-size: 18px;
}

.our-results .our-results-inner-div-2 .our-results-inner-div-2-content h3{
    font-size: 20px;
    margin-top: -10px;
    width: 90%;
}

.our-results .our-results-inner-div-2 .our-results-inner-div-2-content p{
    font-size: 12px;
    width: 90%;
}

.our-results .our-results-inner-div-2 .started-btn{
    width: 70%;
}

.our-results .our-results-inner-div-2 .talk-btn{
    width: 70%;
    margin-top: 10px;
}


}

@media(max-width:580px){
    
    /*_______________Home____________*/

.home .home-heading h1{
    font-size: 20px;
    top: 80px;
}

.home .home-heading p{
    font-size: 12px;
    top: 170px;
}

.home .home-img .home-bg{
    width: 90%;
    height: 80%;
}

.home .home-img .doctor-img{
    width: 98%;
    height: 90%;
    top: 19px;
    left: 2px;
}

.home .home-img .tag-24-7{
    width: 50%;
    top: 280px;
    left: -30px;
}

/*_______________Find A Doctor____________*/

.find-doctor{
    margin-top: -50px;
    background-color: var(--bg-color);
}

.find-doctor .find-doctor-heading h3{
    font-size: 20px;
}

.find-doctor .find-doctor-form .search-btn{
    font-size: 15px;
}

.find-doctor .find-doctor-form .form1::placeholder,
.find-doctor .find-doctor-form .form2::placeholder{
 font-size: 11px;
}


.find-doctor .find-doctor-form .form1 , 
.find-doctor .find-doctor-form .form2{
    position: absolute;
    top: 58px;
    width: 22%;
    border: 2px solid var(--main-color);
}

.find-doctor .find-doctor-form .form1{
    left: 5%;
}

.find-doctor .find-doctor-form .form2{
    left: 30%;
}

.find-doctor .find-doctor-form .checkbox{
    position: absolute;
    top: 65px;
    left: 54%;
    font-size: 14px;
}

/*_______________Our Results In Number____________*/

.our-results h3{
    font-size: 18px;
}

.our-results .our-results-inner-div h6{
    font-size: 20px;
}

.our-results .our-results-inner-div h5{
    font-weight: 700;
    font-size: 15px;
}

.our-results .our-results-inner-div-2 .our-results-inner-div-2-img{
    position: absolute;
    display: none;
}

.our-results .our-results-inner-div-2 .our-results-inner-div-2-content{
    width: 100%;
}
.our-results .our-results-inner-div-2 .our-results-inner-div-2-content h3{
    font-size: 20px;
    margin-top: -30px;
    width: 100%;
    text-align: center;
}

.our-results .our-results-inner-div-2 .our-results-inner-div-2-content p{
    font-size: 12px;
    width: 100%;
    text-align: center;
}

.our-results .our-results-inner-div-2 .our-results-inner-div-2-content .started-btn{
  margin-left: 15%;
}

.our-results .our-results-inner-div-2 .talk-btn{
     margin-left: 15%;
}


}

@media(max-width:510px){
    /*_______________Home____________*/

.home .home-heading{
    width: 100%;
    margin-left: auto;
    position: relative;
}

.home .home-heading h1{
    font-size: 28px;
    top: 30px;
    text-align: center;
    position: absolute;
    left: 25px;
    width: 90%;

}

.home .home-heading p{
    font-size: 12px;
    top: 150px;
    text-align: center;
    position: absolute;
    top: 150px;
    left: 70px;
}

.home .home-img{
    position: absolute;
    top: 250px;
}

.home .home-img .home-bg{
    left: 180px;
    top: 80px;
    width: 85%;
    height: 55%;
}

.home .home-img .doctor-img{
    width: 85%;
    height: 55%;
    top: 60px;
    left: 170px;
}

.home .home-img .tag-24-7{
    top: 150px;
    left: 50px;
}

/*_______________Find A Doctor____________*/

.find-doctor{
    margin-top: 50px;
    background-color: var(--bg-color);
}

.find-doctor .find-doctor-heading h3{
    font-size: 24px;
}

.find-doctor .find-doctor-form .search-btn{
    font-size: 15px;
}

.find-doctor .find-doctor-form .form1::placeholder,
.find-doctor .find-doctor-form .form2::placeholder{
 font-size: 15px;
}


.find-doctor .find-doctor-form .form1 , 
.find-doctor .find-doctor-form .form2{
    position: absolute;
    top: 58px;
    width: 22%;
    border: 2px solid var(--main-color);
}

.find-doctor .find-doctor-form .form1{
    left: 5%;
}

.find-doctor .find-doctor-form .form2{
    left: 30%;
}

.find-doctor .find-doctor-form .checkbox{
    position: absolute;
    top: 65px;
    left: 52%;
    font-size: 15px;
}

/*_____________Our Services_____________ */

.ourservices .ourservices-cards-div{
   flex-direction: column;
}

.ourservices .ourservices-cards{
    margin-top: 20px;
    width: 90%;
    margin-left: auto;
    margin-right: auto;
}

/*_____________Our Team Members_____________ */
.ourteam .ourteam-cards-div{
   flex-direction: column;
}
.ourteam .ourteam-cards{
    width: 90%;
    height: 300px;
    margin-left: auto;
    margin-right: auto;

}

.ourteam .ourteam-cards .ourteam-cards-heading{
    width: 90%;
    margin-left: auto;
    margin-right: auto;
}

.ourteam .ourteam-cards img{
    width: 30%;
}


.ourteam .ourteam-cards .ourteam-cards-icons-div {
    width: 70%;
    display: flex;
    justify-content: space-around;
    margin-left: auto;
    margin-right: auto;
}
.ourteam .ourteam-cards .ourteam-cards-icons-div i{
    font-size: 25px;
    text-align: right;
    color: var(--main-color);
}
}

@media(max-width:490px){
   /*_______________Home____________*/

.home .home-heading{
    width: 100%;
    margin-left: auto;
    position: relative;
}

.home .home-img {
    top: 240px;
    width: 60%;
    left: -70px;
}

.home .home-heading h1{
    font-size: 25px;
    top: 20px;
    text-align: center;
    position: absolute;
    left: 25px;
    width: 90%;
}

.home .home-heading p{
    padding-top: 20px;
    font-size: 12px;
    text-align: center;
    position: absolute;
    top: 100px;
    left: 70px;
}

.home .tag-24-7{
    display: none;
}

/*_______________Find A Doctor____________*/

.find-doctor{
    margin-top: 50px;
    background-color: var(--bg-color);
}

.find-doctor .find-doctor-heading h3{
    margin-top: 18px;
    margin-left: 180px;
    font-size: 25px;
    width: 100%;
}

.find-doctor .find-doctor-form .search-btn{
    font-size: 14px;
    margin-top:  10px;
    width: 55%;
    margin-left: -40%;
    border-radius: 5px;
    border: 2px solid var(--main-color);
}

.find-doctor .find-doctor-form .form1::placeholder,
.find-doctor .find-doctor-form .form2::placeholder{
 font-size: 18px;
}


.find-doctor .find-doctor-form .form1 , 
.find-doctor .find-doctor-form .form2{
    position: absolute;
    top: 58px;
    width: 34%;
    border: 2px solid var(--main-color);
}

.find-doctor .find-doctor-form .form1{
    top: 20px;
    left: 4%;
}

.find-doctor .find-doctor-form .form2{
    left: 4%;
    top: 68px;

}

.find-doctor .find-doctor-form .checkbox{
   display: none;
}

}

@media(max-width:420px){
    /*_______________Home____________*/

.home .home-heading h1{
    font-size: 20px;
    top: 20px;
    text-align: center;
    position: absolute;
    left: 25px;
    width: 90%;
}

.home .home-heading p{
    padding-top: 0px;
    font-size: 12px;
}


/*_______________Find A Doctor____________*/

.find-doctor{
    height: 100px;
    margin-top: 50px;
    background-color: var(--bg-color);
}

.find-doctor .find-doctor-heading h3{
    margin-top: 12px;
    margin-left: 150px;
    font-size: 20px;
    width: 100%;
}

.find-doctor .find-doctor-form .search-btn{
    font-size: 14px;
    margin-top:  -5px;
}

.find-doctor .find-doctor-form .form1::placeholder,
.find-doctor .find-doctor-form .form2::placeholder{
 font-size: 18px;
}


.find-doctor .find-doctor-form .form1 , 
.find-doctor .find-doctor-form .form2{
    position: absolute;
    top: 40px;
    width: 34%;
    border: 2px solid var(--main-color);
}

.find-doctor .find-doctor-form .form1{
    top: 9px;
    left: 4%;
}

.find-doctor .find-doctor-form .form2{
    left: 4%;
    top: 55px;

}
}
