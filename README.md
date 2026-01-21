# cash-reconciliation-n8n
AI-powered cash reconciliation workflow built with n8n

# Cash Reconciliation Automation (n8n)

## 🚀 Overview
This n8n workflow automates **cash reconciliation** by matching bank statements with open invoices using
rule-based logic and AI validation.

It eliminates manual reconciliation work for finance teams and improves accuracy and speed.

---

## 🧩 Problem Statement
Manual cash reconciliation is:
- Time-consuming
- Error-prone
- Difficult at scale

Finance teams spend hours matching bank entries with invoices across ERP systems.

---

## ✅ Solution
This automation:
- Reads invoice and bank data from Excel
- Normalizes transaction data
- Matches transactions using logic + AI
- Generates reconciliation results automatically

---

## 🏗 Architecture
![Architecture](architecture/architecture.png)

---

## ⚙️ Workflow Steps
1. Load open invoices (Excel)
2. Load bank statement
3. Normalize transaction data
4. Apply matching logic (amount, date, reference)
5. AI validates uncertain matches
6. Output reconciliation summary

---

## 📦 Input
- Bank Statement (Excel)
- Invoice Data (Excel / ERP export)

---

## 📤 Output
- Matched transactions
- Unmatched invoices
- Reconciliation summary

---

## 🛠 Tech Stack
- n8n
- JavaScript
- OpenAI
- Microsoft Excel API

---

