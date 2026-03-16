# Credit Card Fraud Intelligence

A data analytics project examining patterns and risk factors 
in credit card fraud across 500,000 transactions spanning 
8 European countries between January 2024 and September 2025.

---

## Overview

Fraud detection is one of the most commercially critical 
problems in financial services. I built this project to 
go beyond surface-level fraud rates and identify the 
specific conditions — time of day, transaction type, 
security features, merchant category and geography — 
that make a transaction more or less likely to be 
fraudulent.

The dataset covers half a million transactions across 
8 countries with 16 attributes per transaction including 
card type, device, security features, merchant category, 
transaction amount and distance from home.

---

## What I Found

- Overall fraud rate sits at 1.50% across 500,000 
  transactions — representing $1.09M in fraudulent value
- Fraud is perfectly channel-agnostic — ATM, Online and 
  POS all register exactly 1.50%, indicating a 
  sophisticated distributed attack rather than a single 
  channel vulnerability
- Germany carries the highest fraud rate at 1.596%, 
  Canada and USA the lowest at 1.416%
- 05:00 is the peak fraud hour at 1.674% — the dead-of-night 
  window when monitoring is typically reduced
- High-value transactions above $500 carry a 1.74% fraud 
  rate, rising to 2.04% for transactions over $1,000
- The most counterintuitive finding: Chip + PIN transactions 
  show the highest fraud rate of all security combinations 
  at 1.588%, higher than no-chip/no-PIN at 1.505% — 
  strongly suggesting card-present skimming at chip 
  terminals rather than card-not-present fraud
- Germany Platinum cardholders represent the single riskiest 
  country + card type combination at 1.712%
- Groceries via ATM is the riskiest merchant + channel 
  combination at 1.747%
- Transactions made further from home are statistically 
  safer — the 20km+ distance bucket records only 1.311%

---

## Dashboard

The interactive dashboard covers five areas — an executive 
overview with headline KPIs and monthly trends, a geography 
breakdown by country and card type, transaction pattern 
analysis including an hourly heatmap, a risk factor deep 
dive including the Chip + PIN finding, and a merchant 
intelligence page with a category x channel heatmap table.

[View the live dashboard here](https://jokoroma47.github.io/credit-card-fraud-intelligence)

---

## Tools Used

Tableau · MySQL · Excel · Python · HTML · CSS · JavaScript

---

## Data

The dataset contains 500,000 transactions across 16 fields 
covering transaction identity, amount, merchant category, 
card type, security indicators, device type, geography, 
time of transaction and a fraud flag.

All data is used as provided with no scaling or simulation 
applied. The full dataset is available in the /data folder.

---

## Files

| File | Description |
|------|-------------|
| index.html | Interactive web dashboard |
| data/credit_card_fraud_2025.csv | Source dataset |

---

## Contact

**Portfolio:** [jokoroma47.github.io](https://jokoroma47.github.io)
**GitHub:** [@jokoroma47](https://github.com/jokoroma47)
**LinkedIn:** [linkedin.com/in/jeremiah-okoroma-724908116](https://linkedin.com/in/jeremiah-okoroma-724908116)
