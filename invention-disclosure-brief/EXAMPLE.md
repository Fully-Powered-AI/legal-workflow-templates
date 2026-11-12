# Invention disclosure brief for patent counsel: an invented example

*Illustrative example with invented data.* Company A, Customer B, Contractor C, the Event D meetup, Firm E, Customer F, the Event G trade show, every person named below, the invention and every record are invented. Nothing here describes a real product, company, event or person.

Company A makes conveyors and has no lawyer on staff. Its VP Engineering is preparing for a first call with outside patent counsel. Her five inputs come first, in full, then what the workflow template prepares.

## Input 1: the preparer's note

From Rosalind Teague, VP Engineering, Company A, on Wednesday 11 November 2026.

```
Please prepare the invention disclosure brief for Omar's belt drift board
before our first call with patent counsel.

Patent counsel: Joanna Pell, Firm E. Outside patent counsel; we have no
lawyer on staff.
Confidentiality label: Company A Confidential.
Today is Wednesday 11 November 2026.

Attached: Omar's description, the contributor records, the disclosure
log, and the records they point to that I could find. Joanna has not
sent a question list.

Also: do we need to file before the Event G show in December?
```

## Input 2: the inventor's description

```
Belt drift detection from motor current
Omar Linde, controls engineer. Written 2 November 2026.

1. What it is. A small board that fits inside the motor control cabinet
of our KX conveyors and warns the operator when the belt starts running
off-centre, before the belt edge rubs the frame.

2. How it works. The board samples the drive motor's current 2,000 times
a second. When the belt drifts, a small ripple appears in the current
that repeats once per belt revolution. For the first hour after
installation the board records the normal size of that ripple (the
learned level). After that, if the ripple stays more than the set margin
above the learned level for 3 minutes, it lights the amber lamp and
sends a fault code to the line controller.

3. The problem. Customers usually find out about drift when the belt
edge is already frayed. The optical edge sensors we sell as an option get
coated in dust in flour and cement plants and stop reading.

4. What is different. Nothing has to be mounted near the belt;
everything happens in the cabinet. As far as I know nobody detects belt
drift from the motor current. There was a university paper years ago
about finding bearing faults from motor current, not belts. I can't
remember who wrote it.

5. History. I had the idea after a service call at a customer's Plant 3
and wrote it in my notebook on 12 February. Kit Arrowsmith wrote the
first filter code in April. Mei Sato built the first board in May, and we
ran it on the test rig from 20 May.

6. Outside. We ran the prototype at Customer B's plant in June. I showed
a video of it in my talk at the Event D meetup in September. Sales have
put it in the quote for Customer F.

7. Credit. Teodor at Customer B suggested learning the normal ripple
level after installation instead of using a fixed threshold. We did that.
```

## Input 3: the contributor records

An export with the default headers.

```
Person          | Role                          | Organisation at the time | Contribution as recorded                                                                  | Date       | Record
Omar Linde      | Controls engineer             | Company A                | Idea: detect belt drift from once-per-revolution ripple in motor current; notebook sketch | 2026-02-12 | Notebook OL-7, p. 41
Kit Arrowsmith  | Firmware developer (contract) | Contractor C             | First filter code for ripple detection                                                    | 2026-04-14 | Commit 3f9a2c1, firmware repository
Mei Sato        | Hardware engineer             | Company A                | Prototype board, revision A                                                               | 2026-05-06 | Board drawing BS-A rev A
Rosalind Teague | VP Engineering                | Company A                | Design review                                                                             |            |
```

## Input 4: the disclosure log

An export with the default headers.

```
Date                     | Event                              | Audience                               | What was shown or said                                                         | Confidentiality agreement as recorded | Record
2026-06-09 to 2026-06-23 | Field trial, Customer B plant, line 2 | Customer B maintenance team         | Prototype board fitted; live readings shared daily                             | Yes: mutual NDA, 28 May 2026          | Trial report TR-14
2026-09-17               | Talk, Event D meetup               | About 60 attendees; open registration  | 2-minute video of the amber lamp lighting on the test rig; one slide on current ripple | No                             | Slides and video, not attached
2026-12-03               | Demo on stand, Event G trade show  | Trade show visitors                    | Planned: working conveyor with the board fitted                                | Not recorded                          | Stand plan SP-2
```

## Input 5: the records supplied

```
Notebook OL-7, p. 41
  "12 Feb 2026. Plant 3 drift again. Idea: watch motor current for a
   once-per-rev ripple? Compare with a baseline per belt."

Commit 3f9a2c1, firmware repository
  Date: 2026-04-14. Author: Kit Arrowsmith.
  Message: "Add band-pass filter for once-per-rev ripple"

Board drawing BS-A rev A
  Title block: "Drift board, rev A. Drawn M. Sato. 6 May 2026."

Trial report TR-14
  "Customer B, line 2. Trial 10 to 23 June 2026. Board rev A,
   firmware 0.3. Amber lamp lit twice; belt checked both times."

Stand plan SP-2
  "Event G, 3 December 2026. Stand 14. Live KX conveyor with drift
   board."
```

