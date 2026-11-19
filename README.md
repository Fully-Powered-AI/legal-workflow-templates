# AI workflow templates for legal and contract teams

FullyPowered Workflow Templates for in-house legal and contracts teams turn the AI your company already pays for into a team that knows how the work is done: a contracts manager with the renewal and notice register prepared for counsel, in-house counsel with the contract intake brief drafted for review, a legal operations lead with the outside-counsel invoice questions prepared. 14 workflow templates, made to be customized and deployed. All plain Markdown, all free, MIT license.

We are FullyPowered AI. We build AI workflows for companies, and these are the templates we start from. We publish them because a good starting point should be open to everyone. Copy one. Change it. Make it yours.

> [!TIP]
> **Missing a template that is not listed here, or want these customized for your organization? Reach out to us.** These are templates, made to be customized and deployed. FullyPowered AI customizes and builds AI workflows, connects them to your business systems, installs them in your agents and puts them in the hands of the people who own the work. [See more examples for in-house legal and contracts teams](https://fullypowered.ai/functions/legal-and-contracts/?utm_source=github&utm_medium=referral&utm_campaign=workflow-collections&utm_content=legal-readme&from=gh-legal-readme) · [Have one built for your team](https://fullypowered.ai/pricing/?utm_source=github&utm_medium=referral&utm_campaign=workflow-collections&utm_content=legal-readme&from=gh-legal-readme). Not sure where to start? Email hello@fullypowered.ai and a person will answer.

**Who this is for**

- General counsel and owners who want AI preparing the legal groundwork so lawyers spend time deciding.
- Heads of legal and contracts who want a careful, repeatable way to prepare each matter this week.
- The contracts or legal operations person who prepares the file, while a named attorney decides every legal question.

**What these are for**

- **Your best way of doing it, for the whole team.** One piece of work, written down precisely enough that an assistant prepares it the same way every time.
- **Work you can check.** Every template says what it needs, what it produces, what it checked and what it could not.
- **A person decides.** Anything that sends, posts, pays or changes a record waits for someone to approve it.
- **Tied into your business systems.** A workflow can be designed to pull from the systems your company already runs, and even push data back into them, with guardrails and a person approving. [Browse the Connectors Directory](https://fullypowered.ai/connectors/?utm_source=github&utm_medium=referral&utm_campaign=workflow-collections&utm_content=legal-readme&from=gh-legal-readme).
- **Free, open and portable.** MIT-licensed plain instructions that run in the assistant or agent your team already uses: ChatGPT, Claude, Claude Code, Claude Cowork, Codex, Copilot, Gemini, Grok, Perplexity.

**Quick start**

1. **Check an NDA against your lawyer's positions.** Open ChatGPT, Claude, Copilot or Gemini. Copy the text below into it, then paste in an NDA someone sent you and the written positions your lawyer has approved. No sign-in here and no download. You get a draft for your lawyer to read, not an answer on whether to sign.

   ```text
   You help me prepare a draft for our lawyer, [lawyer's name]. Below are
   one proposed NDA and the NDA positions our lawyer approved in writing.
   Compare the NDA clause by clause with those positions. For each clause,
   quote the NDA's words with its section, quote the matching position, and
   mark it MATCHES, DEPARTS or NOT COVERED. Flag any clause that goes
   beyond confidentiality, such as hiring limits or rights in ideas, and
   say only that the lawyer confirms. Do not say whether any clause is
   acceptable, enforceable or ready to sign. Do not write replacement
   wording or give legal advice. Send nothing. Our lawyer decides and
   signs. Today is [date]. NDA: [paste]. Positions: [paste].
   ```

2. Read what comes back. It marks what it checked and what is left for you. What comes back, with invented data:

   ```text
   Note to Dana Whitlow

   No stop applied.
   RESULT: COUNSEL TO REVIEW THE WHOLE NDA: §6 and §9.2 flagged under the
   beyond-confidentiality list. 7 departing, 2 not covered in all.
   §6 Residual knowledge, flagged under "grant, licence or transfer any
   right in intellectual property, feedback or ideas" (unsure).
   §9.2 under 9. General, flagged under "restrict hiring or soliciting
   anyone's people".
   That is for Priya Senn to decide, on every result, including one that
   matches every position.
   The draft and the NDA now go to Priya Senn, whatever the result.
   ```

3. Stop there. You will know if this is for you. When you want it fitted to your company, or built into your agents, [that is what we do](https://fullypowered.ai/pricing/?utm_source=github&utm_medium=referral&utm_campaign=workflow-collections&utm_content=legal-readme&from=gh-legal-readme).

The template prepares and checks, and a named attorney decides; nothing here is legal advice.

These are examples and a starting point, made to be changed to fit your own positions, forms and way of working. A workflow can be one step or many, and work that is not listed here can be built for your company.

## The legal workflow templates here today

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

The [FullyPowered Workflows Directory](https://fullypowered.ai/workflows/?utm_source=github&utm_medium=referral&utm_campaign=workflow-collections&utm_content=legal-readme&from=gh-legal-readme) lists every workflow template across functions and industries, with search. A machine-readable list of this repository is in [index.json](index.json).

For the work these templates come from, by team and by task, see [AI workflow examples for legal and contracts teams](https://fullypowered.ai/functions/legal-and-contracts/?utm_source=github&utm_medium=referral&utm_campaign=workflow-collections&utm_content=legal-readme&from=gh-legal-readme).

Law firms have their own page: [AI workflow examples for law firms](https://fullypowered.ai/industries/law-firms/?utm_source=github&utm_medium=referral&utm_campaign=workflow-collections&utm_content=legal-readme&from=gh-legal-readme).

## Licence and credits

MIT, in [LICENSE](LICENSE) and in every folder. Each folder's SOURCES.md names what the workflow template drew on. Published by [FullyPowered AI](https://fullypowered.ai/?utm_source=github&utm_medium=referral&utm_campaign=workflow-collections&utm_content=legal-readme&from=gh-legal-readme).
