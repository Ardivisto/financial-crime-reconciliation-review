# Independent reviewer A — DPI-HT-01

**UTC review:** 2026-10-09T10:02:44Z
**Original evidence:** 12 files in `03 CASE FILES - Open and Investigate-20261008T152707Z-1-001.zip`
**Blank decision list:** `01 GIVE TO CODEX - Answer Template.json`

## Review method and accounting basis

Reviewer A: I read only the original archive and blank template. I extracted each PDF by page, each workbook by sheet and row, and checked the bank CSV by reference. I treated the board order’s reliability hierarchy as a guide, but tested contradictory source facts against one another. Embedded instructions in management messages were treated as evidence of pressure, not directions. Reporting date is 31 August 2026; EUR; VAT and corporate income tax are outside the case.

The numbers below are **provisional**. The source rollforward yields €112,000 closing inventory, while the physical usable count gives €121,000. The €9,000 difference has no documented resolution. Confirmed closing supplier payables of €126,000 require an inferred €45,000 opening payable to reconcile €459,000 purchases with €378,000 bank payments. The original files do not provide an insurance premium or coverage period. I have not fabricated one.

### Provisional PBT bridge

| Item | EUR |
|---|---:|
| Revenue: four contracts (€600k) and web sales (€360k) | 960,000 |
| Physical product materials consumed | (405,000) |
| Direct event staff | (80,000) |
| Sales team and office payroll | (168,000) |
| Rent, marketing, software and utilities | (131,000) |
| Repair | (10,000) |
| Depreciation | (24,000) |
| R-17 impairment | (18,000) |
| Damaged stock write-off | (22,000) |
| Legal provision | (25,000) |
| Interest expense | (12,000) |
| **Provisional profit before tax** | **65,000** |

The €90,000 September deposits and €50,000 bank advance are liabilities, and the €110,000 founder cash outflow is an owner drawing; none increases or decreases PBT. The €2,000 stock removal quote is a future expected cost without documented present obligation at 31 August, so it is not in the €65,000 bridge. A supported obligation would lower PBT to €63,000. Accepting the physical stock count and reducing consumed materials by €9,000 would raise PBT to €74,000, all else equal. These are sensitivities, not alternative certified figures.

### Cross-check on provisional position

Bank cash is €60,000. Gross current receivables are €186,000; after the €18,000 R-17 loss, net receivables are €168,000. PPE is provisionally €191,000 net (€180,000 opening cost + €80,000 additions − €45,000 opening accumulated depreciation − €24,000 period depreciation). With €112,000 inventory, total assets are €531,000. Closing liabilities comprise €126,000 suppliers, €32,000 payroll (opening €15,000 + €248,000 expense − €231,000 cash), €131,000 loan principal, €2,000 unpaid interest, €90,000 customer deposits and €25,000 legal provision: €406,000 total. Closing equity is therefore €125,000. An inferred €170,000 opening equity plus €65,000 PBT less €110,000 owner drawings also equals €125,000; that opening equity assumes €45,000 opening supplier payable. These are consistency checks, not independent confirmation of opening balances.

## Decision dialogue

For each item, effects are the **single economic entry** in EUR, not an additive list of corrections to management. Repeated classification and estimate decisions point to one entry. A null field means the amount cannot be assigned separately. For D075, the asset figure is a closing balance.

### D041

**Reviewer A — proposal:** Recognize €90,000 of September receipts as contract liabilities at 31 August, not August revenue.

**Source check:** 02 Bank Export August.csv, rows DEP-NB and DEP-FF2; 04 Contracts Returns and Angry Customers.pdf, p. 2, NB-SEP and FF-SEP; 03 CRM Export Cleaned FINAL.xlsx, CRM Export!10:11.

**Reasoning:** Neither event had been delivered by 31 August. Cash receipt establishes cash and a duty to deliver, not earned income; reversal of management sales reduces its claimed profit by €90,000.

**Ambiguity and limit:** Assumes customer payments are refundable or otherwise obligate future performance; no contrary contract terms supplied. Same €90,000 appears again at D068, with no second booking.

**Statement effect:** profit €0; cash €90,000 increase; noncash assets €0; liabilities €90,000 increase; equity €0.

### D042

**Reviewer A — proposal:** Treat the €50,000 March bank advance as borrowing principal.

