# Contract renewal and notice register: an invented example

*Illustrative example with invented data.* The Company, Suppliers A to D, the agreements, the amendment, the counting rules and the closed-day list below are all invented, and the addresses use placeholder names. The counting rules are one invented company's way of counting its own notice dates. They are not any real law or court rule and must not be used for a real date.

The Company is an invented 150-person software business with an in-house counsel and a contracts manager. The contracts manager supplies five inputs, given here in full, and then the workflow template prepares the register.

## Input 1: the settings

```
Company: the Company
Counsel who confirms: In-house counsel
Prepared by: Contracts manager
Today: Monday 16 November 2026
Horizon: 120 days
Bands: the defaults (Urgent 0 to 21 days, Soon 22 to 60, Watch 61 to 120)
```

## Input 2: the agreement list

```
Agreement ID,Counterparty,Title,Documents,Business owner,Status notes
A1,Supplier A,Data platform subscription agreement,A1-agreement.pdf,Head of data,No notice given; not ended
A2,Supplier B,Managed print services agreement,A2-agreement.pdf; A2-amendment-1.pdf,Office manager,No notice given; not ended
A3,Supplier C,Office cleaning services agreement,A3-agreement.pdf,Office manager,No notice given; not ended
A4,Supplier D,Fleet telematics agreement,A4-agreement.pdf,,No notice given; not ended
```

## Input 3: the counting rules

```
RENEWAL NOTICE COUNTING RULES (invented)
Version 2. Approved by: In-house counsel. Dated: 1 September 2026.
Review by: 1 March 2027. Covers: the Company's agreements for goods and
services. Staff may propose dates only under these rules. Counsel
confirms every date.

R1  Notice in days before the end of a term.
    Applies when: the clause requires notice at least, or not less than,
    a stated number of days before the end of the Term, the initial term
    or the then-current term, and does not say business or working days.
    Count: subtract that number of calendar days from the term end. The
    result is the cancel-by date. Then apply R3.

R2  Notice in months before the end of a term.
    Applies when: as R1, with the period stated in months.
    Count: go back that number of calendar months to the same day number.
    If that month has no such day, use its last day. Then apply R3.

R3  Closed days.
    If a cancel-by date falls on a Saturday, a Sunday or a day on the
    closed-day list, move it to the nearest earlier day that is none of
    these. Never later.

R4  Send-by allowance.
    Applies when: the notices clause requires one method only.
    Email to a stated address: the send-by date is the cancel-by date.
    Courier: 3 business days before the cancel-by date.
    Registered or certified post: 5 business days before the cancel-by
    date. Business days exclude Saturdays, Sundays and closed-day list
    days.

R5  Rolling a term forward.
    Applies when: the clause says the agreement renews automatically for
    successive renewal terms of a stated number of whole years, and the
    status notes record no notice given and no ending.
    Count: the next term end is the same day and month, that number of
    years later. A term end of 29 February is not covered.

R6  An amendment that replaces a section.
    Applies when: an amendment signed by both parties says in its own
    words that a numbered section of the agreement "is deleted and
    replaced with" new wording; it states the date on which it takes
    effect, and that date is on or before today; and it states no
    condition on taking effect.
    Count: count from the new wording in place of the section it
    replaces. Counsel confirms which wording applies.

Not covered (counsel only): notice in business or working days; any term
or period that runs from a date the documents do not state; wording that
joins two counts, such as "whichever is earlier"; any method not in R4;
a clause that allows more than one method; a later document that changes
a section without saying it "is deleted and replaced with" new wording.
```

## Input 4: the closed-day list

```
COMPANY CLOSED DAYS (invented). Covers 1 January 2026 to 31 December 2027.
Thursday 1 January 2026
Friday 25 December 2026
Friday 1 January 2027
Monday 15 February 2027
Monday 27 December 2027
```

## Input 5: the signed documents

Each invented document below is complete. Page breaks are shown as page markers.

**A1-agreement.pdf**

