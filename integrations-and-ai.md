---
layout: default
title: "Qeemah Integrations & AI Guide — Salla, Shopify, WhatsApp Reminders, POS Hardware & MCP"
description: "Technical overview of Qeemah Cloud integrations: Salla & Shopify e-commerce sync, automated WhatsApp invoice reminders, POS barcode/scale hardware, and AI Assistant (MCP) connectivity."
---

# E-Commerce Sync, WhatsApp Automation, POS Hardware & AI (MCP) Integrations
[← Back to Qeemah Cloud Documentation Hub](./index.html) | [Explore All Integrations on qeemahcloud.com](https://qeemahcloud.com/en/integrations/)

**[Qeemah Cloud](https://qeemahcloud.com/en/)** is designed so your online stores, physical POS registers, warehouses, WhatsApp communications, and AI assistants operate on a single source of truth.

---

## 1. E-Commerce & Storefront Synchronization

### A. Built-in Public Ordering Storefront (`/o/{orgSlug}`)
Every business on Qeemah can activate a branded online ordering portal without paying for a separate e-commerce subscription:
* **Live Catalog & Stock:** Displays real-time product availability, images, categories, and pricing straight from your Qeemah inventory.
* **Delivery & Pickup Flows:** Customers select branch pickup or delivery (with address, date/time window, and order notes).
* **Unified Order Kanban:** Incoming orders land directly in Qeemah's fulfillment board (`Draft → Confirmed → In Preparation → Ready → Out for Delivery → Delivered → Invoiced`), allocating stock on confirmation and converting to an invoice in one click.

### B. Native Salla Integration (`تكامل سلة`)
For merchants running on **[Salla](https://qeemahcloud.com/en/integrations/salla/)**:
* **Automatic Order & Refund Sync:** Webhook-driven synchronization imports Salla orders and cancellations/returns into Qeemah in real time.
* **Customer & Inventory Matching:** Matches products by SKU/barcode, deducts stock from your designated warehouse, and posts the accounting and tax entries automatically.
* **Learn more:** [Qeemah Salla Integration](https://qeemahcloud.com/en/integrations/salla/)

### C. Native Shopify Integration (`تكامل شوبيفاي`)
For merchants selling on **Shopify**:
* **Two-Way Operational Alignment:** Synchronizes Shopify orders, customer profiles, warehouse inventory deductions, and compliant tax invoices directly into your Qeemah General Ledger.
* **Multi-Channel Consolidation:** Compare your Shopify revenue against your in-store [Cloud POS](https://qeemahcloud.com/en/pos-software-saudi/) and wholesale channels in one P&L report.

---

## 2. WhatsApp Business Automation & Faster Collections

Chasing overdue B2B invoices via phone calls or manual emails slows down cash flow. **[Qeemah's WhatsApp Business Integration](https://qeemahcloud.com/en/features/whatsapp-invoice-reminders/)** automates customer communication:

* **Instant Invoice & Receipt Delivery:** Send PDF invoices, quotations, customer account statements, and POS receipts directly to the customer's WhatsApp in one click.
* **Scheduled Payment Reminders:** Configure polite, automated WhatsApp nudges before an invoice falls due, on the due date, and at overdue intervals (aligned with Saudi & UAE business hours).
* **Order Status Updates:** Notify customers automatically on WhatsApp when their order is confirmed, ready for pickup, or out for delivery.
* **Learn more:** [Automated WhatsApp Invoice Reminders](https://qeemahcloud.com/en/features/whatsapp-invoice-reminders/)

---

## 3. Cloud POS Hardware & Offline Resilience

**[Qeemah Point of Sale (POS)](https://qeemahcloud.com/en/pos-software-saudi/)** runs in any modern browser on touchscreen tablets, all-in-one POS terminals, laptops, or desktops—with zero proprietary hardware lock-in:

* **Barcode Scanners:** Plug-and-play support for all USB and Bluetooth 1D/2D barcode scanners, plus mobile camera barcode scanning.
* **Price & Weight Embedded Scale Barcodes:** Native parsing for supermarket, butcher, roastery, and grocery weighted-scale barcodes (`EAN-13` prefixes `20`–`29`), automatically extracting the item SKU and exact weight/price at the register.
* **Thermal Receipt Printers:** Supports standard `58mm` and `80mm` thermal printers with customizable bilingual headers, logos, terms, and QR codes.
* **Shift & Cash Drawer Management:** Open/close cashier shifts, track petty cash in/out, calculate expected vs. actual drawer cash, and support split payments (Cash + Card + Bank Transfer + Store Credit).
* **Offline Mode:** Keep scanning items and completing walk-in sales during internet interruptions; transactions queue locally and synchronize automatically once connectivity is restored.

---

## 4. AI Supplier Invoice OCR & Model Context Protocol (MCP)

### A. AI Scanning of Supplier Purchase Invoices (OCR)
Stop typing long supplier bills line by line. Upload a photo or PDF of a vendor invoice in [Qeemah Inventory & Purchasing](https://qeemahcloud.com/en/inventory-software-saudi/), and Qeemah's AI OCR extracts supplier details, line items, quantities, prices, and tax amounts into a ready-to-review Purchase Invoice.

### B. Connect ChatGPT & AI Assistants via MCP (`Model Context Protocol`)
Qeemah includes native **MCP (`https://api.qeemahcloud.com/api/v1/mcp`)** support with OAuth 2.1 + PKCE security and strict organization-level permission scoping:
* **Executive AI CFO Pulse:** Query your live revenue, expenses, receivables aging, and quarterly VAT liability directly from supported AI hosts.
* **Drafting & XML Auditing:** Draft quotes and invoices from natural-language prompts or audit e-invoice XML payloads in seconds.
* **Entity & AI Documentation:** Machine-readable specifications are maintained at [`qeemahcloud.com/en/llm-info/`](https://qeemahcloud.com/en/llm-info/) and [`qeemahcloud.com/llms.txt`](https://qeemahcloud.com/llms.txt).

---

### Need a Custom Integration Built for Your Business?
At Qeemah, **custom workflows and bespoke integrations are built free of charge** by our engineering team.  
👉 **[Book a 30-Minute Demo](https://qeemahcloud.com/en/demo/)** or **[Contact Our Team](https://qeemahcloud.com/en/contact/)**.
