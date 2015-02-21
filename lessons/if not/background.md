Sometimes we want to execute code if something is not `true`.
In this case we use the negation operator `!`. You can put the `!` operator in front of any conditional expression or boolean variable and it will turn it into the opposite boolean value. So if the value was `false`, it wil turn it to `true`. And if it was `true`, then... well... it will turn it to `false`.

In this code we've got a boolean variable of `true`. Let's change it to false by using the `!` operator.
####The `!` operator at work
    var nourished = false;
    if(!nourished){
        console.log('eating something');
    }
