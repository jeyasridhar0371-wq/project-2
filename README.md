# Real-Time Character Counter

## 📖 Project Overview

This project is a simple **Real-Time Character Counter** built using **HTML, CSS, and JavaScript**. It allows users to type a message inside a text area while displaying the number of characters entered and the remaining characters available. The counter updates instantly as the user types, providing immediate feedback.

---

## 🚀 Features

- Simple and responsive text area.
- Displays the maximum character limit (200 characters).
- Real-time character counting.
- Shows the number of characters typed.
- Displays the remaining characters available.
- Prevents users from typing beyond the maximum limit.
- Displays a warning message when the limit is reached.
- Built using pure HTML, CSS, and JavaScript (no external libraries).

---

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript (DOM Manipulation & Event Handling)

---

## 📂 Project Structure

```
Real-Time-Character-Counter/
│
├── index.html
├── style.css
├── script.js
└── README.md
```

---

## ⚙️ How It Works

1. The user types a message into the text area.
2. JavaScript listens for the `input` event.
3. The character counter updates in real time.
4. The application displays:
   - Characters typed
   - Characters remaining
5. Once the maximum limit (200 characters) is reached:
   - Additional typing is prevented.
   - A warning message is displayed.

---

## 📸 Output

Example:

```
200 characters max

Type your message here...

150/200 characters
Remaining: 50 characters
```

When the limit is exceeded:

```
⚠ Character limit reached!
```

---

## 🎯 Learning Objectives

This project helps understand:

- DOM Manipulation
- Event Listeners
- Input Events
- String Length Property
- Real-Time UI Updates
- JavaScript Validation

---

## 💡 Future Improvements

- Add a progress bar.
- Change counter color as the limit approaches.
- Allow users to customize the character limit.
- Add a dark mode.
- Support word counting in addition to character counting.

---

## 📄 License

This project is open source and available under the **MIT License**.
