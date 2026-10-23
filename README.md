# AI Risk–Mitigation Crosswalk

This project connects structured descriptions of AI risks with the interventions proposed to address them. The work combines risk-taxonomy development and source-based mitigation mapping to make it easier to examine what a safeguard does, who must act, and which dependencies remain unresolved.

## Work completed so far

- **Risk taxonomy and review tools.** Developed a five-axis risk model covering causes, vectors, proximal harms, distal harms, and standing challenges, together with internal interactive tools for reviewing the taxonomy and its expanded categories. These prototypes are not included in the public release.
- **Feedback on the risk categories.** Analyzed 261 expert-feedback response records using AI-assisted coding and adjudication. [Aggregate findings](docs/research/methods-and-limitations.md#feedback-on-the-risk-categories) explain what was analyzed and its limits.
- **Mitigation extraction and mapping.** Completed a data-security pilot with 65 substantive controls and 85 supported risk links across 58 controls. A broader October 1 delivery contains 2,094 source records and 2,720 risk links.
- **Consolidation and traceability.** Completed a scoped repair and preservation review accounting for 4,532 mitigation source records, retaining unresolved questions for human review.
- **Interactive mitigation explorer.** Published a browsable collection of 377 actions from 16 research and guidance sources, with source comparisons, mitigation types, subject filters, and risk connections. Of these, 354 have proposed risk connections and 23 remain general recommendations or lack a supported specific connection. Source-explicit, weakly inferred plausible connections, and earlier analysis are clearly distinguished; inferred links show their assumptions.

These outputs represent different, overlapping stages of the research. Their counts should not be added. The [evidence register](docs/research/evidence-register.md) explains the dates, units, and review status behind each result.

## Explore the work

Start with the [worked data-security example](docs/research/worked-example.md), which distinguishes supplier assurances, consumer acceptance requirements, and rejecting altered data. Then open the [Mitigation Pathway Explorer](https://adityasinghphd.github.io/AI-Risk-Mitigation-Crosswalk/research/mitigation-pathway-explorer.html) to inspect the underlying relationships. The explorer opens as an interactive page in your browser.

For more context:

- [Project overview](docs/research/project-overview.md)
- [Mitigation coding process and four-agent flowchart](docs/research/mitigation-coding-process.md)
- [Methods, findings, and limitations](docs/research/methods-and-limitations.md)
- [Evidence register](docs/research/evidence-register.md)
- [Machine-readable evidence and example records](docs/research/evidence/project-evidence.json)

The two taxonomy review tools remain research prototypes; their publication scope is still being considered. This repository currently includes the mitigation explorer and the supporting research documents linked above.

Final whole-corpus acceptance and external usability evaluation remain open. Reviewed mappings describe intended mechanisms and dependencies; they do not establish measured mitigation effectiveness.

*Mitigation explorer updated 22 October 2026. Supporting results retain their original dates and taxonomy versions.*

