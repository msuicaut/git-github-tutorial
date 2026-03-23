# Git & GitHub — A Beginner's Guide

A visual, step-by-step tutorial for teams collaborating on training content. Covers repositories, branching, pull requests, and the full Git workflow — no prior experience needed.

---

## Prerequisites

Please complete the following steps **before the session**. Each one should take no more than 10 minutes.

> **Working on an institutional or work-managed computer?**
> Some organisations restrict software installation on their machines. If you are unable to install Git or VS Code, please contact your IT department in advance and let them know you need these tools for a training session. Allow a few extra days in case approval is required. If installation is not possible before the session, please let the facilitator know so alternative arrangements can be made.

---

### 1. Install Git

Git is the version control tool that runs on your computer.

**Mac**

1. Open the **Terminal** app (search for it in Spotlight with `Cmd + Space`)
2. Type `git --version` and press Enter
3. If Git is not installed, macOS will prompt you to install the **Xcode Command Line Tools** — click Install and follow the prompts
4. Once complete, run `git --version` again to confirm it worked — you should see something like `git version 2.x.x`

**Windows**

1. Go to [https://git-scm.com/download/win](https://git-scm.com/download/win)
2. Download the installer and run it
3. Accept the default options throughout the installation wizard
4. Once installed, open **Git Bash** (search for it in the Start menu) and run `git --version` to confirm

**Linux (Ubuntu/Debian)**

1. Open the Terminal
2. Run `sudo apt update && sudo apt install git`
3. Confirm with `git --version`

---

### 2. Create a GitHub Account

GitHub is where you will store and share your Git repositories online.

1. Go to [https://github.com](https://github.com)
2. Click **Sign up** and follow the steps to create a free account
3. Verify your email address when prompted
4. You do not need to pay for any plan — the free tier is sufficient for this tutorial

> Already have a GitHub account? You're all set.

---

### 3. Ensure Access to a Text Editor

A text editor is where you will edit files during the demo. Your computer already has a basic one built in — **Notepad** on Windows and **TextEdit** on Mac — and either is perfectly fine for this session.

If you would like a more feature-rich editor with built-in Git support, we recommend **Visual Studio Code** (VS Code), which is free and works on all platforms.

1. Go to [https://code.visualstudio.com](https://code.visualstudio.com)
2. Click **Download** — the site will detect your operating system automatically
3. Run the installer and follow the prompts
4. Open VS Code and confirm it launches correctly

> VS Code is optional. If you are on an institutional machine and cannot install software, your built-in editor is sufficient for this tutorial.

---

### 4. Set Up a Working Directory

During the demo you will be creating and editing files from the terminal. To avoid confusion about where your files are, please create a dedicated practice folder on your Desktop before the session.

**Mac and Linux**

1. Open the **Terminal**
2. Run the following commands one at a time, pressing Enter after each:
   ```
   cd ~/Desktop
   mkdir git-practice
   ```
3. You should now see a folder called `git-practice` on your Desktop

**Windows**

1. Open **Git Bash** (installed with Git in step 1)
2. Run the following commands one at a time, pressing Enter after each:
   ```
   cd ~/Desktop
   mkdir git-practice
   ```
3. You should now see a folder called `git-practice` on your Desktop

> For the rest of the session, this is your working directory — the folder where all your files will live. When the tutorial asks you to run a command, make sure you are inside this folder by running `cd ~/Desktop/git-practice` first.

---

### 5. Create a Repository on GitHub

A repository is the folder where GitHub stores and tracks your project. You will need one set up before the session.

1. Log in to [https://github.com](https://github.com)
2. Click the **+** icon in the top-right corner and select **New repository**
3. Fill in the details as follows:
   - **Repository name:** `git-practice`
   - **Description:** leave blank for now
   - **Visibility:** select **Public**
   - **Initialise this repository with:** tick **Add a README file**
   - Leave all other options as their defaults
4. Click **Create repository**
5. You should now see your new repository page at `https://github.com/yourusername/git-practice`

> **Why Public?** A public repository is visible to anyone on the internet, but only you can make changes to it. For this tutorial, Public is required if you plan to use GitHub Pages to view the tutorial in a browser. You can always change the visibility to Private afterwards.

> **Why initialise with a README?** This ensures the repository is not empty, which makes it easier to clone to your local machine in the next steps.

---

### Quick checklist

Before the session, make sure you can tick all five:

- [ ] Running `git --version` in your terminal returns a version number
- [ ] You can log in to [github.com](https://github.com)
- [ ] You have a text editor available (built-in Notepad/TextEdit is fine)
- [ ] A `git-practice` folder exists on your Desktop
- [ ] A `git-practice` repository exists on your GitHub account

---

## About this tutorial

This tutorial is built as a single self-contained HTML file and hosted via GitHub Pages. Open it in any modern browser — no installation required.

**Live tutorial:** [https://yourusername.github.io/your-repo-name](https://yourusername.github.io/your-repo-name)

---

## Additional Resources

This tutorial covers the core Git and GitHub workflow. For deeper learning, including topics such as ignoring files with `.gitignore` and resolving merge conflicts, we recommend:

**Software Carpentry — Version Control with Git**
[https://swcarpentry.github.io/git-novice/](https://swcarpentry.github.io/git-novice/)

Software Carpentry offers free, peer-reviewed lessons designed for researchers and practitioners with little to no prior programming experience.

---

## Development Notes

This tutorial was created by **May Chan** with the assistance of **Claude** (Anthropic), an AI assistant. Claude supported the instructional design, visual layout, HTML and SVG coding, and iterative refinement of diagrams and explanatory text across multiple working sessions.

The pedagogical approach — including the choice of analogies, colour logic, diagram directionality, and novice-friendly language — reflects a collaborative process between the author and the AI.

---

## Questions?

If you run into any issues setting up before the session, please reach out so we can help you get sorted ahead of time.

If you run into any issues setting up before the session, please reach out so we can help you get sorted ahead of time.
