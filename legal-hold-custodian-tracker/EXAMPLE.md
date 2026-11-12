# Legal hold custodian tracker: an invented example

*Illustrative example with invented data.* Quillmere Sensor Co., Distributor A, every person named below, the County Court of Velloran, the hold record, its acknowledgement and reminder rules, the reminder text and both exports are all invented. The acknowledgement rule is one invented lawyer’s rule for one invented hold. It is not any real court’s rule or any real company’s practice. The reminder text RT-1 is there only so the example has approved text to copy; it is not a model reminder for anyone to use, and your own counsel writes yours.

Ravi Delacourt, legal operations lead at Quillmere, runs the weekly check on Monday 16 November 2026. Imogen Tarrant, senior counsel, issued the hold. The inputs come first, in full, with today’s date, Monday 16 November 2026, given when Ravi starts the run; then what the workflow template prepares.

## Input 1: counsel’s hold record

```
QUILLMERE SENSOR CO. · LEGAL HOLD RECORD
Hold reference: LH-2026-04
Matter: Distributor A dispute over the 2025 supply agreement (claim in the
  County Court of Velloran)
Issued by: Imogen Tarrant, senior counsel. Changes to this record go
  through her.
Hold issued: 26 October 2026
Record dated: 13 November 2026 (Felix Arnaud added)
Status: Active
Refresh date: 1 December 2026

Custodians in scope
  E1042  Tomasz Brennick     Head of sales
  E1107  Ada Merriwether     Key account manager
  E1188  Jonah Pell          Sales operations analyst
  E0931  Wren Castellane     Supply chain manager
  E1250  Odile Farrant       Finance business partner
  E1019  Bram Okafor         Customer service lead
  E1311  Sunniva Hale        Logistics coordinator      (added 2 November)
  E1276  Felix Arnaud        Product manager            (added 13 November)

Systems in scope (the owner acknowledges)
  Email              E0650  Hana Rook, IT operations lead
  CRM                E0712  Leo Marchetti, CRM administrator
  Warehouse system   E0804  Ines Calloway, warehouse systems lead

How to acknowledge: by replying "Acknowledged" to the notice email.

Acknowledgement rule A-1. Each recipient acknowledges within 5 calendar
days of the day the notice was sent to them. The day sent is not counted.
If the fifth day is a Saturday or a Sunday, the due day is the following
Monday.

Reminder rule. Ravi Delacourt may send one reminder per recipient, using
text RT-1 only, from the day after the due date. After one reminder, an
unacknowledged recipient comes back to me. No reminder to anyone whose
last working day has passed.

Reminder text RT-1, approved by Imogen Tarrant on 26 October 2026:
  Subject: Reminder: legal hold [hold reference]
  Hello [first name],
  On [date sent] you received legal hold notice [hold reference] from
  [issuing lawyer]. We have not yet received your acknowledgement. Please
  read the notice and acknowledge it [how to acknowledge]. If you have
  questions about the notice, please ask [issuing lawyer] directly.
  Thank you,
  [sender name]
```

## Input 2: the acknowledgement log

Exported on 16 November 2026 at 08:00.

```
Recipient ID,Recipient name,Recipient type,System,Hold reference,Sent on,Acknowledged on,Reminders sent,Last reminder on
E1042,Tomasz Brennick,Custodian,,LH-2026-04,2026-10-26,2026-10-27,0,
E1107,Ada Merriwether,Custodian,,LH-2026-04,2026-10-26,2026-10-29,0,
E1188,Jonah Pell,Custodian,,LH-2026-04,2026-10-26,,0,
E0931,Wren Castellane,Custodian,,LH-2026-04,2026-10-26,,1,2026-11-04
E1250,Odile Farrant,Custodian,,LH-2026-04,2026-10-26,2026-10-30,0,
E1019,Bram Okafor,Custodian,,LH-2026-04,2026-10-26,2026-10-28,0,
E1333,Gideon Sault,Custodian,,LH-2026-04,2026-10-26,2026-10-27,0,
E1311,Sunniva Hale,Custodian,,LH-2026-04,2026-11-02,,0,
E1276,Felix Arnaud,Custodian,,LH-2026-04,2026-11-13,,0,
E0650,Hana Rook,System owner,Email,LH-2026-04,2026-10-26,2026-10-27,0,
E0712,Leo Marchetti,System owner,CRM,LH-2026-04,2026-10-26,2026-10-28,0,
E0804,Ines Calloway,System owner,Warehouse system,LH-2026-04,2026-10-26,,0,
E1042,Tomasz Brennick,Custodian,,LH-2026-02,2026-03-09,2026-03-10,0,
```

## Input 3: the HR export

Exported on 16 November 2026 for the people named in the hold record and the log.

