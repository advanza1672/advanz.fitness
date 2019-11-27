<!DOCTYPE html>
<html lang="en">
    <head>
        <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
        <link href="https://fonts.googleapis.com/css?family=Allura|Montserrat&display=swap" rel="stylesheet">
        <meta charset="UTF-8"/>
        <meta name='viewport' content='width=device-width, initial-scale=1.0, maximum-scale=1.0' />
        <title>Portfolio</title>
    </head>
    <style>
        body {
            background-color: white;
        }
      
        .page {
            display: flex;
            flex-wrap: wrap;
            background-color: white;
        }
      
        .section {
            width: 100%;
            height: 300px;
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
        }
      
        .header {
            background-color: #ffc3c9;
            font-family: 'Allura', cursive;
            font-size: 8vw;
            height: 100px;
            padding-top: 100px;
            text-align: center;
            padding-bottom: 70px;
        }

        .tab {
            background-color: #ffc3c9;
            width: 100%;
            align-items: center;
        }

        ul {
            display: flex;
            justify-content: center;
        }

        li {
            background-color: #ffc3c9;
            color: white;
            text-align: center;
            padding: 25px;
            text-decoration: none;
            font-size: 17px;
            line-height: 25px;
            border-radius: 4px;
            font-family: 'Montserrat', sans-serif;
        }

        /* Change the background color on mouse-over */
        li:hover {
            background-color: white;
            color: #ffc3c9;
        }

        li.active {
            background-color: grey;
            color: white;
            text-decoration: underline;
        }

        .tab-content {
            width: 100%;
        }

         .welcome {
            position: relative;
            float: left;
            padding: 2%;
            text-align: left;
            width: 50%;
        }
        
        h1 {
            color: grey;
            padding-top: 5%;
            font-size: 50px;
            font-family: 'Montserrat', sans-serif;
        }
        
        p {
            font-size: 120%;
            font-family: 'Montserrat', sans-serif;
            text-align: left;
            color: grey;
        }


        /* Mobile Styles */
        @media only screen and (max-width: 400px) {
            .header {
                font-size: 40px;
                }
            .welcome {
                width: 95%!important;
            }
        }
        }

        /* Tablet Styles */
        @media only screen and (min-width: 401px) and (max-width: 960px) {
            .sign-up,
            .header {
                font-size: 125px;
                }
            .welcome {
                width: 75%!important;
            }
        }
        }

        /* Desktop Styles */
        @media only screen and (min-width: 961px) {
            .page {
                width: 960px;
                margin: 0 auto;
            }
            .header {
                height: 400px;
                font-size: 150px;
            }
            .sign-up {
                height: 200px;
                order: 1;
            }
            .content {
                order: 2;
                }
            .welcome {
                width: 50%!important;
        }
        }
    </style>
    <body>
        <div class='page'>
            <div class='section header'>
                Advanz <span style="font-family: 'Montserrat', sans-serif; font-size: 6vw;">Fitness</span>
            </div>

            <div class='tab'>
                <ul class="nav nav-pills nav-justified">
                    <li><a href="index.html" style="color: grey;">Home</a></li>
                    <li><a href="classes.html" style="color: grey;">Classes</a></li>
                    <li><a href="certifications.html" style="color: grey;">Certifications</a></li>
                    <li><a href="contact.html" style="color: grey;">Contact</a></li>
                    <li><a href="blog.html" style="color: grey;">Blog</a></li>
                </ul>
            </div>
            
            <div class="welcome">
                <h1>Welcome to <span style="font-family: 'Allura', cursive; font-size: 50px;">Advanz</span> Fitness!</h1>
                <p>My name is Addison Van Zandbergen and I am the founder of <span style="font-family: 'Allura', cursive; font-size: 110%;">Advanz</span> Fitness.
                I decided to start this venture as a way to better promote my services as a group fitness instructor but decided to push myself even further, creating a personal brand. 
                I focus not only on physical fitness, but mental well-being and personal growth as well. 
                My goal is to promote "advanzments" in the wellness of my clients and myself through integrated fitness and relaxation techniques.
                <div style="color: grey;">NOTE: I am NOT a personal trainer or dietition. One-on-one workouts, outside of yoga or pilates, and any nutritional guidance are outside of my scope of practice.</div></p>
            </div> 
            
        </div>     
    </body>
</html>
