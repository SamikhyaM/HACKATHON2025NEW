strong password: 

@import url('https://fonts.googleapis.com/css2?family=Oxanium:wght@200..800&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100..900;1,100..900&display=swap');

html, body {
    margin: 0;
}

h1 {
    font-family: "Oxanium";
}

p, a {
    font-family: "Roboto";
}

a {
    color: #ebebeb;
}

#screen {
    width: 100vw;
    height: 100vh;
    display: flex;
    flex-direction: column;
}

#header {
    display: flex;
    flex-direction: row;
    flex: 5;
    background-color: rgb(255, 255, 255);
}

#footer {
    flex: 1;
    background-color: #242424;
    border-top: 0.2em solid #f0f0f0;
}

#footer p {
    color: white
}

#navbar {
    background-color: #e6e6e6;
    flex: 1;
    color:#242424;
}

#content {
    background-color: #ffffff;
    flex: 3;
    padding: 1em;
    border-left: 0.2em solid #ffffff;
}

.nav-button {
    background-color: #3b4d40;
    margin: 0.1em;
    padding: 0.3em;
    color:black;
}
.nav-separate {
    background-color: #5f7766;
    margin: 0.1em;
    padding: 0.3em;
    color:rgb(236, 236, 236);
}
.whiteText{
    color:#ebe7e7;
}
.headerThing{
    background-color: #b1ccb9;
    font-family: "Oxanium";
    color:#0e0707;
}


.text-input {
    display: block;
    margin: 0.6em;
    border: none;
    width: 20em;
    background-color: #aaa;
    border-radius: 4px;
    color: #f0f0f0;
img{
    align-items: center;
    display: flex;
    margin: auto;
    justify-content: center;
    width: 400px;
    height:px;

}







phishing html

  
<!DOCTYPE html>
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
        <link rel="stylesheet" type="text/css" href="styles.css">
        <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
        <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js"></script>
        <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>
    </head>
        <body>
            <div id="screen">
                <div id="header">
                    <div id="navbar">
                        <div class="nav-button">
                            <a href="index.html" class = "whiteText">
                                Home
                            </a>
                        </div>
                        <div class="nav-button">
                            <a href="tools/scam-detector.html" class="whiteText">
                                Scam Detector
                            </a>
                        </div>
                        <div class="nav-button">
                            <a href="tools/geolocator.html" class="whiteText">
                                Phone Number Geolocator
                       </div>
                        <div class="nav-button">
                            <a href="tools/encryptor.html" class="whiteText">
                                Encryptor
                            </a>
                        </div>
                        <div class="nav-button">
                            <a href="tools/education.html" class="whiteText">
                                Education
                            </a>
                        </div>
                        <div class="nav-separate">
                            Articles
                        </div>
                        <div class="nav-button" >
                            <a href="articles/phishing.html"class = "whiteText">
                                Phishing
                            </a>
                        </div>
                        <div class="nav-button" >
                            <a href="articles/strongPassword.html"class = "whiteText">
                                Strong Passwords
                            </a>
                        </div>
                    </div>
                    <div class="container-fluid">
                        <h1 class="text-center headerThing">What are phishing attacks?</h1>
                        <br>
                        <h4 class="text-center">Unknowingly, a LOT of people tend to get phished becayse they don't know what it is or how to prevent it. 
                            The name makes it sound a bit confusing, but in short: a typical phishing attack occurs when an unethical hacker tries to steal your sensitive information
                            - passwords, credit card details, etc. - in order to steal your money. Many people are easily trapped because they blindly click on insecure links that direct them to a login page, for example, where they are required to enter their username 
                            and/or password. The hacker then saves this informatin to use in the future in order to access the actual website with your credentials.
                       </h4>
                        <br>
                        <h4 class="text-center">
                            Example:
                        </h4>
                        <h4 class="text-center">
                            gmail.com -> update.gmail.com
                        </h4>
                        <br>
                        <h4 class="text-center">
                            Did you notice the difference? In this case, you should consider the update.google.com to be a malicious websiew because it has
                            extra characters in its name you don't see when visiting their website.
                        </h4>
                        <br>
                        <h4 class="text-center">
                            Another thing to note is that all secure websites begin with "https://" in their url. A way to check this is to hover
                            over the link that you recieved in your gmail and see the url. 

                        </h4>
                        <img src="https://adeliarisk.com/wp-content/uploads/2017/06/Hover_Costco.gif" class="img-rounded">
                        <h6 class="text-center">Picture was found on <a href="https://adeliarisk.com/important-phishing-tip/">this</a> website </h6>
                        <h4 class="text-center">
                            In this example, by hovering over the “MEMBERSHIP BONUS: $50 Cash Card for Filling Out Our 30-Second Survey,” we are able to see that the URL of the website does not begin with “https://”.
                        </h4>
                        <br>
                        <br>
                    </div>
                      </div>
                </div>
                <div id="footer">

                </div>
            </div>
    </body>
</html>
