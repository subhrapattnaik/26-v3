The Matter.js library has a function called
Matter.SAT.collides().
This function takes 2 parameters and returns true if there
was collision between the 2 bodies and false if there is no
collision between them.

We’ll declare the collision variable and store the values
we get from the Matter.SAT.collides() function in it.
Now the collision variable will have either true or false as
a value.



We’ll add this code inside the setTimeout() function to
execute the code after 2 seconds; setTimout() function
executes a code after a certain time interval.


Inside the function we’ll use Matter.World.remove() to
remove the boat from the world and use delete method to
delete the boat from the array.

We’ll write the similar remove() function inside the
cannonball class as we also need to remove the
cannonball from the screen.

