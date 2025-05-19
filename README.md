````markdown
# 🌍 Leap Year Calculator

This is a simple JavaScript project that checks whether a given year is a leap year or not. A leap year occurs every 4 years, with a few exceptions based on century rules.

## ✅ Features

- Determines if a year is a leap year based on these rules:
  - A year is a leap year if it is divisible by 4
  - Except years divisible by 100 (not leap years)
  - Unless they are also divisible by 400 (then leap years)
- Outputs a user-friendly message to the console

## 🧠 Logic

A year is a **leap year** if:
```text
(year % 4 === 0 && year % 100 !== 0) || (year % 400 === 0)
```

## 🛠️ Usage

1. Clone or download this repository.
2. Open the JavaScript file in your editor.
3. Modify the `year` variable to test different years.
4. Run the file in a JavaScript environment (e.g., browser console or Node.js).

### Example:

```javascript
let year = 2024;
let result = isLeapYear(year);
console.log(result); // Output: 2024 is a leap year.
```

## 🧪 Sample Test Outputs

| Year | Output                   |
| ---- | ------------------------ |
| 2024 | 2024 is a leap year.     |
| 2000 | 2000 is a leap year.     |
| 1900 | 1900 is not a leap year. |
| 2023 | 2023 is not a leap year. |

## 📄 Code

```javascript
let year = 2024;

function isLeapYear(year) {
  if ((year % 4 === 0 && year % 100 !== 0) || (year % 400 === 0)) {
    return `${year} is a leap year.`;
  } else {
    return `${year} is not a leap year.`;
  }
}

let result = isLeapYear(year);
console.log(result);
``

## 📚 Learn More

* [MDN: Leap Year Rules](https://developer.mozilla.org/)
* [Wikipedia: Leap Year](https://en.wikipedia.org/wiki/Leap_year)

## 📦 Technologies

* JavaScript (ES6)
* Node.js or browser console for execution

---

© 2025 Leap Year Calculator by Jordan Leturgez

```
