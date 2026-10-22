# Putting the rules to work - Compare, revise, and re-check

[Workshop overview](../../README.md) · [Previous: Discovering the rules](../ex1/README.md) · [Next: Exploring further](../ex3/README.md)

With the regional knowledge available in Company Memory, you return to the business agent. This part follows the comparison with the baseline, then a new requirement that the knowledge has to absorb.


## 5. Connect Company Memory to the agent

Return to the business agent and turn **Use Company Memory** on. This starts a fresh conversation with the same initial business case. Repeat the original request:

> Please help me order 40 business laptops from BerlinTech for ACME Germany.

The agent can now search and read the company knowledge when reasoning about the purchase. Compare the reply with the baseline: which requirements does it identify, which sources does it cite, and what next action does it propose? Check whether the mandatory local atoms now affect the answer.

For Europe Procurement, the comparison focuses on several distinct questions:

| Question | Why it matters in this case |
| --- | --- |
| Is there enough written quote evidence? | BerlinTech supplied a written quote. NordByte's telephone indication and the internal benchmark are different kinds of evidence. |
| Can this supplier be used? | NordByte is the recorded framework supplier, while BerlinTech is proposed for the order. The company rules determine whether an exception is required. |
| Who may approve an exception? | The agent needs the applicable policy authority; the existence of a budget approval or a named actor is not sufficient evidence. |
| Does one completed step resolve the other requirements? | Recording a second written quote does not itself grant a supplier exception. A supplier exception does not itself supply the missing quote. |

The workshop's simulated actions let you work through supported next steps and confirm them individually. For example, obtaining comparable written quotes adds evidence to the purchase file; it does not silently approve every other aspect of the purchase.

A useful policy-informed reply explains unresolved requirements and the evidence needed to proceed. Where policies conflict or an action cannot resolve a requirement, the agent should explain the limitation. A new conversation clears the chat and simulated case state; it does not remove policies from the shared tenant.


## 6. Respond to a new requirement

Next, a **new policy change** is announced. The goal is to identify which existing atom needs to change, or where a new atom is needed. Then, check how the agent picks up the change in Company Memory.

For the Europe Procurement example, a representative new requirement is:

> Competitive IT-hardware purchases now require **two comparable written quotes**; a telephone indication no longer counts as competing evidence.

With that requirement, the case no longer has enough quote evidence: BerlinTech has a written quote, but NordByte's indication was recorded from an informal telephone enquiry. (Your assigned case may receive a different requirement; the pattern is the same — note what changed and where the knowledge falls short.)


## 7. Update the policy knowledge

Go back to Company Memory and tell the **Company Memory Agent** about the new requirement. Ask it to change the relevant atom or add a new one, make the updated requirement mandatory where appropriate, and check its scope and source. Confirm the change is available before returning to the business agent.

Inspect the proposed change and its scope before applying it:

- Did the Agent change the right atom, or propose a new one in the right place?
- Is the scope correct — the right region, department, and kind of purchase?
- Does the revised atom still carry a supporting source?


## 8. Check the improved answer

Return to the business agent with Company Memory on and start a **New conversation**. Repeat the same case request, and compare the answer with the previous run:

- Did the agent find and use the revised knowledge?
- Which decision, action, or explanation changed because of the edited atom?
- Which requirements are now satisfied, and which remain unresolved?

In the quote-evidence example, the agent should now treat a single written quote as insufficient and explain what additional evidence the purchase needs, rather than proceed on the earlier basis. Completion of a simulated action does not independently prove policy compliance.


## What the walkthrough illustrates

The business case supplies facts about a decision. Company Memory supplies organizational knowledge that can affect how an agent handles those facts. The Company Memory agent and business agent let you explore how that knowledge is created, inspected, used, and revised.

The comparison asks you to look beyond whether the agent reaches an answer: what evidence supports its advice, which requirements remain unresolved, and how does it respond when the knowledge changes? The optional activities in the next part extend the same idea.

---

[Previous: Discovering the rules](../ex1/README.md) · [Back to workshop overview](../../README.md) · [Continue to Exploring further](../ex3/README.md)
