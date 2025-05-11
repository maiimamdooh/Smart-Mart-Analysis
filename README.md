# Smart-Mart-Analysis

## 📌 Project Overview
Comprehensive analytics solution for Smart-Mart retail operations,using power query and power bi ,providing insights into:
- Sales performance across multiple dimensions
- Product return patterns and root cause analysis
- Customer segmentation by return behavior
- Temporal trends in sales and returns


## 📊 Key Metrics
- **Total Sales:** $4M
- **Total Profit:** $809K
- **Return Rate:** 19%
- **Avg Order Size:** 5 items
- **Total Orders:** 2K

## 🔍 Key Insights
### Sales Performance
- **Top Sales Rep:** Cristian Popescu ($847K sales)
- **Best Day:** Thursday ($0.6M sales)
- **Time Period:** Morning generates most sales ($950K)
- **Yearly Growth:** Consistent growth from 2022-2024

### Return Rate Analysis
- **Daily Patterns:** Higher returns on weekends 24% return rate vs. 18% weekdays
- **Time of Day:** Evening sees highest return rates 20% vs. 18% morning
- **Product Categories:** Electronics have highest return rate 36% , 2.3x higher than average
- **Customer Segments:** Identified high-return customers `Gabriel Petrescu 22% `, `Ion Popescu 21.5%`


## Strategic Recommendations

### **Immediate Actions (0-3 Months)**

#### 1- Product & Inventory
- Conduct quality audit on electronics (focus: TVs/cameras)
- Review product descriptions for accuracy
- Implement bundle limits (avoid 6-8 item combinations)

#### 2- Customer Experience
- Proactive outreach to top returners to understand pain points
- Enhance evening shift support staff

#### 3- Staff Training
- Replicate Cristian Popescu's sales techniques across team


### **Medium-Term Initiatives (3-6 Months)**
- Implement "Frequently Returned" product alerts at POS
- Redesign packaging for most-returned items
- Develop weekend return prevention protocol

### **Analytics Enhancements**
- Build customer lifetime value model incorporating return costs
- Create return reason tracking system
- Develop "return risk score" for new orders

## Data Model

```mermaid
erDiagram
    CUSTOMERS ||--o{ ORDERS : "places"
    PRODUCTS ||--o{ ORDERS : "contains"
    SALES_REP ||--o{ ORDERS : "handles"
    REGIONS ||--o{ SALES_REP : "assigned_to"




