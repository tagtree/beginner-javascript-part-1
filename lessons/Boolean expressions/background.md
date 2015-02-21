Boolean variables are very useful for storing `true/false` values, but often you would want to assign to a boolean or execute conditional logic based on a conditional expression.

To see what we mean by this, have a look at this example. It assigns a boolean variable `isWolfHungry` a value which is a result of evaluating whether the `lastAte` variable has a bigger value than the `yesterday` variable.

In this code, we also introduce the `>` operator. The previous variables we used manipulated the data, whereas the `>` operator is used to evaluate a variable.

####A boolean expression

    var isWolfHungry = lastAte > yesterday;

