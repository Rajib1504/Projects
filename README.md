@@ -0,0 +1,173 @@
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Kanit:wght@500;900&display=swap" rel="stylesheet">
    <title>Suzana Zumpel</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        html,
        body {
            height: 100%;
            width: 100%;
        }




        #mainDiv {
            background-color: #ab8f97;
            height: 100%;
            width: 100%;
            display: flex;
            border-radius: 10px;
            justify-content: center;
            align-items: center;
        }

        #nav {
            position: absolute;
            top: 15%;
            left: 260px;
            display: flex;
            justify-content: space-between;    
            align-items: center;
            width: 250px;
            height: 30px;
        }
        #nav>h5{
            color: white;
            letter-spacing: 2px;
            font-size:11px;
            font-family: gilroy;

        }
        #nav>img{
width: 50px;
        }

        #text {
            position: absolute;
            left: 18%;
            top: 35%;
            /* width: 900px;
            height: 300px;
            background-color: black; */
        }

        #text>h1 {
            font-family: 'Kanit', sans-serif;
            font-size: 99px;
            line-height: 75px;
            font-weight: 510;
            letter-spacing: 1px;
            color: #fff;
            text-transform: uppercase;


        }

        #box1 {
            height: 80%;
            width: 20%;
            background-color: #b6a4a9ec;
        }

        #box2 {
            height: 80%;
            width: 50%;
            background-color: #b0999f54;
            background-image: url(https://images.unsplash.com/photo-1604514628550-37477afdf4e3?q=80&w=1527&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D);
            background-size: cover;
            background-repeat: no-repeat;
            background-position: center;
            /* align-self: center; */
        }

        #overlay {
            background-color: #b3848f4f;
            height: 100%;
            width: 100%;
        }

        #box3 {
            height: 80%;
            width: 7%;
            background-color: #d4bfc4ec;
        }

        #small_Img {
            background-image: url(https://images.unsplash.com/flagged/photo-1628336358297-50dfd92155c8?q=80&w=1587&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D);
            background-repeat: no-repeat;
            background-size: cover;
            background-position: center;
            position: absolute;
            right: 15%;
            top: 45%;
            transform: translate(0, -50%);
            height: 350px;
            width: 250px;
            border-radius: 10px;
        }


        #rotate_Text {
            position: absolute;
            right: -30%;
            top: 11%;
            transform: rotate(90deg);
            transform-origin: 0% 0%;
        }

        #rotate_Text>h1 {
            font-size: 50px;
            font-family: monospace;
            -webkit-text-stroke-width: 2px;
            -webkit-text-stroke-color: white;
            letter-spacing: 10px;
            font-weight: 900;
            color: transparent;
            text-transform: uppercase;

        }
    </style>
</head>

<body>
    <div id="mainDiv">
        <div id="nav">
            <img src="https://www.chungiyoo.com/img/faces/smile%2001.svg"  alt="">
            <h5>Suzana Zumpel</h5>
        </div>
        <div id="box1"></div>
        <div id="box2">
            <div id="overlay"></div>
        </div>
        <div id="box3"></div>
    </div>

    <div id="text">
        <h1>Nature</h1>
        <h1>Morte</h1>
        <h1>For</h1>
        <h1>Harper's</h1>
    </div>
    <div id="small_Img">
        <div id="overlay"></div>
    </div>
    <div id="rotate_Text">
        <h1>Selection Winter</h1>
    </div>

</body>

</html>
