# What are the three states of a Promise?

Pending state: initial state, neither fulfilled nor rejected 
Fulfilled: meaning that the operation was completed successfully 
Rejected: meaning that the operation failed

# How do promises seek to resolve the issues of "callback hell"?
Insted of returning nothing in your function and accepting callback as parameter the promise can help us to wrap the entire content in promise a promise declaration and resolve/rejected.

# What is the difference between .then() and .catch()?
the different between .then() and .catch() methds are in return of the result from asynchronous operation, .then() return promise and takes two arguments callback function for the succes and failure.

https://github.com/Enayatullah-Shadab/Car-gregslist.git