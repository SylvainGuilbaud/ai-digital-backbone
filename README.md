# AI Digital Backbone powered by InterSystems

[Version française](README.fr.md)

## The idea in one paragraph

Most organisations build AI project by project. Each project gets its own copy of the data, its own integration and its own governance. Pilots stall before they scale, and every new use case adds more fragmentation. The problem is not the AI models. It is the architecture underneath them.

A **digital backbone** is a unified data layer: a single source from which to access the truth. It is not a product. It is an **architectural discipline**, a way of building that lets AI scale.

## What makes it a backbone

Two capabilities:

1. **Unmatched interoperability.** Any system, any data model, any format, connected once. Healthcare is the proof point: HL7 v2, CDA documents, FHIR, DICOM, X12, device streams, files and free text, backed by 48 years of connecting health data (1978 to 2026).
2. **Real-time data management.** A common data plane where data is current the moment it changes, deduplicated, and projected rather than copied. Bulk transfers suit analytics. AI needs data as it flows.

The result is data that understands what is connected, can be questioned and analysed, and serves many use cases at the same time.

## The journey: record, insight, intelligence

| Stage | What it tells you | Built on |
| --- | --- | --- |
| Systems of record | What happened | Interoperability |
| Systems of engagement / insight | What it means | Real-time data management |
| Systems of intelligence | What to do next | AI tools and agents, with people in control |

## The four pillars

To scale AI you need four things:

- **Trust.** Trust as a capability: accurate access to structured, semi-structured and free-text data, in one place.
- **Compute.** Bring the compute to the data. Vector search, advanced RAG, prompt management, Python, JSON, AI APIs and MCP all run on the same data layer, with no data movement.
- **Governance.** Govern once, deploy everywhere. Fewer touch points, unified protection, access rules defined once and reused, better audit.
- **Controlled cost.** No sprawl of databases, licences and AI services. Reuse what exists and buy only what is needed.

## Connect once, reuse everywhere

Sources feed health adapters. FHIR services expose the data to every consumer: clinical applications, patient portals, AI tools and agents, partners and regional networks, and analytics. Every new use case reuses what is already there, so the cost of the next one falls.

## Healthcare as the proof point

Healthcare is highly regulated, the data is fragmented and time-sensitive, and the margin for error is low. The deck walks through worked examples:

- **InterSystems IntelliCare** (an AI-native EHR) runs operations and acts as a backbone for the record. The Digital Backbone extends its reach to the systems around it (devices, CRM, ERP and finance, payers, registries, imaging, genomics, social care).
- **HealthShare** gives a single view of the patient and a shared care plan. The backbone adds the organisation around it: who is overdue, what the next step costs, whether capacity exists.
- **Live scenarios** (morning ward round, emergency department, admin and bed management, and more) show AI agents working over one governed layer, with a human approving the decisions that matter.

The same pattern applies to financial services, government and manufacturing: trusted data, built-in governance and one foundation under many use cases.

## The business case on one page

The ROI view chains five factors: **volume x baseline x effect x adoption = benefit**. For the example facility (100,000 outpatient appointments a year), the baseline scenario gives:

- about 6,570 clinical hours freed per year (about 4.3 FTE);
- about £2.67M of capacity value per year (a prudent to optimistic range of £1.32M to £3.50M);
- a 13.1% reduction in average waiting time.

These are freed capacity, not cash savings, and potential benefits based on published data, not forecasts. Cancer-pathway figures are illustrative. The deck includes interactive sliders for each use-case family.

## The closing question

Stop asking "what AI should we build next?". Start asking "what foundation are we building on?"
