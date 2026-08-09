# Form Submission Application

A simple yet powerful web form application with real-time validation, password strength checking, and data collection functionality.

## Features

- **Form Validation**
  - Required field validation (Name, Email, Password)
  - Email format validation using regex
  - Real-time password strength indicator

- **Password Security**
  - Strength levels: Weak, Medium, Strong
  - Requirements: 8+ characters, uppercase, lowercase, numbers, special characters
  - Live feedback as user types

- **Data Collection**
  - Collects user information (name, email, phone, gender, country)
  - Newsletter subscription option
  - Saves data to localStorage
  - Displays submitted data with timestamp

- **User Interface**
  - Styled form with modern design
  - Color-coded success/error messages
  - Responsive layout
  - Navigation bar support

## Files

- `form.html` - Main form structure with styling
- `apply.js` - Form validation and submission logic
- `styl.css` - Navigation and styling
- `README.md` - Project documentation

## How to Use

1. Open `form.html` in your web browser
2. Fill in the form fields:
   - Name (required)
   - Email (required, must be valid format)
   - Password (required, must be strong)
   - Phone (optional)
   - Gender (optional)
   - Country (dropdown)
   - Newsletter subscription (checkbox)
3. Click Submit to validate and submit the form
4. View the submitted data displayed on the page
5. Data is automatically saved to browser's localStorage

## Form Fields

| Field | Type | Required | Notes |
|-------|------|----------|-------|
| Name | Text | Yes | Any name |
| Email | Email | Yes | Must be valid format |
| Password | Password | Yes | Min 8 chars, mixed case, numbers, special chars |
| Phone | Tel | No | Format: 123-456-7890 |
| Gender | Radio | No | Male or Female |
| Country | Select | No | USA, Canada, UK, Australia |
| Newsletter | Checkbox | No | Subscribe option |

## Password Requirements

Password must contain:
- ✓ Minimum 8 characters
- ✓ Uppercase letter (A-Z)
- ✓ Lowercase letter (a-z)
- ✓ Number (0-9)
- ✓ Special character (@$!%*?&)

## Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6)
- LocalStorage API

## Author

Ruben Dsouza

## License

MIT License
