Functions are the building blocks of JavaScript, so it's very important to understand how they work.


A function consists of 4 parts:

1. The function keyword
2. The function name (optional)
3. The argument list
4. The body of the function.


Let's take a look at each part and then put them together.

The `function` keyword is what tells JavaScript that you want to declare a function.

####The function keyword

    function

The name is used when you want to call (execute) the function later on.

####Specifying the function name

    function sayHello

Arguments are used to pass data to the function, something that's unique to the specific execution call of the function. In this scenario, we want our function to say hello to a particular person, using the person's name, for that we add a `name` argument.

####Adding an argument list

    function sayHello(name)

This is where we tell the function what it's supposed to do. Don't worry about what it does at the moment. The important  part to notice is that it is wrapped in what I like to call squiggly braces `{}`.

In this scenario, we `log` a message to the `console`. You will have `console.log` available in most browsers and JavaScript environments. This is where you can output messages to and view them. We also combine the string `hello` with our `name` argument passed to the function. We'll do a bit more with strings later on.

####Creating the function body

    function sayHello(name){
        console.log('hello ' + name);
    }

And that's a function!
