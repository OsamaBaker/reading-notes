# Redux - Additional Topics

1. What’s the best practice for “pre-loading” data into the store (on application start) in a Redux application?
> The most 'redux-like' way of handling the pre-loading of data would be to fire off the asynchronous action in the lifecycle method (probably componentWillMount ) of a Higher Order Component that wraps your app.

2. When using a thunk/async action that dispatches the actual action, which do you export from your reducer?
> When the asynchronous task ends, a callback should manage the outcome of the asynchronous task and appropriately update the state with a positive or negative response, support asynchronous actions by modifying their reducers, i.e. making sure that the reducer intercepting that action starts the asynchronous task and manages its outcome

middleware - Middleware functions are functions that have access to the request object (req), the response object (res), and the next middleware function in the application’s request-response cycle. The next middleware function is commonly denoted by a variable named next.

thunk -  is middleware that allows you to return functions, rather than just actions, within Redux. This allows for delayed actions, including working with promises.