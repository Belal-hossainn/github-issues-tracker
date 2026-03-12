
Assignment Questions Answer:
1. What is the difference between var, let, and const?
var, let, and const are used to declare variables in JavaScript.
var
    1.	It is the older way to declare variables.
    2.	It is function scoped.
    3.	The same variable can be declared repetitively. 
    Ex:
    var name = "Rayhan"
    var name = "Rahim"
    let
    1.	 It is Introduced in ES6.
    2.	It is block scoped.
    3.	The same variable cannot be declared again, but the value can be changed.
    Ex:
    let age = 20
    age = 21
    const
    1.	Also introduced in ES6.
    2.	It is block scoped.
    3.	The value must be assigned when declaring.
    4.	The value cannot be reassigned/changed later.
    Ex:
    const country = "Bangladesh"

 2. What is the spread operator (...)?
Ans: The spread operator (...) is used to expand or copy elements of an array or object. It is commonly used to:
    	copy arrays
    	merge arrays
    	copy objects
    For example:
    const numbers = [1,2,3]

    const newNumbers = [...numbers, 4,5]
    console.log(newNumbers)
    Output:
    [1,2,3,4,5]

 3. What is the difference between map(), filter(), and forEach()?
    Ans: map(), filter(), and forEach() are array method which used to loop through an array. 
    map(): map() method loop through every element on array & function on every element and return a new array. 
    Example: 
    const numbers = [1,2,3]
    const result = numbers.map(n => n * 2)
    Output:
    [2,4,6]
    filter(): filter() method loop through every element on array and match the condition and return new array with the match. It’s condition based. 
    Example:
    const numbers = [1,2,3,4]
    const result = numbers.filter(n => n > 2)
    Output:
    [3,4]
    forEach(): forEach() loops through the array to run some code. It does not return a new array.
    Example:
    const numbers = [1,2,3]
    numbers.forEach(n => {
    console.log(n)
    })

4. What is an arrow function?
    Ans: An arrow function is a shorter way to write a function in JavaScript. 
    It was introduced in ES6 and helps make the code shorter and cleaner.
    Example:
    Normal Function:
    function add(a,b){
    return a + b
    }

    Arrow Function:
    const add = (a,b) => a + b

5. What are template literals?
    Ans: Template literals are used to create strings that can include variables easily.
    We use backticks ` ` instead of quotes. It also allow multi-line strings.
    Example:
    const name = "Rayhan"
    const message = `Hello ${name}`
    console.log(message)
    Output:
    Hello Rayhan
    Template literals also allow multi-line strings.

  
