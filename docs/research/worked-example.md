# What protects a consumer of third party AI data

A reviewer sees supplier assurances, certification requirements, and integrity checks in a safety document. Are these three equivalent protections against compromised training data? The completed project pilot distinguishes their operative functions and the actions on which they depend.

## Source and scope

Source: *AI Data Security: Best Practices for Securing Data Used to Train & Operate AI Systems*, May 2025, version 1.0. [Official publication](https://www.ic3.gov/CSA/2025/250522.pdf). Page references below use PDF page numbers. The descriptions are paraphrases of the project’s coded records, not direct quotations.

Mappings retain prototype taxonomy v0.9.3 and the pilot’s mitigation type snapshot. The three records illustrate related security decisions; the source does not establish that they form a complete jointly implemented defense.

| Record and source location | Intervention and actor | Reviewed relationship | Decision implication |
| --- | --- | --- | --- |
| ADS028, pages 10 and 13 | Foundation-model providers must be able to furnish training-data assurances; filtering attestations and test evidence are described as ideal | Enables protection against Supply Chain Vulnerability | Evidence must be assessed and used by the consumer; a provider assurance alone does not exclude compromised data |
| ADS030, page 10 | Consumers should strongly consider requiring provider certification before using third-party datasets or models, and exercise caution where assurances are absent | Conditional reduction of Supply Chain Vulnerability | Protection depends on substantiation and use in acceptance decisions; the wording is a contemplated requirement, not an unconditional mandate |
| ADS033, page 11 | Consumers downloading curated web-scale datasets check hashes and discard data that fails verification | Direct intended reduction linked to Data Poisoning under both Challenges and the Data Ingest vector | The specified action includes rejecting changed items before use; the vulnerability and ingestion route are different taxonomy roles |

These summaries preserve each source’s actor, trigger, and force. “Direct” describes the intended relationship, not demonstrated effectiveness. A hash check does not establish that the original dataset is safe or that every poisoning mechanism is prevented.

## A concrete reviewer task

Suppose an organization states that it obtains supplier assurances and performs integrity checks. An analyst using this crosswalk could ask:

1. Who examines the supplier evidence, and what is the acceptance decision?
2. Is the integrity check tied to rejecting failed downloads, or does it only log a discrepancy?
3. Which compromised-data routes are covered, and which would require additional evidence?

This is an illustrative application of the mappings, not an assessment of a particular organization. The value to test is whether the catalogue helps reviewers identify these distinctions accurately and trace them to evidence.

## Why abstention also matters

ADS002, page 4, identifies data minimization as a potential collection and processing focus. The pilot retains its mitigation classification but assigns no supported risk target because the statement does not specify the needed risk scenario. The tool preserves both the control and the rationale for abstention. Assigning a generic privacy link merely to fill the diagram would overstate the source.

## Explore and reproduce

Select “Provide supplier assurances,” “Consider requiring certification,” “Verify hashes and discard failures,” or “Consider data minimization” in the [explorer](https://adityasinghphd.github.io/AI-Risk-Mitigation-Crosswalk/research/mitigation-pathway-explorer.html). Expand the source panel to inspect record identifiers, page locators, conditions, and coding reasons. The [evidence summary](evidence/project-evidence.json) includes the selected records and original artifact hashes.