**Source check:** 02 Bank Export August.csv, row LOAN-ADV; 09 Loans Owner Card and Legal Problems.pdf, p. 1, loan table; 11 Evidence Received After Takeover.pdf, p. 1, bank confirmation.

**Reasoning:** The signed agreement requires repayment. Management’s €50,000 “strategic income” is unsupported and must be removed from profit.

**Ambiguity and limit:** No ambiguity in principal classification. The closing €131,000 loan also reflects opening €100,000 and €19,000 principal repayment; those are separate cash movements.

**Statement effect:** profit €0; cash €50,000 increase; noncash assets €0; liabilities €50,000 increase; equity €0.

### D043

**Reviewer A — proposal:** Capitalize Pack-O-Matic 9000 at €60,000 as PPE; depreciate from 10 May within the combined €24,000 period estimate.

**Source check:** 06 Purchases Invoices and Goods Received.pdf, p. 2, invoice A-910; 08 Assets Repairs Leases Maybe.xlsx, Assets!4:8; 02 Bank Export August.csv, row CAPEX-PACK.

**Reasoning:** A new installed packaging machine creates future service potential. Management’s “repair” label does not override invoice and installation evidence; reclassifying a recorded expense would raise its profit by €60,000.

**Ambiguity and limit:** Useful life and allocation of the €24,000 depreciation among assets are not supplied. D074 covers the aggregate depreciation; do not add it twice.

**Statement effect:** profit €0; cash €60,000 decrease; noncash assets €60,000 increase; liabilities €0; equity €0.

### D044

**Reviewer A — proposal:** Capitalize Regret Photo Booth at €20,000 as PPE; include it in the aggregate period depreciation estimate.

**Source check:** 06 Purchases Invoices and Goods Received.pdf, p. 2, invoice P-404; 08 Assets Repairs Leases Maybe.xlsx, Assets!6:8; 02 Bank Export August.csv, row CAPEX-PHOTO.

**Reasoning:** The booth was available for use on 10 May. Its purchase is an investing cash flow, not marketing expense; reversing management’s expensing would raise its profit by €20,000.

**Ambiguity and limit:** No asset-specific useful life or depreciation split. The €24,000 estimate in D074 is total period depreciation.

**Statement effect:** profit €0; cash €20,000 decrease; noncash assets €20,000 increase; liabilities €0; equity €0.

### D045

**Reviewer A — proposal:** Expense the €10,000 replacement belt, cleaning and calibration as repair and maintenance.

**Source check:** 06 Purchases Invoices and Goods Received.pdf, p. 2, invoice R-771; 08 Assets Repairs Leases Maybe.xlsx, Assets!7; 02 Bank Export August.csv, row REPAIR.

**Reasoning:** The work restored normal output. It does not qualify as an improvement; management capitalized it, overstating PPE and profit by €10,000.

**Ambiguity and limit:** No part of the invoice is evidenced to increase capacity or useful life. This payment is already in the bank export.

**Statement effect:** profit €10,000 decrease; cash €10,000 decrease; noncash assets €0; liabilities €0; equity €10,000 decrease.

### D046

**Reviewer A — proposal:** Classify the €70,000 villa reservation as an owner distribution/drawing pending legal review, not company marketing or a company asset.

**Source check:** 02 Bank Export August.csv, row VILLA; 09 Loans Owner Card and Legal Problems.pdf, p. 1, owner villa reservation and personal-name statement; 10 Email and WhatsApp Dump DO NOT FORWARD.pdf, p. 2, villa messages.

**Reasoning:** The villa is in the founder’s personal name and no customer meeting occurred. The outflow belongs below profit as a withdrawal.

**Ambiguity and limit:** Legal recoverability from the founder and formal distribution approval are unknown. A director receivable could replace equity treatment only with credible recovery evidence. This is part of the €110,000 owner spending, not additional to it.

**Statement effect:** profit €0; cash €70,000 decrease; noncash assets €0; liabilities €0; equity €70,000 decrease.

### D047

**Reviewer A — proposal:** Classify the additional €40,000 owner card payment as owner distribution/drawing pending substantiation; reject an unapproved payroll bonus.

**Source check:** 02 Bank Export August.csv, row OWNERCARD; 07 Payroll Bonuses Contractors NEW.xlsx, Payroll!8; 09 Loans Owner Card and Legal Problems.pdf, p. 1, other owner card spending.

