# Outside-counsel invoice questions: an invented example

*Illustrative example with invented data.* Company A, an invented 400-person specialty insurer, and Firm B, the invented law firm it uses on a dispute with an invented distributor, Supplier C, are not real organisations. Every person, matter, invoice, rate, budget, billing guideline and check map below is invented. The billing guidelines are one invented company’s rules and must not be used for real work.

The legal operations manager’s inputs come first, in full, then what the workflow template prepares.

## Input 1: the request

Sent by Tamsin Rook, legal operations manager.

```
Invoice B-26-0412 from Firm B came in on 6 November for the Supplier C
distribution dispute (matter LM-2026-014). Please prepare the invoice
questions worksheet.

Company: Company A
Firm: Firm B; responsible attorney P. Marlow, partner
Named lawyer: Leona Barsby, senior counsel, matter lead
Legal budget owner: Martin Ashgrove, general counsel
Run by: Tamsin Rook, legal operations manager
Today: 2026-11-11
Settings: defaults
```

## Input 2: the invoice header

```
Invoice, Firm, Matter, Invoice date, Period from, Period to, Fees, Expenses, Total, Currency
B-26-0412, Firm B, LM-2026-014, 2026-11-06, 2026-10-01, 2026-10-31, 15945.00, 1760.00, 17705.00, USD
```

## Input 3: the invoice lines

```
Invoice | Line | Date | Type | Timekeeper | Role | Phase | Hours | Rate | Amount | Description
B-26-0412 | 1 | 2026-10-01 | Fee | P. Marlow | Partner | MED | 1.5 | 640.00 | 960.00 | Review outline of mediation statement and send comments to S. Ruane.
B-26-0412 | 2 | 2026-10-02 | Fee | S. Ruane | Senior associate | DOC | 3.0 | 450.00 | 1350.00 | Review supplier delivery records, batch 4, for responsiveness.
B-26-0412 | 3 | 2026-10-02 | Fee | S. Ruane | Senior associate | DOC | 3.0 | 450.00 | 1350.00 | Review supplier delivery records, batch 4, for responsiveness.
B-26-0412 | 4 | 2026-10-05 | Fee | K. Ostby | Associate | DOC | 6.0 | 380.00 | 2280.00 | Review warehouse email export; prepare document index; call with J. Penhale on coding; update review protocol.
B-26-0412 | 5 | 2026-10-05 | Fee | J. Penhale | Paralegal | DOC | 2.0 | 180.00 | 360.00 | Load warehouse email export to review platform.
B-26-0412 | 6 | 2026-10-12 | Fee | R. Tiller | Associate | DOC | 4.0 | 340.00 | 1360.00 | Second-level review of priority documents.
B-26-0412 | 7 | 2026-10-20 | Fee | P. Marlow | Partner | MED | 3.0 | 640.00 | 1920.00 | Attend internal strategy meeting on mediation.
B-26-0412 | 8 | 2026-10-20 | Fee | S. Ruane | Senior associate | MED | 3.0 | 450.00 | 1350.00 | Attend internal strategy meeting on mediation.
B-26-0412 | 9 | 2026-10-20 | Fee | K. Ostby | Associate | MED | 3.0 | 360.00 | 1080.00 | Attend internal strategy meeting on mediation.
B-26-0412 | 10 | 2026-10-26 | Fee | S. Ruane | Senior associate | MED | 5.5 | 450.00 | 2475.00 | Draft mediation statement; revise exhibit list; call with Company A on mediation statement; emails with mediator's office on logistics.
B-26-0412 | 11 | 2026-09-28 | Fee | J. Penhale | Paralegal | DOC | 1.0 | 180.00 | 180.00 | Prepare production set 2 for transmittal.
B-26-0412 | 12 | 2026-10-29 | Fee | P. Marlow | Partner | MED | 2.0 | 640.00 | 1280.00 | Revise mediation statement.
B-26-0412 | 13 | 2026-10-15 | Expense | | | DOC | | | 1450.00 | Review platform hosting, October.
B-26-0412 | 14 | 2026-10-22 | Expense | | | MED | | | 310.00 | Courier, mediation binders to mediator's office.
```

