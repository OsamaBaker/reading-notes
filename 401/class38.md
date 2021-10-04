# Redux - Asynchronous Actions

1. How granular should your reducers be?
> It’s very easy to go full-warp with very specific events, dedicated for every change that occurs when a user is editing forms such as CHANGE_NAME, CHANGE_STREET, CHANGE_AGE, etc…

But it is not actually necessary if the logic behind the update is not different for all those fields. For those parts which require different handling in various reducers; dedicated action is the best solution. For others, sometimes a general action might be good enough.

2. Pro or Con – multiple reducers can “fire” when a commonly named action is dispatched
> Well, it is a Pro more than a Con since we have to change multiple states in multiple components, the fact that all the reducers can listen when the action is dispatched can reduce a lot of work, each reducer can provide a different logic to the same dispatcher.

3. Name a strategy for preventing the above
> Make a reducer for each component that will be affected by the dispatcher, only effecting a specific amount of the state it self.

store - A store holds the whole state tree of your application. The only way to change the state inside it is to dispatch an action on it.

combined reducers - The combineReducers helper function turns an object whose values are different reducing functions into a single reducing function you can pass to createStore . The resulting reducer calls every child reducer, and gathers their results into a single state object.