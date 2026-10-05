# Awesome-Data-Governance-Compliance

# Awesome-Data-Governance-Compliance



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Data Catalogs, Metadata Management, Data Quality, Privacy & Regulatory Compliance*

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Data Governance & Compliance**. These tools help organizations catalog data assets, track lineage, enforce policies, manage data quality, and demonstrate regulatory compliance across hybrid and multi-cloud environments.



**Examples** include Microsoft Purview, Collibra, Alation, OneTrust, Informatica Cloud Data Governance, Atlan, BigID, IBM Knowledge Catalog, Privacera, and Immuta (the category leaders).



**Open-source emphasis**: The open-source data governance ecosystem is **mature and production-proven**. **DataHub** (Apache-2.0) leads with real-time streaming metadata, column-level lineage, and native MCP support for AI agents . **OpenMetadata** provides a unified metadata graph with a built-in MCP server and semantic search . **Apache Atlas** remains the Hadoop-ecosystem standard with deep Hive/Spark/Kafka integration . This section documents these production-grade solutions.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## 📖 Table of Contents



- [☁️ SaaS/Hosted Platforms](#-saas-hosted-platforms)

- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)

- [🤝 How to Contribute](#-how-to-contribute)

- [⚠️ Disclaimer](#-disclaimer)



## ☁️ SaaS/Hosted Platforms



> **📊 Market Context**: The global data governance practice platform market was valued at **$670 million in 2025** and is projected to reach **$750 million in 2026**, growing at a **12.3% CAGR** toward **$1.2 billion by 2030** . The sector is **moderately fragmented** — **Microsoft Purview** offers a **free foundational tier** for Microsoft 365 sources with pay-as-you-go for non-M365 environments . **Collibra** uses **Collibra Units (CUs)** for AI features with annual reset and no rollover . **Alation** charges **0.25 ACU per metered action** with a shared pool across products . **OneTrust** uses **usage meters at the package level** (average daily unique visitors for CMP, annual scan volume for EDD) . No single vendor holds a winner-take-all position; enterprises typically run multi-vendor stacks.



| Platform | Description | Pricing (Starting Tier) | Free Tier Limits | Company Size |

|----------|-------------|------------------------|------------------|--------------|

| **[Microsoft Purview](https://www.microsoft.com/en-us/security/business/microsoft-purview)** | **Integrated data security and governance platform.** Extends from Microsoft 365 to AWS, Azure SQL, Box, Dropbox, Google Drive, and Fabric via pay-as-you-go billing . | **Per-user license** for M365 sources (bundled with E5); **Pay-as-you-go** for non-M365 sources (Azure subscription required) . | **Free foundational tier** for Microsoft 365 and Windows/macOS endpoints. **Pay-as-you-go** consumption model based on Azure billing . | **~$281B revenue (Microsoft FY2025)** |

| **[Collibra](https://www.collibra.com/)** | **Enterprise data intelligence platform.** Data catalog, governance, lineage, and AI-powered features via Collibra Units (CUs). | **Collibra Units (CUs)** for AI features. Extra CU bundles available at contract level. **Annual CU reset** — unused units expire . | **None** — enterprise demo required. **CU guardrails** at 80%, 100%, and 120% consumption thresholds . | **Private (~$2.6B valuation est.)** |

| **[Alation](https://www.alation.com/)** | **Enterprise data catalog with collaborative governance.** AI-powered curation, data quality checks, and agent studio via ACU consumption model. | **Alation Consumption Units (ACUs)** — single pool across five AI products. **Curation Automation**: 0.05 ACU per AI field write. **Data Quality**: 0.075 ACU per check run. **Agent Studio**: 0.25 ACU per call/tool invocation . | **Free tier**: One-time cumulative grant of tool calls that never resets. **Paid tier**: Monthly allocation resetting each billing period . | **Private (~$1.7B valuation est.)** |

| **[OneTrust](https://www.onetrust.com/)** | **Privacy, security, and data governance platform.** Modular packages with usage-metered pricing at package level . | **Usage meters** at package level: **Average Daily Unique Visitors** (CMP), **Data Subjects** (UCPM), **Annual Volume Scanned** (EDD) . | **None** — enterprise demo required. **Implementation/onboarding**: 20–40% of annual subscription . | **Private (~$5.1B valuation est.)** |

| **[Informatica Cloud Data Governance](https://www.informatica.com/)** | **Unified data governance within IDMC.** Metadata management, data lineage, and governance workflows. | **Consumption-based (IPU)** for IDMC. **PowerCenter** (legacy): Perpetual licensing + annual maintenance . | **None** — enterprise demo required. **Consumption true-ups** quarterly or annual for exceeding committed IPU levels . | **~$1.6B revenue, private** |

| **[Atlan](https://atlan.com/)** | **Modern data catalog and governance platform.** Context Layer for AI, active lineage, and automation. | **Custom pricing** — quote required. Positioned as **faster time-to-value** and **more transparent** than Alation . | **None** — enterprise demo required. | **Private (~$100M+ ARR est.)** |

| **[BigID](https://bigid.com/)** | **Data discovery and classification platform.** Often positioned as a complement to OneTrust for discovery use cases . | **Custom pricing** — quote required. **Typically less expensive than OneTrust** for mid-market deployments . | **None** — enterprise demo required. | **Private (~$1B+ valuation est.)** |

| **[IBM Knowledge Catalog](https://www.ibm.com/products/knowledge-catalog)** | **Enterprise metadata and governance within IBM Cloud Pak for Data.** AI-powered cataloging and policy management. | **Custom enterprise pricing** — quote required. | **None** — enterprise demo required. | **~$63B revenue (IBM FY2025)** |

| **[Privacera](https://privacera.com/)** | **Data security and governance platform powered by Apache Ranger.** Access control, encryption, and compliance. | **$1.00/year** (SaaS marketplace starting price) . | **None** — enterprise demo required. | **Private (~$50M+ raised est.)** |

| **[Immuta](https://www.immuta.com/)** | **Data security platform with automated governance.** Dynamic access control and policy enforcement. | **Free** (SaaS marketplace listing) . | **Free tier** available on cloud marketplaces . | **Private (~$100M+ raised)** |



## 🔓 Open-Source GitHub Projects



Sorted by star count (descending). Star badge links to each repo's stargazers page.



| Repo | Description | Stars |

|---|---|---|

| **[DataHub](https://github.com/datahub-project/datahub)** — **The leading open-source metadata platform.** Born at LinkedIn to handle hyperscale data, now proven at thousands of organizations managing millions of data assets. **Real-time streaming metadata** via Kafka (updates in seconds, not hours). **Column-level lineage**, 80+ production-grade connectors, GraphQL/OpenAPI, Python/Java SDKs, and **native MCP support for AI agents**. **Apache-2.0** licensed, vendor-neutral, community-driven . | [![Stars](https://img.shields.io/github/stars/datahub-project/datahub?style=social&color=white)](https://github.com/datahub-project/datahub/stargazers) | ~7,200 |

| **[OpenMetadata](https://github.com/open-metadata/OpenMetadata)** — **Unified metadata platform with AI-ready context.** Single place to discover, collaborate, and govern data. **Memories** preserve organizational context (why metrics changed, why columns renamed, what agents learned). **MCP server** lets AI assistants search metadata, inspect lineage, and retrieve memory nuggets. **Semantic Search** finds assets by meaning. **AI SDK** (`data-ai-sdk`) for building custom AI applications . | [![Stars](https://img.shields.io/github/stars/open-metadata/OpenMetadata?style=social&color=white)](https://github.com/open-metadata/OpenMetadata/stargazers) | ~7,200 |

| **[Apache Atlas](https://github.com/apache/atlas)** — **Metadata management and governance for Hadoop.** **2,011 stars**, 895 forks, Apache-2.0 licensed, Java-based . Centralized metadata management, data lineage, classification-based security, and business glossary. **Deep integration with Hive, HBase, Spark, Kafka** — nearly zero-config metadata collection for Hadoop stacks . **Limitation**: Cloud-native adaptation weaker; community maintenance pace slower than DataHub/OpenMetadata . | [![Stars](https://img.shields.io/github/stars/apache/atlas?style=social&color=white)](https://github.com/apache/atlas/stargazers) | ~2,011 |

| **[SetGo](https://github.com/)** — **Open-source Python toolkit for metadata readiness assessment.** Evaluates **FAIR sub-principles (15 principles)**, governance policies, licensing (SPDX registry), provenance completeness, reproducibility, and catalog-ready fields. **Six independent assessment modules** with configurable policies (MINIMAL, STANDARD, STRICT). **Composite readiness score** (0-1) with letter grades. **CI/CD integration** with exit codes. **Agentic support** via SKILL.md and `/setgo` command for Claude Code . | [![SetGo](https://img.shields.io/badge/SetGo-Toolkit-blue)](https://github.com/) | N/A |



## 🤝 How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## ⚠️ Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Data governance platforms handle sensitive metadata and potentially regulated data; ensure proper access controls and compliance with organizational policies.

- **Open-source reality**: The open-source ecosystem for data governance is **mature and production-proven**. **DataHub** leads with real-time streaming metadata, column-level lineage, and native MCP support — used by Netflix, Visa, and Apple . **OpenMetadata** provides a unified metadata graph with built-in MCP server and semantic search . **Apache Atlas** remains the Hadoop-ecosystem standard with deep Hive/Spark/Kafka integration . However, **commercial platforms** (Collibra, Alation, Microsoft Purview) provide **managed infrastructure, enterprise SLAs, and integrated AI features** that open-source alternatives require significant operational investment to match. **DataHub's learning curve is steep** — it doesn't include a data quality engine and requires integration with Great Expectations or custom rules . The open-source path is **genuinely viable** for organizations with strong data engineering capacity.

- **Pricing caveat**: All pricing figures are **verified against cited search results** but may change without notice. **Consumption models vary** — Collibra CUs reset annually with no rollover , Alation ACUs use a shared pool with daily refresh , and OneTrust meters at package level . **Implementation/onboarding** typically adds **20–40%** to annual subscription costs for enterprise deployments .



---



**Made for data stewards, governance engineers, compliance officers, and data platform teams.**

Let's make data governance more open, transparent, and AI-ready.