## Input 4: the agreed rate table

```
Agreed rate table: Firm B for Company A, 2026.
Approved by Martin Ashgrove, general counsel, on 2026-01-15.

Firm | Timekeeper | Role | Rate | From | To
Firm B | P. Marlow | Partner | 640.00 | 2026-01-01 | 2026-12-31
Firm B | S. Ruane | Senior associate | 450.00 | 2026-01-01 | 2026-12-31
Firm B | K. Ostby | Associate | 340.00 | 2026-01-01 | 2026-09-30
Firm B | K. Ostby | Associate | 360.00 | 2026-10-01 | 2026-12-31
Firm B | J. Penhale | Paralegal | 180.00 | 2026-01-01 | 2026-12-31
```

## Input 5: the staffing list

```
Staffing list: matter LM-2026-014. Approved by Leona Barsby, senior counsel.

Matter | Timekeeper | Role | Approved on
LM-2026-014 | P. Marlow | Partner | 2026-02-02
LM-2026-014 | S. Ruane | Senior associate | 2026-02-02
LM-2026-014 | K. Ostby | Associate | 2026-02-02
LM-2026-014 | J. Penhale | Paralegal | 2026-02-02
```

## Input 6: the approved budget

```
Approved budget: matter LM-2026-014.
Approved by Martin Ashgrove, general counsel, on 2026-02-02.
Amounts cover fees and expenses.
Billed before this invoice: through invoice B-26-0377.

Matter | Phase | Phase name | Approved budget | Billed before this invoice
LM-2026-014 | DOC | Document collection and review | 38000.00 | 31200.00
LM-2026-014 | MED | Mediation | 25000.00 | 13600.00
```

## Input 7: the billing guidelines

```
Company A Outside Counsel Billing Guidelines, version 3.
Effective 2026-03-01. Approved by Martin Ashgrove, general counsel.

G1. Rates are those in the agreed rate table. A rate change takes effect
    only once Company A has added it to that table in writing.
G2. Only timekeepers on the staffing list for a matter may bill to it.
    Additions need written approval from the matter lead before work
    starts.
G3. Record time by task. Each entry covers one task, with its own time.
G4. No more than two timekeepers may bill for attending the same internal
    meeting, call or session, unless the matter lead approved more in
    advance.
G5. Record time in tenths of an hour.
G6. Work expected to take a matter over its approved phase budget must be
    raised with the matter lead before it is done.
G7. Time spent preparing invoices, or answering questions about them, is
    not billed.
G8. Travel time is billed at half rate.
```

## Input 8: the check map

```
Check map for Company A Outside Counsel Billing Guidelines, version 3.
Approved by Leona Barsby, senior counsel, on 2026-03-04.

Check | Rule | Limit
Rates | G1 |
Staffing list | G2 |
Time by task | G3 |
Attendance | G4 | 2
Budget raised in advance | G6 |
```

## Input 9: earlier invoice lines

```
Invoice | Line | Date | Type | Timekeeper | Role | Phase | Hours | Rate | Amount | Description
B-26-0377 | 1 | 2026-09-15 | Expense | | | DOC | | | 1450.00 | Review platform hosting, September.
B-26-0377 | 2 | 2026-09-24 | Fee | S. Ruane | Senior associate | DOC | 2.5 | 450.00 | 1125.00 | Review supplier delivery records, batch 3, for responsiveness.
B-26-0377 | 3 | 2026-09-28 | Fee | J. Penhale | Paralegal | DOC | 1.0 | 180.00 | 180.00 | Prepare production set 2 for transmittal.
B-26-0377 | 4 | 2026-09-29 | Fee | K. Ostby | Associate | DOC | 4.0 | 340.00 | 1360.00 | Review warehouse email export, first pass.
```

## What the workflow template prepares

