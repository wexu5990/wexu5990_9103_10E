# wexu5990_9103_10E
## Final project
Hello! This is George. 
In my approach of the individual work, I am doing the part of employing timers and events for animation.
The animation starts automatically without mouseclicking or refreshing
### Inspiration
My work is inspired from the create function via the link [Link Text] (https://happycoding.io/tutorials/p5js/creating-functions), showing the appearance of circles. 
I'm also inspired form [Link Text] (https://developer.mozilla.org/en-US/docs/Web/API/setInterval), showing how to use functions to update figures. 

#### Individual changes
1. To enhance drawApples() function with animation using timers and events, I add setTimeout() into the function to animate the drawing of apples at different times, creating a sequence effect. 
2. I also add the animateBranches() by using setInterval() function to incrementally update the growthFactor and calls redraw() to refresh the drawing. This makes the branches appear to grow over time.
3. As time passed, the colour of the apples and the ellipse on the bottom change with the growing of branches and random appearance of apples, until the branches grow completely. 