#const NAME = "RASHI";
document.addEventListener("DOMContentLoaded", () => {
  document.querySelectorAll(".name").forEach(el => {
    el.innerText = NAME;
  });
});
<span class="name"></span>
<h1>🎉 Happy Birthday <span class="name"></span> 🎉</h1>
https://cdn.pixabay.com/audio/2022/10/30/audio_2c8c0c1c5f.mp3
<audio autoplay loop>
  <source src="https://cdn.pixabay.com/audio/2022/10/30/audio_2c8c0c1c5f.mp3" type="audio/mpeg">
</audio>
page6.html  (Fake Exit Trap)
page7.html  (Anger Button That Escapes)
page8.html  (Romantic Confession)
<!DOCTYPE html>
<html>
<head>
<title>Bye 😏</title>
<link rel="stylesheet" href="style.css">
<script src="script.js"></script>
</head>
<body class="center bg4">

<h1>Oh okay <span class="name"></span> 😒</h1>
<p class="fun-text">You wanna leave already? Wow. Fake fan.</p>

<button onclick="go('page7.html')" class="cute-btn">
YES LEAVE 🚪
</button>

<button onclick="alert('Button disabled for drama 😌')" class="rage-btn">
NO STAY 🥺
</button>

</body>
</html>
<!DOCTYPE html>
<html>
<head>
<title>Catch It 😈</title>
<link rel="stylesheet" href="style.css">
<script src="script.js"></script>
<style>
#runaway {
  position: absolute;
}
</style>
</head>
<body class="center bg2">

<h1>Click the button <span class="name"></span> 😏</h1>
<p class="small">If you can.</p>

<button id="runaway" class="rage-btn">CLICK ME 😡</button>

<script>
const btn = document.getElementById("runaway");
btn.addEventListener("mouseover", () => {
  btn.style.left = Math.random()*80 + "%";
  btn.style.top = Math.random()*80 + "%";
});
btn.addEventListener("click", () => go("page8.html"));
</script>

</body>
</html>
<!DOCTYPE html>
<html>
<head>
<title>For RASHI 💖</title>
<link rel="stylesheet" href="style.css">
<script src="script.js"></script>
</head>
<body class="center bg5" onclick="confetti()">

<h1 class="glow">💖 RASHI 💖</h1>
<p class="fun-text">
Behind all the jokes and teasing…  
You are genuinely special 🌸  
Your smile, your vibe, your chaos — all perfect ✨  
I hope this birthday makes you feel loved 💕
</p>

<button onclick="go('page5.html')" class="cute-btn">
One Last Boom 🎉
</button>

</body>
</html>
setInterval(() => {
  let heart = document.createElement("div");
  heart.innerHTML = "💖";
  heart.style.position = "fixed";
  heart.style.left = Math.random() * 100 + "%";
  heart.style.top = "-5px";
  heart.style.fontSize = "20px";
  heart.style.animation = "fall 3s linear";
  document.body.appendChild(heart);
  setTimeout(() => heart.remove(), 3000);
}, 700);
