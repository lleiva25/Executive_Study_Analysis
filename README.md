# Executive Study Analysis
----------------------------------------------------------------------------------------------
Background
----------------------------------------------------------------------------------------------
Biotechnology companies are at the forefront of innovation, striving to extend human longevity through cutting-edge assays designed to detect early-onset diseases and offer accessible alternative therapy treatments. A key breakthrough lies in the extraction of cell-free DNA (cfDNA) from whole blood, achieved through the isolation of plasma. This extracted cfDNA is then guided through a meticulous assay workflow, ultimately leading to advanced sequencing processes.

This process not only highlights the industry's commitment to early detection but also underscores the significance of leveraging cfDNA as a valuable resource in the pursuit of groundbreaking medical solutions. The journey from plasma isolation to cfDNA extraction and sequencing showcases the intricate steps involved in revolutionizing healthcare for the common person.

In the realm of studies focused on acquiring these valuable samples, biotechnology companies engage in collaborative efforts with clinical sites. This strategic coordination aims to identify and enlist patients who meet specific criteria outlined by each unique study. A pivotal stage in this process is Accessioning, where collected samples are sent to the lab for meticulous examination.

Accessioning serves as a critical checkpoint in the workflow, empowering lab operators to thoroughly inspect the samples. This inspection ensures strict adherence to the predefined criteria set by the study. Any deviations discovered during this stage are promptly reported, allowing for corrective measures before the samples proceed further down the workflow. This meticulous approach not only upholds the integrity of the study but also contributes to the overall reliability of the acquired data, paving the way for more robust scientific insights.

----------------------------------------------------------------------------------------------
Purpose
----------------------------------------------------------------------------------------------
The primary objective of this analysis is multifaceted, encompassing key parameters to ensure comprehensive monitoring and quality control in the sample processing workflow:

- Total Samples per Site: Tracking the cumulative number of samples received from each clinical site provides a holistic overview of the study's scope and distribution.

- Samples per Quarter: Categorizing samples based on quarters offers a temporal perspective, enabling the identification of trends, patterns, and potential seasonality in sample submissions.

- Daily Average of Samples Received: Calculating the daily average provides a real-time metric, offering insights into the operational efficiency and workload distribution over time.

- Temperature Trackers: Implementing diverse temperature trackers allows for the meticulous monitoring of sample storage conditions. This ensures the preservation of sample integrity and reliability.

- Sample Deviation Analysis per Site: Conducting a thorough analysis of sample deviations at each clinical site identifies potential anomalies or discrepancies, facilitating prompt corrective actions.

- Sample Deviation Percentage Rate per Site: Expressing sample deviations as a percentage of the total samples per site provides a standardized metric, aiding in the comparison of site-specific adherence to criteria.

By addressing these facets, the analysis not only ensures the systematic management of samples but also establishes a robust framework for quality assurance, data integrity, and procedural optimization throughout the study.


----------------------------------------------------------------------------------------------
Workflow Diagram
----------------------------------------------------------------------------------------------

