🧮 Modern Calculator

📖 Description

A responsive, modern calculator built with HTML, Tailwind CSS, and JavaScript.
It supports all basic arithmetic operations and includes a minimal, elegant dark/light mode style powered by Tailwind.

This project demonstrates front-end UI design and basic JavaScript logic handling in a single, self-contained HTML file — no frameworks required.

🚀 Features

✅ Clean and modern UI using Tailwind CSS
✅ Supports addition, subtraction, multiplication, division, and parentheses
✅ Live evaluation with error handling
✅ Dark mode ready (automatic based on system settings)
✅ Responsive design — works perfectly on desktop and mobile
✅ Smooth button animations

🧩 Technologies Used

HTML5

Tailwind CSS (via CDN)

JavaScript (ES6)

Google Fonts (Inter)

📂 Project Structure
calculator/
│
├── index.html      # Main calculator interface (all-in-one file)
└── README.md       # Project documentation

🧠 How It Works

The calculator listens for button clicks.

Each button appends a symbol (number/operator) to the input display.

When = is pressed, the expression is safely evaluated using JavaScript’s Function() constructor after sanitizing the input.

AC resets the screen to zero.

▶️ How to Run

Download or clone this repository:

git clone https://github.com/your-username/calculator.git


Open index.html in any web browser.

That’s it — no build step or dependencies needed.

💡 Example Usage

Click on numbers and operations to form an equation
e.g. (5 + 3) * 2

Press = to get the result
→ Output: 16

Use AC to clear and start a new calculation.

🧰 Future Enhancements

Add keyboard input support

Add scientific mode (sin, cos, log, etc.)

Add history of calculations

Add a toggle button for dark/light mode
