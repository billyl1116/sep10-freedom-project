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

**Basic Animations:**

Fade In / Out
Slide In / Out
Bounce In / Out
Rotate In / Out
Zoom In / Out
Flip In / Out
Roll In / Out
And more...

**Attention Seekers:**

Bounce
Flash
Pulse
Shake
Head Shake
Tada
Jello
And more...


**Special Effects:**

Hinge
Jack in the Box
Roll Out
Rubber Band
Swing
And more...

**Entrances and Exits:**

Fade In Down / Up / Left / Right
Slide In Down / Up / Left / Right
Zoom In Down / Up / Left / Right
Flip In X / Y
Rotate In Down Left / Down Right / Up Left / Up Right
And more...

**Duration and Delay:**

Control animation duration with animate__slow and animate__fast classes.
Add delay to animations using animate__delay-{time} class



**Jsbin link**

https://jsbin.com/rixiluxefe/1/edit?html,css,output
