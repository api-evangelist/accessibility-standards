# Accessibility Standards (accessibility-standards)
Guidelines and technical specifications that ensure digital content, applications, and technologies are usable by people with disabilities, including standards like WCAG, Section 508, and ARIA. These standards help organizations meet regulatory requirements and demonstrate accountability to stakeholders.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/accessibility-standards/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Accessibility, Compliance, UX, Web Standards, WCAG, ARIA, Section 508, Disability

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-04-19

## APIs

### Web Content Accessibility Guidelines (WCAG) 2.2
The current stable web accessibility standard published by the W3C Accessibility Guidelines Working Group (AG WG). WCAG 2.2 comprises 13 guidelines organized under four principles (perceivable, operable, understandable, robust) with success criteria at three levels: A, AA, and AAA. It has been adopted as ISO/IEC 40500:2025 and is referenced by Section 508 and the EU Accessibility Act.

**Human URL:** [https://www.w3.org/WAI/standards-guidelines/wcag/](https://www.w3.org/WAI/standards-guidelines/wcag/)

#### Tags:

 - WCAG, Web Content, Accessibility, W3C, ISO

#### Properties

- [Documentation](https://www.w3.org/WAI/standards-guidelines/wcag/)
- [Specification](https://www.w3.org/TR/WCAG22/)
- [WCAG 2.2 Quick Reference](https://www.w3.org/WAI/WCAG22/quickref/)
- [GitHubRepository](https://github.com/w3c/wcag)
- [WCAG Success Criterion Schema](json-schema/wcag-success-criterion-schema.json)
- [WCAG Conformance Report Schema](json-schema/wcag-conformance-report-schema.json)
- [WCAG Success Criterion Structure](json-structure/wcag-success-criterion-structure.json)
- [WCAG Conformance Report Structure](json-structure/wcag-conformance-report-structure.json)
- [WCAG Success Criterion Example](examples/wcag-success-criterion-example.json)
- [WCAG Conformance Report Example](examples/wcag-conformance-report-example.json)

### WAI-ARIA 1.2
Accessible Rich Internet Applications (WAI-ARIA) 1.2 is a W3C Recommendation (June 2023) that defines semantic attributes enabling assistive technologies to interpret dynamic web content and complex interfaces. The suite includes Core Accessibility API Mappings, Accessible Name and Description Computation, and HTML/SVG API Mappings.

**Human URL:** [https://www.w3.org/WAI/standards-guidelines/aria/](https://www.w3.org/WAI/standards-guidelines/aria/)

#### Tags:

 - ARIA, Semantic, Screen Reader, W3C

#### Properties

- [Documentation](https://www.w3.org/WAI/standards-guidelines/aria/)
- [Specification](https://www.w3.org/TR/wai-aria-1.2/)
- [ARIA Authoring Practices Guide](https://www.w3.org/WAI/ARIA/apg/)
- [ARIA Role Schema](json-schema/aria-role-schema.json)
- [ARIA Role Structure](json-structure/aria-role-structure.json)
- [ARIA Role Example](examples/aria-role-example.json)

### Authoring Tool Accessibility Guidelines (ATAG) 2.0
ATAG 2.0 is a W3C Recommendation that defines standards for making authoring tools (CMSes, code editors, web-based tools) accessible to authors with disabilities, and for helping those tools generate accessible content.

**Human URL:** [https://www.w3.org/WAI/standards-guidelines/atag/](https://www.w3.org/WAI/standards-guidelines/atag/)

#### Tags:

 - ATAG, Authoring Tools, W3C

#### Properties

- [Documentation](https://www.w3.org/WAI/standards-guidelines/atag/)
- [Specification](https://www.w3.org/TR/ATAG/)

### User Agent Accessibility Guidelines (UAAG) 2.0
UAAG 2.0 is a W3C standard for browsers, browser extensions, media players, and other user agents that render web content. It defines how user agents should make web content accessible to users with disabilities either directly or in conjunction with assistive technologies.

**Human URL:** [https://www.w3.org/WAI/standards-guidelines/uaag/](https://www.w3.org/WAI/standards-guidelines/uaag/)

#### Tags:

 - UAAG, Browsers, User Agents, W3C

#### Properties

- [Documentation](https://www.w3.org/WAI/standards-guidelines/uaag/)
- [Specification](https://www.w3.org/TR/UAAG20/)

### Section 508
Section 508 of the Rehabilitation Act requires U.S. federal agencies to ensure their information and communication technology (ICT) is accessible to people with disabilities. The Revised 508 Standards (effective January 18, 2017) incorporate WCAG 2.0 Level A and AA success criteria for web and electronic content across seven chapters of requirements.

**Human URL:** [https://www.access-board.gov/ict/](https://www.access-board.gov/ict/)

#### Tags:

 - Section 508, Federal, Government, US Law, ICT

#### Properties

- [Documentation](https://www.access-board.gov/ict/)
- [Section 508 Web Content Development Guidance](https://www.section508.gov/develop/web-content/)

### Accessibility Conformance Testing (ACT) Rules Format 1.1
ACT Rules Format 1.1 (W3C Recommendation, February 2026) establishes a standardized format for documenting accessibility conformance testing rules. The framework supports automated, semi-automated, and manual testing and is used to create transparent, interoperable accessibility testing methodologies aligned with WCAG.

**Human URL:** [https://www.w3.org/WAI/standards-guidelines/act/](https://www.w3.org/WAI/standards-guidelines/act/)

#### Tags:

 - ACT, Testing, Conformance, W3C

#### Properties

- [Documentation](https://www.w3.org/WAI/standards-guidelines/act/)
- [Specification](https://www.w3.org/TR/act-rules-format/)
- [WCAG ACT Rules Repository](https://github.com/w3c/wcag-act-rules)

## Common Properties

- [Website](https://www.w3.org/WAI/standards-guidelines/)
- [W3C GitHub Organization](https://github.com/w3c)
- [W3C Accessibility Evaluation Tools List](https://www.w3.org/WAI/test-evaluate/tools/list/)
- [axe-core Accessibility Testing Engine](https://github.com/dequelabs/axe-core)
- [Pa11y Automated Accessibility Testing](https://github.com/pa11y/pa11y)
- [Accessibility Standards JSON-LD Context](json-ld/accessibility-standards-context.jsonld)
- [Accessibility Standards Vocabulary](vocabulary/accessibility-standards-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| Perceivable Content | Standards requiring that information and user interface components be presentable to users in ways they can perceive, including text alternatives for non-text content. |
| Operable Interface | Standards ensuring that user interface components and navigation are operable, including keyboard accessibility and sufficient time limits. |
| Understandable Information | Standards ensuring that information and the operation of the user interface is understandable, including readable text and predictable navigation. |
| Robust Technology | Standards requiring that content be robust enough to be reliably interpreted by a wide variety of user agents, including assistive technologies. |
| Conformance Levels | Three-tiered conformance model (Level A, AA, AAA) providing graduated accessibility requirements for organizations to target. |
| Automated Testing Rules | ACT Rules Framework providing standardized, machine-readable rules for automated accessibility conformance testing. |

## Use Cases

| Name | Description |
|------|-------------|
| Web Application Accessibility Auditing | Using WCAG 2.2 success criteria and ACT rules to audit web applications for accessibility compliance. |
| Federal Government ICT Procurement | Applying Section 508 standards when procuring or developing information and communication technology for U.S. federal agencies. |
| Accessible Rich Internet Application Development | Using WAI-ARIA attributes to make dynamic JavaScript-driven interfaces accessible to screen readers and assistive technologies. |
| Automated CI/CD Accessibility Testing | Integrating axe-core or Pa11y into continuous integration pipelines to catch accessibility regressions automatically. |
| Regulatory Compliance Documentation | Producing Voluntary Product Accessibility Templates (VPATs) and Accessibility Conformance Reports aligned with Section 508 and WCAG. |

## Integrations

| Name | Description |
|------|-------------|
| axe-core | Open-source accessibility testing engine by Deque Systems implementing WCAG 2.0/2.1/2.2 rules, integrates with browsers, testing frameworks, and CI tools. |
| Pa11y | Open-source Node.js tool for automated accessibility testing against WCAG standards, integrates with GitHub Actions and CI/CD pipelines. |
| Section508.gov | GSA's Government-wide IT Accessibility Program providing guidance, training, and resources for federal Section 508 compliance. |
| EU Accessibility Act / EN 301 549 | European standard referencing WCAG 2.1 AA, applicable to public and private sector digital services in EU member states. |
| ISO/IEC 40500:2025 | International Standards Organization adoption of WCAG 2.2, enabling global regulatory alignment with the W3C standard. |

## Artifacts

Machine-readable API specifications organized by format.

### JSON Schema

- [WCAG Success Criterion Schema](json-schema/wcag-success-criterion-schema.json)
- [WCAG Conformance Report Schema](json-schema/wcag-conformance-report-schema.json)
- [ARIA Role Schema](json-schema/aria-role-schema.json)

### JSON Structure

- [WCAG Success Criterion Structure](json-structure/wcag-success-criterion-structure.json)
- [WCAG Conformance Report Structure](json-structure/wcag-conformance-report-structure.json)
- [ARIA Role Structure](json-structure/aria-role-structure.json)

### JSON-LD

- [Accessibility Standards Context](json-ld/accessibility-standards-context.jsonld)

### Examples

- [WCAG Success Criterion Example](examples/wcag-success-criterion-example.json)
- [WCAG Conformance Report Example](examples/wcag-conformance-report-example.json)
- [ARIA Role Example](examples/aria-role-example.json)

## Vocabulary

- [Accessibility Standards Vocabulary](vocabulary/accessibility-standards-vocabulary.yaml) — Unified taxonomy mapping 7 resources, 6 actions, 4 workflows, and 5 personas across the accessibility standards landscape

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
