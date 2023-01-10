# Class 01 Reading Notes | Passing Functions as Props

[React Docs - lists and keys](https://reactjs.org/docs/lists-and-keys.html)

## Discussion Questions

- Q: What does .map() return?

  - A: In React, the map() function is used to transform arrays into lists of elements.

- Q: If I want to loop through an array and display each value in JSX, how do I do that in React?

  - A: You use the map() function to loop through the array. Then you would return an `<li>` element for each item in the array. You could then return the entire listItems array inside an `<`ul>` element.

  ```JSX

    function NumberList(props) {
  const numbers = props.numbers;
  const listItems = numbers.map((number) =>
    <li>{number}</li>
  );
  return (
    <ul>{listItems}</ul>
  );
  }
  const numbers = [1, 2, 3, 4, 5];

  const root = ReactDOM.createRoot(document.getElementById('root'));
  root.render(<NumberList numbers={numbers} />);

  ```

You can build collections of elements and include them in JSX using curly braces `{}`.

- Q: Each list item needs a unique.

  - A: Key

- Q: What is the purpose of a key?

  - A: Keys help React identify which items have changed, added, or removed.

[The Spread Operator](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

## Discussion Questions

- Q: What is the spread operator?

  - A: The spread operator is a valuable and quick syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a function’s arguments.

- Q: List 4 things that the spread operator can do.

  - A:
    1. Copy an Array
    2. Combine Arrays
    3. Adding an item to a list
    4. Adding to state in React

- Q: Give an example of using the spread operator to combine two arrays.

  - A:

  ```jsx
  const parents = ["Jeremy", "Megan"];
  const kids = ["Cora", "Norah", "Natlie", "Liam"];

  const fullFamily = [...parents, ...kids];

  //["Jeremy", "Megan", "Cora", "Norah", "Natlie", "Liam]
  ```

- Q: Give an example of using the spread operator to add a new item to an array.

  - A:

  ```jsx
  const parents = ["Jeremy", "Megan"];
  const kids = ["Cora", "Norah", "Natlie", "Liam"];

  const fullFamily = [...parents, ...kids, ..."Gunner"];

  //["Jeremy", "Megan", "Cora", "Norah", "Natlie", "Liam", "Gunner"]
  ```

- Q: Give an example of using the spread operator to combine two objects into one.

  - A:

  ```jsx
  const family = { parent: "Jeremy", kid: "Cora" };
  const pets = { dog: "Gunner", cat: "Amber" };

  const fullFamily = { ...family, ...pets };
  //{parent: "Jeremy", kid: "Cora", dog: "Gunner", cat: "Amber"}
  ```

[How to Pass Functions Between Components](https://www.youtube.com/watch?v=c05OL7XbwXU)

- Q: In the video, what is the first step that the developer does to pass functions between components?

  - A: The first step the developer did was to create the increment function at the App component, which is where the state is located.

- Q: In your own words, what does the increment function do?

  - A: The increment function maps through the people object to verify which person's name equals the one passed from the child component through props. Whichever one was passed has the count in the state incremented by one.

- Q: How can you pass a method from a parent component into a child component?

  - A: The method is passed from the parent to the child using props.

- Q: How does the child component invoke a method that was passed to it from a parent component?

  - A: The child component uses the method by which when the user clicks on the button, it invokes the local increment function, which calls the increment method at the parent component and passes along the name of the person.

## Things I want to know more about
