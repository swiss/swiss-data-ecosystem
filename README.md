# FAQ Swiss Data Ecosystem

## Table of Contents

* [**Basic Concepts and Terminology**](#topic-basic-concepts-and-terminology)
    * [What is meant by data ecosystem?](#what-is-meant-by-data-ecosystem)
    * [What is meant by data space?](#what-is-meant-by-data-space)
    * [What is the difference between data ecosystem and data space?](#what-is-the-difference-between-data-ecosystem-and-data-space)
    * [What is the difference between a data hub and a data space?](#what-is-the-difference-between-a-data-hub-and-a-data-space)
    * [What is a data product?](#what-is-a-data-product)
* [**Purpose and Added Value**](#topic-purpose-and-added-value)
    * [Is dataspace just a data catalogue / consent management system?](#is-dataspace-just-a-data-catalogue--consent-management-system)
    * [Why do we need guidelines? There are already many products for data exchange and data spaces.](#why-do-we-need-guidelines-there-are-already-many-products-for-data-exchange-and-data-spaces)
    * [Can I just use bilateral connections for the data exchange?](#can-i-just-use-bilateral-connections-for-the-data-exchange)
* [**Stakeholders, Roles and Responsibilities**](#topic-stakeholders-roles-and-responsibilities)
    * [Who are the stakeholders of data spaces: Large vs. small players? Public vs. private sector? How to respect non-discrimination?](#who-are-the-stakeholders-of-data-spaces-large-vs-small-players-public-vs-private-sector-how-to-respect-non-discrimination)
    * [Who is responsible, and how are costs shared?](#who-is-responsible-and-how-are-costs-shared)
    * [What does the Anlaufstelle do in relation to data spaces?](#what-does-the-anlaufstelle-do-in-relation-to-data-spaces)
    * [How can the Anlaufstelle support me?](#how-can-the-anlaufstelle-support-me)
* [**Architecture and Standards**](#topic-architecture-and-standards)
    * [What is the time horizon of the target architecture: now, tomorrow, or 10 years from now?](#what-is-the-time-horizon-of-the-target-architecture-now-tomorrow-or-10-years-from-now)
    * [Can I just use DSSC, Gaia-X, IDSA, data mesh, or another standard as the reference architecture?](#can-i-just-use-dssc-gaia-x-idsa-data-mesh-or-another-standard-as-the-reference-architecture)
* [**Material**](#topic-material)
    * [What has changed from the previous version of the documentation?](#what-has-changed-from-the-previous-version-of-the-documentation)
    * [How binding are the documents?](#how-binding-are-the-documents)
    * [Which document is intended for which target audience?](#which-document-is-intended-for-which-target-audience)

---
    
## Topic: Basic Concepts and Terminology

### What is meant by data ecosystem?

The Swiss Data Ecosystem (DOeS) is a national network, orchestrated by a common governance, that enables interoperable, trustworthy, resilient and relevant primary and secondary use of data across business, science, public administration and the public. Regional and national data spaces, data platforms and domain-specific services together form the ecosystem, built on shared public base infrastructure and services (e.g. E-ID, the UID and GWR registers, I14Y, NGDI).

Source: Glossar DOeS V0.9, ch. 2.2; Leitbild DOeS V0.96, Management Summary

### What is meant by data space?

A data space is a technical and organisational structure, based on common governance and a decentralised setup, that enables and regulates trusted data transactions between different sources and actors. Data spaces are often sector-specific, defined by a purpose, clear rules and standards, and organised by a data space governance authority (Datenraumträgerschaft). Examples are the Swiss Health Data Space (SHDS), MODI (mobility) and agridata.ch (agriculture).

Source: Glossar DOeS V0.9, ch. 2.3; Leitbild DOeS V0.96, ch. 3.5

### What is the difference between data ecosystem and data space?

The data ecosystem is the overall national framework, and a data space is one building block within it. Besides data spaces, the ecosystem also includes other data sharing platforms (e.g. OGD platforms, data hubs, bilateral solutions), domain-specific services and common public infrastructure, all of which must meet the ecosystem’s minimum requirements. A data space additionally follows the data space guiding principles, such as a neutral governance authority, decentralised data storage and consent management.

Source: Leitbild DOeS V0.96, ch. 3, 3.5, 3.7, 6.2; Glossar DOeS V0.9, ch. 2.2–2.5

### What is the difference between a data hub and a data space?

In a data hub, data is centralised under one authority and shared one-to-many, which suits a few stable parties, large bulk transfers and near-real-time needs. In a data space, data stays with the provider, sharing is many-to-many with dynamic membership, and providers keep control through fine-grained access and usage policies. The Architecture Guidelines include a decision helper for choosing between a data space, a data hub and a point-to-point connection.

Source: Architecture Guidelines for Data Spaces V0.9, ch. 1.7 (Table 3)

### What is a data product?

A data product is a unit for sharing data that comprises the data, its metadata and all associated access and usage conditions, including licence terms. Unlike a plain dataset, it also has explicit semantics, defined quality, documented lineage, a clear owner responsible for its lifecycle, and is provided via defined interfaces. A data product does not necessarily imply commercial aspects.

Source: Glossar DOeS V0.9, ch. 5.3–5.4

<!--
### Relationships between the terms

See Image
-->

---

## Topic: Purpose and Added Value

### Is dataspace just a data catalogue / consent management system?

No. A data space has five operational capabilities (identity & trust management, data product provisioning, data discovery & access, data exchange & policy execution, traceability/observability) plus institutional capabilities such as governance, trust and long-term viability. The data product catalogue is only one of the obligatory building blocks, and consent management is an optional building block that can also be offered as a domain-specific service.

Source: Architecture Guidelines for Data Spaces V0.9, ch. 2.5, 4.2 (Table 18); Leitbild DOeS V0.96, ch. 4

### Why do we need guidelines? There are already many products for data exchange and data spaces.

The guidelines are deliberately product-neutral: they define what a data space must be able to do (capabilities and architecture building blocks) and which governance rules apply, while concrete products are solution building blocks chosen by each data space in its own reference architecture. Without common guidelines, today’s fragmented and poorly interoperable solutions would persist. Shared minimum requirements, terminology and building blocks keep data spaces interoperable and trustworthy, regardless of the products used.

Source: Architecture Guidelines for Data Spaces V0.9, ch. 1.6, 3; Leitbild DOeS V0.96, ch. 1.3; Glossar DOeS V0.9, ch. 7

### Can I just use bilateral connections for the data exchange?

Yes, if it fits your use case: direct, often bilateral data exchange solutions are part of the Swiss data ecosystem as long as they meet its minimum requirements, and a point-to-point connection suits a few parties with a one-to-one relationship. When many parties, dynamic membership, reuse across use cases or usage control are needed, a data space is recommended, because many bilateral connections lead to fragmentation and inconsistent security and governance.

Source: Leitbild DOeS V0.96, ch. 3.7; Architecture Guidelines for Data Spaces V0.9, ch. 1.7, 3.1 (“Trust over simplicity”)


---

## Topic: Stakeholders, Roles and Responsibilities

### Who are the stakeholders of data spaces: Large vs. small players? Public vs. private sector? How to respect non-discrimination?

The ecosystem addresses all legal and natural persons involved in data collaboration in Switzerland, in particular public administration (federal, cantonal and municipal), the private sector, research and civil society organisations. The population plays an indirect role as holder of digital self-determination. Within a data space, the key roles are the governance authority, operators, data providers and data users, complemented by data producers, data holders and data beneficiaries.

Source: Leitbild DOeS V0.96, ch. 1.2, 7; Governance DOeS V0.4, ch. 1.6; Glossar DOeS V0.9, ch. 3

### Who is responsible, and how are costs shared?

Responsibility is split across levels: the Confederation sets the strategic and regulatory framework, the DOeS governance sets minimum requirements and coordinates, and each data space governance authority is responsible for its data space, including its financing. Participants remain responsible for their own data, services and technical components. Each data space should build a diversified funding model from membership fees, usage fees and public funding (a hybrid model is recommended), with public funds possible where public interest justifies it.

Source: Governance DOeS V0.4, ch. 3.1; Governance-Leitfaden Datenraum V0.9, ch. 3.1, 5.3; Leitbild DOeS V0.96, ch. 4.1

### What does the Anlaufstelle do in relation to data spaces?

The Anlaufstelle Datenökosystem Schweiz is the central coordination and service point of the ecosystem, made up of a strategy board and an operational office. It supports the setup and operation of data spaces, coordinates cooperation between authorities, data spaces and other stakeholders, and promotes a consistent implementation of the governance and architecture. It provides the ecosystem-level documents, while each data space’s own documents (e.g. rulebook, reference architecture) remain the responsibility of the respective initiative.

Source: Governance DOeS V0.4, ch. 4, 4.1; Leitbild DOeS V0.96, ch. 2

### How can the Anlaufstelle support me?

The Anlaufstelle provides tools, methods and models that foster trustworthiness, offers conceptual support for building and developing data spaces and shared components, and promotes organisational, semantic, legal and technical interoperability. It can also help resolve conflicts, support the organisation of a data space’s governance bodies and enable knowledge exchange, for example via the Community of Practice. Templates and checklists are being published successively; contact: dataspaces@bk.admin.ch.

Source: Governance DOeS V0.4, ch. 4.1; Governance-Leitfaden Datenraum V0.9, ch. 1.1; Roadmap & Organisation, slide 2

---

## Topic: Architecture and Standards

### What is the time horizon of the target architecture: now, tomorrow, or 10 years from now?

The documents do not define an explicit time horizon. The Architecture Guidelines give guidance for designing data spaces today and are updated with a new version every year (the 2027 version will deepen cybersecurity, AI in data spaces and standards), while the Leitbild describes the long-term target picture, building partly on the principles of eCH-0279 “Architecture Vision 2050”.

Source: Architecture Guidelines for Data Spaces V0.9, ch. 1.2; Roadmap & Organisation, slide 6; Leitbild DOeS V0.96, ch. 6.1 (Note: answer derived, not stated explicitly)

### Can I just use DSSC, Gaia-X, IDSA, data mesh, or another standard as the reference architecture?

The DOeS documents are oriented to the DSSC Blueprint 3.0, IDSA and Gaia-X, and their building blocks are mapped to DSSC, so these frameworks can serve as a basis. The choice of standards lies with the data space governance authority, which must ensure they are compatible with the DOeS principles and minimum requirements and with Swiss law (e.g. the Data Protection Act), and do not create proprietary lock-in. International standards are not always transferable 1:1, and sector-specific laws take precedence.

Source: Governance-Leitfaden Datenraum V0.9, ch. 2.3; Architecture Guidelines for Data Spaces V0.9, ch. 1.4; Architecture Guidelines Attachment 1 (Mappings), ch. 2

---

## Topic: Material


## What has changed from the previous version of the documentation?

The Reference Architecture 2025 was redefined, extended and split into three documents: technical aspects are now in the Architecture Guidelines, governance topics in the Governance Guidelines for data spaces, and ecosystem topics in the Leitbild and the Governance DOeS. The term “reference architecture” is now reserved for the architecture maintained by each data space governance authority, and Attachment 1 maps the new building blocks to the 2025 components. Terminology was also sharpened, e.g. the ambiguous term “data intermediary” (Datenvermittelnde) was replaced by clearer roles.

Source: Architecture Guidelines for Data Spaces V0.9, ch. 1.4; Leitbild DOeS V0.96, ch. 2.4; Architecture Guidelines Attachment 1 (Mappings), ch. 4; Glossar DOeS V0.9, ch. 3.2

## How binding are the documents?

The Leitbild is for orientation, the Glossary and the Governance DOeS are strongly recommended for all actors, the two guidelines are recommendations, and the in-depth documents are for information only. The minimum requirements in the Governance DOeS are intended to be binding for participation in the ecosystem, but the document is currently a discussion paper; a binding form (e.g. law, ordinance or eCH standard) is planned. Within a data space, its rulebook is binding for participants and its reference architecture is binding for operators.

Source: Governance-Leitfaden Datenraum V0.9, ch. 1.2; Governance DOeS V0.4, ch. 1.1; Roadmap & Organisation, slide 

## Which document is intended for which target audience?

The Leitbild and the Governance DOeS target decision-makers and project leads from administration, business, research and civil society, and the Glossary targets everyone reading the DOeS documents or working on data spaces. The Governance Guidelines target data space governance authorities, operators, participants and service providers. The Architecture Guidelines target enterprise architects and technical implementation teams.

Source: “At a glance” sections of Leitbild DOeS V0.96, Glossar DOeS V0.9, Governance DOeS V0.4, Governance-Leitfaden Datenraum V0.9 and Architecture Guidelines V0.9

<!-- 
## Goal of Communications

ABB, DBB: ~40 people from offices who are candidates for the next data space. Inform vs. Feedback vs. Accept?

CoP: Interested parties -> Inform vs. Feedback

Current data space initiatives: Currently rather as input less as output

Exchange with data initiatives quarterly?

Involve BIT?

--> 

<!--
### Why not only events? Push or pull?

Simplicity over real-time

Focus on "finished" products to ensure quality. (Possibly 2 products for provisional, completed).
-->
