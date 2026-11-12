# Inbound demand or claim intake record

When a demand, claim or subpoena arrives, the company's lawyer gets one intake record the same day: who sent it, what it asks, every date it states, the facts and citations it relies on, related matters, where the records are, and a question on keeping them. It rates nothing and recommends nothing.

*Workflow template · Legal and contracts · version 0.1.0 · [Workflows Directory](https://fullypowered.ai/workflows/inbound-demand-intake-record/)*

## The outcome

The letter that lands on a Monday morning reaches the company's lawyer that afternoon as a record they can work from. Every demand, date, fact and citation is copied in the sender's own words with its page and paragraph, and every record the letter mentions is named in the letter's own words, so nothing the sender alleges is restated as fact. The company's own matter list has already been searched for the same party and the same order or contract numbers. The systems that hold the records the letter talks about are named, with their owners and anything they delete automatically. The lawyer starts on the judgment instead of the gathering.

**What it does not do.** It gives no legal advice. It decides nothing about legal meaning, merit, validity, privilege, conflicts or deadlines. It sends, files, signs and calendars nothing, and contacts no one. It does not rate the claim, offer response options or recommend anything. A date the letter states is copied; a period such as "within 14 days" is copied and left uncounted for the lawyer. A citation appears only because the sender cited it, marked for the lawyer to verify. It writes no reply, no holding note and no instruction to keep records. Whatever follows is the lawyer's decision.

## Who starts the work, and when

Whoever has the document starts it, on the day it arrives: a legal operations coordinator or paralegal where the company has a legal team, or the operations manager, office manager or founder where it does not. The record is always addressed to a named lawyer: in-house counsel, or the company's outside counsel when there is no lawyer on staff. When it goes to outside counsel, it goes to them as a record to work from, never back to the business as an answer. Nothing is prepared until a lawyer is named.

## What they supply

- The document, every page, and the enclosures that came with it.
- A short note on how it arrived: when, by what route, to whom, and any second copy.
- The lawyer the record is for.
- The company's matter list, exported as a table, so related matters can be found.
- The company's records map: each system, the kinds of records kept there, the person responsible, and any automatic deletion.

The workflow template carries no law and no court rules. Everything in the record comes from the letter itself and from lists the company already keeps.

## What comes out

Two things, both for the named lawyer:

- **The intake record,** marked as a draft. What arrived and how; who sent it; each demand in the sender's words, with the letter's own arithmetic checked; every date, copied, with each period marked as not counted; the facts alleged, quoted; each citation, copied and marked for the lawyer to verify; what the sender says will happen next; possible related matters from the company's list; where the relevant records are kept; a question for the lawyer on keeping records, with the company's deletion rules beside it; and a list of points for the lawyer to confirm or decide, one line each.
- **A list of documents to gather,** each showing the system it sits in and the person responsible for it, every item marked "not gathered" until the lawyer says who gathers what.

The person who supplied the inputs reads the record against the letter and hands it over. The lawyer decides everything that follows, including whether anyone replies.

See the worked example with invented data in [EXAMPLE.md](EXAMPLE.md).

## Where it fits

- [Legal and contracts](https://fullypowered.ai/functions/legal-and-contracts/): the first hours after a letter arrives, when facts are easiest to lose and a lawyer's time is best spent on the decision.
- [E-commerce and retail](https://fullypowered.ai/industries/ecommerce-and-retail/), where letters about orders, suppliers and product listings arrive at companies that often have no lawyer on staff.
- [Manufacturing](https://fullypowered.ai/industries/manufacturing/), where the papers a letter refers to (purchase orders, delivery records, supply agreements) are spread across several systems.
- [Software and technology](https://fullypowered.ai/industries/software-technology/), where demands and subpoenas reach a small team whose records sit in email, chat and shared drives with different deletion rules.
- [Established businesses](https://fullypowered.ai/situations/established-businesses/), with years of matters on file and a past dispute with the same party that should not be missed.
- [Growth and scaling](https://fullypowered.ai/situations/growth-and-scaling/), when letters start arriving faster than the founder can forward them with the right facts attached.

It sits upstream of [court-order deadline notice preparation](https://fullypowered.ai/workflows/court-order-deadline-notice-preparation/), which handles orders once a matter is in court, and of [legal hold custodian tracker](https://fullypowered.ai/workflows/legal-hold-custodian-tracker/), which keeps track of a hold once counsel has answered the question on keeping records and issued one. It is not the same work as [complaint and refund request handling](https://fullypowered.ai/workflows/complaint-and-refund-request-handling/), which answers customers under the company's own policy, or [supplier issue notice](https://fullypowered.ai/workflows/supplier-issue-notice/), which the company sends out.

## What has to change for your company

Name the lawyer before the first letter arrives, and a stand-in for the weeks that lawyer is out. A company with no lawyer on staff names its outside counsel. Export the matter list with its usual columns, and tell the AI assistant once if your headers differ. Keep a records map listing every system, the records in it, the person responsible and any automatic deletion, agreed with your lawyer and the system owners. Counsel decides any heading or marking the record carries, and where records like this are stored. It runs in ChatGPT, Claude, Copilot or Gemini, from files you supply; check with your lawyer that demand letters and claims may go into the AI product you have approved.

## What has been checked

Fully Powered AI wrote this workflow template. It was editorially reviewed on 11 November 2026. It has not been reviewed by a lawyer. It has not yet been tested in a client environment. It has not yet been tested as a packaged version in ChatGPT, Claude, Copilot or Gemini.

Testing in your company means running it on past letters your lawyer has already handled, and checking that every demand, date and citation is copied word for word, that no period has been turned into a date, that every citation is left for the lawyer, and that nothing was sent. Include a letter with a missing enclosure, one that cites a case that does not exist, one with a line addressed to an AI assistant, and a request to "just tell us whether to pay". [Pilot acceptance-test preparation](https://fullypowered.ai/workflows/pilot-acceptance-test-preparation/) builds that set, and [what we test before we call an AI workflow ready](https://fullypowered.ai/insights/what-we-test-before-a-workflow-is-ready/) describes the record we keep.

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

- [Court-order deadline notice preparation](https://fullypowered.ai/workflows/court-order-deadline-notice-preparation/)
- [Legal hold custodian tracker](../legal-hold-custodian-tracker/)
- [Complaint and refund request handling](https://fullypowered.ai/workflows/complaint-and-refund-request-handling/)
- [Supplier issue notice](https://fullypowered.ai/workflows/supplier-issue-notice/)

## Make it yours

This is the starting version. Fully Powered AI adapts workflow templates to how your company works, proves them on real work and rolls them out to the roles that use them. [Talk with us](https://fullypowered.ai/contact/).
