# 📱 UPI Transaction Data Analysis - Power BI Dashboard

A comprehensive Power BI dashboard analyzing UPI (Unified Payments Interface) transaction data with advanced interactivity. Features multiple synchronized slicers, bookmarks for quick view switching, and drill-through capabilities for in-depth transaction insights across cities, payment methods, and merchant categories.

---
Priview - https://app.powerbi.com/links/AXtyxy0ZMA?ctid=886abe6e-5df5-4218-aa37-00e1df3c3234&pbi_source=linkShare&bookmarkGuid=9f7508d9-bd42-4046-ad2e-fba8ed97ffbc

## 📋 Project Overview

This Power BI project provides detailed analysis of digital payment transactions including transaction volumes, balance trends, geographic distribution, and payment method analysis. Built with **multiple synced slicers, interactive bookmarks for view switching, and dynamic filtering** for seamless data exploration.

**Dataset:** UPI Transaction Database (2024)  
**Tool:** Microsoft Power BI Desktop  
**Analysis Period:** Year 2024 (Monthly data)  
**Geographic Coverage:** India (Delhi, Hyderabad, and more)  
**Features:** Multi-slicer sync, Bookmarks (view switching), Drill-through, Line & Column charts

---

## 🎯 Key Metrics & KPIs

| Metric | Value | Insight |
|--------|-------|---------|
| **Total Transaction Volume** | 1.6M+ transactions/month | Consistent monthly transactions |
| **Peak Transaction Month** | ~1.7M (February) | February shows highest activity |
| **Currency Support** | USD, GBP | Multi-currency transactions enabled |
| **Geographic Spread** | Delhi, Hyderabad | Major metro city focus |
| **Device Types** | Multiple | Cross-platform transactions |
| **Average Remaining Balance** | ~84M+ (various currencies) | Strong account balances maintained |

---

## 📊 Dashboard Features

### **1. Transaction Trends Analysis**
- **Monthly Transaction Volume (Line Chart):** Year 2024 trends
  - February: 1,693K transactions
  - April: 1,646K transactions
  - June: 1,599K transactions
  - August: 1,691K transactions
  - October: 1,653K transactions
  - December: 1,663K transactions

- **Amounts Column Chart:** Monthly transaction amounts
- **Balance Tracking:** Remaining balance trends over time

### **2. Advanced Filtering & Slicers (SYNCED)**
Interactive slicers for multi-dimensional exploration:
- **Bank Name Sent** - Source bank filter
- **Bank Name Received** - Destination bank filter
- **City** - Geographic location (Delhi, Hyderabad)
- **Device Type** - Mobile, Web, ATM, etc.
- **Gender** - Customer gender demographics
- **Age Groups** - Age-based segmentation
- **Merchant Name** - Merchant-specific analysis
- **Payment Method** - UPI, Card, Net Banking, etc.
- **Purpose** - Transaction purpose category
- **Currency** - USD, GBP filtering

### **3. Dynamic City View**
- City-wise transaction breakdown (Delhi vs Hyderabad)
- Month-by-month comparison across cities
- Amount and balance tracking per city

### **4. Interactive Bookmarks (View Switching)**
Quick navigation buttons to switch between pre-saved filtered views:

| Bookmark | What It Shows | Use Case |
|----------|---|---|
| **Overall View** | All data, no filters | See complete dashboard |
| **Delhi Focus** | Automatically filters to Delhi | Analyze Delhi-only transactions |
| **Hyderabad Focus** | Automatically filters to Hyderabad | Analyze Hyderabad-only transactions |
| **Mobile Payments** | Filters to mobile device type only | See mobile transaction patterns |
| **High-Value Trans** | Shows large transaction amounts | Analyze premium transactions |
| **Premium Users** | Age 25-50, high balance accounts | Target high-value segment |

**How to Use:** Click any bookmark button at the top of the dashboard to instantly switch views without manually adjusting slicers.

