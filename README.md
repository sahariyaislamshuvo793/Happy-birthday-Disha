# Happy-birthday-Disha
<!DOCTYPE html>
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
    alert("🎂 Happy Birthday Mama! May all your dreams come true. ❤️");
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
