# Class 06 Reading Notes

## Learn JS

### Important JS Links

[JavaScript Object Basics](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics)
[Introduction To The DOM](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction)

### JS Questions

- Q: How would you describe an object to a non-technical friend you grew up with?
  
  - A: An object is a standalone entity with properties and methods. For example, a coffee mug has different properties, such as color: white and material: ceramic. There is also methods. For example, the coffee cup auto heats to the perfect temp.

- Q: What are some advantages of creating object literals?

  - A: Object literals provide flexibility in devlaration and use less code.
  - Freedom of having private functions only used by your module

- Q: How do objects differ from arrays?
  - Objects map strings to values
  - Arrays map numbers to values

- Q: Give an example of when you would need to use bracket notation to access an object’s property instead of dot notation.

  - A: If an object property name is held in a variable, then you can't use dot notation to access the value, but you can access the value using bracket notation

- Q: Evaluate the code below. What does the term `this` refer to, and what is the advantage of using this?

  - A: DOG

``` JS

const dog = {
  name: 'Spot',
  age: 2,
  color: 'white with black spots',
  humanAge: function (){
    console.log(`${this.name} is ${this.age*7} in human years`);
  }
}

```

- A:

### Introduction to the DOM

- Q: What is the DOM?

  - A: The Document Object Model (DOM) is an interface for web document programming. It depicts the page so programs can modify the document's structure, style, and content. So that computer languages may interact with the page, the Document Object Model (DOM) represents the document as nodes and objects.

- Q: Briefly describe the relationship between the DOM and JavaScript.

  - A: The DOM is not part of the JavaScript language but is a Web API used to build websites.
  - The DOM is not a programming language; without it, JavaScript wouldn't have the notion of websites.

## Things I want to know more about

## Code 201

- [Class 01 Reading Notes](/code201/class-01.md)
- [Class 02 Reading Notes](/code201/class-02.md)
- [Class 03 Reading Notes](/code201/class-03.md)
- [Class 4 Reading Notes](/code201/class-04.md)
- [Class 5 Reading Notes](/code201/class-05.md)
- [Class 6 Reading Notes](/code201/class-06.md)
- [Class 7 Reading Notes](/code201/class-07.md)
- [Class 8 Reading Notes](/code201/class-08.md)
- [Class 9 Reading Notes](/code201/class-09.md)
- [Class 10 Reading Notes](/code201/class-10.md)
- [Class 11 Reading Notes](/code201/class-11.md)
- [Class 12 Reading Notes](/code201/class-12.md)
- [Class 13 Reading Notes](/code201/class-13.md)
- [Class 14 Reading Notes](/code201/class-14.md)
- [Class 15 Reading Notes](/code201/class-14.md)
