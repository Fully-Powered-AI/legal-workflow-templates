# Contract renewal and notice register

From your signed agreements and amendments, the contracts manager gets a register for counsel to confirm: each term, renewal and notice clause quoted with its section, cancel-by and send-by dates proposed only under counsel's own counting rules, and the windows sorted by proposed send-by date. Nothing is sent.

*Workflow template · Legal and contracts · version 0.1.0 · [Workflows Directory](https://fullypowered.ai/workflows/contract-renewal-notice-register/)*

## The outcome

Counsel sees every notice window in one place, sorted by how soon its proposed send-by date comes. One register holds every agreement's term, renewal wording, notice period, notice method and address, each quoted from the documents with its section. Agreements whose proposed send-by date is already before today sit at the top, each showing whether its proposed cancel-by date is before or after today. The register never says a window is open or closed, or that notice is late or in time: that is counsel's to say.

Each window carries two dates, kept apart on purpose: the cancel-by date, the date the company's own counting rule gives for the notice period, and the send-by date, that date less the rule's allowance for the delivery method the agreement names. What each date stands for is what the company's rule file says. Where the term end in the documents has passed, the status notes record no notice and no ending, and the company's rules allow it, a later term end is proposed by carrying the term forward step by step under those rules, with a line for counsel to confirm each renewal it assumes, so a register first built years ago still proposes this year's dates. Where the status notes record notice given or an ending, no notice date is counted and counsel confirms the status.

What it does not do: it gives no legal advice. It decides nothing about legal meaning, merit, validity, privilege, conflicts or deadlines. It sends, files, signs and calendars nothing. A date the agreement states is copied. A date that has to be counted is a proposed date, counted only under the company's own counting rules approved by its lawyer, with the working shown. Anything those rules do not cover is left uncounted for counsel. It works only from the company's own documents and rules, and names no law or case. Asked whether to renew, whether it is too late, what a clause means or for a law or case, it says that is for counsel and points to the line where counsel answers it.

## Who starts the work, and when

The contracts manager or legal operations lead starts it when the register is first built, on a fixed rhythm after that (monthly suits most companies), and whenever new agreements or amendments are signed. Counsel confirms: in-house counsel, the responsible attorney, or outside counsel where the company has no lawyer of its own, in which case the register goes to outside counsel and never to the business as an answer.

The business owner of each agreement receives their lines only after counsel has signed, and decides whether to renew. It is not for unsigned versions, for terms still being negotiated, or for saying what a clause means.

## What they supply

- **The signed documents** for each agreement: the agreement and every amendment, extension or order form that touches the term, renewal or notice, every page.
- **The agreement list:** Agreement ID, counterparty, title, the files, the business owner, and status notes saying whether notice has been given or the agreement has ended. If the column headers differ, the workflow template stops and asks.
- **The company's counting rules,** dated and approved by its lawyer: which kinds of notice clause staff may count, exactly how each is counted, what happens when a date lands on a closed day, how much time each delivery method needs, and whether staff may count from an amendment's wording in place of the section it replaces.
- **The closed-day list** the company keeps, with the period it covers.
- **Today's date,** the horizon (120 days unless changed) and who confirms.

The workflow template ships no counting rules. A company without them still gets every clause quoted and located and every copied date; each counted date goes to counsel.

## What comes out

One register, marked as a draft for counsel:

- **The register:** for each agreement, the documents read, the term, renewal, notice period, notice method, notice address and any renewal price wording, each quoted with its document and section; where an amendment replaces earlier wording, both wordings, with dates counted from the later one only where the company's own rules say so; the term end, cancel-by date and send-by date, each copied, proposed with its working, or marked "Not computed" with the reason.
- **Upcoming windows:** agreements whose proposed send-by date is before today, then those with no send-by date, then Urgent, Soon and Watch by days to the proposed send-by date.
- **Counsel to confirm:** one line for every date, every rolled-forward renewal, every wording question (where an amendment changes a clause, or the documents state a point two ways), every status note that records notice or an ending, and every notice method and address.
- **For business owners:** each owner's agreements and the decision needed, held until counsel signs.
- **Check:** documents and pages read, the tally of dates, the rules used, and anything referred to but not supplied.

The contracts manager reads it against the documents, recounts each proposed date on a calendar and gives it to counsel. Counsel confirms or corrects each line. Only then does a person give the business owners their lines and put dates on a calendar. Any notice is a matter for counsel, outside this workflow.

See the worked example with invented data in [EXAMPLE.md](EXAMPLE.md).

## Where it fits

- [Legal and contracts](https://fullypowered.ai/functions/legal-and-contracts/), which keeps the signed agreements and answers for every notice window.
- [Procurement and suppliers](https://fullypowered.ai/functions/procurement-and-suppliers/), whose supplier agreements carry renewal and notice clauses on many different dates.
- [Software and technology](https://fullypowered.ai/industries/software-technology/), where subscriptions on both sides carry renewal dates and notice methods that differ from one agreement to the next.
- [Professional services](https://fullypowered.ai/industries/professional-services/), where office, software and service agreements are signed by different teams and carry different renewal dates.
- [Manufacturing](https://fullypowered.ai/industries/manufacturing/), where maintenance, supply and equipment agreements run for years and carry fixed terms and renewal clauses.
- [Established businesses](https://fullypowered.ai/situations/established-businesses/), where dozens of agreements were signed over years and their dates live in memory.
- [Acquisitions and integration](https://fullypowered.ai/situations/acquisitions-and-integration/), where a whole set of inherited agreements needs every notice window found and put in front of counsel.

Once counsel has confirmed a supplier's dates, [vendor renewal review](https://fullypowered.ai/workflows/vendor-renewal-review/) prepares the commercial decision for that one supplier. Law firms reading court orders use the sister workflow template, [court-order deadline notice preparation](https://fullypowered.ai/workflows/court-order-deadline-notice-preparation/), built on the same rule: count only under the lawyer's own rules, and show the working.

## What has to change for your company

The counting rules are yours, and they are the heart of this. Your lawyer decides which kinds of notice clause staff may count, how a period in days or months is counted back from the term end, what happens when a date lands on a weekend or a day you are closed, how long each delivery method needs, and whether a term end that has passed may be carried forward. Everything the rules leave out goes to counsel. You name counsel for each run, and outside counsel if you have no lawyer in house; set your horizon and bands; map your agreement list's column headers once; and decide who gives business owners their confirmed lines and who calendars the dates.

We sit with the person who keeps the agreements and the lawyer who owns the rules, write down what is really done, and set it up in the AI product your company has approved: ChatGPT, Claude, Copilot or Gemini. Your company keeps control of how the work gets done.

## What has been checked

Fully Powered AI wrote this workflow template. It was editorially reviewed on 11 November 2026. It was tried on its invented example in Claude on 11 November 2026, and the record of that run is published with the template. The record also says what happened when people tried to draw advice out of it, and how its rules for answering such questions were tightened afterwards. It has not been reviewed by a lawyer. It has not yet been tested in a client environment. It has not yet been tested as a packaged version in ChatGPT, Claude, Copilot or Gemini.

Testing in your company means running it on past agreements whose dates your lawyer has already settled, and comparing: every clause quoted with the right section, every proposed date equal to the lawyer's, every uncovered count left alone, nothing sent. Include an agreement that has renewed twice, one with an amendment that replaces the notice clause, one with notice in business days and one whose date lands on a closed day. [Pilot acceptance-test preparation](https://fullypowered.ai/workflows/pilot-acceptance-test-preparation/) builds that set, and [what we test before we call an AI workflow ready](https://fullypowered.ai/insights/what-we-test-before-a-workflow-is-ready/) describes the record we keep.

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
- [Court-order deadline notice preparation](https://fullypowered.ai/workflows/court-order-deadline-notice-preparation/)
- [Pilot acceptance-test preparation](https://fullypowered.ai/workflows/pilot-acceptance-test-preparation/)

## Make it yours

This is the starting version. Fully Powered AI adapts workflow templates to how your company works, proves them on real work and rolls them out to the roles that use them. [Talk with us](https://fullypowered.ai/contact/).