## What the workflow template prepares

A short note to the preparer, then the brief and the missing-records list.

> Rosalind, the brief for Omar's belt drift board is below, with the missing-records list after it. No stop applied. Outside disclosures: 2 logged, 1 mentioned elsewhere and not in the log, 1 planned. Teodor, Customer B, is named in the description, para. 7, and is not in the contributor records. Records differ on the dates of the field trial at Customer B (Disclosure log, row 1; Trial report TR-14). Eight records are missing and nine facts are open.
>
> You asked a question about filing. I have not answered it: it is for Joanna Pell. Counsel to confirm: "Whether to file, where and when: for counsel to decide."
>
> Still to do, by people: check the brief against the records, collect what you can from the missing-records list, get the open facts answered, and send the brief to Joanna Pell. I have sent nothing, searched nothing and counted no date. The brief goes to counsel, not back to the business as an answer.

```
INVENTION DISCLOSURE BRIEF · DRAFT FOR PATENT COUNSEL TO CONFIRM
For Joanna Pell, outside patent counsel, Firm E.
Gives no legal advice. Decides nothing about legal meaning, merit,
validity, privilege, conflicts or deadlines. Sends, files, signs and
calendars nothing, and nothing has been sent, filed, signed or
calendared. Says nothing about whether the invention is new,
patentable or owned by anyone, and gives no view on filing or its
timing. No search was run.
Company A Confidential

Invention, as the records name it: "Belt drift detection from motor
  current"
Prepared by: Rosalind Teague, VP Engineering, 11 November 2026

1. WHAT WAS MADE, IN THE INVENTOR'S WORDS
What it is:
- "A small board that fits inside the motor control cabinet of our KX
  conveyors and warns the operator when the belt starts running
  off-centre, before the belt edge rubs the frame." (Description,
  para. 1)
How it works:
- "The board samples the drive motor's current 2,000 times a second.
  When the belt drifts, a small ripple appears in the current that
  repeats once per belt revolution. For the first hour after
  installation the board records the normal size of that ripple (the
  learned level). After that, if the ripple stays more than the set
  margin above the learned level for 3 minutes, it lights the amber lamp
  and sends a fault code to the line controller." (Description, para. 2)
The problem it addresses, as the inventor puts it:
- "Customers usually find out about drift when the belt edge is already
  frayed. The optical edge sensors we sell as an option get coated in
  dust in flour and cement plants and stop reading." (Description,
  para. 3)
What the inventor says is different:
- "Nothing has to be mounted near the belt; everything happens in the
  cabinet. As far as I know nobody detects belt drift from the motor
  current. There was a university paper years ago about finding bearing
  faults from motor current, not belts. I can't remember who wrote it."
  (Description, para. 4)
  The inventor's own statement. Not checked, and not a finding that
  anything is new.
Referred to but not given:
- "the set margin" (Description, para. 2): its size is not given.
  Asked in 7.
- "a university paper years ago" (Description, para. 4): its authors,
  title and year are not given. Asked in 7.
- "a customer's Plant 3" (Description, para. 5): the customer is not
  named. Asked in 7.
- "Teodor at Customer B" (Description, para. 7): a full name and role
  are not given. Asked in 7.

2. WHO CONTRIBUTED WHAT, AND WHEN
From the contributor records:
- Omar Linde, Controls engineer, Company A: "Idea: detect belt drift
  from once-per-revolution ripple in motor current; notebook sketch".
  2026-02-12. Record: Notebook OL-7, p. 41.
  The record says: "12 Feb 2026. Plant 3 drift again. Idea: watch motor
  current for a once-per-rev ripple? Compare with a baseline per belt."
  (Notebook OL-7, p. 41)
- Kit Arrowsmith, Firmware developer (contract), Contractor C: "First
  filter code for ripple detection". 2026-04-14. Record: Commit
  3f9a2c1, firmware repository.
  The record says: "Add band-pass filter for once-per-rev ripple"
  (Commit 3f9a2c1, message)
- Mei Sato, Hardware engineer, Company A: "Prototype board, revision
  A". 2026-05-06. Record: Board drawing BS-A rev A.
  The record says: "Drift board, rev A. Drawn M. Sato. 6 May 2026."
  (Board drawing BS-A rev A, title block)
- Rosalind Teague, VP Engineering, Company A: "Design review". Date not
  recorded. Record: Not recorded.
Named elsewhere, not in the contributor records:
- Teodor, Customer B: "Teodor at Customer B
  suggested learning the normal ripple level after installation instead
  of using a fixed threshold. We did that." (Description, para. 7)
Who counts as an inventor, and who owns anything, is for counsel.

3. DATED RECORD
- 12 February 2026 · Idea written in notebook, Omar Linde (Contributor
  records, row 1; Notebook OL-7, p. 41; Description, para. 5)
- 14 April 2026 · First filter code for ripple detection, Kit
  Arrowsmith (Contributor records, row 2; Commit 3f9a2c1; Description,
  para. 5, "in April")
- 6 May 2026 · Board drawing BS-A rev A drawn: "Drift board, rev A.
  Drawn M. Sato. 6 May 2026." (Board drawing BS-A rev A, title block);
  "Prototype board, revision A", 2026-05-06 (Contributor records, row 3)
- 28 May 2026 · "mutual NDA, 28 May 2026", as the disclosure log
  records it (Disclosure log, row 1, confidentiality field)
- 9 June 2026 to 23 June 2026 · Field trial, Customer B plant, line 2
  (Disclosure log, row 1; Trial report TR-14; Description, para. 6, "in
  June") Records differ, below.
- 17 September 2026 · Talk, Event D meetup (Disclosure log, row 2;
  Description, para. 6, "in September")
- 3 December 2026 · Demo on stand, Event G trade show, planned
  (Disclosure log, row 3; Stand plan SP-2)
Records differ:
- Field trial, Customer B plant, line 2: 9 June 2026 to 23 June 2026
  (Disclosure log, row 1); 10 June 2026 to 23 June 2026 (Trial report
  TR-14).
Undated or partly dated:
- "I had the idea after a service call at a customer's Plant 3"
  (Description, para. 5). No date given.
- "Mei Sato built the first board in May" (Description, para. 5). Date
  as given: May.
- "we ran it on the test rig from 20 May" (Description, para. 5). Date
  as given: 20 May.
- Design review, Rosalind Teague (Contributor records, row 4). No date
  given.
- Teodor's suggestion (Description, para. 7). No date given.
- The quote for Customer F (Description, para. 6). No date given.

4. OUTSIDE DISCLOSURES
From the disclosure log:
A. 2026-06-09 to 2026-06-23 · Field trial, Customer B plant, line 2
   Audience: Customer B maintenance team
   What was shown or said: Prototype board fitted; live readings shared
   daily
   Confidentiality agreement, as recorded: Yes: mutual NDA, 28 May 2026
   Record: Trial report TR-14. Supplied
   Records differ: see 3.
B. 2026-09-17 · Talk, Event D meetup
   Audience: About 60 attendees; open registration
   What was shown or said: 2-minute video of the amber lamp lighting on
   the test rig; one slide on current ripple
   Confidentiality agreement, as recorded: No
   Record: Slides and video, not attached. Not supplied
Mentioned elsewhere, not in the log:
C. No date given · "Sales have put it in the quote for Customer F."
   (Description, para. 6)
Planned, as recorded:
D. 2026-12-03 · Demo on stand, Event G trade show
   Audience: Trade show visitors
   What was shown or said: Planned: working conveyor with the board
   fitted
   Confidentiality agreement, as recorded: Not recorded
   Record: Stand plan SP-2. Supplied
The brief does not say whether any of these made the invention public,
whether any agreement covered it, or what any of them means.

5. NAMED IN THE RECORDS
- "our KX conveyors" (Description, para. 1). To be verified by the
  lawyer.
- "The optical edge sensors we sell as an option" (Description,
  para. 3). To be verified by the lawyer.
- "a university paper years ago about finding bearing faults from motor
  current, not belts" (Description, para. 4). To be verified by the
  lawyer.

6. COUNSEL'S QUESTIONS
No question list from counsel was supplied.

7. OPEN FACTS
1. What is the size of "the set margin" in paragraph 2? Who can answer:
   Omar Linde. Fills: 1, Referred to but not given.
2. Teodor's full name, his role at Customer B, when he made the
   suggestion, and any message or note that records it. Who can answer:
   Omar Linde. Fills: 1, Referred to but not given; 2, Named elsewhere;
   3, Undated or partly dated.
3. The date of Rosalind Teague's design review, what it covered, and
   where it is recorded. Who can answer: Rosalind Teague. Fills: 2, From
   the contributor records; 3, Undated or partly dated.
4. Did the Customer B trial start on 9 June 2026 or 10 June 2026? Who
   can answer: Omar Linde, or whoever keeps the disclosure log. Fills:
   3, Records differ; 4, A.
5. The Customer F quote: its date, who received it, and what it says
   about the board. Who can answer: Sales (Description, para. 6). Fills:
   4, C; 3, Undated or partly dated.
6. The year of the test rig runs "from 20 May", and where their results
   are recorded. Who can answer: Omar Linde. Fills: 3, Undated or partly
   dated.
7. Which customer's Plant 3 the service call was at, its date, and any
   record of it. Who can answer: Omar Linde. Fills: 1, Referred to but
   not given; 3, Undated or partly dated.
8. Any author, title or year Omar Linde recalls for the university
   paper. Who can answer: Omar Linde. Fills: 1, Referred to but not
   given; 5.
9. On what date, including the year, was the first board built ("Mei
   Sato built the first board in May"), and where is that recorded?
   Who can answer: Mei Sato. Fills: 3, Undated or partly dated.

COUNSEL TO CONFIRM
[ ] Section 1 describes the invention well enough to start from.   ____
[ ] Contributors in 2, including anyone named only elsewhere.      ____
[ ] A. Field trial, Customer B, 2026-06-09 to 2026-06-23.          ____
[ ] B. Talk, Event D meetup, 2026-09-17.                           ____
[ ] C. Quote for Customer F, no date given.                        ____
[ ] D. Demo on stand, Event G trade show, 2026-12-03, planned.      ____
[ ] Field trial, Customer B: 9 June 2026 to 23 June 2026
    (Disclosure log, row 1) or 10 June 2026 to 23 June 2026
    (Trial report TR-14).                                          ____
[ ] Whether to search, and how: for counsel to decide.             ____
[ ] Whether to file, where and when: for counsel to decide.        ____
[ ] Who is named as an inventor, and who owns it: for counsel.     ____
[ ] What any occasion or agreement in 4 means: for counsel to
    decide.                                                        ____
[ ] Which open facts in 7 to answer before the first meeting.      ____

CHECK
- Records read: Description (2 November 2026); Contributor records
  (undated); Disclosure log (undated); Notebook OL-7, p. 41 (12 February
  2026); Commit 3f9a2c1 (14 April 2026); Board drawing BS-A rev A (6 May
  2026); Trial report TR-14 (undated); Stand plan SP-2 (undated).
- Rows read: contributor records 4 of 4; disclosure log 3 of 3.
- Tallies: contributors 4 recorded, 1 named elsewhere; outside
  disclosures 2 logged, 1 mentioned elsewhere, 1 planned; open facts 9;
  records missing 8.
- Description: in the inventor's words.
- No date was counted, and no period was worked out from any date.
- Nothing outside the records supplied was searched or consulted.
- This brief says nothing about whether the invention is new,
  patentable or owned by anyone, and gives no view on filing or its
  timing.

Confirmed by (patent counsel): ____________  Date: ________
Until counsel signs, this is a draft for counsel.

MISSING RECORDS · FOR ROSALIND TEAGUE TO COLLECT
1. "mutual NDA, 28 May 2026" (Disclosure log, row 1, confidentiality
   field): named in the log; not supplied. Supports: 4, A.
    Likely held by: Not known.
2. Event D slides and video as shown on 2026-09-17: the log says "not
   attached". Supports: 4, B.
    Likely held by: Omar Linde, who gave the talk (Description, para. 6).
3. The quote for Customer F: named in the description, para. 6; not in
   the log and not supplied. Supports: 4, C.
    Likely held by: Sales (Description, para. 6).
4. A record of Rosalind Teague's design review: contributor records,
   row 4, has no date and no record. Supports: 2, From the contributor
   records.
    Likely held by: Rosalind Teague.
5. A record of Teodor's suggestion: named in the description, para. 7;
   none supplied. Supports: 2, Named elsewhere.
    Likely held by: Not known.
6. Test rig records from 20 May: named in the description, para. 5;
   none supplied. Supports: 3, Undated or partly dated.
    Likely held by: Not known.
7. A record of the service call at a customer's Plant 3: named in the
   description, para. 5; none supplied. Supports: 3, Undated or partly
   dated.
    Likely held by: Not known.
8. A record of the first board build "in May": named in the
   description, para. 5; none supplied. Supports: 3, Undated or partly
   dated.
    Likely held by: Not known.
Rosalind Teague collects these and decides whom to ask. Nothing is
requested from anyone outside the company by this workflow.
```

The brief copies each of the four rows of the contributor records and quotes the record behind each row that has one. It then lists, under "Named elsewhere", the one person the description names who is not in those records, with the description's own words and paragraph. It weighs none of these against another, and leaves every question about what any of them means to counsel.

Rosalind Teague checks the brief against the records, collects what she can from the list, and asks Omar and the sales team the open facts. Then she sends the brief to Joanna Pell, who confirms each line, decides on search, filing, inventorship and ownership, and answers Rosalind's question about filing. The brief never goes back to the business as an answer.
