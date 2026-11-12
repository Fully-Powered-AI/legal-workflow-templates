# Weekly status requests to outside counsel: an invented example

*Illustrative example with invented data.* Company K, its people, Firms A, B and C and their lawyers, the other parties, the Superior Court of Eastmere, Agency W, the matters, the dates and the amounts below are all invented. Company K is an invented maker of industrial valves with one in-house lawyer, Mara Ilsley, and a legal operations manager, Devon Achterberg, who runs the work each Monday.

Devon's four inputs come first, in full, then everything the workflow template prepared.

## Input 1: today's date

```
Monday 16 November 2026
```

## Input 2: the house settings, approved by Mara Ilsley

```
Reviewing counsel: Mara Ilsley, Senior Counsel
Prepared by: Devon Achterberg, Legal Operations Manager
Sender: Mara Ilsley <mara.ilsley@company-k.example>
Subject: [matter_id] [matter_name]: status request
Greeting: [first name],
Opening line: Ahead of our Monday review, a few questions on [matter_name].
Sign-off: Thank you,
          Mara Ilsley
          Senior Counsel, Company K
Top line: Confidential: Company K legal department
Stale after: 10 days
Upcoming within: 21 days
Spend flag at: 80%
Currency: US dollars ($)
Include this week: none
Leave out this week: none
```

## Input 3: the matter list, exported from Company K's matter system

```
matter_id,matter_name,status,priority,firm,lead_lawyer,lead_email,last_update,next_date,next_event,budget_authorised,billed_to_date,billed_through
M-201,Company K v. Supplier C,open,high,Firm A LLP,Hal Brennick,hal.brennick@firm-a.example,2026-10-30,2026-12-08,Mediation session,120000,86400,2026-10-31
M-202,Distributor D v. Company K,open,normal,Firm B LLP,Selin Okafor,selin.okafor@firm-b.example,2026-11-12,2026-12-01,Case management conference,60000,61250,2026-10-31
M-203,Agency W inquiry,open,normal,Firm C LLP,Tomas Reyna,tomas.reyna@firm-c.example,2026-11-10,2027-01-15,Agency's requested response date,40000,12300,2026-10-31
M-204,Warehouse lease with Landlord L,on hold,normal,Firm A LLP,Hal Brennick,hal.brennick@firm-a.example,2026-09-14,,,15000,3100,2026-09-30
M-205,Customer M incident claim,open,high,,,,,,,,,
M-206,Customs classification review,open,normal,Firm C LLP,Ada Morrow,,2026-10-20,,,25000,4800,2026-10-31
```

## Input 4: the matter notes

```
Matter: M-201
Last update from the firm: 2026-10-30 (call with Hal Brennick)
Events since:
- 2026-10-28 Firm A sent the draft mediation statement for comment
- 2026-11-04 Supplier C's counsel wrote proposing a second mediation day
- 2026-11-09 Firm A's October invoice received
Dates on record:
- 2026-12-08 Mediation session (Firm A's email of 2026-10-30)
Decisions pending:
- Whether a second mediation day is needed (Firm A to advise)
- Who from Company K attends the mediation
Open questions for the firm:
- Has Supplier C produced the batch test records it promised?
Internal only:
- Finance wants the matter closed before year end.

Matter: M-202
Last update from the firm: 2026-11-12 (email from Selin Okafor)
Events since:
- 2026-11-13 Company K's sales team sent Firm B the distributor file (12 documents)
Dates on record:
- 2026-12-01 Case management conference (notice from the Superior Court of Eastmere, forwarded by Firm B)
Decisions pending:
- Who from Company K attends the case management conference
Open questions for the firm:
- none
Internal only:
- The CFO wants to discuss whether Firm B stays on this matter after the conference.

Matter: M-206
Last update from the firm: 2026-10-20 (report from Ada Morrow)
Events since:
- none
Dates on record:
- none
Decisions pending:
- none
Open questions for the firm:
- Has the customs authority acknowledged the classification request?
Internal only:
- none
```

## What the workflow template prepared

