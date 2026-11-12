# Contract amendment trace

Before a question about a signed contract goes to counsel, the contracts manager has one dated history of the provision that matters: every signed document in order, each version quoted with its document and section, every gap marked, and a list for the lawyer to confirm. It never says which wording controls.

*Workflow template · Legal and contracts · version 0.1.0 · [Workflows Directory](https://fullypowered.ai/workflows/contract-amendment-trace/)*

## The outcome

The lawyer opens one page and sees how a provision got to where it is. The base agreement and every amendment sit in order of the latest date beside a signature, with the effective date each one states and each party's signature block shown as it is. Every place in a signed document that names the provision, the section that holds it, or words that apply across the whole agreement is quoted with the document, section and page, so every line can be checked against the page it came from. Places that name or redefine the terms it relies on are listed beside it. The awkward findings arrive before the call rather than during it: an amendment number that is missing, a version only one side signed, a signed paper still marked as a draft, a countersigned letter that names the provision, a document that gives two effective dates, a party whose name has changed. The gathering is done, and the lawyer's time goes to the judgment.

This is preparation, and it stays preparation. The workflow template gives no legal advice. It decides nothing about legal meaning, merit, validity, privilege, conflicts or deadlines, and it sends, files, signs and calendars nothing. When the papers conflict, it never says which version governs, and it never fills a gap with wording from an unsigned draft. Its search reports words found or not found, never an effect: it never says that a document changes the provision or leaves it alone, and it asks the lawyer whether any document changes it in words the search did not find. It never says whether or when a document was executed, and it never decides whether a letter or email changes the agreement: such papers are set aside and listed for the lawyer. It writes no clause, amendment or letter, even for a lawyer to edit, and it counts no date.

## Who starts the work, and when

A contracts manager, paralegal or operations person starts it when a question turns on one provision of an agreement that has been amended: a supplier announces a price increase, a customer claims a service credit, a renewal is coming up, or a buyer of the business asks about a contract.

A named lawyer confirms it: in-house counsel, the responsible attorney, or outside counsel where the company has no lawyer. In a company with no lawyer, it is the preparation done before calling outside counsel. Outside counsel is named first, and nothing is prepared until a lawyer is named. The trace is addressed to outside counsel and is never handed to the business owner as an answer.

## What they supply

- **The request:** the agreement, the provision's heading and its section number in the base agreement, and the lawyer who will read the trace.
- **The signed base agreement,** every page, signature page included.
- **Every amending document the company holds:** amendments, addenda, side letters and restated versions. Drafts and versions one side has not signed can be included; they are listed and never used. Letters, emails and notices can be included too; they are set aside, listed with what they name and who signed them, and left for the lawyer to decide on.
- **The contract register rows for the agreement,** if the company keeps a register. The default columns are Agreement, Document, Number, Execution date, Effective date and File. If the headers differ, the workflow template stops and asks which column is which.

It carries no law and no playbook. It works only from the company's own documents.

## What comes out

One draft, headed for the named lawyer and marked as a draft:

- **Documents in order,** each with the latest date beside a signature, its effective date in its own words, each party's signature block, any draft marking, and where the search terms for the provision were found in it, or that they were not found.
- **The provision's history:** the base text, then each place in a signed document where the search found the provision's number or heading, the section that holds it, or words that apply across the agreement, quoted with document, section and page. Where an amendment swaps words in place, the instruction is quoted and no combined text is written. Where an instruction was found only through the section that holds the provision or through general words, it is quoted with no view on whether it reaches the provision.
- **Related terms:** places that name the section defining a term the provision uses, or define the term again in different words, quoted and located, with no view on their effect.
- **Gaps and conflicts:** missing documents, versions with a blank signature block or a draft marking, letters and other papers set aside, conflicting or out-of-order dates, party names that change, section references that do not hold, two copies of one document that differ, and section numbers that skip. A version that is not traced is listed by its title, marking, number, stated date and signature blocks only; none of its wording is quoted.
- **For counsel to confirm,** each line a question: whether the document set is complete, whether and when each document was executed, one line for each gap, whether any document changes the provision in words the search did not find, which text controls and from when, and what it means.
- **A check:** pages read, search terms used, the register compared, and a statement that no date was counted.

The preparer reads the draft against the documents and gives it to the named lawyer. Only the lawyer answers the business or the other side.

See the worked example with invented data in [EXAMPLE.md](EXAMPLE.md).

## Where it fits

- [Legal and contracts](https://fullypowered.ai/functions/legal-and-contracts/): the trace is the groundwork counsel would otherwise do by hand before answering any question about an amended agreement.
- [Manufacturing](https://fullypowered.ai/industries/manufacturing/), where supply agreements are amended for prices, volumes and specifications year after year.
- [Consumer brands](https://fullypowered.ai/industries/consumer-brands/), where packaging, co-packing and distribution agreements pile up amendments and side letters.
- [Software technology](https://fullypowered.ai/industries/software-technology/), where customer and reseller agreements change at every renewal and the papers live in several places.
- [Established businesses](https://fullypowered.ai/situations/established-businesses/), with long-running agreements whose history only one person remembers.
- [Acquisitions & integration](https://fullypowered.ai/situations/acquisitions-and-integration/), where the buyer's counsel asks how a key contract stands and the answer has to be assembled from many documents.

It sits well before [vendor renewal review](https://fullypowered.ai/workflows/vendor-renewal-review/), which weighs whether to renew once counsel has said what the agreement provides. It is different from [contract renewal and notice register](https://fullypowered.ai/workflows/contract-renewal-notice-register/), which lists the term, renewal and notice clauses across many agreements, from [contract issues table for counsel](https://fullypowered.ai/workflows/contract-issues-table-for-counsel/), which sets one agreement's clauses against a counsel-approved playbook before negotiation, and from [rent-roll to lease-abstract match](https://fullypowered.ai/workflows/rent-roll-to-lease-abstract-match/), which checks lease fields against a rent roll. The trace follows one provision of one agreement back through every document that changed it.

## What has to change for your company

Name the lawyer who receives traces for each kind of agreement, and who stands in when that lawyer is away. With no lawyer on staff, name the outside counsel who receives them. Ask counsel which documents count as amendments in your company, such as side letters, change orders, order forms or renewal letters; until counsel says otherwise, everything else is set aside and listed for counsel. Tell the workflow template how your documents number their sections, so it searches the right forms. Point it at your contract register and its column headers, and decide where the lawyer's answers are recorded.

We sit with the person who gathers contracts and the lawyer who reads them, write down what is really done, and set it up in the AI product the company has approved: ChatGPT, Claude, Copilot or Gemini. Your company keeps control of how the work gets done.

## What has been checked

Fully Powered AI wrote this workflow template in its own words, taking one idea from a published package credited with it. It was editorially reviewed on 11 November 2026. It has not been reviewed by a lawyer. It has not yet been tested in a client environment. It has not yet been tested as a packaged version in ChatGPT, Claude, Copilot or Gemini.

Testing in your company means running it on past agreements whose history your counsel has already settled, and comparing: every instruction that names the provision found, every quotation exact, every gap marked, nothing said about which wording controls or whether a document changes the provision. Include an agreement with a missing amendment, one with an amendment that deletes the whole section without naming the provision, one with a draft only one side signed, one with a signed paper still marked as a draft, one with a countersigned letter, and one with two effective dates. [Pilot acceptance-test preparation](https://fullypowered.ai/workflows/pilot-acceptance-test-preparation/) builds that set, and [what we test before we call an AI workflow ready](https://fullypowered.ai/insights/what-we-test-before-a-workflow-is-ready/) describes the record we keep.

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

- [Vendor renewal review](https://fullypowered.ai/workflows/vendor-renewal-review/)
- [Contract renewal and notice register](../contract-renewal-notice-register/)
- [Contract issues table for counsel](../contract-issues-table-for-counsel/)
- [Rent roll to lease abstract match](https://fullypowered.ai/workflows/rent-roll-to-lease-abstract-match/)
- [Pilot acceptance-test preparation](https://fullypowered.ai/workflows/pilot-acceptance-test-preparation/)

## Make it yours

This is the starting version. Fully Powered AI adapts workflow templates to how your company works, proves them on real work and rolls them out to the roles that use them. [Talk with us](https://fullypowered.ai/contact/).
