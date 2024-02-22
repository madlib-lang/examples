# Collatz Conjecture

Worth watching: https://www.youtube.com/watch?v=094y1Z2wpJg

Starting with any number, if the number is even, multiply it by 3 and add 1 -- if it is odd, divide it by two -- continue following this pattern until you hit 1 (if ever!).

This example demonstrates:

 - composition with `pipe` and `|>`
 - usage of chain (for flattening containers)
 - imported types (Maybe)
 - a recursive pattern for the applied collatz calls
 - the ability to pass in a CLI argument to the main command: `madlib run src/CollatzConjecture.mad 123456`
 - usage of **The Fence** for the default input value (if no arguments are provided to the command)

## How to Run

By default this will generate a random(-ish) value (JS-only)

```
madlib run src/CollatzConjecture/Main.mad
```

### With a starting number

If you want to give a specific input value, you can call the script like so:

```
madlib run src/CollatzConjecture/Main.mad 296781503
```
