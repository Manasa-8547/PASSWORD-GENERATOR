# PASSWORD-GENERATOR
A Web based application designed to help users create strong, random and secure passwords for protecting their online accounts and sensitive information. The tool enables users to customize their passwords by selecting their criteria such as length, use of uppercase and lowercase letters, numbers and special characters.
# Developer Information 
- **Developer**: P.Manasa
- **Roll No**: 222T1A3145
- **Institution**: Ashoka Womens Engineering College.
- **Academic Year**: 2024-2025
# Secure Password Manager

A simple, client-side password manager that allows users to generate secure passwords or create custom passwords with strength validation.

## Features

- **Password Generation**: Generate cryptographically strong passwords with customizable length
- **Password Creation**: Create custom passwords with real-time validation
- **Security Requirements**: Enforces strong password policies
- **User-friendly Interface**: Clean, tabbed interface for easy navigation
- **Clipboard Integration**: One-click copy functionality for generated passwords

## Security Features

### Password Requirements
All passwords (generated or custom) must meet the following criteria:
- Minimum 8 characters in length
- Contains at least one lowercase letter (a-z)
- Contains at least one uppercase letter (A-Z)
- Contains at least one digit (0-9)
- Contains at least one special character (!@#$%^&*()-_=+[{]};:,.<>?/)

### Password Generation
- Uses a secure character set including all required character types
- Generates passwords up to any specified length (minimum 8)
- Ensures all generated passwords meet security requirements
- Uses JavaScript's `Math.random()` for character selection

## How to Use

### Generate Password Tab
1. Enter desired password length (minimum 8 characters)
2. Click "Generate Password"
3. Copy the generated password using "Copy to Clipboard"

### Create Password Tab
1. Enter your desired password
2. Confirm the password by re-entering it
3. Click "Submit" to validate the password
4. Receive feedback on password strength and compliance

## File Structure

```
password-manager/
│
├── index.html          # Main application file (complete standalone app)
└── README.md          # This documentation file
```

## Installation & Setup

### Option 1: Direct Usage
1. Save the provided HTML code as `index.html`
2. Open the file in any modern web browser
3. Start using the password manager immediately

### Option 2: Web Server (Recommended)
1. Place the `index.html` file in your web server directory
2. Access via `http://your-domain/index.html`
3. Enjoy full functionality including clipboard operations

## Browser Compatibility

 **Chrome**: Full support (version 66+)
 **Firefox**: Full support (version 63+)
 **Safari**: Full support (version 13.1+)
- **Edge**: Full support (version 79+)

**Note**: Clipboard functionality requires HTTPS or localhost for security reasons in modern browsers.

## Technical Specifications

### Technologies Used
- **HTML5**: Structure and semantic markup
- **CSS3**: Styling and responsive design
- **Vanilla JavaScript**: All functionality and interactivity

### Key Functions
- `generatePassword()`: Creates secure random passwords
- `submitManualPassword()`: Validates custom passwords
- `copyGenerated()`: Copies password to clipboard
- `switchTab()`: Manages tab navigation

## Security Considerations

### Client-Side Only
- All operations happen in the browser
- No data is sent to external servers
- No password storage or persistence
- Complete user privacy

### Limitations
- Uses `Math.random()` which is not cryptographically secure for high-security applications
- No password storage functionality
- No password history or management features

## Customization

### Modifying Password Requirements
To change password requirements, modify the validation regex patterns in the JavaScript:
```javascript
/[a-z]/.test(password)        // Lowercase requirement
/[A-Z]/.test(password)        // Uppercase requirement
/[0-9]/.test(password)        // Digit requirement
/[!@#$%^&*()...]/.test(password)  // Special character requirement
```

### Styling Customization
Modify the CSS section to change:
- Color scheme
- Layout and spacing
- Typography
- Responsive breakpoints

## Contributing

This is a standalone application perfect for:
- Educational purposes
- Personal use
- Integration into larger projects
- Customization and extension

## License

This project is provided as-is for educational and personal use.

## Future Enhancements

Potential improvements could include:
- Cryptographically secure random number generation
- Password strength meter with visual feedback
- Local storage for encrypted password vault
- Export/import functionality
- Multiple password generation templates
- Pronounceable password generation option

## Support

For issues or questions:
1. Check browser console for JavaScript errors
2. Ensure you're using a supported browser
3. Verify HTTPS is used for clipboard functionality
4. Test in an updated browser version

---

**Version**: 1.0  
**Last Updated**: August 2025
