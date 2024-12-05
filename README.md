<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<style>
    body{
        justify-content: center;
    }
    .dis-flex{
        display: flex;
        
    }
    .justify-center{
        justify-content: center;

    }
    .align-center{
        align-items: center;
    }
    .rounded-50{
        border-radius: 50%;
    }
    .outer{
        height:400px;
        width: 400px;
        background-color: green;
    }
    .inner{
        background-color: blue;
        height: 350px;
        width: 350px;

    }
    .inner1{
        height: 300px;
        width: 300px;
        background-color: red;
    }
    .inner2{
        height: 250px;
        width: 250px;
        background-color: black;
    }
    .inner3{
        height: 200px;
        width: 200px;
        background-color: white;
    }
    .inner4{
        height: 150px;
        width: 150px;
        background-color: aqua;
    }
    .inner5{
        height: 100px;
        width: 100px;
        background-color: beige;
    }
</style>
<body>
    <div class="outer rounded-50 dis-flex justify-center align-center">
        <div class="inner rounded-50 dis-flex justify-center align-center ">
            <div class="inner1 rounded-50 dis-flex justify-center align-center">
                <div class="inner2 rounded-50 dis-flex justify-center align-center">
                    <div class="inner3 rounded-50 dis-flex justify-center align-center">
                        <div class="inner4 rounded-50 dis-flex justify-center align-center">
                            <div class= "inner5 rounded-50">
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
