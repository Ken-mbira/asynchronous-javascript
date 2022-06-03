# ASYNC JAVASCRIPT

## Callbacks
Pass a function as a parameter, then set the function to wait for something else to happen then the passed in function is called.

## Promises
These are sort of like agreements where you agree to do something once something is done. You can however do something else once it fails to complete. A promise returns an instance of a promise with the parameters resolve and reject and you can define what happens when it happens as expected (resolve) and when it doesn't (reject). At the end you can use then when it resolves, catch when it fails and finally to happen regardless of what happened.

## Async Await
These are the simplified way of doing all this... all you need to do is add the async key or word before the name of the function when definig it then add await to the functions within this. This will pause at the await function till it completes and only then will it move over to the next line. It helps keep things in order especially if they depend on each other.