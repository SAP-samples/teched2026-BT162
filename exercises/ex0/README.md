# Getting ready - Meet your business case

[Workshop overview](../../README.md) · [Next: Discovering the rules](../ex1/README.md)

This page introduces the business case and shows how it fits into the rest of the workshop. In the live session, you first listen to a short introduction and then get to know your assigned case before you start working with the agents.


## Listen to the introduction

The workshop opens with an introduction to the idea behind it and the role of Company Memory. If you are reading this walkthrough on your own, the pages that follow cover the same ground: an agent that can retrieve company-specific rules, and the agents that help create, inspect, and use that knowledge.


## One company, different business contexts

The workshop uses **ACME**, a fictional global company with regional subsidiaries. Its departments work under global policies and additional regional rules. A useful answer to a business request therefore depends on both the facts of the case and the organizational knowledge that applies to it.

During the workshop, each participant works in one region and one department:

| Dimension | Workshop setting |
| --- | --- |
| Regions | Europe, North America, South America, Africa, and Asia-Pacific |
| Departments | Human Resources, Procurement, Operations, and Finance |
| Shared setting | ACME's global policies, supplemented by regional policies |
| Participant's task | Work with a business agent on a decision in their assigned context |

Every combination yields a different case, but each one follows the same pattern: a business agent that already knows the facts of the decision, and company policy that may govern how the decision can be made. This walkthrough follows one of those cases — **Procurement in Europe** — as a worked example. Your assigned case may differ; the steps are the same.


## Your case: 40 laptops for ACME Germany

In the Europe Procurement example, you work with the following case.

- **Your role:** procurement coordinator at ACME Germany.
- **People involved:** your buyer, who proposed the supplier, and the regional approvers referenced by company policy.
- **Requested outcome:** order **40 business laptops within six business days**.
- **Suggested opening request:** *Please help me order 40 business laptops from BerlinTech for ACME Germany.*

Your buyer proposes BerlinTech, and the budget and an unreleased purchase order are already recorded. The agent starts with these business facts:

| Item | Initial business facts |
| --- | --- |
| BerlinTech offer | EUR 12,000, delivery in five business days, written supplier quote available |
| NordByte indication | EUR 12,800, delivery in twelve business days, recorded from an informal telephone enquiry |
| Framework supplier record | NordByte is listed as ACME's European IT-hardware framework supplier |
| Other price evidence | An internal benchmark based on historical purchasing data |
| Budget and purchase order | Approved budget and unreleased purchase order for BerlinTech at EUR 12,000 |

A framework supplier holds a purchasing agreement with pre-agreed terms. Its presence in the business records does not, by itself, explain when using it is mandatory or who can approve an alternative. Those questions require company policy — which is where Company Memory comes in.

The agent already receives the case facts, so you can focus on the decision rather than re-entering the purchase file. The same initial facts and simulated actions are available with Company Memory switched off or on.


## How the agents work together

Company Memory provides workshop agents with a shared source of organizational knowledge. A **process atom** represents a specific piece of that knowledge, such as a rule, with its scope and source context.

| Agent | Role in the workshop |
| --- | --- |
| Agent in Company Memory | Proposes process atoms from a policy document and helps revise the knowledge, and helps participants find applicable atoms and inspect their requirements and supporting sources. |
| Business agent in the workshop app | Consults Company Memory when enabled, explains its advice, and proposes supported simulated actions for confirmation. |

You review the proposed knowledge and confirm actions in the business conversation. A proposed or completed action remains a fictional exercise event.


## What you will do during the workshop

1. Ask the business agent for help **without Company Memory**, then import your policy and discover the applicable rules.
2. Reconnect Company Memory and repeat the request, then respond to a new requirement and compare the advice again.
3. Explore further: try another assignment, another document format, or how the knowledge behaves when rules duplicate or conflict.

The important comparison is how policy evidence affects the agent's reasoning, required next steps, and explanation. It is not a promise that every conversation will use the same wording or reaches completion.

---

[Back to workshop overview](../../README.md) · [Continue to Discovering the rules](../ex1/README.md)
