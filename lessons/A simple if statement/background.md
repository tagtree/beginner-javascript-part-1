In this exercise we finally get to use the conditional expressions we've been practicing.

Probably the most common code we'll ever write that works with conditional expressions is `if` statements.

An `if` statement starts with the `if` word, like so:


####The start of an `if` statement
    if

Then you stick on the conditional expression that the `if` statement uses to figure out if it should execute:


####The conditional expression
    if(10>1)


The next part is defining the body of the `if` statement. This body is best implemented when a block is provided. To provide the block for the if statement, we start it with an open brace `{` and end it with a close brace `}`.

####The execution block of the `if` statement
    if(10>1){

    }

We then provide the code that we want to execute if the condition is evaluated to `true`.

####The if body
    if(10>1){
        console.log("10 is more than 1");
    }

You might have noticed the `console.log(...)` piece of code. Well we use `console.log` a lot in most JavaScript environments like browsers to output messages we can read. It's a function that you can mostly expect to be available. It's not available in some old browsers, but mostly you can expect it to be there.


