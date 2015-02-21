Ok, so we've defined a function and specified an argument on it.
Although it's very common to have functions that don't return anything, as we've been doing so far, we often want to return data from functions.

To return data from a function, we will use the `return` keyword. Simply speaking, any expression you put after the return statement will be returned from the function.
Later in this course, we'll even return functions from functions!

####Returning a value from a function

    function add(num1, num2){
        return num1 + num2;
    }