```
Employee ID,Name,Job title,Status,Effective date,Last working day,Previous job title
E1042,Tomasz Brennick,Head of sales,Active,,,
E1107,Ada Merriwether,Key account manager,Active,,,
E1188,Jonah Pell,Sales operations analyst,Active,,,
E0931,Wren Castellane,Supply chain manager,Active,,,
E1250,Odile Farrant,Finance business partner,Active,,,
E1019,Bram Okafor,Customer service lead,Leaver,2026-11-20,2026-11-20,
E1311,Sunniva Hale,Procurement coordinator,Role change,2026-11-09,,Logistics coordinator
E1276,Felix Arnaud,Product manager,Active,,,
E0650,Hana Rook,IT operations lead,Active,,,
E0712,Leo Marchetti,CRM administrator,Active,,,
E0804,Ines Calloway,Warehouse systems lead,Active,,,
E1333,Gideon Sault,Sales analyst,Active,,,
```

## Input 4: the offboarding checklist for Bram Okafor

The checklist's heading and its access and equipment lines.

```
Offboarding checklist · Bram Okafor (E1019) · approved by Mae Dunstan,
  HR lead, on 12 November 2026
Access
- Email: mailbox removed by Hana Rook, IT operations lead, on 20 November
  2026 at 18:00. Mail forwarded to Tomasz Brennick for 30 days.
- CRM: account removed by Leo Marchetti, CRM administrator, on 20 November
  2026.
- Shared drive: access removed by Hana Rook on 20 November 2026; personal
  folder moved to the customer service team folder.
Equipment
- Laptop QK-0412: returned on 20 November 2026; wiped and reissued by IT on
  23 November 2026.
```

## What the workflow template prepares

A short note to Ravi, then the tracker.

> Ravi, the tracker for LH-2026-04 is below.
>
> Stops: None.
>
> Overdue on the proposed due dates: 4 (Jonah Pell, Wren Castellane, Ines Calloway, Sunniva Hale).
>
> Reminders drafted: 2 (Jonah Pell, Ines Calloway).
>
> Held back for Imogen Tarrant: 1 (Sunniva Hale, people change, item 3).
>
> Overdue with no reminder for another reason: Wren Castellane, reminder limit reached, item 2.
>
> Earliest dated offboarding line: 20 November 2026, Bram Okafor, 4 days from today.
>
> Still to do, by people: check the tracker against the exports, recount each proposed due date on a calendar, and give the tracker to Imogen Tarrant. Only after Imogen Tarrant has confirmed the proposed due dates (item 7), send the drafted reminders from your own mailbox, only as the reminder rule allows, and record each send in the log.
>
> I have sent nothing and changed nothing.

