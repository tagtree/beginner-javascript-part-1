Now we know how to define functions, let's use them!
Calling (executing) a function in JavaScript is simple.

This is an example of calling the function which we defined in the previous task. You might notice that we are assigning the result of the function call to a variable called `value`.

We looked at assigning values to variables earlier, and this is very similar to that.
Instead of doing a simple assignment, we are saying that JavaScript should call the function, take the return value and assign it to the variable.

####Calling a function

    function multiply(num1, num2){
        return num1 * num2;
    }

    //here we call the function
    var value = multiply(10, 10);
