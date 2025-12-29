# JavaScript Form Validation (No Libraries)

A simple, production-style **client-side form validation** project built using **vanilla JavaScript** and **browser-native APIs**.

No frameworks. No libraries. Just fundamentals.

---

## 🚀 Features

* Uses the **HTML Constraint Validation API** (`form.checkValidity()`)
* Password match validation
* Clear success & error messaging
* Real-time visual feedback (border + message states)
* Prevents invalid form submission
* Clean separation of concerns

---

## 🧠 Why this project?

Most beginner form validation examples:

* Overuse libraries
* Mix validation with submission logic
* Ignore browser-native capabilities

This project focuses on:

* Readable control flow
* Early returns
* Explicit validation state
* Scalable logic that mirrors real-world apps

---

## 🧩 How it works

### Validation Flow

1. Browser checks required fields using `checkValidity()`
2. Password fields are compared manually
3. UI feedback is updated based on validation state
4. Data is only processed if the form is valid

---

## 📂 Project Structure

```bash
├── index.html
├── style.css
└── script.js
```

---

## 🛠️ Technologies Used

* HTML5
* CSS3
* JavaScript (ES6)
* Browser Constraint Validation API

---

## 📌 Key Concepts Covered

* Client-side form validation
* DOM manipulation
* Event handling
* Early return pattern
* Separation of concerns
* UX-focused error handling

---

## 🧪 Example Output

On successful validation:

* Green borders
* Success message displayed
* User data logged to the console

On failure:

* Red borders
* Contextual error message
* Submission blocked

---

## 📎 Usage

1. Clone the repository

   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```
2. Open `index.html` in your browser
3. Submit the form with valid and invalid inputs to see validation in action

---

## 🔮 Possible Improvements

* Inline field-level error messages
* Password strength validation
* Accessibility improvements (ARIA)
* Backend integration
* Conversion to React controlled form

---

## 🤝 Contributing

Contributions, suggestions, and improvements are welcome.
Feel free to fork the repo and submit a PR.

---

## 📬 Contact

If you’re interested in collaborating or discussing frontend fundamentals, feel free to connect.

---
