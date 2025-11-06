🔢 Number to Words (Indian Currency System)

A simple yet powerful Python-based number-to-words converter that follows the Indian numbering system — supporting crores, lakhs, thousands, and hundreds.

🚀 Features

Converts numeric values into Indian-style words

Supports crores, lakhs, thousands, hundreds

Handles all special cases (1–19, tens, hundreds)

Recursive logic for clean, scalable conversion

Fully written in pure Python (no dependencies)

Lightweight, easy to integrate into other projects

🧠 Logic Overview

At first, this logic may seem simple — but when you start implementing it, it gets progressively tougher.
You’ll face multiple exceptions, edge cases, and recursive logic challenges that make it a perfect problem to test your analytical thinking and Python fundamentals.

Example:

Input: 1234567  
Output: twelve lakh thirty four thousand five hundred and sixty seven

🧩 Concepts Used

Recursion & modular arithmetic

String manipulation

Logical flow control

Clean, reusable functions

💻 Tech Used

🐍 Python 3

(No external modules required)

⚙️ Installation & Usage

Clone this repository:

git clone https://github.com/akshithkendyala/Number-to-Words.git
cd Number-to-Words
python number_to_words.py


Run the program and enter any number:

Enter number: 1234567
twelve lakh thirty four thousand five hundred and sixty seven

📂 File Structure
number_to_words.py
│
├── two_digit(n)       → Handles numbers from 0–99
├── three_digit(n)     → Handles 0–999
├── number_to_words(n) → Recursive logic for larger values
└── Main section       → Input + output display

💬 Note

This project might look basic, but the logic behind it challenges your problem-solving mindset.
It’s one of those problems that sharpen your logical depth and attention to detail.

💡 Explore Further

Try implementing this in C++, JavaScript, or Java with your own optimized approach —
and see how different languages handle recursion and string logic.

👨‍💻 Author

Akshith Kendyala
