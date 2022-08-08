## CSS ANIMATIONS - A Simple yet Beautiful way to make your websites look better

#What are CSS ANIMATIONS?
CSS animations, its something that doesn’t come to mind first but is surely an underrated art that truly is beautiful and interesting. It basically means animating transitions from one CSS style configuration to another.
Animations consist of two components, a style describing the CSS animation and a set of keyframes that indicate the start and end states of the animation's style, as well as possible intermediate waypoints. To style a CSS animation sequence, we use the animation property or its sub-properties. This lets you configure the timing, duration, and other details of how the animation sequence should progress. This does not configure the actual appearance of the animation, which is done using the @keyframes at-rule. In simple words; styling answers how and keyframes answer when. Keyframes use a <percentage> to indicate the time during the animation sequence at which they take place
So for example,
 

 
Glimpse into the Common animation properties
animation-name
Specifies the name of the @keyframes at-rule describing the animation's keyframes or the effects it brings about on the object

animation-duration 
Specifies the length of time that the animation will be taking to complete one animation cycle.

animation-delay
introduces a  delay between the time an element is loaded and the beginning of its animation sequence.

animation-iteration-count
Configures the number of times the animation should repeat; you can specify infinite to repeat the animation indefinitely.

animation-direction
Configures whether or not the animation should alternate direction on each run through the sequence or reset to the start point and repeat itself.

animation-play-state
Lets you pause and resume the animation sequence.

