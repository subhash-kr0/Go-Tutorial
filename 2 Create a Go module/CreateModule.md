This is the first part of a tutorial that introduces a few fundamental features of the Go language. if you're just getting started with Go , be sure to take a look at "Tutorial: Get started with Go", which introduces the "go" command, Go modules and very simpe Go code.

In this tutorial you'll create two modules. The first is a library which is intended to be imported by other libraries or applications. The second is caller application which will use the first.

This tutorial's sequence includes seven brief topics that each illustrate a different part of the language.
 
 1. Create a module -- Write a small module with functions you can call from another module.
 2. Call your code from another module -- import and use your new module.
 3. Return and handle an error -- Add simple error handling.
 4. Return a random greeting -- Hnadle data in slices (Go's dynamically-sized arrays).
 5. Return greetings for multiple people -- Store key/value pairs in a map.
 6. Add a test -- Use Go's built-in unit testing features to test your code.
 7. Compile and install the application -- Compile and install your code locally.