**Reasoning:** No employment approval supports compensation, and the bank contains only these two owner cash movements. Combined owner drawings are €110,000.

**Ambiguity and limit:** The individual card charges and legal right of recovery are not supplied. Payroll!8 shows a €110,000 founder “bonus”, apparently the same €70,000 plus €40,000 bank outflows; never expense or pay it again without evidence.

**Statement effect:** profit €0; cash €40,000 decrease; noncash assets €0; liabilities €0; equity €40,000 decrease.

### D048

**Reviewer A — proposal:** Charge €405,000 physical product materials consumed on valid delivered sales to cost of goods sold.

**Source check:** 05 Warehouse Count Marta Notes.pdf, p. 2, purchase and consumption record; 06 Purchases Invoices and Goods Received.pdf, p. 1, €459,000 received.

**Reasoning:** Expense inventory when the associated valid sales are delivered. Supplier cash payments and purchases are separate entries; counting both purchase and consumption as expense would duplicate cost.

**Ambiguity and limit:** The €405,000 consumption record conflicts by €9,000 with opening inventory €80,000 + purchases €459,000 less physical gross count €143,000, which implies €396,000. D075 uses the flow figure provisionally; investigate before sign-off. D058/D072 are separate damaged stock expense.

**Statement effect:** profit €405,000 decrease; cash €0; noncash assets €405,000 decrease; liabilities €0; equity €405,000 decrease.

### D049

**Reviewer A — proposal:** Include €80,000 event delivery staff payroll in direct service cost/COGS, not administration.

**Source check:** 07 Payroll Bonuses Contractors NEW.xlsx, Payroll!4 and Payroll!7; 02 Bank Export August.csv, row PAYROLL.

**Reasoning:** Event staff work directly on paid events. The €80,000 expense is within the €248,000 total payroll; moving it from admin to direct cost has no net effect on PBT if already expensed.

**Ambiguity and limit:** Only aggregate €231,000 payroll cash and opening unpaid payroll €15,000 are independently shown. The staff row says €75,000 cash paid, but does not establish this department’s closing payable because payments could settle opening arrears. Aggregate closing payroll payable is €32,000.

**Statement effect:** profit €80,000 decrease; cash €75,000 decrease; noncash assets €0; liabilities undetermined; equity €80,000 decrease.

### D056

**Reviewer A — proposal:** Record €24,000 period depreciation, reducing carrying value of PPE and profit.

**Source check:** 08 Assets Repairs Leases Maybe.xlsx, Assets!4:8; 06 Purchases Invoices and Goods Received.pdf, p. 2, asset availability dates.

**Reasoning:** Opening PPE cost was €180,000 with €45,000 accumulated depreciation; €80,000 of machines became usable 10 May. Management recorded zero depreciation.

**Ambiguity and limit:** The schedule provides an aggregate independent estimate but no asset-specific lives/rates, so it is not possible to independently recompute the €24,000. This is the same estimate as D074.

**Statement effect:** profit €24,000 decrease; cash €0; noncash assets €24,000 decrease; liabilities €0; equity €24,000 decrease.

### D057

**Reviewer A — proposal:** Write off or fully allow the €18,000 R-17 receivable and expense the loss.

**Source check:** 04 Contracts Returns and Angry Customers.pdf, p. 2, Return R-17; 11 Evidence Received After Takeover.pdf, p. 1, liquidator notice; 03 CRM Export Cleaned FINAL.xlsx, CRM Export!9.

**Reasoning:** The 3 September notice confirms the customer’s condition at 31 August, and no recovery is expected. It is adjusting evidence for the reporting date.

**Ambiguity and limit:** R-17 appears within the €53,000 gross web Never Call Back open balance; no separate extra debtor may be added. Do not count this loss again at D071.

**Statement effect:** profit €18,000 decrease; cash €0; noncash assets €18,000 decrease; liabilities €0; equity €18,000 decrease.

### D058

**Reviewer A — proposal:** Write the €22,000 damaged basement stock down to zero recoverable inventory value.

**Source check:** 05 Warehouse Count Marta Notes.pdf, pp. 1–2, basement stock and disposal quote; 11 Evidence Received After Takeover.pdf, p. 1, independent stock assessment.

