# JS Variables and Data Types Exercise

1. Create the following variables
    - ***name**, which is a string set to your current name*
        ```js
        const name = "Patrick";
        ```
    - ***dayOfBirth**, which is a number set to the day of your birth month*
        ```js
        const dayOfBirth = 2;
        ```
2. See what happens when you have multiple variables of the same name. Which one takes precedence?
    - You can't have multiple variables with the same name. You can define and reassign as long as you've used `let` though.
3. Write some JavaScript that prompt’s the user for their favorite color. Once the user has submitted a favorite color, log that color to the console along with a friendly message.
    ```js
    const colorResp = prompt("What's your favorite color?");
    console.log(`${ colorResp } is my favorite color too!`);
    ```
4. Create a string that contains both single quotes and double quotes.
    ```js
    const oneStr = "Here's a quote that I wrote, \"hi\"";
    const anothrStr = `Here's another way to have both " and ' in a string.`;
    ```
5. What is the difference between null and undefined?
    - `null` is set by you and means there is no value.
    - `undefined` is used for variables that have no values (or no values *yet*).
6. What is ***NaN*** in JavaScript? What is the ***typeof NaN***?
    - `NaN` is "not a number." Resulting from operations that might involve numbers and other incompatible data types.
    - The value of `typeof NaN` is `number`
7. You can declare a variable by typing ***let thing;***. What is the value of ***thing***?
    - `thing` will be `undefined`