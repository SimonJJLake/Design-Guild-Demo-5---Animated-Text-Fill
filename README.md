# Design Guild Demo 5 - Animated Text Fill
<img width="1511" alt="image" src="https://user-images.githubusercontent.com/113339746/228310569-4943b240-6d7d-4567-9939-5073ea252e67.png">
A quick demonstration of text being filled in from left to right when the cursor hovers over it, demonstrated on https://weareadaptable.com/
<img width="1511" alt="image" src="https://user-images.githubusercontent.com/113339746/228311716-0c37d7c9-81f2-45d5-a409-1f96f37c77ff.png">

The demo uses a gradient background on the text component, with a background;s width being twice the size of the component. 

The gradient has a sharp transition from black to transparent halfway. 

The initial background position is -50% of the width of the background, so only the transparent part of the gradient is visible.

When the user hovers on the component, the background position transitions to 0%, so only the black part of the gradient is visible.
