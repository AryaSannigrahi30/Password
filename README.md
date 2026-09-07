# 🔐 Password Generator

A simple and beginner-friendly Password Generator built using Python. This project generates a random password based on the length entered by the user. The generated password contains a combination of uppercase letters, lowercase letters, numbers, and special characters.

## 📌 Features

- Generates random passwords.
- Allows the user to choose the password length.
- Includes uppercase letters (A-Z).
- Includes lowercase letters (a-z).
- Includes numbers (0-9).
- Includes special characters.
- Simple and easy-to-use command-line interface.
- Beginner-friendly Python project.

## 🛠️ Technologies Used

- Python
- Random Module
- String Module

## 📂 Project Structure

Password-Generator/
│
├── password_generator.py
└── README.md

## ▶️ How to Run

Make sure Python is installed on your computer. Clone the repository using the following command:

git clone https://github.com/your-username/Password.git

Open the project folder:

cd Password

Run the Python program:

python password.py

Enter the desired password length when prompted. The program will generate and display a random password.

## 💻 Example Output

Enter password length: 10

Generated Password: aB7@kP2#xQ

The generated password will be different each time because the characters are selected randomly.

## 🧠 How It Works

The program first asks the user to enter the required password length. It then creates a collection of uppercase letters, lowercase letters, numbers, and special characters using Python's string module. The random.choice() function randomly selects characters from this collection. A loop continues selecting characters until the password reaches the length specified by the user. Finally, the generated password is displayed on the screen.

## 🎯 Purpose

The purpose of this project is to create a simple password generator while practicing basic Python programming concepts such as user input, variables, strings, loops, modules, and random character selection.

## 📚 Learning Outcome

Through this project, I learned how to use Python's built-in modules, take input from users, work with strings, use loops, and generate random values. This project also helped me gain practical experience in developing a simple command-line application using Python.

## 🚀 Future Improvements

The project can be improved in the future by adding password strength checking, allowing users to select specific character types, generating multiple passwords at once, adding different password security levels, and creating a graphical user interface (GUI).

## 🙏 Acknowledgement

This project was created as part of a Python Internship Task. It helped me understand and practice fundamental Python programming concepts through a practical project.

## 👨‍💻 Author

Arya Sannigrahi

CSE Student
