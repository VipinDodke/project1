<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/twitter/bootstrap/4.1.2/css/bootstrap.min.css">


    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/css/bootstrap.min.css" integrity="sha384-TX8t27EcRE3e/ihU7zmQxVncDAy5uIKz4rEkgIXeMed4M0jlfIDPvg6uqKI2xXr2" crossorigin="anonymous">

    <title>Template!</title>
  </head>
  <!------------------------------------------style---------------------------->
  <style>
    
        #wrapper
        {
            width:100%;
            height: 100vh;
            scroll-behavior: smooth;
            overflow-y: scroll;

        }
        #wrapper div
        {
           position: relative;
           width: 100%;
           height: 100%;  
        }
        .text-content
        {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%,-50%);
            width: 100%;
            text-align: center;
            padding: 0 150px;
        }
        .text-content h1
        {
            font-size: 100px;
            font-weight: bold;
            color: #fff;
            font-family: bignoodletitling;
            letter-spacing: 5px;
        }
        .text-content p
        {
            font-family: merienda;
            line-height: 35px;
            color: #fff;
        }
        ul
        {
            position: fixed;
            top: 10%;
            right: 15px;
            transform: translateY(50%);
            margin: 0;
            padding: 0;
            z-index: 1; 
        }
        ul li
        {
            background-color: transparent;
        }
        ul li a
        {
            display: block;
            text-decoration: none;
            height: 45px;
            font-size: 24px;
            background: #fff;
            width: 55px;
            color: #262626;
            margin: 4px 0;
            padding-left: 15px;
            line-height: 45px; 
        }
        ul li a:hover
        {
            background: #333;
            text-orientation: none;
            color: #fff;
        }
        #home
        {
            background-image: url(https://source.unsplash.com/1600x900/?Dark);
            -webkit-background-size:cover;
            background-size: cover;
            background-position: center center;  
        }
        #about
        {
            background-color: goldenrod ;
        }
        #section
        {
            background-color: deepskyblue ;
        }
        #tech
        {
            background-color: brown ;
        }
        #contact
        {
            background-color: royalblue ;
        }
                
                
                








  </style>
  <body>

    <ul>
        <li><a href="#home"><i class="fa fa-home"><svg width="1em" height="1em" viewBox="0 0 16 16" class="bi bi-grid-1x2" fill="currentColor" xmlns="http://www.w3.org/2000/svg">
  <path fill-rule="evenodd" d="M6 1H1v14h5V1zm9 0h-5v5h5V1zm0 9h-5v5h5v-5zM0 1a1 1 0 0 1 1-1h5a1 1 0 0 1 1 1v14a1 1 0 0 1-1 1H1a1 1 0 0 1-1-1V1zm9 0a1 1 0 0 1 1-1h5a1 1 0 0 1 1 1v5a1 1 0 0 1-1 1h-5a1 1 0 0 1-1-1V1zm1 8a1 1 0 0 0-1 1v5a1 1 0 0 0 1 1h5a1 1 0 0 0 1-1v-5a1 1 0 0 0-1-1h-5z"/>
</svg></i></a></li>
        <li><a href="#about"><i class="fa fa-book"><svg width="1em" height="1em" viewBox="0 0 16 16" class="bi bi-people" fill="currentColor" xmlns="http://www.w3.org/2000/svg">
  <path fill-rule="evenodd" d="M15 14s1 0 1-1-1-4-5-4-5 3-5 4 1 1 1 1h8zm-7.978-1h7.956a.274.274 0 0 0 .014-.002l.008-.002c-.002-.264-.167-1.03-.76-1.72C13.688 10.629 12.718 10 11 10c-1.717 0-2.687.63-3.24 1.276-.593.69-.759 1.457-.76 1.72a1.05 1.05 0 0 0 .022.004zM11 7a2 2 0 1 0 0-4 2 2 0 0 0 0 4zm3-2a3 3 0 1 1-6 0 3 3 0 0 1 6 0zM6.936 9.28a5.88 5.88 0 0 0-1.23-.247A7.35 7.35 0 0 0 5 9c-4 0-5 3-5 4 0 .667.333 1 1 1h4.216A2.238 2.238 0 0 1 5 13c0-1.01.377-2.042 1.09-2.904.243-.294.526-.569.846-.816zM4.92 10c-1.668.02-2.615.64-3.16 1.276C1.163 11.97 1 12.739 1 13h3c0-1.045.323-2.086.92-3zM1.5 5.5a3 3 0 1 1 6 0 3 3 0 0 1-6 0zm3-2a2 2 0 1 0 0 4 2 2 0 0 0 0-4z"/>
</svg></i></a></li>
        <li><a href="#section"><i class="fa fa-cog"><svg width="1em" height="1em" viewBox="0 0 16 16" class="bi bi-tags" fill="currentColor" xmlns="http://www.w3.org/2000/svg">
  <path fill-rule="evenodd" d="M3 2v4.586l7 7L14.586 9l-7-7H3zM2 2a1 1 0 0 1 1-1h4.586a1 1 0 0 1 .707.293l7 7a1 1 0 0 1 0 1.414l-4.586 4.586a1 1 0 0 1-1.414 0l-7-7A1 1 0 0 1 2 6.586V2z"/>
  <path fill-rule="evenodd" d="M5.5 5a.5.5 0 1 0 0-1 .5.5 0 0 0 0 1zm0 1a1.5 1.5 0 1 0 0-3 1.5 1.5 0 0 0 0 3z"/>
  <path d="M1 7.086a1 1 0 0 0 .293.707L8.75 15.25l-.043.043a1 1 0 0 1-1.414 0l-7-7A1 1 0 0 1 0 7.586V3a1 1 0 0 1 1-1v5.086z"/>
</svg></i></a></li>
        <li><a href="#tech"><i class="fa fa-folder"><svg width="1em" height="1em" viewBox="0 0 16 16" class="bi bi-link-45deg" fill="currentColor" xmlns="http://www.w3.org/2000/svg">
  <path d="M4.715 6.542L3.343 7.914a3 3 0 1 0 4.243 4.243l1.828-1.829A3 3 0 0 0 8.586 5.5L8 6.086a1.001 1.001 0 0 0-.154.199 2 2 0 0 1 .861 3.337L6.88 11.45a2 2 0 1 1-2.83-2.83l.793-.792a4.018 4.018 0 0 1-.128-1.287z"/>
  <path d="M6.586 4.672A3 3 0 0 0 7.414 9.5l.775-.776a2 2 0 0 1-.896-3.346L9.12 3.55a2 2 0 0 1 2.83 2.83l-.793.792c.112.42.155.855.128 1.287l1.372-1.372a3 3 0 0 0-4.243-4.243L6.586 4.672z"/>
</svg></i></a></li>
        <li><a href="#contact"><i class="fa fa-envelope"><svg width="1em" height="1em" viewBox="0 0 16 16" class="bi bi-soundwave" fill="currentColor" xmlns="http://www.w3.org/2000/svg">
  <path fill-rule="evenodd" d="M8.5 2a.5.5 0 0 1 .5.5v11a.5.5 0 0 1-1 0v-11a.5.5 0 0 1 .5-.5zm-2 2a.5.5 0 0 1 .5.5v7a.5.5 0 0 1-1 0v-7a.5.5 0 0 1 .5-.5zm4 0a.5.5 0 0 1 .5.5v7a.5.5 0 0 1-1 0v-7a.5.5 0 0 1 .5-.5zm-6 1.5A.5.5 0 0 1 5 6v4a.5.5 0 0 1-1 0V6a.5.5 0 0 1 .5-.5zm8 0a.5.5 0 0 1 .5.5v4a.5.5 0 0 1-1 0V6a.5.5 0 0 1 .5-.5zm-10 1A.5.5 0 0 1 3 7v2a.5.5 0 0 1-1 0V7a.5.5 0 0 1 .5-.5zm12 0a.5.5 0 0 1 .5.5v2a.5.5 0 0 1-1 0V7a.5.5 0 0 1 .5-.5z"/>
</svg></i></a></li>
    </ul>

    <div id="wrapper">
        <div id="home">
            <section class="text-content">
                <h1>HOMEPAGE</h1>
                <p><b>This page sets forth the nuts and bolts of creating a page in any namespace – the mechanics of doing so. Please note that only logged in users can create pages in non-talk namespaces.This page does not delve into the reasons one should or should not create a page, for a more general treatment regarding the DOs and DON'Ts of article creation, please see Wikipedia:Contributing to Wikipedia and consider taking a tour through the Wikipedia:Tutorial. For a guided process to create an article (and for which these technical instructions will not be needed), see the article wizard and Wikipedia:Articles for creation, where a proposed article will first be created as a draft and then submitted for review before possible "publication" by a move to the article mainspace.</b></p>
            </section>
            
        </div>
        <div id="about">
            <section class="text-content">
                <h1>About</h1>
                <p>This page sets forth the nuts and bolts of creating a page in any namespace – the mechanics of doing so. Please note that only logged in users can create pages in non-talk namespaces.This page does not delve into the reasons one should or should not create a page, for a more general treatment regarding the DOs and DON'Ts of article creation, please see Wikipedia:Contributing to Wikipedia and consider taking a tour through the Wikipedia:Tutorial. For a guided process to create an article (and for which these technical instructions will not be needed), see the article wizard and Wikipedia:Articles for creation, where a proposed article will first be created as a draft and then submitted for review before possible "publication" by a move to the article mainspace.</p>
            </section>
            
        </div>
        <div id="section">
            <section class="text-content">
                <h1>SECTion</h1>
                <p>This page sets forth the nuts and bolts of creating a page in any namespace – the mechanics of doing so. Please note that only logged in users can create pages in non-talk namespaces.This page does not delve into the reasons one should or should not create a page, for a more general treatment regarding the DOs and DON'Ts of article creation, please see Wikipedia:Contributing to Wikipedia and consider taking a tour through the Wikipedia:Tutorial. For a guided process to create an article (and for which these technical instructions will not be needed), see the article wizard and Wikipedia:Articles for creation, where a proposed article will first be created as a draft and then submitted for review before possible "publication" by a move to the article mainspace.</p>
            </section>
            
        </div>
        <div id="tech">
            <section class="text-content">
                <h1>TECHNOLOGY</h1>
                <p>This page sets forth the nuts and bolts of creating a page in any namespace – the mechanics of doing so. Please note that only logged in users can create pages in non-talk namespaces.This page does not delve into the reasons one should or should not create a page, for a more general treatment regarding the DOs and DON'Ts of article creation, please see Wikipedia:Contributing to Wikipedia and consider taking a tour through the Wikipedia:Tutorial. For a guided process to create an article (and for which these technical instructions will not be needed), see the article wizard and Wikipedia:Articles for creation, where a proposed article will first be created as a draft and then submitted for review before possible "publication" by a move to the article mainspace.</p>
            </section>
            
        </div>
        <div id="contact">
            <section class="text-content">
                <h1>CONTACT</h1>
                <p>This page sets forth the nuts and bolts of creating a page in any namespace – the mechanics of doing so. Please note that only logged in users can create pages in non-talk namespaces.This page does not delve into the reasons one should or should not create a page, for a more general treatment regarding the DOs and DON'Ts of article creation, please see Wikipedia:Contributing to Wikipedia and consider taking a tour through the Wikipedia:Tutorial. For a guided process to create an article (and for which these technical instructions will not be needed), see the article wizard and Wikipedia:Articles for creation, where a proposed article will first be created as a draft and then submitted for review before possible "publication" by a move to the article mainspace.</p>
            </section>
            
        </div>
       
    </div>









    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ho+j7jyWK8fNQe+A12Hb8AhRq26LrZ/JpcUGGOn+Y7RsweNrtN/tE3MoK7ZeZDyx" crossorigin="anonymous"></script>

  </body>
</html>
