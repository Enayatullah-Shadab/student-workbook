## What are the three ways to syntactically write a function? What are the differences in how the function acts (if any)?
1-Anonymous function which dose not have name and we assign it to a variable.
2-Named function which has name and it comes after the function
3-Self invoking function that calls itself inside of a function after the curly bracket.

## What is the difference between Parameters and Arguments?
parameters are parts of definition the function, while arguments are using for the calling of the function.
Or parameters are the placeholder for input that a function should receive it,
 while the arguments are specific value which is giving to run the function.

## What are higher order functions? Can you provide an example?
the parameters are the higher in order because they are placed in the definition or () 
while arguments are placed at the bottom when calling the functions 

function bottleCapper(bottle, cap) // parameters { 
    return bottle + cap;
}
bottleCapper("green bottle","white cap") // arguments