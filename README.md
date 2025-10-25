📝 Simple Notepad

A lightweight text editor built using Qt Framework (C++).
Supports basic file operations like New, Open, Save, and Exit, with a clean interface powered by QTextEdit.

✨ Features

📄 New File — Clears the editor to start fresh.

📂 Open File — Opens existing .txt or text-based files using QFileDialog.

💾 Save File — Saves current content to a chosen location.

🚪 Exit Application — Gracefully closes the editor.

⚠️ Error Handling — Displays message boxes for failed read/write operations.

🧠 Central Editor — Built with QTextEdit for smooth typing and formatting.

📂 Project Structure
Simple_Notepad/
├── SimpleNotepad.pro        # Qt project file
├── main.cpp                 # Entry point
├── notepad.h                # Header for Notepad class
└── notepad.cpp              # Implementation file

🔧 Requirements

Qt Creator

Qt 5.x or Qt 6.x SDK

C++ compiler: MinGW / MSVC

🚀 How to Run

Open Qt Creator

Go to File → Open Project...

Select SimpleNotepad.pro

Configure a Qt kit (if needed)

Click Build → Run

📸 Output

A clean GUI window with:

Menu bar: File → New / Open / Save / Exit

Central text area using QTextEdit

Error dialogs when file operations fail

🧩 Future Enhancements

🧾 Add Find & Replace

🪶 Support Font & Color customization

📑 Add Recent Files list

☁️ Optional: Auto-Save and Cloud Sync

🏷️ Tags

#cpp #qt #gui #texteditor #desktopapp #qtcreator

🧑‍💻 Author

Deepjyoti Das
🔗 https://www.linkedin.com/in/deepjyotidas1

💻 GitHub
