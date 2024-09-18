# NET ARMOR - Security and Networking Toolkit

NET ARMOR is a security and networking tool with a splash screen introduction and two main functionalities: **Community Post** and **Toolkit**. The **Community Post** section allows users to create and read posts, while the **Toolkit** section offers several utilities like a password manager, password generator, password strength checker, IP lookup, and encryption/decryption features.

## Features
- **Splash Screen**: Displays a loading screen while the main window is prepared.
- **Custom Background**: Custom background images for different windows.
- **Community Post**: 
  - Create and save community posts.
  - Read previously saved posts.
  - Clear input fields.
- **Toolkit**: Offers the following functionalities:
  - Password Manager
  - Password Generator
  - Password Strength Checker
  - IP Lookup
  - Encryption/Decryption

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/Net-Armor.git
    cd NetArmor
    ```

2. **Install dependencies**:
    Ensure you have `PyQt5` installed. If not, install it using:
    ```bash
    pip install pyqt5
    ```

3. **Add background images**:
    Make sure you have the following image files in the project directory:
    - `loading screen3.jpg` (for the splash screen)
    - `homepage1.jpg` (for the main window background)
    - `toolkit back.jpg` (for the toolkit window background)

4. **Run the application**:
    ```bash
    python main.py
    ```

## How to Use

### Splash Screen and Main Window
- When you run the application, a splash screen appears displaying the loading process.
- After the splash screen, the main window appears with two buttons: **Community Post** and **Toolkit**.

### Community Post
- You can create a community post by entering a name and the post content.
- Click **Create Post** to save the post to a text file.
- Use **Read Post** to view all previously saved posts.
- **Clear Fields** clears the input fields.

### Toolkit
- The toolkit contains several security and networking utilities:
  - **Password Manager**: Manage your passwords securely.
  - **Password Generator**: Generate strong passwords.
  - **Password Strength Checker**: Check the strength of a password.
  - **IP Lookup**: Get information about an IP address.
  - **Encryption/Decryption**: Encrypt or decrypt text data.
  
  Each tool can be accessed by clicking the respective buttons.

### Quit Confirmation
- When attempting to close the application, a confirmation dialog will appear to ensure you want to quit.

## Dependencies
- Python 3.x
- PyQt5

## Contributing
Feel free to contribute to this project by submitting a pull request or reporting issues.

## License
This project is licensed under the MIT License.
