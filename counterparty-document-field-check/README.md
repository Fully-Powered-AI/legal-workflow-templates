# Counterparty certificate and bond field check

When the other side hands over a bond, guarantee, standby letter of credit or estoppel certificate, the contracts manager gets each field set beside the contract and the file records, quoted, with every mismatch raised as a question for counsel. It never says whether the document is valid, sufficient or enforceable.

*Workflow template · Legal and contracts · version 0.1.0 · [Workflows Directory](https://fullypowered.ai/workflows/counterparty-document-field-check/)*

## The outcome

A contractor emails the bond, or a tenant returns the estoppel certificate, and a payment or a closing is waiting on it. Before it is passed along, somebody should set what it says beside what the contract and the company's own records say. A comma in a company name, a contract number with two characters missing, an amount that reads one way in words and another in figures: these are the details that slip past a skim. This workflow template looks for them in the same order every time.

For each field (the parties, the contract number and date, the project or premises, the amount, the dates), it copies every place the document states it and sets it beside the same field in the contract and in the company's records, with the page or clause of each. Each field gets one plain status: the same, different, stated two ways on the document itself, the contract and the records disagreeing, or not compared. Every mismatch becomes a short factual question. Signature blocks, seals and any attached power of attorney are recorded as found. Counsel opens one page with the gathering done and spends the time on the judgment.

This is preparation for a lawyer, and it stays preparation. It gives no legal advice. It never says whether the document is genuine, valid, in force, sufficient, acceptable or enforceable, and it decides nothing about legal meaning, merit, privilege, conflicts or deadlines. It counts no date: an expiry tied to an event, such as "one year after completion", is left for counsel. It compares no wording with a required form and judges no condition, such as a surety "acceptable to the owner". It does not check the issuer or anyone's authority to sign, and it contacts nobody. It names no case, statute or rule. It writes no letter or request to the other side and no replacement wording, even for a lawyer to edit. It sends, signs, files, accepts and calendars nothing, releases no payment, and changes no record. Every check is headed as a draft for the named lawyer, with a line for each point that lawyer confirms.

## Who starts the work, and when

The contracts manager, contract administrator, project administrator or lease administrator starts it when the other party to a contract or lease hands over the document it promised: a performance or payment bond from a contractor, a parent company guarantee, a standby letter of credit, or an estoppel certificate a tenant returns before a sale or a loan. It runs before anyone treats the document as received in order or releases a payment that waits on it.

A named lawyer decides: in-house counsel, the responsible attorney, or the outside counsel the company uses where it has no lawyer. In that case the check is addressed to outside counsel and goes to them; it is never handed to the business as an answer. If the company has no lawyer at all, the check is marked not ready for counsel and waits for one. A question such as "is this bond fine so we can pay?" is copied into the check for counsel and not answered.

It is not for the company's own certificates, which its signatory and counsel decide; not for insurance certificates, which [vendor insurance certificate check](https://fullypowered.ai/workflows/vendor-insurance-certificate-check/) reads against an approved requirement sheet; and not for letters, notices, claims or a call on a bond, which go to counsel as received.

## What they supply

- **The request:** which document and which contract or lease, the clause that calls for the document if known, the named lawyer, and any question someone has asked about it.
- **The document as received,** every page, with every attached page such as a power of attorney or a rider, as text or a PDF with readable text. One document per run.
- **The contract or lease** it is given under, every page, with every amendment the company holds.
- **A records sheet:** the company's own values for each field, from its contract register, vendor master, entity list, project particulars, ledger or deposit record. The default columns are Field, Value, Source and As of. If the headers differ, the workflow template stops and asks which is which.
- **A field list** for this kind of document, if the company keeps one. Without it, the workflow template's default list for a bond, a guarantee, a standby letter of credit or a tenant's estoppel certificate is used.

It works only from the company's own documents and records. It never asks for a password or a login code.

## What comes out

One check, marked as a draft for counsel, in six parts:

- **What arrived:** the title, every attached page, the page counts against the footers, any draft or specimen marking, and the clause that calls for the document, located and quoted.
- **The field comparison,** field by field: every value from the document, the contract and the records, quoted with its place, and one status. Where the contract states an amount as a percentage of a stated figure, the arithmetic is shown and labelled as arithmetic only, as is the difference between two amounts the document states for the same field.
- **Signatures, seals and attached authority,** as found, with any difference between a signer's name and the name on the power of attorney.
- **Statements not compared,** such as "no defaults" on an estoppel certificate, quoted and left alone: nothing is inferred from records that are silent.
- **Verification questions,** one for each mismatch, asking a fact only. Counsel decides whether, how and of whom each is asked.
- **Counsel to confirm:** a line for the document set, each question, each field not compared, authenticity and current status with the issuer (not checked), and whether the document can be accepted.

A check block closes it: pages read, the count of each status, the records rows used and not used, and a statement that no date was counted, no wording was compared with a form, and nobody was contacted. The preparer checks the draft against the documents and gives it to the named lawyer.

See the worked example with invented data in [EXAMPLE.md](EXAMPLE.md).

## Where it fits

- [Legal and contracts](https://fullypowered.ai/functions/legal-and-contracts/), where security documents and certificates from the other side arrive under contracts the team already administers.
- [Procurement and suppliers](https://fullypowered.ai/functions/procurement-and-suppliers/), where a contractor's or supplier's bond or guarantee is due before work or payment starts.
- [Construction](https://fullypowered.ai/industries/construction/), where performance and payment bonds arrive with a contract package and a mobilisation payment is waiting on them.
- [Real estate](https://fullypowered.ai/industries/real-estate/), where tenants return estoppel certificates before a sale or refinancing and each one has to be set against the lease file.
- [Energy](https://fullypowered.ai/industries/energy/), where project agreements call for bonds, guarantees and standby letters of credit from contractors and offtakers.
- [Acquisitions & integration](https://fullypowered.ai/situations/acquisitions-and-integration/), where a buyer's or lender's checklist calls for estoppels and security documents from many counterparties at once.
- [Growth & scaling](https://fullypowered.ai/situations/growth-and-scaling/), when more projects or properties bring more of these documents than one person can read closely.

It sits beside [contract amendment trace](https://fullypowered.ai/workflows/contract-amendment-trace/), which follows one provision through every amendment, and [rent-roll to lease-abstract match](https://fullypowered.ai/workflows/rent-roll-to-lease-abstract-match/), which checks a rent roll against lease terms. This one reads a single document the other side supplied, field by field, against your contract and your records.

## What has to change for your company

Name the lawyer who receives these checks, who stands in, and, where there is no lawyer on staff, the outside counsel who receives them. Decide which kinds of document come through it and agree a field list for each with counsel, adding the fields your contracts care about. Point the records sheet at your own systems and name the owner of each source, so questions about your own records reach the right desk. Name the person counsel may ask to confirm a document with its issuer. Decide where checks and counsel's answers are kept.

We sit with the person who receives these documents and the lawyer who reads them, write down how the check is really done, and set it up in the AI product your company has approved: ChatGPT, Claude, Copilot or Gemini. Confirm first that your company's policy allows documents from other parties to be used in it.

## What has been checked

Fully Powered AI wrote this workflow template from its own published map of the work. It was editorially reviewed on 12 November 2026. It has not been reviewed by a lawyer. It has not yet been tested in a client environment. It has not yet been tested as a packaged version in ChatGPT, Claude, Copilot or Gemini.

Testing in your company means running it on past documents whose checks counsel has already settled, and comparing: every field found in every place, every quotation exact, every near match called a difference, no date counted, nothing said about whether the document is good. Include a bond with a comma missing from a name, an amount that differs in words and figures, an expiry tied to completion, a power of attorney naming the signer differently, an estoppel certificate that lists fewer amendments than the file, and a request asking whether the document is fine to accept. [Pilot acceptance-test preparation](https://fullypowered.ai/workflows/pilot-acceptance-test-preparation/) builds that set, and [what we test before we call an AI workflow ready](https://fullypowered.ai/insights/what-we-test-before-a-workflow-is-ready/) describes the record we keep.

- Written by Fully Powered AI.
- Sources and rights reviewed.
- Editorially reviewed on 12 November 2026.
- Package format checked by script on every release.
- Tried once on its invented example in Claude on 12 November 2026. The record is in [TRIAL.md](TRIAL.md).
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

- [Vendor insurance certificate check](https://fullypowered.ai/workflows/vendor-insurance-certificate-check/)
- [Contract amendment trace](../contract-amendment-trace/)
- [Rent roll to lease abstract match](https://fullypowered.ai/workflows/rent-roll-to-lease-abstract-match/)

## Make it yours

This is the starting version. Fully Powered AI adapts workflow templates to how your company works, proves them on real work and rolls them out to the roles that use them. [Talk with us](https://fullypowered.ai/contact/).
