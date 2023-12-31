# Julian Cabrini's Portfolio
*Health Data Analytics Portfolio*

## Project: General Service Report - Healthcare Center

### Overview
The clinic I worked for lacked comprehensive insights into its service activities. Management reporting methods were basic, outdated, and lacked automation. Recognizing the need for detailed information on health service production, the project aimed to understand quantities, estimated revenues over different periods, primary financiers, and the activities of various medical providers, among other aspects.

### Data Source
The database was exported from the Electronic Health Record and Enterprise Resource Planning systems, providing fact-type tables with all necessary details. The tables contained approximately 120,000 entries. Extensive data cleaning was performed, primarily addressing errors from clinic data entry operators. Various dimensional tables, such as financiers and practice groups, were created to efficiently anchor and organize the data.

### Creation of Specific Measures
Multiple measures were applied to the extracted tables to identify quantities, averages, rankings, and other relevant metrics.

### Data Visualization
The data were segmented into five sections, representing simultaneous operational units within the clinic:

- **Outpatient Service**

![consultorio](https://github.com/juliancabrini/portfolio/assets/152528339/c463bbe4-f9cb-44d9-8f20-356b815cc245)

- **Emergency Room**

![guardia](https://github.com/juliancabrini/portfolio/assets/152528339/e6f77ac3-84aa-4822-bff0-756c6732dd4c)

- **Computed Tomography Service**

![tomografia](https://github.com/juliancabrini/portfolio/assets/152528339/a9a7a791-197f-4474-b08d-8fb71cc6d5aa)

- **Operating Room Service**

![cirugia](https://github.com/juliancabrini/portfolio/assets/152528339/56390fb5-cd14-4ae2-abc9-6343e2107d92)

![cirugias detalle](https://github.com/juliancabrini/portfolio/assets/152528339/fb27a7c3-625e-4ad7-855b-912af4922e0f)

- **Gastrointestinal Endoscopy Service**

![endoscopia](https://github.com/juliancabrini/portfolio/assets/152528339/b3c7f196-7082-4505-a18d-2f492aac35a7)

### Results and Conclusions
Given its dynamic and daily-updatable data model, the project aimed to provide a detailed and easily interpretable understanding of the clinic's diverse operational units. The goal was to view the clinic as a whole, simplifying data for intelligent and data-driven decision-making.

The model allowed for a preliminary view, before monthly billing to major financiers, of the number and approximate monetary value of practices performed in a month. It facilitated historical comparisons between different periods, presenting a comparative historical graph with future projections.

Moreover, the model provided insights into peak service hours, prompting adjustments to admission processes to enhance the patient experience.

### Skills Utilized

**Database:**
- Geclisa (EHR-ERP software)
- SQL
- Microsoft Excel

**ETL Tool:**
- Power Query

**Data Visualization:**
- Power BI Desktop/Service
