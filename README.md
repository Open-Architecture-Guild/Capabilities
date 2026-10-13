# Capabilities 🚀
This repository offers an open-source, standardized, and extensible Business Capability Map designed to bridge the gap between strategic business planning and enterprise architecture (EA).

---

## What is a Business Capability Map?
A business capability map is a structured, hierarchical framework that defines an organization's absolute capacity to successfully execute a business activity. 

### Core Characteristics for Enterprise Architecture
* **Stability**: Unlike volatile organizational charts or shifting process flows, core capabilities (e.g., *Manage Finances*, *Fulfill Orders*, *Acquire Customers*) remain constant across restructurings, technological upgrades, and strategy pivots.
* **Non-Redundancy (MECE)**: Every capability is mutually exclusive and collectively exhaustive, defined uniquely regardless of how many legacy systems or departments touch it.
* **Outcome-Oriented**: Formatted strictly in a **Verb + Noun** structure to focus relentlessly on business value creation rather than technical implementation steps.

---

## Structural Hierarchy
The map is structured across three levels to accommodate both high-level executive visualization and granular architectural analysis:

* **Level 1 (Top-Level Domains / Pillars)**: Broad enterprise domains categorized into three standard buckets:
  * **Core / Operational Capabilities**: Directly generate revenue and deliver value to customers (e.g., *Sales*, *Marketing*, *Service Delivery*).
  * **Management / Strategic Capabilities**: Govern, plan, and direct the enterprise (e.g., *Strategic Planning*, *Risk & Compliance Management*).
  * **Enabling / Support Capabilities**: Provide the internal infrastructure required to run the business (e.g., *Manage IT*, *Manage Legal*, *Manage HR*).
* **Level 2 & Level 3 (Sub-Capabilities & Granular Operations)**: Progressive breakdowns. For instance, under *Manage Human Resources* (Level 1), Level 2/3 definitions dive into *Recruit Talent*, *Manage Compensation*, and *Track Performance*.

---

## Quality Metrics & Maturity Framework
To ensure enterprise-grade quality and maintainability within an open-source model, every capability included or contributed must adhere to the following quality metrics:

| Metric | Description | Target / Standard |
| :--- | :--- | :--- |
| **Structural Integrity** | Adherence to the Verb + Noun naming convention and hierarchical depth (Max 3 levels recommended). | 100% compliance |
| **MECE Compliance** | Absence of functional overlaps or redundant capability definitions across domains. | Verified via architectural peer review |
| **Strategic Alignment** | Measurable impact on at least one overarching business outcome or strategic KPI. | Explicitly mapped |
| **Maturity Index (CMMI-based)** | Assessment of process predictability and optimization for the capability (Level 1: Initial to Level 5: Optimizing). | Regularly audited |
| **Technology Coupling** | Degree of independence from specific software vendors or legacy systems (Lower coupling is better). | Low to Zero |

---

## Project Structure
This repository is organized in a clean, folder-based hierarchy. 
* **Top-level folders** represent Level 1 domains.
* **Sub-folders** represent Level 2 operational areas.
* **Leaf nodes (Files)** define the granular Level 3 sub-capabilities.

```text
├── 01-core-capabilities/
│   ├── 010-sales-management.yaml
│   ├── 010-sales-management/
│   │   ├── 011-lead-generation.yaml
│   │   └── 012-deal-closing.yaml
├── 02-management-capabilities/
└── 03-enabling-capabilities/
```

---

## Why an Open Source Capability Map?
Traditional capability modeling is often locked behind proprietary vendor walls, siloed within individual consultancies, or reinvented from scratch by every organization. An open-source approach fundamentally changes this paradigm by crowdsourcing cross-industry best practices and breaking down enterprise silos. It enables a transparent, peer-reviewed standard where organizations no longer have to pay high licensing fees or spend months building taxonomies alone. By pooling collective architectural intelligence, we create a living, universally understood framework that accelerates digital transformation, fosters vendor-agnostic interoperability, and empowers a global community of architects to continuously evolve enterprise design together.

---

## Contributing to the Community
We believe that the best architecture is built collectively. Whether you are an Enterprise Architect, Business Analyst, or C-Level Leader, your domain expertise helps keep this map robust and industry-relevant.

1. Review our [Contribution Guidelines](CONTRIBUTING.md).
2. Propose modifications or add new capabilities via a Pull Request (PR).
3. Ensure your contributions meet the **Quality Metrics** outlined above.

---

## License
This project is licensed under the terms of the [MIT License](LICENSE).
