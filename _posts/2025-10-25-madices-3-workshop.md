---
layout: post
title: MADICES 3 workshop
subtitle: October 20-24, 2025 in PSI, Switzerland
tags: [meeting, outreach]
comments: true
author: Edan Bainglass
---

The MADICES 3 workshop was held on October 20-24, 2025 in PSI, Switzerland. As with previous workshops, the audience included experts from ELN and WFMS initiatives, and ontology knowledge base developers and administrators. MADICES 3 saw an expansion of representation in the workflow management systems (WFMS) space, as well as participation from experts in AI/LLM applications for data interoperability and laboratory instrument control.

After a day of orientation including introductions, an expert panel, and selected talks, the remainder of the workshop was dedicated to breakout sessions on the various topics of interest (see below), conceptual alignment, development of concrete outcomes, and implementation time including a hands-on hackathon. The workshop ended with a summary session including presentations from each working group and a discussion of next steps, including continued engagement, collaboration, and dissemination of results, as well as plans for future MADICES workshops.

## Organizers

- Edan Bainglass (PSI, PREMISE)
- Caterina Barillari (ETH Zurich, PREMISE)
- Matthew Evans (University of Cambridge)
- Samantha Pearman-Kanza (University of Southampton and PSDI)
- Joseph Rudzinski (Humboldt-Universität zu Berlin and FAIRmat)
- Jörg Schaarschmidt (Karlsruhe Institute of Technology (KIT) and MaterialDigital)

## Sponsors

Along with PREMISE, MADICES 3 was supported by [CECAM](https://www.cecam.org/workshop-details/madices-3-machine-actionable-data-interoperability-for-the-chemical-sciences-1450) and [PSDI](https://www.psdi.ac.uk/).

## Working groups

- [Common schemas for workflows](https://github.com/MADICES/MADICES-2025/discussions/21)
- [Protocols and guidelines for semantic data exchange](https://github.com/MADICES/MADICES-2025/discussions/22)
- [Automated semantic annotations](https://github.com/MADICES/MADICES-2025/discussions/23)
- [AI/LLM-based tooling and best practices for semantic data pipelines](https://github.com/MADICES/MADICES-2025/discussions/24)
- [Controlling instruments with FAIR software](https://github.com/MADICES/MADICES-2025/discussions/25)
- [Community engagement on data interoperability](https://github.com/MADICES/MADICES-2025/discussions/26)
- [Common interfaces for ORD exchange across RDM platforms](https://github.com/MADICES/MADICES-2025/discussions/27)

## Highlights

- The common workflow schemas group extended the [Python Workflow Definition (PWD) schema](https://pubs.rsc.org/en/content/articlelanding/2025/dd/d5dd00231a) to cover while loops, nested workflows, and output data. [Ongoing discussion](https://github.com/MADICES/MADICES-2025/discussions/33) aims to bring PWD into FINALES to integrate PWD workflows into MAPs.
- Much [discussion](https://github.com/MADICES/MADICES-2025/discussions/22) took place regarding best practices for semantic data exchange, with a focus on bridging the knowledge gap and stress testing concepts on real-world use cases, including FINALES-MAPs interoperability and instrument-to-ELN data transfer. A summary report is in preparation.
- [Discussion](https://github.com/MADICES/MADICES-2025/discussions/23) regarding the integration of Semantikon into the AiiDA WFMS to facilitate automatic semantic annotation of AiiDA workflows is ongoing.
- The AI/LLM tooling group worked on developing LLM-based tools to assist in semantic annotation of datasets. Development of the [RDMage](https://github.com/MADICES/rdm-agent/) and [Herbert](https://github.com/MADICES/herbert) prototypes is ongoing.
- The instrument control group developed [an example for an RO-Crate-based protocol for transferring datasets from laboratory instruments to ELNs](https://github.com/MADICES/MADICES-2025/discussions/25#discussioncomment-14755321). The group also stress tested the [RO-Crate Schema Plus](https://researchobjectschema.github.io/ro-crate-schema-web/) specification and highlighted areas of concern for further development.
- Much [discussion](https://github.com/MADICES/MADICES-2025/discussions/4) took place regarding community engagement. A "Blueprint for community engagement to improve interoperability" draft is in preparation.
- The ORD exchange group continued the work of MADICES 2 towards a platform-agnostic interoperability protocol for ORD transfer between RDM systems. The PREMISE D1.3 and D2.2 deliverables were considered as a core use case. An ongoing collaboration between the PREMISE and FINALES teams aims to leverage FINALES as a middleware for ORD exchange between ELNs and WFMSs, with a summary of the discussion provided [here](https://github.com/MADICES/MADICES-2025/discussions/27#discussioncomment-14770400).

Discussion and research efforts will continue on the relevant repositories mentioned above.
