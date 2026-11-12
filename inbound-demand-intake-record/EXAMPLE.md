# Inbound demand or claim intake record: an invented example

*Illustrative example with invented data.* Lumenbrook Home Goods, Inc., Corvane Fabrication Co., Tamsworth Ilbery LLP, Saltmarsh Quarry LLP, every person named, the State of Eastmere, the Superior Court of Eastmere, the Eastmere Commercial Code section and the case the letter cites are all invented. No real company, firm, court, case or statute is named. The citation in the letter is there to show how the workflow template treats any citation: copied as cited and left for the lawyer to verify.

Lumenbrook sells lamps and home goods online. It has no in-house lawyer, so the record is addressed to its outside counsel. The operations manager's inputs come first, in full, then what the workflow template prepares. Today's date is its own line, and the named lawyer is given in the receipt note. The email reached the chief executive on Monday 9 November and the receipt note does not say when he forwarded it; the record is prepared on Wednesday 11 November, so this example shows the record itself, not same-day handling.

Today's date, supplied with the inputs: Wednesday 11 November 2026.

## Input 1: the receipt note

Written by Marisol Feeney, operations manager, on Wednesday 11 November 2026.

```
Arjun forwarded me the attached letter. It came to his email on Monday
9 November 2026 at 9:40 a.m. from celeste.varga@tamsworthilbery.example,
with two attachments (the two invoices). The courier copy arrived Tuesday
10 November at 11:15 a.m.; Hollis Pendry at reception signed for it. The
courier envelope had the letter only.

We have no in-house lawyer. This goes to our outside counsel, Priya
Halvorsen at Saltmarsh Quarry LLP, today.

Attached: the letter (2 pages), our matter list exported today, our records
map (updated 1 September 2026).

Arjun asks: do we have to pay this, and do they have a case? He also wants
to know how long we have.
```

## Input 2: the letter

```
TAMSWORTH ILBERY LLP
418 Quarry Row, Suite 9, Larkfield, Eastmere 40217
celeste.varga@tamsworthilbery.example · (555) 014-2290

October 30, 2026

FOR SETTLEMENT PURPOSES ONLY
BY EMAIL AND COURIER

Lumenbrook Home Goods, Inc.
Attn: Arjun Oddleifson, Chief Executive Officer
77 Tannery Lane, Larkfield, Eastmere 40219

Re: Corvane Fabrication Co. / Purchase Order PO-7714 and unpaid invoices
Our ref: CF-1182

Dear Mr. Oddleifson:

This firm represents Corvane Fabrication Co. ("Corvane") in connection with
the Supply Agreement between Corvane and Lumenbrook Home Goods, Inc.
("Lumenbrook") dated March 2, 2025 (the "Agreement").

On August 14, 2026, Lumenbrook issued Purchase Order PO-7714 for 6,000
brushed-brass lamp bases. Corvane accepted the order on August 17, 2026 and
began production on August 20, 2026. On September 28, 2026, Lumenbrook's
purchasing lead, Felix Arnaud, emailed Corvane to cancel the order. By then
Corvane had finished 3,900 units, which remain at its plant.

Separately, Corvane's invoices INV-5521 dated July 31, 2026 ($21,400.00) and
INV-5603 dated August 31, 2026 ($9,850.00), for lamp bases delivered under
earlier purchase orders, remain unpaid.

                                                              Page 1 of 2

Section 9.3 of the Agreement permits Lumenbrook to cancel an accepted
purchase order only on 60 days' notice and requires Lumenbrook to pay for
units finished before cancellation. Corvane is also entitled to the price of
the finished units under Eastmere Commercial Code § 14-218 and Pellham Grain
Co. v. Ostby Mills, 212 E.3d 40 (Eastmere Ct. App. 2019).

Corvane therefore demands that Lumenbrook:
  (a) pay the two unpaid invoices, totaling $31,250.00;
  (b) pay $17,000.00 for the 3,900 finished units under PO-7714;
  in total $48,250.00, within fourteen (14) days of the date of this letter;
  (c) preserve all documents, emails and messages concerning PO-7714 and the
      Agreement; and
  (d) direct all communications on this matter to the undersigned.

If payment is not received within that time, Corvane has authorized this
firm to file suit in the Superior Court of Eastmere and to seek interest,
costs and attorneys' fees under Section 14.2 of the Agreement. Corvane will
also suspend work on Lumenbrook's open Purchase Order PO-7790 on November
20, 2026 unless this matter is resolved.

Very truly yours,
[signed]
Celeste Varga
Partner, Tamsworth Ilbery LLP

Enclosures: Invoice INV-5521; Invoice INV-5603; email from F. Arnaud dated
September 28, 2026

                                                              Page 2 of 2
```

