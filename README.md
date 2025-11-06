🧾 Number to Words (Indian Currency System)
📖 Overview:

This Python program converts a numeric value into its word representation following the Indian numbering system — including crores, lakhs, thousands, and hundreds.
For example:

Input: 1234567  
Output: twelve lakh thirty four thousand five hundred and sixty seven


While it may seem simple at first glance, implementing it requires handling several exceptions, recursive breakdowns, and language-specific nuances.
This project focuses on logic clarity, recursion, and clean scalability.

⚙️ Features

Supports Indian numbering units: Crore, Lakh, Thousand, Hundred

Converts any integer (up to crores and beyond)

Simple, readable output structure

Handles special cases like:

Numbers below 20

Tens and ones separation

“and” insertion for hundreds

Modular design with reusable functions

🧠 Concepts Used

Recursion for number decomposition

Integer division & modulo operations for digit grouping

String concatenation for structured output

Logical flow control for exceptions

🧩 Example Outputs
Input	Output
0	zero
7	seven
45	forty five
100	one hundred
1205	one thousand two hundred and five
1234567	twelve lakh thirty four thousand five hundred and sixty seven
🚀 How to Run

Clone this repository

git clone https://github.com/your-username/number-to-words-indian.git


Navigate to the folder

cd number-to-words-indian


Run the Python script

python number_to_words.py

💬 Note

This logic seems simple, but once you start implementing it, it gets progressively complex with exceptions and recursion flow.
It’s an excellent problem to strengthen your logical thinking and Python fundamentals.

💡 Want to Take It Further?

Try building this logic in other programming languages (like C++, Java, or JavaScript) or explore ways to make it more optimal or modular.
Feel free to share your version or open a pull request!

🧑‍💻 Author

Akshith Kendyala
