# BT162 - SAP Company Memory preview: Give different AI agents the context to act

## Description

This repository contains the material for the SAP TechEd 2026 session **BT162 - SAP Company Memory preview: Give different AI agents the context to act**.

It provides a walkthrough of the workshop: how participants turn company policies into knowledge that AI agents can consult, compare the agents' advice, and explore what happens when that knowledge changes.

## Overview

AI agents can help with business decisions when they know the facts of a case. But do they know your company's rules? And which of those rules apply in your part of the organization?

This hands-on workshop explores how **Company Memory in SAP Signavio** allows to capture policies and rules across the whole company and provides the necessary guidance to agents.
Participants work with a business agent on a realistic decision, then add the relevant company policy to Company Memory, from where the agent can retrieve it.
By repeating the same request and comparing the answers, they experience how organizational knowledge changes and guides an agent's advice — and what happens when that knowledge is revised.

The setup uses a fictional global company with regional subsidiaries and departments, so similar requests can require different steps depending on where you sit. Each participant takes an assigned role and case; the detailed scenario is introduced in [Getting ready](exercises/ex0/README.md).

The workshop explores three questions:

- What is Company Memory and how can it support in managing knowledge?
- How can agents utilize Company Memory to apply company-specific policies?
- What happens when a rule changes, conflicts with another rule, or disagrees with a business record?

## Requirements

To complete the exercises in this repository, you need access to an SAP Signavio tenant with Company Memory enabled.
We will provide such a tenant for the workshop, as well as an interface to communicate with a prepared AI agent; details will be provided by the instructors during the workshop.

> [!NOTE]
> All names, company entities, suppliers, business records, and actions described in the workshop material are fictional.

## Exercises

Read the pages in order. Each page links back to this overview and onward through the walkthrough.

- [Getting ready - Meet your business case](exercises/ex0/README.md)
- [Discovering the rules - From policy documents to shared knowledge](exercises/ex1/README.md)
  - [Start without Company Memory](exercises/ex1/README.md#1-start-without-company-memory)
  - [Log in to Company Memory](exercises/ex1/README.md#2-log-in-to-company-memory)
  - [Create atoms from your local policy](exercises/ex1/README.md#3-create-atoms-from-your-local-policy)
  - [Find the applicable rules](exercises/ex1/README.md#4-find-the-applicable-rules)
- [Putting the rules to work - Compare, revise, and re-check](exercises/ex2/README.md)
  - [Connect Company Memory to the agent](exercises/ex2/README.md#5-connect-company-memory-to-the-agent)
  - [Respond to a new requirement](exercises/ex2/README.md#6-respond-to-a-new-requirement)
  - [Update the policy knowledge](exercises/ex2/README.md#7-update-the-policy-knowledge)
  - [Check the improved answer](exercises/ex2/README.md#8-check-the-improved-answer)
- [Exploring further - Optional activities](exercises/ex3/README.md)


## Contributing

Please read the [CONTRIBUTING.md](CONTRIBUTING.md) to understand the contribution guidelines.

## Code of Conduct

Please read the [SAP Open Source Code of Conduct](https://github.com/SAP-samples/.github/blob/main/CODE_OF_CONDUCT.md).

## How to obtain support

Support for the content in this repository is available during the actual time of the online session for which this content has been designed. Otherwise, you may request support via the [Issues](../../issues) tab.

## License

Copyright 2026 SAP SE or an SAP affiliate company and teched2026-BT162 contributors. Please see our [LICENSE](LICENSE) for copyright and license information. Detailed information including third-party components and their licensing/copyright information is available [via the REUSE tool](https://api.reuse.software/info/github.com/SAP-samples/teched2026-BT162).
