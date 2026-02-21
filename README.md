# Credit Valuation Adjustment (CVA) Analysis of an FX Forward – Nordea Bank 

This repository contains a complete implementation and analysis of a **Credit Valuation Adjustment (CVA)** calculation for a **long-dated EUR/USD FX forward**, based on a simplified framework commonly used in academic teaching and introductory CVA modeling. The project follows a discrete-time approach consistent with standard lecture material and demonstrates both **analytical** and **Monte Carlo–based** methods for computing **expected exposure** and **CVA**.

![Nordea Photo](Nordea%20photo.png)

## 🏛️ Academic Context and Industry Collaboration

This project was conducted as part of an academic assignment under the supervision of **Jussi Vähä-Vahe, Director of Structured Credit Trading at Nordea Markets**. The project was supported by industry engagement, including study visits to Nordea’s headquarter in Helsinki, which provided valuable practical insight into CVA, counterparty credit risk, and real-world risk management practices within a large financial institution.

## 📄 Project Overview

The analysis considers an FX forward contract between a bank and a corporate counterparty with five years remaining maturity. The CVA is computed as the expected loss due to counterparty default, combining: 
- the expected positive exposure (EE) of the FX forward over time 
- the default probability inferred from CDS spreads 
- the loss given default, derived from an assumed recovery rate 

## 📌 Key Takeaways

This project highlights that CVA is not merely a pricing adjustment, but a dynamic risk management quantity that is sensitive to market movements and counterparty credit quality. The Monte Carlo framework presented here provides a flexible foundation for extending the analysis to more realistic settings, including netting, collateral, and wrong-way risk.
