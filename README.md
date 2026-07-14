<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Happy Birthday Suraiya Shammi Disha ❤️</title>

<link rel="stylesheet" href="style.css">
</head>

<body>

<div class="balloons"></div>
<div class="cakes"></div>

<header>
<div class="logo">
<span>G</span><span>o</span><span>o</span><span>g</span><span>l</span><span>e</span>
</div>

<form action="https://www.google.com/search" method="GET">
<input type="text" name="q" placeholder="Search Google..." class="search">
</form>

<div class="apps">

<a href="https://facebook.com" class="app">
<img src="https://cdn-icons-png.flaticon.com/512/733/733547.png">
<p>Facebook</p>
</a>

<a href="https://instagram.com" class="app">
<img src="https://cdn-icons-png.flaticon.com/512/2111/2111463.png">
<p>Instagram</p>
</a>

<div class="app">
<img src="https://cdn-icons-png.flaticon.com/512/2276/2276931.png">
<p>Cake</p>
</div>

<div class="app">
<img src="https://cdn-icons-png.flaticon.com/512/1829/1829586.png">
<p>Gallery</p>
</div>

</div>

<section class="card">

<img src="photo.jpg" class="hero">

<div class="text">

<h1>🎂 Happy Birthday ❤️</h1>

<h2>Suraiya Shammi Disha</h2>

<p>

May Allah bless you with happiness,
success and a beautiful life.

Stay smiling forever.

I Love You So Much ❤️

Happy Birthday 🎉

</p>

</div>

</section>

<script src="script.js"></script>

</body>
</html>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,sans-serif;
}

body{
background:#202124;
color:#fff;
overflow-x:hidden;
text-align:center;
}

.logo{
font-size:70px;
font-weight:bold;
margin-top:40px;
}

.logo span:nth-child(1){color:#4285F4;}
.logo span:nth-child(2){color:#EA4335;}
.logo span:nth-child(3){color:#FBBC05;}
.logo span:nth-child(4){color:#4285F4;}
.logo span:nth-child(5){color:#34A853;}
.logo span:nth-child(6){color:#EA4335;}

.search{
width:90%;
max-width:650px;
padding:15px;
margin:30px auto;
display:block;
border:none;
border-radius:30px;
background:#303134;
color:#fff;
font-size:18px;
outline:none;
}

.apps{
display:flex;
justify-content:center;
gap:20px;
flex-wrap:wrap;
margin:30px;
}

.app{
background:#303134;
padding:15px;
border-radius:15px;
width:90px;
text-decoration:none;
color:#fff;
transition:.3s;
}

.app:hover{
transform:scale(1.08);
}

.app img{
width:45px;
height:45px;
}

.card{
width:90%;
max-width:900px;
margin:40px auto;
background:#303134;
border-radius:20px;
overflow:hidden;
box-shadow:0 0 20px rgba(255,255,255,.08);
}

.hero{
width:100%;
height:420px;
object-fit:cover;
}

.text{
padding:25px;
}

.text h1{
color:#ff4d6d;
margin-bottom:10px;
}

.text h2{
margin-bottom:15px;
}

.text p{
line-height:1.8;
color:#ddd;
}

.balloon,
.cake{
position:fixed;
top:-120px;
pointer-events:none;
z-index:999;
animation:fall linear infinite;
}

.balloon{
font-size:40px;
}

.cake{
font-size:34px;
}

@key

// Balloon Rain
const balloonBox = document.querySelector(".balloons");

function createBalloon() {
    const b = document.createElement("div");
    b.className = "balloon";
    b.innerHTML = "🎈";

    b.style.left = Math.random() * 100 + "vw";
    b.style.animationDuration = (4 + Math.random() * 5) + "s";
    b.style.fontSize = (30 + Math.random() * 30) + "px";

    balloonBox.appendChild(b);

    setTimeout(() => {
        b.remove();
    }, 9000);
}

setInterval(createBalloon, 400);


// Cake Rain
const cakeBox = document.querySelector(".cakes");

function createCake() {
    const c = document.createElement("div");
    c.className = "cake";
    c.innerHTML = "🎂";

    c.style.left = Math.random() * 100 + "vw";
    c.style.animationDuration = (5 + Math.random() * 4) + "s";
    c.style.fontSize = (25 + Math.random() * 20) + "px";

    cakeBox.appendChild(c);

    setTimeout(() => {
        c.remove();
    }, 9000);
}

setInterval(createCake, 900);


// Auto Focus Search
window.onload = () => {
    document.querySelector(".search").focus();
};


// Birthday Message
setTimeout(() => {
    alert("🎉 Happy Birthday Suraiya Shammi Disha ❤️\n\nMay Allah Bless You Always! 🎂");
}, 1500);