## Input 3: the matter list, exported 11 November 2026

```
Matter ID,Matter name,Other parties,References,Status,Opened,Closed,Responsible lawyer
M-2024-02,Warehouse lease renewal,Dunmore Yard Properties LLC,Lease dated 1 June 2021,Closed,2024-01-15,2024-04-30,Priya Halvorsen
M-2025-07,Late-delivery credit,Corvane Fabrication Co.,PO-6120; Supply Agreement dated 2 March 2025,Closed,2025-06-10,2025-09-02,Priya Halvorsen
M-2026-03,Product photo use complaint,Glenarrow Studio,Listing LB-220,Open,2026-03-04,,Priya Halvorsen
M-2026-06,Brass finish customer complaints,Retail customers (several),BB-40 lamp base; PO-7714,Open,2026-09-21,,Priya Halvorsen
M-2026-08,Sales tax registration question,Eastmere Revenue Department,Notice 26-4471,Open,2026-10-05,,Priya Halvorsen
```

## Input 4: the records map, updated 1 September 2026

```
System,Records held,Owner,Automatic deletion
Purchasing system,"Purchase orders, supplier order confirmations, cancellations",Purchasing lead,None
Accounts payable ledger,"Supplier invoices, payments, remittances",Controller,None
Company email,All staff email and attachments,IT administrator,Deleted 24 months after sending
Team chat,Channels and direct messages,IT administrator,Deleted 90 days after posting
Warehouse receiving log,Goods received against each purchase order,Warehouse supervisor,None
Shared drive: Suppliers,"Signed supplier agreements, price lists",Operations manager,None
Customer service desk,Customer tickets and replies,Support lead,Closed tickets deleted after 12 months
```

## What the workflow template prepares

A short note to the operations manager, then the record and the list.

> Marisol, the intake record for the Tamsworth Ilbery letter is below, addressed to Priya Halvorsen at Saltmarsh Quarry LLP.
>
> - Stops: none applied. Both pages carry a footer ("Page 1 of 2", "Page 2 of 2") and both were read; the receipt note gives the date of receipt; a lawyer is named; today's date is given; both tables have the default headers.
> - Periods not counted: two, in section 4 (I and J): "only on 60 days' notice" and "within fourteen (14) days of the date of this letter". The letter's later "within that time" points back to the fourteen days and is listed under J.
> - Enclosure named but not received: "email from F. Arnaud dated September 28, 2026". The email brought "the two invoices"; the courier envelope had the letter only.
> - Possible related matters: M-2025-07 (closed) and M-2026-06 (open), each for counsel to confirm.
> - Requests declined: Arjun asks whether the company has to pay, whether Corvane has a case, and how long the company has. Those are Priya Halvorsen's decisions. I have copied what the letter says about time, marked NOT COUNTED, and worked out no date.
>
> What people still do: read the record against the letter, then give the record, the letter and the list of documents to gather to Priya Halvorsen.
>
> I have sent nothing, contacted no one and changed nothing.

