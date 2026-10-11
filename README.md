# 🔐 Password Generator

A simple and interactive **Password Generator App** built using HTML, CSS, and JavaScript. It allows users to generate random passwords with customizable lengths and character types, check password strength, and copy passwords to the clipboard.

## ✨ Features

- **Custom Password Length:** Choose the desired password length using a slider.
- **Uppercase Letters:** Include uppercase letters (A–Z).
- **Lowercase Letters:** Include lowercase letters (a–z).
- **Numbers:** Include numeric characters (0–9).
- **Symbols:** Include special characters such as `@`, `#`, `$`, `%`, and more.
- **Password Strength Indicator:** Visual indicator to represent password strength.
- **Copy to Clipboard:** Copy the generated password with a single click.
- **Random Password Shuffling:** Shuffles characters to improve character distribution.
- **Responsive Interface:** Easy-to-use interface for generating passwords.

## 🛠️ Technologies Used

- **HTML5** – Structures the application.
- **CSS3** – Styles the interface and its components.
- **JavaScript (ES6)** – Handles password generation, validation, strength indication, and clipboard functionality.

## ⚙️ How It Works

1. Select the desired password length using the slider.
2. Choose one or more character types:
   - Uppercase letters
   - Lowercase letters
   - Numbers
   - Symbols
3. Click the **Generate Password** button.
4. View your generated password in the display field.
5. Check the password strength indicator.
6. Click the **Copy** button to copy the password to your clipboard.

## 📂 Project Structure

```text
Password-Generator/
├── index.html
├── style.css
├── script.js
└── README.md
```

*Note: Update the filenames above if your project uses a different folder structure.*

## 🚀 Getting Started

### Prerequisites

You need a modern web browser such as Google Chrome, Mozilla Firefox, or Microsoft Edge.

### Installation

1. Clone the repository:

   ```bash
   git clone <your-repository-url>
   ```

2. Navigate to the project directory:

   ```bash
   cd Password-Generator
   ```

3. Open `index.html` in your browser.

   Alternatively, use the **Live Server** extension in Visual Studio Code for a better development experience.

## 🔒 Password Strength Indicator

The application evaluates password strength based on the selected character types and password length.

| Indicator Color | Meaning |
|---|---|
| 🔴 Red | Weak password |
| 🟡 Yellow | Medium password |
| 🟢 Green | Strong password |

*Note: The strength indicator uses the application's own rules and is not a comprehensive security assessment.*

## 🎯 Learning Outcomes

This project demonstrates practical use of:

- DOM manipulation and event listeners.
- JavaScript functions and arrays.
- Checkbox and slider interactions.
- Random character generation.
- The Fisher–Yates shuffle algorithm.
- Clipboard API using `navigator.clipboard`.
- Conditional logic and password strength evaluation.

## 🔮 Future Improvements

- Use the Web Crypto API for cryptographically secure random generation.
- Add password history with an option to clear it.
- Improve password strength estimation.
- Add a password visibility toggle.
- Display clear validation messages when no character type is selected.
- Improve accessibility and mobile responsiveness.

## 👨‍💻 Author

**Sanjit Kumar Saha**

- GitHub: [@yarsanjit](https://github.com/yarsanjit)
- LeetCode: [@yarsanjit](https://leetcode.com/u/yarsanjit/)

## 📄 License

This project is open-source and available for learning and personal use. Add a license file if you intend to distribute it under a specific open-source license.