```
DATA PLATFORM SUBSCRIPTION AGREEMENT
Between Supplier A ("Supplier A") and the Company ("Customer").
                                                           Page 1 of 3
1. Definitions
1.4 "Effective Date" means 1 March 2024.
5. Fees
5.1 Customer pays the annual fees in this section, invoiced yearly in
advance: 36,500 per year.
5.4 Fees for each renewal term are those in Supplier A's published fee
schedule on the first day of that renewal term.
                                                           Page 2 of 3
12. Term and renewal
12.1 The Initial Term begins on the Effective Date and ends on
28 February 2027.
12.2 After the Initial Term, this Agreement renews automatically for
successive renewal terms of one (1) year each unless either party gives
written notice of non-renewal at least ninety (90) days before the end
of the then-current term.
18. Notices
18.2 Notices under this Agreement must be in writing and delivered by
courier to the address of the receiving party set out in Schedule 1.
                                                           Page 3 of 3
Schedule 1. Addresses for notices
Supplier A: Legal Department, 40 Example Road, Example City.
Customer: In-house counsel, the Company, 7 Sample Street, Example City.

Signed for Supplier A by its Chief Executive, 1 March 2024: [signature]
Signed for Customer by its Chief Operating Officer, 1 March 2024: [signature]
```

**A2-agreement.pdf**

```
MANAGED PRINT SERVICES AGREEMENT
Between Supplier B and the Company.
                                                           Page 1 of 2
Addresses: Supplier B, 3 Placeholder Lane, Example Town.
The Company, 7 Sample Street, Example City.
9. Term
9.1 This Agreement begins on 15 January 2023 and continues for
thirty-six (36) months.
9.2 This Agreement renews for successive periods of twelve (12) months
unless either party gives notice at least sixty (60) days before the end
of the Term.
                                                           Page 2 of 2
14. Notices
14.1 Notices must be sent by registered post to the addresses on page 1.

Signed for Supplier B by its Managing Director, 12 January 2023: [signature]
Signed for the Company by its Chief Operating Officer, 12 January 2023: [signature]
```

**A2-amendment-1.pdf**

```
AMENDMENT 1 TO THE MANAGED PRINT SERVICES AGREEMENT
Between Supplier B and the Company.
                                                           Page 1 of 1
1. This Amendment takes effect on 10 December 2025.
2. Section 9.1 of the Agreement is deleted and replaced with: "This
Agreement begins on 15 January 2023 and ends on 18 February 2027."
3. Section 9.2 of the Agreement is deleted and replaced with: "This
Agreement renews for one further period of twelve (12) months unless
either party gives notice at least three (3) months before the end of
the Term."
4. All other terms of the Agreement are unchanged.

Signed for Supplier B by its Managing Director, 10 December 2025: [signature]
Signed for the Company by its Chief Operating Officer, 10 December 2025: [signature]
```

**A3-agreement.pdf**

```
OFFICE CLEANING SERVICES AGREEMENT
Between Supplier C and the Company.
                                                           Page 1 of 2
2. Term
2.1 The initial term runs from 18 March 2024 to 17 March 2025.
2.2 This Agreement renews automatically for successive renewal terms of
one (1) year each unless either party gives written notice of
non-renewal at least thirty (30) days before the end of the then-current
term.
3. Price
3.1 The monthly price is set out in Schedule A.
                                                           Page 2 of 2
8. Notices
8.1 Notices must be sent by email to the notice address of the receiving
party stated in Schedule A.
Schedule A
Monthly price: 2,400.
Notice addresses: Supplier C: notices@supplier-c.example.
The Company: legal@company.example.

Signed for Supplier C by its Director, 8 March 2024: [signature]
Signed for the Company by its Office Manager, 8 March 2024: [signature]
```

**A4-agreement.pdf**

