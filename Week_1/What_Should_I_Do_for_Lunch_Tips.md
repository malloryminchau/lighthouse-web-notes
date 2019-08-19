### Tips

Try experimenting with the comparison operators (`<`, `>`, `===`, etc.) in the node REPL, which you can launch using the `node` command in Vagrant.

Work on your code iteratively – that means in small pieces. 

To help you figure out how to use `hungry` and `availableTime` inside your function, try outputting their values to the Terminal as follows.

```javascript
const whatToDoForLunch = function(hungry, availableTime) {
  if (hungry === true) {
    if (availableTime < 20) {
      console.log("Pick something up and eat it back in the Lab or the kitchen, where you can get to know your fellow classmates.");
    } else if ((availableTime >= 20) && (availableTime <= 30)) {
      console.log("You deserve a break. You could try a place in Gastown.");
    } else if (availableTime > 30) {
      console.log("This is a bootcamp after all, maybe you should reconsider.");
    }
  } else if (hungry === false) {
    console.log("You should wait to eat until you are hungry");
  }
  //console.log("I don't know what to do!");
};
```