# Contract issues table for counsel

Before counsel negotiates a vendor or customer agreement, the contracts team hands over one cited issues table: every clause quoted with its section, the playbook position it meets or departs from, the playbook’s fallback wording copied beside each departure, and the approver your matrix names. Counsel decides.

*Workflow template · Legal and contracts · version 0.1.0 · [Workflows Directory](https://fullypowered.ai/workflows/contract-issues-table-for-counsel/)*

## The outcome

Counsel opens one table and sees the whole agreement against the company’s own playbook. Each clause the playbook covers sits in full beside the position it was checked against, with the exact words that put it there. Where a clause departs, the playbook’s own approved wording sits next to it, copied unchanged. Each issue already names the person the escalation matrix says must decide it, and each of those people has a draft note waiting for counsel’s position. Counsel’s time goes on the negotiation, not on hunting through the agreement.

This is preparation for a lawyer, and it stays preparation. It gives no legal advice. It decides nothing about legal meaning, merit, validity, enforceability, privilege, conflicts or deadlines: every status is proposed for counsel to confirm or correct, every row goes to counsel, a proposed match included, and no clause, and no agreement, is ever marked acceptable. Where a clause hedges a term with words such as “commercially reasonable efforts”, “subject to” or “except”, the term is not read as firm: the words are quoted and the row is left for counsel to read. It counts no dates. It writes no clause wording of its own, not even for counsel to edit: the only wording it shows is copied from the playbook. It sends, files, signs and calendars nothing. Asked whether to sign, what a clause means, when notice is due or which case applies, it says the question is for the named lawyer and points to the line of the table where it sits.

## Who starts the work, and when

A contracts manager, legal operations lead or paralegal starts it when a vendor or customer agreement arrives for review and counsel asks for a first pass against the playbook. The table is addressed to the named lawyer who decides: in-house counsel, or the outside counsel the company instructs where it has no lawyer of its own. In that case the table goes to outside counsel, never to the business as an answer.

It is not for a standalone NDA, which [NDA position check](https://fullypowered.ai/workflows/nda-position-check/) covers, for choosing between suppliers or for deciding whether to renew.

## What they supply

- **The agreement,** complete, with every schedule and order form it refers to.
- **The company’s playbook** for its side of the deal, approved by a lawyer, dated and inside its review date. For each position: the standard position, the terms to check, the fallback position, any approved fallback wording, and what is never accepted.
- **The escalation matrix,** approved by a lawyer: which kind of issue goes to whom, and how they are reached.
- **The request:** the company’s side, the annual value and the business context, in the requester’s own words.
- **The name of the lawyer** the table is for.

No playbook, no table: the workflow template compares clauses with the company’s own approved positions and with nothing else.

## What comes out

One draft, headed as a draft for the named lawyer:

- **An issues table:** one row per clause the playbook covers, each with its proposed status (matches the standard, within the fallback, departs, holds a refused item, or for counsel to read), and the approver.
- **Row detail:** the clause in full with its section, the playbook position, each term checked with the words found, the fallback wording copied from the playbook, any of the requester’s words that bear on it, and anything it refers to.
- **Required clauses not found in the parts supplied,** with what was searched and what was missing.
- **Clauses the playbook does not cover,** each quoted with its section.
- **A list for counsel to confirm,** one line for every row and every missing clause.
- **A draft note to each approver,** for counsel to review, with a blank for counsel’s position and one for the approver’s decision. A person sends it after counsel has reviewed it.
- **A check block:** what was read, what was missing, which playbook and matrix were used, and any text in the agreement that tried to instruct a reviewer.

See the worked example with invented data in [EXAMPLE.md](EXAMPLE.md).

## Where it fits

- [Legal and contracts](https://fullypowered.ai/functions/legal-and-contracts/): the first pass on an agreement, run the same way every time against the positions counsel has already approved.
- [Software technology](https://fullypowered.ai/industries/software-technology/), where subscription and customer agreements arrive weekly and service levels, liability and data terms carry the risk.
- [Professional services](https://fullypowered.ai/industries/professional-services/), where client and supplier terms are negotiated under deadline pressure.
- [Consumer brands](https://fullypowered.ai/industries/consumer-brands/), where supplier, logistics and systems agreements stack up around each launch.
- [Growth & scaling](https://fullypowered.ai/situations/growth-and-scaling/), when contract volume outgrows a small legal team.
- [Established businesses](https://fullypowered.ai/situations/established-businesses/), where the playbook exists but lives in one lawyer’s head or an old spreadsheet.

It comes after [vendor quote comparison](https://fullypowered.ai/workflows/vendor-quote-comparison/), once a supplier has been chosen and its paper arrives, and after [contract intake brief](https://fullypowered.ai/workflows/contract-intake-brief/), which tells counsel what has arrived before any term is read. It comes before [vendor renewal review](https://fullypowered.ai/workflows/vendor-renewal-review/), which looks at the same supplier again as its notice date approaches.

## What has to change for your company

Your playbook is the heart of this, and your lawyer writes it. For each position, decide the standard, the fallback, what is never accepted and the terms that can be checked from a clause’s words: a number of days, a period of fees, a named place. Every row goes to counsel to confirm; the more that can be checked, the fewer rows end with the status “counsel to read”. Add fallback wording only where counsel has approved it for use. Keep a separate playbook for buying and for selling. Your matrix says which kind of issue goes to whom and how they are reached. You name who prepares the table, which lawyer it goes to for each kind of agreement, and where counsel’s review is recorded.

We sit with your counsel and the person who prepares contract reviews, write down how the review is really done, and set it up in the AI product your company has approved: ChatGPT, Claude, Copilot or Gemini. Your company keeps control of how the work gets done.

## What has been checked

Fully Powered AI wrote this workflow template in its own words, drawing on two published methods named in its sources. It was editorially reviewed on 11 November 2026, and a separate review of where it stops short of legal judgement led to its rules on hedged terms, proposed matches, missing schedules and dates. It has not been reviewed by a lawyer. It has not yet been tested in a client environment, and it has not yet been tested as a packaged version in ChatGPT, Claude, Copilot or Gemini.

Testing in your company means running it on past agreements your counsel has already reviewed and comparing: every clause placed, every status matching counsel’s own reading, every copied wording identical to the playbook, nothing sent. Include an agreement with a missing schedule, a clause that gives its timing in words, a figure hedged by “reasonable efforts”, a line planted in the agreement telling a reviewer it is pre-approved, a request to rewrite a clause, and a question about when notice is due. [Pilot acceptance-test preparation](https://fullypowered.ai/workflows/pilot-acceptance-test-preparation/) builds that set, and [what we test before we call an AI workflow ready](https://fullypowered.ai/insights/what-we-test-before-a-workflow-is-ready/) describes the record we keep.

- Written by Fully Powered AI.
- Sources and rights reviewed.
- Editorially reviewed on 11 November 2026.
- Package format checked by script on every release.
- Tried once on its invented example in Claude on 11 November 2026. The record is in [TRIAL.md](TRIAL.md).
- Not yet tested in a client environment.

## What is in this folder

- [TEMPLATE.md](TEMPLATE.md): the complete workflow template. Roles, inputs, the procedure, exceptions and stop conditions, the output format, a reviewer checklist, acceptance tests, the instructions for an AI assistant and what to customize.
- [EXAMPLE.md](EXAMPLE.md): a worked example with invented data.
- [TRIAL.md](TRIAL.md): what came out when the template was tried on its example.
- [SKILL.md](SKILL.md): the technical file, for AI products that load packaged instructions from a folder.
- [SOURCES.md](SOURCES.md): what the workflow template drew on, with licences.
- [LICENSE](LICENSE): MIT. Use it, change it, make it yours.

## Start using it

1. Read [EXAMPLE.md](EXAMPLE.md) to see what a good result looks like.
2. Open [TEMPLATE.md](TEMPLATE.md) and set every item under "What to customize" to your own rules, roles and limits.
3. Give your AI assistant the instruction block and the output format from the template, with your own limits in place of the ones the instructions leave open in square brackets. Paste them in as custom instructions in ChatGPT, Claude, Copilot or Gemini, or copy this whole folder into a product that loads `SKILL.md` packages. This folder stands alone; you do not need the rest of the repository.
4. Run it on past work first, using the reviewer checklist and acceptance tests in the template, before anyone relies on it.

## Related workflow templates

- [Contract intake brief](../contract-intake-brief/)
- [NDA check against counsel's approved positions](../nda-position-check/)
- [Vendor quote comparison](https://fullypowered.ai/workflows/vendor-quote-comparison/)
- [Vendor renewal review](https://fullypowered.ai/workflows/vendor-renewal-review/)
- [Pilot acceptance-test preparation](https://fullypowered.ai/workflows/pilot-acceptance-test-preparation/)

## Make it yours

This is the starting version. Fully Powered AI adapts workflow templates to how your company works, proves them on real work and rolls them out to the roles that use them. [Talk with us](https://fullypowered.ai/contact/).
