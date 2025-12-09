# Hotel Acme Sands - Executive Operations Report

## Project Overview

This project analyzes 17 months of housekeeping operations data for Hotel Acme Sands to 
identify productivity patterns, operational efficiency issues, and potential fraud 
requiring management attention. The analysis focuses on room cleaning operations 
across three shifts (Day, Swing, Night) and provides actionable recommendations 
for operational improvements.

## Business Problem

Hotel Acme Sands management needed to:
- Identify productivity patterns across different shifts
- Detect potentially fraudulent activity (impossible productivity claims)
- Assess employee performance and training needs
- Understand seasonal activity patterns for staffing optimization
- Provide data-driven recommendations for operational efficiency

## Data Source

**Dataset:** Hotel Acme Sands internal housekeeping operations data
- **Time Period:** April 2024 - November 2025 (17 months)
- **Records:** 500+ workflow entries covering 69 room cleaning sessions
- **Employees:** 250 total employees analyzed
- **Files:**
  - `users.csv` - Employee information (ID, name, contact details, location)
  - `workflow_log.csv` - Operations log (employee ID, action, shift, rooms cleaned, date, status)

## Key Findings

### Critical Issues Identified

1. **Fraud Detection:** 3 employees flagged for impossible productivity claims
   - Claims of 60+ rooms cleaned per 8-hour shift (industry standard: maximum 48-60 rooms)
   - Requires immediate investigation and verification

2. **Training Needs:** 43 employees (81% of workforce) require additional training support
   - Completion rates below 70% threshold
   - Significant opportunity for productivity improvement through targeted training

3. **Shift Performance:** Day shift shows highest productivity (24.6 rooms/session average)
   - Night and Swing shifts average 20-21 rooms/session
   - Operational oversight needed to maintain consistency

### Operational Insights

- **Seasonal Patterns:** Activity variance of up to 40% between peak and low months
- **Staffing Balance:** Work evenly distributed across all three shifts
- **Performance Distribution:** Clear segmentation into high performers, average workers, 
	and those needing training

## Methodology

This analysis follows the **PACE framework** (Plan, Analyze, Construct, Execute):

1. **Plan:** Define business objectives and data requirements
2. **Analyze:** Exploratory data analysis to identify patterns and anomalies
3. **Construct:** Build visualizations and statistical analysis
4. **Execute:** Deliver actionable insights and recommendations

For detailed methodology, see [PACE_Strategy.md](documentation/PACE_Strategy.md)

## Technology Stack

- **Python 3.x**
- **pandas** - Data manipulation and analysis
- **matplotlib** - Data visualization
- **numpy** - Numerical computations
- **Jupyter Notebook** - Interactive development and reporting

## Visualizations

The project includes four comprehensive visualizations:

1. **Fraud Detection Chart** - Identifies employees with impossible productivity claims
2. **Seasonal Activity Patterns** - Monthly room cleaning volume trends
3. **Workforce Performance Distribution** - Employee completion rate segmentation
4. **Shift Performance & Risk Analysis** - Comparative analysis across shifts

All visualizations use CVD-friendly (colorblind-accessible) color palettes following 
accessibility best practices.

## Project Structure

```
hotel-acme-sands/
├── documentation/
│   ├── Executive_Summary.md
│   └── PACE_Strategy.md
│   └── PACE_Framework.md 
├── notebook/
│   └── Hotel_Acme_Sands_Executive_Report.ipynb
├── data/
│   ├── users.csv
│   └── workflow_log.csv
├── visualizations/
│   └── executive_dashboard_summary.png
├── README.md

```

## Installation and Usage

### Prerequisites
```bash
Python 3.8+
pandas
matplotlib
numpy
jupyter
```

### Setup
```bash
# Clone the repository
git clone [repository-url]

# Navigate to project directory
cd hotel-acme-sands

# Install required packages
pip install pandas matplotlib numpy jupyter

# Launch Jupyter Notebook
jupyter notebook
```

### Running the Analysis
1. Open `notebook/Hotel_Acme_Sands_Executive_Report.ipynb`
2. Run all cells sequentially (Cell > Run All)
3. Review generated visualizations and statistics
4. Generated dashboard saved to `visualizations/executive_dashboard_summary.png`

## Key Recommendations

### Immediate Actions (High Priority)

1. **Fraud Investigation**
   - Coordinate with HR for formal investigation of 3 flagged employees
   - Review room assignment logs and security footage for verification
   - Implement enhanced verification procedures

2. **Training Program Implementation**
   - Develop comprehensive training for 43 employees with <70% completion rates
   - Estimated investment: $25,000-40,000
   - Expected productivity gains: 15-25%

3. **Day Shift Oversight Enhancement**
   - Implement additional quality control measures
   - Supervisor training for fraud detection
   - Regular audit procedures

### Strategic Improvements (Medium Priority)

4. **Seasonal Staffing Optimization**
   - Hire seasonal staff for peak activity months
   - Plan maintenance during low activity periods
   - Budget for 40% capacity fluctuation

5. **Policy Review**
   - Update reporting standards and verification procedures
   - Enhance staff training on accurate productivity reporting
   - Implement quarterly performance reviews

## Expected Impact

- **Fraud Prevention Savings:** $20,000-40,000 annually
- **Training Investment:** $25,000-40,000 (one-time)
- **Productivity Gains:** 15-25% improvement expected
- **Operational Efficiency:** Enhanced oversight and reduced risk

## Accessibility

This project follows strict accessibility standards:
- **CVD-Compliant Visualizations:** All charts use colorblind-friendly palettes
- **Clear Color Meanings:** Consistent color usage across all visualizations
- **Professional Formatting:** Clean, readable documentation and code

## Acknowledgments

This project was completed as part of demonstrating practical application of data 
analysis techniques to real-world operational challenges.

## License

This project is for portfolio demonstration purposes.

## Contact

For questions or collaboration opportunities, please connect via:
- GitHub: billmarmcswss
- LinkedIn: linkedin.com/in/william-matthews-65a071232
- Email: billmarmc@gmail.com

---

**Note:** This analysis uses simulated hotel operations data for demonstration purposes. 
All employee names and identifying information are fictional.
