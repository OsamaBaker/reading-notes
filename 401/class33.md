# <Login /> and <Auth />

1. Why is the Context API useful?
> It enables you to exchange unique details and assists in solving prop-drilling from all levels of your application.

2. Can a component outside of a provider get its context?
> The most common way to access Context from a class component is via the static contextType.

3. What are some common use cases for using the Context API?
> Some sample use cases where the Context API proves helpful are: Theming — Pass down app theme. Pass down translation messages. Authentication — Pass down current authenticated user.

4. Describe “Context Hell”
> The React Context hell is the nasty code you get taking advantage of the React Context API.

global state - global state is the data that is shared between all the components within a React application.

global context - Global Context is designed to share data that can be considered “global” for a tree of React components.

provider -  The <Provider> component makes the Redux store available to any nested components that need to access the Redux store.

consumer - A React component that subscribes to context changes.