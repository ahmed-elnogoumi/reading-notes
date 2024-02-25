# Readings: HTML Lists, Control Flow with JS, and the CSS Box Model

## Reading

1. When should you use an unordered list in your HTML document?
    - Items that don't need to be ordered.
2. How do you change the bullet style of unordered list items?
    - The type attribute.
3. When should you use an ordered list vs an unorder list in your HTML document?
    - An ordered list is for any information that needed to be ordered, an unordered list is for anything that doesn't need any ordered.
4. Describe two ways you can change the numbers on list items provided by an ordered list?
    - The type attribute.

## Learn CSS

1. Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?
    - Margin; the invisible super hero who protects the content past the border. Padding, the superhero who keeps the border from collapsing in on the content.
2. List and describe the four parts of an HTML elements box as referred to by the box model.
    - Margin, Border, Padding, Content

## Learn JS

1. What data types can you store inside of an Array?
    - Strings, numbers, objects and arrays.
2. Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?
    - Yes. You can access the values by using indices. 
    ``` Javascript
        People[0][0]
    ```

``` Javascript
 const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];
```
3. List five shorthand operators for assignment in javascript and describe what they do.
    - =, assignment. +=, addition. -=, subtraction. /=, division.  %=, remainder.
4. Read the code below and evaluate the last expression and explain what the result would be and why.
    - 10dog. The 10 would concatenate to the 'dog' string - but false doesn't output anything.

``` Javascript
 let a = 10;
 let b = 'dog';
 let c = false;

 // evaluate this
 (a + c) + b;
```

5. Describe a real world example of when a conditional statement should be used in a JavaScript program.
    - A real world example would be using JS to check if a user input a phone number or an email address - for example.
6. Give an example of when a Loop is useful in JavaScript.
    - To do iterations or counting.

## Things I want to know more about
- Can I use JS to modify CSS?
- JS animation? What can I do with that?