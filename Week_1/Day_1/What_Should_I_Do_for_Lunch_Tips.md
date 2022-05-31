### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

```javascript
const whatToDoForLunch = function(hungry, availableTime) {
  console.log("I don't know what to do!");
  if (hungry === false) {
    console.log("I'm not hungry right now.");
  }
  if (hungry === true)
    if (availableTime < 20) {
      console.log("Grab a snack, there's not much time.");
    } else if (availableTime >= 20 && availableTime <= 30) {
      console.log("I need a break, I should cook something up.");
    } else if (availableTime > 30) {
      console.log("You should probably reconsider since this is a bootcamp. ");
    }
};
```