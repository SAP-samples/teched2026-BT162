# Discovering the rules - From policy documents to shared knowledge

[Workshop overview](../../README.md) · [Previous: Meet your business case](../ex0/README.md) · [Next: Putting the rules to work](../ex2/README.md)

This part follows the first half of the live workshop: asking the business agent for help before connecting Company Memory, then importing your local policy and discovering which rules apply. Your group shares a Company Memory environment, so uploads and changes may also affect other participants.


## 1. Start without Company Memory

Open your assigned business case and switch **Use Company Memory** off. This starts a fresh conversation. For the Europe Procurement example, make the suggested opening request — or phrase it in your own words:

> Please help me order 40 business laptops from BerlinTech for ACME Germany.

The agent can reason about the recorded offers, delivery deadline, budget, and purchase order. BerlinTech is cheaper than NordByte's telephone indication and meets the six-day business need. NordByte's indicated delivery would take twelve days.

Note the advice and any proposed action. Look for the distinction between ordinary business judgment and company-specific obligations: does the reply recommend proceeding, ask for more information, or suggest another step? What is the basis for that advice?

An agent can still raise sensible concerns without Company Memory. The purpose of this baseline is to compare its evidence and reasoning with the later conversation, rather than assume that it will always agree to release the order.

If you want to inspect the source policy yourself, use the regional policy document referenced in step 3. Keep Company Memory off for this baseline run.


## 2. Log in to Company Memory

Now access Company Memory in SAP Signavio's Lab Space. Log in using the credentials provided on the printed handout at your place, then open the app:

1. Click **Lab Space** at the bottom left (the flask icon).
2. On the next screen, use the **Search apps** input field on the right to search for **company memory**.
3. Locate the **Company Memory** card and click **Open**.


## 3. Create atoms from your local policy

ACME's global policy is already imported into Company Memory. Each group adds the regional policy for its assigned department; in this example, the Europe Procurement policy. Upload only your local policy — the global policy is already in place.

The activity has three parts:

1. Upload the regional policy document to Company Memory.
2. Ask the **Agent** in Company Memory to derive process atoms and make the applicable requirements **mandatory** using the same chat.
3. Review and approve the proposals, their scope, and their source, then confirm that the resulting knowledge is available for search.

> [!NOTE]
> Groups share a Company Memory environment, and choosing a different region in the workshop app does not create a separate policy store. However, it is ensured that each combination of region and department is unique in a workspace. E.g., there will not be another group working on Procurement in Europe in the same workspace.

The document provides company knowledge that was absent from the first conversation. Check whether the proposed atoms preserve the meaning of the policy and identify the appropriate organizational scope.

For this fictional purchase, the relevant policy topics include the evidence needed for a competitive purchase, use of a framework supplier, and the authority required for an exception. An approved budget alone does not answer all of those questions.


## 4. Find the applicable rules

Open the **Agent chat** in Company Memory and query the atom base for your case. For Europe Procurement, useful questions are:

> Which Procurement policies apply to ordering 40 business laptops for ACME Germany, Europe?

> Which process atoms are mandatory before this purchase can be completed, and what source supports each one?

Compare the answer with the source document available in the workshop and inspect:

- Whether the rules apply to the entity, region, and purchase in this case.
- Which requirements are mandatory, and what evidence would satisfy them.
- Whether the answer supports each requirement with a source.
- Whether global and regional requirements conflict or leave an authority question unresolved.

The aim is to understand the knowledge the business agent can retrieve. A plausible summary or a mandatory label still needs to be read in the context of the underlying requirement.


## What changes at this point?

The laptop offers, business deadline, approved budget, and purchase order are still the same. The new element is the policy knowledge available through Company Memory.

The next part reconnects the business agent and repeats the opening request, so you can examine how that evidence changes the advice.

---

[Previous: Meet your business case](../ex0/README.md) · [Back to workshop overview](../../README.md) · [Continue to Putting the rules to work](../ex2/README.md)
