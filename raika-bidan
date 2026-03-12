<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Bidan ❤️ Raika</title>

<style>

body{
margin:0;
padding:0;
font-family: 'Segoe UI', sans-serif;
background: linear-gradient(135deg,#ff4e50,#fc913a,#ff6a88,#ff99ac);
background-size:400% 400%;
animation:bgmove 12s infinite alternate;
overflow-x:hidden;
color:white;
text-align:center;
}

@keyframes bgmove{
0%{background-position:0% 50%}
100%{background-position:100% 50%}
}

.title{
font-size:70px;
margin-top:100px;
font-weight:bold;
text-shadow:0 0 10px #fff,0 0 20px #ff3e6c,0 0 40px #ff3e6c;
animation:glow 2s infinite alternate;
}

@keyframes glow{
from{ text-shadow:0 0 10px #fff,0 0 20px #ff2d55;}
to{ text-shadow:0 0 20px #fff,0 0 40px #ff2d55;}
}

.subtitle{
font-size:30px;
margin-top:20px;
opacity:.9;
}

.section{
margin-top:80px;
padding:20px;
}

.card{
width:300px;
margin:20px auto;
padding:25px;
border-radius:20px;
background:rgba(255,255,255,0.15);
backdrop-filter:blur(10px);
box-shadow:0 10px 30px rgba(0,0,0,0.3);
transition:.4s;
}

.card:hover{
transform:scale(1.05);
box-shadow:0 15px 40px rgba(0,0,0,0.4);
}

.card h2{
margin-bottom:10px;
}

.heart{
position:fixed;
top:-10px;
color:#ff003c;
animation:fall linear infinite;
}

@keyframes fall{
0%{transform:translateY(-10px)}
100%{transform:translateY(110vh)}
}

button{
padding:15px 35px;
font-size:18px;
border:none;
border-radius:30px;
background:#ff2d55;
color:white;
cursor:pointer;
transition:.3s;
box-shadow:0 5px 15px rgba(0,0,0,.3);
}

button:hover{
transform:scale(1.1);
background:#ff0044;
}

footer{
margin-top:120px;
padding:30px;
font-size:18px;
opacity:.8;
}

</style>
</head>

<body>

<h1 class="title">Bidan ❤️ Raika</h1>
<p class="subtitle">A Beautiful Love Story</p>

<div class="section">

<div class="card">
<h2>❤️ Love Message</h2>
<p>
Bidan loves Raika more than words can explain.  
This page is dedicated to a beautiful love story.
</p>
</div>

<div class="card">
<h2>🌹 Forever Promise</h2>
<p>
No matter what happens,  
love always finds a way.  
Bidan & Raika forever.
</p>
</div>

<div class="card">
<h2>✨ Special Memory</h2>
<p>
Every moment together becomes  
a memory that lasts forever.
</p>
</div>

<button onclick="showLove()">Click For Love Message</button>

<p id="loveText" style="font-size:25px;margin-top:20px;"></p>

</div>

<footer>
Made with ❤️ for Bidan & Raika
</footer>

<script>

function showLove(){
document.getElementById("loveText").innerHTML=
"💖 Bidan Loves Raika Forever 💖";
}

function createHeart(){
const heart=document.createElement("div");
heart.classList.add("heart");
heart.innerHTML="❤";

heart.style.left=Math.random()*100+"vw";
heart.style.fontSize=(Math.random()*20+15)+"px";
heart.style.animationDuration=(Math.random()*3+3)+"s";

document.body.appendChild(heart);

setTimeout(()=>{
heart.remove();
},6000);
}

setInterval(createHeart,300);

</script>

</body>
</html>
