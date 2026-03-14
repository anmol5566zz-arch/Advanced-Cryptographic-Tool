# 🛡️ NEXUS Cryptographic Laboratory

Welcome to the **NEXUS Cryptographic Laboratory**—an advanced, browser-based encryption simulator and cryptanalysis research tool. 

Think of this tool as a high-tech digital safe for your secret messages or files. Instead of just putting one lock on your safe, NEXUS allows you to build a custom security "assembly line" to scramble, hide, and lock your data using multiple cryptographic layers.

## ✨ Key Features

* **🧩 Modular Encryption Pipeline:** Build custom encryption workflows by stacking native algorithms (AES-GCM, AES-CTR) with simulated ciphers (ChaCha20), scrambling techniques, noise injection, and hashing layers.
* **🔒 100% Client-Side & Offline:** NEXUS is a single-file application. It uses the browser's native Web Crypto API. No data is ever sent to a server, meaning it is completely private and immune to network interception.
* **📊 Advanced Cryptanalysis Models:** Test the strength of your encryption in real-time with visual mathematical modeling:
  * **Shannon Entropy Scoring & Heatmap:** Visualize the randomness of your ciphertext.
  * **Byte Frequency Histogram:** Ensure your data output is indistinguishable from random noise.
  * **Markov Transition Matrix:** Detect hidden structural patterns in byte sequences.
  * **Strict Avalanche Criterion (SAC):** Automatically flip a single input bit to measure the resulting cryptographic cascade.
  * **Elliptic Curve (ECC) Geometry:** Interactive mathematical graphing of $y^2 = x^3 + ax + b$.
* **💻 Cyberpunk UI:** A responsive, tactical, military-grade console aesthetic. 

## 🚀 Getting Started

Because NEXUS is entirely self-contained, getting started takes less than 5 seconds. No Node.js, databases, or web servers required.

### Option 1: Run Locally (Offline)
1. Download or clone this repository.
2. Double-click the `index.html` file to open it in any modern web browser.
3. You are now running the lab securely and offline!

### Option 2: Host via GitHub Pages
1. Fork or upload `index.html` to a new repository.
2. Go to your repository **Settings** > **Pages**.
3. Set the source branch to `main` and save.
4. Your lab is now hosted live on your personal GitHub Pages URL!

## 🛠️ How to Use

1. **Input Data:** Type a secret message or drag-and-drop a file into the I/O panel.
2. **Set a Master Key:** Enter a strong password (the built-in entropy meter will grade your password's strength).
3. **Build Your Pipeline:** Use the center console to add encryption and transformation layers. Drag to reorder them. 
4. **Compile & Execute:** Click "Initialize Compilation". The engine will run your data through every layer sequentially.
5. **Analyze:** Check the bottom Cryptanalysis tier to view the mathematical strength of your resulting ciphertext.

## ⚙️ Tech Stack

* **HTML5 & CSS3:** For structure and the custom cyberpunk UI.
* **Vanilla JavaScript:** Core logic, state management, and math rendering.
* **Web Crypto API:** For hardware-accelerated, secure execution of symmetric ciphers (AES) and hashing (SHA).
* **HTML5 Canvas:** For high-performance rendering of the Markov matrix, heatmaps, and ECC graphs.

## ⚠️ Security Disclaimer

While NEXUS utilizes the native, cryptographically secure Web Crypto API for its core AES operations, the modular "simulated" layers (e.g., XOR scrambling, Noise Injection, ChaCha20 simulations) are designed for **educational, experimental, and visualization purposes**. Do not use simulated layers alone to protect highly sensitive real-world data without a native AES layer included in your pipeline.

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
