Right-Aligned Pyramid Pattern in Python

Overview
A simple Python script that demonstrates the use of for loops and string multiplication to generate a right-aligned triangle pattern.

🚀 How it Works
The script iterates through a range based on the number of rows. For each row, it calculates:

Spaces: (rows - i) spaces to push the asterisks to the right.

Stars: i asterisks to form the triangle body.

Code Snippet
Python

rows = 5

for i in range(1, rows + 1):
    # Prints spaces followed by stars
    print(" " * (rows - i) + "*" * i)
📊 Visual Output
When rows = 5, the console will display:

Plaintext

    *
   **
  ***
 ****
*****

🛠️ Customization

You can easily modify the rows variable to increase or decrease the height of the triangle, or change the "*" character to any other symbol (like # or @) to change the look.

📝 License

This project is open-source and available under the MIT License.

<img width="503" height="784" alt="image" src="https://github.com/user-attachments/assets/84751889-f9c4-4f42-a107-6c07cbae8a4c" />
