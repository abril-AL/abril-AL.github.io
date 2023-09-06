# CSS Notes

## CSS Animations

Intro: CSS animations allow us to change elements gradually from style to another. Fist must specify some keyframes to hold what styles the element will have at certain times

### The @keyframes Rule
- When you specify CSS styles inside the @keyframes rule, the animation will gradually change from the current style to the new style at certain times.
- To get an animation to work, you must bind the animation to an element.
Example
```html
/* The animation code */
@keyframes example {
  from {background-color: red;}
  to {background-color: yellow;}
}

/* The element to apply the animation to */
div {
  width: 100px;
  height: 100px;
  background-color: red;
  animation-name: example;
  animation-duration: 4s;
}
```