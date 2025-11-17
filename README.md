# Smart City Analytics Dashboard

<img width="952" height="539" alt="Screenshot 2025-11-17 084627" src="https://github.com/user-attachments/assets/2bc6503c-d7ac-433e-bf63-74e692eb4ad3" />

## 📊 Project Overview

The Smart City Analytics Dashboard is a comprehensive Power BI solution that transforms multi-domain urban data into actionable intelligence for city planning and management. This project integrates traffic, public transport, energy consumption, air quality, and citizen feedback data to provide a 360-degree view of urban operations.

## 🎯 Key Objectives

- **Integrate** multiple urban datasets into a unified data model
- **Clean, validate, and standardize** data using Power Query and advanced data management techniques
- **Develop analytical measures** for performance scoring, anomaly detection, and forecasting
- **Provide actionable visualizations** for data-driven decision making
- **Support strategic urban management** through comprehensive performance metrics

## 📈 Dataset Architecture

### Core Data Domains
- **Traffic Data**: Vehicle count, average speed, accidents, congestion levels
- **Public Transport**: Passenger flow, satisfaction ratings, service delays
- **Energy Consumption**: Residential, commercial, industrial, and renewable usage
- **Air Quality**: PM2.5, PM10, O3 readings
- **Citizen Feedback**: Public complaints, satisfaction scores, service categories

### Data Modeling
- **Star Schema Design** with central Date and District dimension tables
- **5 Fact Tables** covering all urban domains
- **Advanced Data Cleaning** with Power Query transformations
- **Data Validation Rules** and outlier detection

## 🚀 Advanced Features

### Composite Performance Indices
- **District Performance Score**: Unified metric combining traffic, transport, energy, and environmental factors
- **Traffic Efficiency Index**: Balances volume, safety, and mobility factors
- **Anomaly Detection System**: Z-score analysis with 95% statistical significance

### Predictive Analytics
- **7-day traffic forecasting** using exponential smoothing
- **Early warning system** for developing urban trends
- **Root cause analysis** across multiple domains

### Interactive Visualization
- **Drill-through intelligence** layers for detailed analysis
- **Heat maps** for spatial pattern recognition
- **Conditional formatting** with traffic light indicators
- **Cross-filtering** across all visualizations

## 💡 Technical Implementation

### Tools & Technologies
- **Power BI Desktop** for dashboard development
- **Power Query** for ETL processes
- **DAX** for advanced calculations and measures
- **Star Schema** for data modeling
- **Conditional Formatting** for visual analytics

### Key DAX Measures
```dax
District Performance =
VAR TrafficScore = 100 - ([Total Accidents] * 10)
VAR TransportScore = [Avg Satisfaction] * 20
VAR EnergyScore = [Sustainability Score]
VAR AirScore = 100 - ([Avg PM2.5] * 2)
RETURN (TrafficScore + TransportScore + EnergyScore + AirScore) / 4
```

## 📊 Dashboard Features

### Main Views
1. **Executive Overview**: High-level KPIs and performance scores
2. **Traffic Analytics**: Congestion patterns and efficiency metrics
3. **Environmental Monitoring**: Air quality trends and pollution analysis
4. **Energy Management**: Consumption patterns and sustainability tracking
5. **Citizen Engagement**: Feedback analysis and satisfaction trends

### Interactive Capabilities
- **Drill-through pages** for detailed investigation
- **Cross-filtering** between related metrics
- **Time intelligence** for trend analysis
- **Geographic analysis** by district

## 🏆 Business Impact

### Expected Outcomes
- **Economic**: $15M annual savings from reduced congestion
- **Environmental**: 12% decrease in transportation emissions
- **Social**: 30% improvement in citizen service perception
- **Operational**: 8% reduction in peak energy demand costs

### Strategic Benefits
- **Proactive urban management** through predictive insights
- **Cross-department coordination** with unified data
- **Evidence-based decision making** with comprehensive analytics
- **Continuous improvement** through performance monitoring

## 🔧 Implementation Framework

### Phased Approach
- **Immediate (0-3 months)**: Traffic optimization and transport enhancements
- **Medium-term (3-12 months)**: Energy infrastructure modernization
- **Long-term (1-3 years)**: Integrated urban management platform

## 🎓 Learning Outcomes

### Technical Skills Developed
- **Advanced DAX** for complex business logic
- **Power Query** for robust data transformation
- **Data Modeling** with star schema architecture
- **Statistical Analysis** for anomaly detection
- **User Experience Design** for intuitive navigation

### Professional Competencies
- **Cross-domain integration** of urban systems
- **Stakeholder requirement analysis**
- **Project documentation** and technical reporting
- **Problem-solving** for data quality challenges

## 📁 Project Structure
```
Smart-City-Analytics/
├── README.md
├── Report.docx
├── media/
│   ├── image1.png
│   ├── image2.png
│   ├── image3.png
│   ├── image4.png
│   └── image5.png
└── datasets/
    ├── traffic_data.csv
    ├── transport_usage.csv
    ├── energy_consumption.csv
    ├── air_quality.csv
    └── citizen_feedback.csv
```


