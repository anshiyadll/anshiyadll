<!DOCTYPE html>
<html>
  <head>
    <style>
    @import url('https:fonts.googleapis.com/css2?family=Poppins:wght@200;300;400;500;600;700;800;900&display=swap');
    *{
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Poppins', sans-serif;
    }
    .contact{
      position: relative;
      min-height: 100vh;
      padding: 50px  100px;
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;
      background:  url(file:///A:/20230930_202527.jpg);
      background-size: cover;
    }
    .contact .ContactUs{
      font-style: italic;
      font-size: 20px;
    }
    .contact .ContactUs h1{
      color: #00bca4;
    }
    .contact .ContactUs p{
      color: white;
    }
    .contant .content{
      max-width: 800px;
      text-align: center;
    }
    .contant .content h2 {
      font-size: 36px;
      font-weight: 500;
      color: #ffff00;
    }.contant .content p{
      font-weight: 300;
      color: #fff;
    }
    .container{
      width: 100%;
      display: flex;
      justify-content: center;
      align-items: center;
      margin-top: 30px;
    }
    .container .contactInfo{
      width: 50%;
      display: flex;
      flex-direction: column;
    }
    .container .contactInfo .box{
      position: relative;
      padding: 20px 0px;
      display: flex;
    }
    .container .contactInfo .box .icon{
      min-width: 60px;
      height: 60px;
      background: #fff;
      display: flex;
      justify-content: center;
      align-items: center;
      border-radius: 50%;
      font-size: 22px;
    }
    .container .contactInfo .box .text{
      display: flex;
      margin-left: 20px;
      font-size: 16px;
      color: #fff;
      flex-direction: column;
      font-weight: 600;
    }
    .container .contactInfo .box .text h2{
      font-weight: 500;
      color: #00bca4;
    }
    .contactForm{
      width: 40%;
      padding: 40px;
      background: url(file:///A:/1696085576643.jpg);
    }
    .contactForm h3{
      font-size: 30px;
      color: #00bca4;
      font-weight: 50;
    }
    .contactForm .inputBox{
      position: relative;
      width: 100%;
      margin-top: 10px;
    }
    .contactForm .inputBox .input,
    .contactForm .inputBox texttarea{
      width: 300%;
      padding: 5px 0;
      font-size: 16px;
      margin: 10px 0;
      border: none;
      border-bottom: 2px solid #333;
      outline: none;
      resize: none;
    }
    .contactForm .inputBox span{
      position: relative;
      pointer-events: none;
      transition: 0.5%;
      color: red;
    }
    .contactForm .inputBox input:focus ~ span,
    .contactForm .inputBox input:valid ~ span,
    .contactForm .inputBox textarea:focus ~ span,
    .contactForm .inputBox textarea:valid ~ span{
      color: #e91e63;
      font-size: 12px;
      transform: translate(-55px);
    }
    .contactForm .inputBox input[type="submit"]{
      width: 100px;
      background: none;
      color: #fff;
      border: none;
      cursor: pointer;
      padding: 10px;
      font-size: 18px;
    }
    @import (max-width: 991px)
    {
      .contact
      {
        padding: 50px;
      }
      .container{
        flex-direction: column;
      }
      .container.contactInfo{
        margin-bottom: 40px;
      }
      .container.contactInfo,
      .contactForm
      {
        width: 100%;
      }
      .contactForm .inputBox input[type="submit"]{
        background: cyan;
      }
    }
    </style>
    <meta name="viewport" content="initial-scale=1.0">
    <title>Contact Us</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css" integrity="sha512-z3gLpd7yknf1YoNbCzqRKc4qyor8gaKU1qmn+CShxbuBusANI9QpRohGBreCFkKxLhei6S9CQXFEbbKuqLg0DA=="
    crossorigin="anonymous" referrerpolicy="no-referrer">
    <link rel="stylesheet" type="text/css" href="style.css">
  </head>
  <body>
    <section class="contact">
      <div class="content">
        <div class="ContactUs">
          <h1>Contact Us.</h1>
          <p>ridhim99 the site is arid, it is followed by adipisicingelit, but it is the same time that
             they happen to wash and ridhim99 some great things</p>
        </div>
        <div class="container">
          <div class="contactInfo">
            <div class="box">
              <div class="icon"><i class="fa fa-map-marker" aria-hidden="true"></i></div>
              <div class="text">
                <h2>Address.</h2>
                <p>Ulau,<br>Firozabad,<br>Uttar-Pradesh,<br>283103</p>
              </div>
            </div>
            <div class="box">
              <div class="icon"><i class="fa fa-phone" aria-hidden="true"></i></div>
              <div class="text">
                <h2>Phone</h2>
                <p>853-501-1326</p>
              </div>
            </div>
            <div class="box">
              <div class="icon"><i class="fa fa-envelope" aria-hidden="true"></i></div>
              <div class="text">
                <h2>Email</h2>
                <p>shivamyadav142312@gmail.com</p>
              </div>
            </div>
          </div>
          <div class="contactForm">
            <form>
              <h3>Send Message</h3>
              <div class="inputBox">
                <input type="text" name="" required="required">
                <span>Full name.</span>
              </div>
              <div class="inputBox">
                <input type="text" name="" required="required">
                <span>Email.</span>
              </div>
              <div class="inputBox">
                <textarea required="required"></textarea>
                <span>Text your Message.</span>
              </div>
              <div class="input">
                <input type="submit" name="" value="send">
              </div>
            </form>
          </div>
        </div>
      </div>
    </section>
  </body>
</html>
