This project focuses on analyzing employee satisfaction, job roles, and attrition rates across different demographic categories using Tableau. 
Below is a step-by-step overview of each analytical component, with a specific focus on creating a custom donut chart for analyzing attrition rates by gender across age groups:

Department-wise Attrition Analysis-
Visualize department-wise attrition using a pie chart. Departments are placed in columns, and attrition counts are represented as segments within the pie chart. This helps understand attrition trends across organizational units.


Age Group Analysis-
Segment employees into age groups using Tableau's binning feature with adjustable bin sizes (min: 2, max: 10, step: 1). The distribution is displayed as a bar chart showing employee counts in each age category, offering insights into age diversity.


Job Satisfaction Rating-
Analyze job satisfaction ratings by job roles, displaying categorical values (e.g., "satisfied," "neutral," "dissatisfied") using text annotations. Grand totals summarize overall satisfaction levels across all roles.


Education Field-wise Attrition-
Display attrition rates categorized by education fields in a formatted visualization using a yellow color scheme without grid lines. This analysis helps identify attrition patterns based on employees' educational backgrounds.


Attrition Rate by Gender across Age Groups: Custom Donut Chart-
Visualize attrition rates by gender within different age groups using a custom donut chart for enhanced clarity and visual impact.
Start with a pie chart setup: Place "Age Band" in Columns and "Attrition Count" in Marks as a Pie Chart to show initial attrition counts by age groups.
Differentiate attrition rates by gender: Drag "Gender" to Color in the Marks card, assigning distinct colors for male and female attrition counts within the pie chart segments.
Create a dual-axis chart: Right-click on "Attrition Count" in the Marks shelf and select "Dual Axis" to overlay the pie chart with a second axis, forming the donut shape.
Adjust appearance: Format the second axis to reduce its size, creating the central hole characteristic of a donut chart for improved visual clarity.
Enhance sorting: Manually sort the age bands to arrange them sequentially for clearer presentation and comparative analysis.


Conclusion
This project provides comprehensive insights into employee satisfaction, job roles, and demographic factors influencing attrition. For detailed exploration, refer to the attached Tableau workbook, which includes visualizations and data insights. Additionally, a background color sheet is provided for better visualization clarity and aesthetic appeal.
