# Methods, findings, and limitations

## Completed mitigation pilot

The AI Data Security pilot used independent extraction passes, reconciliation, source review, and independent mitigation-type and risk-mapping passes followed by reconciliation and review. The agents came from the same model family.

The [mitigation coding process](mitigation-coding-process.md) shows the complete flowchart, the four agents reused across both stages, correction limits, and the human-review route.

The final delivery records 65 substantive controls and 85 risk links across 58 controls. Its 68 total source records also include one example and two grouping records. Five advisory human questions remain recorded. The seven original pilot examples remain in the evidence JSON. The current explorer is a broader selected release, described below.

## Current mitigation explorer

The [public explorer](https://adityasinghphd.github.io/AI-Risk-Mitigation-Crosswalk/research/mitigation-pathway-explorer.html) contains 377 actions from 16 research and guidance sources. It provides three ways to browse: **Type of Mitigation** describes how an action works using the research classifications; **Focus of Mitigation** uses separate presentation topics; **Explore by Risk** starts from the risks an action may address. Source passages, conditions, actors where specified, and differences between recommendations can be inspected within each action.

354 actions have at least one proposed specific risk connection; 23 have none. The latter include general recommendations and cases whose wording does not support a specific connection. Their explanations remain visible. These are counts for the selected release, not the whole research corpus.

Connections carry one of three labels. **Explicit in source** means the source states the relevant protective purpose. **Weakly inferred — plausible connection** means the analysis proposes a possible pathway that needs additional assumptions, shown with the link. **Earlier analysis** means the connection predates this distinction and has not yet been assessed on that basis. There are 8 source-specific explicit links, 36 inferred links, and 538 earlier links. One action can have several links, so these are not counts of actions. The explicit/inferred distinction describes the basis of an interpretation, not a measured effectiveness score.

The risk names shown are those used in the reviewed mappings. They do not constitute publication of the full prototype taxonomy, its definitions, or its review tools.

Source review and recorded correction improve traceability. They do not make model-generated mappings human-validated ground truth. The explorer retains source conditions and supports abstention where a risk target is not sufficiently specified.

## Feedback on the risk categories

A retained analysis covers **261 expert-feedback response records** about the risk categories. This counts responses, not a verified number of distinct experts. The responses were interpreted using AI-assisted coding and adjudication, followed by de-duplication and a check against the existing category coverage.

| Interpretation assigned to a response | Response records |
| --- | ---: |
| No change | 137 |
| Refine an existing category | 97 |
| Unclear feedback or interpretation | 64 |
| Expand or restructure coverage | 35 |
| Add a category | 21 |

The categories overlap, so the column must not be summed as a respondent total. These are AI-assisted interpretations of the feedback, not a vote on the taxonomy, proof of expert consensus, or a record that every suggestion was adopted. The [evidence summary](evidence/project-evidence.json) records the aggregate results and source-report hash. Raw responses, respondent identities, and unpublished category definitions are not part of this release.

## Consolidation status

The October 9 repair report accounts for 4,532 source records and records preservation checks. That scoped work was self-verified. Human grouping and mapping decisions, final acceptance, and a final distinct-mitigation count remain open.

The broader source-record delivery, the pilot, and the consolidation accounting overlap. They must not be summed or treated as counts of independent interventions.

## Interpretation limits

- Source records are occurrences in documents, not necessarily distinct interventions, deployments, or evidence of effectiveness.
- Reviewed relationships describe intended action and dependencies. They do not establish measured protection or a complete defense.
- A missing mapping may reflect source coverage, granularity, or insufficient evidence. It is not proof of a real-world mitigation gap.
- The historical data-security pilot uses prototype taxonomy v0.9.3. The expanded explorer retains mappings made with their original v0.9.2 or v0.9.3 versions; compatibility with later taxonomy work requires assessment.
- External usability evaluation remains to be conducted.

[Evidence register](evidence-register.md) · [Project introduction](../../README.md)
