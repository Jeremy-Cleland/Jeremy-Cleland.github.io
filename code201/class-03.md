# Class 03 Reading Notes

- [Class 03 Reading Notes](#class-03-reading-notes)
  - [Reflection](#reflection)
  - [Learn HTML](#learn-html)
    - [Important HTML Links](#important-html-links)
      - [HTML Questions](#html-questions)
  - [Learn CSS](#learn-css)
    - [Important CSS Links](#important-css-links)
    - [CSS Questions](#css-questions)
  - [Learn JS](#learn-js)
    - [Important JS Links](#important-js-links)
    - [JS Questions](#js-questions)
  - [Things I want to know more about](#things-i-want-to-know-more-about)

## Reflection

## Learn HTML

### Important HTML Links

[Ordered Lists](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol)

[Unordered Lists](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul)

#### HTML Questions

Q: When should you use an unordered list in your HTML document?

 You would use the unordered list when it's not necessary to be ordered.

Q: How do you change the bullet style of unordered list items?

  To change the style of the bullet you would change the attribute

Q: When should you use an ordered list vs. an unorder list in your HTML document?

  You would use the ordered list when you want the list to be ordered such as numbers.

Q: Describe two ways you can change the numbers on list items provided by an ordered list?

  You can use the start attribute such as `<ol start="4">` and you can also use Roman Numberal type `<ol type="i">`
  
## Learn CSS

### Important CSS Links

[The Box Model](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model)

### CSS Questions

Q: Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?

  The margin is the space around the box who can push other elements away.

  The padding is between the border and the content area and is used to push the content away fro the border.
  
Q: List and describe the four parts of an HTML elements box as referred to by the box model.

Content box - The area where your content is displayed; size it using properties like inline-size and block-size or width and height

Padding box - The padding sits around the content as white space; size it using padding and related properties.

Border box - The border box wraps the content and any padding; size it using border and related properties.

Margin box - The margin is the outermost layer, wrapping the content, padding, and border as whitespace between this box and other elements; size it using margin and related properties.
  
## Learn JS

### Important JS Links

[Arrays](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/Arrays)
[Operators and Expressions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)
[Conditionals](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/conditionals)
[Loops](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Looping_code)

### JS Questions

Q: What data types can you store inside of an Array?

  Strings, Numbers, Arrays, Objects

Q: Is the people array a valid JavaScript array? If so, how can I access the values stored?

If not, why? Yes, it is an valid array. It is a nested Array. people[1][0] is smith.

``` JS

 const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];

```

Q: List five shorthand operators for assignment in javascript and describe what they do.

- Assignement `=` Assigns a value to a variable.

- Addition assignment: `+=`  Ads the value of the right operand to a variable and  assigns the result to the variable

- Subtraction assignment: `-=` Subtracts the value of the right operand from a variable and assigns the result to the variable.

- Multiplication assignment: `*=` Multiplies a variable by the value of the right operand and assigns the result to the variable.

- Division assignment: `/=`: Divides a variable by the value of the right operand and assigns the result to the variable.

Q: Read the code below and evaluate the last expression and explain what the result would be and why.

  '10dog'

``` JS

 let a = 10;
 let b = 'dog';
 let c = false;

 // evaluate this
 (a + c) + b;

 ```

Q: Describe a real-world example of when a conditional statement should be used in a JavaScript program.

  You would use a conditional statement for many reasons but one could be for checking if a user is logged in and if they aren't logged in, to ask them to login in, and lastly, if they don't have an account, to create one.

Q: Give an example of when a Loop is useful in JavaScript.

Using a loop would be beneficial for iterating over a list of users to ensure that someone making a new username isn't picking one already used.

## Things I want to know more about
