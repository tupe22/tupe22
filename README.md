<!DOCTYPE html>
<html>
    <head>
        <style>
body{
    margin:0;
    padding: 0;
    background: #000000;
}
ul{
position: absolute;
top: 50%;
left: 50%;
transform: translate(-50%,-50%
);
margin:0;
padding:0;
display: flex;
}
ul li{
    list-style: none;
    font-family: Arial;
    font-size: 3em;
letter-spacing: 15px;
text-shadow: none;
animation:animate 1s infinite
linear;
}
@keyframes animate{
    0%{
        color:#484848;
        text-shadow: none;
    }
    18%{
        color:#484848;
        text-shadow: none;
    }
    20%{
        color:#fff900;
        text-shadow: 0 0 7px #fff900
        ,0 0 20px #ff6c00;
    }
    30%{
        color:#484848;
        text-shadow: none;
    }
    35%{
        color:#fff900;
        text-shadow: 0 0 7px #fff900
        ,0 0 20px #ff6c00;
    }
    70%{
        color:#484848;
        text-shadow: none;
    }
    85%{
        color:#fff900;
        text-shadow: 0 0 7px #fff900
        ,0 0 20px #ff6c00;
    }
    90%{
        color:#484848;
        text-shadow: none;
    }
    100%{   
        color:#484848;
        text-shadow: none;
    }
}
ul li:nth-child(1){
    animation-delay:.2s;
    }
ul li:nth-child(2){
    animation-delay:.4s;
}
ul li:nth-child(3){
    animation-delay:.6s;
}
ul li:nth-child(4){
    animation-delay:.8s;
}
ul li:nth-child(5){
    animation-delay:1s;
}
ul li:nth-child(6){
    animation-delay:1.2s;
}
ul li:nth-child(7){
    animation-delay:1.4s;
}
        </style>
    </head>
    <body>
<ul>
    <li>T</li>
    <li>U</li>
    <li>P</li>
    <li>E</li>
</ul>
</body>
</html>
