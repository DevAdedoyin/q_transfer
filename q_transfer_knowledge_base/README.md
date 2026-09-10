# Q-Transfer Synthetic Fintech Knowledge Base

This is a fictional knowledge base for building and testing a Retrieval-Augmented Generation (RAG) application for Q-Transfer, a fictional fintech company.

## Scope

The dataset covers:
- Company structure
- Branches
- Employees and access
- Customers and KYC
- Local and international transfers
- Fees and FX
- Transaction operations
- AML/CFT and sanctions
- Fraud and risk
- Investments
- Finance and reconciliation
- Technology and security
- Support
- Policies
- Third-party management

## Important

All people, customer records, transaction IDs, investment accounts, branches, products, targets, and company information in this dataset are synthetic.

## Suggested RAG Questions

### Direct retrieval
- What are the transaction states?
- What are the responsibilities of Treasury?
- What does KYC mean at Q-Transfer?
- What investment products does Q-Transfer offer?
- Which branches are in Nigeria?

### Multi-document questions
- What should happen when an international transfer fails?
- How do fraud controls and transaction monitoring work together?
- Which teams may be involved when a customer reports a suspicious transaction?
- What records are important for reconciling a transfer?
- What should happen when an employee leaves Q-Transfer?

### Cross-domain questions
- What is the relationship between KYC, sanctions screening, and transaction monitoring?
- How could a payment incident affect Operations, Compliance, Customer Support, and Engineering?
- What controls should apply to an international transfer from initiation through settlement?

### Out-of-scope tests
Your assistant should say it does not have enough information for questions such as:
- What is Q-Transfer's exact regulatory licence number?
- What is today's GBP/NGN exchange rate?
- What is the exact legal retention period in a specific jurisdiction?
- Who is Q-Transfer's real CEO?
- What is the current balance of a real customer?

These tests are important because a good RAG system should know when the knowledge base does not contain an answer.
