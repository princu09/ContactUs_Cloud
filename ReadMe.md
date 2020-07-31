### ContactUs Cloud

##### Join Our Telegram Channel [ProgHub09](http://t.me/ProgHub09) and Also Download Our App.

###### HTML File :

```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css" integrity="sha384-wvfXpqpZZVQGK6TAh5PVlGOfQNHSoD2xbE+QkPxCAFlNEevoEH3Sl0sibVcOQVnN" crossorigin="anonymous">
    <link rel="shortcut icon" href="https://princu09.github.io/nfwebbuilder/img/logo.png" type="image/png">
</head>

<body>
    <div class="banner">
        <div class="clouds">
            <img src="img/cloud1.png" alt="" style="--i:1;">
            <img src="img/cloud2.png" alt="" style="--i:2;">
            <img src="img/cloud3.png" alt="" style="--i:3;">
            <img src="img/cloud4.png" alt="" style="--i:4;">
            <img src="img/cloud5.png" alt="" style="--i:5;">
            <img src="img/cloud1.png" alt="" style="--i:10;">
            <img src="img/cloud2.png" alt="" style="--i:9;">
            <img src="img/cloud3.png" alt="" style="--i:8;">
            <img src="img/cloud4.png" alt="" style="--i:7;">
            <img src="img/cloud5.png" alt="" style="--i:6;">
        </div>
    </div>

    <section class="contact">
        <div class="content">
            <h2>Contact Us</h2>
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Nobis nemo, dignissimos blanditiis libero architecto nulla natus ullam optio.</p>
        </div>
        <div class="container">
            <div class="contactInfo">
                <div class="box">
                    <div class="icon"><i class="fa fa-map-marker" aria-hidden="true"></i></div>
                    <div class="text">
                        <h3>Address :</h3>
                        <p>Lorem Happy Road, <br> Sad City , Cry State <br> 354565.
                        </p>
                    </div>
                </div>
                <div class="box">
                    <div class="icon"><i class="fa fa-phone" aria-hidden="true"></i></div>
                    <div class="text">
                        <h3>Phone :</h3>
                        <p>786-4545-800</p>
                    </div>
                </div>
                <div class="box">
                    <div class="icon"><i class="fa fa-envelope-o" aria-hidden="true"></i></div>
                    <div class="text">
                        <h3>Email :</h3>
                        <p>HelloBoy@sad.com</p>
                    </div>
                </div>
            </div>
            <div class="contactForm">
                <form action="">
                    <h2>Send Message</h2>
                    <div class="inputBox">
                        <input type="text" name="" id="" required>
                        <span>Full Name</span>
                    </div>
                    <div class="inputBox">
                        <input type="email" name="" id="" required>
                        <span>Email</span>
                    </div>
                    <div class="inputBox">
                        <textarea name="" id="" required></textarea>
                        <span>Type Your Message Here...</span>
                    </div>
                    <div class="inputBoxBtn">
                        <input type="submit" value="Send" name="" id="">
                    </div>
                </form>
            </div>
        </div>
    </section>
</body>

</html>
```

###### CSS File :

