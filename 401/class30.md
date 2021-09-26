# Context API - Behaviors

1. When you have multiple contexts, what component type should you use (class/function) and why?
> Class Components, in class components, the render method will be called, whenever the state of the components changes. On the other hand, the Functional components render the UI based on the props.

2. What are some good use cases for using the Context API for global state?
> Context is primarily used when some data needs to be accessible by many components at different nesting levels.

3. How can you best test context?
> The best way to test Context is to make our tests unaware of its existence and avoiding mocks

context - Context provides a way to pass data through the component tree without having to pass props down manually at every level.

useContext() - Accepts a context object (the value returned from React.createContext) and returns the current context value for that context. The current context value is determined by the value prop of the nearest <MyContext.Provider> above the calling component in the tree.

static context - A static method or, block belongs to the class and these will be loaded into the memory along with the class. You can invoke static methods without creating an object.