# Password Strength Checker

A lightweight, client-side password strength evaluation tool with visual feedback.


## Features

- Real-time strength calculation as you type
- Visual strength bar with color coding (red/orange/green)
- Percentage-based strength indicator
- Clear requirement listing
- Mobile-friendly responsive design

## Password Requirements

- Minimum 15 characters (20+ recommended)
- At least one uppercase letter (A-Z)
- At least one lowercase letter (a-z)
- At least one number (0-9)
- At least one special character (!@#$%^&* etc.)

## Strength Levels

- **Very Weak** (Red): < 40% (meets 0-1 criteria)
- **Medium** (Orange): 40-79% (meets 2-3 criteria)
- **Strong** (Green): 80-100% (meets 4-5 criteria)

## How to Use

1. Clone this repository or download `index.html`
2. Open the file in any web browser
3. Type your password in the input field
4. View real-time strength feedback

## Technical Details

- Pure HTML/CSS/JavaScript (no dependencies)
- Uses regular expressions for pattern matching
- Responsive design works on all screen sizes
- Lightweight (under 10KB total)

## Customization Options

1. Change colors in the CSS `.weak`, `.medium`, `.strong` classes
2. Adjust minimum length in both HTML placeholder and JavaScript
3. Modify scoring system in the strength calculation function

## License

MIT License - Free for personal and commercial use
