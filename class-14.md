# CSS Transforms, Transitions and Animations

## Transforms
* The transform property allows new ways to size, position, and change elements. The transform property comes in two settings, two-dimensional and three dimensional.

* The syntax for the transform property includes the transform property followed by the value.
* Two-dimensional transforms work on both the x and y axes.
* three-dimensional transforms work on the x, y, and z axes

* The **rotate** value provides the ability to rate an element from 0 to 360 degrees.

* The **scale** value within the transform property allows you to change the appeared size of an element.

* The **translate** value works like relative positioning, pushing and pulling the element in different directions without interrupting the normal flow of the document.* The **skew** value is used to distort elements on the horizontal axis, vertical axis, or both. 

## Transitions 
* With CSS3 you have the potential to alter the appearance and behavior of an element whenever a state change occurs, such as when it is hovered over, focused on, active, or targeted. You can do this with **Transitions**.
* In order for a transition to take place, an element must have a change in state and different styles must be identified for each state. `:hover, :focus, :active, and :target` are some pseudo-classes that determine styles for different states.
* There are four transition related properties, including:
  * **transition-property**: determines exactly what properties will be altered in conjunction with the other transitional properties.

  * **transition-duration**: The duration in which a transition takes place. Can be set using general timing values including seconds(s) and (ms)miliseconds. 

  * **transition-timing-function**: This is used to set the speed in which the transition will move. Example key-word values are `ease-in` and `ease-out`.
  * **transition-delay**: This sets a time value, seconds or milliseconds, that determines how long a transition should be stalled before executing. 

## Animations

* To set multiple points at which an element should undergo a transition, use the `@keyframes` rule. The keyframes rule includes the animation name, any animation breakpoints, and the properties intended to be animated.

* To have an animation repeat itself numerous times the `animation-iteration-count` property may be used. These values include either an integer or the **infinite** keyword. 
* To declare the direction an animation completes use the `animation-direction` property. Values for this include **normal, reverse, alternate and alternate-reverse**.
* The `animation-play-state property allows an animation to be played or paued using the **running** and **paused** keyword values respectively. 
* The `animation-fill-mode` property identifies how an element should be styled either before, after, or before and after the animation is run.