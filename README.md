# 🔐 Secure Password Manager

A lightweight, client-side password manager and generator built with HTML, CSS, and JavaScript. Create strong passwords or generate secure ones instantly - all without storing any data on servers!

# 👨‍💻 Developer Information 
- **Developer**: P.Manasa
- **Roll No**: 222T1A3145
- **Institution**: Ashoka Womens Engineering College.


## 🌟 Features

### 🎲 Password Generator
- **Customizable Length**: Generate passwords from 8 to any desired length
- **Strong Security**: Includes uppercase, lowercase, digits, and special characters
- **Guaranteed Strength**: Ensures all character types are present in generated passwords
- **One-Click Copy**: Copy generated passwords to clipboard instantly

### ✍️ Manual Password Creation
- **Password Validation**: Real-time strength checking
- **Confirmation Matching**: Ensures password consistency
- **Security Requirements**: Enforces strong password policies
- **User-Friendly Feedback**: Clear error messages and success confirmations

### 🎨 User Interface
- **Clean Design**: Modern, responsive interface
- **Tab-based Navigation**: Easy switching between generator and manual creation
- **Visual Feedback**: Color-coded messages and hover effects
- **Mobile-Friendly**: Works seamlessly on all device sizes



## 🛠️ Technologies Used

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Libraries**: None - Pure vanilla JavaScript
- **Browser APIs**: Clipboard API for copy functionality
- **Styling**: Custom CSS with modern design patterns

## 📋 Requirements

- Modern web browser with JavaScript enabled
- No server or database required
- Internet connection not needed (runs offline)


## 🎯 How to Use

### Password Generator Tab:
1. Set desired password length (minimum 8 characters)
2. Click "Generate Password"
3. Copy the generated password using "Copy to Clipboard"

### Create Password Tab:
1. Enter your desired password
2. Confirm by retyping the password
3. Click "Submit" to validate

## 🔒 Security Features

### Password Requirements:
- ✅ **Minimum 8 characters** - Industry standard minimum length
- ✅ **Uppercase letters** - At least one (A-Z)
- ✅ **Lowercase letters** - At least one (a-z)
- ✅ **Numbers** - At least one digit (0-9)
- ✅ **Special characters** - At least one (!@#$%^&*()etc.)

### Security Benefits:
- 🛡️ **Client-side only** - No data sent to servers
- 🔐 **No data storage** - Passwords are not saved anywhere
- 🎲 **Cryptographically secure** - Uses Math.random() for generation
- 🚫 **No tracking** - Complete privacy protection

## 📁 File Structure

```
secure-password-manager/
│
├── index.html              # Main application file
├── README.md              # This documentation
├── screenshots/           # Application screenshots
│   ├── main-interface.png
│   ├── generator-tab.png
│   └── manual-tab.png
└── LICENSE               # MIT License
```

## 🎨 Customization

### Modify Password Character Sets:
```javascript
const lowercase = 'abcdefghijklmnopqrstuvwxyz';
const uppercase = 'ABCDEFGHIJKLMNOPQRSTUVWXYZ';
const digits = '0123456789';
const symbols = '!@#$%^&*()-_=+[{]};:,.<>?/';
```

### Change Color Scheme:
```css
:root {
  --primary-color: #007BFF;
  --hover-color: #0056b3;
  --background-color: #f9f9f9;
}
```
## 🙏 Acknowledgments

- Inspired by modern password management best practices
- Design influenced by Material Design principles
- Security guidelines from OWASP recommendations
- Thanks to the web development community for feedback


**Stay Secure! 🔐**

