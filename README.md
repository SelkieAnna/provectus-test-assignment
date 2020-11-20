# Provectus Internship Test Assignment

## Block 1: Common

1. What are primitives? How can developers use them?

    A primitive is data that is not considered an object. For example, numbers and strings are primitives.
    Developers can use primitives to construct more complex classes and objects, or to validate different object values.

2. What does keyword `this` mean?

    `this` keyword means the context object. It is often `global` or some `function`.

3. What are callbacks?

    Callbacks are functions that are called after specific events, such as another function execution.

4. What is a function declaration and how are its types different?

    A `function declaration` is a construction used to define the function's parameters and contents (functionality).

    Function can be declared by `function declaration`, `function expression` or `arrow function`. `Function declaration` does not create binding to the function variable and allows using the function before its declaration. `Function expression` is usually assigned to a variable which has it's benefits. It can also be used for the object's method declaration or used as a callback. It's shorter than a `function declaration`, but the `arrow function` is even smaller. `Arrow functions` are always anonymous and do not create any execution context.

5. Compare spread and rest operators.

    Spread operator expands an existing iterable object. Rest, on the other hand, allows to represent indefinite number of arguments and does not have anything to do with already existing objects.

[Code exercise solution](https://stackblitz.com/edit/js-block1-bs9p4b?file=task.js)

---

## Block 2: Async

1. JavaScript, is it synchronous or not?

    JavaScript is synchronous.

2. What is the key principle of Call Stack?

    Call stack is a stack of functions calls. When a function is called, it is added to the stack, and when it is finished, it is removed.

3. What does AJAX mean?

    AJAX (Asynchronous JavaScript and XML) is a model that describes how to create web pages that can refresh user interface without refreshing the page.

4. Promise hell. How would you solve it?

    Depend on the case, but probably by removing unnecessary nesting, brackets and returns. I could also use Promise.all and restructure the code using variables for some of the promises.

5. How would you handle exceptions in JS? List two options.

    try...catch

    Promise.catch

6. Which framework would you choose for a new project? Explain why.

    I would choose Angular, because it has high performance, and I need more practice using it.

[Code exercise solution](https://stackblitz.com/edit/js-llr1ac-async-task-eydn53?file=index.ts)

---

## Block 3: TypeScript

1. Is it possible to check types in runtime? If so, how?

    In runtime the types do not exist, but it's possible to check the shape of an object.

2. What is the difference between private and protected fields?

    The difference is that protected class property can be accessed from within deriving classes.

3. How do interfaces help in development?

    Interfaces are useful to check types and create abstractions.

4. How would you pass arguments into a Class?

    Using a constructor that checks argument types.

[Code exercise solution](https://stackblitz.com/edit/typescript-11pw73?file=index.ts)
