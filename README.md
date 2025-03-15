# Day Activity Switch Statement

🚀 A simple JavaScript program that uses a `switch` statement to determine activities based on the day of the week.

## 📌 Features
- Uses a `switch` statement to check the current day.
- Outputs a specific activity for each day.
- Encourages rest on Sundays! 😴

## 🛠️ Technologies Used
- JavaScript

## 📜 Code Overview
```javascript
let day = 'Sunday';

switch (day) {
    case 'Monday':
    case 'Tuesday':
    case 'Wednesday':
    case 'Thursday':
    case 'Friday':
    case 'Saturday':
        console.log('Eaty, sleepy, trainy!');
        break;
    case 'Sunday':
        console.log('Rest!');
        break;
}
```

## 🚀 How to Run
1. Copy the script into a `.js` file (e.g., `script.js`).
2. Open the browser console or run the file using Node.js.
3. Observe the console output based on the assigned `day` variable.

## 📌 Future Improvements
- Add user input to dynamically select a day.
- Expand activities with more specific plans for each day.

---
💡 **Happy Coding!** 🎉
