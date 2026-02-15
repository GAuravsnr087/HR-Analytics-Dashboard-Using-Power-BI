HR Analytics Dashboard 📊

![HR Analytics Dashboard](https://claude.ai/api/f9eefbbf-1464-4826-ab9f-4819d761b8ce/files/9b9540ae-072a-4b69-ac10-2a4a970b2297/preview)

## 🎯 Project Overview

This project presents an interactive HR Analytics Dashboard that provides comprehensive insights into employee data, attrition patterns, and workforce demographics. The dashboard enables HR professionals and business leaders to make data-driven decisions regarding employee retention, satisfaction, and organizational planning.

## 📈 Key Metrics & Features

### Dashboard Highlights

- **Overall Employees**: 1,480 total workforce
- **Attrition**: 238 employees (16.08% attrition rate)
- **Active Employees**: 1,242 employees
- **Average Age**: 37 years

### Visual Analytics

1. **Department-wise Attrition**
   - Research & Development: 133 employees (55.88%)
   - Sales: 93 employees (39.08%)
   - Human Resources: 12 employees (5.04%)

2. **Employee Demographics**
   - Age group distribution (18-25, 26-35, 36-45, 46-55, 55+)
   - Gender-wise employee count
   - Distribution across departments

3. **Job Satisfaction Ratings**
   - Analysis across different job roles
   - Rating scale from 1 to 4
   - Role-specific satisfaction trends

4. **Education Field-wise Attrition**
   - Life Sciences: 89 employees
   - Medical: 63 employees
   - Marketing: 36 employees
   - Technical Degree: 32 employees
   - Other: 11 employees
   - Human Resources: 7 employees

5. **Age Group Attrition Analysis**
   - Detailed breakdown by age groups (Under 25, 26-35, 36-45, 46-55, Above 55)
   - Gender distribution within each age group
   - Percentage-wise attrition rates

## 🗂️ Dataset Information

### Data Source
- **File**: `HR_Analytics.xlsx`
- **Total Records**: 1,480 employees
- **Total Attributes**: 38 columns

### Key Attributes

| Category | Attributes |
|----------|-----------|
| **Employee Info** | EmpID, Age, AgeGroup, Gender, MaritalStatus, Education, EducationField |
| **Job Details** | Department, JobRole, JobLevel, JobSatisfaction, JobInvolvement |
| **Compensation** | MonthlyIncome, SalarySlab, DailyRate, HourlyRate, MonthlyRate, PercentSalaryHike |
| **Work Metrics** | TotalWorkingYears, YearsAtCompany, YearsInCurrentRole, YearsSinceLastPromotion, YearsWithCurrManager |
| **Satisfaction** | EnvironmentSatisfaction, JobSatisfaction, RelationshipSatisfaction, WorkLifeBalance |
| **Attrition** | Attrition, BusinessTravel, OverTime, DistanceFromHome |
| **Performance** | PerformanceRating, TrainingTimesLastYear, StockOptionLevel |

## 🛠️ Tools & Technologies

- **BI Tool**: Power BI / Tableau (specify your tool)
- **Data Source**: Microsoft Excel
- **Data Processing**: Power Query / Excel
- **Visualization**: Interactive dashboards with filters and drill-through capabilities

## 📊 Dashboard Features

### Interactive Elements
- **Department Filters**: Human Resources, Life Sciences, Marketing, Medical, Technical Degree
- **Dynamic KPI Cards**: Real-time metrics for key HR indicators
- **Drill-through Analysis**: Click through charts to explore detailed data
- **Age Group Segmentation**: Analyze patterns across different age demographics
- **Gender-based Analysis**: Compare attrition and distribution by gender

### Key Insights

1. **High Attrition in R&D**: Research & Development shows the highest attrition with 133 employees leaving
2. **Critical Age Group**: The 26-35 age group has the highest attrition count (116 employees)
3. **Job Role Analysis**: Laboratory Technicians (261 total) and Research Scientists (293 total) form significant portions of the workforce
4. **Education Impact**: Life Sciences background shows the highest attrition rate
5. **Gender Distribution**: Visible gender disparities across different age groups and roles

## 🚀 How to Use

### Prerequisites
- Power BI Desktop (or relevant BI tool)
- Microsoft Excel (to view source data)

### Steps to Run
1. Clone this repository
   ```bash
   git clone https://github.com/yourusername/hr-analytics-dashboard.git
   ```
2. Open the `.pbix` file (or relevant dashboard file) in Power BI Desktop
3. Refresh the data source if needed
4. Explore the interactive dashboard

### File Structure
```
hr-analytics-dashboard/
│
├── HR_Analytics.xlsx          # Source dataset
├── dashboard_preview.png      # Dashboard screenshot
├── HR_Dashboard.pbix          # Power BI dashboard file
└── README.md                  # Project documentation
```

## 📌 Key Findings & Recommendations

### Critical Insights
- **16.08% Attrition Rate**: Above industry average, requires immediate attention
- **R&D Department**: Focus on retention strategies for this critical department
- **Young Professionals**: 26-35 age group shows highest attrition - consider career development programs
- **Job Satisfaction**: Varies significantly across roles - targeted interventions needed

### Recommended Actions
1. Implement retention programs for R&D department
2. Develop career progression pathways for 26-35 age group
3. Conduct satisfaction surveys for roles with low ratings
4. Review compensation and benefits for high-attrition roles
5. Enhance work-life balance initiatives

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📧 Contact

Name - Gaurav Sonar - grvsnr087@gmail.com

## 🙏 Acknowledgments

- Dataset source: KAGGLE.COM
- Inspired by real-world HR analytics challenges
- Built for HR professionals and data enthusiasts

---

⭐ If you found this project helpful, please give it a star!

**Note**: This dashboard is created for educational and analytical purposes. Ensure compliance with data privacy regulations when using real employee data.
