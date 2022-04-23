## Javascript Comments

JavaScript comments are hints that a programmer can add to make their code easier to read and understand. They are completely ignored by JavaScript engines.

### There are two ways to add comments to code:

- ```//``` - Single Line Comments
- ``` /* */``` -Multi-line Comments

## Single Line Comments
In JavaScript, any line that starts with // is a single line comment. For example,
```
name = "Jack";

// printing name on the console
console.log("Hello " + name);
Here, // printing name on the console is a comment.
```
You can also use single line comment like this:

```
name = "Jack";

console.log("Hello " + name);  // printing name on the console
```

## Multi-line Comments
In Javascript, any text between ```/* and */``` is a multi-line comment. For example,
```
/* The following program contains the source code for a game called Baghchal. 

Baghchal is a popular board game in Nepal where two players choose either sheep or tiger. It is played on a 5x5 grid.

For the player controlling the tiger to win, they must capture all the sheep. There are altogether 4 tigers on the board.

For the sheep to win, all tigers must be surrounded and cornered so that they cannot move. The player controlling the sheep has 20 sheep at his disposal.
*/
```

Since the rest of the source code will be used to implement the rules of the game, the comment above is a good example where you might use a multi-line comment.

## Using Comments for Debugging

Comments can also be used to disable code to prevent it from being executed. For example,
```
console.log("some code");
console.log("Error code);
console.log("other code");
```
If you get an error while running the program, instead of removing the error-prone code, you can use comments to disable it from being executed; this can be a valuable debugging tool.
```
console.log("some code");
// console.log("Error code);
console.log("other code");
```
> Pro Tip: Remember the shortcut for using comments; it can be really helpful. For most code editors, it's Ctrl + / for Windows and Cmd + / for Mac.

## Make Code Easier to Understand
As a JavaScript developer, you will not only write code but may also have to modify code written by other developers.

If you write comments on your code, it will be easier for you to understand the code in the future. Also, it will be easier for your fellow developers to understand the code.

As a general rule of thumb, use comments to explain why you did something rather than how you did something, and you are good.

> Note: Comments shouldn't be the substitute for a way to explain poorly written code in English. You should always write well-structured and self-explanatory code. And, then use comments.

