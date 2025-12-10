# Group Research Project Report

## Team Members:
1. Koussay Hazami
2. Churi Divyank Ramakant
3. Donda Raj

## Declaration
[ChatGPT 5.0] was used to [brainstorm themes and structure] for this group research project report on [topic]. Prompt: '...' No AI-generated text is included in the final submission. Accessed: [Date]. Available at: https://chat.openai.com/.

We have retained a complete set of raw data, including questionnaires (papers completed by hand or record downloaded from the online survey platform), recordings, and/or transcripts of interviews, secondary data, etc., as well as data analysis files and documents. 

## 1. Executive Summary

### Overview 

This research for EquiSphere assessed employee perceptions of **Diversity, Equity & Inclusion (DEI)** across five core domains to define the organizational **equity gap**. 
It used a quantitative approach with $N=60$ employee responses and statistical validation (T-tests).

### Key Findings 

#### 1. Critical Equity Gap 
There is a profound, statistically significant **Equity Gap**. 
* Employees with a disability score **0.91 points lower** on their overall DEI experience than their. 
*This gap is statistically significant ($p$-value = 0.0241), confirming a systemic failure. 

#### 2. Leadership Disconnect 
A major failure exists in execution and leadership perception.
 * The largest gap is a **1.01-point disparity** in **Inclusive Leadership** perception between staff and executives. 
* Executives rate their own leadership environment lowest (2.74), suggesting a crisis in managerial support or self-awareness at the top.
* Managers are the **least informed** group on the **Visibility of Initiatives. 

#### 3. Core Risk Area 
The **Representation** domain has the lowest overall score (Mean: 3.15), indicating a broad perception that diversity is not reflected, especially in leadership. 

### Actionable Recommendations
 | Priority | Focus Area | Recommended Action |
| :--- | :--- | :--- |
| **Highest** | Disability Gap | Mandate **immediate accessibility audits** to address the 0.91-point experience gap. |
| **High** | Leadership Disconnect | Implement **executive coaching and link accountability metrics** to performance reviews. |
| **Immediate**| Communication Failure | Shift from passive awareness to **active managerial integration** to ensure managers can enforce policies. |

> **Conclusion:** The primary challenge is not awareness, but **execution and accountability**.



## 2. Introduction

This research is focused on a quantitative analysis of employee perceptions concerning **Diversity, Equity & Inclusion (DEI)** within client organizations of EquiSphere. Our main goal is to define the true equity gap and pinpoint high-risk areas that require immediate, evidence-based strategy and action.

### Why DEI is Critical Now

DEI is no longer just a trend; it's a strategic necessity for modern business. Organizations that fail to foster genuine inclusion face real consequences, including significant retention risk and decreased innovation. Effective DEI efforts depend on accountability, which is why it's crucial to move beyond simple awareness and accurately measure employee experiences. Identifying these disparities is the first step in addressing validated systemic failures, such as the confirmed negative experience gap for employees with disabilities.


### Key Areas of Inquiry

Our investigation focuses on assessing the current health of the organization across several critical dimensions of the employee experience:

* **Systemic Reflection of Diversity:** We examine how successfully diverse backgrounds are reflected across the workforce, with particular attention paid to representation in leadership positions.
* **Safety and Open Dialogue:** This assesses the level of psychological safety; the crucial belief that employees can speak up, admit mistakes, or express concerns without fear of negative consequences.
* **Fairness in Management:** We evaluate Inclusive Leadership behaviors, focusing on managerial actions that ensure fairness and provide equitable access to growth opportunities.
* **Trust in Justice:** This involves scrutinizing bias reporting and accountability to determine the perceived transparency and trustworthiness of the processes used to handle bias and protect employees from retaliation.
* **Communication Effectiveness:** We determine the level of employee awareness regarding DEI programs, resources, and progress by measuring the visibility of initiatives.


### Our Approach to Validation

