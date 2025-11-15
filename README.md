# 🌟 Quality Clouds LivecheckAI (via MCP)

**Real-time code validation and governance for AI-assisted development using the Model Context Protocol (MCP).**

This repository provides the MCP integration used by **Quality Clouds LivecheckAI**, enabling VS Code and other MCP-compatible to validate AI-generated Apex, LWC, and metadata code against enterprise development standards, Salesforce platform limits, and security best practices — *right from the first line of code*.

---

## 📄 Overview

Quality Clouds **LivecheckAI** brings real-time validation and governance to Salesforce development by analyzing all AI-generated code through the **Quality Clouds MCP (Model Context Protocol) Server**.

As you write code with AI assistants like GitHub Copilot, LivecheckAI automatically checks each suggestion against:

- Enterprise development standards  
- Salesforce best practices  
- Platform limits and metadata rules  
- Naming conventions and architecture guidelines  
- Security and compliance policies  
- Org-specific custom rules  

Developers receive **instant inline feedback, warnings, and automatic fixes** directly in Visual Studio Code.

---

## 📚 Table of Contents

- [Overview](#-overview)
- [Repository Description](#-repository-description)
- [Key Benefits](#-key-benefits)
- [How It Works](#-how-it-works)
- [Outcomes](#-outcomes)
- [Use Case Example](#-use-case-example)
- [Installation & Setup](#-installation--setup)
  - [Step 1 – Install Visual Studio Code](#step-1--install-visual-studio-code)
  - [Step 2 – Install the Livecheck Extension](#step-2--install-the-livecheck-extension)
  - [Step 3 – Authenticate with Quality Clouds](#step-3--authenticate-with-quality-clouds)
  - [Step 4 – Verify the Integration](#step-4--verify-the-integration)
- [MCP Configuration Example](#-mcp-configuration-example)
- [Need Help?](#-need-help)
- [Summary](#-summary)

---

## 💡 Key Benefits

### ✔ Real-time validation  
LivecheckAI checks every AI suggestion (Apex, LWC, metadata) instantly as it appears in VS Code.

### ✔ Salesforce-aware governance  
Applies advanced rules covering platform limits, security patterns, metadata conventions, naming standards, and architecture guidelines.

### ✔ Consistent compliance  
All developers follow the same organization-wide development and security standards.

### ✔ Automatic corrections  
LivecheckAI auto-fixes common issues such as:  
- Missing documentation  
- Naming inconsistencies  
- Hard-coded IDs  
- Security vulnerabilities  
- Incorrect SOQL patterns  
- Metadata violations  

### ✔ Smooth developer experience  
Runs natively in VS Code without switching tools or waiting for CI processes.

---

## ⚙️ How It Works

1. The developer writes or triggers AI-generated Salesforce code.
2. LivecheckAI sends it to the **Quality Clouds MCP server** for validation.
3. The MCP engine evaluates the code using QC’s Salesforce ruleset.
4. VS Code displays inline results, warnings, and autofixes.
5. Only compliant, secure code continues through the development lifecycle.

---

## 🚀 Outcomes

- Reduced deployment failures  
- Stronger security posture  
- Cleaner and more maintainable code  
- Consistency across teams and repositories  
- Faster onboarding and improved team productivity  
- Lower technical debt and rework  
- Faster and safer release cycles  

---

## 🧱 Use Case Example

A developer prompts GitHub Copilot to generate a new Apex class.

LivecheckAI instantly:

- validates naming and documentation  
- checks platform governor limits  
- prevents unsafe SOQL/DML  
- detects and fixes hard-coded IDs  
- ensures metadata consistency  
- enforces org-specific architectural and governance rules  

Feedback appears **inline in real time**, long before creating a pull request.

---

# 🔧 Installation & Setup

## Step 1 – Install Visual Studio Code

If VS Code is not installed:

1. Go to: https://code.visualstudio.com/download  
2. Install the version for your OS (Windows, macOS, Linux).

---

## Step 2 – Install the Livecheck Extension

1. Open **Visual Studio Code**  
2. Go to **Extensions**  
3. Search for: **“Livecheck Quality for Salesforce”**  
4. Click **Install**  

Once installed, LivecheckAI will be available in your workspace.

---

## Step 3 – Authenticate with Quality Clouds

### For Quality Clouds Customers

1. Ensure the **auto-update** setting is enabled in the extension.  
2. Request your QC Success Manager to enable the **LivecheckAI Add-on**.  
3. Once activated, LivecheckAI features will appear automatically in VS Code.

### For New Users / Non-customers

1. Sign up: https://id.qualityclouds.com/sign-up  
2. Complete the onboarding steps.  
3. Wait for account activation.  
4. Return to VS Code and open the Livecheck extension.  
5. Access **Quality Clouds settings** (bottom-left corner).  
6. Authenticate with your QC credentials.  

LivecheckAI will activate once authenticated.

---

## Step 4 – Verify the Integration

To confirm everything is working:

1. Open GitHub Copilot inside VS Code.  
2. Ask it to generate Apex or LWC code.  
3. LivecheckAI will automatically validate the output.  
4. You will see:  
   - inline warnings  
   - autofixes  
   - platform rule validations  
   - governance compliance notices  

If you see this inline feedback → **setup is successful**.

---


