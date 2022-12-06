# Class 7 Notes - Object-Oriented Programming, HTML Tables

## Domain Modeling

[Domain Modeling](https://github.com/codefellows/domain_modeling#domain-modeling)

- Q: Explain why we need domain modeling.
  
  - A: The purpose of domain modeling is to produce a reusable structure. Domain modeling generates a model into which we can plug specific data without re-creating an entire coding framework from scratch. This is comparable to the creation and reuse of a function in code.

### HTML Table Basics

[HTML Table Basics](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Basics)

- Q: Why should tables not be used for page layouts?

  - A:
    - Not a tool for layouts
    - If used as layout instead of for data, they reduce accessibility for screen readers
    - Unresponsive

***HTML tables should be used for tabular data — this is what they are designed for***

- Q: List and describe three different semantic HTML elements used in an HTML `table`.

  - A:
    - You have to start your table with `table`.
    - To begin a new row, use `tr`
    - Under `tr`, each `td` is an individual cell.

```HTML
        <table>
        <tr>  
          <td>Table Cell</td>
          <td>Table Cell</td>
          <td>Table Cell</td>
        </tr>
      </table>

```

### Intro to Constructors

[Introducing Constructors](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics#introducing_constructors)

- Q: What is a constructor, and what are some advantages of using it?

  - A:
    - A constructor is a framework for an object. It allows us to make one set of code that can be used with as many objects as we want without having to write lines of code to make an object literal each time.

    - Drastically saves time and chances of errors in code.

- Q: How does the term `this` differ when used in an object literal versus when used in a constructor?
  
  - A: When calling a constructor, bind `this` to the new object so you can refer to `this` in your constructor code

### Object Prototypes Using A Constructor

[Object Prototypes Using A Constructor](https://ui.dev/beginners-guide-to-javascript-prototype)

- Q: Explain prototypes and inheritance via an analogy from your previous work experience.

  - A: A prototype is a property that references an object.Each object has a private property that holds a link to another object called its prototype

  ***NEED TO WORK ON PROTOTYPES MORE***

[HTML Table Advanced Features and Accessibility](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Advanced)

#### Things I want to know more about

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
