# VS Code Setup Guide: Gemini CLI & GitHub Copilot

This guide provides instructions on how to set up and use the Gemini CLI and GitHub Copilot within Visual Studio Code.

---

## Part 1: Setting up Gemini CLI in VS Code

The Gemini CLI is a powerful command-line tool that can be used directly from within VS Code's integrated terminal.

### Prerequisites

*   You have already installed the Gemini CLI on your system.
*   You have Visual Studio Code installed.

### Steps

1.  **Open VS Code.**
2.  **Open the Integrated Terminal:** You can open the terminal by going to the top menu and selecting `Terminal` > `New Terminal`, or by using the shortcut `` ` `` (backtick).
3.  **Start the Gemini CLI:** In the terminal, you can start the Gemini CLI by running the `gemini` command. If you have a specific project, navigate to your project's directory first:
    ```bash
    cd /path/to/your/project
    gemini
    ```
4.  **Using Gemini:** You can now interact with the Gemini CLI as you would in any other terminal. You can ask it to read files, write code, run commands, etc. The integrated terminal allows you to easily switch between your code and the Gemini CLI.

### Tips for a Better Workflow

*   **Split Terminal:** You can have multiple terminals open at once. For example, you could have one terminal running the Gemini CLI and another for running build commands or tests.
*   **Editor and Terminal Side-by-Side:** You can drag the terminal to the side to have your code and the Gemini CLI visible at the same time.

---

## Part 2: Setting up GitHub Copilot in VS Code

GitHub Copilot is an AI pair programmer that offers intelligent code completions and suggestions.

### Prerequisites

*   You have a GitHub account.
*   You have a subscription to GitHub Copilot (it's a paid service, but there's a free trial).
*   You have Visual Studio Code installed.

### Steps

1.  **Install the Extension:**
    *   Open VS Code.
    *   Go to the Extensions view by clicking on the Extensions icon in the Activity Bar on the side of the window or by pressing `Cmd+Shift+X`.
    *   Search for "GitHub Copilot".
    *   Click "Install" on the official extension by GitHub.

2.  **Authorize VS Code:**
    *   After installation, you'll be prompted to sign in to GitHub.
    *   A dialog box will appear asking you to sign in. Click "Sign in to GitHub".
    *   Your web browser will open with a GitHub device activation page.
    *   Authorize VS Code to access your GitHub account.

3.  **Using Copilot:**
    *   Once authorized, Copilot will be active. You can start coding, and it will automatically provide suggestions as you type.
    *   You can accept a suggestion by pressing `Tab`.
    *   You can cycle through alternative suggestions by pressing `Option+]` (or `Alt+]` on Windows/Linux).
    *   You can trigger Copilot manually by pressing `Ctrl+Enter` to open a new tab with multiple suggestions.

### Tips for Using Copilot Effectively

*   **Write good comments:** Copilot uses comments to understand the context of what you're trying to do. Writing a clear comment like `// function to fetch user data from an API` can help Copilot generate the right code.
*   **Be specific with function names:** A good function name like `function calculateSalesTax(price, location)` will give Copilot more context than a generic name like `function calc()`.
*   **Review suggestions:** Always review Copilot's suggestions carefully. It's a powerful tool, but it's not perfect and can sometimes generate incorrect or insecure code.

---
