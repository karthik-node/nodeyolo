
Promises using Bluebird library ,to avoid pyramid of doom (nested callback hell)

$node promise.js  --------------> Chaining (.then) promises.
$node promise1.js --------------> CATCH HANDLER WILL CATCH REJECTION.
$node promise2.js --------------> ERROR HANDLER WILL CATCH REJECTION.
$node promise3.js --------------> Promise.reject will allow the error handler to work correctly.