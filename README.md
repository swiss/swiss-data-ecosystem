# FAQ Swiss Data Ecosystem

This FAQ is related to the Swiss data ecosystem.<br>
More information can be found at https://www.bk.admin.ch/de/datenoekosystem-schweiz

Do you have more questions? Contact us dataspaces@bk.admin.ch.

## Table of Contents

* [**Basic Concepts and Terminology**](#topic-basic-concepts-and-terminology)
    * [What is meant by data ecosystem?](#what-is-meant-by-data-ecosystem)
    * [What is a data space?](#what-is-a-data-space)
    * [What is the difference between a data ecosystem and a data space?](#what-is-the-difference-between-a-data-ecosystem-and-a-data-space)
    <!--
    * [What is the difference between a data hub and a data space?](#what-is-the-difference-between-a-data-hub-and-a-data-space)
    -->
    * [What is a data product?](#what-is-a-data-product)
* [**Purpose and Added Value**](#topic-purpose-and-added-value)
    * [Is a data space merely a data catalogue or a consent management system?](#is-a-data-space-merely-a-data-catalogue-or-a-consent-management-system)
    * [Why do we need guidelines? There are already many products for data exchange and data spaces.](#why-do-we-need-guidelines-there-are-already-many-products-for-data-exchange-and-data-spaces)
    * [Can I just use bilateral connections for data exchange?](#can-i-just-use-bilateral-connections-for-data-exchange)
* [**Stakeholders, Roles and Responsibilities**](#topic-stakeholders-roles-and-responsibilities)
    * [Who are the stakeholders in the Swiss data ecosystem?](#who-are-the-stakeholders-in-the-swiss-data-ecosystem)
    * [Who is responsible, and how are costs shared?](#who-is-responsible-and-how-are-costs-shared)
    * [What does the Anlaufstelle do in relation to data spaces?](#what-does-the-anlaufstelle-do-in-relation-to-data-spaces)
    * [How can the Anlaufstelle support me?](#how-can-the-anlaufstelle-support-me)
* [**Architecture and Standards**](#topic-architecture-and-standards)
    * [What is the time horizon of the target architecture: now, tomorrow, or 10 years' time?](#what-is-the-time-horizon-of-the-target-architecture-now-tomorrow-or-10-years-time)
    * [Can I just use DSSC, Gaia-X, IDSA, data mesh, or another standard as the reference architecture?](#can-i-just-use-dssc-gaia-x-idsa-data-mesh-or-another-standard-as-the-reference-architecture)
* [**Material**](#topic-material)
    * [What has changed from the previous version of the documentation?](#what-has-changed-from-the-previous-version-of-the-documentation)
    * [How binding are the documents?](#how-binding-are-the-documents)
    * [Which document is intended for which target audience?](#which-document-is-intended-for-which-target-audience)

---
    
## Topic: Basic Concepts and Terminology

### What is meant by data ecosystem?

The Swiss Data Ecosystem is a national network for the exchange and multi-use of data. It connects data repositories, data platforms and services from public administration, business, research and civil society. Common rules and a shared public infrastructure ensure that data exchange is trustworthy and interoperable.

Source: Glossar DOeS V1.0; Leitbild DOeS V1.0

<details>
<summary>Extended Answer</summary>
The Swiss Data Ecosystem (DOeS) is a national network, orchestrated through a governance framework, which enables the interoperable, trustworthy, resilient and user-relevant primary and secondary use of data in business, science, public administration and the general public. Regional and national data spaces, data platforms and sector-specific services, based on the public sector’s basic infrastructure and services, collectively form the Swiss Data Ecosystem. The initiative was approved by the Federal Council and aims to promote the re-use of data so that its potential can be better exploited.
</details>

### What is a data space?

A data space is a technical and organisational structure, based on common governance and a decentralised setup, that enables and regulates trusted data transactions between different sources and actors. Data spaces are often sector-specific, defined by a purpose, clear rules and standards, and organised by a data space governance authority (Datenraumträgerschaft). Examples are the Swiss Health Data Space (SHDS), MODI (mobility) and agridata.ch (agriculture).

Source: Glossar DOeS V1.0; Leitbild DOeS V1.0

<details>
<summary>Extended Answer</summary>
A data space is a technical and organisational structure based on shared governance and a decentralised structure, which enables and regulates trustworthy data transactions between different sources and by different stakeholders. Participants in a data space undertake to comply with shared governance – extended to the Swiss Data Ecosystem – as well as specific, domain-specific rules and standards. 
</details>

### What is the difference between a data ecosystem and a data space?

The data ecosystem is the overall national framework, and a data space is one building block within it. Besides data spaces, the ecosystem also includes other data sharing platforms (e.g. OGD platforms, data hubs, bilateral solutions), domain-specific services and common public infrastructure, all of which must meet the ecosystem’s minimum requirements. A data space additionally follows the data space guiding principles, such as a neutral governance authority, decentralised data storage and consent management.

Source: Leitbild DOeS V1.0; Glossar DOeS V1.0

<details>
<summary>Extended Answer</summary>
The Swiss data ecosystem is an overarching coordination framework and not an additional, standalone data infrastructure. Through its vision, regulation, core characteristics and minimum requirements, it creates a common framework for data spaces, other data exchange platforms, support and value-added services, as well as the shared public infrastructure. data spaces are one such component: they constitute core infrastructures within the data ecosystem and facilitate and regulate trustworthy data exchange, usually for a specific sector or region.
</details>

### What is a data product?

A data product is a unit for sharing data that comprises the data, its metadata and all associated access and usage conditions, including licence terms. Unlike a plain dataset, it also has explicit semantics, defined quality, documented lineage, a clear owner responsible for its lifecycle, and is provided via defined interfaces. A data product does not necessarily imply commercial aspects.

Source: Glossar DOeS V1.0

<details>
<summary>Extended Answer</summary>
A data product is a unit for the shared use of data, comprising data and metadata as well as all associated access and usage conditions / licence terms. Part of this (metadata, access and usage guidelines) may be published in a data product catalogue that can be searched by data users; a data product requires clear accountability, including product lifecycle management. 
</details>

---

## Topic: Purpose and Added Value

### Is a data space merely a data catalogue or a consent management system?

No. The catalogue and consent management are just two components of a data space. These are complemented by identities and trust, data products, the actual data exchange with its rules of use, and monitoring. Furthermore, a data space requires common rules and a responsible governing body.

Source: Architecture Guidelines for Data Spaces V1.0; Leitbild DOeS V1.0

<details>
<summary>Extended Answer</summary>
No. A data space comprises five operational capabilities: identity and access management, provision of data products, discoverability and access, data exchange and policy enforcement, as well as traceability and monitoring. The data product catalogue is a mandatory component within ‘discoverability and access’, whilst consent management is an optional component of ‘provision of data products’; furthermore, a data space requires shared governance and a neutral, trustworthy data space sponsor.
</details>

### Why do we need guidelines? There are already many products for data exchange and data spaces.

There are many solutions, but they are often not necessarily interoperable. The guidelines define common rules and building blocks. This ensures that data spaces remain compatible and trustworthy. They do not prescribe any specific product or technology – each data space selects its own technology within this framework.

Source: Architecture Guidelines for Data Spaces V1.0; Leitbild DOeS V1.0; Glossar DOeS V1.0

<details>
<summary>Extended Answer</summary>
Today’s data exchange landscape in Switzerland is characterised by fragmented, isolated solutions and low interoperability, which makes the cross-platform, multi-purpose use of data extremely difficult or impossible. The guidelines provide a common framework of principles, minimum requirements and architectural building blocks, ensuring that each data space functions reliably in its own right whilst remaining interoperable and trustworthy with others. They do not prescribe specific products: each data space selects the specific solution components when implementing its reference architecture.
</details>

### Can I just use bilateral connections for data exchange?

Yes, if only a few partners exchange data within a fixed framework. Bilateral connections form part of the ecosystem as long as they meet the minimum requirements. Where there are many and changing partners, a data space is preferable. Shared rules and trust mechanisms then replace numerous individual agreements.

Source: Leitbild DOeS V1.0; Architecture Guidelines for Data Spaces V1.0

<details>
<summary>Extended Answer</summary>
Direct data exchange solutions that enable ad hoc, often bilateral, data flows between stakeholders can form part of the Swiss data ecosystem, provided they meet its minimum requirements; developing into a data space is neither generally required nor a target. Point-to-point connections are suitable for a small number of parties in a stable one-to-one relationship. If there are many, changing participants, data is used in multiple use cases and usage control is required, a data space offers shared trust mechanisms instead of individually managed access credentials and implicit agreements.
</details>

---

## Topic: Stakeholders, Roles and Responsibilities

### Who are the stakeholders in the Swiss data ecosystem?

Everyone who shares or uses data in Switzerland: public authorities, businesses, research organisations and civil society organisations. The public is indirectly involved. They retain control over their own data and benefit from improved services. Within a data space, organisations can act as providers, users, operators or sponsors.

Source: Leitbild DOeS V1.0; Governance DOeS V0.5; Glossar DOeS V1.0

<details>
<summary>Extended Answer</summary>
The Swiss data ecosystem is designed as an inclusive network and is aimed at all participants involved in data collaboration in Switzerland, in particular public administration, the private sector, research and civil society organisations. The general public plays a primarily indirect role as the bearer of digital self-determination; legal frameworks and consent management enable control over the use of one’s own data. Within a data space, stakeholders assume roles such as data space sponsors, data space operators, data providers, data users or service providers.
</details>

### Who is responsible, and how are costs shared?

Responsibility is distributed across three levels: the federal government sets the framework, the ecosystem’s governing bodies establish common rules, and each data space operates independently. The sponsoring body of a data space is responsible for its funding. A mix of membership fees, usage fees and public funding is recommended.

Source: Governance DOeS V0.5; Governance-Leitfaden Datenraum V1.0; Leitbild DOeS V1.0

<details>
<summary>Extended Answer</summary>
In accordance with the principle of subsidiarity, governance is structured across three levels: the federal government establishes the strategic and regulatory framework; the steering level sets out common rules and minimum requirements; and the sponsoring bodies or operating organisations are responsible for the operational governance and running of their data spaces. The data space sponsoring body is responsible for strategic management, compliance and funding, based on a business and operating model. The data space Governance Guide recommends a hybrid model comprising membership fees, usage charges and public funding, as well as an early transition from start-up funding to long-term self-financing.</details>

### What does the Anlaufstelle do in relation to data spaces?

The contact point is the central point of contact and coordination for the Swiss data ecosystem. It provides tools and guidelines, promotes interoperability and supports data space initiatives. It does not operate data spaces itself – this remains the responsibility of the respective data space.

Source: Governance DOeS V0.5; Leitbild DOeS V1.0

<details>
<summary>Extended Answer</summary>
</details>

### How can the Anlaufstelle support me?

The contact point assists you in setting up your data space by providing advice, guides, checklists and templates. It connects you with other initiatives and supports you in the event of conflicts. You can contact the helpdesk at dataspaces@bk.admin.ch.

Source: Governance DOeS V0.5; Governance-Leitfaden Datenraum V1.0

<details>
<summary>Extended Answer</summary>
The contact point offers conceptual support for the establishment and further development of data spaces, assists with the organisation of data space governance bodies, and helps to resolve conflicts between participants or data spaces. It publishes a mission statement, a glossary, the ‘Governance of the Swiss Data Ecosystem’ document, as well as governance and architecture guidelines containing recommendations for action, checklists and templates, and ensures communication and the exchange of knowledge within the data ecosystem. Initiatives can contact it at dataspaces@bk.admin.ch and share their experiences.</details>

---

## Topic: Architecture and Standards

### What is the time horizon of the target architecture: now, tomorrow, or 10 years' time'?

All three. The Architecture Vision 2050 and the Mission Statement set out the long-term direction. The Architecture Guide provides practical recommendations for setting up data spaces today – starting small and growing step by step. It is updated regularly.

Source: Architecture Guidelines for Data Spaces V1.0; Leitbild DOeS V1.0

<details>
<summary>Extended Answer</summary>
The mission statement describes Switzerland’s future data ecosystem and bases some of its guiding principles on eCH-0279 ‘Architecture Vision 2050’, which sets out the long-term direction. The ‘data space’ Architecture Guide provides practical recommendations for the design and implementation of data spaces today; in line with the principle of ‘simplicity over completeness’, it focuses on core requirements and enables iterative growth in line with real-world needs. As new data space initiatives are constantly emerging, the guide is regularly updated on the basis of relevant standards and initiatives.
</details>

### Can I just use DSSC, Gaia-X, IDSA, data mesh, or another standard as the reference architecture?

These frameworks are important foundations, and the Swiss guidelines build upon them. However, they cannot simply be adopted as they stand: Swiss law and sector-specific regulations take precedence, and the minimum requirements of the DOeS must be met. Use them within the guidelines to create your own data space’s reference architecture.

Source: Governance-Leitfaden Datenraum V1.0; Architecture Guidelines for Data Spaces V1.0; Architecture Guidelines Mappings Attachment 

<details>
<summary>Extended Answer</summary>
The DOeS documents are based on the DSSC Blueprint 3.0, IDSA and Gaia-X. However, international standards are not always directly applicable to Switzerland and are sometimes too broad in scope: Data protection law and sector-specific legislation take precedence, and the choice of standards is the responsibility of the sponsoring organisation, which must ensure that they are compatible with the DOeS principles and do not create dependencies on proprietary solutions. The DOeS guidelines flesh out the concepts and form the common framework within which each data space develops its own reference architecture using appropriate standards.
</details>

---

## Topic: Material

## What has changed from the previous version of the documentation?

The former Reference Architecture 2025 has been split across several documents. Operational topics are covered in the Architecture Guide, whilst organisational topics are covered in the Governance Guide. The Mission Statement and the Governance Paper provide an overview of the whole picture. An appendix shows where the former elements can now be found.

Source: Architecture Guidelines for Data Spaces V1.0; Leitbild DOeS V1.0; Architecture Guidelines Mapping Attachment Mappings; Glossar DOeS V1.0

<details>
<summary>Extended Answer</summary>
The 2025 Reference Architecture has been superseded by the data space Architecture Guide; its content has been redefined in scope, expanded and reorganised. Operational aspects are now covered in the Architecture Guide, institutional aspects in the data space Governance Guide, and ecosystem-related content in the Mission Statement and in the Governance of the Swiss Data Ecosystem; the term ‘Reference Architecture’ is now reserved for the architecture maintained by the respective data space steering group. The ‘Mappings’ appendix maps each component of the Reference Architecture 2025 to its successor in the DOeS.
</details>

## How binding are the documents?

Most documents are currently recommendations rather than obligations. The mission statement provides guidance; the glossary and governance paper are strongly recommended; and the guidelines offer best practices. Binding minimum requirements are planned for the future. A data space’s own rules are binding on its participants.

Source: Governance-Leitfaden Datenraum V1.0; Governance DOeS V1.0 

<details>
<summary>Extended Answer</summary>
The binding nature varies by document: the Mission Statement serves as a guide for all stakeholders; the Glossary and the ‘Governance of the Swiss Data Ecosystem’ are strongly recommended for all stakeholders; and the Governance and Architecture Guides are recommended for sponsoring bodies, data space operators and technical implementation teams. The ‘Governance of the Swiss Data Ecosystem’ is currently a discussion paper; the future aim is to establish a concrete and binding definition of the minimum requirements (e.g. in the form of a law, an ordinance and/or standards), which requires a corresponding legal or competence basis. Within a data space, the Rulebook and Reference Architecture, as specifications set by the respective data space sponsoring body, are binding on its participants and data space operators.
</details>

## Which document is intended for which target audience?

Decision-makers: Start with the mission statement and the governance paper. Anyone setting up or operating a data space: Use the Governance Guide. Architects and technical teams: Use the Architecture Guide. The glossary is useful for everyone.

Source: Leitbild DOeS V1.0; Glossar DOeS V1.0; Governance DOeS V0.5; Governance-Leitfaden Datenraum V1.0; Architecture Guidelines V1.0

<details>
<summary>Extended Answer</summary>
The mission statement is aimed at decision-makers and project managers from public administration, the private sector, research and civil society; the glossary is aimed at anyone who reads the DOeS documents or works on data spaces. The Swiss Data Ecosystem Governance is aimed at decision-makers and project managers involved in data collaboration, whilst the data space Governance Guide is aimed at data space sponsors, data space operators, data space participants, service providers and decision-makers who wish to set up, operate or participate in a data space. The data space Architecture Guide is primarily aimed at enterprise architects and technical implementation teams.
</details>