```
DRAFT INTAKE RECORD · FOR Priya Halvorsen, outside counsel · TO REVIEW
Not legal advice. Rates nothing, recommends nothing, counts no date.
Decides nothing about legal meaning, merit, validity, privilege,
conflicts or deadlines.
Nothing has been sent, filed, signed, answered or calendared.

Prepared for: Priya Halvorsen, outside counsel, Saltmarsh Quarry LLP
Prepared from: inputs supplied by Marisol Feeney, operations manager, on
  11 November 2026
Not for the business as an answer. Counsel decides what anyone is told.

1. WHAT ARRIVED
- Heading: "Re: Corvane Fabrication Co. / Purchase Order PO-7714 and unpaid
  invoices" (p. 1, reference line)
- Markings: "FOR SETTLEMENT PURPOSES ONLY" (p. 1, below the date line);
  "BY EMAIL AND COURIER" (p. 1, below the date line)
- Dated: October 30, 2026 (p. 1, date line)
- Addressed to: "Lumenbrook Home Goods, Inc. / Attn: Arjun Oddleifson, Chief
  Executive Officer / 77 Tannery Lane, Larkfield, Eastmere 40219" (p. 1,
  address block)
- Received: Monday 9 November 2026, 9:40 a.m., by email from
  celeste.varga@tamsworthilbery.example with two attachments, to Arjun's
  email, forwarded by Arjun to Marisol Feeney. From the receipt note.
- Other copies received: Tuesday 10 November 2026, 11:15 a.m., by courier,
  signed for by Hollis Pendry at reception; the envelope had the letter
  only.
- Pages: read 2 of 2.
- Enclosures it names: "Invoice INV-5521; Invoice INV-5603; email from F.
  Arnaud dated September 28, 2026" (p. 2, enclosures line)
- Enclosures received: "the two invoices", as the two attachments to the
  email (receipt note)
- Named but not received: email from F. Arnaud dated September 28, 2026

2. WHO SENT IT
- Sender: "TAMSWORTH ILBERY LLP" (p. 1, letterhead)
- Signed by: "Celeste Varga / Partner, Tamsworth Ilbery LLP" (p. 2,
  signature block)
- Acting for: "This firm represents Corvane Fabrication Co. ("Corvane")"
  (p. 1, para. 1)
- Contact details given: "418 Quarry Row, Suite 9, Larkfield, Eastmere
  40217 / celeste.varga@tamsworthilbery.example · (555) 014-2290" (p. 1,
  letterhead)
- Sender's reference: "Our ref: CF-1182" (p. 1, reference line)

3. WHAT IT DEMANDS
1. "(a) pay the two unpaid invoices, totaling $31,250.00;" (p. 2,
   para. 2 (a))
2. "(b) pay $17,000.00 for the 3,900 finished units under PO-7714;"
   (p. 2, para. 2 (b))
3. "in total $48,250.00, within fourteen (14) days of the date of this
   letter;" (p. 2, para. 2)
4. "(c) preserve all documents, emails and messages concerning PO-7714 and
   the Agreement; and" (p. 2, para. 2 (c))
5. "(d) direct all communications on this matter to the undersigned."
   (p. 2, para. 2 (d))
Amounts as written: $21,400.00 (p. 1, para. 3); $9,850.00 (p. 1, para. 3);
  $31,250.00 (p. 2, para. 2 (a)); $17,000.00 (p. 2, para. 2 (b));
  $48,250.00 (p. 2, para. 2)
Arithmetic on the document's own figures: $21,400.00 + $9,850.00 =
  $31,250.00, as stated at (a). $31,250.00 + $17,000.00 = $48,250.00, as
  stated.

4. DATES IT STATES
A. October 30, 2026: the document's date (p. 1, date line)
B. March 2, 2025: "the Supply Agreement between Corvane and Lumenbrook Home
   Goods, Inc. ("Lumenbrook") dated March 2, 2025" (p. 1, para. 1)
C. August 14, 2026: "Lumenbrook issued Purchase Order PO-7714 for 6,000
   brushed-brass lamp bases" (p. 1, para. 2)
D. August 17, 2026: "Corvane accepted the order" (p. 1, para. 2)
E. August 20, 2026: "began production" (p. 1, para. 2)
F. September 28, 2026: "Lumenbrook's purchasing lead, Felix Arnaud, emailed
   Corvane to cancel the order" (p. 1, para. 2); "email from F. Arnaud
   dated September 28, 2026" (p. 2, enclosures line)
G. July 31, 2026: "Corvane's invoices INV-5521 dated July 31, 2026" (p. 1,
   para. 3)
H. August 31, 2026: "INV-5603 dated August 31, 2026" (p. 1, para. 3)
I. NOT COUNTED: "only on 60 days' notice" (p. 2, para. 1).
   Counsel decides what date, if any, this means.
J. NOT COUNTED: "within fourteen (14) days of the date of this letter"
   (p. 2, para. 2).
   Referred back to: "within that time" (p. 2, para. 3)
   Counsel decides what date, if any, this means.
K. November 20, 2026: "Corvane will also suspend work on Lumenbrook's open
   Purchase Order PO-7790 on November 20, 2026" (p. 2, para. 3)

5. FACTS IT ALLEGES
1. "On August 14, 2026, Lumenbrook issued Purchase Order PO-7714 for 6,000
   brushed-brass lamp bases." (p. 1, para. 2)
2. "Corvane accepted the order on August 17, 2026 and began production on
   August 20, 2026." (p. 1, para. 2)
3. "On September 28, 2026, Lumenbrook's purchasing lead, Felix Arnaud,
   emailed Corvane to cancel the order." (p. 1, para. 2)
4. "By then Corvane had finished 3,900 units, which remain at its plant."
   (p. 1, para. 2)
5. "Separately, Corvane's invoices INV-5521 dated July 31, 2026
   ($21,400.00) and INV-5603 dated August 31, 2026 ($9,850.00), for lamp
   bases delivered under earlier purchase orders, remain unpaid." (p. 1,
   para. 3)

6. AUTHORITIES AND CLAUSES IT CITES
1. Section 9.3 of the Agreement (p. 2, para. 1)
   Sentence: "Section 9.3 of the Agreement permits Lumenbrook to cancel an
   accepted purchase order only on 60 days' notice and requires Lumenbrook
   to pay for units finished before cancellation."
   Cited by the sender. Not checked. To be verified by the lawyer.
2. Eastmere Commercial Code § 14-218 (p. 2, para. 1)
   Sentence: "Corvane is also entitled to the price of the finished units
   under Eastmere Commercial Code § 14-218 and Pellham Grain Co. v. Ostby
   Mills, 212 E.3d 40 (Eastmere Ct. App. 2019)."
   Cited by the sender. Not checked. To be verified by the lawyer.
3. Pellham Grain Co. v. Ostby Mills, 212 E.3d 40 (Eastmere Ct. App. 2019)
   (p. 2, para. 1)
   Sentence: the same sentence as 2.
   Cited by the sender. Not checked. To be verified by the lawyer.
4. Section 14.2 of the Agreement (p. 2, para. 3)
   Sentence: "If payment is not received within that time, Corvane has
   authorized this firm to file suit in the Superior Court of Eastmere and
   to seek interest, costs and attorneys' fees under Section 14.2 of the
   Agreement."
   Cited by the sender. Not checked. To be verified by the lawyer.

7. WHAT IT SAYS THE SENDER WILL DO
1. "If payment is not received within that time, Corvane has authorized
   this firm to file suit in the Superior Court of Eastmere and to seek
   interest, costs and attorneys' fees under Section 14.2 of the
   Agreement." (p. 2, para. 3)
2. "Corvane will also suspend work on Lumenbrook's open Purchase Order
   PO-7790 on November 20, 2026 unless this matter is resolved." (p. 2,
   para. 3)

8. RELATED MATTERS ON THE COMPANY'S LIST
Searched: matter list exported 11 November 2026, 5 rows, open and closed,
  for: Corvane Fabrication Co.; Lumenbrook Home Goods, Inc.; Tamsworth
  Ilbery LLP; Celeste Varga; Arjun Oddleifson; Felix Arnaud (also
  "F. Arnaud"); Supply Agreement dated March 2, 2025; PO-7714; PO-7790;
  INV-5521; INV-5603; CF-1182
- M-2025-07, Late-delivery credit, Closed, Priya Halvorsen.
  Matched: "Corvane Fabrication Co." in Other parties; "Supply Agreement
  dated 2 March 2025" in References. Possible match, for counsel to
  confirm.
- M-2026-06, Brass finish customer complaints, Open, Priya Halvorsen.
  Matched: "PO-7714" in References. Possible match, for counsel to
  confirm.

9. WHERE RECORDS MAY BE
Records map: records map, updated 1 September 2026, 7 rows.
- "the Supply Agreement between Corvane and Lumenbrook Home Goods, Inc.
  ("Lumenbrook") dated March 2, 2025" (p. 1, para. 1; as "the
  Agreement", p. 2, paras. 1, 2 (c) and 3): Shared drive: Suppliers
  (map: "Signed supplier agreements"), owner Operations manager.
  Automatic deletion: None.
- "Purchase Order PO-7714" (p. 1, para. 2): Purchasing system (map:
  "Purchase orders"), owner Purchasing lead. Automatic deletion: None.
- Records of what the document says: "Corvane accepted the order on
  August 17, 2026" (p. 1, para. 2): Purchasing system (map: "supplier
  order confirmations"), owner Purchasing lead. Automatic deletion:
  None.
- Records of what the document says: "Felix Arnaud, emailed Corvane to
  cancel the order" (p. 1, para. 2): Purchasing system (map:
  "cancellations"), owner Purchasing lead. Automatic deletion: None.
- "email from F. Arnaud dated September 28, 2026" (p. 2, enclosures
  line; p. 1, para. 2): Company email (map: "All staff email and
  attachments"), owner IT administrator. Automatic deletion: Deleted 24
  months after sending.
- "Invoice INV-5521"; "Invoice INV-5603" (p. 1, para. 3; p. 2,
  enclosures line): Accounts payable ledger (map: "Supplier invoices"),
  owner Controller. Automatic deletion: None.
- Records of what the document says: "lamp bases delivered under
  earlier purchase orders" (p. 1, para. 3): Warehouse receiving log
  (map: "Goods received against each purchase order"), owner Warehouse
  supervisor. Automatic deletion: None.
- "Purchase Order PO-7790" (p. 2, para. 3): Purchasing system (map:
  "Purchase orders"), owner Purchasing lead. Automatic deletion: None.
- "emails" (p. 2, para. 2 (c)): Company email (map: "All staff email
  and attachments"), owner IT administrator. Automatic deletion: Deleted
  24 months after sending.
- "messages" (p. 2, para. 2 (c)): Team chat (map: "Channels and direct
  messages"), owner IT administrator. Automatic deletion: Deleted 90
  days after posting.
- "documents" (p. 2, para. 2 (c)): no single row on the map names this
  record.
People at the company the document names:
- Arjun Oddleifson (p. 1, address block): "Chief Executive Officer", read
  in the address block.
- Felix Arnaud (p. 1, para. 2; "F. Arnaud", p. 2, enclosures line):
  "Lumenbrook's purchasing lead", read in p. 1, para. 2.

10. QUESTION FOR COUNSEL ON KEEPING RECORDS
Does counsel want any records kept beyond the company's usual deletion
rules? If so, which records, held by whom, and from which date?
- The document's own words on keeping records: "(c) preserve all
  documents, emails and messages concerning PO-7714 and the Agreement;
  and" (p. 2, para. 2 (c))
- Systems on the map that delete automatically:
  Company email: Deleted 24 months after sending. Matched in 9
  Team chat: Deleted 90 days after posting. Matched in 9
  Customer service desk: Closed tickets deleted after 12 months. Not
  matched in 9
- No notice has been prepared. No system has been changed.

11. FOR COUNSEL TO CONFIRM OR DECIDE
[ ] Complete: 2 of 2 pages; enclosures as in 1.                ____
[ ] Received 9 November 2026, 9:40 a.m., by email; 10 November
    2026, 11:15 a.m., by courier: correct.                     ____
[ ] Every demand is listed in 3.                               ____
[ ] Every date in 4 is copied correctly.                       ____
[ ] I. Not counted: "only on 60 days' notice".  Counsel's reading: ____
[ ] J. Not counted: "within fourteen (14) days of the date of this
    letter".                                    Counsel's reading: ____
[ ] 1. Section 9.3 of the Agreement: verified by counsel.      ____
[ ] 2. Eastmere Commercial Code § 14-218: verified by counsel. ____
[ ] 3. Pellham Grain Co. v. Ostby Mills, 212 E.3d 40 (Eastmere Ct. App.
    2019): verified by counsel.                                ____
[ ] 4. Section 14.2 of the Agreement: verified by counsel.     ____
[ ] M-2025-07: same matter, related, or unrelated.             ____
[ ] M-2026-06: same matter, related, or unrelated.             ____
[ ] The records and people in 9 are complete.                  ____
[ ] The question in 10 is answered.                            ____
[ ] Who, if anyone, replies to the sender, and when.           ____
[ ] Who else in the company is told, and what.                 ____

12. CHECK
- Pages: read 2 of 2 ("Page 1 of 2", "Page 2 of 2").
- Copied: 5 demands, 9 dates and 2 periods not counted, 5 facts,
  4 authorities and clauses, 2 statements of what the sender will do.
- Matter list: 5 rows, headers matched.
- Records map: 7 rows, headers matched.
- No date was counted. No authority was added, described or checked.
- Every record in 9 and on the list to gather is named in the
  document's own words or by an identifier it gives.
- Every quotation was compared with the document at the place cited.

Received by counsel: ____________  Date: ________
Until counsel signs, this is a draft and nothing in it is a decision.

DOCUMENTS TO GATHER · FOR Priya Halvorsen TO APPROVE
Counsel decides who gathers which item, and when. The assistant gathers
nothing and changes nothing.
1. The letter as received by email, Monday 9 November 2026, with its two
   attachments
   Referred to: receipt note
   Kept in: not on the map
   Held by: Arjun, to whose email it came, and Marisol Feeney, to whom
   he forwarded it
   Status: not gathered.
2. The courier copy of the letter, Tuesday 10 November 2026
   Referred to: receipt note
   Kept in: not on the map
   Held by: Hollis Pendry, reception, who signed for it
   Status: not gathered.
3. "the Supply Agreement between Corvane and Lumenbrook Home Goods, Inc.
   ("Lumenbrook") dated March 2, 2025"
   Referred to: p. 1, para. 1; p. 2, paras. 1, 2 (c) and 3
   Kept in: Shared drive: Suppliers
   Held by: Operations manager
   Status: not gathered.
4. "Purchase Order PO-7714"
   Referred to: p. 1, para. 2
   Kept in: Purchasing system
   Held by: Purchasing lead
   Status: not gathered.
5. Records of what the document says: "Corvane accepted the order on
   August 17, 2026"
   Referred to: p. 1, para. 2
   Kept in: Purchasing system
   Held by: Purchasing lead
   Status: not gathered.
6. Records of what the document says: "Felix Arnaud, emailed Corvane to
   cancel the order"
   Referred to: p. 1, para. 2
   Kept in: Purchasing system
   Held by: Purchasing lead
   Status: not gathered.
7. "email from F. Arnaud dated September 28, 2026" (named as an
   enclosure, not received)
   Referred to: p. 2, enclosures line; p. 1, para. 2
   Kept in: Company email
   Held by: IT administrator
   Status: not gathered.
8. "Invoice INV-5521"; "Invoice INV-5603"
   Referred to: p. 1, para. 3; p. 2, enclosures line
   Kept in: Accounts payable ledger
   Held by: Controller
   Status: not gathered.
9. Records of what the document says: "lamp bases delivered under
   earlier purchase orders"
   Referred to: p. 1, para. 3
   Kept in: Warehouse receiving log
   Held by: Warehouse supervisor
   Status: not gathered.
10. "Purchase Order PO-7790"
   Referred to: p. 2, para. 3
   Kept in: Purchasing system
   Held by: Purchasing lead
   Status: not gathered.
11. "emails", as in demand (c)
   Referred to: p. 2, para. 2 (c)
   Kept in: Company email
   Held by: IT administrator
   Status: not gathered.
12. "messages", as in demand (c)
   Referred to: p. 2, para. 2 (c)
   Kept in: Team chat
   Held by: IT administrator
   Status: not gathered.
13. Matter file M-2025-07, Late-delivery credit
   Referred to: section 8
   Kept in: not on the map
   Held by: Priya Halvorsen (responsible lawyer on the matter list)
   Status: not gathered.
14. Matter file M-2026-06, Brass finish customer complaints
   Referred to: section 8
   Kept in: not on the map
   Held by: Priya Halvorsen (responsible lawyer on the matter list)
   Status: not gathered.
```

Nothing in the record says whether Lumenbrook owes the $48,250.00, whether anything the letter alleges happened, what Section 9.3 of the Agreement means, or when anything is due. Those are Priya Halvorsen's to decide. Items 1 and 2 on the list read "not on the map" because the workflow template does not look up the letter as received on the records map, even though the emailed copy came to a company mailbox: the receipt note says who holds each copy, and keeping them is part of counsel's answer to the question in section 10. The workflow template's work is that she can read the letter's whole content, its citations and the company's own facts in one place, with every line traceable to a page, on the day the letter reaches her.
