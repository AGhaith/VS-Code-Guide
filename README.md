# VSCode Setup Guide

## What is an IDE vs. a Text Editor?

- **IDE (Integrated Development Environment)**: A full software suite with built-in tools for coding, debugging, and compiling (e.g., PyCharm, Rider).
- **Text Editor**: A lightweight program for writing and editing code with fewer built-in tools (e.g., Notepad, VSCode).

## Why Use VSCode?

1. Lightweight and doesn’t use as much RAM as other IDEs.
2. Supports many programming languages: C, C++, C#, Java, Python, SQL, JavaScript, and more.
3. Tons of useful **extensions** for debugging, themes, and extra features.
4. FREE and works on Windows, Mac, and Linux, meaning you won’t need to adjust to a new tool if you switch platforms.

---

## Step 1: Download and Install VSCode

1. Go to [VSCode’s official website](https://code.visualstudio.com/).
2. Click **Download for Windows / Mac / Linux** (it detects your OS automatically).
3. Open the downloaded file and follow the installation instructions.
4. Launch **VSCode** after installation.

---

## Step 2: Setting Up VSCode

### 1️⃣ Install Extensions

To use VSCode for any programming language, you will need its corresponding extension:

#### Language-Specific Extensions:

- **Python** (for Python development)
- **C/C++** (for C and C++ development)
- **Java Extension Pack** (for Java)
- **C# Dev Kit** (for C#)
- **SQL Server** (for SQL databases)

#### Quality-of-Life Extensions:

- **Prettier - Code Formatter** (for clean, formatted code)
- **Bracket Pair Colorizer** (makes nested brackets easier to read)
- **Code Spell Checker** (helps prevent typos in code)
- **Error Lens** (highlights errors inline)

### 2️⃣ Customize Your Theme

You can customize your VSCode theme and even download new themes from the Extensions tab (Ctrl+Shift+X).

- Go to **File → Preferences → Color Theme**
- Choose a theme you like (e.g., Dark+, Light+, or download one from the extensions).

### 3️⃣ Set Up Auto-Save

- Go to **File → Preferences → Settings**
- Search for **Auto Save** and enable it.

---

## Step 3: Writing Your First Code

### Understanding the Difference Between a File and a Folder

- A **file** is an individual document, like a Word document, a music file, or a program (e.g., Spotify, WhatsApp).
- A **folder** is a container that holds files and other folders.

💡 **Tip**: When writing code, always create a new file and place it in a suitable folder so you can easily find it later. You can organize folders by year, semester, or topic — JUST DON'T LEAVE EVERYTHING ON YOUR DESKTOP OR IN RANDOM PLACES!!!!

### **Python Example**

Let’s assume you have installed the Python extension and are ready to write code.

1. Open VSCode and navigate to the folder where you want to create your file.
2. Click **New File** → Name it anything you want, for example, `file.py`.
3. Then start writing your code, for example:
   ```python
   print("Hello, World!")
   ```
4. Save the file and run it in the terminal.

---

## Step 4: Understanding Basic Terminal Commands

To navigate and manage files through the terminal, you need to understand a few basic commands:

- **`cd <folder>`** – Change directory (move into a folder).
- **`cd .`** – Stays in the current directory (does nothing).
- **`cd ..`** – Moves up one level to the parent directory.
- **`ls`** (List) – Displays all files and folders in the current directory.
  - **`ls`** works on Windows if you use Git Bash or PowerShell.
  - On Command Prompt, use **`dir`** instead.

### ⚡ Pro Tip: Open VSCode Instantly from the Terminal

Instead of manually opening VSCode and searching for your project, just navigate to your folder using `cd`, then type:

```sh
code .
```

This instantly launches VSCode in the current folder—no extra clicks needed. Try it and save yourself time!
