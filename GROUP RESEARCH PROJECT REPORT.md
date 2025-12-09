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

#### Demographic Profiles** 
![Demographic Profiles](images/Demographic_Profile.png)
Figure 1: Demographic Profiles of respondants (N=60)

---

### 4.3 Overall DEI Domain Scores 

We did Descriptive Statistics-Test to comapare scores of dirrent dimentions.

- Bias Reporting is the highest score -- 3.4, but the high SD shows this masks deep disagreement.
- Inclusive Leadership score --3.39 is also higher.
- The true overall risk is Representation,because the score is the lowest 3.15

Table 1. Overall DEI Domain Scores

|    **Domain**        |**Mean**|**SD**|**Min**|**Max**|
| -------------------- | ------ | ---- | ----- | ----- |
| Representation       | 3.15   | 1.17 |   1   |   5   |
| Psychological Safety | 3.20   | 1.11 |   1   |   5   |
| Inclusive Leadership | 3.39   | 1.23 |   1   |   5   |
| Bias Reporting       | 3.4    | 1.27 |   1   |   5   |
| Visibility           | 3.27   | 1.23 |   1   |   5   |



---

### 4.4 DEI Differences Across Employment Levels  

**The Equity Gap Insight:**
- The largest disparity is a 1.01-point gap in Inclusive Leadership perception between staff and executives.
- Executives score themselves and their environment lowest (2.74 in Leadership).
- Staff (ICs) are surprisingly the most positive group.

#### DEI Scores by Employment Level**
![Employment Level](images/Employment_Level.png)
Figure 2:DEI_Perception_by_Employment_Level

---

### 4.5 Strongest and Weakest Perceived DEI Items 

Table-2:Highest Risk/Streangth Area 

|                         Item               | Mean |
|--------------------------------------------|------|
| **Lowest-scoring:** Diverse leadership rep.| 2.77 |
| **Highest-scoring:** Manager accessibility | 3.56 |

**Insights:**Employees feel their managers are approachable, but do not see sufficient diversity in leadership roles.

---

### 4.6 Majority vs Underrepresented Groups (URG)

#### DEI Scores: Majority vs URG**
![URG Comparison](images/URG_group.png)
Figure 3:DEI_Perception_by_Majority vs Underrepresented Groups


Table-3:IDENTITY EQUITY GAP 

|    Domains        | Majority | URG |
|------------------ |----------|------|
| Representation    |   3.11   | 3.16 |
| Psych. Safety     |   2.97   | 3.29 |
| Inclu. Leadership |   2.98   | 3.56 |
| Bias Reporting    |   3.16   | 3.49 |
| Visibility        |   3.04   | 3.36 |

**Insights**: URG respondents consistently score Higher across all domains.

---

### 4.7 DEI Differences by Disability Status

#### DEI Scores by Disability Status**
![Disability status](images/Disability_Status.png)
Figure 3:DEI Perception by Disability status


Table-4:Segmentation by Disability Status

|     Domain       | No Disability | Disability | Prefer Not to Say |
|------------------|---------------|------------|-------------------|
| Representation   |     3.23      |     2.83   |      3.46         |
| Psych. Safety    |     3.32      |     2.50   |      3.87         |
| Inclu.Leadership |     3.56      |     2.70   |      3.87         |
| Bias Reporting   |     3.35      |     2.53   |      3.46         |
| Visibility       |     3.38      |     2.87   |      3.87         |


**The Equity Gap Insight:**
- Employees identifying with a disability score 0.91 points lower on their overall DEI experience than their peers.
- **Systemic Failure:** This gap is statistically significant (p-value = 0.0241).

---

### 5.7 Correlation Analysis

Correlation between Psychological Safety and Bias Reporting: 0.78

**Insight:** The strong positive correlation (R > 0.6) suggests these two issues are fundamentally linked.Employees who feel psychologically safe are far more likely to trust the reporting process.You cannot fix one without fixing the other.




5.  Discussion
... 

---

## 6. Recommendations

### Priority 1 — Strengthen Inclusive Leadership  
Mandatory training on inclusive decision-making  
Leadership performance KPIs tied to DEI metrics  
Transparent criteria for promotion and talent pipelines  

### Priority 2 — Improve Psychological Safety Mechanisms  
Train managers in open dialogue and constructive feedback  
Introduce anonymous feedback channels  
Encourage speak-up culture through regular forums  

### Priority 3 — Build Trust in Bias Reporting Systems  
Communicate processes clearly and transparently  
Provide case examples of resolved issues  
Protect confidentiality rigorously  

### Priority 4 — Support Underrepresented and Disabled Employees  
Targeted mentoring programmes  
Accessibility audits  
Employee Resource Groups (ERGs) for identity-based communities  
Clear accommodation pathways  

### Priority 5 — Enhance Visibility of DEI Initiatives  
Regular progress updates  
Success stories and role models  
DEI dashboards accessible to employees  

These interventions align with global best practices and directly target the gaps observed in the data.

## 7. Reflection on Team Process (Agile + GitHub)

Our team implemented several Agile practices as required in the assignment brief:

### Sprint Planning  
We conducted an initial sprint planning meeting to define milestones:  
Survey design  
Data collection  
Python analysis  
Drafting report sections  
Final integration and review  

### Daily/Regular Stand-Ups  
Short check-ins were held every 2–3 days to:  
Review progress  
Discuss blockers  
Reassign tasks if needed  

### GitHub Collaboration  
We used branches for separate tasks (analysis, visuals, writing).  
Pull requests ensured peer review of all contributions.  
Issues were used to track tasks (e.g., “Fix visualisation labels”, “Add segmentation table”).  
This aligns with the criteria for effective GitHub use (page 2 of assignment brief).  

### Retrospective  
At the end of the project, we held a retrospective to evaluate:  
What worked: clear division of labour, steady progress  
What could improve: earlier testing of visualisations, more consistent documentation  
What to keep: regular stand-ups, GitHub branching model  

Overall, teamwork was balanced, communicative, and adaptive.


8. References and Appendices
... 
