# SQL-Analysis---Hospital-Nursing-Intervention-Pilot-Program-
Hospital Nursing Intervention Pilot Analysis A data-driven analysis to identify hospitals with high ICU/SICU bed volumes for a nursing intervention pilot, using SQL-based exploration and dimensional modeling.

# Overview

This project analyzes ICU and SICU bed capacities across hospitals in the ACME Integrated Delivery System to support leadership in selecting one or two pilot sites for a nursing intervention program. The intervention aims to improve patient outcomes by increasing nurse-to-patient ratios at hospitals with sufficient ICU/SICU bed volumes. The analysis uses SQL-based data exploration and modeling to identify top-performing hospitals based on key bed capacity metrics.

# Background

Higher nurse-to-patient ratios in critical care settings improve patient outcomes. However, implementing such an intervention is cost-effective only if hospitals have sufficient ICU and SICU capacity. This project evaluates licensed, staffed, and census bed volumes to determine the best candidates for the pilot program. The dataset consists of three tables:

business.csv (hospital information)

bed_type.csv (bed classification)

bed_fact.csv (bed count data)

# Tasks

Fact vs. Dimension Identification:

Identify dimension attributes in business.csv and bed_type.csv.

Determine fact variables in bed_fact.csv.

ICU/SICU Bed Analysis:

Extract hospitals with either ICU (bed_id = 4) OR SICU (bed_id = 15) beds.

Generate three Top 10 hospital lists:

By licensed beds

By census beds

By staffed beds

Insights for Leadership:

Analyze trends from Top 10 hospital lists.

Identify hospitals appearing on multiple lists as strong candidates.

Drill-Down Investigation:

Identify hospitals with both ICU and SICU beds.

Generate refined Top 10 lists based on combined ICU/SICU bed counts.

Final Recommendation:

Recommend one or two hospitals for the intervention pilot.

Justify selection based on data-driven insights.

This project delivers SQL-driven insights to support strategic decision-making in hospital staffing improvements.

