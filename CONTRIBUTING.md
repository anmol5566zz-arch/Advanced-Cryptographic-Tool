# Contributing to NEXUS Cryptographic Laboratory

First off, thank you for considering contributing to NEXUS! It's people like you that make the open-source community such an amazing place to learn, inspire, and create.

This document provides guidelines and steps for contributing to the project.

## 🧠 How Can You Contribute?

### 1. Reporting Bugs
If you find a bug or a flaw in the cryptographic logic or UI, please open an issue! Include as much detail as possible:
* Your browser and OS.
* The exact steps to reproduce the bug.
* What you expected to happen vs. what actually happened.
* Any errors shown in the browser console (F12).

### 2. Suggesting Enhancements
Have an idea for a new encryption layer, a new mathematical visualization, or a UI improvement? 
* Open an issue using the "Enhancement" tag.
* Describe how it works and why it would be useful.
* If it involves a new cryptographic algorithm, please link to the relevant documentation or math.

### 3. Submitting Pull Requests (PRs)
Ready to write some code? Awesome! Here is the process:
1. **Fork** the repository to your own GitHub account.
2. **Clone** the project to your local machine.
3. Create a new branch for your feature (`git checkout -b feature/AmazingNewCipher`).
4. Make your changes and test them locally.
5. Commit your changes (`git commit -m 'Add AmazingNewCipher layer'`).
6. Push to the branch (`git push origin feature/AmazingNewCipher`).
7. Open a **Pull Request** against the `main` branch of this repository.

## 💻 Local Development Setup

Because NEXUS is entirely dependency-free, setting up a development environment is incredibly simple:

1. Clone your fork: `git clone https://github.com/YOUR-USERNAME/nexus-crypto-lab.git`
2. Open the folder on your computer.
3. Open `index.html` in your web browser or use a simple tool like VS Code's "Live Server" extension.
4. Edit the HTML, CSS, or JS directly in the file. No build steps, no Node.js, and no `npm install` required!

## 📏 Coding Guidelines

To keep the project clean and accessible:
* **Zero Dependencies:** Please do not add external libraries (no React, jQuery, or external CSS frameworks) unless absolutely necessary and discussed in an issue first. 
* **Web Crypto API:** When implementing real-world cryptographic primitives (like AES or SHA), always use the browser's native `window.crypto.subtle` API rather than writing custom math, to ensure security and performance.
* **Simulations:** If you are adding a "simulated" cipher (like ChaCha20 or experimental obfuscation) for educational purposes, please clearly label it as a simulation in the UI and comments.
* **UI Theme:** Try to match the existing cyberpunk/terminal aesthetic (Dark backgrounds, neon accents, monospace fonts).

## 🤝 Code of Conduct

Please be respectful and constructive in all issues and pull request discussions. We are here to learn and build cool security tools together!
