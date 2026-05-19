# Credit Risk Analysis Dashboard

Power BI dashboard analyzing 32,000+ loan records to identify risk 
patterns across borrower demographics, loan purpose, and repayment terms.

---

## Background

Most credit dashboards show you what happened. This one is built to 
show you where the exposure is. The goal was to give a lending team 
a single view that connects loan size, borrower profile, and risk 
classification so they can spot concentration risk at a glance.

---

## What the data shows

| Metric | Finding |
|--------|---------|
| Total loan portfolio analyzed | $331M |
| High risk average loan amount | $19K |
| Low risk average loan amount | $7K |
| Most common loan term | 36 months (66%) |
| Highest volume loan purpose | Education ($61M) |

**High risk borrowers take out nearly 3x more than low risk borrowers**
Average loan amount jumps from $7K for low risk to $19K for high risk,
with a corresponding increase in interest rate. This means the cost of 
a misclassified high-risk borrower is significantly higher than the 
loan count alone would suggest.

**Renters represent the largest borrower segment**
Renters account for the largest share of total loan volume at $150M, 
slightly above mortgage holders. Ownership status alone is not a 
clean predictor of risk category.

**Education and medical loans dominate volume**
Education ($61M) and medical ($56M) are the top two loan purposes 
by volume, which matters for risk modeling since these are often 
non-discretionary borrowing decisions — borrowers may take on higher 
risk because they have no choice.

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
