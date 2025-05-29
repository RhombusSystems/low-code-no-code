# ⚙️ Rhombus Low-Code/No-Code Automation Templates

Welcome to the official repository for **Rhombus Low-Code/No-Code Integrations**. This repo serves as a centralized collection of automation templates and workflows designed for platforms such as **Zapier**, **Make.com**, and **n8n**. These templates help accelerate automation by showcasing real-world examples of how to connect Rhombus with third-party apps using event-driven logic—no heavy coding required.

---

## 🚀 Purpose

The goal of this repository is to:

- Enable fast deployment of pre-built automations using Rhombus APIs and event hooks.
- Provide real-world templates for common business workflows.
- Empower teams across engineering, sales, and operations to leverage Rhombus data in their preferred automation platforms.
- Offer a starting point for partners and customers exploring Rhombus integrations.

---

## 🧩 Supported Platforms

This repository currently includes templates for:

- [Zapier](https://zapier.com/)
- [Make.com (formerly Integromat)](https://www.make.com/)
- [n8n (self-hosted or cloud)](https://n8n.io/)

Additional platform support may be added over time based on internal use cases and community demand.

---

## 📁 Repository Structure
/
├── zapier/
│   └── rhombus-slack-alert.json
├── make/
│   └── rhombus-google-sheets-export.json
├── n8n/
│   └── rhombus-door-alert-email-workflow.json
├── docs/
│   └── README.md
│   └── CONTRIBUTING.md
└── LICENSE
Each subdirectory contains importable templates along with documentation on usage and prerequisites.

---

## 🧪 Example Use Cases

- **Security Alert to Slack**: Automatically send a Slack message when a Rhombus camera detects a person after hours.
- **Access Control Sync**: Log Rhombus access events to a Google Sheet for auditing.
- **N8N Webhook Trigger**: Initiate a custom workflow when a vape sensor is triggered in a school setting.

---

## 🛠 Setup Instructions

Each template includes an importable `.json` file and a `README.md` within the subdirectory explaining:

1. Platform-specific setup.
2. Required API tokens and authentication.
3. How to test and deploy the automation.
4. Optional enhancements or variables.

Refer to the relevant folder for step-by-step instructions.

---

## 🤝 Contributing

We welcome contributions! Please see [docs/CONTRIBUTING.md](docs/CONTRIBUTING.md) for guidelines on how to:

- Submit new templates.
- Report issues.
- Propose platform expansions or workflow optimizations.

---

## 📜 License

This project is licensed under the [MIT License](LICENSE). Templates are provided as-is with no warranty.

---

## 📫 Contact

For internal Rhombus team members, reach out to `engineering-ops@rhombus.com` or @jeremy on Slack. For external partners, please contact your Rhombus representative.

---

**Build smart. Automate fast. Ship with impact.**