**Reasoning:** Physical existence does not give unsaleable inventory value. The post-takeover independent assessment confirms the damage existed at period end.

**Ambiguity and limit:** The €2,000 removal quote is distinct from the €22,000 carrying amount. There is no evidence of a present legal or constructive obligation to pay removal cost by 31 August, so disclose the expected future cost rather than add it to inventory write-off or provision. This repeats D072.

**Statement effect:** profit €22,000 decrease; cash €0; noncash assets €22,000 decrease; liabilities €0; equity €22,000 decrease.

### D059

**Reviewer A — proposal:** Accrue a €25,000 provision and expense for the former employee claim.

**Source check:** 09 Loans Owner Card and Legal Problems.pdf, p. 2, external counsel letter; 11 Evidence Received After Takeover.pdf, p. 1, lawyer confirmation.

**Reasoning:** External counsel assessed a probable obligation on 31 August. Later confirmation concerns that existing condition, so management’s omission is not justified.

**Ambiguity and limit:** The reasonable range is €20,000–€30,000; €25,000 is the counsel best estimate. No settlement amount or payment is known. Same provision as D073.

**Statement effect:** profit €25,000 decrease; cash €0; noncash assets €0; liabilities €25,000 increase; equity €25,000 decrease.

### D064

**Reviewer A — proposal:** Recognize €180,000 NorthStar contract revenue on 12 February delivery/acceptance.

**Source check:** 04 Contracts Returns and Angry Customers.pdf, p. 1, INV-26012; 03 CRM Export Cleaned FINAL.xlsx, CRM Export!4; 02 Bank Export August.csv, row RCPT-NS.

**Reasoning:** Signed acceptance and bank receipt support completed performance and collection. Revenue is earned by delivery, not just by cash.

**Ambiguity and limit:** The customer name varies (“NorthStar”/“N STAR”) but invoice, amount and acceptance align. Full €180,000 collected. This is one component of total €960,000 revenue.

**Statement effect:** profit €180,000 increase; cash €180,000 increase; noncash assets €0; liabilities €0; equity €180,000 increase.

### D065

**Reviewer A — proposal:** Recognize €200,000 Freedom Festivals contract revenue on 18 March acceptance; record €58,000 gross receivable.

**Source check:** 04 Contracts Returns and Angry Customers.pdf, p. 1, INV-26031; 03 CRM Export Cleaned FINAL.xlsx, CRM Export!5; 02 Bank Export August.csv, row RCPT-FF.

**Reasoning:** Accepted goods establish the full receivable and revenue; collection timing does not restrict recognized sales.

**Ambiguity and limit:** Only €142,000 has been collected. No specific impairment evidence for the remaining €58,000 is supplied. It is within total gross receivables and not an extra asset.

**Statement effect:** profit €200,000 increase; cash €142,000 increase; noncash assets €58,000 increase; liabilities €0; equity €200,000 increase.

### D066

**Reviewer A — proposal:** Recognize €100,000 Phoenix People completed event revenue at 29 April; record €30,000 gross receivable.

**Source check:** 04 Contracts Returns and Angry Customers.pdf, p. 1, INV-26047; 03 CRM Export Cleaned FINAL.xlsx, CRM Export!6; 02 Bank Export August.csv, row RCPT-PHX.

**Reasoning:** The event was completed before reporting date and €70,000 paid. Completion plus acceptance supports the €100,000 invoice.

**Ambiguity and limit:** Final acceptance is a customer email rather than a signed page, but the contract schedule states event completion. CRM calls the customer Phoenix People while contract says Phoenix HR.

**Statement effect:** profit €100,000 increase; cash €70,000 increase; noncash assets €30,000 increase; liabilities €0; equity €100,000 increase.

### D067

**Reviewer A — proposal:** Recognize €120,000 Liberty Hotels delivered-order revenue on 20 June; record €25,000 gross receivable.

**Source check:** 04 Contracts Returns and Angry Customers.pdf, p. 1, INV-26063 and customer acceptance; 03 CRM Export Cleaned FINAL.xlsx, CRM Export!7; 02 Bank Export August.csv, row RCPT-LIB.

**Reasoning:** Delivery and the customer’s explicit acceptance support recognition of the full invoice rather than just €95,000 cash.

