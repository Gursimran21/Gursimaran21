# Gursimaran21

# 100Hires Tools: Installation & Setup Guide

## **How to Install Cursor IDE**

To install the **Cursor IDE** on your desktop, follow these steps:

**Download the Installer:**

**1.** Visit the official [Cursor website](https://cursor.com/).

**2.** Click the **Download** button located at the top-left corner of the homepage.

**3.** On the download page, scroll down to locate the installer specific to your operating system (macOS, Windows, or Linux).

**4.** Select the version that matches your system architecture (e.g., Mac ARM64/x64, Windows x64/ARM64, or the appropriate Linux format) and click the download icon.

**Run the Installer:**

**1.** Once the download completes, locate the file in your browser's download manager or your computer's "Downloads" folder.

**2.** Double-click the installer file (e.g., ```CursorUserSetUp-x64-x.x.x.exe```) to launch the setup wizard.

**Complete the Installation:**

**1.** **License Agreement:** Read the agreement, select "I accept the agreement," and click **Next**.

**2.** **Destination:** Keep the default installation location and click **Next**.

**3.** **Start Menu:** Keep the default settings and click **Next**.

**4.** **Additional Tasks:** You may choose to "Create a desktop icon" for easier access. The default selections (registering file types and adding to PATH) are recommended. Click **Next**.

**5.** **Install:** Review your settings and click **Install**.

**6.** **Finish:** Once the installation progress bar completes, click **Finish** to close the setup wizard.
    
## **How to add Claude Code extension in Cursor**

To add the **Claude Code** extension in Cursor, follow these steps:

**Install the Claude Code Extension**

**1.** Open Cursor and navigate to the Extensions view by clicking the square icon in the sidebar or using the shortcut ```Ctrl+Shift+X``` (Windows/Linux) or ```Cmd+Shift+X``` (Mac).

**2.** In the search bar, type **Claude Code**.

**3.** Locate the official **Claude Code** extension by Anthropic and click **Install**.

## **How to Log In to the Claude Code extension in Cursor**

To log in to the **Claude Code extension** within the Cursor IDE, follow these steps:

**Log In Claude Code and Connect**

**1. Open the Claude Code Panel**

   Once you have installed the "Claude Code" extension from the Cursor/VS Code marketplace, you need to open its interface:

- **Via Sidebar:** Click the **Spark icon** (Claude Code icon) in the left-hand Activity Bar.
  
- **Via Toolbar:** With a file open, look for the Spark icon in the top-right corner of the editor.
  
- **Via Command Palette:** Press ```Cmd+Shift+P``` (Mac) or ```Ctrl+Shift+P``` (Windows/Linux),   type **"Claude Code"**, and select an option like **"Open in New Tab"**.

**2. Sign In to Claude Code**

- The first time you open the Claude Code panel, a **"Sign in"** screen will appear automatically.
  
- Click the **Sign in** button.
  
- This will open your default web browser, where you will be prompted to authorize the connection to your Anthropic account.
  
- Complete the authentication in your browser. Once successful, return to Cursor, and you should be logged in.

## **Troubleshooting Common Issues while Signing In Claude Code**

- **If you don't see the sign-in screen:** If you see a "Not logged in" message, try opening the Command Palette (```Cmd/Ctrl+Shift+P```) and running **"Developer: Reload Window"**. This often forces the extension to re-check your status and trigger the sign-in prompt.

- **If you are prompted to sign in repeatedly:**

    - Ensure you have **not** accidentally disabled the login prompt in your settings. Check Cursor's **Settings (UI)**, search for ```claudeCode.disableLoginPrompt```, and ensure it is **unchecked** (false).

    - If you have an ```ANTHROPIC_API_KEY``` set in your terminal environment, Cursor might not be inheriting it correctly. Try launching Cursor from your terminal by typing ```cursor .``` to ensure it picks up your environment variables.

- **Distinction between "Claude Code" and Cursor's Native AI:** Note that "Claude Code" is a separate extension from Anthropic. If you are just trying to use Claude models (like Claude 3.5 Sonnet) within Cursor's standard chat or composer, you do not need to "log in" to Claude Code; you simply select the model in Cursor’s native model picker.

## **How to add Codex extension in Cursor**

To add the **OpenAI Codex** extension in Cursor, follow these steps:

**Install the Codex Extension**

**1.** Open the Cursor IDE on your computer.

**2.** Navigate to the **Extensions** view by clicking the extensions icon in the Activity Bar (usually on the left) or by pressing ```Ctrl+Shift+X (Cmd+Shift+X``` on Mac).

**3.** In the search bar at the top of the Extensions view, type **"Codex"**.

**4.** Locate the official **"OpenAI Codex"** extension (often titled "Codex: OpenAI coding assistant") and click **Install**. Once installed, you may need to restart Cursor or click the reload button if prompted.

## **How to Log In to the Codex extension in Cursor**

To log in to the **Codex extension** within the Cursor IDE, follow these steps:

**Log In Codex and Connect**

**1. Open the Codex Panel**

- Look for the **Codex icon** that should now appear in your Activity Bar (or click the triple dot menu ```...``` to find "Open Codex").
  
- Click on the icon to open the Codex panel. You will be prompted with a **"Sign in"** button.

**2. Sign In to Codex**
   
- Select **Sign in with ChatGPT.** This will open your default web browser.
  
- Log in to your OpenAI/ChatGPT account. Most ChatGPT plans (Free, Plus, Pro, etc.) include usage credits for Codex.
  
- After successful authentication in the browser, you may be redirected back to Cursor, where the Codex interface will now be active.

**3. Alternative Login (API Key)**

   If you prefer not to use browser-based login, you can manually authenticate using an **OpenAI API key:**
   
  - Open the Codex settings within the extension (click the gear icon or "Settings").
    
  - Enter your API Key generated from your OpenAI API Keys dashboard.

## **Troubleshooting Common Issues while Signing In Codex**

If you are using a legacy "Codex" extension for VS Code:

- **Conflict with API Keys:** Many users find that the "Sign in with ChatGPT" OAuth flow can be unstable. If it repeatedly fails or requires re-authentication, the standard workaround is to use an **OpenAI API Key** instead of OAuth. You can set this in the extension's settings by adding your ```OPENAI_API_KEY```.
  
- **Multiple Accounts:** If you are signed into multiple OpenAI/ChatGPT accounts in your browser, try signing out of all of them, restarting your browser, and then initiating the sign-in from VS Code again.
  
- **Extension Conflicts:** Sometimes other AI extensions (like GitHub Copilot or other coding assistants) conflict with Codex's authentication. Try disabling other AI extensions temporarily to see if the sign-in succeeds.

## **References**

**1.** [Cursor IDE: Installation Guide](https://cursor.com/docs/get-started/quickstart).

**2.** [Complete Guide of Claude Code extension in Cursor](https://code.claude.com/docs/en/vs-code).

**3.** [Complete Guide of Codex extension in Cursor](https://developers.openai.com/codex/ide).
