# Contributing to the Open Capability Map

First off, thank you for taking the time to contribute! 🚀 
We are building an open, community-driven enterprise capability map designed for architects, business analysts, and executive decision-makers. Your industry expertise helps keep this framework robust, standard, and universally applicable.

By participating in this project, you agree to abide by our governance and structural standards.

---

## Architecture & Hierarchy Standards

To ensure our map remains clean, predictable, and useful for enterprise-grade tooling, every contribution must respect our 3-tier hierarchy:

1. **Level 1: Domain (`domain`)** – Broad enterprise pillars (e.g., *Manage Finances*).
2. **Level 2: Sub-Domain (`sub-domain`)** – Functional groupings within a domain (e.g., *Financial Accounting & Operations*).
3. **Level 3: Capability (`capability`)** – Granular, executable leaf nodes (e.g., *Manage Accounts Payable*).

---

## How to Contribute a New Capability (Level 3)

Since Level 3 capabilities are the core operational "leafs" of our repository, they require strict adherence to our formatting and metadata guidelines.

### 1. Check the Naming Convention
* **Format**: Strictly use the **Verb + Noun** format (e.g., *Acquire Customers*, *Fulfill Orders*, *Manage Accounts Payable*).
* **MECE Principle**: Ensure the capability is mutually exclusive and collectively exhaustive. Do not duplicate existing capabilities.

### 2. Follow the YAML Template
Every Level 3 capability must be defined using our standardized YAML structure. You can find the current template under `.github/templates/`
