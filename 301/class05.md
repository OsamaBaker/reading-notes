How would you break a mock into a component heirarchy?
>The first thing you’ll want to do is to draw boxes around every component (and subcomponent) in the mock and give them all names. If you’re working with a designer, they may have already done this, so go talk to them! Their Photoshop layer names may end up being the names of your React components!

What is the single responsibility principle and how does it apply to components?
>

What does it mean to build a ‘static’ version of your application?
>To build a static version of your app that renders your data model, you’ll want to build components that reuse other components and pass data using props. props are a way of passing data from parent to child. If you’re familiar with the concept of state, don’t use state at all to build this static version. State is reserved only for interactivity, that is, data that changes over time. Since this is a static version of the app, you don’t need it.

Once you have a static application, what do you need to add?
> To build your app correctly, you first need to think of the minimal set of mutable state that your app needs

What are the three questions you can ask to determine if something is state?
> Is it passed in from a parent via props? If so, it probably isn’t state.
> Does it remain unchanged over time? If so, it probably isn’t state.
> Can you compute it based on any other state or props in your component? If so, it isn’t state.


How can you identify where state needs to live?
> Identify every component that renders something based on that state.
Find a common owner component (a single component above all the components that need the state in the hierarchy).
Either the common owner or another component higher up in the hierarchy should own the state.
If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.

>>> Cited from Thinking in React.