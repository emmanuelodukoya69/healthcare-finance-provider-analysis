# HealthCare Finance & Provider Performance Analysis

Power BI dashboard analyzing 5,000 patient visits — covering billing, treatment and medication costs, insurance coverage, provider performance, and patient satisfaction across a healthcare center's operations (Jan 2024–May 2025).

<img width="800" height="460" alt="HealthCare_Light Mode" src="https://github.com/user-attachments/assets/71361043-7e6e-4032-b295-1eec8be810ba" />

**Dashboard includes:** KPI summary cards (billing, treatment cost, medication cost, room charges, insurance coverage, out-of-pocket), a billing-by-city map, a billing-by-procedure column chart, a diagnosis/service-type breakdown, a billing-by-department bar chart, and interactive filters by patient location, race, and date (year/quarter/month).

<img width="800" height="460" alt="HealthCare_Dark Mode" src="https://github.com/user-attachments/assets/151e68d6-2697-4772-ac34-de9e72910bcf" />

Built from a healthcare finance requirements brief calling for KPI reporting, financial overview, provider insights, and trend analysis in a single interactive report.

---

## Overview

| Metric | Value |
|---|---|
| Total visits | 5,000 |
| Total patients | 4,973 |
| Total providers | 5 |
| Total billing amount | $3,249,615 |
| Average billing per visit | $650 |
| Average patient satisfaction (1–10) | 3.8 |

---

## Key Findings

### 1. Financial Overview

| Cost Category | Total |
|---|---|
| Treatment cost | $2,630,406 |
| Medication cost | $546,039 |
| Room charges | $73,170 |
| **Total billing amount** | **$3,249,615** |
| Insurance coverage | $2,225,924 |
| Out-of-pocket (patient-paid) | $1,023,691 |

Insurance covers about $2 of every $3 billed; patients carry the remaining $1,023,691 out of pocket.

| Payment Status | Visits |
|---|---|
| Paid | 3,085 |
| Pending | 1,915 |

**1,915 visits — nearly 2 in 5 — are still pending payment**, a meaningful chunk of receivables sitting uncollected.

### 2. Provider Performance

| Provider | Visits | Total Billing | Avg. Satisfaction (1–10) |
|---|---|---|---|
| Dr. Sade Kikiola | 1,875 | $1,214,312 | 2.35 |
| Dr. Olu Abisola | 1,358 | $872,949 | 5.45 |
| Dr. Ravi Patel | 855 | $562,043 | 3.36 |
| Dr. Emma Jones | 467 | $310,181 | 4.85 |
| Dr. Johnson Grek | 445 | $290,130 | 5.05 |

**The highest-earning provider has the lowest patient satisfaction score.** Dr. Sade Kikiola generates the most revenue by a wide margin ($1.21M) but rates lowest on satisfaction (2.35 of 10), while Dr. Olu Abisola pairs high volume with the best satisfaction score (5.45).

### 3. Department & Service Breakdown

| Department | Visits | Total Billing |
|---|---|---|
| Cardiology | 1,281 | $841,895 |
| General Surgery | 1,185 | $768,217 |
| Orthopedics | 1,179 | $766,723 |
| Neurology | 697 | $457,660 |
| Pediatrics | 658 | $415,120 |

| Service Type | Visits |
|---|---|
| Outpatient | 2,520 |
| Inpatient | 1,245 |
| Emergency | 1,235 |

| Top Procedures by Billing | Total Billing |
|---|---|
| X-Ray | $999,679 |
| CT Scan | $799,468 |
| MRI Scan | $585,219 |
| Ultrasound | $468,817 |
| Blood Test | $396,432 |

| Top Diagnoses by Billing | Total Billing |
|---|---|
| Hypertension | $1,306,343 |
| Appendicitis | $653,008 |
| Asthma | $590,605 |
| Fracture | $388,490 |
| Migraine | $311,169 |

Hypertension alone accounts for roughly 40% of all diagnosis-linked billing — by far the single largest cost driver.

### 4. Geography

| State | Total Billing |
|---|---|
| Wales | $1,255,139 |
| Northern Ireland | $988,707 |
| England | $583,285 |
| Scotland | $422,484 |

Edinburgh ($964,684) and Birmingham ($772,150) are the two highest-billing cities, together accounting for more than half of total revenue.

### 5. Trend Over Time

Average billing per visit stayed steady (roughly $620–$690) every month from January 2024 through May 2025 — cost per visit is not drifting up or down.

However, **visit volume shows a data gap**: only 45 visits are recorded in October 2024, none in November 2024, and then a spike to 925 visits in January 2025 — roughly 3x a typical month. This looks like a data-collection gap (Oct–Dec 2024) followed by a catch-up entry batch in January, rather than a genuine demand surge, and is worth flagging before using this period for trend decisions.

---

## Key Insights

- **Revenue and patient satisfaction are not aligned** — the top revenue-generating provider has the lowest satisfaction score, which is a flag for care-quality review, not just a billing success story.
- **Nearly 2 in 5 visits (1,915 of 5,000) are still pending payment**, representing over $1M in potential unresolved receivables and a target for collections follow-up.
- **Hypertension drives the single largest share of diagnosis-linked billing**, making it the top candidate for a dedicated cost/quality management program.
- **Imaging procedures (X-Ray, CT, MRI) together account for over $2.3M in billing** — more than two-thirds of total revenue — making imaging capacity and pricing a major financial lever.
- **The Oct–Dec 2024 reporting gap** means trend figures spanning that window should be interpreted with caution until the data gap is explained or corrected.

---

## Recommendations

1. Investigate the gap between Dr. Sade Kikiola's revenue and satisfaction — review consult length, wait times, or communication practices with the highest-volume provider.
2. Prioritize collections outreach on the 1,915 pending-payment visits (~$1M+ potentially exposed) to improve cash flow.
3. Build a hypertension-specific cost and outcomes review, given it accounts for the largest single share of billing.
4. Evaluate imaging pricing and scheduling efficiency, since X-Ray, CT, and MRI together drive the majority of procedure revenue.
5. Resolve the October–December 2024 data gap before using year-over-year trend figures in financial planning or reporting.
6. Track satisfaction alongside revenue per provider going forward, so high performers are recognized on both dimensions rather than volume alone.

---

*Source: HealthCare Finance & Provider Performance dashboard (Power BI), 5,000-visit dataset spanning patients, providers, departments, diagnoses, procedures, insurance, and visit records (Jan 2024–May 2025).*
