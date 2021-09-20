# Component Lifecycle / useEffect() Hook

1. Why do we not need more .html pages in a multi-page React app?
> Because React app is a single-app page which renders each HTML on its own.

2. What does routing do with the components that were rendered when a new route is requested
> A callback is called, which will set the state to the new component.

3. What does props.children contain?
> props. children does is that it is used to display whatever you include between the opening and closing tags when invoking a component. 

4. How do useState() and this.setState() differ?
> Unlike the setState method found in class components, useState does not automatically merge update objects.

State Hook - The useState hook is a special function that takes the initial state as an argument and returns an array of two entries

Mounting and Un-Mounting - A React component's lifecycle contains distinct phases for creation and deletion.