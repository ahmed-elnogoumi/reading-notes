## React Docs - lists and keys

1. What does .map() return?
    - Returns a new array with the results of every element on the calling array.
2. If I want to loop through an array and display each value in JSX, how do I do that in React?
    - .map()
3. Each list item needs a unique ____.
    - a 'key'
4. What is the purpose of a key?
    - to identify items in a list.

## The Spread Operator

1. What is the spread operator?
    - ('...') to put iterable objects into individual elements. Allows you to manipulat arrays and objects.
2. List 4 things that the spread operator can do.
    - To copy arrays.
    - Concatenate arrays.
    - Add elements to arays.
    - Merge objects.
3. Give an example of using the spread operator to combine two arrays.
    ```
    const array1 = [1, 2, 3];
    const array2 = [4, 5, 6];
    const combinedArray = [...array1, ...array2];
    ```
4. Give an example of using the spread operator to add a new item to an array.
    ```
    const originalArray = [1, 2, 3];
    const newArray = [...originalArray, 4];
    ```
5. Give an example of using the spread operator to combine two objects into one.
    ```
    const obj1 = { a: 1, b: 2 };
    const obj2 = { c: 3, d: 4 };
    const combinedObject = { ...obj1, ...obj2 };
    ```

## How to Pass Functions Between Components

1. In the video, what is the first step that the developer does to pass functions between components?
    - Definite function in the parent component.
2. In your own words, what does the handleClick function do?
    - Event handler that's triggered by a button click on the mouse.
3. How can you pass a method from a parent component into a child component?
    - Pass it as a prop to a child component.
4. How does the child component invoke a method that was passed to it from a parent component?
    - Child component invokes method from parent component by calling method through props passed through it.
