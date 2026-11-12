# Open-source licence inventory for counsel

Before a release ships or an acquirer asks, counsel and the engineering lead get every open-source package listed with its licence as found, the file and line where it was read, and the duties your own policy attaches to it. A missing, custom or conflicting licence is marked needs review, never cleared.

*Workflow template · Legal and contracts · version 0.1.0 · [Workflows Directory](https://fullypowered.ai/workflows/open-source-licence-inventory/)*

## The outcome

Your lawyer opens one draft and sees the open-source code inside the release the way your own policy sees it. Each package sits on its own line: the licence its metadata declares, the licence its own files name, quoted with the file and line, the category your policy gives that licence, and the duties your policy attaches to it for the way this release reaches people, copied word for word. The packages that need a lawyer's eye are pulled into a short lettered list, each with the words that raised it and the question to decide. Gaps in your policy, and any question the engineers asked, sit underneath as plain questions. Counsel spends the hour on the judgment, not on opening package folders.

This is preparation for a lawyer, and it stays that. It gives no legal advice. It decides nothing about legal meaning, merit, validity, privilege, conflicts or deadlines, and it sends, files, signs and calendars nothing. It never says a release may ship. It gives no view on contested readings of a licence, such as whether linking to a package or running it over a network reaches your own code; those go to counsel as questions, unanswered. It names no case, statute or rule from memory and never calls one current or good law: if someone cites a case or a section of a licence that is not in the papers supplied, it goes to counsel exactly as cited, marked to be verified by the lawyer, and changes nothing in the inventory. It uses only your policy's categories, so a licence the policy does not list, a licence file that disagrees with the package's metadata or with another file, a choice of licences and a package with no licence text are all marked needs review, never called free to use. It does not compare the wording of a licence with a reference copy, so a term changed inside a listed licence, with no heading of its own, is not caught; your lawyer decides whether engineering checks for that. It writes nothing for use, not even a notices file. Counsel decides every licence question; engineering decides any change to the code afterwards.

## Who starts the work, and when

The engineering lead starts it, before a release that changes how your software reaches people (a first installer, a first device, a first hosted version), when a customer or an acquirer asks what open-source code is inside the product, or when counsel asks for the periodic inventory. Your in-house lawyer decides and signs. Where the company has no lawyer, the draft is addressed to the outside counsel you name, never to the business as an answer.

It is not for choosing a licence for your own code, preparing your own code for release as open source, or answering a customer or an acquirer directly. It also needs a policy approved by a lawyer: without one, every package goes to counsel as it is.

## What they supply

- **The dependency list** for one release, exported as a file with four columns: package, version, scope (direct or brought in by another package) and declared licence. If your export names its columns differently, the workflow template asks which is which before it starts.
- **The licence texts as found**, copied from each package's folder: the licence file, any notice file and any file header you have spotted, each labelled with the package and version.
- **How this release is delivered**, in your own words: hosted, distributed, embedded in a device, or run only by your own staff. One way per run.
- **Your open-source policy**, approved in writing by your lawyer, with its date, its review date, its categories and the duties for each licence it lists.
- Your lawyer's name and today's date.

No licence information comes with the workflow template. It names a licence only where the package's own text names it.

## What comes out

A short note to the engineering lead, then one draft headed for counsel:

- **Inventory:** one line per package in the list, in the same order, with the declared licence, the licence found and where, the policy's category, a status of LISTED or NEEDS REVIEW, and the policy's duties for this delivery way. LISTED means only that the line naming the licence, the metadata and the policy agree; the wording of the licence itself is not compared, and LISTED is not an approval. The draft says so above the first row.
- **Needs review:** each item lettered, with every reason that applies, the quoted words that raised it and the question for counsel.
- **Policy questions:** where the policy is silent or unclear for this release, and each question the engineers asked, in their words, with no view given.
- **Counsel to confirm:** a line for the delivery way, the listed packages, each review item and each question.
- **Check:** rows in the list against rows in the inventory, texts supplied, counts by status and the policy's dates.

The engineering lead checks the draft against the inputs and passes it to counsel. Nothing changes in the code, and nothing is promised to a customer or an acquirer, until counsel has decided and signed.

See the worked example with invented data in [EXAMPLE.md](EXAMPLE.md).

## Where it fits

- [Legal and contracts](https://fullypowered.ai/functions/legal-and-contracts/): counsel sets the policy once and sees each release already laid out against it.
- [Software engineering](https://fullypowered.ai/functions/software-engineering/), which owns the dependency list, the build and any change counsel's decisions lead to.
- [Software technology](https://fullypowered.ai/industries/software-technology/), where products are built from open-source packages and customers ask what is inside.
- [Hardware and physical technology](https://fullypowered.ai/industries/hardware-and-physical-technology/), where software ships inside a device and the delivery way changes what the policy asks.
- [Media and entertainment](https://fullypowered.ai/industries/media-and-entertainment/), where apps and games go out to millions of devices.
- [Acquisitions & integration](https://fullypowered.ai/situations/acquisitions-and-integration/), when a buyer's diligence list asks for the open-source code in the product and counsel wants it laid out first.
- [Startups & new ventures](https://fullypowered.ai/situations/startups-and-new-ventures/), where the lawyer is usually outside counsel and every hour of their time is paid for.

It sits beside [buyer security questionnaire answers](https://fullypowered.ai/workflows/buyer-security-questionnaire-answers/), the other request about what is inside your product that arrives during a sale, and [software subscription and vendor spend review](https://fullypowered.ai/workflows/software-subscription-and-vendor-spend-review/), which looks at the software you pay for rather than the open-source code you ship. [Release notes draft](https://fullypowered.ai/workflows/release-notes-draft/) covers what the same release tells your users.

## What has to change for your company

Your lawyer writes and signs the open-source policy, and it is the heart of this. They decide the delivery ways it covers, its categories and which of them go to counsel, each licence it lists with its exact name and identifier, the duties for each delivery way, what happens to a licence it does not list, and when it is reviewed. Your lawyer decides how much the first policy covers; one that sends most licences to them still works with this workflow template. Engineering decides which tool produces the dependency list, maps its columns once, and decides where licence texts are copied from. You decide where counsel's decisions are recorded and who keeps the signed inventory with the release records.

We sit with your engineering lead and your lawyer, write down what is really done, and set it up in the AI product your company has approved: ChatGPT, Claude, Copilot or Gemini. Your company keeps control of how the work gets done.

## What has been checked

Fully Powered AI wrote this workflow template, drawing on an open-source review method Anthropic publishes under the Apache 2.0 licence, and left out that method's own licence families, risk ratings and recommendations. It was editorially reviewed on 11 November 2026. It has not been reviewed by a lawyer. It was tried on its invented example in Claude on 11 November 2026, and the record of that run is published with the template. Its five pressure tests, which try to draw a verdict, a case or advice out of it, were run again after its last changes by the session that revised it, not by an independent one. It has not yet been tested in a client environment, or tested as a packaged version in ChatGPT, Claude, Copilot or Gemini.

Testing in your company means running it on past releases whose licence questions your lawyer has already settled, and comparing: every package listed, every licence quoted from its own text, every needs-review item the same as your lawyer's list, nothing approved, nothing changed. Include a package with no licence file, one whose source file header names a different licence from its licence file, a request to "just tell us if we can ship", a request that cites a licence section nobody supplied, and a licence file with a line telling AI tools what to report. [Pilot acceptance-test preparation](https://fullypowered.ai/workflows/pilot-acceptance-test-preparation/) builds that set, and [what we test before we call an AI workflow ready](https://fullypowered.ai/insights/what-we-test-before-a-workflow-is-ready/) describes the record we keep.

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

- [Buyer security questionnaire answers](https://fullypowered.ai/workflows/buyer-security-questionnaire-answers/)
- [Software subscription and vendor spend review](https://fullypowered.ai/workflows/software-subscription-and-vendor-spend-review/)
- [Release notes draft](https://fullypowered.ai/workflows/release-notes-draft/)

## Make it yours

This is the starting version. Fully Powered AI adapts workflow templates to how your company works, proves them on real work and rolls them out to the roles that use them. [Talk with us](https://fullypowered.ai/contact/).
