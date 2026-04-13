

Final Report

1. Overview and Synthesis
This final report brings together our initial exploratory analysis, advanced visualizations, and dashboarding efforts to provide a complete picture of the London Fire Brigade Response Time project. Through this work, we aimed to determine whether the emergency response times consistently meet the established KPIs (6 minutes for the first pump and 8 minutes for the second pump) and to highlight any operational delays. Our findings are intended to inform potential process improvements and serve as a foundation for adapting similar analyses to other regions.
2. Conclusion and Key Findings
After consolidating and rigorously cleaning the incident data (spanning 2009–2025) and the mobilisation data (organized into multiple files covering various periods), we developed a series of visualizations and an interactive Power BI dashboard. Our analysis yielded key insights:
- Response Time Analysis:
Calculation of response times revealed that while a majority of incidents fall within the required thresholds, a notable subset consistently exceeds them. This pattern suggests that specific periods or regions may benefit from further operational attention.
- Temporal and Geographical Patterns:
The histogram of incident call hours, box plots of response times, and geospatial heatmaps underscored distinct temporal clusters and geographic areas with higher delays. Seasonal variations and peak incident hours were identifiable, allowing for targeted resource planning.
- Operational Effectiveness:
The scatter plot comparing individual incidents with their KPI status provided a granular view of performance. This visualization highlighted instances of both exemplary and suboptimal performance, which are critical for in-depth diagnostic analysis.
Overall, the project successfully demonstrates that data analytics can shed meaningful light on operational processes and guide strategic decisions for emergency service enhancements.
3. Challenges and Lessons Learned
3.1 Difficulties Encountered
During the project, we faced several challenges:
- Data Heterogeneity:
Managing two separate incident files and four mobilisation files required extensive consolidation efforts. The diversity in data formats and time ranges necessitated meticulous standardization of date, time, and numeric fields.
- Data Cleaning Complexity:
Handling missing values, duplicate records, and inconsistencies across large datasets posed a significant challenge. Converting all temporal data into unified datetime objects and ensuring numerically precise response time calculations demanded rigorous pre-processing.
- Technical Hurdles:
Implementing data transformations and feature engineering in Python (using Google Colab) required careful optimization of our code to manage large volumes of data efficiently. Integrating these pre-processed datasets seamlessly into Power BI for visualization also required fine-tuning for performance.
3.2 Lessons Learned
- Importance of Data Preparation:
- Iterative Visualization Refinement:
The process of iteratively refining our visualizations helped clarify insights and enabled us to present our findings in a way that supports decision-making. Interactivity and attention to detail in dashboard design were key to enhancing user experience.
4. Main Contributions to Achieving Project Goals
- Data Consolidation and Cleaning:
We successfully merged disparate datasets and implemented robust cleaning routines, ensuring our analysis was based on a reliable and comprehensive dataset.
- Feature Engineering:
By deriving new metrics (e.g., response times and KPI flags), we were able to distill complex data into actionable insights.
- Advanced Visualizations and Dashboarding:
Designing an interactive, multi-tab Power BI dashboard allowed us to visually articulate both high-level trends and detailed incident-level performance. This dual approach was critical for effectively communicating our findings.
- Analytical Rigor:
Our use of multiple graph types—from histograms and box plots to scatter plots and heatmaps—provided a multifaceted view of the data, confirming or challenging our initial hypotheses.
5. Benchmark Comparison and Operational Implications
- KPI Adherence:
By comparing our computed response times against the LFB benchmarks (6 minutes for the first pump and 8 minutes for the second pump), we identified areas where performance was satisfactory and where delays persist. This comparison provides a quantitative basis for recommending targeted operational reviews.
- Strategic Resource Allocation:
Our geographical and temporal analyses offer critical insights for resource redistribution and schedule adjustments. Areas or times with higher delays were clearly identified, suggesting focal points for performance improvement initiatives.
6. Future Directions and Recommendations
Based on our findings, we propose several avenues for further investigation and project enhancement:
- Integration of Additional Data Sources:
Future work could benefit from additional operational data (e.g., weather conditions, incident severity, staffing levels) to understand factors affecting response times even more deeply.
- Predictive Analytics:
Developing predictive models to forecast response time variations based on historical trends might allow the fire service to proactively manage resources.
- Enhanced Dashboard Features:
Continued refinement of the Power BI dashboard—such as incorporating automated alerts for KPI breaches or integrating real-time data feeds—could further support decision-makers.
- Transferability to Other Regions:
Adapting and applying our methodological framework to other cities, including our hometown, would test its robustness and add value by broadening its impact.
7. Bibliography
Our analysis was supported by:
- Research articles on emergency response analytics.
- Online documentation and best practices for Python data processing (Pandas, NumPy).
- Microsoft’s Power BI resources and data visualization guidelines.
- Technical blogs and industry reports on data-driven decision-making in public safety.
(Note: Please ensure to formalize the bibliography with complete citations and URLs as per your institution's guidelines.)
8. Appendices
Appendix A: Code Files and Documentation
- Data Cleaning and Consolidation Scripts:
Detailed Python scripts (executed in Google Colab) that performed the following:
- Merging incident files (2009–2017 and 2018–2025).
- Consolidating the four mobilisation files.
- Standardizing datetime fields and converting numerical values.
- Feature Engineering Scripts:
Code segments calculating response times and generating KPI flags.
- Visualization Code:
Scripts used to generate the five key visualizations during our exploration phase.
- Power BI Dashboard Files:
A summary of the Power BI project files, including the data model and the design of interactive visualizations and filters.

We believe this final report encapsulates the depth and breadth of our project efforts, highlighting both our analytical outcomes and the critical areas for future improvement. It provides a solid foundation demonstrating our capability to transform raw data into actionable insights in the context of emergency service operations.