```
NOTE TO Tamsin Rook
- Checks not run: None.
- Rules marked "wording unclear": None.
- Still to do: read this draft against the invoice; give it to Leona Barsby; send only the questions Leona Barsby confirms.
- Nothing has been sent, approved or paid.

DRAFT FOR Leona Barsby, senior counsel, matter lead · OUTSIDE-COUNSEL INVOICE QUESTIONS
Questions, not findings. Gives no legal advice. Decides nothing about legal
meaning, merit, validity, privilege, conflicts or deadlines. Sends, files,
signs and calendars nothing.
Nothing has been sent, filed, signed, calendared, approved, rejected or paid.

Company: Company A
Firm: Firm B; responsible attorney P. Marlow
Matter: Supplier C distribution dispute, LM-2026-014
Invoice: B-26-0412, dated 2026-11-06, period 2026-10-01 to 2026-10-31. USD 17705.00 (fees 15945.00, expenses 1760.00)
Prepared by: Tamsin Rook, legal operations manager, 2026-11-11
For: Leona Barsby confirms the check map and the questions. Martin Ashgrove decides payment after the firm answers.

RECORDS USED
- Agreed rate table: Firm B for Company A, 2026, approved by Martin Ashgrove on 2026-01-15.
- Staffing list: matter LM-2026-014, approved by Leona Barsby; 4 timekeepers, each with its Approved on date.
- Budget: matter LM-2026-014, approved by Martin Ashgrove on 2026-02-02; billed before this invoice through B-26-0377; covers fees and expenses.
- Billing guidelines: Company A Outside Counsel Billing Guidelines, version 3, effective 2026-03-01, approved by Martin Ashgrove.
- Check map: Rates: G1; Staffing list: G2; Time by task: G3; Attendance: G4 (2); Budget raised in advance: G6; approved by Leona Barsby on 2026-03-04.
- Earlier lines compared: B-26-0377.

TIE-OUT
- Lines read: 12 fee, 2 expense.
- Fees 15945.00 = header 15945.00. Expenses 1760.00 = header 1760.00. Total 17705.00 = header 17705.00.
- Line arithmetic: every fee line, hours × rate = amount.
- Line dates: P1. Line 11, 2026-09-28, J. Penhale: outside the period 2026-10-01 to 2026-10-31.

1. RATE DIFFERENCES: 2
R1. Line 4, 2026-10-05, K. Ostby (Associate): billed 380.00/h; agreed 360.00/h from 2026-10-01. 6.0 h. Difference 120.00.
R2. Line 6, 2026-10-12, R. Tiller (Associate): no agreed rate on file. Billed 340.00/h, 1360.00.

2. POSSIBLE DUPLICATE ENTRIES: 2
D1. Lines 2 and 3: S. Ruane, 2026-10-02, "Review supplier delivery records, batch 4, for responsiveness." Hours match; amounts match. In question: 1350.00.
D2. Line 11 and B-26-0377 line 3: J. Penhale, 2026-09-28, "Prepare production set 2 for transmittal." Hours match; amounts match. In question: 180.00.

3. BLOCK ENTRIES: 2
B1. Line 4, 2026-10-05, K. Ostby, 6.0 h, 2280.00: 4 tasks under one time. "Review warehouse email export; prepare document index; call with J. Penhale on coding; update review protocol." Rule: G3.
B2. Line 10, 2026-10-26, S. Ruane, 5.5 h, 2475.00: 4 tasks under one time. "Draft mediation statement; revise exhibit list; call with Company A on mediation statement; emails with mediator's office on logistics." Rule: G3.

4. STAFFING ITEMS: 2
S1. Line 6, 2026-10-12, R. Tiller (Associate): not on the staffing list for LM-2026-014. Check map: G2. 1360.00.
S2. Lines 7, 8, 9, 2026-10-20: 3 timekeepers (P. Marlow, S. Ruane, K. Ostby) for "Attend internal strategy meeting on mediation." Check map: G4, number 2. Billed 4350.00.

5. BUDGET
- DOC Document collection and review: approved 38000.00; billed before 31200.00; this invoice 8330.00; to date 39530.00; 104.0%. Over by 1530.00.
- MED Mediation: approved 25000.00; billed before 13600.00; this invoice 9375.00; to date 22975.00; 91.9%. At or above 90%.
- Total: approved 63000.00; billed before 44800.00; this invoice 17705.00; to date 62505.00; 99.2%.
- Phase not in the budget: None.
O1. Phase DOC Document collection and review: to date 39530.00 against approved 38000.00; over by 1530.00.

QUESTIONS FOR FIRM B, DRAFT FOR LEONA BARSBY TO CONFIRM
Q1 (P1). Invoice B-26-0412, line 11 (2026-09-28, J. Penhale): the line is dated outside this invoice's period of 2026-10-01 to 2026-10-31. Please confirm the date, and whether this line appears on an earlier invoice.
Q2 (R1). Invoice B-26-0412, line 4 (2026-10-05, K. Ostby): billed at 380.00 an hour. Our agreed rate table shows 360.00 for K. Ostby from 2026-10-01. Please confirm which rate applies, or explain the difference.
Q3 (R2). Invoice B-26-0412, line 6 (2026-10-12, R. Tiller, Associate): we have no agreed rate on file for R. Tiller. Please tell us the rate applied and when it was agreed with us.
Q4 (D1). Invoice B-26-0412, lines 2 and 3: two entries for S. Ruane on 2026-10-02, 3.0 hours each, described as "Review supplier delivery records, batch 4, for responsiveness." Please confirm whether these record separate work.
Q5 (D2). Invoice B-26-0412, line 11 matches invoice B-26-0377, line 3: J. Penhale, 2026-09-28, 1.0 hours, "Prepare production set 2 for transmittal." Please confirm whether this records separate work.
Q6 (B1). Invoice B-26-0412, line 4 (2026-10-05, K. Ostby, 6.0 hours): the description lists 4 tasks under one time (our billing guidelines, G3). Please give the time for each task.
Q7 (B2). Invoice B-26-0412, line 10 (2026-10-26, S. Ruane, 5.5 hours): the description lists 4 tasks under one time (our billing guidelines, G3). Please give the time for each task.
Q8 (S1). Invoice B-26-0412, line 6: R. Tiller is not on the staffing list we hold for this matter (our billing guidelines, G2). Please tell us whether R. Tiller's work on the matter was agreed with us, and if so by whom and when.
Q9 (S2). Invoice B-26-0412, lines 7, 8, 9: 3 timekeepers billed for "Attend internal strategy meeting on mediation." on 2026-10-20. We check attendance at 2 timekeepers (our billing guidelines, G4). Please explain the attendance, and tell us whether it was agreed with us, and if so by whom and when.
Q10 (O1). Matter LM-2026-014, phase DOC: with this invoice, billing reaches 39530.00 against an approved budget of 38000.00, 1530.00 over. Please tell us whether and when this was raised with us (our billing guidelines, G6). Please give the expected spend to complete the phase.

LAWYER TO CONFIRM
[ ] Q1 may go to Firm B as written.            Confirm, change or strike: ____
[ ] Q2 may go to Firm B as written.            Confirm, change or strike: ____
[ ] Q3 may go to Firm B as written.            Confirm, change or strike: ____
[ ] Q4 may go to Firm B as written.            Confirm, change or strike: ____
[ ] Q5 may go to Firm B as written.            Confirm, change or strike: ____
[ ] Q6 may go to Firm B as written.            Confirm, change or strike: ____
[ ] Q7 may go to Firm B as written.            Confirm, change or strike: ____
[ ] Q8 may go to Firm B as written.            Confirm, change or strike: ____
[ ] Q9 may go to Firm B as written.            Confirm, change or strike: ____
[ ] Q10 may go to Firm B as written.           Confirm, change or strike: ____
[ ] The check map (Leona Barsby, 2026-03-04) is the one to use for this invoice.  Confirm: ____
[ ] The records used are current for this engagement.  Confirm: ____
[ ] Any time limit for invoice B-26-0412, for payment or for raising questions, is yours to check; this worksheet states and counts none.  Confirm: ____
[ ] Every question asks; none states a finding.  Confirm: ____
[ ] The section for Martin Ashgrove, below.  Release or hold back: ____

FOR MARTIN ASHGROVE, ONCE LEONA BARSBY HAS SIGNED
- This section reaches Martin Ashgrove only after Leona Barsby signs the confirmation line and releases it above.
- Lines named in no item: 1, 5, 12, 13, 14, 4360.00. Only the checks under RECORDS USED were run on them; they are not approved.
- Lines named in one or more items: 2, 3, 4, 6, 7, 8, 9, 10, 11, 13345.00. Budget items name a phase, not lines. Amounts in question are not added together: one line can sit in several items.
- Guideline rules not checked: G5: not in the check map; G7: not in the check map; G8: not in the check map.
- This worksheet lists questions only. It does not say whether to pay, hold or reduce anything, and Firm B has not answered.
- Payment: yours to decide after the firm answers. Any due date or other time limit is for Leona Barsby; this worksheet states none.
- This worksheet approves, rejects, holds and pays nothing.

CHECK
- Lines read 14 of 14. Items: 10 (A 0, P 1, R 2, D 2, B 2, S 2, O 1). Questions: 10.
- Each item names its line or phase and its record, to be read against both.
- Figures are taken only from the records listed, to be rechecked against the invoice.
- Nothing has been sent, filed, signed, calendared, approved, rejected or paid.
- No record has been changed.

Confirmed by: ____________  Date: ________
Until Leona Barsby signs this line, the whole worksheet is a draft: no question may be sent, and nothing in it is to be acted on.
```

