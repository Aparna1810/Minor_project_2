# Minor_project_2
# 💸 SpendDNA: Your Wallet's Year-End Story

## 📖 Project Overview

SpendDNA is a Python-based financial analytics project that transforms raw bank and UPI transaction data into meaningful spending insights. The project analyzes six months of transaction history, cleans messy financial records, categorizes spending patterns, detects anomalies, and identifies spending personalities.

The goal is to help users understand where their money goes and generate a detailed financial report from unstructured transaction data.


# ❓ Project Question

**How can raw and unstructured bank transaction data be automatically cleaned, categorized, and analyzed to generate meaningful financial insights and spending patterns?**


# 🚨 Problem Statement

Bank and UPI transaction exports are often messy and difficult to interpret because they contain:

* Multiple date formats
* Different currency and amount formats
* Inconsistent transaction types
* Messy vendor descriptions
* Duplicate and missing values
* Unstructured financial data

As a result, users cannot easily answer questions like:

* Where did my money go?
* Which categories consume most of my spending?
* Am I overspending?
* What kind of spender am I?


# 🎯 Proposed Solution

To solve this problem, I developed an end-to-end transaction analytics pipeline that:

1. Cleans and preprocesses raw transaction data.
2. Standardizes dates, amounts, and transaction types.
3. Extracts vendor names from transaction descriptions.
4. Categorizes transactions into spending groups.
5. Generates financial summaries and monthly trends.
6. Detects anomalous transactions using statistical methods.
7. Identifies user spending archetypes and behavioural patterns.

# 🚀 Features Implemented

## 1. Transaction Parser

* Parsed multiple date formats.
* Standardized amount formats.
* Standardized transaction types.
* Removed duplicate records.

## 2. Vendor Extractor

* Extracted canonical vendor names from messy descriptions.
* Handled multiple vendor name variations.

## 3. Category Tagger

Categorized transactions into:

* Food Delivery
* Quick Commerce
* E-commerce
* Transport
* Restaurants
* Cafe
* Groceries
* Utilities
* Investments
* Entertainment
* Personal Transfer
* Cash Withdrawal

## 4. Spending Overview

Generated:

* Total Credits
* Total Debits
* Net Savings
* Savings Rate
* Top Categories
* Top Vendors

## 5. Monthly Trend Analysis

* Category-wise monthly spending trends.
* Spending growth and decline patterns.

## 6. Time-of-Day Analysis

* Hour-wise spending behaviour analysis.
* Detection of late-night spending patterns.

## 7. Anomaly Detection

* Identified unusually large transactions using Z-Score analysis.

## 8. Spending Archetype Detection

Detected different spending personalities


# 🛠️ Libraries Used

* **Python**
* **Pandas**
* **NumPy**
* **Datetime Module**


# 🧠 How the Problem Was Solved

The project follows the following workflow:

```text
Raw Transaction Data
        ↓
Data Cleaning & Parsing
        ↓
Vendor Extraction
        ↓
Category Mapping
        ↓
Financial Analysis
        ↓
Trend Analysis
        ↓
Anomaly Detection
        ↓
Spending Archetype Detection
        ↓
Final Financial Report
```


# 📈 Output

The project generates:

* Executive Financial Summary
* Spending Category Breakdown
* Vendor Insights
* Monthly Spending Trends
* Time-of-Day Patterns
* Spending Archetypes
* Anomaly Reports
* Key Financial Insights

# 🤖 AI Assistance Disclosure

Artificial Intelligence was used as a learning and debugging aid for:

* Error correction and debugging.
* Code optimization suggestions.
* Improving logic for a few features.
* Reviewing code structure and documentation.

All major design decisions, feature implementation, testing, data analysis, vendor mapping, and final integration were completed manually by the author.


# 📌 Project Constraints

This project was developed using only:

* Python Fundamentals
* Pandas
* NumPy

The following were **not used**:

* Matplotlib
* Seaborn
* Scikit-Learn
* Regex (`re`)
* External transaction analysis libraries
* Machine Learning models