```
DRAFT FOR Imogen Tarrant, senior counsel · LEGAL HOLD TRACKER
For the lawyer who issued the hold to decide. Gives no legal advice.
Decides nothing about legal meaning, merit, validity, privilege,
conflicts or deadlines. Sends, files, signs and calendars nothing.
Nothing has been changed or deleted. Every due date below is proposed.

Hold: LH-2026-04 · Distributor A dispute over the 2025 supply agreement
  (claim in the County Court of Velloran)
Issued by: Imogen Tarrant, on 26 October 2026 (hold record dated
  13 November 2026)
Status in the record: Active
Checked by: Ravi Delacourt, before it goes to Imogen Tarrant
Today: Monday 16 November 2026

CUSTODIANS
1. Tomasz Brennick (E1042), Head of sales
   Sent 26 October 2026. Acknowledged 27 October 2026.
   Reminders sent: 0.
   Status: ACKNOWLEDGED
   HR: Active
2. Ada Merriwether (E1107), Key account manager
   Sent 26 October 2026. Acknowledged 29 October 2026.
   Reminders sent: 0.
   Status: ACKNOWLEDGED
   HR: Active
3. Jonah Pell (E1188), Sales operations analyst
   Sent 26 October 2026. Not acknowledged.
   Reminders sent: 0.
   Due Monday 2 November 2026 (proposed, rule A-1). Working: sent Monday
   26 October 2026; the day sent is not counted; day 1 Tuesday 27, day 2
   Wednesday 28, day 3 Thursday 29, day 4 Friday 30, day 5 Saturday
   31 October 2026; a Saturday, so the following Monday, 2 November 2026.
   Status: OVERDUE by 14 days
   HR: Active
4. Wren Castellane (E0931), Supply chain manager
   Sent 26 October 2026. Not acknowledged.
   Reminders sent: 1, last 4 November 2026.
   Due Monday 2 November 2026 (proposed, rule A-1). Working: sent Monday
   26 October 2026; the day sent is not counted; day 1 Tuesday 27, day 2
   Wednesday 28, day 3 Thursday 29, day 4 Friday 30, day 5 Saturday
   31 October 2026; a Saturday, so the following Monday, 2 November 2026.
   Status: OVERDUE by 14 days
   HR: Active
5. Odile Farrant (E1250), Finance business partner
   Sent 26 October 2026. Acknowledged 30 October 2026.
   Reminders sent: 0.
   Status: ACKNOWLEDGED
   HR: Active
6. Bram Okafor (E1019), Customer service lead
   Sent 26 October 2026. Acknowledged 28 October 2026.
   Reminders sent: 0.
   Status: ACKNOWLEDGED
   HR: Leaver
7. Sunniva Hale (E1311), Logistics coordinator
   Sent 2 November 2026. Not acknowledged.
   Reminders sent: 0.
   Due Monday 9 November 2026 (proposed, rule A-1). Working: sent Monday
   2 November 2026; the day sent is not counted; day 1 Tuesday 3, day 2
   Wednesday 4, day 3 Thursday 5, day 4 Friday 6, day 5 Saturday
   7 November 2026; a Saturday, so the following Monday, 9 November 2026.
   Status: OVERDUE by 7 days
   HR: Role change
8. Felix Arnaud (E1276), Product manager
   Sent 13 November 2026. Not acknowledged.
   Reminders sent: 0.
   Due Wednesday 18 November 2026 (proposed, rule A-1). Working: sent
   Friday 13 November 2026; the day sent is not counted; day 1 Saturday
   14, day 2 Sunday 15, day 3 Monday 16, day 4 Tuesday 17, day 5
   Wednesday 18 November 2026; not a Saturday or Sunday, so no move.
   Status: NOT YET DUE
   HR: Active

SYSTEMS
A. Email · owner Hana Rook (E0650)
   Sent 26 October 2026. Acknowledged 27 October 2026.
   Reminders sent: 0.
   Status: ACKNOWLEDGED
   HR: Active
B. CRM · owner Leo Marchetti (E0712)
   Sent 26 October 2026. Acknowledged 28 October 2026.
   Reminders sent: 0.
   Status: ACKNOWLEDGED
   HR: Active
C. Warehouse system · owner Ines Calloway (E0804)
   Sent 26 October 2026. Not acknowledged.
   Reminders sent: 0.
   Due Monday 2 November 2026 (proposed, rule A-1). Working: sent Monday
   26 October 2026; the day sent is not counted; day 1 Tuesday 27, day 2
   Wednesday 28, day 3 Thursday 29, day 4 Friday 30, day 5 Saturday
   31 October 2026; a Saturday, so the following Monday, 2 November 2026.
   Status: OVERDUE by 14 days
   HR: Active

OVERDUE ACKNOWLEDGEMENTS
- Jonah Pell, custodian, proposed due 2 November 2026, 14 days overdue,
  reminders sent 0. Reminder 1 drafted below.
- Wren Castellane, custodian, proposed due 2 November 2026, 14 days
  overdue, reminders sent 1. Reminder limit reached: item 2.
- Ines Calloway, owner of Warehouse system, proposed due 2 November
  2026, 14 days overdue, reminders sent 0. Reminder 2 drafted below.
- Sunniva Hale, custodian, proposed due 9 November 2026, 7 days
  overdue, reminders sent 0. Reminder held back for counsel (people
  change): item 3.

PEOPLE CHANGES (HR export dated 16 November 2026)
- Bram Okafor (E1019): Leaver, effective 20 November 2026. Last working
  day 20 November 2026. Item 1.
  Offboarding checklist, approved 12 November 2026:
  - Email: mailbox removed by Hana Rook, IT operations lead, on
    20 November 2026 at 18:00. Mail forwarded to Tomasz Brennick for
    30 days.
  - CRM: account removed by Leo Marchetti, CRM administrator, on
    20 November 2026.
  - Shared drive: access removed by Hana Rook on 20 November 2026;
    personal folder moved to the customer service team folder.
  - Laptop QK-0412: returned on 20 November 2026; wiped and reissued by
    IT on 23 November 2026.
  Bram Okafor is on the hold record as a custodian. The tracker does
  not say which of these lines the hold covers; counsel decides.
  Earliest dated line: 20 November 2026, 4 days from today.
- Sunniva Hale (E1311): Role change, effective 9 November 2026. Job
  title Procurement coordinator, previously Logistics coordinator.
  Item 3.
  No offboarding checklist supplied.

RECORD MISMATCHES
- Gideon Sault (E1333): in the log for LH-2026-04, not on the hold
  record dated 13 November 2026. Log row: "E1333,Gideon Sault,
  Custodian,,LH-2026-04,2026-10-26,2026-10-27,0,". HR export: Sales
  analyst, Active. Item 4.

REFRESH
- Refresh date set by Imogen Tarrant: 1 December 2026. 15 days from
  today. WITHIN 30 DAYS.
- Raised in this run, for the refresh: items 1, 2, 3, 4.

DRAFT REMINDERS · for Ravi Delacourt to send only after Imogen Tarrant
confirms the proposed due dates. Not sent.
Reminder 1. To: Jonah Pell. Text RT-1, approved 26 October 2026, copied
word for word.
   Subject: Reminder: legal hold LH-2026-04
   Hello Jonah,
   On 26 October 2026 you received legal hold notice LH-2026-04 from
   Imogen Tarrant. We have not yet received your acknowledgement. Please
   read the notice and acknowledge it by replying "Acknowledged" to the
   notice email. If you have questions about the notice, please ask
   Imogen Tarrant directly.
   Thank you,
   Ravi Delacourt
Reminder 2. To: Ines Calloway. Text RT-1, approved 26 October 2026,
copied word for word.
   Subject: Reminder: legal hold LH-2026-04
   Hello Ines,
   On 26 October 2026 you received legal hold notice LH-2026-04 from
   Imogen Tarrant. We have not yet received your acknowledgement. Please
   read the notice and acknowledge it by replying "Acknowledged" to the
   notice email. If you have questions about the notice, please ask
   Imogen Tarrant directly.
   Thank you,
   Ravi Delacourt

COUNSEL TO DECIDE OR CONFIRM
[ ] 1. Bram Okafor (E1019), on the hold record as a custodian,
    acknowledged 28 October 2026. HR: Leaver, last working day
    20 November 2026. Offboarding checklist lines copied under PEOPLE
    CHANGES; earliest dated line 20 November 2026, 4 days from today.
                                              Decision: ____
[ ] 2. Wren Castellane (E0931), custodian, overdue by 14 days on the
    proposed due date. Reminders sent: 1, on 4 November 2026. The
    reminder rule says "one reminder per recipient" and "After one
    reminder, an unacknowledged recipient comes back to me." No
    reminder drafted.                         Decision: ____
[ ] 3. Sunniva Hale (E1311), custodian, on the record as Logistics
    coordinator. HR: role change effective 9 November 2026, now
    Procurement coordinator. Not acknowledged; overdue by 7 days on the
    proposed due date. Reminder held back for you; none drafted.
                                              Decision: ____
[ ] 4. Gideon Sault (E1333): in the log for LH-2026-04 with recipient
    type "Custodian", sent 26 October 2026, acknowledged 27 October
    2026; HR export: Sales analyst, Active. Not on the hold record
    dated 13 November 2026.                   Decision: ____
[ ] 5. Refresh date 1 December 2026, 15 days from today. Items 1 to 4
    were raised in this run.                  Decision: ____
[ ] 6. Every custodian and system on the hold record dated 13 November
    2026 is listed above.                     Confirm: ____
[ ] 7. Proposed due dates counted under rule A-1, working shown. No
    drafted reminder is sent until you confirm them.
                                              Confirm or correct: ____

CHECK
- Hold record: LH-2026-04, dated 13 November 2026, issued by Imogen
  Tarrant, Active.
- Acknowledgement log: exported 16 November 2026. Rows for this hold: 12.
  Rows for other holds, ignored: 1. Headers: as expected.
- HR export: dated 16 November 2026, 0 days old, within the 7-day limit.
  Headers: as expected.
- Offboarding checklists: Bram Okafor, approved 12 November 2026.
- On the hold record: 8 custodians, 3 systems. Acknowledged 6;
  not yet due 1; overdue 4; not sent 0; not counted 0.
- Reminders drafted: 2. Held back for the lawyer: 1. Items for the
  lawyer: 7.
- Counting: day by day, shown above. Recount before the tracker goes to
  the lawyer.
- The hold notice was not drafted, read for meaning or changed. No one
  was added to or removed from the record. No data was moved, released
  or deleted.

Checked by (legal operations): ____________  Date: ________
Decided by (issuing lawyer): ____________  Date: ________
```

Gideon Sault is the line to notice. The log shows an acknowledgement dated 27 October 2026, so a tracker that only chased the overdue would never show this row. Gideon Sault is in the log and not on the record, and only Imogen Tarrant can say whether the record or the log is wrong. The workflow template does not add the name to the record and does not take the row out of the log; it puts the question to Imogen Tarrant.

Imogen Tarrant decides items 1 to 5 and confirms 6 and 7. Whatever happens to Bram Okafor’s material before 20 November is Imogen Tarrant’s decision under item 1; the tracker tells nobody to keep, move or remove anything, and it does not say which of the offboarding lines the hold covers. Ravi Delacourt recounts the due dates and gives the tracker to Imogen Tarrant first; the two drafted reminders go out only after she confirms the proposed due dates under item 7. Had the HR export been missing or out of date, the tracker would have been marked NOT READY and no reminder would have been drafted at all. Sunniva Hale gets no reminder from this run: with a role change in the HR export, that waits for Imogen Tarrant under item 3.