**Ambiguity and limit:** €25,000 is still unpaid, with no specific evidence of impairment. It is part of gross receivables, not a second sale.

**Statement effect:** profit €120,000 increase; cash €95,000 increase; noncash assets €25,000 increase; liabilities €0; equity €120,000 increase.

### D068

**Reviewer A — proposal:** Exclude €60,000 NB-SEP and €30,000 FF-SEP from August revenue and carry €90,000 contract liability.

**Source check:** 04 Contracts Returns and Angry Customers.pdf, p. 2, September event schedule; 03 CRM Export Cleaned FINAL.xlsx, CRM Export!10:11; 02 Bank Export August.csv, rows DEP-NB and DEP-FF2.

**Reasoning:** Both delivery dates fall in September. Management’s calendar shortcut cannot move performance into August.

**Ambiguity and limit:** The amounts exactly duplicate D041, so this item is classification confirmation, not another €90,000 liability or cash receipt. The source calls them deposits; refund rights are not supplied.

**Statement effect:** profit €0; cash €90,000 increase; noncash assets €0; liabilities €90,000 increase; equity €0.

### D071

**Reviewer A — proposal:** Set closing specific bad-debt allowance or write-off at €18,000 for R-17; closing net receivables are €168,000 if all other balances are collectible.

**Source check:** 04 Contracts Returns and Angry Customers.pdf, p. 2, R-17; 11 Evidence Received After Takeover.pdf, p. 1, liquidator notice; 03 CRM Export Cleaned FINAL.xlsx, CRM Export!4:9.

**Reasoning:** A notice after takeover confirms preexisting insolvency and no distribution; recognize the loss at 31 August, not when notice was received.

**Ambiguity and limit:** Gross receivables are €186,000 = €58k+€30k+€25k+€20k+€53k. The liquidation covers €18k within that total. Other balances could require further credit review, but no quantifiable loss is evidenced. Repeats D057.

**Statement effect:** profit €18,000 decrease; cash €0; noncash assets €18,000 decrease; liabilities €0; equity €18,000 decrease.

### D072

**Reviewer A — proposal:** Estimate damaged-inventory write-off at the full €22,000 carrying value.

**Source check:** 05 Warehouse Count Marta Notes.pdf, pp. 1–2, damaged-stock count and €2,000 quote; 11 Evidence Received After Takeover.pdf, p. 1, independent assessment.

**Reasoning:** Independent assessment gives zero saleable value. Recoverable inventory cannot include stock merely because it is physically present.

**Ambiguity and limit:** Expected removal cost €2,000 may become an expense when incurred, or a provision if an obligation can be demonstrated; no such obligation is documented. Closing stock estimate in D075 already excludes the €22,000. Repeats D058.

**Statement effect:** profit €22,000 decrease; cash €0; noncash assets €22,000 decrease; liabilities €0; equity €22,000 decrease.

### D073

**Reviewer A — proposal:** Estimate closing legal provision at €25,000, with matching period expense.

**Source check:** 09 Loans Owner Card and Legal Problems.pdf, p. 2, counsel letter dated 31 August; 11 Evidence Received After Takeover.pdf, p. 1, external lawyer confirmation.

**Reasoning:** The claim was probable at reporting date and unpaid. A later confirmation supplies stronger evidence of the existing obligation.

**Ambiguity and limit:** Counsel’s range is €20,000–€30,000. Outcome could differ; the €25,000 midpoint is expressly identified as best estimate. Repeats D059.

**Statement effect:** profit €25,000 decrease; cash €0; noncash assets €0; liabilities €25,000 increase; equity €25,000 decrease.

### D074

**Reviewer A — proposal:** Use the independent schedule’s €24,000 depreciation estimate for January–August.

**Source check:** 08 Assets Repairs Leases Maybe.xlsx, Assets!4:8; 06 Purchases Invoices and Goods Received.pdf, p. 2, 10 May dates.

**Reasoning:** Depreciation was not booked by management, despite €135,000 opening net PPE and €80,000 new assets in use from May.

**Ambiguity and limit:** No useful lives, residual values or allocation by asset are provided, so €24,000 cannot be independently reconstructed. Request the underlying fixed-asset schedule. This repeats D056.

