# Banking System - Java Swing Project

## Description
The Banking System is a Java Swing application that simulates basic banking operations. It provides a user-friendly interface for managing accounts, transactions, and other essential banking functions.

## Features
- Account creation and management
- Deposit and withdrawal transactions
- Balance inquiry
- Transaction history
- User-friendly GUI with Java Swing

## Screenshots
![Screenshot 1](screenshot/1.png)
![Screenshot 2](screenshot/2.png)

## Technologies Used
- Java
- Java Swing for GUI

## Installation & Running

### Option 1: Eclipse IDE (Recommended)

1. Clone the repository:
   ```bash
   git clone https://github.com/orgito1015/BankingSystem-Swing-Java-Edition.git
   ```
2. Open Eclipse and go to **File → Import → Existing Projects into Workspace**.
3. Select the cloned repository folder as the root directory and click **Finish**.
4. Eclipse will automatically build the project. Make sure there are no errors in the **Problems** tab.
5. In the **Package Explorer**, open `src/Application.java`.
6. Right-click on `Application.java` → **Run As → Java Application**.

> **Default login credentials:** Username: `admin` / Password: `admin`

### Option 2: Command Line

1. Clone the repository:
   ```bash
   git clone https://github.com/orgito1015/BankingSystem-Swing-Java-Edition.git
   cd BankingSystem-Swing-Java-Edition
   ```
2. Compile the source files:
   ```bash
   mkdir -p bin
   javac -d bin src/Application.java src/Bank/*.java src/Data/*.java src/Exceptions/*.java src/GUI/*.java
   ```
3. Copy the image resource:
   ```bash
   cp -r src/img bin/img
   ```
4. Run the application:
   ```bash
   java -cp bin Application
   ```

## Usage
1. Launch the application — the Login screen will appear.
2. Enter `admin` as both the username and password, then click **Login**.
3. Use the main menu to add accounts, deposit, withdraw, or view the account list.

## Contribution
Contributions are welcome! If you'd like to contribute to the project, please follow these steps:

1. Fork the repository
2. Create a new branch (git checkout -b feature/new-feature)
3. Commit your changes (git commit -m 'Add new feature')
4. Push to the branch (git push origin feature/new-feature)
5. Create a pull request

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
- Thanks to Java for the programming language.
- Special thanks to Java Swing for the GUI components.
- Feel free to customize the content according to your project's specific details. Add more sections or information as needed.
