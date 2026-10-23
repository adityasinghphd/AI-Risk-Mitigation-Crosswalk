# Project overview

A safety framework can contain many safeguards without making clear how they work together. An evaluation may reveal a dangerous capability, a disclosure may inform another organization, and a release rule may require a response. Understanding the relationship between these actions requires more detail than a list of safeguard names.

This project connects a structured risk codebook to source-supported mitigation records. The risk model distinguishes how a risk arises (causes), which AI capabilities are involved (vectors), harms from specific uses (proximal harms), wider impacts (distal harms), and barriers to managing risk (standing challenges). The mitigation model records an intervention's actor, object, conditions, and relationship to those risk categories.

## Research outputs

The work has produced interactive taxonomy review tools, source-based mitigation records, consolidation artifacts, and an interactive demonstration of mitigation-to-risk relationships.

The completed AI Data Security pilot yielded 65 substantive controls and 85 risk links across 58 controls. A broader October 1 delivery contains 2,094 records and 2,720 links. A subsequent scoped consolidation repair accounted for 4,532 source records while preserving unresolved human-review questions. These scopes overlap; they do not form an additive total.

A separate feedback analysis covers 261 response records about the risk categories. Its aggregate methods and limitations are described in [methods and findings](methods-and-limitations.md#feedback-on-the-risk-categories); response records should not be read as a count of distinct experts.

The [evidence register](evidence-register.md) gives the dates and boundaries of these results. The [methods and limitations](methods-and-limitations.md) describe what the evidence supports.

## How the crosswalk can be used

The intended users include AI safety researchers and governance analysts reviewing safety documents. A concrete task is to determine which proposed interventions act on a particular risk, which observe it, and which depend on another actor or protective action. Each interpretation should be traceable to a source statement and coding rationale.

The [worked example](worked-example.md) shows how provider assurances, consumer acceptance requirements, and rejecting altered data differ. The [interactive explorer](https://adityasinghphd.github.io/AI-Risk-Mitigation-Crosswalk/research/mitigation-pathway-explorer.html) contains 377 actions from 16 sources. It lets readers browse by action type, subject, and risk, compare source passages and conditions, and distinguish source-explicit purposes from weakly inferred plausible connections and earlier analysis.

A longer-term application is to examine safeguards along pathways involving dangerous capabilities, failures of oversight, and loss of control. The completed data-security example demonstrates the mapping method. Its findings do not establish a measured reduction in severe AI risk.

The full taxonomy and its interactive review tools remain unpublished prototypes. This repository provides a working mitigation explorer and selected research evidence.

[Return to the project introduction](../../README.md)
