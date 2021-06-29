What is a ‘Controlled Component’?

In HTML, form elements such as <input>, <textarea>, and <select> typically maintain their own state and update it based on user input. In React, mutable state is typically kept in the state property of components, and only updated with setState().

Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

No, because it runs as the user hits keystrokes.

How do we target what the user is entering if we have an event handler on an input field?
In HTML, an <input type="file"> lets the user choose one or more files from their device storage to be uploaded to a server or manipulated by JavaScript via the File API.

Why would we use a ternary operator?
It's shorter way.

  if(x===y){
 console.log(true);
  } else {
 console.log(false);
  }

  > x === y ? true : false