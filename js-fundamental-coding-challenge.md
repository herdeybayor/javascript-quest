# JavaScript Fundamentals Coding Challenge

## Overview
This challenge will test your understanding of JavaScript basics including syntax, variables, operators, and control flow. Complete each section and test your code to ensure it works correctly.

---

## Section 1: Basic Syntax & Output

### Challenge 1.1: Multi-line Comments
Create a multi-line comment that includes:
- Your name
- Today's date
- A brief description: "JavaScript Fundamentals Challenge"

```javascript
// Your code here
```

### Challenge 1.2: Output Methods
Write code that displays "Hello, JavaScript!" using three different output methods:
1. `console.log()`
2. `alert()`
3. `document.write()`

```javascript
// Your code here
```

### Challenge 1.3: Single-line Comments
Add single-line comments explaining what each output method does in Challenge 1.2.

---

## Section 2: Variables and Constants

### Challenge 2.1: Variable Declarations
Declare the following using appropriate keywords (`let`, `const`, or `var`):
- A variable `age` with your age (should be changeable)
- A constant `birthYear` with your birth year (should NOT be changeable)
- A variable `name` with your name using `var`

```javascript
// Your code here
```

### Challenge 2.2: Primitive Data Types
Create variables demonstrating each primitive data type:
```javascript
let myNumber = // assign a number
let myString = // assign a string with your favorite quote
let myBoolean = // assign true or false
let myNull = // assign null
let myUndefined = // declare without assigning a value
```

### Challenge 2.3: Naming Practice
Fix the following variable names to follow proper JavaScript naming conventions (camelCase):
```javascript
let my_first_name = "John";
let USERAGE = 25;
let user-email = "test@example.com";
let 1stPlace = "Gold";
```

---

## Section 3: Operators

### Challenge 3.1: Calculator
Create a simple calculator that:
- Declares two numbers: `num1 = 10` and `num2 = 3`
- Calculates and stores:
  - Addition result
  - Subtraction result
  - Multiplication result
  - Division result
  - Modulus (remainder) result
- Logs all results to the console with descriptive labels

```javascript
// Your code here
```

### Challenge 3.2: Assignment Operators
Start with `let score = 100`. Use assignment operators to:
1. Add 50 to score using `+=`
2. Subtract 30 using `-=`
3. Multiply by 2 using `*=`
4. Divide by 5 using `/=`

Log the score after each operation.

```javascript
// Your code here
```

### Challenge 3.3: Comparison Operators
Given `let a = 10` and `let b = "10"`, write code that:
- Compares `a` and `b` using `==` (loose equality)
- Compares `a` and `b` using `===` (strict equality)
- Checks if `a` is greater than 5
- Checks if `b` is not equal to 20 using `!=`

Log each result with a descriptive message.

```javascript
// Your code here
```

### Challenge 3.4: Logical Operators
Create variables:
```javascript
let isStudent = true;
let hasLicense = false;
let age = 20;
```

Use logical operators to check:
- Is the person a student AND has a license?
- Is the person a student OR has a license?
- Is the person NOT a student?
- Is the person older than 18 AND is a student?

```javascript
// Your code here
```

---

## Section 4: Control Flow

### Challenge 4.1: Grade Calculator
Write a program that:
- Takes a score (use `let score = 85`)
- Uses `if/else if/else` to determine the grade:
  - 90-100: "A"
  - 80-89: "B"
  - 70-79: "C"
  - 60-69: "D"
  - Below 60: "F"
- Logs: "Your grade is: [grade]"

```javascript
// Your code here
```

### Challenge 4.2: Day of the Week
Create a `switch` statement that:
- Takes a number (1-7) representing a day of the week
- Logs the corresponding day name (1 = Monday, 2 = Tuesday, etc.)
- Includes a default case for invalid numbers

```javascript
let dayNumber = 3;
// Your code here
```

### Challenge 4.3: Ternary Operator Practice
Use the ternary operator to:
1. Check if a person is an adult (age >= 18) and assign "Adult" or "Minor" to a variable
2. Check if a number is even or odd
3. Determine if a password length is valid (>= 8 characters)

```javascript
let userAge = 21;
let number = 7;
let password = "mypass123";

// Your code here
```

### Challenge 4.4: Complex Conditions
Create a program that checks if someone can rent a car:
- Must be 21 or older
- Must have a license
- If age is between 21-24, there's a "young driver fee"
- If 25 or older, no extra fee

Use nested `if` statements and log appropriate messages.

```javascript
let driverAge = 23;
let hasDriverLicense = true;

// Your code here
```

---

## Bonus Challenge: Combine Everything!

Create a simple "User Profile Validator" that:
1. Declares user information (name, age, email, isSubscribed)
2. Uses comments to explain each section
3. Validates:
   - Name is not empty (use comparison operators)
   - Age is between 13 and 120 (use logical operators)
   - Email contains "@" symbol
   - isSubscribed is a boolean
4. Uses control flow to log whether the profile is valid or which field has an error
5. Uses the ternary operator to assign a user type: "Premium" if subscribed, "Free" otherwise

```javascript
// Your code here
```

---

## Testing Your Code

1. Create an HTML file and link your JavaScript file, or use a browser console
2. Test each challenge individually
3. Make sure there are no errors in the console
4. Verify that outputs match expected results

## Submission Guidelines

- Complete all challenges in a single JavaScript file
- Add comments explaining your logic
- Test thoroughly before submitting
- Make sure your code follows proper naming conventions

## Tips

- Use `console.log()` frequently to debug
- Test edge cases (like negative numbers, empty strings)
- Read error messages carefully
- Remember: `let` and `const` are preferred over `var` in modern JavaScript

---

**Good luck! 🚀**
