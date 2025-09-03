
# 🛡️ The TitanPass Project: A Public Archive for Password Security Research

> **Mission:** To provide a continuously updated, large-scale public dataset of algorithmically generated passwords for educational and research purposes. This repository serves as a living resource for understanding password entropy, strength, and the principles of digital credential security.

**Live Tool:** 🌐 **[TitanPass Secure Generator]((https://password-generator.opcelon.workers.dev/))**

---

### 📜 **Project Charter & Philosophy**

The TitanPass Project is founded on a simple principle: **security through understanding**. In an era of constant digital threats, abstract advice is not enough. This repository provides concrete, observable data, allowing students, security professionals, and the public to explore the tangible differences between weak and strong credentials.

Our philosophy is built on three pillars:
1.  **Transparency:** The generation process is open, and its output is publicly archived for analysis.
2.  **Education:** We aim to demystify concepts like entropy and crack times by providing a vast set of real-world examples.
3.  **Responsibility:** We clearly delineate between the public, insecure data in this archive and the private, secure passwords users should generate for themselves using best practices.

---

### ⚠️ **Critical Alert: This is a Public, Insecure Dataset**

The password examples contained within this repository are **PUBLIC, COMPROMISED, and UNSAFE** by design. They exist solely for academic, research, and educational analysis.

-   **DO NOT USE** any password from this repository for any real account.
-   **DO NOT** base your personal passwords on patterns observed here.
-   This archive is a **read-only educational tool**.

Interacting with this repository signifies your understanding and acceptance of these terms. The project maintainers assume no liability for the misuse of this public data.

---

## 🔬 **How to Use This Repository for Learning & Research**

This archive is structured to facilitate learning. By examining the data, you can gain a deep, practical understanding of password security.

### **Step 1: Understand the Data Structure**

-   **`YYYY-MM-DD/` Directories:** Data is organized into daily directories. This chronological structure allows for the analysis of data over time, although the generation algorithm remains consistent.
-   **`password_log.md` Files:** Each file contains batches of generated password examples. These files are periodically updated with new data, providing a constantly growing dataset.

### **Step 2: Analyze the Core Metrics**

Each entry in the log files is accompanied by critical security metrics. Focus on the relationships between them:

| Metric                 | Icon | What It Represents                                                                                                  |
| ---------------------- | :--: | ------------------------------------------------------------------------------------------------------------------- |
| **Password String**    | `🔑` | The generated character sequence. Observe the mix of character types (lowercase, uppercase, digits, symbols).         |
| **Length**             | `📏` | The number of characters. This is the single most important factor in password strength.                               |
| **Entropy (in bits)**  | `🧠` | A mathematical measure of a password's unpredictability. **Higher is better.** An entropy of 80+ bits is recommended. |
| **Strength Assessment**| `⚖️` | A qualitative label (e.g., *Moderate, Strong, Ultra*) based on calculated entropy and length.                       |
| **Composition**        | `🧬` | A breakdown of the character types used (L/U/D/S). A balanced composition increases the potential character pool.     |
| **Crack Time Estimates**| `⏳` | Theoretical time required for a brute-force attack under different scenarios (Online, GPU). A purely academic metric. |

### **Step 3: Draw Key Insights**

Browse the logs and ask critical questions:
-   *How does adding just two characters impact the entropy and theoretical crack times?*
-   *What is the entropy difference between a password with only letters and one with all character types?*
-   *At what length does a password consistently achieve a "Strong" or "Ultra" rating?*
-   *Why is a 12-character password with high complexity potentially stronger than a 16-character password with low complexity?*

---

##  💡 **The TitanPass Method: From Theory to Practice**

After analyzing the data, apply its lessons to your own security practices. The **TitanPass Method** is a framework for creating and managing secure credentials.

### **I. Generate a High-Entropy Foundation**
Use a trusted, privacy-respecting tool (like our live generator) to create a long, random, and complex password. This is your algorithmic base.

### **II. Apply a Personal, Unpredictable Modification**
This is the crucial step that elevates security. Before saving the password, make **one small, manually-applied change** that only you can easily remember but an attacker cannot guess.

-   **Effective Modifications:** Increment a digit (`4` → `5`), swap a symbol (`!` → `#`), shift a capital letter (`wA` → `Wa`).
-   **Ineffective Modifications:** Using predictable personal data (initials, birthdays) or simple patterns (`123`).

This modification ensures the final password you use has never existed on any screen and is disconnected from any single algorithm, providing a powerful defense against both brute-force and targeted attacks.

### **III. Practice Secure Credential Management**
1.  **Use a Password Manager:** It is impossible for a human to securely manage dozens of unique, complex passwords. Use a trusted, encrypted password manager.
2.  **Enable Multi-Factor Authentication (MFA):** MFA is the single most effective defense against account compromise. Enable it on every service that offers it.
3.  **Enforce a Zero-Reuse Policy:** Every account must have a unique password. A breach at one service must never cascade to another.

---

## 📜 **Project Governance & Acceptable Use**

This project is governed by the MIT License and operates in full compliance with GitHub's Terms of Service.

-   **Purpose:** This repository exists for the explicit purpose of education and security research.
-   **Usage:** You are encouraged to use this data for analysis, presentations, and academic work, with attribution. You may fork the code to learn from its design, provided your use is compliant with all platform rules.
-   **Restrictions:** You may not use the data or code from this project for malicious purposes, including but not limited to creating spam, credential stuffing lists, or any form of platform abuse.

By engaging with this project, you agree to use it responsibly, ethically, and for the betterment of the digital security community.
