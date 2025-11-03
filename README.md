# Pitch Rise - Cursor Setup Verification

This repository is used to verify that Pitch Rise students have successfully set up Cursor IDE and can work with Git/GitHub.

## 🎯 How It Works

Students complete the following steps to verify their Cursor setup:

1. **Fork this repository** to your GitHub account
2. **Clone your fork** to your local machine using Cursor
3. **Create a new branch** called `add-verification`
4. **Create a new file** in the `verifications/` folder named `YOUR-USERNAME.txt`
5. **Add your verification code** (provided in your Pitch Rise dashboard) to the file
6. **Commit and push** your changes to your fork
7. **Submit a pull request** to this repository

## 📋 Pull Request Format

**Title:** `Add verification for [YOUR-USERNAME]`

**Description:** Include your verification code from the Pitch Rise dashboard

**Target:** Base repository should be `rogerSuperBuilderAlpha/pitch-rise-verification`, branch `main`

### ✏️ What to Do If Your PR is Missing a Description

If you created a pull request without a description (or need to edit it), you can easily add one:

1. **Go to your pull request** on GitHub
2. **Click the "..." menu** (three dots) next to the PR title
3. **Select "Edit"** from the dropdown menu
4. **Add your verification code** in the description field (e.g., `PITCH-XXXX-XXXX`)
5. **Click "Update"** or "Save" to save your changes

**Note:** The verification system looks for your code in the PR description, so it's important to include it there even if you've already added it to your verification file.

## 🔑 Verification Code Format

Your verification code will look like this:

```
PITCH-XXXX-XXXX
```

Example: `PITCH-A7F3-2K9L`

You can find your unique code in your Pitch Rise dashboard after signing up.

## ✅ Verification Process

Our system automatically:
- Detects new pull requests
- Validates the verification code against your account
- Updates your Pitch Rise dashboard
- Confirms you're ready to continue learning!

This usually happens within **5-30 seconds** of submitting your PR.

## 📁 File Structure

```
pitch-rise-verification/
├── README.md
└── verifications/
    ├── .gitkeep
    └── [your files will be added here]
```

## 🆘 Need Help?

If you're stuck on any step:
- Check the detailed step-by-step guide in your Pitch Rise dashboard
- Make sure you're submitting a PR from YOUR fork to this repository
- Verify your verification code is correct
- Ensure the PR title and description follow the format above
- **Missing a PR description?** See the section above: "What to Do If Your PR is Missing a Description"

## 📚 What You're Learning

By completing this verification, you demonstrate:
- ✅ Ability to use Cursor IDE
- ✅ Understanding of Git basics (fork, clone, branch, commit, push)
- ✅ GitHub workflow knowledge (creating pull requests)
- ✅ Following technical documentation

These are fundamental skills for modern software development!

## 📦 Prerequisites for Next Steps

Before building your first website, you'll need to install Node.js:

### Installing Node.js

Node.js is required to run Next.js applications. Follow these steps:

1. **Visit nodejs.org**
   - Open your web browser and go to [nodejs.org](https://nodejs.org)
2. **Download the LTS (Long Term Support) version** for your operating system
   - The website will automatically detect if you're on Windows, Mac, or Linux
   - LTS versions are recommended for stability and long-term support
3. **Run the Node.js installer**
   - Find the downloaded installer in your Downloads folder (usually named `node-vXX.X.X-x64.msi`)
   - Double-click the installer file to run it
   - Follow the installation wizard, accepting the default settings
   - This will install both Node.js and npm (Node Package Manager)
4. **Verify Node.js installation: `node --version`**
   - **Open your system terminal** (NOT Cursor)
     - **Windows:** Click Start and type "cmd" or "powershell"
     - **Mac:** Press Command+Space and type "terminal"
   - Type `node --version` and press Enter
   - You should see a version number like `v20.x.x` (this confirms Node.js is installed correctly)

5. **Verify npm installation: `npm --version`**
   - In the same system terminal, type `npm --version` and press Enter
   - You should see a version number
   - npm comes bundled with Node.js and is used to install JavaScript packages
   - You can now close this system terminal - we'll use Cursor's terminal for the rest

**Note:** After installing Node.js, you'll also have npm (Node Package Manager) installed, which is used to manage project dependencies.

### Installing Node.js via Docker (Alternative Method)

If you prefer to use Docker, you can run Node.js in a container:

1. **Install Docker first**
   - Docker has specific installation instructions for each operating system
   - Please refer to the official documentation at [docker.com/get-started](https://docker.com/get-started/)

2. **Pull the Node.js Docker image:**
   ```bash
   docker pull node:24-alpine
   ```

3. **Create a Node.js container and start a shell session:**
   ```bash
   docker run -it --rm --entrypoint sh node:24-alpine
   ```

4. **Verify the Node.js version:**
   ```bash
   node -v  # Should print "v24.11.0"
   ```

5. **Verify npm version:**
   ```bash
   npm -v  # Should print "11.6.1"
   ```

**Note:** With Docker, you'll work inside the container. When you exit the container, it will be removed automatically (`--rm` flag). For ongoing development, you may want to install Node.js directly on your system instead.

## 🚀 What's Next?

After verification, you'll continue with:
- Building your first personal website
- Deploying to Vercel
- Creating AI-powered custom projects
- Building a professional portfolio

---

**Note:** This is a practice repository. All pull requests help verify your development environment is working correctly. Welcome to Pitch Rise! 🎉
