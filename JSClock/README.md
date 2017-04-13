#Javascript 2/30 JS Clock

What I learned:

How to use rotate as part of a function in JS

Rotate: 
const secondsDegrees = ((seconds / 60) * 360) + 90;
secondHand.style.transform = `rotate(${secondsDegrees}deg)`;