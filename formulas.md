# 🔢 Tracker Formulas

## Total Applications
=COUNT(AppTracker!A2:A10000)

## Response Rate
=IFERROR(COUNTIF(AppTracker!I2:I10000,"Yes") / COUNT(AppTracker!A2:A10000),0)

## Interview Rate
=IFERROR(COUNTIF(AppTracker!J2:J10000,"Yes") / COUNT(AppTracker!A2:A10000),0)

## Offer Rate
=IFERROR(COUNTIF(AppTracker!K2:K10000,"Yes") / COUNT(AppTracker!A2:A10000),0)

## Follow-Up Rate
=IFERROR(COUNTIF(AppTracker!L2:L10000,"Yes") / COUNT(AppTracker!A2:A10000),0)
