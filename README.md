# GhostVault: Open-Source Anonymous Messenger

**English** · [Русский](README.ru.md)

**GhostVault** is an open-source anonymous messenger that gives users a secure space to communicate, with full control over their data and connections.

🔗 **[Download GhostVault](https://github.com/k1y0miiii/GhostVault-Open-Source-Anonymous-Messenger/releases/tag/v1.0.0)**

## 🚀 Key Features

- **Connect to your own server:** After installation, the app automatically initializes the tables and data it needs so you can start right away.
- **Flexible encryption settings:** Change encryption keys directly from the app's interface for extra security (coming soon...).
- **Interactive UI:** Convenient registration, login, and account-management forms make the app simple and intuitive to use.
- **Security and privacy:** Built with protecting users' conversations and data as the top priority.
- **Shared database access:** Grant other users access to your database when needed. Once you've connected and created a database, you can share an access key. Click the **[`Connect to database`](#)** button, copy the encrypted key, and pass it to other users.


## 🛠️ Technologies

- **Python** — application logic.
- **PySimpleGUI** — graphical user interface.
- **PostgreSQL** — database management.

## 🏁 Getting Started

### 📥 Installation

1. **Download and install the app:**
   - Go to the [Releases](https://github.com/k1y0miiii/GhostVault-Open-Source-Anonymous-Messenger/releases/tag/v1.0.0) section of the repository on GitHub.
   - Download the latest release, `GhostVaultSETUP.exe`.
   - Run the installer and follow the instructions to install it on your computer.

### 🖥️ Development and Contributing

2. **Clone the repository:**
   - Make sure Git is installed on your machine.
   - Open a terminal and run:
     ```bash
     git clone https://github.com/k1y0miiii/GhostVault-Open-Source-Anonymous-Messenger.git
     ```

3. **Install the dependencies:**
   - Make sure Python is installed.
   - In the project directory, run:
     ```bash
     pip install -r requirements.txt
     ```

4. **Set up your development environment:**
   - An IDE such as **PyCharm** or **Visual Studio Code** is recommended.

5. **Run and test the app:**
   - In the terminal, run:
     ```bash
     python GhostVault.py
     ```

## 🔧 Building an EXE

If you need to compile the project into a Windows `.exe`, use **PyInstaller**.

**Install PyInstaller:**

```bash
pip install pyinstaller
```

**Run the following command to build the `.exe`:**

```bash
pyinstaller --onefile --noconsole --icon="icon.ico" \
--add-data "ghostvault.png;." \
--add-data "message_in_dialog.mp3;." \
--add-data "avatar.png;." \
--add-data "database_config.db;." \
GhostVault.py
```

After a successful build, the executable will be in the `dist/` folder.


### 🤝 Contributing

6. **Open a Pull Request:**
   - Create a new branch for your changes:
     ```bash
     git checkout -b feature/your-branch-name
     ```
   - After making changes, commit and push them:
     ```bash
     git add .
     git commit -m "Description of your changes"
     git push origin feature/your-branch-name
     ```
   - Open a Pull Request on GitHub and describe what you changed.

## 📫 Contact

If you have suggestions or questions, please open a thread in the **Issues** section on GitHub or email us at [email](mailto:ghostvaultmessenger@gmail.com).

## 📄 License

This project is distributed under the **MIT** license — see the [LICENSE](LICENSE) file in the repository for details.

---

**GhostVault** aims to deliver maximum security and a comfortable communication experience. We welcome any contribution to the project and appreciate your feedback and suggestions!
