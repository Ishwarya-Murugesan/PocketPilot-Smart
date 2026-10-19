# 💰 PocketPilot Smart

### Safe-to-Spend Intelligence for College Students

**PocketPilot Smart** is a student-focused budgeting web application concept designed to help college students manage their pocket money, track daily expenses, plan savings, and make more informed spending decisions.

Instead of only showing past expenses, PocketPilot Smart aims to answer a practical question:

> **“How much can I safely spend today while keeping enough money for my upcoming expenses and savings goals?”**

## 🎯 Problem Statement

Many college students manage limited monthly allowances, pocket money, scholarships, or part-time income. Inconsistent expense tracking can make it difficult to understand how much money remains available after upcoming commitments and savings.

PocketPilot Smart aims to make everyday budgeting simpler, clearer, and more actionable.

## 💡 Our Proposed Solution

PocketPilot Smart combines expense tracking, budget monitoring, savings goals, and a daily spending allowance in one web application.

### ⭐ Key Features

- **Expense Tracking:** Record daily expenses and organize spending by category.
- **Monthly Budget Dashboard:** View spending, remaining budget, and category-wise totals.
- **Safe-to-Spend Intelligence:** Calculate a suggested daily spending allowance after accounting for planned expenses and savings.
- **What-If Purchase Simulator:** Explore how a potential purchase could affect the remaining daily allowance.
- **Budget Alerts:** Receive understandable alerts when spending approaches or exceeds budget limits.
- **CSV Import (Planned):** Import supported transaction files with validation and duplicate checks.
- **Savings Goal Tracking:** Monitor progress toward personal savings targets.

## 🧮 How Safe-to-Spend Works

Our core idea is to estimate a daily spending allowance using the following formula:

**Daily allowance = (Money remaining − Planned expenses − Savings target) ÷ Days remaining**

The result is a suggested budgeting limit, not a guarantee of affordability. If planned expenses and savings exceed the available money, the application should flag the shortfall instead of displaying a negative amount as spendable money.

### Example

Suppose a student has ₹3,000 remaining, ₹1,000 reserved for upcoming expenses, a ₹500 savings target, and 10 days left in the budgeting period.

- Money remaining: ₹3,000
- Planned expenses: ₹1,000
- Savings target: ₹500
- Days remaining: 10

**Suggested daily allowance = (₹3,000 − ₹1,000 − ₹500) ÷ 10 = ₹150 per day.**

The what-if simulator can then help the student understand how a proposed purchase may change this allowance.

## 🛠️ Proposed Technology Stack

| Component | Technology |
|---|---|
| Frontend | HTML, CSS, JavaScript |
| Backend | Python, Django |
| Database | SQLite for the initial MVP |
| Charts and Visualizations | Chart.js |
| Future Data Analysis | Scikit-learn, if suitable data and a clear use case are available |

## 🔄 Planned Workflow

1. Enter an expense or import a supported CSV file.
2. Validate transaction details and identify possible duplicates.
3. Update category totals, remaining budget, and savings progress.
4. Calculate the Safe-to-Spend allowance.
5. Display budget alerts, dashboard insights, and what-if simulation results.

## 🔐 Privacy and Security

- Use synthetic transaction data for demonstrations.
- Never request UPI PINs, OTPs, or banking passwords.
- Minimize the collection of sensitive financial information.
- Treat forecasts as estimates and explain their assumptions.
- Do not claim direct Google Pay, PhonePe, or bank synchronization unless it is actually implemented and properly authorized.

## 🌱 Expected Impact

PocketPilot Smart aims to help college students:

- Build better spending awareness.
- Plan their daily expenses more confidently.
- Avoid overlooking upcoming financial commitments.
- Track savings goals consistently.
- Understand the potential consequences of purchases before spending.

These benefits will need to be validated through testing with users.

## 🚧 Project Status

**Status: Initial proposal / MVP under development.**

The planned development stages are:

1. Expense entry and category management.
2. Monthly budget and savings tracking.
3. Safe-to-Spend calculation.
4. What-if purchase simulator and budget alerts.
5. Optional forecasting and further improvements.

Features will be marked as completed as they are implemented and tested.

## 🚀 Future Scope

- Improved transaction categorization.
- Optional spending forecasts based on suitable historical data.
- Multilingual guidance for greater accessibility.
- Additional supported import formats.
- Authorized financial-data integrations, subject to availability, permissions, and security requirements.

## 👥 Team

**Team Name:** FINOVATE  
**Team ID:** DEX26291  
**Event:** DEXATHON 2026

## 📚 References

- [Django Documentation](https://docs.djangoproject.com/)
- [Chart.js Documentation](https://www.chartjs.org/docs/)
- [Google Pay Help](https://support.google.com/pay/)
- [Reserve Bank of India](https://www.rbi.org.in/)
- [Scikit-learn Documentation](https://scikit-learn.org/stable/) — optional future development

---

*PocketPilot Smart is a proposed budgeting support tool for educational and informational purposes. It is not a financial advisory service.*
