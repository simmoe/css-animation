# css-animation
Pure CSS transitions and animations course 

## Follow links to watch demos


- <a href="https://simmoe.github.io/css-animation/01-basic-transition-transform">Introduction to transitions</a>
- <a href="https://simmoe.github.io/css-animation/02-basic-keyframe-animation">Keyframe animation intro</a>
- <a href="https://simmoe.github.io/css-animation/03-basic-letter-animation">CSS typewriter animation</a>
- <a href="https://simmoe.github.io/css-animation/04-animated-sections/">Full page hover transitions</a>
- <a href="https://simmoe.github.io/css-animation/05-animated-form-elements/">XD style form transitions</a>

---

CSS animation has become much more fun than in the old days. Browsers are catching up on standards, and transitions can actuallly be made estethic and subtle. In this repo you'll find a set of introductory exercises and techniques to get you started. The material was developed with high school level A informatics students in mind.

## Getting started with css animation
The first thing you need to know, is how to make a transition - an effect that takes place when the css values of en HTML element changes. 

Say, we want to change the background color of a button when the cursor hovers over it:

```css 
button {
   background-color:#1592E6;
   transition: .6s ease;
}

button:hover {
    background-color:#4EB8FF;
}
````

There´s a lot going on here, so lets break it down. First we give the button a background color, but what is the tranistion thing? The transition property means we want *any* change on the element, to morph over some time. *.6s* means the transition should take 0.6 seconds. The *ease* property means the effect will use an easing function in order for the morphing to look more smooth. Always use that property. 

Next, we give the button another background color on hover - paste the css into your HTML and watch the transition betwween the two background colors. Nice.

The repo is organised from easy to slightly more advanced. In a set of exercises, I give my try on reproducing some standard Adobe XD transitions, that students are generally interested in learning.  
