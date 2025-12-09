# Group Research Project Report

## Team Members:
1. Koussay Hazami
2. Churi Divyank Ramakant
3. Donda Raj

## Declaration
[ChatGPT 5.0] was used to [brainstorm themes and structure] for this group research project report on [topic]. Prompt: '...' No AI-generated text is included in the final submission. Accessed: [Date]. Available at: https://chat.openai.com/.

We have retained a complete set of raw data, including questionnaires (papers completed by hand or record downloaded from the online survey platform), recordings, and/or transcripts of interviews, secondary data, etc., as well as data analysis files and documents. 

1. Executive Summary
...

2. Introduction
...  

## 3. Methodology

### 3.1 Survey Design

An organized online survey has been designed that had:

**Demographic questions** (age, gender identity, race/ethnicity, disability status, tenure, employment level)

**Five composite domains** of DEI, which are calculated using several Likert-scale items:

- Representation
- Psychological Safety
- Inclusive Leadership
- Bias Reporting & Accountability
- Visibility of Initiatives

Responses were measured using a 1-5 Likert scale (1 = strongly disagree, 5 = strongly agree).

---

### 3.2 Sampling and Data Collection

Instrument we used: Google Forms containing 25 questionnaire.

Sample size: N = 60 employees responses.

Sampling procedure we did: Convenience sampling within in some multinational organisation.

Timeline: Data was collected between 15th November to 1st December, 2025.

Respondent profiles we get:

- 43% aged between 25-34 years.
- 43% are women, 35% of them are men, and 5% non-binary/gender-diverse.
- 33% of underrepresented racial/ethnic groupings.
- 17% who considered themselves having a disability.
- Most of them were individual respondents (N=29) or people managers (N=18).

---

### 3.3 Data Handling and Preparation

In order to be accurate and more reliable in the analysis process, standard data handling methods were used and applied on the responses of the survey. It was checked that all the entries in the dataset were complete, consistent and ina a format that would be nalyzed automatically. Simple assessments were conducted in order to determine the presence of any repeated answers, lack of answers, and demographical labels anomalies. Variable names (example.. Q_Represent_Leadership, Q_Bias_Reporting) were standardised and made easier to read, as well as compatible with Python. Every step of the analysis was recorded to enhance transparency and reproducibility when working in the group.

---

### 4.Results & Data Analysis

### 4.1 Data Analysis

To carry out the analysis section, we primarily worked with Python, in particular, Pandas, NumPy and Matplotlib.To get a rough idea of the way people responded we first had a glance at some basic descriptive statistics. Next we did the demographic breakdowns and then we saw how various groups (age, gender, etc) were represented in the survey. Then we compared the scores of the DEI domain by employment status, ethnicity, and disability status. To check the possibilities that dissimilar groups of people had significantly different experiences. We also determined what questions in the survey scored the highest and the lowest. From this we get idea of the best and the worst area in the DEI activities in the organisation.Finally, a basic correlation test was conducted to determine the extent to which psychological safety and bias reporting were related. Generally, the analysis has made us see the trend of the data in a better way.

---

### 4.2 Demographic Overview

 We firstly analyzed demographic profiles :

**Age:** 43% aged between 25-34 years. 
**Gender:** 26 female, 21 male, 3 non-binary/gender-diverse, 10 prefer not to say.
**Tenture:** Largly 1-3 years
**Level of employment:** 48% Individual contributor

These distributions bring out heterogeneity that is necessary in segmentation analysis.

#### **Figure 1. Demographic Profiles** 
![Demographic Profiles](images/Demographic_Profile.png)
Figure 1: Demographic Profiles of respondants (N=60)

---

### 4.3 Overall DEI Domain Scores 

We did Descriptive Statistics-Test to comapare scores of dirrent dimentions.

- Bias Reporting is the highest score -- 3.4, but the high SD shows this masks deep disagreement.
- Inclusive Leadership score --3.39 is also higher.
- The true overall risk is Representation,because the score is the lowest 3.15

|    **Domain**        |**Mean**|**SD**|**Min**|**Max**|
| -------------------- | ------ | ---- | ----- | ----- |
| Representation       | 3.15   | 1.17 |   1   |   5   |
| Psychological Safety | 3.20   | 1.11 |   1   |   5   |
| Inclusive Leadership | 3.39   | 1.23 |   1   |   5   |
| Bias Reporting       | 3.4    | 1.27 |   1   |   5   |
| Visibility           | 3.27   | 1.23 |   1   |   5   |



---
5.  Discussion
... 

6. Recommendations
... 

7. Reflection on Team Process
... 

8. References and Appendices
... 
