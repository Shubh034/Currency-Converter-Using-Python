# Currency Converter

## Overview
The **Currency Converter** is a Python-based application developed using the **Streamlit** library.  
It provides an interactive user interface to visualize and analyze foreign exchange (FX) rates over different time durations and years. The application also supports currency conversion and comparative analysis between two currencies.

---

## Features

### 1. Data Handling
- Read and store exchange rate data from files
- Fetch FX data for selected currencies and time periods

---

### 2. Interactive User Interface
- Built using **Streamlit**
- Dropdowns and search-enabled selectors for currencies
- Currency names displayed alongside currency codes
- Graphical visualization using **Plotly**

---

### 3. Currency Selection
- **Currency 1**:
  - Auto-populated with **USD** by default
  - Can be changed to any other currency
- **Currency 2**:
  - Search-enabled currency selector
- Ability to select **any two currencies**

---

### 4. Time Duration & Year Selection
Users can view exchange rate trends based on:
- Weekly
- Monthly
- Quarterly
- Annual

Users can also select a **specific year** to view historical data and charts.

---

### 5. Trend Analysis
For the selected currency pair and duration:
- Displays exchange rate trend graph
- Shows:
  - Highest exchange rate with corresponding date
  - Lowest exchange rate with corresponding date

---

### 6. FX Rate Service
- Provides FX rates for **all currencies** using a selected **base currency**
- Example:
  - Base currency: USD
  - Displays value of all other currencies in terms of USD for a given date

---

### 7. Currency Conversion Service
- Converts an amount from one currency to another
- Example:
  - Base currency: USD
  - Target currency: INR
  - Amount: 1000
  - Exchange rate: 79  
  - Result: **79,000 INR**

---

### 8. Cross-Currency Conversion Using USD
- When both se
