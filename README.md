# Madlib Examples

A listing of common software problems solved with Madlib

### Notes on Madlib

[Madlib](https://madlib.space) is a general purpose programming language that compiles to Javascript. If you prefer learning via video, maybe [this talk](https://www.youtube.com/watch?v=441RqxnjVac) may be informative.



### How to run it

First, you need to compile the program.

*For node*:
```shell
madlib compile -i src/Main.mad
```

Then, you can run it like this:
```shell
node build/Main.mjs
```

*As a native binary*:

```shell
madlib compile --target llvm -i src/Main.mad -o ./build/helloWorld
```
Then, you can run it like this:

```shell
./build/helloWorld
```
