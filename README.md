# 🛡️ RyPX (Ranyang Project X)

### 🔑 The Secure, Unified Script Ecosystem and Framework for Termux.

[![GitHub License](https://img.shields.io/badge/License-MIT%2FApache%202.0-blue.svg)]([YOUR_WIKI_LINK]/RyLicense)
[![Latest Release](https://img.shields.io/github/v/release/[YOUR_USERNAME]/RyPX?style=for-the-badge&color=2ecc71&label=Latest%20Version)](https://github.com/[YOUR_USERNAME]/RyPX/releases/latest)
[![Code Size](https://img.shields.io/github/languages/code-size/[YOUR_USERNAME]/RyPX?style=for-the-badge&color=9b59b6)](https://github.com/[YOUR_USERNAME]/RyPX)
[![Open Issues](https://img.shields.io/github/issues/[YOUR_USERNAME]/RyPX?style=for-the-badge&color=e74c3c)](https://github.com/[YOUR_USERNAME]/RyPX/issues)

---

> **RyPX** is an ambitious project built to solve the **fragmentation** and **security risks** inherent in the Termux script community. We provide a **bulletproof framework** where community-contributed tools can be deployed, managed, and executed under strict **client-side integrity controls.**

---

## 🌟 The Core Ambition: Trust and Structured Architecture

The primary goal of RyPX is to redefine the reliability of mobile terminal scripting by implementing a robust, modular architecture and a comprehensive security defense system.

### The RyPX Solution: Core Pillars

| Feature | Component | 🔥 Value Proposition (Why it Matters) |
| :---: | :--- | :--- |
| **Integrity Validation** | **🛡️ RyDefend** | **CRITICAL USP.** Every Sub-Script's integrity is verified via checksum against the centralized metadata before any execution attempt. **Minimizes risk from malicious or corrupted scripts.** |
| **System Isolation** | **RySystem/Installer** | **Validates *Root Path* and Installation Signature (`RyBase`).** Ensures RyPX only runs in a compatible Termux environment and prevents accidental double-installation. |
| **Clean Architecture** | **RySystem/RyLib** | **Strict separation of concerns.** Provides a modular foundation, making core system maintenance easier and integration of new scripts simpler. |
| **Centralized Data** | **💾 RyStorage** | Organizes scripts, logs, configurations, and cache in a secure, designated directory. Eliminates file clutter across your Termux environment. |

---

## 🏗️ Architectural Overview (The Five Modules)

RyPX's operational stability relies on five distinct, yet integrated, core modules.

### 1. 💻 RySystem (The Brain)
* **Role:** The initializer and main system handler. Responsible for setting global variables, loading **RyLib** functions, and launching the main UI.

### 2. 🧱 RyLib (The Toolkit)
* **Role:** A collection of highly reusable and dependency-checked functions for tasks like network handling and JSON parsing.

### 3. 💾 RyStorage (The Vault)
* **Role:** Local persistence layer. Safely stores all non-core data, including downloaded scripts and security logs.

### 4. ⚙️ RyService (The Background Worker)
* **Role:** Manages background tasks vital for platform health, such as scheduled metadata cache updates.

### 5. 🛡️ RyDefend (The Guardian)
* **Role:** The core security module. It enforces all integrity and sandboxing rules, acting as the primary guardian of the execution process.

---

## 🚀 Installation Guide (How to Get Started)

### Prerequisites

| Tool | Necessity | Command |
| :--- | :--- | :--- |
| **Termux** | Mandatory execution environment. | N/A |
| **git** | Core dependencies for cloning and data handling (RyLib). | `pkg install git -y` |

### **Procedure (The 3 Steps)**

1.  **Prepare Termux** and install core dependencies:
    ```bash
    pkg update && pkg upgrade
    pkg install git
    ```

2.  **Clone the official RyPX Repository** and navigate to the folder:
    ```bash
    git clone https://github.com/BluePlayzgoStudio/RanyangProjectX/tree/main
    cd RyPX
    ```

3.  **Execute the self-validating installer**:
    ```bash
    bash install.sh
    ```

> **note when Installing** : there will be some that will be installed automatically 

---

## 📜 Mandatory: RyLicense (End-User License Agreement)

**RyPX is provided under a robust license that prioritizes user safety and platform integrity.**

While **RyDefend** is our commitment to a secure environment, the **ultimate legal responsibility** for running any third-party Sub-Script rests solely with the User.

➡️ **[READ THE FULL RyLICENSE DOCUMENTATION HERE](https://github.com/BluePlayzgoStudio/RanyangProjectXBeta/wiki/RyLisense)**

---

## 🤝 Contribution & Support

We invite talented developers and security enthusiasts to join the RyPX vision.

* **View Core Documentation:** [Visit the RyPX Wiki](https://github.com/BluePlayzgoStudio/RanyangProjectXBeta/wiki/core)
* **Report Issues:** [Open a detailed Bug Report Here](https://github.com/BluePlayzgoStudio/RanyangProjectXBeta/issues/new?assignees=&labels=bug&projects=&template=bug_report.md&title=)
* **Submit a Sub-Script:** Check our contribution guidelines for how to securely submit your tool for inclusion in the RyPX server metadata.
