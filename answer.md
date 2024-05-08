
Distinguishing localStorage from sessionStorage, localStorage retains data even after the page is closed or refreshed, while sessionStorage clears its data once the page session ends, which occurs when the tab is closed. Each tab creates a unique page session.

Global and local scopes are fundamental in JavaScript. Global variables can be accessed from anywhere in the code and are typically declared at the top level. Local variables, on the other hand, are confined within the function where they are defined, including function parameters.

The JavaScript event loop manages asynchronous operations, allowing single-threaded execution while providing the illusion of multi-threading. Operations are tracked in a call stack, with functions being popped when finished.

There are several ways to obtain undefined in JavaScript:

A variable that hasn't been initialized.
A function without a return statement.
An undefined parameter.
A return statement with nothing to return.
Accessing a non-existent property of an object.
Accessing array elements outside of the defined index range.
Deleting an element from an array.
Assigning a value directly to undefined.