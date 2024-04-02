# Tool Learning Log

Tool: Animate Css
---

[https://animate.style/](https://animate.style/)

[https://www.w3schools.com/css/css3_animations.asp](https://www.w3schools.com/css/css3_animations.asp)





<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width">
  <title>JS Bin</title>
</head>
<body>

<div id="grid">
  <div id="left"></div>
  <div id="right"></div>
</div>




</body>
</html>



body {
  margin: 0;
}

#grid {
  height: 100vh;
}

#left {
  background: crimson;
}

#right {
  background: navajowhite;
  border: 4rem solid rgb(0 0 0 / 10%);
}

/* the magic */
#grid {
  transition: 300ms;
  display: grid;
  grid-template-columns: 48px auto;
}

#grid:has(#left:hover) {
  grid-template-columns: 40% auto;
}
/* magic + CSS variable */
#grid {
  transition: 300ms;
  display: grid;
  grid-template-columns: var(--left, 48px) auto;
}

#grid:has(#left:hover) {
  --left: 30%;
}




https://jsbin.com/rixiluxefe/1/edit?html,css,output




<!--
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
