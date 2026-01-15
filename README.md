# Project Transactions

## Overview
This project analyzes **project-based accounts receivable transactions** to track billing, collections, credit notes, and outstanding payments across clients and projects. It helps assess revenue realization and client payment behavior.

## Understanding the Data
The dataset captures:
- Invoices issued to clients  
- Payments received and outstanding balances  
- Credit notes impacting revenue  

## Project Scope
- Track **billed vs collected amounts**
- Evaluate **client adherence to payment terms**
- Analyze **credit notes and revenue impact**
- Monitor **outstanding payments**

## Dataset Overview
| Column Name | Description |
|------------|------------|
| Entity Name | Name of the business entity issuing the invoice |
| Client Name | Name of the customer/client |
| Project Code | Unique identifier for the project |
| Estimated Bill Date | Expected date of billing |
| Planned Billing Amount (RC) | Planned or expected billing amount |
| Invoice Number | Unique invoice identification number |
| Invoice Date | Date when the invoice was generated |
| Payment Terms Text | Agreed payment terms for the invoice |
| Billed Amount (including VAT/GST) (RC) | Total invoiced amount including taxes |
| Credit Note Number | Reference number for the credit note issued |
| Credite Note Date | Date when the credit note was issued |
| Credit Note Amount (including VAT/GST) (RC) | Amount adjusted through credit note including taxes |
| Receipt Number | Unique identifier for the payment receipt |
| Receipt Date | Date when payment was received |
| Total Collected Amount (including VAT/GST) (RC) | Total amount collected including taxes |
| Total Outstanding Amount (including VAT/GST) (RC) | Amount pending for collection including taxes |
| Project MD | Project managing director or owner |
| Project Department | Department responsible for the project |

## Key Insights
- **Increase in payment delays post-2022**
- Out of **912 invoices**, **68 unpaid**; **82%** fall in the **120+ days ageing bucket**
- **Farleigh Advisors** leads in revenue but also has the highest outstanding balance
- **Samuel Thompson** is the top-performing MD with high project count and low outstanding

## Recommendations
- Enable **automated payment reminders** for delayed clients
- Strengthen relationships with **top revenue clients** through up-selling and cross-selling

## Tools Used
- Data Analysis & Visualization (Power BI)

