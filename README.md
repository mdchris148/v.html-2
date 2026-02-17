<html lang="en">
<head>
<meta charset="UTF-8">
<title> Bazina my love  </title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
body {
font-family: Arial, sans-serif;
background: linear-gradient(135deg, #ff4d6d, #ff758f);
height: 100vh;
display: flex;
justify-content: center;
align-items: center;
margin: 0;
color: white;
text-align: center;
}
.card {
background: rgba(0,0,0,0.2);
box-shadow: 0 10px 30px rgba(0,0,0,0.3);
padding: 30px;
border-radius: 20px;
max-width: 320px;
}
h1 {
font-size: 26px;
margin-bottom: 10px;
}
p {
font-size: 16px;
margin-bottom: 25px;
}
button {
font-size: 16px;
padding: 10px 20px;
border: none;
border-radius: 30px;
cursor: pointer;
margin: 10px;
}
#yes {
background: #2ecc71;
color: white;
}
#no {
background: #e74c3c;
color: white;
position: absolute;
}
</style>
</head>
<body>
<div class="card">
<h1>Bazina sweetheart </h1>
<p>
wampaye kumafaranga😂?<br>
</p>
<button id="yes" onclick="sayYes()">Yes</button>
<button id="no" onmouseover="moveNo()">No</button>
</div>
<script>
function sayYes() {
document.body.innerHTML = `
<div style="
height:100vh;
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
background:linear-gradient(135deg, #ff4d6d,#ff758f);
color:white;
font-family:Arial;
text-align:center;">
<h1>nukoo nukoo </h1>
<p>Thanks for accepting it without force😂
knd i really love you !</p>
</div>`;
}
function moveNo() {
const button = document.getElementById("no");
const x = Math.random() * (window.innerWidth - 100);
const y = Math.random() * (window.innerHeight - 50);
button.style.left = x + "px";
button.style.top = y + "px";
}
</script>
</body>
</html>
