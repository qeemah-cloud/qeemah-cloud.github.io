---
layout: default
title: "GCC Chart of Accounts (شجرة الحسابات) & Cost Center Templates — Retail, F&B, Wholesale & Contracting"
description: "Free bilingual (Arabic & English) Chart of Accounts and Cost Center templates for Saudi & UAE businesses across Retail, Restaurants, Wholesale, and Contracting by Qeemah Cloud."
---

# GCC Chart of Accounts (`شجرة الحسابات`) & Cost Center Templates
[← Back to Qeemah Cloud Documentation Hub](./index.html) | [Explore Qeemah Accounting & Finance](https://qeemahcloud.com/en/accounting-software-saudi/)

A clean **Chart of Accounts (CoA)** paired with structured **Cost Centers (`مراكز التكلفة`)** is the foundation of accurate financial reporting. Instead of bloating your Chart of Accounts with hundreds of duplicate ledger accounts for every branch, vehicle, or project, **[Qeemah Cloud](https://qeemahcloud.com/en/)** separates **what** happened (Account) from **where/why** it happened (Cost Center / Branch).

> **Need this pre-loaded and customized?** When you join [Qeemah Cloud](https://qeemahcloud.com/en/demo/), our team configures your Chart of Accounts, Cost Centers, and opening balances **free of charge**.

---

## 1. Standard Bilingual Chart of Accounts Structure (KSA & UAE)

Qeemah uses a standard 5-class numbering hierarchy that supports automated daily warehouse GL postings, POS shift summaries, payroll runs, and one-click year-end closing:

| Code Range | Classification (EN) | التصنيف (AR) | Normal Balance | Key Sub-Accounts Included |
| :--- | :--- | :--- | :--- | :--- |
| **`1000 – 1999`** | **Assets** | **الأصول** | Debit (`مدين`) | Cash & Equivalents, Bank Accounts (Al Rajhi, SNB, Alinma, Emirates NBD, FAB), POS Cash Drawers, Accounts Receivable (`ذمم مدينة`), Inventory by Warehouse, Prepaid Expenses, Fixed Assets & Accumulated Depreciation |
| **`2000 – 2999`** | **Liabilities** | **الالتزامات (الخصوم)** | Credit (`دائن`) | Accounts Payable (`ذمم دائنة`), Accrued Salaries & Wages, GOSI Payable (`مستحقات التأمينات`), Output VAT Payable, Customer Advances / Unearned Revenue, End-of-Service Provision (`مخصص مكافأة نهاية الخدمة`) |
| **`3000 – 3999`** | **Equity** | **حقوق الملكية** | Credit (`دائن`) | Partner/Shareholder Capital, Statutory Reserve, Drawings / Current Account, Retained Earnings (`أرباح مبقاة`), Current Year Net Profit/Loss |
| **`4000 – 4999`** | **Revenue** | **الإيرادات** | Credit (`دائن`) | Retail POS Sales, Wholesale B2B Sales, Online Storefront Sales (`/o/{orgSlug}`), Salla & Shopify Synced Sales, Service & Contracting Revenue, Sales Discounts (`خصم مسموح به`), Sales Returns |
| **`5000 – 5999`** | **Cost of Sales & Expenses** | **تكلفة المبيعات والمصروفات** | Debit (`مدين`) | Cost of Goods Sold (COGS - FIFO / Weighted Avg), Raw Materials Consumed (Manufacturing BOM), Direct Labor, Salaries & Housing/Transport Allowances, Branch Rent & Utilities, Delivery & Fleet Expenses, Payment Gateway Fees |

---

## 2. Industry-Specific Cost Center (`مراكز التكلفة`) Blueprints

Rather than creating `5101 - Rent Riyadh Branch`, `5102 - Rent Jeddah Branch`, `5103 - Rent Dammam Branch`, keep **one** `5100 - Rent Expense` account and tag transactions with **Cost Centers** in [Qeemah Cloud](https://qeemahcloud.com/en/accounting-software-saudi/).

### A. Retail, Supermarkets & Multi-Branch Stores
* **Recommended Dimensions:** `Branch / Showroom` + `Sales Channel`
* **Example Cost Centers:**
  * `CC-BR-01` — Riyadh Olaya Showroom (`فرع العليا - الرياض`)
  * `CC-BR-02` — Jeddah Tahlia Branch (`فرع التحلية - جدة`)
  * `CC-CH-POS` — In-Store POS Registers (`نقاط البيع الكاشير`)
  * `CC-CH-ECOM` — Online Ordering & Salla/Shopify (`المتجر الإلكتروني وسلة وشوبيفاي`)
* **How Qeemah Automates It:** POS sales, warehouse stock movements, and cashier shifts tied to a branch automatically post to that branch's Cost Center. → [See Retail & POS Solutions](https://qeemahcloud.com/en/pos-software-saudi/)

### B. Restaurants, Cafés & Cloud Kitchens
* **Recommended Dimensions:** `Outlet / Kitchen` + `Order Fulfillment Type`
* **Example Cost Centers:**
  * `CC-KIT-01` — Central Prep Kitchen (`المطبخ المركزي`)
  * `CC-OUT-01` — Dine-In & Takeaway Counter (`الفرع الرئيسي - محليوسفري`)
  * `CC-DEL-01` — Direct Online Delivery (`/o/{orgSlug}` Storefront)
* **How Qeemah Automates It:** Raw material production orders (BOM) convert ingredients into prepared items in the central kitchen, transfers move stock to branches, and offline-capable POS terminals record shift sales even if internet drops. → [See Inventory & Production](https://qeemahcloud.com/en/inventory-software-saudi/)

### C. Contracting, Engineering & Professional Services
* **Recommended Dimensions:** `Project / Contract` + `Equipment / Vehicle` + `Department`
* **Example Cost Centers:**
  * `CC-PRJ-2026-01` — Villa Construction Contract #104 (`مشروع بناء فيلا رقم 104`)
  * `CC-EQP-07` — Excavator / Delivery Truck #07 (`معدة / شاحنة رقم 07`)
  * `CC-DEP-ENG` — Engineering & Site Supervision (`قسم الهندسة والإشراف`)
* **How Qeemah Automates It:** Every purchase order, supplier invoice (scanned via AI OCR), manual journal entry, quotation, customer invoice, and employee payroll allocation can be linked to a specific Project or Equipment Cost Center—giving you instant P&L per contract. → [Explore ERP for Contracting & Services](https://qeemahcloud.com/en/erp-software-saudi/)

### D. Wholesale & Distribution
* **Recommended Dimensions:** `Warehouse` + `Territory / Sales Rep` + `Product Brand`
* **Example Cost Centers:**
  * `CC-WH-CENTRAL` — Central Distribution Warehouse (`المستودع المركزي`)
  * `CC-REP-CENTRAL` — Central Region Van Sales (`مبيعات المنطقة الوسطى`)
* **How Qeemah Automates It:** Buy in pallets or cartons and sell in individual pieces or boxes with automatic UoM conversion, customer credit limit enforcement, AR aging statements, and automated [WhatsApp overdue payment reminders](https://qeemahcloud.com/en/features/whatsapp-invoice-reminders/).

---

## 3. Automated Payroll & Statutory Accrual Mapping

When running monthly payroll in [Qeemah HR & Payroll](https://qeemahcloud.com/en/features/#payroll), the system automatically posts balanced journal entries:

```
Dr. 5201 Basic Salaries & Wages (الرواتب الأساسية)
Dr. 5202 Housing & Transport Allowances (بدل السكن والنقل)
Dr. 5203 Employer GOSI Contribution (حصة صاحب العمل في التأمينات)
    Cr. 2201 Accrued Net Salaries Payable / WPS (صافي الرواتب المستحقة - مدد)
    Cr. 2202 GOSI Payable - Employee & Employer (مستحقات التأمينات الاجتماعية)
    Cr. 1305 Employee Advances / Loans Deducted (سلف الموظفين المستردة)
```

Need to estimate statutory obligations before running payroll? Use Qeemah's free browser calculators:
* [Saudi GOSI Contribution Calculator](https://qeemahcloud.com/en/tools/gosi-calculator/)
* [Saudi End-of-Service Benefits (EOSB) Calculator](https://qeemahcloud.com/en/tools/eosb-calculator/)
* [UAE Gratuity Calculator](https://qeemahcloud.com/en/tools/uae-gratuity-calculator/)
* [WPS SIF Salary File Generator](https://qeemahcloud.com/en/tools/wps-sif-generator/)
* [Salary Breakdown Calculator](https://qeemahcloud.com/en/tools/salary-breakdown/)

---

### Want our team to set up your Chart of Accounts & Cost Centers for free?
**[Book a 30-Minute Demo on Qeemah Cloud](https://qeemahcloud.com/en/demo/)** — We migrate your existing accounts, balances, and items at zero cost.
