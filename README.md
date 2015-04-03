
<html>
    <head>
        <title>NFC West</title>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
                <link rel="stylesheet" type="type/css" href="homepage.css">
                <link rel="stylesheet" href="styles-320.css" media="only screen and (max-width:320px)">
                <link rel="stylesheet" href="styles-480.css" media="only screen and (min-width:320px) and (max-width:480px)">
                <meta name="viewport" content="width=device-width">
                <script src="jquery-1.11.1.min.js"></script>

</head>
    <body>
          <div id="header"> NFC Western Division</div>   
          
          <canvas id="myCanvas" width="750" height="200" style="border:3px solid blue;">
            Your browser does not support the HTML5 canvas tag.
        </canvas>
        
        <script>
            var c=document.getElementById ("myCanvas");
            var ctx=c.getContext ("2d");
            ctx.font="40px Arial";
            ctx.strokeStyle='red';
            ctx.strokeText("Welcome To Greatest Website On Earth!",3,120);
        </script>
        
        <div id="wrapper">
            <div id="content">This website will allow you to navigate between each of the four 
                    NFC West NFL teams and view thier 2013 statistical leaders as well as their 2014 player 
                    rosters and depth charts. <br> If you would like to receive updates on the NFL as well as your favorite teams, 
                    click on the following link and you will be redirected to our registration page. <a href="registration.html">Registration Form</a></div>
            <div id="left">
                <h1>NFL Teams</h1>
                <h3> <a id="ari" href="cardinals.html"> Arizona Cardinals </a> </h3>
                <h3> <a id="san" href="49ers.html"> San Francisco 49ers </a> </h3>
                <h3> <a id="sea" href="seahawks.html"> Seattle Seahawks </a> </h3>
                <h3> <a id="stl" href="rams.html"> St. Louis Rams </a> </h3>
            </div>
            <div id="right">
                <h1>Partner Sites</h1>
                <h3> <a id="espn" href="http://espn.go.com/">ESPN</a></h3>
                <h3> <a id="yahoo" href="http://sports.yahoo.com/">Yahoo Sports</a></h3>
                <h3> <a id="nfl" href="http://www.nfl.com/">NFL</a></h3>
                <h3> <a id="cbs" href="http://www.cbssports.com/">CBS</a></h3>
            </div>
        </div>
        <div id="footer"> Mark Eulalia Final Project &copy; </div>
      
    </body>
</html>
