# Class 09 Reading Notes

[Functional Programming Concepts](https://medium.com/the-renaissance-developer/concepts-of-functional-programming-in-javascript-6bc84220d2aa)

## Discussion Questions

- Q: What is functional programming?

  - A: Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data — ^[Wikipedia](https://en.wikipedia.org/wiki/Functional_programming)

- Q: What is a pure function and how do we know if something is a pure function?

  - A:

    - It returns the same result if given the same arguments (it is also referred as deterministic)
    - It does not cause any observable side effects

- Q: What are the benefits of a pure function?

  - A: The code’s definitely easier to test.

- Q: What is immutability?

  - A: When data is immutable, its state cannot change after it’s created. If you want to change an immutable object, you can’t. Instead, you create a new object with the new value.

- Q: What is Referential transparency?

  - A: pure functions + immutable data = referential transparency

  Passing 2 as a parameter of the square function will always returns 4. So now we can replace the square(2) with 4. That's it! Our function is referentially transparent.

[Node JS Tutorial for Beginners #6 - Modules and require()](https://www.youtube.com/watch?v=xHLd36QoS4k)

## Discussion Questions

- Q: What is a module?

  - A: Module in Node.js is a simple or complex functionality organized in single or multiple JavaScript files which can be reused throughout the Node.js application.

- Q: What does the word ‘require’ do?

  - A: `require` keyword refers to a function which is used to import all the constructs exported using the module.exports object from another module.

- Q: How do we bring another module into the file the we are working in?

  - A: Go into the module you want available outside of that module and module.export, which allows the module to be used outside. After that, you would go into the file you want to use and use the keyword required to import that module.

- Q: What do we have to do to make a module available?

  - A: Module keyword refers to the object representing the current module. The module object has a key named exports. module.exports is another object which is used for defining what can be exported by a module and can be made available to other modules. In short, if a module wants to export something, it should be added to the module.exports object.

## Things I want to know more about

HOOKS!
