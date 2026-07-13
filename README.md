# Happy-birthday-Disha
<!Happy Birthday! 🎂❤️
Wishing you a day filled with love, happiness, laughter, and unforgettable memories.
May all your dreams come true and may this new year of your life bring endless success, good health, and joy.
Stay blessed, keep smiling, and enjoy your special day! 🎈🎁✨>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Happy Birthday Disha 🎂</title>



<HAPPY BIRTHDAY DISHA>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Happy Birthday Disha</title>i

<style>
body{
    margin:0;
    font-family:Arial,sans-serif;
    background:linear-gradient(135deg,#ff6b81,#ffb6c1);
    display:flex;
    justify-content:center;
    align-items:center;
    height:100vh;
}
.card{
    background:#fff;
    padding:30px;
    border-radius:20px;
    text-align:center;
    box-shadow:0 10px 25px rgba(0,0,0,.2);
    max-width:400px;
}
h1{
    color:#ff4081;
}
p{
    color:#555;
    font-size:18px;
}
button{
    background:#ff4081;
    color:#fff;
    border:none;
    padding:12px 25px;
    border-radius:30px;
    cursor:pointer;
    font-size:16px;
}
button:hover{
    background:#e91e63;
}
</style>
</head>

<body>

<div class="card">
    <h1>🎉 Happy Birthday Disha  🎂</h1>
    <p>
        Wishing you a day filled with happiness, love, and laughter.
        May Allah bless you with good health and a long life.
        ❤️
    </p>

    <button onclick="showWish()">Click for Surprise</button>
</div>

<script>
function showWish(){
    alert("🎂 Happy Birthday! 🎂❤️
Wishing you a day filled with love, happiness, laughter, and unforgettable memories.
May all your dreams come true and may this new year of your life bring endless success, good health, and joy.
Stay blessed, keep smiling, and enjoy your special day! 🎈🎁✨ ❤️");
}
</script>

</body>
</html>
<div class="card">
    <img src="1783603161529.jpg.jpg" alt="DISHA"
         style="width:180px;height:180px;border-radius:50%;object-fit:cover;border:5px solid #ff4081;">

    <h1>🎉 Happy Birthday DISHA🎂</h1>

    <p>
        Wishing you a day filled with happiness, love, and laughter.
        May Allah bless you with good health and a long life. ❤️
    </p>

    <button onclick="showWish()">Click for Surprise</button>
</div>
<img src="1783603214477.jpg









<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Happy Birthday</title>

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
}

body{
overflow:hidden;
height:100vh;
background:linear-gradient(#ff9ecf,#ffd6e8,#fff);
font-family:Arial,sans-serif;
display:flex;
justify-content:center;
align-items:center;
flex-direction:column;
}

h1{
font-size:50px;
color:#fff;
text-shadow:2px 2px 10px #ff0080;
z-index:10;
}

.cake{
font-size:100px;
z-index:10;
}

.balloon{
position:absolute;
top:-100px;
font-size:40px;
animation:fall linear infinite;
}

@keyframes fall{
0%{
transform:translateY(-100px);
}
100%{
transform:translateY(120vh);
}
}
</style>
</head>

<body>

<h1>🎉 HAPPY BIRTHDAY 🎉</h1>
<div class="cake">🎂</div>

<script>

function balloon(){

const b=document.createElement("div");

b.className="balloon";

b.innerHTML="🎈";

b.style.left=Math.random()*100+"vw";

b.style.animationDuration=(3+Math.random()*5)+"s";

document.body.appendChild(b);

setTimeout(()=>{
b.remove();
},8000);

}

setInterval(balloon,250);

</script>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Happy Birthday ❤️</title>

<style>
*{margin:0;padding:0;box-sizing:border-box;}
body{
font-family:Arial,sans-serif;
background:linear-gradient(135deg,#ff4e8a,#7b5cff);
display:flex;
justify-content:center;
align-items:center;
height:100vh;
overflow:hidden;
color:white;
text-align:center;
}

.page{
width:100%;
padding:20px;
}

h1{
font-size:45px;
margin-bottom:20px;
}

p{
font-size:20px;
margin-bottom:25px;
line-height:1.6;
}

button{
padding:15px 35px;
font-size:20px;
border:none;
border-radius:30px;
cursor:pointer;
background:white;
color:#ff2d75;
font-weight:bold;
}

#gallery{
display:none;
}

img{
width:260px;
height:320px;
border-radius:20px;
object-fit:cover;
box-shadow:0 0 20px white;
}

.caption{
margin-top:20px;
font-size:24px;
}

.balloon{
position:absolute;
bottom:-100px;
font-size:35px;
animation:fly 8s linear infinite;
}

@keyframes fly{
0%{transform:translateY(0);}
100%{transform:translateY(-120vh);}
}
</style>
</head>

<body>

<div id="welcome" class="page">
<h1>🎉 Happy Birthday 🎉</h1>

<p>
Today is your special day ❤️<br>
May your life be filled with happiness,<br>
love and endless smiles.<br><br>
Happy Birthday My Dear! 🎂
</p>

<button onclick="start()">Continue ❤️</button>
</div>

<div id="gallery" class="page">
<img id="photo" src="1.jpg">

<div class="caption" id="text">
Beautiful Memories ❤️
</div>
</div>

<script>

let images=[
"1.jpg",
"2.jpg",
"3.jpg",
"4.jpg"
];

let captions=[
"Our Beautiful Moment ❤️",
"Your Sweet Smile 😊",
"Best Memory Together 💖",
"Happy Birthday My Love 🎂"
];

let i=0;

function start(){
document.getElementById("welcome").style.display="none";
document.getElementById("gallery").style.display="block";

setInterval(()=>{
i=(i+1)%images.length;
document.getElementById("photo").src=images[i];
document.getElementById("text").innerHTML=captions[i];
},3000);

setInterval(balloon,300);
}

function balloon(){
let b=document.createElement("div");
b.className="balloon";
b.innerHTML="🎈";
b.style.left=Math.random()*100+"vw";
document.body.appendChild(b);

setTimeout(()=>{
b.remove();
},8000);
}

</script>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Shuvo | Professional Portfolio</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
}

body{
background:#0f172a;
color:#fff;
overflow-x:hidden;
}

body::before{
content:'';
position:fixed;
width:500px;
height:500px;
background:#3b82f6;
filter:blur(180px);
top:-150px;
left:-100px;
opacity:.4;
z-index:-2;
}

body::after{
content:'';
position:fixed;
width:450px;
height:450px;
background:#8b5cf6;
filter:blur(180px);
bottom:-150px;
right:-100px;
opacity:.4;
z-index:-2;
}

header{
display:flex;
justify-content:space-between;
align-items:center;
padding:25px 8%;
position:fixed;
width:100%;
backdrop-filter:blur(18px);
background:rgba(255,255,255,.05);
z-index:100;
}

.logo{
font-size:28px;
font-weight:bold;
color:#38bdf8;
}

nav a{
color:white;
text-decoration:none;
margin-left:30px;
transition:.3s;
}

nav a:hover{
color:#38bdf8;
}

.hero{
height:100vh;
display:flex;
justify-content:center;
align-items:center;
text-align:center;
padding:20px;
}

.box{
background:rgba(255,255,255,.08);
border:1px solid rgba(255,255,255,.15);
backdrop-filter:blur(20px);
padding:50px;
border-radius:25px;
max-width:800px;
animation:up 1s ease;
}

.box img{
width:180px;
height:180px;
border-radius:50%;
border:5px solid #38bdf8;
object-fit:cover;
margin-bottom:25px;
}

h1{
font-size:50px;
}

h1 span{
color:#38bdf8;
}

p{
margin:20px 0;
font-size:18px;
color:#ddd;
line-height:1.7;
}

.btn{
display:inline-block;
padding:15px 40px;
background:#38bdf8;
color:#fff;
text-decoration:none;
border-radius:40px;
font-weight:bold;
transition:.4s;
}

.btn:hover{
transform:translateY(-5px);
box-shadow:0 0 30px #38bdf8;
}

@keyframes up{
from{
opacity:0;
transform:translateY(80px);
}
to{
opacity:1;
transform:translateY(0);
}
}

@media(max-width:768px){

header{
padding:20px;
}

nav{
display:none;
}

h1{
font-size:35px;
}

.box{
padding:35px;
}

.box img{
width:140px;
height:140px;
}

}
</style>

</head>
<body>

<header>
<div class="logo">SHUVO</div>

<nav>
<a href="#">Home</a>
<a href="#">About</a>
<a href="#">Projects</a>
<a href="#">Contact</a>
</nav>

</header>

<section class="hero">

<div class="box">

<img src="your-photo.jpg" alt="Profile">

<h1>Hi, I'm <span>Shuvo</span></h1>

<p>
Professional Web Developer creating modern,
fast and beautiful websites with clean UI and
smooth animations.
</p>

<a href="#" class="btn">View Portfolio</a>

</div>

</section>

</body>
</Shuvo>
