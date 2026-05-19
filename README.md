# Credit Risk Analysis Dashboard

Power BI dashboard analyzing 32,000+ loan records to identify risk 
patterns across borrower demographics, loan purpose, and repayment terms.

---

## Background

Most credit dashboards show you what happened. This one is built to 
show you where the exposure is. Having worked across financial and 
healthcare data, I wanted to build something that gives a lending team 
a single view connecting loan size, borrower profile, and risk 
classification so they can spot concentration risk at a glance rather 
than across three separate reports.

---

## What the data shows

| Metric | Finding |
|--------|---------|
| Total portfolio analyzed | $331M |
| High risk loan volume | $150M (45% of portfolio) |
| Medium risk loan volume | $100M (30% of portfolio) |
| Low risk loan volume | $60M (18% of portfolio) |
| High risk average loan | $19K |
| Low risk average loan | $7K |
| Largest loan purpose | Education ($61M) |
| Most common loan term | 36 months (66%) |

**High risk borrowers take out nearly 3x more than low risk borrowers**
Average loan amount jumps from $7K for low risk to $19K for high risk 
with a corresponding increase in interest rate. This means the cost of 
a misclassified high-risk borrower is significantly higher than loan 
count alone would suggest. Nearly half the portfolio by dollar value 
sits in the high risk category.

**Education and medical loans dominate volume at $117M combined**
Education ($61M) and medical ($56M) are the top two purposes by volume. 
These are largely non-discretionary borrowing decisions, meaning 
borrowers may accept unfavorable terms because they have no alternative, 
which concentrates risk in segments that are harder to screen out.

**Renters carry more total exposure than mortgage holders**
Renters account for $150M vs $140M for mortgage holders. Home ownership 
status is not a clean risk predictor here, which suggests the portfolio 
may need additional segmentation beyond standard borrower profiles.

**Two thirds of borrowers choose shorter 36 month terms**
66% of loans are on 36 month terms vs 34% on 60 months. Shorter terms 
mean higher monthly payments and potentially higher default risk for 
borrowers who are already in the high risk category.

---

## Dashboard

See `Credit_Risk_Analysis_Dashboard.pdf` for full visuals.

Filters included for risk category, loan purpose, home ownership, 
and loan term.

---

## Files

- `Credit_Risk_Analysis_Dashboard.pdf` — dashboard export
- `cleaned_credit_risk.xlsx` — cleaned dataset

---

## Tools

Power BI, Microsoft Excel

Dashboard built from raw loan data — cleaning, risk categorization, 
and DAX measures built from scratch.

---

*Understanding where dollar exposure concentrates — not just where 
borrower count is highest — is what separates a risk dashboard from 
a reporting dashboard.*
