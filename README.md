# Personal Loan Analytics Dashboard

A comprehensive analytics dashboard for personal loan data analysis and visualization, built with Power BI and supported by detailed CSV datasets.

## 📊 Project Overview

This project provides an interactive dashboard for analyzing personal loan data, helping financial institutions and analysts understand customer behavior, loan patterns, and risk factors. The dashboard offers insights into loan approval trends, customer demographics, and financial indicators.

## 🗂️ Project Structure

```
Personal-Loan-Analytics-Dashboard/
├── Bank_Personal_Loan_Modelling.csv    # Main dataset with 5,000+ records
├── finalexcel.xlsx                     # Processed Excel data
├── Personal Loan Analytics Dashboard.pbix  # Power BI dashboard file
└── README.md                           # Project documentation
```

## 📈 Dataset Description

### Bank Personal Loan Modelling Dataset
The primary dataset contains **5,001 records** with the following key features:

| Column | Description | Data Type | Values |
|--------|-------------|-----------|---------|
| **ID** | Unique identifier | Integer | Sequential (1-5001) |
| **Age** | Customer age | Integer | 25-67 years |
| **Experience** | Years of work experience | Integer | -1 to 41 years |
| **Income** | Annual income (in thousands) | Integer | 8-224 thousand |
| **ZIP Code** | Customer ZIP code | Integer | 5-digit codes |
| **Family** | Family size | Integer | 1-4 members |
| **CCAvg** | Average credit card spending | Float | 0.0-10.0 |
| **Education** | Education level | Integer | 1=Undergrad, 2=Graduate, 3=Advanced |
| **Mortgage** | Mortgage value | Integer | 0-635 thousand |
| **Personal Loan** | Loan acceptance (Target) | Binary | 0=No, 1=Yes |
| **Securities Account** | Has securities account | Binary | 0=No, 1=Yes |
| **CD Account** | Has CD account | Binary | 0=No, 1=Yes |
| **Online** | Uses online banking | Binary | 0=No, 1=Yes |
| **CreditCard** | Has credit card | Binary | 0=No, 1=Yes |

### Key Insights from Data
- **Loan Acceptance Rate**: Approximately 9.6% of customers accepted personal loans
- **Age Distribution**: Wide range from 25 to 67 years
- **Income Range**: $8,000 to $224,000 annually
- **Education Levels**: Three distinct categories with varying loan acceptance rates

## 🎯 Dashboard Features

### Power BI Dashboard (`Personal Loan Analytics Dashboard.pbix`)
The interactive dashboard provides:

- **Customer Demographics Analysis**
  - Age distribution and loan acceptance correlation
  - Income levels vs. loan approval rates
  - Education level impact on loan decisions

- **Financial Behavior Insights**
  - Credit card usage patterns
  - Mortgage vs. loan acceptance relationship
  - Securities and CD account ownership analysis

- **Geographic Analysis**
  - ZIP code-based loan distribution
  - Regional loan acceptance patterns

- **Interactive Visualizations**
  - Dynamic charts and graphs
  - Filterable data views
  - Drill-down capabilities

## 🚀 Getting Started

### Prerequisites
- **Power BI Desktop** (Free version available)
- **Microsoft Excel** or compatible spreadsheet software
- **Python** (optional, for data preprocessing)

### Installation & Setup

1. **Clone or Download the Repository**
   ```bash
   git clone https://github.com/yourusername/Personal-Loan-Analytics-Dashboard.git
   cd Personal-Loan-Analytics-Dashboard
   ```

2. **Open the Dashboard**
   - Install Power BI Desktop from [Microsoft's official website](https://powerbi.microsoft.com/desktop/)
   - Open `Personal Loan Analytics Dashboard.pbix` in Power BI Desktop
   - The dashboard will load with all visualizations and data connections

3. **Data Refresh** (if needed)
   - In Power BI, go to Home → Refresh
   - Ensure the CSV file path is correctly set
   - Update data source if file location changes

### Alternative: Excel Analysis
- Open `finalexcel.xlsx` for pre-processed data analysis
- Use Excel's built-in analytics tools and pivot tables
- Create custom visualizations as needed

## 📊 Usage Examples

### Basic Analysis
1. **Loan Acceptance by Age Group**
   - Filter dashboard by age ranges
   - Analyze loan approval rates across demographics

2. **Income vs. Loan Correlation**
   - Use scatter plots to visualize income vs. loan acceptance
   - Identify income thresholds for loan approval

3. **Geographic Patterns**
   - Map loan acceptance by ZIP codes
   - Identify high-performing regions

### Advanced Insights
- **Risk Assessment**: Analyze factors contributing to loan defaults
- **Customer Segmentation**: Group customers by behavior patterns
- **Predictive Modeling**: Use data for loan approval predictions

## 🔧 Customization

### Adding New Data Sources
1. Update the CSV file with new records
2. Refresh the Power BI dashboard
3. Modify visualizations as needed

### Creating New Visualizations
1. In Power BI, add new visual elements
2. Connect to relevant data fields
3. Customize formatting and interactions

## 📈 Business Applications

- **Loan Officers**: Quick customer assessment and risk evaluation
- **Risk Management**: Identify high-risk loan applications
- **Marketing Teams**: Target customers based on loan acceptance patterns
- **Executive Dashboards**: High-level loan portfolio overview

## 🤝 Contributing

Contributions are welcome! Please feel free to:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

### Areas for Improvement
- Additional data sources
- Enhanced visualizations
- Machine learning models
- API integrations

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 📞 Support

For questions or support:
- Create an issue in the GitHub repository
- Contact the development team
- Check Power BI documentation for technical issues

## 🔄 Version History

- **v1.0.0** - Initial dashboard with basic analytics
- **v1.1.0** - Enhanced visualizations and data processing
- **v1.2.0** - Added geographic analysis and customer segmentation

---

**Note**: This dashboard is designed for educational and analytical purposes. Always verify data accuracy and consult with financial experts before making business decisions based on the insights provided.