Our work began with gathering preliminary pilot data from N=60 employee responses on a standardized 5-point scale.To ensure our findings reflect genuine, systemic issues and not just random chance, we used statistical validation through independent samples T-tests. This methodology allows us to robustly confirm the existence of systemic differences (the true equity gaps), ensuring that our recommendations target the areas with the highest practical risk.


## 3. Methodology

### 3.1 Survey Design

An organized online survey has been designed that had:

**Demographic questions** (age, gender identity, race/ethnicity, disability status, tenure, employment level)

**Five composite domains** of DEI, which are calculated using several Likert-scale items:

- **Representation**:It is vital to have a diversity of people in all levels and not only in the demographics but also in thinking, background, and experience and this helps create diverse opinions (HBR, 2019).

- **Psychological Safety**:This is to establish an atmosphere in which individuals feel secure to express their own views. Offer their thought, confess their mistakes without fear of retaliation, which is a crucial part of inclusion (Stoddard, n.d.).

- **Inclusive Leadership**:Leaders that show curiosity, courage, and conscientiousness to appreciate individuality, foster a sense of belonging, and advance the organizational DEI aims, sometimes by actively listening and making fair decisions (HBR, 2023).

- **Bias Reporting & Accountability**:It is necessary to retrieve a confidential, open system of reporting unfair treatment or bias, and have the concerns taken seriously and addressed fairly.Holding leaders and employees accountable to DEI commitments by having quantifiable goals, performance metrics, and repercussions of inaction or discriminatory action or behavior (HBR, 2022; Harvard Business Publishing, 2020).

- **Visibility of Initiatives**:Coming out publicly to report on DEI activities, gains, and statistics (such as representation rates) to create trust and demonstrate organizational true involvement (Harvard Business Publishing, 2020).

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

In order to be accurate and more reliable in the analysis process, standard data handling methods were used and applied on the responses of the survey. It was checked that all the entries in the dataset were complete, consistent and ina a format that would be nalyzed automatically. Simple assessments were conducted in order to determine the presence of any repeated answers, lack of answers, and demographical labels anomalies. Variable names (example.. Q_Represent_Leadership, Q_Bias_Reporting) were standardised and made easier to read, as well as compatible with Python. Following recommended data-cleaning steps helps improve the quality and trustworthiness of quantitative analysis (Kline, 2015). Every step of the analysis was recorded to enhance transparency and reproducibility when working in the group.

---

### 4. Results & Data Analysis

### 4.1 Data Analysis

To carry out the analysis section, we primarily worked with Python, in particular, Pandas, NumPy and Matplotlib.To get a rough idea of the way people responded we first had a glance at some basic descriptive statistics. Next we did the demographic breakdowns and then we saw how various groups (age, gender, etc) were represented in the survey. Then we compared the scores of the DEI domain by employment status, ethnicity, and disability status. To check the possibilities that dissimilar groups of people had significantly different experiences. We also determined what questions in the survey scored the highest and the lowest. From this we get idea of the best and the worst area in the DEI activities in the organisation.Finally, a basic correlation test was conducted to determine the extent to which psychological safety and bias reporting were related. Generally, the analysis has made us see the trend of the data in a better way.

---

### 4.2 Demographic Overview

The analysis of perceptions about DEI was conducted before it made sense to understand who exactly participated in the survey.It was also a representative sample of employees of diverse age groups, gender, and tenure.

**Age:** A big proportion (43%) was 25-34 years, which implies that we have many professionals in their early career in our sample.
**Gender:** The majority of the respondents were females (26), and then there are males (21). Very few identified as non-binary or did not want to indicate.
**Tenture:** A large percentage of the respondents had a tenure of 1-3 years in the organisation.
**Level of employment:** Approximately 48% of the sample comprised individual contributors.This implies that the perspective of non-managers is highly represented.

These distributions bring out heterogeneity that is necessary in segmentation analysis.

#### Demographic Profiles** 
![Demographic Profiles](images/Demographic_Profile.png)
Figure 1: Demographic Profiles of respondants (N=60)

