# Architectural Decision Records (ADRs)

This repository contains a collection of Architectural Decision Records (ADRs) documenting significant architectural decisions made throughout the development process.

## Table of Contents
- [Architectural Decision Records (ADRs)](#architectural-decision-records-adrs)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
  - [ADR Template](#adr-template)
  - [Creating New ADRs](#creating-new-adrs)

## Introduction

Architectural Decision Records (ADRs) serve as a crucial tool for documenting and communicating architectural choices within a software project. They capture the context, rationale, and consequences of each decision, providing valuable insights for current and future contributors.

## ADR Template

To maintain consistency and clarity across ADRs, we use the following template:

```md
# mADR Title

## Context and Problem Statement

[Describe the context and problem statement prompting the need for this mADR.]

## Considered Options

* [Foo](example.com/#foo);
* [Bar](example.com/#bar).

## Decision Outcome

Chosen option: <Option>, because <reasoining>.
```

Feel free to customize this template to suit the specific needs and conventions of your project.

## Creating New ADRs

The process of creating new ADRs involves the following steps:

1. **Open an Issue**: Start by opening an issue to initiate discussion about the proposed architectural decision. Clearly articulate the context, rationale, and any alternatives considered.

2. **Discussion and Acceptance**: Engage in discussions within the open issue to gather feedback and refine the proposal. Once there is a consensus or the decision is approved by the relevant stakeholders, proceed to the next step.

3. **Create a Pull Request**: Create a pull request (PR) with a filename following the convention `<issue-id>-<short-description>.md`, where `<issue-id>` corresponds to the ID of the issue opened in step 1, and `<short-description>` provides a brief summary of the decision.

4. **Document the ADR**: In the pull request, document the decision using the ADR template provided above. Ensure that the ADR is clear, concise, and includes all relevant information.

5. **Review and Merge**: Collaborate with other team members to review the ADR. Address any feedback or suggestions for improvement. Once the ADR is finalized and approved, merge the pull request into the main repository.

By following this process, you can effectively capture and document architectural decisions in a structured and transparent manner.