### **5. Synchronized Slicer Experience**
All slicers work together seamlessly:
- Select city → Charts update automatically
- Filter payment method → All visualizations refresh
- Choose age group → Related data syncs across dashboard
- Multi-select capability on all dimensions

---

## 📈 Data Insights

### **Key Findings:**

**1. Transaction Volume Patterns**
- Consistent monthly transactions around 1.6M-1.7M range
- Minimal seasonal variation (only ~100K difference)
- Indicates stable, recurring transaction behavior
- Peak in February (1,693K) and August (1,691K)

**2. Geographic Distribution**
- Delhi and Hyderabad are primary transaction hubs
- Both cities show similar transaction volumes
- Opportunity to expand to other metros

**3. Balance Maintenance**
- Consistent remaining balances around 83-85M
- Healthy account liquidity maintained month-to-month
- Slight growth trend in balance

**4. Multi-Currency Transactions**
- USD and GBP support indicates international transactions
- Growing cross-border payment capability
- Diversified currency portfolio

**5. Device & Payment Method Diversity**
- Multiple device types supported (Mobile, Web, ATM)
- Various payment methods enabled
- Multi-channel transaction capability

---

## 🛠️ Technical Stack

- **Business Intelligence Tool:** Microsoft Power BI Desktop
- **Data Source:** UPI Transaction Database
- **Visualization Types:** Line Charts, Column Charts, Tables, KPI Cards, Slicers
- **Advanced Features:**
  - ✅ **Synchronized Slicers** - All filters work together
  - ✅ **Bookmarks** - Saved filter states for quick view switching
  - ✅ **Drill-through** - Deep dive into transaction details
  - ✅ **Multi-select Filtering** - Complex data queries
  - ✅ **DAX Calculations** - Custom measures and columns
  - ✅ **Dynamic Sorting** - Interactive chart sorting

---

## 📁 Repository Structure

```
UPI-Transaction-Data-Analysis/
├── UPI-Txn-Data-Analysis.pbix          # Main Power BI file (open with Power BI Desktop)
├── UPI-Txn-Data-Analysis.pdf           # Report export with all dashboards
├── screenshots/                         # Dashboard preview images
│   ├── 01-monthly-trends.png
│   ├── 02-city-wise-analysis.png
│   ├── 03-payment-methods.png
│   ├── 04-demographic-insights.png
│   ├── 05-device-type-breakdown.png
│   └── 06-merchant-analysis.png
└── README.md                           # This file
```

---

## 🚀 How to Use This Project

