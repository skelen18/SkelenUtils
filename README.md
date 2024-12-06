# SkelenUtils

Welcome to **SkelenTools**! This repository contains a collection of tools, tips, and commands that will help you streamline your development workflow. From Git commands to PowerShell scripts, you'll find everything you need to work efficiently with various technologies and platforms.

## 📋 Table of Contents
- [Getting Started](#getting-started)
- [Git Commands](#git-commands)
- [PowerShell Commands](#powershell-commands)
- [Discord Formatting](#discord-formatting)
- [Contributing](#contributing)

## 🚀 Getting Started

This repository is designed to be a quick reference guide for common tasks, programming languages, and tools you use. The content is organized into different sections, with each section dedicated to a specific topic.

### How to Use:
- Navigate through the different sections using the **Wiki** tab for detailed information.
- For quick access to essential commands and tips, check out the relevant sections below.

## 🛠️ Git Commands

This section includes the most frequently used Git commands with detailed examples to help you manage your repositories efficiently.

### Basic Git Commands

- **`git init`** – Initialize a new Git repository
    - **Example**:  
      If you're starting a new project, navigate to your project folder and run:
      ```bash
      git init
      ```
      This command initializes a new Git repository in the current folder.

- **`git add .`** – Stage all changes
    - **Example**:  
      After making changes to your files, run:
      ```bash
      git add .
      ```
      This stages all changes in the directory, preparing them for commit.

- **`git commit -m "message"`** – Commit changes with a message
    - **Example**:  
      After staging your changes, commit them with a meaningful message:
      ```bash
      git commit -m "Add new feature"
      ```
      This command commits the staged changes with a description of what was changed.

- **`git push`** – Push changes to a remote repository
    - **Example**:  
      To upload your local commits to a remote repository (like GitHub):
      ```bash
      git push origin main
      ```
      This command pushes your commits to the `main` branch of the remote repository.

- **`git pull`** – Fetch and merge changes from the remote repository
    - **Example**:  
      To get the latest changes from the remote repository and merge them into your local branch:
      ```bash
      git pull origin main
      ```
      This command fetches changes from the remote `main` branch and merges them into your local `main` branch.

For more detailed information, visit the [Git Wiki](https://github.com/skelen18/SkelenUtils/wiki/Git-Commands).

---

## 💻 PowerShell Commands

This section includes useful PowerShell commands to automate tasks, manage files, and interact with your system more efficiently.

### Basic PowerShell Commands

- **`Get-Help <command>`** – Get help for any command
    - **Example**:  
      If you're unsure about how to use a specific command, you can get help with:
      ```powershell
      Get-Help Get-Process
      ```
      This will show you all the details about the `Get-Process` command, including its syntax and examples.

- **`Get-Process`** – List all running processes
    - **Example**:  
      To list all the running processes on your system, use:
      ```powershell
      Get-Process
      ```
      This will display a list of all the active processes.

- **`Set-ExecutionPolicy RemoteSigned`** – Allow running scripts
    - **Example**:  
      If you want to allow the execution of PowerShell scripts, you can set the execution policy with:
      ```powershell
      Set-ExecutionPolicy RemoteSigned
      ```
      This command allows you to run locally created scripts but requires remote scripts to be signed.

- **`New-Item <path>`** – Create a new file or directory
    - **Example**:  
      To create a new file, you can use:
      ```powershell
      New-Item -Path "C:\Users\YourUsername\Documents\NewFile.txt" -ItemType "File"
      ```
      This will create a new file called `NewFile.txt` in the specified location.

For more detailed PowerShell examples, visit the [PowerShell Wiki](link-to-powershell-wiki).

---

## 🎮 Discord Formatting

Learn how to format your messages in Discord using Markdown. This section provides tips on bold, italic, code blocks, and other text formatting features that will make your messages more readable.

### Text Formatting in Discord

- **Bold**: `**text**`  
    - **Example**:  
      To make your text bold, wrap it in double asterisks:
      ```markdown
      **This is bold text**
      ```
      It will appear as: **This is bold text**

- **Italic**: `*text*` or `_text_`  
    - **Example**:  
      To italicize your text, use single asterisks or underscores:
      ```markdown
      *This is italic text*
      ```
      or
      ```markdown
      _This is italic text_
      ```
      It will appear as: *This is italic text* or _This is italic text_

- **Strikethrough**: `~~text~~`  
    - **Example**:  
      To strike through your text, use double tildes:
      ```markdown
      ~~This is strikethrough text~~
      ```
      It will appear as: ~~This is strikethrough text~~

- **Code Block**: `` `code` `` (for inline) or triple backticks for multi-line code blocks  
    - **Example (inline)**:  
      To format inline code, wrap it in single backticks:
      ```markdown
      `const x = 5;`
      ```
      It will appear as: `const x = 5;`

- **Links**: `[Link Text](URL)`  
    - **Example**:  
      To add a clickable link:
      ```markdown
      [Click here](https://example.com)
      ```
      It will appear as: [Click here](https://example.com)

For more detailed formatting guides, check out the [Discord Wiki](link-to-discord-wiki).

---


## 🤝 Contributing

If you have any useful tools, commands, or tips that you want to share, feel free to contribute! You can fork this repository, add your changes, and submit a pull request.


