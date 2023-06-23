# Glowing-button
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        *{
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body{
        background: black;
        font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
        font-weight: bold;

        }
        div{
            display: flex;
            align-items: center;
            justify-content: center;
            flex-direction: column;
            margin-top: 50px;
        }
        a{
            position: relative;
            display: inline-block;
            padding: 25px 30px;
            margin: 35px 0px;
            color:#00ffff;
            text-decoration: none;
            text-transform: uppercase;
            transition: 0.5s;
            letter-spacing: 4px;
            overflow: hidden;

        }
        a:hover{
            background: #00ffff;
            color:#000017;
            box-shadow: 
            0 0 5px #00ffff,
            0 0 25px #00ffff,
            0 0 50px #00ffff,
            0 0 200px #00ffff;
        -webkit-box-reflect:
        below 1px linear-gradient(transparent,#0005);    
        }
        a:nth-child(1){
            filter: hue-rotate(240deg);
        }
        a:nth-child(2){
            filter: hue-rotate(110deg);
        }
        a span{
            position: absolute;
            display: block;

        }
        a span:nth-child(1){
            top:0;
            left:0;
            width: 100%;
            height: 2px;
            background:linear-gradient(90deg,transparent,#00ffff);
            animation:animate1 1s linear infinite;
        }
        @keyframes animate1{
            0%{
                left:-100%;

            }
            50%,100%{
                left:100%;
            }
        }

        a span:nth-child(2){
            top:-100%;
            right:0;
            width: 2px;
            height: 100%;
            background:linear-gradient(90deg,transparent,#00ffff);
            animation:animate2 1s linear infinite;
            animation-delay: 0.25s;
        }
        @keyframes animate2{
            0%{
                top:-100%;

            }
            50%,100%{
                top:100%;
            }
        }
        a span:nth-child(3){
            bottom:0;
            right:0;
            width: 100%;
            height: 2px;
            background:linear-gradient(90deg,transparent,#00ffff);
            animation:animate3 1s linear infinite;
            animation-delay: 0.50ss;
        }
        @keyframes animate3{
            0%{
                right:-100%;

            }
            50%,100%{
                right:100%;
            }
        }
        a span:nth-child(4){
            bottom:-100%;
            left:0;
            width: 2px;
            height: 100%;
            background:linear-gradient(90deg,transparent,#00ffff);
            animation:animate4 1s linear infinite;
            animation-delay: 0.75s;
        }
        @keyframes animate4{
            0%{
                bottom:-100%;

            }
            50%,100%{
                bottom:100%;
            }
        }
h1{
              margin-top: 15px;
             
             position: relative;
            display: inline-block;
            padding: 15px 25px;
            margin: 30px 0px;
            color:pink;
            text-decoration: none;
            text-transform: uppercase;
            transition: 0.5s;
            letter-spacing: 3px;
            overflow: hidden;
            text-align: center;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
}
h1:hover{
            background: red;
            color:#000017;
            box-shadow: 
            0 0 5px #00ffff,
            0 0 25px #00ffff,
            0 0 50px #00ffff,
            0 0 200px #00ffff;
        -webkit-box-reflect:
        below 1px linear-gradient(transparent,#0005);    
        }


    </style>
</head>
<body>
<center><h1> glowing buttons  </h1>  </center>
    <div>
        <a href="#">
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            NEHA PANDEY
        </a>
        <a href="#">
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            NEHA PANDEY
        </a>
        <a href="#">
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            NEHA PANDEY
        </a>
    </div>
</body>
</html>
