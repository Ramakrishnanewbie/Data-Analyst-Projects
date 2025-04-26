# Presence Insights Dashboard

## Project Background

This Presence Insights Dashboard emerged from a hybrid work environment challenge. As organizations worldwide adapted to new work models combining in-person and remote work, our leadership team needed clear visibility into employee work patterns. Traditional attendance systems weren't designed for hybrid workforces, and managers lacked the tools to understand attendance trends, work-from-home patterns, and sick leave usage.

I developed this Power BI solution to transform raw attendance data into actionable workforce insights, enabling data-driven decisions about space planning, team scheduling, and employee well-being.

## Business Objectives

The Presence Insights Dashboard addresses several critical business questions:

- What is the overall employee presence rate across the organization?
- How prevalent is work-from-home (WFH) adoption among different teams?
- What patterns exist in sick leave (SL) usage?
- Are there day-of-week trends in office presence or remote work?
- Which employees might need additional support based on attendance patterns?
- How are attendance patterns changing over time?

## Data Sources & Structure

The dashboard analyzes attendance data that includes:
- Employee details (names, teams, roles)
- Daily attendance records
- Attendance type categorization (Present, WFH, SL, etc.)
- Time period information

## Power BI Techniques Applied

### Data Modeling
- Creation of a robust date dimension for time intelligence
- Star schema implementation with attendance facts and employee dimensions
- Calculated columns for attendance type categorization
- Measures for daily and aggregate presence metrics

### DAX Measures & Calculations
- Complex presence percentage calculations
- Running averages for trend analysis
- Time intelligence functions for period comparisons
- Conditional aggregations for attendance type analysis
- Employee-specific metrics with context transition

### Advanced Visualizations
- Line charts displaying presence percentage trends over time
- Employee detail tables with conditional formatting
- Day-of-week analysis using matrix visuals
- Custom tooltips providing additional context
- Visual hierarchies for drill-down capabilities

### Interactive Elements
- Month slicer for timeframe selection
- Employee filters for individual analysis
- Presence type toggle for specific attendance categories
- Bookmark navigation for different analytical perspectives
- Cross-filtering between visuals for coordinated analysis

## Key Dashboard Elements

### Summary Metrics
- **Overall Presence Rate**: 91.83% attendance across the organization
- **WFH Utilization**: 10.00% of workdays conducted remotely
- **Sick Leave Usage**: 1.10% of total workdays

### Trend Analysis
- **Presence % by Date**: Time-series visualization showing daily attendance patterns
- **WFH % by Date**: Daily work-from-home utilization over time
- **SL % by Date**: Sick leave patterns throughout the analyzed period

### Employee Details
- Individual presence percentages with comparative ranking
- Personal WFH utilization rates
- Sick leave patterns by employee
- Detailed attendance record with date and type

### Day of Week Analysis
- Presence percentages by weekday (Mon-Fri)
- WFH utilization patterns across different days of the week
- Sick leave frequency by day of the week

## Key Insights & Findings

The dashboard revealed several valuable workforce insights:

1. **Attendance Patterns**: Overall presence rates remain high (91.83%), but show distinct patterns with noticeable dips mid-week and month-end.

2. **Remote Work Adoption**: The 10% WFH rate varies significantly by employee, with some team members working remotely full-time while others rarely utilize this option.

3. **Day-of-Week Trends**: Fridays show the highest WFH utilization (13.01%) and lowest in-person presence (90.19%), suggesting employees prefer remote work before weekends.

4. **Individual Variations**: Significant differences exist in how employees utilize WFH options, with some consistently working remotely and others maintaining traditional in-office schedules.

5. **Time Period Patterns**: Attendance data shows cyclical patterns with predictable variations that can inform staffing and space planning.

## Business Value & Implementation Results

This dashboard delivers substantial business value through:

### Operational Improvements
- **Space Optimization**: Data-driven decisions about office space requirements based on actual utilization
- **Meeting Scheduling**: More effective meeting planning by understanding when teams are likely to be present
- **Resource Allocation**: Optimized resource distribution based on in-office headcount predictions

### Management Enhancements
- **Team Visibility**: Better understanding of team attendance patterns
- **Employee Support**: Early identification of attendance anomalies that might indicate employee challenges
- **Policy Effectiveness**: Data-driven evaluation of flexible work policies

### Strategic Benefits
- **Long-term Planning**: Trend data to support facilities and resource planning
- **Policy Development**: Insights to guide refinement of hybrid work policies
- **Cultural Assessment**: Understanding of how workplace flexibility is being utilized

## Technical Implementation

### Data Pipeline
- Automated data extraction from attendance systems
- Power Query transformations for data standardization
- Incremental refresh for efficient processing
- Row-level security implementation for data privacy

### Dashboard Development
- Custom theme implementation for consistent branding
- Mobile-optimized layout for on-the-go access
- Performance optimization for large datasets
- Tooltip enhancements for contextual information

## User Guide

The dashboard offers intuitive navigation through:
- Month selector for period-specific analysis
- Employee filters for individual focus
- Day-of-week breakdowns for pattern identification
- Trend visualizations for temporal analysis
- Detailed attendance records for specific inquiries

## Future Enhancements

Planned enhancements include:
- Integration with team performance metrics
- Correlation analysis with project timelines
- Advanced anomaly detection for attendance patterns
- Predictive modeling for attendance forecasting
- Expanded demographic analysis for policy development

This dashboard has transformed how our organization understands and manages its hybrid workforce, converting raw attendance data into actionable insights that drive better operational decisions and support employee flexibility.