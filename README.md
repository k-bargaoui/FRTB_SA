# FRTB_SA
This repository implements a modular Python notebook for computing capital requirements under the FRTB Standardized Approach (SA) as per the Basel III regulatory framework. It supports capital charge calculations through SMB, Default Risk Charge (DRC) and Residual Risk Add-On (RRAO). The notebook also features Value-at-Risk (VaR), Expected Shortfall (ES), and stress testing capabilities.

🔎 Overview
The Fundamental Review of the Trading Book (FRTB) is a regulatory standard issued by the Basel Committee on Banking Supervision to overhaul the capital requirements for market risk. The Standardized Approach (SA) is a prescribed, risk-sensitive methodology designed for simplicity, transparency, and comparability.

This implementation goes for auditability with all key parameters and calculations accessible and logged.

🚀 Features
✅ Sensitivity-based capital computation for:

Interest Rate (IR)

Equity (EQ)

Foreign Exchange (FX)

✅ Default Risk Charge (DRC) based on PD, LGD, and exposure.

✅ Residual Risk Add-On (RRAO) based on notional exposures.

✅ Regulatory risk weights and correlation matrices configurable via an object-oriented loader.

✅ Risk metrics:

Historical Value-at-Risk (VaR)

Expected Shortfall (ES)

Stress Testing (5% default shock)

✅ Audit trail via built-in logging to frtb_audit.log
