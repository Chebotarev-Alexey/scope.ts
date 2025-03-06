# Scope.ts

**Scope.ts** is an experimental framework designed to enhance typescript type safety, improve code reliability and eliminate the need for JavaScript garbage collection. It originates from the concept of a next-generation programming language and serves as a proof of concept for its core ideas.


## Overview of Features

1. All variables, whether global or local, are accessed through a `Scope` object, which is denoted as `$` by default. Alternative names can be used in case of naming conflicts.
2. Every function must be an arrow function wrapped in `$.foo()`, accepting a single argument of a `Scope` subtype.
3. To execute a function, it must be accessible in the current scope and invoked as `$.functionName(options)`. The `options` parameter fully determines how the subscope for the function is created.
4. Most standard language constructs, such as `if`, `for` and `while`, are not allowed and must be replaced with their `scope.ts` equivalents.


__More details coming soon.__