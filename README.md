# 🔐 Password Strength Analyzer

A responsive and interactive Password Strength Analyzer built using **HTML**, **CSS**, and **JavaScript**. It evaluates the strength of a password in real-time based on multiple criteria like length, character variety, and common password patterns.


## 🚀 Features

- ✅ Real-time password strength analysis
- ✅ Dynamic strength meter with colored bars
- ✅ Visual feedback on password requirements:
  - Minimum 12 characters
  - Includes uppercase and lowercase letters
  - Contains numbers and special characters
  - Not a common password
- ✅ Toggle password visibility
- ✅ Responsive and mobile-friendly design
- ✅ Smooth UI transitions and tooltips for guidance

## 📸 UI Overview

- **Strength Meter**: Visually indicates password strength (`Weak` to `Very Strong`)
- **Strength Score**: Ranges from 0–100 based on a weighted scoring algorithm
- **Requirements Checklist**: Highlights which criteria are met
- **Tooltip Info**: Provides extra help on why requirements matter

## 🛠️ Technologies Used

- HTML5
- CSS3 (with custom variables for theme consistency)
- Vanilla JavaScript
- Font Awesome for icons
- Google Fonts (`Poppins`)

## 💡 How It Works

The password strength is calculated based on:

| Criteria             | Weight  |
|----------------------|---------|
| Minimum Length (12+) | 25 pts  |
| Uppercase Letters    | 10 pts  |
| Lowercase Letters    | 10 pts  |
| Numbers              | 10 pts  |
| Special Characters   | 20 pts  |
| Extra Length Bonus   | +15 pts |
| Common Password Penalty | -30 pts |

The score is then reflected in the progress bar and strength label.


## 📦 How to Run Locally

1. Clone the repository:
   ```bash
     git clone https://github.com/keshavcybersec/passchecker.git
2. Navigate to the project folder:

     cd password-strength-analyzer

3. Open index.html in any browser.


🙌 Contributing

Contributions are welcome! Feel free to:

    Add new password rules

    Improve accessibility

    Integrate a password generator

📄 License

This project is licensed under the MIT License.
