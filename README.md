# 🔥 FLAMES Game - Python Implementation
This is a simple Python program to determine the relationship status between two people using the classic FLAMES game.

🚀 What is FLAMES?
FLAMES is an acronym for:

Friends

Love

Affection

Marriage

Enemy

Siblings

This fun game counts the number of unique characters between two names (after removing common characters) and uses that count to cyclically eliminate options in the FLAMES list until one remains.

📂 How to Use
Run the Python script.

Enter two names when prompted.

The script will display the relationship status based on the FLAMES logic.

📄 Example
yaml
Copy code
Player 1 name: Alice
Player 2 name: Bob
Relationship status: Enemy
🧠 How It Works
Convert names to lowercase and remove spaces.

Remove common characters from both names (one occurrence at a time).

Count the total remaining characters.

Use that count to cyclically eliminate options from the FLAMES list.

Output the final relationship result.

🧪 Requirements
Python 3.x

▶️ Running the Program
bash
Copy code
python flames_game.py
(Replace flames_game.py with your actual filename.)

📌 Notes
Handles duplicate characters correctly.

Avoids modifying lists while iterating directly.

Works for all English names.