![image](https://github.com/lleiva25/Executive_Study_Analysis/assets/140974405/90a0a5db-5652-4b1d-9160-7089796f0353)

----------------------------------------------------------------------------------------------
Data Analysis
----------------------------------------------------------------------------------------------
In the detailed analysis of sample contributions, it is evident that sites 112, 111, and 109 emerge as the most prolific contributors, surpassing the 2000-sample mark, while sites 103, 102, and 108 lag behind, providing less than 600 samples each. February stands out with the lowest sample intake, recording only 1224 samples. However, a closer examination of daily and quarterly contributions reveals a commendable consistency, indicating stable operational processes.

Delving into the temperature data for 2023, Tempsensors play a predominant role, followed closely by Flashlinks in providing insights into sample storage conditions. Notably, the top deviations identified across sites include issues such as One viable BCT (27%), blank forms (19.9%), and missing information (17.0%). Site-specific analysis showcases the disparity in deviation rates, with site 109 reporting only one deviation at a rate of 0.04%, while site 103 exhibits the highest deviation rate at 6%.

Furthermore, the data suggests an encouraging trend as sample deviations decrease throughout the year. This positive trajectory may be attributed to initiatives such as site retraining and improved instructions for clinics. Interestingly, Wednesdays consistently stand out with the highest number of deviation tickets, warranting a closer examination of processes on this particular day. Notably, in Q4, there is a significant increase in deviations related to missing information and blank forms, highlighting a specific area that requires targeted attention and improvement efforts. These insights collectively provide a comprehensive understanding of sample contributions, deviations, and trends, paving the way for strategic enhancements in quality control processes.

![Execution_Study_Plot_1](https://github.com/lleiva25/Executive_Study_Analysis/assets/140974405/895fe00a-658f-42a7-837c-0f3586fc86e1)

![Execution_Study_Plot_2](https://github.com/lleiva25/Executive_Study_Analysis/assets/140974405/0ac67f48-5fa8-45a4-aca4-e29114c48ca8)

![Execution_Study_Plot_3](https://github.com/lleiva25/Executive_Study_Analysis/assets/140974405/df337882-cd24-409a-b37b-aa7379ead609)

![Execution_Study_Plot_8](https://github.com/lleiva25/Executive_Study_Analysis/assets/140974405/040c1ce8-1cd5-4ee4-915a-55dd97945444)

![Execution_Study_Plot_17](https://github.com/lleiva25/Executive_Study_Analysis/assets/140974405/ce97dcc2-0f1a-4fec-a811-1fec1e29e5ba)

![Execution_Study_Plot_18](https://github.com/lleiva25/Executive_Study_Analysis/assets/140974405/59055a5f-0c6c-4e8c-ad06-5d8f257d082f)

![Execution_Study_Plot_21](https://github.com/lleiva25/Executive_Study_Analysis/assets/140974405/003397e6-9657-4d3c-b2bf-42f1416baf87)

![Execution_Study_Plot_20](https://github.com/lleiva25/Executive_Study_Analysis/assets/140974405/d39bb930-092b-4b97-915c-f653c6e3e228)

![Execution_Study_Plot_24](https://github.com/lleiva25/Executive_Study_Analysis/assets/140974405/0cc2ee6e-a37f-42ee-a847-188611b8a208)

![Execution_Study_Plot_25](https://github.com/lleiva25/Executive_Study_Analysis/assets/140974405/ae930bb7-b89d-4cd9-98e4-2ef28d752de9)

----------------------------------------------------------------------------------------------
Data Preparation
----------------------------------------------------------------------------------------------
1. Randomization of Original Database: The initial database underwent a randomization process, ensuring that it is devoid of any representation of ongoing studies or actual data. This deliberate step eliminates biases and establishes a neutral foundation for subsequent analyses.

2. Conversion to Pandas Data Frame: Datasets were meticulously referenced and subsequently converted into a structured Pandas data frame. This transformation sets the stage for efficient data manipulation, analysis, and visualization.

3. Removal of Unnecessary Values: To enhance data quality, rows containing extraneous values such as "0", "NaN", "nan", and "na" were systematically removed. This data-cleaning step contributes to the overall integrity and reliability of the dataset.

4. Subject ID Verification: A specific check was implemented to identify and address any missing Subject IDs in the dataset. In the event of a missing Subject ID, a protocol is in place to promptly refer the matter to project stakeholders for clarification. This ensures the completeness and accuracy of the dataset.

5. Grouping and Graphical Representation: Utilizing the cleaned dataframe, filter and groupby attributes were defined, and graphs were generated. These graphical representations serve as visual metrics, providing a comprehensive overview of the study's key insights. The combination of groupby operations and graphical visualization enhances the interpretability of the data, facilitating a deeper understanding of patterns and trends within the study parameters.

----------------------------------------------------------------------------------------------
Modules Utilized
----------------------------------------------------------------------------------------------
- Pandas
- Pathlib
- Sys
- Matplotlib
- Numpy
- Os
- Seaborn
- Datetime
  
----------------------------------------------------------------------------------------------
Future Improvements
----------------------------------------------------------------------------------------------
- Optimizing and condensing code utilized for repetitive steps.
- Provide insights into the status of samples when received/processed.
- Create a Tableau dashboard for this dataset for interactivity and easier comprehension.

----------------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------------

