# San Francisco Restaurant Health Inspection Analysis

**Author:** Julian  
**Date:** June 2025  
**Data Source:** [San Francisco Open Data Portal](https://data.sfgov.org)

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

## 📊 Executive Summary

This analysis examines health inspection data from restaurants and food establishments in San Francisco to identify patterns in health code violations, risk categories, and compliance trends. The dataset contains **53,973 inspection records** across multiple years, revealing critical insights for public health officials, restaurant owners, and policymakers.

### Key Findings

1. **High-Risk Violation Patterns**: The most common high-risk violations relate to improper food storage temperatures and inadequate handwashing facilities
2. **Geographic Hotspots**: Certain ZIP codes show significantly higher violation rates, suggesting targeted intervention opportunities
3. **Temporal Trends**: Inspection volumes and violation patterns vary seasonally, with peaks during summer months
4. **Repeat Offenders**: A small subset of establishments account for a disproportionate number of high-risk violations
5. **Business Performance Trends**: Analysis reveals success stories (businesses improving 10+ points) and concerning declines requiring intervention

## 🎯 Business Impact

- **Public Health Officials**: Prioritize resources toward high-risk areas and establishments
- **Restaurant Owners**: Benchmark compliance against city averages and identify improvement areas
- **Policy Makers**: Design targeted intervention programs based on data-driven insights

## 📁 Repository Structure

```
.
├── SF_Public_Health_Analysis.ipynb    # Main analysis notebook
├── Sf_Public_Health.csv               # Dataset (if local)
├── README.md                          # This file
└── requirements.txt                   # Python dependencies
```

## 🚀 Getting Started

### Prerequisites

- Python 3.8 or higher
- Jupyter Notebook or JupyterLab
- Required libraries (see Installation)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/sf-health-inspection-analysis.git
cd sf-health-inspection-analysis
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

3. Launch Jupyter Notebook:
```bash
jupyter notebook SF_Public_Health_Analysis.ipynb
```

### Required Libraries

```python
pandas
numpy
matplotlib
seaborn
plotly
requests
```

## 📈 Analysis Overview

The notebook is organized into the following sections:

### 1. Setup & Data Import
- Library imports and configuration
- Data fetching from SF Open Data API
- Alternative local file loading

### 2. Data Overview & Quality Check
- Dataset structure and dimensions
- Data dictionary and schema
- Quality assessment and preprocessing

### 3. Exploratory Data Analysis
- Distribution of inspection scores
- Inspection type breakdown
- Initial pattern identification

### 4. Risk Category Analysis
- Overall risk distribution
- High-risk violations analysis
- Most common violation types

### 5. Geographic Analysis
- Violations by ZIP code
- Interactive geographic visualizations
- Hotspot identification

### 6. Temporal Trends
- Inspection volume over time
- Seasonal patterns
- Interactive time series analysis

### 7. Violation Deep Dive
- High-risk violation patterns by business
- Repeat offender analysis
- Violation clustering

### 8. Business Performance Trends
- Identifying improving and declining businesses
- Most improved/declined establishments
- Score distribution comparisons
- Individual business time series
- Interactive performance tracking

### 9. Key Insights & Recommendations
- Summary of findings
- Actionable recommendations for stakeholders

## 🔍 Key Insights

### 1. High-Risk Violation Concentration
- A small number of establishments account for a disproportionate share of high-risk violations
- Critical violations include:
  - Improper food temperature control
  - Inadequate handwashing facilities
  - Cross-contamination risks
  - Pest control issues

### 2. Geographic Patterns
- Certain ZIP codes show significantly higher violation rates
- High-density commercial areas have more inspections and violations
- Geographic clustering suggests opportunities for targeted interventions

### 3. Temporal Trends
- Inspection volume varies seasonally with peaks in summer months
- High-risk violations show consistent patterns across years
- Weekend/holiday periods may correlate with violation spikes

### 4. Risk Distribution
- Majority of inspections result in low to moderate risk findings
- High-risk violations represent a critical subset requiring immediate attention
- Repeat offenders need focused compliance support

### 5. Business Performance Dynamics
- Some businesses show remarkable improvement (10+ point increases)
- Others exhibit concerning declines that warrant immediate investigation
- Most businesses maintain stable performance over time
- Success stories can serve as models for struggling establishments

## 💡 Recommendations

### For Public Health Officials

1. **Targeted Intervention Programs**
   - Focus resources on high-violation ZIP codes
   - Implement proactive support programs for repeat offenders
   - Increase inspection frequency for high-risk establishments

2. **Predictive Compliance**
   - Use temporal patterns to optimize inspection scheduling
   - Deploy resources during peak violation periods
   - Develop early warning systems for declining businesses

3. **Best Practice Sharing**
   - Study improved businesses to identify success factors
   - Create case studies from high-performing establishments
   - Develop mentorship programs pairing successful and struggling businesses

### For Restaurant Owners

1. **Proactive Compliance**
   - Regular self-audits using common violation checklists
   - Staff training on food safety protocols
   - Investment in proper equipment and facilities

2. **Benchmarking**
   - Compare performance against city averages
   - Learn from high-performing establishments
   - Monitor improvement trends over time

3. **Early Intervention**
   - Address violations immediately rather than waiting for next inspection
   - Seek guidance from health inspectors before issues escalate
   - Implement corrective actions with documented procedures

## 📊 Data Source

This analysis uses publicly available data from the [San Francisco Open Data Portal](https://data.sfgov.org/Health-and-Social-Services/Restaurant-Scores-LIVES-Standard/pyih-qa8i). The dataset is updated regularly and contains:

- Business information (name, address, location)
- Inspection details (date, type, score)
- Violation descriptions and risk categories
- Geographical coordinates for mapping

## 🛠️ Technologies Used

- **Python**: Primary programming language
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computing
- **Matplotlib & Seaborn**: Static visualizations
- **Plotly**: Interactive visualizations
- **Jupyter Notebook**: Development environment

## 📝 Future Enhancements

- Machine learning models to predict inspection outcomes
- Real-time dashboard for monitoring compliance trends
- Automated alert system for declining business performance
- Integration with additional datasets (e.g., Yelp reviews, demographics)
- Sentiment analysis of inspection violation descriptions

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.


## 🙏 Acknowledgments

- San Francisco Department of Public Health for providing open data
- SF Open Data Portal for data accessibility
- The data science community for various analytical techniques and visualizations

---

**Note**: This is an independent analysis for educational and informational purposes. Always refer to official San Francisco health inspection records for the most current and authoritative information.