```
FLEET TELEMATICS AGREEMENT
Between Supplier D and the Company.
                                                           Page 1 of 2
1. Definitions
"Go-Live Date" means the date Supplier D confirms in writing that the
Services are live.
3. Term
3.1 The Services start on the Go-Live Date.
3.2 This Agreement renews on each anniversary of the Go-Live Date for a
further year unless either party gives notice not less than twenty (20)
business days before that anniversary.
5. Fees
5.2 Renewal fees may increase by up to the percentage stated in the
Order Form.
                                                           Page 2 of 2
11. Notices
11.1 Notices may be sent by email or by courier to the addresses in the
Order Form.

Signed for Supplier D by its Head of Sales, 2 June 2025: [signature]
Signed for the Company by its Chief Operating Officer, 2 June 2025: [signature]
```

## What the workflow template prepares

```
DRAFT RENEWAL AND NOTICE REGISTER · FOR IN-HOUSE COUNSEL TO CONFIRM
Prepared for In-house counsel, who decides and signs. Not legal advice. This
draft decides nothing about legal meaning, merit, validity, privilege,
conflicts or deadlines. Every counted date is a proposed date. Nothing
has been sent, filed, signed, calendared or changed, and nothing goes
to a business owner until counsel signs.

Company: the Company · Prepared by: Contracts manager · Today: Monday 16 November 2026
Horizon: 120 days, to Tuesday 16 March 2027. Bands: Urgent 0 to 21 days,
Soon 22 to 60, Watch 61 to 120.
Counting rules: RENEWAL NOTICE COUNTING RULES (invented), version 2,
approved by In-house counsel, dated 1 September 2026, review by 1 March
2027. In date.
Closed-day list: COMPANY CLOSED DAYS (invented), covers 1 January 2026 to
31 December 2027.
Agreements: 4 on the list. Documents: 5 read.

REGISTER
A1 · Supplier A · Data platform subscription agreement
  Business owner: Head of data
  Documents read: A1-agreement.pdf, shows a signature and date for each
    party: 1 March 2024, 3 pages
  Term: "The Initial Term begins on the Effective Date and ends on
    28 February 2027." (A1-agreement.pdf §12.1, headed "12. Term
    and renewal")
  Renewal: "After the Initial Term, this Agreement renews automatically
    for successive renewal terms of one (1) year each unless either party
    gives written notice of non-renewal at least ninety (90) days before
    the end of the then-current term." (A1-agreement.pdf §12.2)
  Notice period: In the renewal sentence above.
  Notice method: "Notices under this Agreement must be in writing and
    delivered by courier to the address of the receiving party set out
    in Schedule 1." (A1-agreement.pdf §18.2)
  Notice address of Supplier A: "Supplier A: Legal Department,
    40 Example Road, Example City." (A1-agreement.pdf Schedule 1, page 3)
  Renewal price wording: "Fees for each renewal term are those in
    Supplier A's published fee schedule on the first day of that renewal
    term." (A1-agreement.pdf §5.4)
  Amended: No later supplied document touches the term, renewal or
    notice wording.
  Status notes: No notice given; not ended
  Term end: COPIED Sunday 28 February 2027 (A1-agreement.pdf §12.1).
  Cancel-by date: PROPOSED Monday 30 November 2026. Working: start Sunday
    28 February 2027 (term end, copied); less 90 calendar days in steps:
    28 days to Sunday 31 January 2027, 31 days to Thursday 31 December
    2026, 31 days to Monday 30 November 2026 (28 + 31 + 31 = 90). Monday
    30 November 2026 is not a Saturday, a Sunday or a closed day: no
    move. Rules R1, R3.
  Send-by date: PROPOSED Wednesday 25 November 2026. Working: courier,
    3 business days before Monday 30 November 2026: Sunday 29 and
    Saturday 28 November skipped, Friday 27 November (1), Thursday
    26 November (2), Wednesday 25 November (3); none is a closed day.
    Rule R4.

A2 · Supplier B · Managed print services agreement
  Business owner: Office manager
  Documents read: A2-agreement.pdf, shows a signature and date for each
    party: 12 January 2023, 2 pages; A2-amendment-1.pdf, shows a
    signature and date for each party: 10 December 2025, 1 page
  Term: "This Agreement begins on 15 January 2023 and ends on 18 February
    2027." (A2-amendment-1.pdf §2)
    Earlier: "This Agreement begins on 15 January 2023 and continues for
    thirty-six (36) months." (A2-agreement.pdf §9.1, headed "9. Term")
  Renewal: "This Agreement renews for one further period of twelve (12)
    months unless either party gives notice at least three (3) months
    before the end of the Term." (A2-amendment-1.pdf §3)
    Earlier: "This Agreement renews for successive periods of twelve (12)
    months unless either party gives notice at least sixty (60) days
    before the end of the Term." (A2-agreement.pdf §9.2)
  Notice period: In the renewal sentence above.
  Notice method: "Notices must be sent by registered post to the
    addresses on page 1." (A2-agreement.pdf §14.1)
  Notice address of Supplier B: "Addresses: Supplier B, 3 Placeholder
    Lane, Example Town." (A2-agreement.pdf page 1)
  Renewal price wording: None found in the supplied documents.
  Amended: "Section 9.1 of the Agreement is deleted and replaced with:"
    (A2-amendment-1.pdf §2); "Section 9.2 of the Agreement is deleted and
    replaced with:" (A2-amendment-1.pdf §3). Takes effect: "This
    Amendment takes effect on 10 December 2025." (A2-amendment-1.pdf §1).
    No condition stated. Counted from the later wording under rule R6:
    shows signatures for both parties, dated 10 December 2025
    (A2-amendment-1.pdf); "is
    deleted and replaced with" in its own words (§2, §3); a stated date
    of taking effect, 10 December 2025, before today (§1); no condition
    stated. Either way: Counsel to confirm which wording applies.
  Status notes: No notice given; not ended
  Term end: COPIED Thursday 18 February 2027 (A2-amendment-1.pdf §2).
  Cancel-by date: PROPOSED Wednesday 18 November 2026. Working: start
    Thursday 18 February 2027 (term end, copied); back 3 calendar months
    to the same day number: 18 January 2027, 18 December 2026,
    18 November 2026, a Wednesday. Not a Saturday, a Sunday or a closed
    day: no move. Rules R2, R3.
  Send-by date: PROPOSED Wednesday 11 November 2026. Working: registered
    post, 5 business days before Wednesday 18 November 2026: Tuesday
    17 November (1), Monday 16 November (2), Sunday 15 and Saturday
    14 November skipped, Friday 13 November (3), Thursday 12 November (4),
    Wednesday 11 November (5); none is a closed day. Rule R4.

A3 · Supplier C · Office cleaning services agreement
  Business owner: Office manager
  Documents read: A3-agreement.pdf, shows a signature and date for each
    party: 8 March 2024, 2 pages
  Term: "The initial term runs from 18 March 2024 to 17 March 2025."
    (A3-agreement.pdf §2.1, headed "2. Term")
  Renewal: "This Agreement renews automatically for successive renewal
    terms of one (1) year each unless either party gives written notice
    of non-renewal at least thirty (30) days before the end of the
    then-current term." (A3-agreement.pdf §2.2)
  Notice period: In the renewal sentence above.
  Notice method: "Notices must be sent by email to the notice address of
    the receiving party stated in Schedule A." (A3-agreement.pdf §8.1)
  Notice address of Supplier C: "Notice addresses: Supplier C:
    notices@supplier-c.example." (A3-agreement.pdf Schedule A, page 2)
  Renewal price wording: None found in the supplied documents.
  Amended: No later supplied document touches the term, renewal or
    notice wording.
  Status notes: No notice given; not ended
  Term end: PROPOSED Wednesday 17 March 2027, rolled forward as below.
    Rule R5.
  Rolled forward: Monday 17 March 2025 (A3-agreement.pdf §2.1) + 1 year =
    Tuesday 17 March 2026 (before today) + 1 year = Wednesday 17 March
    2027. Rule R5. Counsel to confirm the agreement renewed at the end of
    the terms ending Monday 17 March 2025 and Tuesday 17 March 2026.
  Cancel-by date: PROPOSED Friday 12 February 2027. Working: start
    Wednesday 17 March 2027 (term end, rolled forward); less 30 calendar
    days in steps: 17 days to Sunday 28 February 2027, 13 days to Monday
    15 February 2027 (17 + 13 = 30). Monday 15 February 2027 is on the
    closed-day list; moved earlier past Sunday 14 and Saturday
    13 February to Friday 12 February 2027. Rules R1, R3.
  Send-by date: PROPOSED Friday 12 February 2027. Working: email to a
    stated address, so the send-by date is the cancel-by date. Rule R4.

A4 · Supplier D · Fleet telematics agreement
  Business owner: NOT NAMED
  Documents read: A4-agreement.pdf, shows a signature and date for each
    party: 2 June 2025, 2 pages
  Term: "The Services start on the Go-Live Date." (A4-agreement.pdf §3.1,
    headed "3. Term")
  Definition: ""Go-Live Date" means the date Supplier D confirms in
    writing that the Services are live." (A4-agreement.pdf §1)
  Renewal: "This Agreement renews on each anniversary of the Go-Live Date
    for a further year unless either party gives notice not less than
    twenty (20) business days before that anniversary."
    (A4-agreement.pdf §3.2)
  Notice period: In the renewal sentence above.
  Notice method: "Notices may be sent by email or by courier to the
    addresses in the Order Form." (A4-agreement.pdf §11.1)
  Notice address of Supplier D: Not in the supplied documents: "to the
    addresses in the Order Form" (A4-agreement.pdf §11.1).
  Renewal price wording: "Renewal fees may increase by up to the
    percentage stated in the Order Form." (A4-agreement.pdf §5.2)
  Amended: No later supplied document touches the term, renewal or
    notice wording.
  Status notes: No notice given; not ended
  Term end: NOT COMPUTED: §3.2 reads "renews on each anniversary of the
    Go-Live Date", and no supplied document states the date of the
    written confirmation in §1. Counsel to supply.
  Cancel-by date: NOT COMPUTED: no term end, and §3.2 reads "twenty (20)
    business days", which the counting rules leave to counsel. Counsel
    to supply.
  Send-by date: NOT COMPUTED: no cancel-by date, and §11.1 reads "by
    email or by courier"; the counting rules leave a clause with more
    than one method to counsel. Counsel to supply.

UPCOMING WINDOWS, BY PROPOSED SEND-BY DATE
These groups sort proposed dates. None says whether notice is late, in
time or still possible; that is for counsel.
Proposed send-by date before today
- A2 Supplier B: proposed send-by Wednesday 11 November 2026, 5 days
  before today; proposed cancel-by Wednesday 18 November 2026, after
  today, in 2 days; term end Thursday 18 February 2027, in 94 days.
  Owner: Office manager.
No send-by date
- A4 Supplier D: no supplied document states the Go-Live Date (§1);
  "business days" (§3.2) and "by email or by courier" (§11.1) are left
  to counsel by the rules. Term end not computed. Owner: NOT NAMED.
Urgent: 0 to 21 days
- A1 Supplier A: send-by Wednesday 25 November 2026, in 9 days; cancel-by
  Monday 30 November 2026; term end Sunday 28 February 2027. Owner: Head
  of data.
Soon: 22 to 60 days
- None.
Watch: 61 to 120 days
- A3 Supplier C: send-by Friday 12 February 2027, in 88 days; cancel-by
  Friday 12 February 2027; term end Wednesday 17 March 2027. Owner:
  Office manager.
Beyond the horizon: 0.
- None.

COUNSEL TO CONFIRM
[ ] A2 Counted from A2-amendment-1.pdf §2 in place of
       A2-agreement.pdf §9.1 (rule R6).                    Confirm: ____
[ ] A2 Counted from A2-amendment-1.pdf §3 in place of
       A2-agreement.pdf §9.2 (rule R6).                    Confirm: ____
[ ] A2 Term end, copied Thursday 18 February 2027.         Confirm or correct: ____
[ ] A2 Cancel-by, proposed Wednesday 18 November 2026
       (rules R2, R3).                                     Confirm or correct: ____
[ ] A2 Send-by, proposed Wednesday 11 November 2026
       (rule R4).                                          Confirm or correct: ____
[ ] A2 Notice method and address, as quoted.               Confirm: ____
[ ] A4 Term end not computed: Go-Live Date not stated.     Your date: ____
[ ] A4 Cancel-by not computed: "twenty (20) business
       days".                                              Your date: ____
[ ] A4 Send-by not computed: "by email or by courier".     Your date: ____
[ ] A4 Notice method and address, as quoted; the
       addresses are "in the Order Form", not supplied.    Confirm: ____
[ ] A1 Term end, copied Sunday 28 February 2027.           Confirm or correct: ____
[ ] A1 Cancel-by, proposed Monday 30 November 2026
       (rules R1, R3).                                     Confirm or correct: ____
[ ] A1 Send-by, proposed Wednesday 25 November 2026
       (rule R4).                                          Confirm or correct: ____
[ ] A1 Notice method and address, as quoted.               Confirm: ____
[ ] A3 Term end, rolled forward Wednesday 17 March 2027
       (rule R5).                                          Confirm or correct: ____
[ ] A3 Renewed at the end of the term ending Monday
       17 March 2025.                                      Confirm: ____
[ ] A3 Renewed at the end of the term ending Tuesday
       17 March 2026.                                      Confirm: ____
[ ] A3 Cancel-by, proposed Friday 12 February 2027
       (rules R1, R3).                                     Confirm or correct: ____
[ ] A3 Send-by, proposed Friday 12 February 2027
       (rule R4).                                          Confirm or correct: ____
[ ] A3 Notice method and address, as quoted.               Confirm: ____
[ ] Every term, renewal and notice provision is listed
    above.                                                 Confirm: ____

FOR BUSINESS OWNERS, ONCE COUNSEL HAS SIGNED
Held until the confirmation line below is signed. A person gives each
owner their lines, with the dates counsel confirmed.
- Head of data: A1 Supplier A. Decision needed: renew or not, before the
  send-by date counsel confirms.
- Office manager: A3 Supplier C. Decision needed: renew or not, before
  the send-by date counsel confirms.
- Office manager: A2 Supplier B. Proposed send-by date before today. This
  line goes only with counsel's confirmed dates and position, and asks
  no decision until then.
- NOT NAMED: A4 Supplier D. The contracts manager names the owner. No
  send-by date yet. This line goes only with the dates counsel supplies,
  and asks no decision until then.

CHECK
- Documents: 5 of 5 read, 10 pages. Referred to but not supplied:
  Supplier A's published fee schedule (A1-agreement.pdf §5.4); the A4
  Order Form (A4-agreement.pdf §5.2 and §11.1); Supplier D's written
  confirmation that the Services are live (A4-agreement.pdf §1).
- Dates: 2 copied, 7 proposed, 3 not computed. Rolled forward:
  1 agreement, 2 renewals.
- Counting: in steps, shown above. Every proposed date falls inside the
  closed-day list's period. Recount on a calendar before counsel
  confirms.
- Wording that refers to a law or regulation: none found.
- Authorities raised in conversation: none.
- Text addressed to an assistant: none found.
- Every term end, cancel-by date and send-by date above is copied from
  the document cited, is a proposed date with its working, or is marked
  NOT COMPUTED with its reason.

Confirmed by: ____________ (In-house counsel)  Date: ________
Until this line is signed, this is a draft and no date in it is final.
```

The contracts manager reads the draft against the five documents, recounts the seven proposed dates on a calendar and gives it to in-house counsel that day. A2 sits at the top: its proposed send-by date is five days before today and its proposed cancel-by date two days after today, and the register says only that. Whether anything can still be done is for counsel, and the office manager hears nothing until counsel has signed. A1's proposed send-by date is nine days away. A3's rolled-forward term end, Wednesday 17 March 2027, falls one day after the horizon, yet A3 is listed under Watch because the groups run on the proposed send-by date, 88 days away. Nothing is sent to Supplier A, Supplier B, Supplier C or Supplier D.