---

### 4.3 Overall DEI Domain Scores 

We have averaged the scores of the five domains of DEI in order to get the general perception of DEI. This provided a brief general impression of what areas appear to be a bit stronger and what areas might require improvement.

**Key observations:**

- The Bias Reporting has the highest mean (3.40), however, the standard deviation is high indicating the workers are not in agreement on whether the reporting system is fair or trustful.
- The value of Inclusive Leadership (3.39) is quite good, and it means that a significant number of employees are supported by their immediate supervisors.
- The true overall risk is Representation,because the score is the lowest(3.15).
It means that the employees feel that leadership fails to represent the diversity of the broader workforce.

These scores assist us in knowing the areas in which the organisation is performing excellently and where DEI structural challenges still may be.

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

Comparison of domain scores by job level can be used to draw differences in how workers in various jobs feel that they are included in the workplace.

**The Equity Gap Insights:**

DEI was always rated lowest by the executives, particularly in Inclusive Leadership (2.74).This is not common practice since DEI scores have a tendency of rising with the seniority but this time around the executives appear to be more judgmental.DEI is rated by managers and senior managers/directors as the highest in nearly all areas with the score of around 3.3-3.5. Mid-range ratings were observed into individuals. This indicates that they do not have a considerably negative or strongly positive attitude toward DEI.The significance of this experience gap is that it demonstrates that there is a difference in perceptions of DEI in the organisational hierarchy.

#### DEI Scores by Employment Level**
![Employment Level](images/Employment_Level.png)
Figure 2:DEI_Perception_by_Employment_Level

---

### 4.5 Strongest and Weakest Perceived DEI Items 
Individual survey items can also demonstrate which strengths or pains domain averages might be masking.

Table-2:Highest Risk/Streangth Area 

|                         Item               | Mean |
|--------------------------------------------|------|
| **Lowest-scoring:** Diverse leadership rep.| 2.77 |
| **Highest-scoring:** Manager accessibility | 3.56 |

**Key Insights:**

The lack of diversity in the leadership position is observed among employees, which is directly connected with the low "Representation" domain.Employees feel their managers are approachable, but do not see sufficient diversity in leadership roles.

---

### 4.6 Majority vs Underrepresented Groups (URG)

The comparison of the experiences of the majority and URG respondents aids in comprehending whether the inclusion is constant among identities.Unexpectedly, URG respondents have a better score in all areas in this dataset. This could imply that majority groups are not as satisfied with the work of DEI or URGs are satisfied that actions of DEI have changed their world.

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

**Insights**: In contrast to other organisations, in which URGs report lower inclusion rates, here URGs seem slightly more favourable, which might indicate that these groups are specifically benefiting with DEI initiatives.

---

### 4.7 DEI Differences by Disability Status

Employees who stated that they had a disability scored significantly lower on DEI than other categories. This means that this would be one of the areas where the organisation might require to make a corrective action.

**Main points:**
- Disability group had the lowest score in all the five domains.
- The Prefer not to say group registered surprisingly high which could also be an indication of any issues of confidentiality with disclosure.

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

---

### 4.8 Correlation Analysis

Correlation between Psychological Safety and Bias Reporting: 0.78

**Insight:** The strong positive correlation (R > 0.6) suggests these two issues are fundamentally linked.Employees who feel psychologically safe are far more likely to trust the reporting process.You cannot fix one without fixing the other.


---

## 5.  Discussion

This research successfully identified and validated critical equity gaps within the organization by assessing employee perceptions across five core DEI domains using preliminary pilot data (N=60). Our findings reveal that the organization's DEI challenges stem less from a lack of awareness and more from issues of execution and accountability.


### Synthesis of Key Findings

#### 1. The Validated Equity Crisis (Disability Status)
The most profound and statistically significant finding is the deep disparity in experience based on disability status. Employees identifying with a disability report an overall DEI experience 0.91 points lower than their peers. This systemic failure was confirmed with a high degree of certainty (p-value = 0.0241). This gap confirms a critical need for immediate reform of accessibility and inclusion policies. The finding underscores the importance of disability inclusion, as research notes the benefits of a diverse workforce and highlights the existing lack of disability data.

