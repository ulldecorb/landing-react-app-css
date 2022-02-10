# Animated react app landing
Animated full responsive landing for react app.

## Technologies applied
* HTML
* CSS

## General info
This project is an example of how CSS animation works.
There are 2 elements to study:
### CSS @keyframes Rule
The tool to control the timeline during the animation.   
Within the keyframe we control each style of the element where we declare the animation. To do this we must declare the style we want in each specific time of the animation.

```
@keyframes example {
  from {color: white;}
  to {color: black;}
}
```

Just after declare keyframe rule a reference animationname must be declared.
In the keyframe above we set a color that changes from white, at the start of animation, to black at the end of animation.
But there are more specific ways to control the animation transition:   

```
@keyframes inner-box-circle {
  0% { height: 50vmin;
       width: 50vmin;}
  25% {background-color: darkred;}
  50% {height: 60vmin;
       width: 60vmin;};
  55% {background-color: antiquewhite;}
  100%{height: 50vmin;
       width: 50vmin;}
}
```
The keyframes-selector set percentage of the animation duration. It use 1-100% or/and from-to operators.
I recommend that you follow the [MDN documentation](https://developer.mozilla.org/es/docs/Web/CSS/@keyframes) to learn more about the concepts.   
### CSS Animation property
To get a keyframe works, you must bind the animation to an element. And set what kind of animation you want: 
* animation-name: the reference animationname set on keyframe.   
'''animation-name: inner-box-circle'''
* animation-duration: duration of the animation.   
'''animation-duration: 4s'''
* animation-timing-function: flow of the animation.   
'''animation-timing-function: ease'''
* animation-delay: timer delay to start the animation.   
'''animation-delay: 0s'''
* animation-iteration-count: how many times does the animation repeat before it stops.  
* '''animation-iteration-count: 1'''
* '''animation-direction: normal'''
* '''animation-fill-mode: none'''
* '''animation-play-state: running'''
Again, search on [MDN documentation](https://developer.mozilla.org/es/docs/Web/CSS/animation) for in deep.
## Examples of use
Perfect landing for junior developers who wants learn CSS animation and make fun landings on hers first react apps.

## Sources
This project take the initial animated logo on react apps and incorpore the fantastic examples about CSS animation of [W3schools](https://www.w3schools.com/css/css3_animations.asp).

## Other information
I'm Ausias Bertran, a Full Stack developer from Barcelona in love with CSS. I hope this project encourages and helps other developers try out their own animations.
You can contact me through my [mail](ausias.bertran@gmail.com), [github](https://github.com/ulldecorb) or [linkedin](https://www.linkedin.com/in/ausias-bertran-23137320b/).