```
DRAFTS FOR Mara Ilsley · NOTE TO THE COORDINATOR
Not legal advice. Decides nothing about legal meaning, merit, validity,
privilege, conflicts or deadlines. Nothing has been sent, filed, signed,
calendared or recorded.
3 drafts, 3 skipped. 3 items for counsel's attention, listed in the
run summary.
Event lines left out as dated on or before the last update: M-201, 1.
Still to do: read each draft against the matter file, then pass the set to
Mara Ilsley, who edits, answers the confirm lines and sends.
I have sent nothing, saved nothing to a mailbox and recorded nothing.

----------------------------------------------------------------------

DRAFT STATUS REQUEST · FOR Mara Ilsley TO REVIEW AND SEND
Not legal advice. Decides nothing about legal meaning, merit, validity,
privilege, conflicts or deadlines. Nothing has been sent, filed, signed,
calendared or recorded.

Matter: M-201, Company K v. Supplier C
Why drafted: last update 17 days ago
To: Hal Brennick, Firm A LLP <hal.brennick@firm-a.example>
From: Mara Ilsley <mara.ilsley@company-k.example>
Subject: M-201 Company K v. Supplier C: status request

Confidential: Company K legal department

Hal,

Ahead of our Monday review, a few questions on Company K v. Supplier C.

1. Since your last update on 2026-10-30
   Our notes show:
   - 2026-11-04: Supplier C's counsel wrote proposing a second mediation day
   - 2026-11-09: Firm A's October invoice received
   What has happened on the matter since then, and is anything waiting on
   either side?

2. Dates we have on record
   - 2026-12-08: Mediation session
   Could you confirm these, and tell us of any date we should have that is
   not here?

3. Decisions pending
   - Whether a second mediation day is needed (Firm A to advise)
   - Who from Company K attends the mediation
   Where does each of these stand, and what do you need from us?

4. Spend against the authorised budget
   Authorised: $120,000. Billed to date: $86,400, invoices through
   2026-10-31. Remaining: $33,600 (72% of the budget billed).
   What work has been done that is not yet billed, and do you expect the
   matter to need more than the authorised budget?

5. Our open questions
   - Has Supplier C produced the batch test records it promised?

Thank you,
Mara Ilsley
Senior Counsel, Company K

COUNSEL TO CONFIRM BEFORE SENDING
[ ] Recipient and email address are right.                    Confirm: ____
[ ] The events listed match the matter file.                  Confirm: ____
[ ] The dates are as the company has them on record.
    None was counted here.                                    Confirm: ____
[ ] The decisions listed are the ones to raise with the firm. Confirm: ____
[ ] The spend figures match the firm's invoices.              Confirm: ____
[ ] The email holds no view of the case, no figure for
    settlement and nothing you keep internal.                 Confirm: ____

Working: today 2026-11-16. Last update 2026-10-30, 17 days ago. Next date on
record 2026-12-08, 22 days away. Spend 120,000 − 86,400 = 33,600;
86,400 ÷ 120,000 = 72%.

----------------------------------------------------------------------

DRAFT STATUS REQUEST · FOR Mara Ilsley TO REVIEW AND SEND
Not legal advice. Decides nothing about legal meaning, merit, validity,
privilege, conflicts or deadlines. Nothing has been sent, filed, signed,
calendared or recorded.

Matter: M-202, Distributor D v. Company K
Why drafted: date on record in 15 days
To: Selin Okafor, Firm B LLP <selin.okafor@firm-b.example>
From: Mara Ilsley <mara.ilsley@company-k.example>
Subject: M-202 Distributor D v. Company K: status request

Confidential: Company K legal department

Selin,

Ahead of our Monday review, a few questions on Distributor D v. Company K.

1. Since your last update on 2026-11-12
   Our notes show:
   - 2026-11-13: Company K's sales team sent Firm B the distributor file
     (12 documents)
   What has happened on the matter since then, and is anything waiting on
   either side?

2. Dates we have on record
   - 2026-12-01: Case management conference
   Could you confirm these, and tell us of any date we should have that is
   not here?

3. Decisions pending
   - Who from Company K attends the case management conference
   Where does each of these stand, and what do you need from us?

4. Spend against the authorised budget
   Authorised: $60,000. Billed to date: $61,250, invoices through
   2026-10-31. Over by: $1,250 (102% of the budget billed).
   What work has been done that is not yet billed, and what further fees
   do you expect the matter to need?

Thank you,
Mara Ilsley
Senior Counsel, Company K

COUNSEL TO CONFIRM BEFORE SENDING
[ ] Recipient and email address are right.                    Confirm: ____
[ ] The events listed match the matter file.                  Confirm: ____
[ ] The dates are as the company has them on record.
    None was counted here.                                    Confirm: ____
[ ] The decisions listed are the ones to raise with the firm. Confirm: ____
[ ] The spend figures match the firm's invoices.              Confirm: ____
[ ] The email holds no view of the case, no figure for
    settlement and nothing you keep internal.                 Confirm: ____
[ ] Spend over the authorised budget: billed $61,250 against
    $60,000, over by $1,250 (102%).                           Confirm: ____

Working: today 2026-11-16. Last update 2026-11-12, 4 days ago. Next date on
record 2026-12-01, 15 days away. Spend 61,250 − 60,000 = over by 1,250;
61,250 ÷ 60,000 = 102%.

----------------------------------------------------------------------

DRAFT STATUS REQUEST · FOR Mara Ilsley TO REVIEW AND SEND
Not legal advice. Decides nothing about legal meaning, merit, validity,
privilege, conflicts or deadlines. Nothing has been sent, filed, signed,
calendared or recorded.

Matter: M-206, Customs classification review
Why drafted: last update 27 days ago
To: Ada Morrow, Firm C LLP <email not on record>
From: Mara Ilsley <mara.ilsley@company-k.example>
Subject: M-206 Customs classification review: status request

Confidential: Company K legal department

Ada,

Ahead of our Monday review, a few questions on Customs classification review.

1. Since your last update on 2026-10-20
   Our notes show:
   - None in our notes.
   What has happened on the matter since then, and is anything waiting on
   either side?

2. Dates we have on record
   - None on record.
   Could you tell us of any date we should have on record?

3. Spend against the authorised budget
   Authorised: $25,000. Billed to date: $4,800, invoices through
   2026-10-31. Remaining: $20,200 (19% of the budget billed).
   What work has been done that is not yet billed, and do you expect the
   matter to need more than the authorised budget?

4. Our open questions
   - Has the customs authority acknowledged the classification request?

Thank you,
Mara Ilsley
Senior Counsel, Company K

COUNSEL TO CONFIRM BEFORE SENDING
[ ] Recipient and email address are right.                    Confirm: ____
[ ] The events listed match the matter file.                  Confirm: ____
[ ] The dates are as the company has them on record.
    None was counted here.                                    Confirm: ____
[ ] The decisions listed are the ones to raise with the firm. Confirm: ____
[ ] The spend figures match the firm's invoices.              Confirm: ____
[ ] The email holds no view of the case, no figure for
    settlement and nothing you keep internal.                 Confirm: ____
[ ] No email address on record for Ada Morrow.                Confirm: ____

Working: today 2026-11-16. Last update 2026-10-20, 27 days ago. Next date on
record none. Spend 25,000 − 4,800 = 20,200; 4,800 ÷ 25,000 = 19%.

----------------------------------------------------------------------

DRAFT RUN SUMMARY · FOR Mara Ilsley
Weekly status requests to outside counsel, run of 2026-11-16
Not legal advice. Decides nothing about legal meaning, merit, validity,
privilege, conflicts or deadlines. Nothing has been sent, filed, signed,
calendared or recorded.
Prepared by: Devon Achterberg, Legal Operations Manager

RULES USED
- Requests due when the firm's last update is older than 10 days, or a
  date on record falls within 21 days or has passed.
- Spend flagged at 80% of the authorised budget or over it.
- Counsel's changes this week: none.

DRAFTED (3)
- M-201, Company K v. Supplier C · Firm A LLP, Hal Brennick · last update
  17 days ago
- M-202, Distributor D v. Company K · Firm B LLP, Selin Okafor · date on
  record in 15 days
- M-206, Customs classification review · Firm C LLP, Ada Morrow · last
  update 27 days ago

SKIPPED (3)
- M-203, Agency W inquiry · update 6 days ago; next date on record
  2027-01-15
- M-204, Warehouse lease with Landlord L · on hold
- M-205, Customer M incident claim · no outside firm or lead lawyer on
  record

NEEDS COUNSEL'S ATTENTION (3)
- M-202 · spend over the authorised budget: billed $61,250 against
  $60,000, over by $1,250 (102%).
- M-205 · HIGH PRIORITY · open, with no outside firm or lead lawyer on
  record.
- M-206 · no email address on record for Ada Morrow.

COUNSEL TO CONFIRM
[ ] Each skipped matter can wait until the next run.          Confirm: ____
[ ] Each item under NEEDS COUNSEL'S ATTENTION is dealt with.  Confirm: ____
[ ] Each draft was reviewed and its confirm lines answered
    before it was sent.                                       Confirm: ____

CHECK
- Rows read: 6. Drafted 3 + skipped 3 = 6.
- Columns: default headers.
- Notes blocks used: 3.
- Event lines left out as dated on or before the last update: 1.
- Every fact in the drafts is in the matter list or the notes. No date was
  counted or added, no case, statute or rule was added, and nothing has
  been sent, saved to a mailbox or recorded.
```

What to notice: M-201's line from 28 October was left out because it predates Firm A's last update, and the note says so. Neither "Internal only" line reached a draft. M-202 has no open questions, so its fifth item is left out; M-206 has no decisions pending, so its items are renumbered, and with no date on record its second item asks the firm for any date rather than to confirm one. M-202's fees are already over the authorised budget, so its spend question asks what further fees the firm expects rather than whether it expects to go over. The court and the source of each date stay in Devon's notes and out of the emails. The two matters with something wrong on the company's own side, a high-priority claim with no firm and a missing email address, go to Mara rather than into an email. Mara edits each draft, answers its confirm lines and sends it herself. The trial record published with this example shows the same week prepared for a company with no in-house lawyer, where the person who sends the drafts checks facts only and every point for a lawyer names the lawyer it goes to.