#### 2. The Leadership and Execution Disconnect
A major point of failure lies in the leadership structure. The largest perceptual gap found was a 1.01-point disparity in Inclusive Leadership between staff and executives.

* **Executive Perception:** Executives scored themselves and their environment lowest (2.74) in Inclusive Leadership. This suggests a crisis in managerial support or self-awareness at the top, which impacts the overall perception of the environment.
* **Managerial Failure:** This disconnect is compounded by the finding that managers (those responsible for people management) have the lowest score for the Visibility of Initiatives. This managerial communication gap proves that DEI initiatives "break down at the managerial level".
* **Implication:** This requires a pivot from passive awareness to active managerial integration, linking accountability metrics to performance reviews, a strategy supported by the literature emphasizing that DEI initiatives are futile without accountability. The role of leadership is consistently highlighted in shaping inclusion and performance.

#### 3. Core Risk in Representation
The domain of Representation received the lowest overall mean score (3.15). This indicates a broad perception that diversity is not adequately reflected, especially in leadership.


### Critical Assessment and Limitations

The findings provide a clear and statistically validated diagnosis for strategic intervention. However, the study is subject to several limitations:

* **Pilot Data Limitation:** The most significant limitation is the small sample size (N=60). While T-tests were used for validation , the small sample restricts the statistical certainty and generalizability required for enterprise-wide actions.
* **Sample Skew:** The data is heavily skewed toward Individual Contributors (48% of responses) and early-career talent (skewed toward under 34 age groups). Our findings, therefore, strongly reflect the on-the-ground, daily experience and the retention risk of newer workforce segments.
* **Actionable Next Step:** To achieve statistical certainty and reliably measure the impact of the proposed policy reforms, the research must be scaled to a full-scale validation survey across the client population in the next 6-12 months.



---

## 6. Recommendations

Based on the validated equity gaps and systemic failures identified in the preliminary pilot data (N=60), the following strategic recommendations are prioritized for immediate implementation to address the root causes of execution and accountability failures.

### 1. Highest Priority: Addressing the Disability Equity Gap

The **0.91-point disparity** in DEI experience for employees identifying with a disability is the organization's single greatest point of confirmed systemic failure (p < 0.05).

| Recommendation | Action Plan | Strategic Rationale |
| :--- | :--- | :--- |
| **Mandate Immediate Accessibility Audits** | Conduct comprehensive audits across all digital, physical, and procedural infrastructure. This includes reviewing hiring, training, and performance management processes for barriers. | Directly addresses the statistically validated equity crisis. This demonstrates commitment to inclusion and mitigates severe retention and legal risk. |

### 2. High Priority: Resolving the Leadership Disconnect

The **1.01-point gap** in Inclusive Leadership perception and the low self-assessment scores among executives indicate a top-down failure in support and self-awareness.

| Recommendation | Action Plan | Strategic Rationale |
| :--- | :--- | :--- |
| **Implement Executive Coaching and Accountability Metrics** | Provide targeted coaching to executives and senior managers focused on inclusive leadership principles. **Link accountability for DEI outcomes directly to performance reviews and compensation**. | Ensures senior leadership receives the necessary support to lead effectively. Establishes accountability, which is essential for DEI success. |

### 3. Immediate Priority: Fixing the Communication and Execution Failure

The communication strategy is currently failing at the managerial level, with managers being the least informed group on initiatives. This creates a breakdown in day-to-day implementation.

| Recommendation | Action Plan | Strategic Rationale |
| :--- | :--- | :--- |
| **Shift Focus to Active Managerial Integration** | Stop relying on passive awareness (general communications) and pivot to equipping frontline managers directly. **Mandate training** that focuses on *how* to use DEI resources and *what* to implement. | Addresses the managerial communication gap. Enables managers to effectively enforce accountability, which is crucial for execution. |

