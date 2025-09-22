<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Reto Html</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            background-color: #f5cf51;
            font-family: arial, sans-serif;
            margin: 0;
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        #card {
            border: solid;
            width: 350px;
            background-color: #ffffff;
            padding: 16px;
            border-radius: 8px;
        }

        img {
            width: 100%;
            border-radius: 8px;
            display: block;
            margin: 0 auto;
            border-radius: 8px;
        }

        .Learning {
            background-color: #f5cf51;
            text-align: left;
            font-weight: bold;
            font-size: 12px;
            margin-bottom: 12px;
            margin-top: 12px;
            /*mover el div un poco mas abajo*/
            padding: 16px;
            border-radius: 8px;
            display: inline-block;
            /*para que ocupe solo la palabra*/
        }


        .hooper img {

            float: left;
            width: 15%;
            border-radius: 50%;

        }

        h1 {
            text-align: left;
            font-size: 16px;
            font-weight: bolder;
            margin-bottom: 12px;
            margin-top: 16px;
        }

        h2 {
            text-align: left;
            font-size: 10px;
        }

        p {
            font-size: 10px
        }

        h3 {

            text-align: left;
            font-size: 12px;
            font-weight: bold
            
        }
        
    </style>
</head>

<body>
    <section id="card">
        <img src="Screenshot 2025-09-17 195756.png" alt="">
        <div class="Learning">Learning</div>
        <h2>Published 21 Dec 2023</h2>

        <h1>HTML & CSS Foundations</h1>
        <p>These languages are the backbone of every website, defining structure,content, and presentation</p>
        <div class="hooper">
            <img src="GREG_HOOPER_6457.webp" alt="Greg hooper">
            <h3>Greg Hooper</h3>
        </div>


    </section>
</body>

</html>
