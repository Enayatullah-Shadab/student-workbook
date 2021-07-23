## What problems does the Observer Pattern seek to solve?
Allow us subscribe to an event while certain event occurs let us to trigger a series of functions and methods

## What are the three mechanisms of the observer pattern?
on (event, fn){...}
off (event, fn){...}
notify (event, fn){...}

## Review the code generated from the bcw-template and reflect on the proxy objects from yesterday, and your understanding of the observer pattern today. With this knowledge, explain how the magic of the bcw-template uses these two concepts to manage and update the dom.
The observer pattern is used to listen to a particular types of event and doing something.

https://github.com/Enayatullah-Shadab/Zoo-keeper