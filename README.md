/* ===== Google Style Birthday Theme ===== */

*{
  margin:0;
  padding:0;
  box-sizing:border-box;
}

body{
  font-family:Arial,sans-serif;
  background:#202124;
  color:#fff;
  overflow-x:hidden;
}

header{
  display:flex;
  justify-content:flex-end;
  padding:20px;
}

header a{
  color:#fff;
  text-decoration:none;
  margin-left:20px;
  font-size:15px;
}

.container{
  width:100%;
  display:flex;
  flex-direction:column;
  align-items:center;
  margin-top:60px;
}

.logo{
  font-size:80px;
  font-weight:bold;
}

.logo span:nth-child(1){color:#4285F4;}
.logo span:nth-child(2){color:#EA4335;}
.logo span:nth-child(3){color:#FBBC05;}
.logo span:nth-child(4){color:#4285F4;}
.logo span:nth-child(5){color:#34A853;}
.logo span:nth-child(6){color:#EA4335;}

.search{
  width:650px;
  max-width:90%;
  margin-top:25px;
}

.search input{
  width:100%;
  padding:16px 25px;
  border:none;
  border-radius:40px;
  background:#303134;
  color:#fff;
  font-size:18px;
  outline:none;
}

.apps{
  display:grid;
  grid-template-columns:repeat(4,90px);
  gap:20px;
  margin-top:35px;
}

.app{
  width:90px;
  height:90px;
  border-radius:20px;
  background:#303134;
  display:flex;
  align-items:center;
  justify-content:center;
  flex-direction:column;
  cursor:pointer;
  transition:.3s;
}

.app:hover{
  transform:scale(1.08);
}

.app img{
  width:42px;
  height:42px;
}

.app p{
  margin-top:8px;
  font-size:13px;
}

.news-card{
  width:90%;
  max-width:900px;
  margin:50px auto;
  background:#303134;
  border-radius:20px;
  overflow:hidden;
}

.news-card img{
  width:100%;
  display:block;
}

.note{
  padding:25px;
  text-align:center;
}

.note h2{
  color:#ff4d6d;
  margin-bottom:10px;
}

.note p{
  line-height:1.8;
  color:#ddd;
}

/* ===== Birthday Card ===== */

.birthday-card{
    width:90%;
    max-width:900px;
    margin:40px auto;
    background:#303134;
    border-radius:20px;
    overflow:hidden;
    box-shadow:0 0 20px rgba(255,255,255,.08);
}

.birthday-card img{
    width:100%;
    height:420px;
    object-fit:cover;
}

.birthday-content{
    padding:25px;
    text-align:center;
}

.birthday-content h1{
    color:#ff4d6d;
    font-size:36px;
    margin-bottom:15px;
}

.birthday-content p{
    color:#ddd;
    font-size:18px;
    line-height:1.8;
}

/* Balloon */

.balloon{
    position:fixed;
    top:-120px;
    width:45px;
    animation:fallBalloon linear infinite;
    z-index:999;
}

@keyframes fallBalloon{
0%{
transform:translateY(-120px) rotate(0deg);
}
100%{
transform:translateY(120vh) rotate(360deg);
}
}

/* Cake */

.cake{
    position:fixed;
    top:-100px;
    width:60px;
    animation:fallCake linear infinite;
    z-index:998;
}

@keyframes fallCake{
0%{
transform:translateY(-100px);
}
100%{
transform:translateY(120vh);
}
}

/* Responsive */

@media(max-width:768px){

.logo{
font-size:60px;
}

.apps{
grid-template-columns:repeat(2,90px);
}

.birthday-card img{
height:260px;
}

.birthday-content h1{
font-size:28px;
}

.birthday-content p{
font-size:16px;
}

.search{
