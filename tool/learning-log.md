

Tool: Animate Css

<<<<<<< HEAD
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
=======
<--
>>>>>>> ed1088e4ccf3fac8c8b6f6d4eacc4cc622b7a5f9
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->

https://www.youtube.com/watch?v=S2KCXKAView

https://animate.style/

**Include the Library**: Start by including the Animate.css library in your HTML file. You can either download the library and link to it locally or use a content delivery network (CDN) link.

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css">

```<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css">```
**Apply Classes:** Animate.css provides a variety of animation classes that you can apply to elements you want to animate. These classes define different animations, such as fade-in, slide-in, bounce, etc.


```<div class="animate__animated animate__bounce">Animated Content</div>```
<div class="animate__animated animate__bounce">Animated Content</div>

**Animation Options**: Animate.css offers customization options by combining different classes or modifying the animation duration and delay using inline styles or CSS.


```<div class="animate__animated animate__bounce animate__delay-2s" style="animation-duration: 3s;">Customized Animation</div>```
<div class="animate__animated animate__bounce animate__delay-2s" style="animation-duration: 3s;">Customized Animation</div>


---





While the library offers a couple of helper classes, such as the animated class, to get you started, you can use the animations keyframes directly from the library. This gives you the flexibility of using Animate.js with your existing projects, without having to rewrite your HTML code.

Example:

```css .my-element {
  display: inline-block;
  margin: 0 0.5rem;

  animation: bounce; /* referring directly to the animation's @keyframe declaration */
  animation-duration: 2s; /* don't forget to set a duration! */
}
```
)https://www.youtube.com/watch?v=S2KCXKAView

https://animate.style/

**Include the Library**: Start by including the Animate.css library in your HTML file. You can either download the library and link to it locally or use a content delivery network (CDN) link.

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css">

```<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css">```
**Apply Classes:** Animate.css provides a variety of animation classes that you can apply to elements you want to animate. These classes define different animations, such as fade-in, slide-in, bounce, etc.


```<div class="animate__animated animate__bounce">Animated Content</div>```
<div class="animate__animated animate__bounce">Animated Content</div>

**Animation Options**: Animate.css offers customization options by combining different classes or modifying the animation duration and delay using inline styles or CSS.


```<div class="animate__animated animate__bounce animate__delay-2s" style="animation-duration: 3s;">Customized Animation</div>```
<div class="animate__animated animate__bounce animate__delay-2s" style="animation-duration: 3s;">Customized Animation</div>


---





While the library offers a couple of helper classes, such as the animated class, to get you started, you can use the animations keyframes directly from the library. This gives you the flexibility of using Animate.js with your existing projects, without having to rewrite your HTML code.

Example:

```css .my-element {
  display: inline-block;
  margin: 0 0.5rem;

  animation: bounce; /* referring directly to the animation's @keyframe declaration */
  animation-duration: 2s; /* don't forget to set a duration! */
}
```
