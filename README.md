<!--HTML code-->

<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8" />
        <meta name="viewport" content="width = device-width, initial-scale = 1.0" />
        <link 
        rel="shortcut icon" 
        href = "https://cdn4.iconfinder.com/data/icons/logos-and-brands/512/227_Netflix_logo-512.png"
        type="image/x-icon" 
        />
        <title>Netflix India - Watch TV Shows Online, Watch Movies Online </title>
        <link rel="stylesheet" href="/CSS/style.css" />
    </head>
    <body>

        <div class="root">
            <nav  class="nav_bar">
                <img class="img-logo" src = "https://www.clipartmax.com/png/middle/215-2154144_transparent-background-netflix-logo.png"
                     alt="Netflix logo" />
                <div class="button-sign-in">Sign in </div>
            </nav>
            <div class="main_container">
                <div class="main_titles_container"></div>          
            </div>
        </div>
             <div>
                <h1 class="main_title">Unlimited movies, TV Shows and more.</h1>
                <h2 class="main_subtitles">Watch anywhere, Cancel anytime.</h2>
                <p class="main_call-to-action">
                    Ready to watch? Enter your email to create or restart your membership.
                </p>
            </div>
            <div class="main_email-container">
                 <input class="main_email_container" type="text" placeholder="Email address" />
                 <div class="button_get_started">Get Started</div>
            </div>
        </div>
    </body>
</html>



/* CSS code */


@font-face {
    font-family: Netflix_Sans_Regular;
    src: url("../fonts/Netflixsans_W_Rg.woff2");
}


.body{
    padding: 0px;
    margin: 0px;
    overflow-y: hidden;
}

root{
    background-size: cover;
    background-image: radial-gradient(rgba(0,0,0,0.4), rgba(0,0,0,0.8)),
    url(https://wpassets.brainstation.io/app/uploads/2017/04/13100509/Netflix-Background.jpg);
    background-repeat: no-repeat;
    background-position: center;
}


.nav_bar{
    padding-top:1%;
    padding-left: 2vw;
    padding-right: 4vw;
    height: 10vh;
    display:flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
    font-family: Arial, Helvetica, sans-serif;
}


.img-logo{
    width: 14%
}

.button-sign-in{
    padding-top: 8px;
    padding-bottom: 8px;
    padding-left: 20px;
    padding-right: 20px;
    background-color: #e50914;
    border-radius: 5px;
    color: white;
    cursor: pointer;
    width:fit-content;
}
.main_container{
    width:100%;
    height:90 vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

.main_title_container{
    font-family:Netflix_Sans_Regular ;
    width: 50%;
    color:white;
}

.main_title{
    font-size: 3.2em;
    margin-bottom: 14px;
    line-height: 1.1;
}

.main_subtitle{
    font-family: Arial, Helvetica, sans-serif;
    font-size: 1.5em;
    margin-bottom: 30px;
}


.main_call-to-action{
    font-family: Arial, Helvetica, sans-serif;
    font-size: 1.2em;
}

.main_email_container{
    width:55%;
    height:fit-content;
    background-color: #ffffff;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
}


.main_email_container{
    outline:none;
    border:none;
    padding: 20px 10px;
    font-size: 1em;
}


.button_get-started{
    cursor: pointer;
    padding:18px 32px;
    font-family: Arial, Helvetica, sans-serif;
    height: fit-content;
    background-color: #e50914;
    color: white;
    font-size: 1.4em;
    text-transform: uppercase;
    text-align: center;
}

.button_get-started:hover{
    background-color: #ff0b18;

}