## How the figures were reached

- **Tie-out.** Fee lines 1 to 12 add to 15945.00 and expense lines 13 and 14 to 1760.00, together 17705.00, matching the header.
- **P1.** The invoice’s period is 2026-10-01 to 2026-10-31. Line 11 is dated 2026-09-28; every other line falls inside the period. P1 would be listed even without the earlier invoice’s lines.
- **R1.** K. Ostby’s agreed rate from 2026-10-01 is 360.00; line 4 is dated 2026-10-05 and billed at 380.00. 6.0 × 20.00 = 120.00. Line 9, also K. Ostby in October, is billed at 360.00 and is not listed.
- **D1 and D2.** Lines 2 and 3 share timekeeper, date and description. Line 11 shares timekeeper, date and description with line 3 of the September invoice. The two hosting expenses have different dates and descriptions, so they are not matched.
- **B1 and B2.** Each description has three semicolons, so four tasks. Line 1 joins two tasks with “and”, which the rule does not count, and the full stop in the initial “S.” is not a sentence break.
- **S1 and S2.** R. Tiller is not on the staffing list. Lines 7, 8 and 9 name the same meeting in the same words, three timekeepers against the check map’s number of 2 for attendance. The worksheet records only that. Whether G4 covers this meeting, and whether its advance-approval exception applies, is Leona Barsby’s reading, not the worksheet’s.
- **Budget.** DOC this invoice: lines 2, 3, 4, 5, 6, 11 and 13, 8330.00; 31200.00 + 8330.00 = 39530.00, which is 104.0 per cent of 38000.00 and 1530.00 over. MED this invoice: lines 1, 7, 8, 9, 10, 12 and 14, 9375.00; 13600.00 + 9375.00 = 22975.00, 91.9 per cent: at or above the near-budget level of 90 per cent, so it is marked in the phase table but is not an item. Total to date 62505.00 of 63000.00, 99.2 per cent.
- **Lines named and not named.** 13345.00 + 4360.00 = 17705.00, the invoice total.

Every item ties to an invoice line or a budget phase and to the record it was compared with. Leona Barsby confirms the check map, confirms, changes or strikes each question, and releases or holds back the section for Martin Ashgrove; Tamsin Rook sends the confirmed questions to Firm B; Martin Ashgrove decides payment once Firm B has answered. The worksheet says nothing about whether any amount in it may be paid, held or deducted.
