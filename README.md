# Vibe-coding-web-page-lab1
I am starting to Vibe code.<br>
sampleWebPage- Used Claude AI to create a web page where the button clicked tells you that it works.

## How to Use Claude Pro Models in Visual Studio Code

You can use Claude Pro models directly inside VS Code through **GitHub Copilot**. Follow the steps below:

### Prerequisites
- [Visual Studio Code](https://code.visualstudio.com/) installed
- A **GitHub Copilot** subscription (Individual, Business, or Enterprise)
- Note: A separate Claude Pro (Anthropic) subscription is **not required** — GitHub Copilot provides access to Claude models as part of the Copilot subscription.

### Steps

1. **Install the GitHub Copilot extension**
   - Open VS Code and go to the Extensions panel (`Ctrl+Shift+X` / `Cmd+Shift+X`).
   - Search for **"GitHub Copilot"** and click **Install**.
   - Also install **"GitHub Copilot Chat"** for the chat interface.

2. **Sign in to GitHub**
   - After installation, click the Accounts icon in the bottom-left corner of VS Code.
   - Select **"Sign in with GitHub"** and complete the browser authentication flow.

3. **Select a Claude model in Copilot Chat**
   - Open Copilot Chat with `Ctrl+Alt+I` (Windows/Linux) or `Cmd+Option+I` (macOS), or click the Copilot Chat icon in the sidebar.
   - Click the **model picker** (shown as the current model name, e.g. "GPT-4o") at the top of the chat panel.
   - Choose a **Claude model** from the list (e.g. `claude-sonnet-4`, `Claude 3.5 Sonnet`).

4. **Start Vibe Coding with Claude**
   - Type your prompt in the chat box, for example:
     > *"Create an HTML page with a button that shows an alert when clicked."*
   - Claude will generate the code and you can apply it directly to your files.

### Tips
- Use **Copilot Edits** (`Ctrl+Shift+I`) to let Claude make multi-file edits across your project.
- You can switch between Claude and other models (GPT-4o, o3, etc.) at any time using the model picker.
- For inline code completions, Claude models are used automatically when selected as the active model.

### References
- [GitHub Copilot documentation](https://docs.github.com/en/copilot)
- [Changing the AI model for Copilot Chat](https://docs.github.com/en/copilot/using-github-copilot/asking-github-copilot-questions-in-your-ide)
