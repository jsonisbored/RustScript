# JScript
Building a language while learning at the same time. JScript transpiles to JavaScript.

## Goals
- Address pain points in JavaScript
- Use features that JavaScript will never have
- Maintain JavaScript ecosystem interop

## Progress
1. Parsing, checking, and generating
    - ✓ | Basic expressions
    - ✓ | Let, fn, assign statements
    - ✓ | Arrays with destructuring
    - ✗ | Syntax for ranges
    - ✗ | Control flow
    - ✗ | Structs
    - ✗ | Enums
    - ✗ | Impl statements
    - ✗ | Pattern matching
2. ✗ | Parser rewrite
3. ✗ | Good error messages
4. ✗ | Decide on a macro system
5. ✗ | Decide on a macro system
6. ✗ | Lowering and optimizations
7. ✗ | Figure out CLI, standard library, & package manager details

## Example
Code will look a lot like rust with a garbage collector.
```rus
fn fib(n: num): num {
    match n {
        0 => 1,
        1 => 1,
        _ => fib(n-1) + fib(n-2),
    }
}
```