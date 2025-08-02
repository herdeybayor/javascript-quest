# 🧪 JavaScript Beginner Assessment: FizzBuzz

## 🔁 Objective

Write a JavaScript program that prints numbers from **1 to 50**, but with the following rules:

- If a number is **divisible by 3**, print `"Fizz"` instead of the number.
- If a number is **divisible by 5**, print `"Buzz"` instead of the number.
- If a number is **divisible by both 3 and 5**, print `"FizzBuzz"` instead of the number.
- Otherwise, just print the number itself.

---

## ✅ Example Output

```
1
2
Fizz
4
Buzz
Fizz
7
8
Fizz
Buzz
11
Fizz
13
14
FizzBuzz
...
```

---

## 🧠 Your Task

1. Use a loop (`for` loop preferred) to go through numbers from `1` to `50`.
2. Use the modulo operator (`%`) to check divisibility.
3. Use `console.log()` to print the result for each number.

---

## 💡 Helpful Tips

- A number is divisible by another number if `number % divisor === 0`.
- The order of your conditions matters!
  - Check if a number is divisible by **both 3 and 5** before checking 3 or 5 individually.

---

## 💻 Starter Code

```javascript
function fizzBuzz(end) {
  for (let i = 1; i <= end; i++) {
    // Your code here
    console.log(i);
  }
}

fizzBuzz(50);
```

---

## 🌟 Bonus Challenge

Create a function called `fizzBuzz()` that accepts a number (`maxNumber`) and performs FizzBuzz from `1` to `maxNumber`.

### Example:

```javascript
fizzBuzz(20);
```

### Output:
```
1
2
Fizz
4
Buzz
Fizz
7
8
Fizz
Buzz
11
Fizz
13
14
FizzBuzz
16
17
Fizz
19
Buzz
```

---

## 🚀 Submission

Once you're done:
- Test your code with different ranges.
- Push your solution to GitHub (in a `.js` file).
- Optionally, share your code with peers or mentors for feedback!

Happy coding! 💻✨