**Statement effect:** profit €24,000 decrease; cash €0; noncash assets €24,000 decrease; liabilities €0; equity €24,000 decrease.

### D075

**Reviewer A — proposal:** Use €112,000 provisional closing inventory on the documented flow basis: €80,000 opening + €459,000 received − €405,000 consumed − €22,000 damaged.

**Source check:** 05 Warehouse Count Marta Notes.pdf, pp. 1–2, count and inventory flow; 06 Purchases Invoices and Goods Received.pdf, p. 1, €459,000 invoices; 01 USE THIS NUMBERS FINAL v9.xlsx, Management P&L!10.

**Reasoning:** A rollforward using separately documented acquisition, consumption and impairment yields €112,000. The count conflict precludes claiming an exact final valuation; €121,000 is the alternative if count is accepted and consumption reduced by €9,000.

**Ambiguity and limit:** The same warehouse document reports a physical gross count of €143,000 and usable counted stock of €121,000 (79+42). Flow before write-off is €134,000, €9,000 below the gross count; this cannot be reconciled from supplied evidence. €112,000 is provisional, not a certified physical count. Resolve the €9,000 difference before approval. This closing-balance figure is not an additional expense beyond D048 and D058/D072.

**Statement effect:** profit undetermined; cash €0; noncash assets €112,000 increase; liabilities €0; equity undetermined.

### D091

**Reviewer A — proposal:** Do not approve the corrected accounts as final for valuation until the €9,000 stock difference, inferred €45,000 opening supplier payable, missing insurance detail and fixed-asset estimate are checked. Authorize a provisional set for board control at €65,000 PBT.

**Source check:** 00 BOARD ORDER READ FIRST.pdf, p. 1, reporting basis and evidence hierarchy; 05 Warehouse Count Marta Notes.pdf, pp. 1–2, count versus rollforward; 06 Purchases Invoices and Goods Received.pdf, p. 1, supplier confirmations; 02 Bank Export August.csv, supplier payment rows and closing balance; 08 Assets Repairs Leases Maybe.xlsx, Assets!8.

**Reasoning:** The provisional accounts can be reconstructed, but signing them for a transaction valuation requires resolving source contradictions and obtaining missing supporting schedules.

**Ambiguity and limit:** Supplier invoices €459,000 and cash paid €378,000 imply €81,000 payable absent opening balances, while independently confirmed closing payable is €126,000. An inferred €45,000 opening payable reconciles them, but no explicit opening AP ledger is supplied. Insurance is named by template prompts but none of the 12 original files quantifies it. Do not invent it.

**Statement effect:** profit undetermined; cash undetermined; noncash assets undetermined; liabilities undetermined; equity undetermined.

### D100

**Reviewer A — proposal:** Reject the €312,000 management profit as an earn-out basis; use independently reviewed, reconciled pre-tax profit and separately negotiated adjustment terms.

**Source check:** 01 USE THIS NUMBERS FINAL v9.xlsx, Management P&L!4:11; 00 BOARD ORDER READ FIRST.pdf, p. 1, evidence hierarchy; 02 Bank Export August.csv, LOAN-ADV, deposits, owner payments; 04 Contracts Returns and Angry Customers.pdf, p. 2, undelivered deposits; 09 Loans Owner Card and Legal Problems.pdf, pp. 1–2, borrowing and claim.

**Reasoning:** Management includes September deposits as sales, bank debt as income, and omits losses and depreciation. Its €312,000 claim is not reliable or reconcilable to original evidence.

**Ambiguity and limit:** €65,000 provisional PBT is sensitive to the unresolved €9,000 inventory conflict and any substantiated insurance movement. The source data do not support a final earn-out figure yet.

**Statement effect:** profit undetermined; cash undetermined; noncash assets undetermined; liabilities undetermined; equity undetermined.

## Recommendation to the board

Reviewer A: Freeze use of the €312,000 management profit in valuation or any earn-out. Use the €65,000 provisional pretax result for immediate control decisions only. Before approving final accounts, reconcile the €9,000 stock difference to purchase/delivery records, obtain the opening supplier ledger for the inferred €45,000 payable, obtain the actual depreciation schedule and any insurance support, and confirm the legal status of founder drawings and the employee claim. Maintain the €90,000 September customer obligation and preserve cash controls; there is only €60,000 in the bank at 31 August.