```
@import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;1,100;1,200;1,300;1,400;1,500;1,600;1,700&display=swap');
html {
    scroll-behavior: smooth;
}

* {
    margin: 0;
    padding: 0;
    font-family: 'Poppins', sans-serif;
    letter-spacing: 1px;
}

body {
    background: url(BG.jpg);
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    background-attachment: fixed;
}

.contact {
    position: relative;
    min-height: 100vh;
    padding: 0 100px;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    background: rgba(0, 0, 0, 0.2);
}

.contact .content {
    max-width: 800px;
    text-align: center;
}

.contact .content h2 {
    margin-bottom: 20px;
    font-size: 36px;
    color: darkorange;
    font-weight: 500;
}

.contact .content p {
    color: rgba(255, 255, 255, 0.7);
    font-weight: 500;
}

.container {
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    margin-top: 100px;
}

.container .contactInfo {
    width: 30%;
    display: flex;
    flex-direction: column;
}

.container .contactInfo .box {
    position: relative;
    padding: 20px 0;
    display: flex;
}

.container .contactInfo .box .icon {
    background: rgba(0, 0, 0, 0.5);
    color: darkorange;
    font-weight: bolder;
    min-width: 60px;
    height: 60px;
    display: flex;
    justify-content: center;
    align-items: center;
    border-radius: 50%;
    font-size: 22px;
}

.container .contactInfo .box .text {
    display: flex;
    margin-left: 20px;
    font-size: 16px;
    flex-direction: column;
    font-weight: 300;
}

.container .contactInfo .box .text h3 {
    font-weight: 500;
    color: darkorange;
}

.container .contactInfo .box .text p {
    letter-spacing: 1px;
    color: rgba(255, 255, 255, 0.7);
    font-weight: 500;
}

.contactForm {
    border-radius: 15px;
    width: 25%;
    padding: 40px;
    background: rgba(255, 255, 255, 0.2);
}

.contactForm h2 {
    font-size: 20px;
    font-weight: 500;
    color: black;
    letter-spacing: 1px;
}

.contactForm .inputBox {
    color: #000;
    position: relative;
    width: 100%;
    margin-top: 25px;
}

.contactForm .inputBox input,
.contactForm .inputBox textarea {
    background: none;
    font-weight: 600;
    width: 100%;
    padding: 5px 0;
    font-size: 16px;
    margin: 10px 0;
    border: none;
    color: #000;
    letter-spacing: 1.5px;
    border-bottom: 1.5px solid #333;
    outline: none;
    resize: none;
}

.contactForm .inputBoxBtn input[type="submit"]:focus {
    outline: none;
    border: none;
}

.contactForm .inputBox span {
    position: absolute;
    left: 0;
    padding: 5px 0;
    font-size: 16px;
    margin: 10px 0;
    pointer-events: none;
    transition: 0.5s;
    color: rgba(255, 255, 255, 0.7);
}

.contactForm .inputBox input:focus~span,
.contactForm .inputBox input:valid~span,
.contactForm .inputBox textarea:focus~span,
.contactForm .inputBox textarea:valid~span {
    color: darkorange;
    font-size: 12px;
    transform: translateY(-20px);
}

.inputBoxBtn {
    justify-content: center;
    align-items: center;
    position: relative;
    display: flex;
}

.contactForm .inputBoxBtn input[type="submit"] {
    width: 200px;
    border-radius: 50px;
    background: darkorange;
    color: #000;
    border: none;
    cursor: pointer;
    padding: 10px;
    font-size: 18px;
    transition: 1s;
}

.contactForm .inputBoxBtn input[type="submit"]:hover {
    background: #000;
    color: darkorange;
}

@media (max-width:991px) {
    .contact {
        padding: 50px;
    }
    .container {
        flex-direction: column;
    }
    .container .contactInfo {
        margin-bottom: 40px;
    }
    .container .contactInfo,
    .contactForm {
        width: 100%;
    }
}

@media (max-width:300px) {
    .contact {
        overflow: hidden;
    }
    .container {
        flex-direction: column;
    }
    .container .contactInfo {
        margin-bottom: 40px;
    }
    .container .contactInfo,
    .contactForm {
        width: 100%;
    }
}


/* ----------Cloud Animation---------- */

.banner .clouds {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    overflow: hidden;
    pointer-events: none;
}

.banner .clouds img {
    position: absolute;
    bottom: 0;
    max-width: 100%;
    animation: animate calc(1s * var(--i)) linear infinite;
}

@keyframes animate {
    0% {
        opacity: 0;
        transform: scale(1);
    }
    25%,
    75% {
        opacity: 0.3;
    }
    100% {
        opacity: 0;
        transform: scale(3);
    }
}

@media (max-width: 720px) {
    @keyframes animate {
        0% {
            opacity: 0;
            transform: scale(1);
        }
        25%,
        75% {
            opacity: 0;
        }
        100% {
            opacity: 0;
            transform: scale(3);
        }
    }
    .contact {
        background: rgba(0, 0, 0, 0.5);
    }
    .contactForm h2 {
        color: darkorange;
    }
}
```