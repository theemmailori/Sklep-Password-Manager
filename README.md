# Sklep Password Manager

**Sklep Password Manager** is a simple password management application built using the Python `tkinter` library. It allows users to store and retrieve passwords for different websites, generate secure passwords, and copy them to the clipboard.

## Features

1. **Password Generation:** You can generate strong and secure passwords with a mix of letters (both uppercase and lowercase), numbers, and symbols.

2. **Password Storage:** Store login information for websites, including website name, email or username, and password.

3. **Password Retrieval:** Retrieve stored passwords for websites when needed.

4. **Data Persistence:** The application stores data in a JSON file called `data.json`, ensuring that your password information is saved even if you close the application.

5. **User-Friendly UI:** The user interface is designed to be simple and intuitive, making it easy to use for all.

## How to Use

1. **Search Password:** Enter the website name in the "Website" field and click the "Search" button to retrieve the stored email/username and password for that website.

2. **Generate Password:** Click the "Generate Password" button to create a secure password. It will be automatically copied to your clipboard and displayed in the "Password" field.

3. **Add Password:** Fill in the "Website," "Email/Username," and "Password" fields, and click the "Add" button to store the login information for a website. The information will be saved in the `data.json` file.

## Getting Started

To run the application, make sure you have Python installed on your computer. You can run the following command to start the application:

```bash
python filename.py
```

Make sure to replace `filename.py` with the actual name of the Python script where you've placed the code.

## Dependencies

The application uses the following Python libraries:

- `tkinter`: The standard Python interface to the Tk GUI toolkit for creating the graphical user interface.

- `pyperclip`: A clipboard module that allows you to copy and paste text to and from the clipboard.

## Data Storage

User data is stored in a JSON file named `data.json` in the same directory as the script. You can back up this file to ensure your password data is not lost.

**Note:** This is a simple password manager meant for educational purposes. For enhanced security, consider using a dedicated password manager software.

## License

This code is provided under an open-source license. You can find the license information in the LICENSE file.

---

Feel free to use and modify this code as needed, but please use it responsibly and ensure the security of your password data.