### **Option 1: Explore Interactive Dashboard (Recommended)**
1. Visit the **[Live Power BI Dashboard](https://app.powerbi.com/links/AXtyxy0ZMA?ctid=886abe6e-5df5-4218-aa37-00e1df3c3234&pbi_source=linkShare&bookmarkGuid=9f7508d9-bd42-4046-ad2e-fba8ed97ffbc)**
2. Use the **synchronized slicers** on the left to filter data
3. Click on **bookmarks** at the top to switch between pre-filtered views
4. Hover over charts to see exact values
5. Click and drag to zoom into specific periods

### **Option 2: Download & Open in Power BI Desktop**
1. Download the `.pbix` file from GitHub
2. Open with **Microsoft Power BI Desktop**
3. Explore bookmarks by clicking them at the top
4. Modify visualizations, filters, or data connections
5. Refresh data to get latest transactions

### **Option 3: View Static PDF Report**
1. Download `UPI-Txn-Data-Analysis.pdf`
2. Open in any PDF reader
3. View snapshot of all dashboards
4. Perfect for presentations or sharing

---

## 📌 How Slicers & Bookmarks Work Together

### **Manual Filtering with Slicers:**
1. **Select a City** (e.g., Delhi)
   → All charts update to show only Delhi transactions

2. **Choose Device Type** (e.g., Mobile)
   → Combined filter: Delhi + Mobile transactions

3. **Filter by Age Group** (e.g., 25-35)
   → Further refined: Delhi + Mobile + Age 25-35

4. **Add Payment Method** (e.g., UPI)
   → Final view: Delhi + Mobile + Age 25-35 + UPI

**Reset:** Click "Clear All" to reset all slicers

---

### **Quick Switching with Bookmarks:**

Instead of manually selecting slicers each time, just click a bookmark:

1. **Click "Delhi Focus" bookmark**
   → Instantly shows Delhi filtered view (replaces manual slicer selection)

2. **Click "Mobile Payments" bookmark**
   → Instantly shows only mobile transactions

3. **Click "Overall View" bookmark**
   → Instantly shows all data with no filters

This saves time and creates a **guided user experience**.

---

## 🎓 Advanced Features Explained

### **Bookmarks (View Switching)**

**What it does:** Saves a "snapshot" of filter settings so you can switch between views with one click.

**Example:**
- User clicks "Delhi Focus" bookmark → Dashboard instantly applies City=Delhi filter
- Same as manually selecting Delhi in the City slicer, but done in one click

**Benefits:**
- Faster navigation
- Guided analysis paths
- Professional user experience
- Reduces manual filter adjustments

---

### **Synced Slicers**

All filters are connected and work together:
- **Independent Slicers:** Bank Name Sent & Received can be used separately
- **Dependent Slicers:** City, Device Type, Gender all affect transaction data
- **Multi-select:** Hold CTRL and click to select multiple values in any slicer

---

### **Drill-through Capabilities**

- Click on any bar in the chart
- Drill to detailed transaction view
- See merchant-level transactions
- Go back to summary with back button

---

## 💡 Business Use Cases

**For Finance Teams:**
- Monitor transaction volumes and trends
- Track account balances and liquidity
- Identify peak transaction periods
- Analyze payment method adoption

**For Product Managers:**
- Understand user device preferences
- Track payment method performance
- Identify geographic growth opportunities
- Monitor cross-border transaction capability

**For Data Analysts:**
- Deep dive into transaction patterns
- Analyze customer demographics
- Segment users by behavior
- Create predictive models

**For Executive Dashboards:**
- High-level KPI overview
- Geographic performance comparison
- Trend identification and forecasting
- Strategic planning insights

---

## 📊 Sample Questions You Can Answer

Using the interactive dashboard, you can instantly answer:

✅ "What was the transaction volume in Delhi during Q2?"
✅ "Which payment method is most popular among mobile users?"
✅ "How does age group affect transaction patterns?"
✅ "What's the trend for USD vs GBP transactions?"
✅ "Which merchants generate the highest transaction volume?"
✅ "How do account balances vary by city?"
✅ "What's the device type distribution across age groups?"

---

## 🔗 View the Interactive Dashboard

### **Live Dashboard:** [📊 Open in Power BI Service](https://app.powerbi.com/links/AXtyxy0ZMA?ctid=886abe6e-5df5-4218-aa37-00e1df3c3234&pbi_source=linkShare&bookmarkGuid=9f7508d9-bd42-4046-ad2e-fba8ed97ffbc)

**Features:**
- ✅ Fully interactive with real-time filtering
- ✅ Multiple synchronized slicers
- ✅ Saved bookmarks for quick view switching
- ✅ No login required for viewing
- ✅ Mobile-responsive design

---

## 📥 Project Resources

| Resource | Link | Purpose |
|----------|------|---------|
| **Live Dashboard** | [Power BI Service](https://app.powerbi.com/links/AXtyxy0ZMA?ctid=886abe6e-5df5-4218-aa37-00e1df3c3234&pbi_source=linkShare&bookmarkGuid=9f7508d9-bd42-4046-ad2e-fba8ed97ffbc) | Interactive exploration |
| **PBIX File** | Download from GitHub | Open in Power BI Desktop |
| **PDF Report** | Download from GitHub | View all dashboards statically |
| **Source Code** | This repository | Project documentation |

---

## 🎓 Skills Demonstrated

✅ **Interactive Dashboard Design** - Synchronized slicers and bookmarks for user experience  
✅ **Advanced Power BI Features** - Bookmarks for view switching, drill-through, multi-page reports  
✅ **Data Visualization** - Line charts, column charts, KPI cards  
✅ **UX/UI Thinking** - Intuitive navigation with bookmarks  
✅ **Business Intelligence** - Transaction analysis and financial insights  
✅ **DAX & Power Query** - Custom calculations and data modeling  
✅ **Multi-dimensional Analysis** - City, Device, Payment method breakdowns

---

## 🔍 Data Dictionary

| Column | Description | Sample Values |
|--------|-------------|---|
| **BankNameSent** | Source bank for transaction | HDFC, ICICI, Axis, SBI |
| **BankNameReceived** | Destination bank | HDFC, ICICI, Axis, SBI |
| **City** | Transaction location | Delhi, Hyderabad |
| **DeviceType** | Device used | Mobile, Web, ATM, Tablet |
| **Gender** | Customer gender | Male, Female |
| **Age Groups** | Age segmentation | 18-25, 25-35, 35-50, 50+ |
| **MerchantName** | Merchant identifier | Amazon, Flipkart, Uber, etc. |
| **PaymentMethod** | Payment type | UPI, Card, Net Banking, Wallet |
| **Purpose** | Transaction purpose | Shopping, Bills, Transfer, Investment |
| **TransactionType** | Type of transaction | Transfer, Payment, Withdrawal |
| **Amount** | Transaction amount | Numeric value |
| **Remaining Balance** | Account balance after transaction | Numeric value |
| **Currency** | Currency denomination | USD, GBP, INR |
| **Month** | Transaction month | Jan, Feb, Mar, etc. |

---

## 💡 Unique Features of This Dashboard

🌟 **Synchronized Slicer Network** - All 10 slicers work together seamlessly  
🌟 **Bookmark Navigation** - 6+ pre-saved views for quick switching between charts  
🌟 **Multi-chart Synchronization** - Line and column charts update together  
🌟 **Geographic Analysis** - City-by-city transaction breakdown  
🌟 **Temporal Trends** - Full year 2024 month-by-month analysis  
🌟 **Multi-currency Support** - USD, GBP analysis  

---

## 📞 Contact & Portfolio

This project is part of a comprehensive **Data Analytics Portfolio** demonstrating expertise in:
- Power BI advanced features (bookmarks for view switching, synchronized slicers, drill-through)
- Interactive dashboard design and UX
- Financial data analysis
- Multi-dimensional data exploration
- Real-world transaction analytics

**[View Full Portfolio](https://github.com/yourusername)** | **[LinkedIn](https://linkedin.com/in/yourusername)** | **[Email](mailto:your.email@example.com)**

---

## ⭐ About This Project

This project showcases advanced Power BI skills beyond basic charting:
- Real-world transaction data analysis
- Complex filter synchronization with bookmarks for quick switching
- User-friendly bookmark experience for guided analysis
- Professional dashboard design
- Business intelligence best practices

Perfect for roles requiring:
- Power BI Expert/Advanced User
- Data Analyst with BI focus
- Business Intelligence Developer
- Financial Data Analyst

---

## 🔄 Project Versions

| Version | Date | Updates |
|---------|------|---------|
| 1.0 | Nov 2025 | Initial dashboard release |
| | | - Monthly transaction trends |
| | | - 10 synchronized slicers |
| | | - 6 interactive bookmarks for view switching |
| | | - City-wise analysis |
| | | - Payment method breakdown |

---

## 📋 Checklist for Viewing

- [ ] Click on live Power BI dashboard link
- [ ] Try different slicers and see how data updates
- [ ] Click on bookmarks at the top to switch views
- [ ] Hover over charts to see exact values
- [ ] Download PBIX file to explore in Power BI Desktop
- [ ] View PDF for static snapshot
- [ ] Share link with recruiters/stakeholders

---

**Status:** ✅ Complete and Production-Ready  
**Last Updated:** November 2024  
**Best For:** Portfolio, Interviews, Freelance Projects
