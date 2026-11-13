# Fully Powered Workflow Templates: Legal

Counsel's time spent on the judgment, not the gathering. These workflow templates prepare, organise, check and track legal work for the lawyer who decides and signs. They give no legal advice, draft nothing for use, and have not been reviewed by a lawyer.

This repository holds 14 workflow templates for in-house counsel, contracts teams and the operations people who prepare work for outside counsel. Each one is a single piece of work with its own folder: what it is for and who starts it, the complete template an AI assistant follows, a worked example with invented data, what to change for your company, what has been checked, and its sources.

## The workflow templates

- **[Contract amendment trace](contract-amendment-trace/)**: Before a question about a signed contract goes to counsel, the contracts manager has one dated history of the provision that matters: every signed document in order, each version quoted with its document and section, every gap marked, and a list for the lawyer to confirm. It never says which wording controls.
- **[Contract intake brief](contract-intake-brief/)**: When another party's agreement arrives, counsel gets a one-page intake brief: what it is, read from its titles, the parties as named, what is missing, the requester's purpose and date, and the reviewer your own routing rules name. It comments on no term; counsel decides.
- **[Contract issues table for counsel](contract-issues-table-for-counsel/)**: Before counsel negotiates a vendor or customer agreement, the contracts team hands over one cited issues table: every clause quoted with its section, the playbook position it meets or departs from, the playbook’s fallback wording copied beside each departure, and the approver your matrix names. Counsel decides.
- **[Contract renewal and notice register](contract-renewal-notice-register/)**: From your signed agreements and amendments, the contracts manager gets a register for counsel to confirm: each term, renewal and notice clause quoted with its section, cancel-by and send-by dates proposed only under counsel's own counting rules, and the windows sorted by proposed send-by date. Nothing is sent.
- **[Counterparty certificate and bond field check](counterparty-document-field-check/)**: When the other side hands over a bond, guarantee, standby letter of credit or estoppel certificate, the contracts manager gets each field set beside the contract and the file records, quoted, with every mismatch raised as a question for counsel. It never says whether the document is valid, sufficient or enforceable.
- **[Inbound demand or claim intake record](inbound-demand-intake-record/)**: When a demand, claim or subpoena arrives, the company's lawyer gets one intake record the same day: who sent it, what it asks, every date it states, the facts and citations it relies on, related matters, where the records are, and a question on keeping them. It rates nothing and recommends nothing.
- **[Invention disclosure brief for patent counsel](invention-disclosure-brief/)**: Before the first call with patent counsel, the founder or engineering lead has one factual brief: the invention in the inventor's words, who contributed what and when, every outside demonstration, sale, talk or publication with its date and audience, and the records still missing. Counsel decides.
- **[IP ownership and licence question table](ip-terms-question-table/)**: Before an agreement or statement of work is signed, IP counsel gets one table of the ownership, assignment, licence, background-IP and confidentiality clauses, each quoted with its section, set against the company's own IP positions and led by whether the assignment words counsel expects were found.
- **[Legal hold custodian tracker](legal-hold-custodian-tracker/)**: Once counsel has issued a legal hold, your legal operations lead keeps one tracker for counsel: every custodian and system in counsel’s scope, who has acknowledged and who is overdue, who has left or changed role, the refresh date counsel set, and reminders copied from counsel’s own text for a person to send.
- **[NDA check against counsel's approved positions](nda-position-check/)**: Before anyone signs a proposed NDA, counsel gets every clause quoted with its section and set beside the positions counsel has approved: matching, departing or not covered. Any obligation beyond confidentiality sends the whole NDA to counsel. The check never says an NDA is ready to sign.
- **[Open-source licence inventory for counsel](open-source-licence-inventory/)**: Before a release ships or an acquirer asks, counsel and the engineering lead get every open-source package listed with its licence as found, the file and line where it was read, and the duties your own policy attaches to it. A missing, custom or conflicting licence is marked needs review, never cleared.
- **[Outside-counsel invoice questions](outside-counsel-invoice-questions/)**: When a law firm’s invoice arrives, legal operations has one worksheet ready: every line set against the agreed rates, the approved matter budget and the company’s own billing guidelines, each difference written as a neutral question for the firm. Nothing is sent, paid or rejected until people decide.
- **[Weekly status requests to outside counsel](outside-counsel-status-requests/)**: Every Monday, in-house counsel has a draft status request for each outside firm that owes one: what has happened since the last update, the dates on record to confirm, decisions pending and spend against budget, plus the matters skipped and why. Counsel edits and sends each one.
- **[Workplace investigation record for counsel](workplace-investigation-record/)**: When counsel directs a workplace investigation, the HR investigator turns the interview notes and documents into one restricted record for that lawyer: the allegations, who said what, a dated chronology, where accounts differ, an evidence index and the follow-up still open, each pinned to its source.

## How to use one

Open a folder and start with its README. Every folder stands alone, so copy the one you want and leave the rest. The templates are written for ChatGPT, Claude, Copilot and Gemini: paste the instruction block and the output format in as custom instructions, or load the folder in a product that reads `SKILL.md` packages.

To take the whole collection, press **Use this template** at the top of this page: it copies every folder into a repository in your own account, yours to change.

In every template a person starts the work, supplies the inputs and decides. The template prepares and checks. Anything that sends, posts, pays or changes a record waits for a person to approve it.

## What SKILL.md is

Each folder holds a file named `SKILL.md`. It is the technical file: the same instructions and output format as the template, in the packaged form that AI products which load instructions from a folder read. It is generated from `TEMPLATE.md`, so the two always agree. The workflow template is the whole folder; `SKILL.md` is one way of loading it. If your AI product does not read that format, use `TEMPLATE.md`.

## What "checked" means here

Each folder says exactly what was checked and when: who wrote it, that its sources and rights were reviewed, the date of its editorial review, and whether it has been tried on its invented example in a named AI product. Nothing is described as tested for a client unless it was. Test a template on your own past work before your team relies on it; each one comes with acceptance tests for that.

## More workflow templates

The [Fully Powered Workflows Directory](https://fullypowered.ai/workflows/) lists every workflow template across functions and industries, with search. A machine-readable list of this repository is in [index.json](index.json).

## Licence and credits

MIT, in [LICENSE](LICENSE) and in every folder. Each folder's SOURCES.md names what the workflow template drew on. Published by [Fully Powered AI](https://fullypowered.ai/).
