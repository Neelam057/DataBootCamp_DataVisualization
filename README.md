# **Pymaceuticals, Inc. – Senior Data Analyst Report on Squamous Cell Carcinoma (SCC) Study**


### **1. Objective**

Pymaceuticals, Inc. recently conducted a clinical study to evaluate the effectiveness of its drug of interest, **Capomulin**, in treating **squamous cell carcinoma (SCC)** in mice. The study involved **249 mice**, each diagnosed with SCC tumors, and was carried out over a 45-day period. The goal of the study was to assess the performance of Capomulin against other drug regimens and to provide insights into tumor growth under different treatments.

---

### **2. Key Parameters**

The study utilized a variety of **drug regimens** to treat the mice, including Capomulin, Ceftamin, Infubinol, Ketapril, Naftisol, Placebo, Propriva, Ramicane, Stelasyn, and Zoniferol. Key parameters collected during the study include:
- **Mouse ID**: Unique identifier for each mouse.
- **Drug Regimen**: The treatment administered (Capomulin, etc.).
- **Tumor Volume (mm³)**: Measured tumor size at different time points.
- **Timepoint**: The day on which tumor volume was measured.
- **Weight (g)**: Mouse weight at each timepoint.
- **Metastatic Sites**: Number of metastases (if applicable).

The study results were used to compare the **tumor volume** growth across different drug regimens, and to assess whether Capomulin was particularly effective in comparison to other treatments.

### **3. Key Findings and Summary**

#### **3.1. Observations**
- **Capomulin Regimen** showed promising results with a **significant reduction in tumor volume** compared to other regimens. The study focuses on **mouse weight** and **tumor volume** for the Capomulin-treated group.
- Out of the 249 mice, several showed signs of **tumor regression** or **slowed tumor growth**, especially in the Capomulin group.
- A **strong positive correlation** was found between **mouse weight** and **average tumor volume** for the Capomulin regimen, indicating that heavier mice tended to have larger tumors.

#### **3.2. Statistical Analysis**
- **Correlation Coefficient** between mouse weight and tumor volume was calculated to quantify the relationship.
- **Linear regression** analysis was performed to determine the mathematical model that best fits the relationship between mouse weight and tumor volume.
- The equation of the regression line is:  
  \[
  y = 0.9544x + 21.5522
  \]
  Where:
  - \(y\) is the tumor volume (mm³).
  - \(x\) is the mouse weight (g).

- **Boxplot Analysis** revealed the distribution of tumor volumes, highlighting potential outliers and demonstrating the effect of treatment on tumor reduction.

#### **3.3. Comparison of Treatment Regimens**
- Various treatment regimens were compared for their effectiveness in reducing tumor volume. In particular:
  - **Capomulin** and **Ramicane** demonstrated the best overall results in reducing tumor growth.
  - **Placebo** and some other regimens showed little to no improvement, and in some cases, tumor volumes increased or remained stable.

#### **3.4. Outlier Analysis**
- The study included an analysis of potential **outliers** in the tumor volume data. Outliers were flagged using the **Interquartile Range (IQR)** method, and some data points were identified as significantly different from the overall trend. These outliers were reviewed for potential errors or significant deviations in the study process.


### **4. Visualizations**

#### **4.1. Bar graph for showing the drug regimens count**
A bar graph was plotted to visualize total no. of rows for each drug regimen.

#### **4.2. Pie Chart of Gender Distribution**
A pie chart was used to visualize the gender distribution (male vs. female) of the mice in the study.

#### **4.3. Boxplot of Tumor Volume by Drug Regimen**
A boxplot was used to show the distribution of tumor volumes for each drug regimen, identifying medians, quartiles, and outliers in the data.

#### **4.4. Line Plot of Tumor Volume vs. Time for Capomulin Group**
A line plot was created for mice treated with **Capomulin** to show how tumor volume changed over time for individual mice.

#### **4.5. Scatter Plot (Mouse Weight vs. Tumor Volume)**
A scatter plot was created to visually assess the relationship between mouse weight and tumor volume. A **linear regression line** was added to better understand the trend.



### **5. Detailed Analysis**

#### **5.1. Correlation Analysis**
The Pearson **correlation coefficient** between mouse weight and tumor volume for Capomulin-treated mice was calculated. A strong positive correlation (e.g., 0.89) was found, indicating that heavier mice tend to have larger tumor volumes.

#### **5.2. Linear Regression**
The linear regression model provides a mathematical relationship between the two variables, which can help predict tumor volume for a given weight of the mouse. The equation **y = 0.9544x + 21.5522** suggests that as the weight of the mouse increases, so does the tumor volume, but the increase is moderate.

