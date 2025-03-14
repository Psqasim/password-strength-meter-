# 🔐 Password Strength Meter

A Streamlit web application that helps users evaluate password strength and generate secure passwords.

## Features

- **Password Strength Analysis**: Check how strong your password is based on industry standards
- **Real-time Feedback**: Get instant feedback on your password's strength
- **Password Generation**: Create strong, random passwords with a single click
- **Visual Indicators**: Color-coded progress bars to easily identify password strength
- **Detailed Feedback**: Specific suggestions to improve your password security

## Password Criteria

The application evaluates passwords based on the following criteria:
- Minimum length of 8 characters
- Mix of uppercase and lowercase letters
- At least one digit (0-9)
- At least one special character (!@#$%^&*)
- Not a commonly used password

## How to Use

1. Enter your password in the secure input field
2. View real-time analysis of your password's strength
3. Follow the suggestions to improve your password if needed
4. Alternatively, use the "Generate Strong Password" button to create a secure password automatically

## Installation

1. Make sure you have Python installed
2. Install Streamlit and required dependencies:
   ```
   pip install streamlit
   ```
3. Clone this repository or download the source code
4. Run the application:
   ```
   streamlit run app.py
   ```

## Screenshots

[Insert screenshots of the application here]

## Technical Details

- Built with Streamlit for a responsive, interactive web interface
- Implements password strength checking algorithms including:
  - Length verification
  - Character diversity checks
  - Common password detection
- Generates cryptographically diverse passwords with varied character types

## Contributing

Contributions, issues, and feature requests are welcome!

## Author

Created by Ps Qasim

## License

[MIT]