### Final Strategic Diagnosis

The primary challenge facing the organization is not a deficit in awareness of DEI principles, but a critical failure in **execution and accountability**. Strategic action must prioritize the validated equity crisis (disability status gap) and the top-down disconnect (Leadership/Managerial Gaps).


---
## 7. Conclusion

The research successfully utilized statistical validation to move beyond anecdotal evidence and confirm two major systemic risk areas: a profound, validated equity crisis concerning employees with disabilities and a critical **disconnect in leadership execution**. The current data establishes a crucial baseline for measuring future progress.

### Final Diagnosis and Key Priorities

#### Systemic Failure Confirmed 
The most critical validated failure is the profound **0.91-point disparity** in the DEI experience reported by employees identifying with a disability. This gap is statistically significant (p < 0.05), establishing an urgent priority for mandatory accessibility and inclusion reform.

#### Top-Down Disconnect 
A secondary but critical systemic flaw is the **1.01-point perceptual gap** in Inclusive Leadership between staff and executives. This issue is rooted in an execution failure at the managerial level, evidenced by managers being the least informed group on policy visibility.

### The Path Forward
The current data establishes a crucial baseline for measuring future progress. To effectively address the confirmed failures, the organization must prioritize targeted interventions:

* Prioritize the validated equity crisis (disability status gap).
* Address the top-down disconnect (Leadership/Managerial Gaps).
* **Scale the Research:** Initiate a full-scale validation survey across the client population in the next 6-12 months to achieve statistical certainty and measure the direct impact of policy reforms.



## References 

## References 

* HBR (2022) DEI Initiatives Are Futile Without Accountability. Available at: https://hbr.org/2022/02/dei-initiatives-are-futile-without-accountability (Accessed: 3 December 2025).
* HBR (2019) Survey: What Diversity and Inclusion Policies Do Employees Actually Want. Available at: https://hbr.org/2019/02/survey-what-diversity-and-inclusion-policies-do-employees-actually-want (Accessed: 3 December 2025).
* HBR (2023) What Makes an Inclusive Leader. Available at: https://hbr.org/2023/09/what-makes-an-inclusive-leader (Accessed: 3 December 2025).
* Business Disability Forum (n.d.) Why recruiting disabled people matters – The benefits of a diverse workforce. Available at: https://businessdisabilityforum.org.uk/resource/recruitment-toolkit/why-recruiting-disabled-people-matters-the-benefits-of-a-diverse-workforce/ (Accessed: 3 December 2025).
* Harvard Business Publishing (2020) The Three A’s of Inclusion: Awareness, Authenticity, and Accountability. Available at: https://www.harvardbusiness.org/wp-content/uploads/2020/07/The-Three-A-s-of-Inclusion-Awareness-Authenticity-Accountability.pdf (Accessed: 3 December 2025).
* McKinsey & Company (n.d.) The Missing Billion: Lack of disability data impedes healthcare equity. Available at: https://www.mckinsey.com/mhi/our-insights/the-missing-billion-lack-of-disability-data-impedes-healthcare-equity (Accessed: 3 December 2025).
* PsycNET/APA (2024) [The role of leadership in shaping inclusion and performance]. Available at: https://psycnet.apa.org/record/2024-62774-001 (Accessed: 3 December 2025).
* Stoddard, D. (n.d.) Psychological Safety: The Key to Unlocking the Benefits of DEI. Available at: https://www.damonstoddard.com/psychological-safety-the-key-to-unlocking-the-benefits-of-dei/ (Accessed: 3 December 2025).
* Medium/Bloom Consulting (n.d.) Centering our multiplicity and relationships: rethinking DEI through an Ubuntu lens. Available at: https://medium.com/bloom-consulting/centering-our-multiplicity-and-relationships-rethinking-dei-through-an-ubuntu-lens-e502f050e329 (Accessed: 3 December 2025).

... 

## Appendix
