# Awesome-Enterprise-Cloud-Platform

# Top Enterprise Cloud Platform Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Cloud Infrastructure, Low-Code Platforms & Self-Hosted PaaS*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Enterprise Cloud Platforms**. These tools provide the foundational infrastructure and development environments for building, deploying, and operating enterprise applications—from hyperscale public clouds and integrated application platforms to self-hosted low-code builders and Kubernetes-native PaaS alternatives.

**Examples** include Workday Platform, Salesforce Platform, ServiceNow Now Platform, Microsoft Power Platform, Oracle Cloud Platform, SAP Business Technology Platform, AWS, Microsoft Azure, Google Cloud Platform, and IBM Cloud (the category leaders).

**Open-source emphasis**: Enterprise Cloud Platforms span a vast spectrum—from hyperscale infrastructure (AWS, Azure, GCP) to application development platforms (Salesforce, ServiceNow) and low-code builders. Open-source tooling is **mature and production-proven in specific layers**: **Coolify** and **Dokku** provide self-hosted PaaS alternatives to Vercel/Heroku , **Appsmith** and **ToolJet** provide low-code internal tool builders , and **Convertigo** offers full-stack mobile/web low-code development . However, no single open-source project replicates the integrated breadth of a hyperscale cloud or the ecosystem lock-in of Salesforce/ServiceNow. Organizations must assemble components based on their specific needs—infrastructure, application development, or both.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Workday Platform](https://www.workday.com/)**  
  Unified enterprise management cloud for HCM, financials, and planning; provides a single data model, configurable business processes, and an extensible platform for building Workday-native applications. ISG Research notes Workday's Enterprise Management Cloud (v2025R2) in its Application Platforms Buyers Guide 2026 .

- **[Salesforce Platform](https://www.salesforce.com/)**  
  Metadata-driven application platform with Lightning App Builder, Flow Orchestration, and Data Cloud; the Agentforce AI layer is Salesforce's fastest-growing product (330% YoY, $500M ARR in Q4 2025), with Agentforce relying on unified CRM data in Data Cloud for value realization .

- **[ServiceNow Now Platform](https://www.servicenow.com/)**  
  Enterprise workflow platform with App Engine Studio, Flow Designer, and IntegrationHub; Now Assist ranked first in Gartner's 2025 Critical Capabilities for AI agents, with the AI Agent Orchestrator coordinating multi-agent workflows and the AI Control Tower providing centralized governance . ISG Research places ServiceNow among the highest in Customer Experience for application platforms .

- **[Microsoft Power Platform](https://powerplatform.microsoft.com/)**  
  Suite of low-code tools including Power Apps (canvas and model-driven), Power Automate (cloud and desktop flows with RPA), Power Pages, Dataverse, and Copilot Studio. Academic comparison notes Power Apps as "absolute ruler" in low-code platforms for ease of use and integration, with Power Automate leading in process automation .

- **[Oracle Cloud Platform](https://www.oracle.com/)**  
  Includes Oracle Cloud Infrastructure (OCI) excelling in high-performance database workloads , and Oracle APEX for low-code application development. Oracle's modular, microservices-based approach with Oracle Integration Cloud provides significant composability for integrating Oracle and third-party solutions .

- **[SAP Business Technology Platform](https://www.sap.com/)**  
  Application development and automation platform with SAP Build (low-code/pro-code), Joule Studio for custom AI agents, and ABAP AI capabilities. Academic analysis rates SAP as highly composable (9/10) with excellent orchestration via BTP, SAP Workflow Management, and RPA tools .

- **[AWS](https://aws.amazon.com/)**  
  Hyperscale cloud provider excelling in global scalability and service breadth ; enterprise spending concentrates in the $200K–$500K/month range (16% of enterprises), ranking first in that tier .

- **[Microsoft Azure](https://azure.microsoft.com/)**  
  Hyperscale cloud excelling in hybrid enterprise integration ; Azure shows strong presence in midrange enterprise spend tiers, ranking first in the $50K–$200K/month ranges .

- **[Google Cloud Platform](https://cloud.google.com/)**  
  Hyperscale cloud excelling in AI/ML and data analytics ; GCP has its largest share of enterprise customers in the lowest spending tier (<$50K/month, 18%) .

- **[IBM Cloud](https://www.ibm.com/cloud)**  
  Hyperscale cloud excelling in governed hybrid environments and AI security ; enterprise spending is concentrated at lower ends, with 13% spending less than $50K/month .

## Open-Source GitHub Projects

### Self-Hosted PaaS & Infrastructure Platforms

- **[Coolify](https://github.com/coollabsio/coolify)**  
  Open-source, self-hostable PaaS alternative to Vercel, Heroku, and Netlify (Apache 2.0, 63K+ GitHub stars); deploys static sites, databases, and full-stack applications on your own servers; active development with weekly updates . **The leading open-source alternative to managed PaaS platforms** for teams wanting deployment control without Kubernetes complexity.

- **[Dokploy](https://github.com/Dokploy/dokploy)**  
  Open-source alternative to Vercel, Netlify, and Heroku (37K+ GitHub stars); self-hosted deployment platform with active weekly updates . Positioned as a modern, developer-friendly PaaS for teams migrating off managed platforms.

- **[Dokku](https://github.com/dokku/dokku)**  
  Docker-powered PaaS (32K+ GitHub stars) for building and managing application lifecycles via `git push` deployments; the "smallest PaaS you've ever seen" philosophy; mature and actively maintained .

- **[UbiCloud](https://github.com/ubicloud/ubicloud)**  
  Open-source alternative to AWS (12K+ GitHub stars); provides elastic compute, block storage, firewall/load balancer, managed Postgres, K8s, and AI capabilities; actively developed . **For organizations wanting AWS-like primitives without hyperscaler dependency.**

### Low-Code Application Platforms

- **[Appsmith](https://github.com/appsmithorg/appsmith)**  
  Open-source platform for building admin panels, internal tools, and dashboards (41K+ GitHub stars); integrates with 25+ databases and any API; actively maintained with weekly updates . **The most mature open-source low-code internal tools builder.**

- **[ToolJet](https://github.com/ToolJet/ToolJet)**  
  Open-source foundation for enterprise app generation (41K+ GitHub stars); builds internal tools, dashboards, and business applications; actively maintained .

- **[Budibase](https://github.com/Budibase/budibase)**  
  Open-source low-code platform (28K+ GitHub stars) with AI agents, automations, and apps; model-agnostic; active weekly development .

- **[Convertigo](https://github.com/convertigo/convertigo)**  
  AI-powered open-source enterprise low-code platform (AGPL-3.0) including a No Code Application builder for full-stack mobile and web application development; actively maintained with weekly updates (386 GitHub stars) .

- **[NocoBase](https://github.com/nocobase/nocobase)**  
  Open-source AI + no-code platform for building business systems (24K+ GitHub stars); actively developed .

- **[Lowcoder](https://github.com/lowcoder-org/lowcoder)**  
  Open-source Retool, ToolJet, and Appsmith alternative (1.6K GitHub stars); actively maintained .

### Enterprise Application Frameworks

- **[Frappe Framework](https://github.com/frappe/frappe)**  
  Low-code web framework for real-world applications in Python and JavaScript (11K+ GitHub stars); the foundation for ERPNext and Frappe HR; active weekly updates . **For organizations wanting to build custom enterprise apps on a proven framework.**

- **[Odoo](https://github.com/odoo/odoo)**  
  Open-source business application suite (55K+ GitHub stars) with modular apps for CRM, eCommerce, accounting, manufacturing, and more; active weekly updates . **The most comprehensive open-source ERP/business apps platform.**

- **[Twenty](https://github.com/twentyhq/twenty)**  
  Open-source alternative to Salesforce, designed for AI (58K+ GitHub stars); active weekly development . **For teams wanting CRM primitives with modern architecture.**

### Additional Strong Open-Source Options

- **Kubero** — Free self-hosted PaaS alternative running on Kubernetes (4.4K GitHub stars) .
- **CapRover** — Scalable PaaS (Docker + nginx), "Heroku on Steroids" (15K GitHub stars) .
- **Kubernetes** — The foundational container orchestration platform underpinning most modern PaaS alternatives.
- **Apache OFBiz** — Open-source enterprise automation framework (1.1K GitHub stars); active weekly development .
- **iDempiere** — Community-powered open-source ERP/CRM (666 GitHub stars); active weekly updates .

**Frameworks for building custom systems**: The choice depends on need. For **infrastructure/PaaS**: Coolify or Dokploy for self-hosted deployments, UbiCloud for AWS-like primitives. For **low-code application development**: Appsmith (internal tools), Convertigo (mobile/web full-stack), or Frappe Framework (enterprise apps). For **business application suites**: Odoo or ERPNext. No single open-source platform spans all layers—organizations must choose based on whether they need infrastructure, development tooling, or business applications.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Enterprise cloud platforms handling infrastructure and application data must comply with applicable security policies, data residency requirements, and regulatory obligations; access controls and audit logging are critical.
- **Open-source enterprise cloud platforms are layer-specific**—Coolify and UbiCloud address infrastructure/PaaS, Appsmith and Convertigo address low-code development, and Odoo/Frappe address business applications. No open-source project replicates the integrated breadth of a hyperscale cloud (AWS/Azure/GCP) or the ecosystem lock-in of Salesforce/ServiceNow. Organizations should select components based on their specific needs and integration requirements.
- Verify license terms for commercial use; Coolify uses Apache 2.0, Appsmith uses Apache 2.0, ToolJet uses AGPL-3.0, Convertigo uses AGPL-3.0, and Frappe Framework uses MIT .

---

**Made for enterprise architects, platform engineers, cloud infrastructure teams, and application development leaders.**  
Let's make enterprise cloud platforms more open, but with clear eyes about which layer each tool actually addresses.
