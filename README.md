# 🚗 Car Sales Dashboard - Power BI Project

An interactive Car Sales Dashboard built in Power BI featuring advanced analytics and AI-powered insights using the Key Influencer visual.

## 📊 Project Overview

This project demonstrates a comprehensive sales analytics solution for the automotive industry, combining data modeling best practices with advanced AI-powered visualizations to uncover actionable business insights.

## 🎯 Key Features

### Dashboard Components
- **Revenue Tracking**: Monitor total sales revenue across multiple dimensions
- **Quantity Analysis**: Track sales volume and inventory movement
- **Profit Monitoring**: Analyze profitability trends and patterns
- **Dynamic Date Intelligence**: Full calendar table with 25 columns for comprehensive time-based analysis

### Data Model
- **Star Schema Design**: Optimized for query performance and ease of use
- **Multi-table Architecture**:
  - `Sales` (Fact Table): Transaction-level data with SaleID, Date, DealerID, ModelID, Quantity, TotalPrice, and Total Profit
  - `Dealers` (Dimension): Dealer information and locations
  - `Models` (Dimension): Car model specifications and details
  - `Calendar` (Dimension): Comprehensive date table for time intelligence

### Advanced Analytics

#### 🤖 Key Influencer Visual Implementation
The Key Influencer visual leverages AI to automatically analyze data and explain what drives changes in key metrics:

- **Revenue Drivers**: Identifies which factors most significantly impact revenue
- **Model Performance**: Analyzes how different car models affect overall sales
- **Dealer Insights**: Reveals dealer-wise performance patterns and anomalies
- **Seasonal Trends**: Uncovers temporal patterns influencing sales metrics

**Benefits**:
- Root cause analysis for sales variations
- Automatic identification of hidden patterns
- Data-driven recommendations for stakeholders
- Easy-to-understand visualizations for non-technical audiences

## 🛠️ Technical Implementation

### Data Model Architecture
```
Sales (Fact)
├── → Dealers (1:Many)
├── → Models (1:Many)
└── → Calendar (1:Many)
```

### Custom Measures
- **Revenue**: `SUM(Sales[TotalPrice])` - Total sales revenue
- **Quantity**: `SUM(Sales[Quantity])` - Total units sold
- **Profit**: `SUM(Sales[Total Profit])` - Total profitability

### Calendar Table Features
The custom Calendar table includes 25 columns for advanced time intelligence:
- Year, Quarter, Month hierarchies
- Week and day-level analysis
- Weekend/Weekday classification
- Month/Quarter/Year start and end dates
- Day of Week, Day of Month, Day of Year
- Proper sorting with MonthNum for correct chronological ordering

## 📈 Use Cases

1. **Sales Performance Analysis**: Track revenue, quantity, and profit trends over time
2. **Dealer Performance**: Compare sales performance across different dealerships
3. **Product Analytics**: Identify best-selling car models and understand demand patterns
4. **Predictive Insights**: Use Key Influencer to predict what drives future sales
5. **Seasonal Planning**: Leverage weekend/weekday and seasonal trends for inventory planning

## 🎓 Learning Outcomes

- Designed and implemented a star schema data model
- Created custom DAX measures for business metrics
- Built a comprehensive Calendar table with 25+ date intelligence columns
- Implemented AI-powered Key Influencer visual for advanced analytics
- Applied data modeling best practices (relationships, cardinality, filter direction)
- Developed interactive dashboards for stakeholder communication

## 📸 Dashboard Preview

*[Add screenshots of your dashboard here]*

## 🙏 Acknowledgments

Special thanks to **Satish** for providing excellent training and guidance on Power BI advanced features and best practices.

## 📫 Connect With Me

I'm actively seeking Data Analyst opportunities in Qatar or remote positions. If you're interested in my work or have opportunities available, let's connect!

**Skills**: Power BI | DAX | Data Modeling | Business Intelligence | Data Visualization | SQL | Advanced Analytics

---

## 📄 License

This project is available for educational and portfolio purposes.

## 🔗 Links

- [LinkedIn Profile](your-linkedin-url)
- [Portfolio](your-portfolio-url)
- [Email](your-email@example.com)
