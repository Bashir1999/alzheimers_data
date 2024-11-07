# Data Visualization Project

## Data

The data I propose to visualize for my project is Alzheimer's Disease Dataset
Link to dataset: https://www.kaggle.com/datasets/rabieelkharoua/alzheimers-disease-dataset


## Questions & Tasks

The following tasks and questions will drive the visualization and interaction decisions for this project:

 * What is the relationship between BMI and Alzheimer's diagnosis? -- Done
 * What is the distribution of Alzheimer's diagnosis across different age groups? -- Done
 * How does the diagnosis rate vary between different genders? -- Done
 * How does educational level correlate with the risk of Alzheimer's? -- Done
 * What is the effect of smoking and alcohol consumption on Alzheimer's diagnosis? --
 * What is the relationship between head injuries and Alzheimer's? -- DONE
 * How do MMSE scores vary with Age and BMI across different diagnosis statuses? -- DONE
 * What is the effect of alcohol consumption on sleep quality among Alzheimer’s patients? -- DONE
 * How do physical activity interact to affect Alzheimer’s diagnosis? -- DONE
 * How do diet interact to affect Alzheimer’s diagnosis? -- DONE
 * What is the impact of memory complaints on Alzheimer’s diagnosis? -- DONE
 * Avg Cholesterol by Age Group -- DONE
 * What is the relationship between Alcohol Consumption and Sleep Quality on Depressed and Non-depressed patients? -- DONE

## Sketches


Distribution of Age by Alzheimer's Diagnosis:
This graph can answer the first question: What is the distribution of Alzheimer's diagnosis across different age groups?
By using variables such as age and percentage of those who are diagnosed, we can see which age group has the highest percentage of Azheimer's diagnosis, considering the fact, that there might be more people in one age group then other, which is why it is better to use average. 

![image](https://github.com/user-attachments/assets/443e338c-9790-4c94-94da-c65779228977)


Memory Complaints Progression with Age:
This graph can also be beneficial to see the effect of age on memory complaints, wether old people complain more about losing memory or not. 

![image](https://github.com/user-attachments/assets/0b5005f0-7fb6-4a50-bacb-a403e315c3d3)


Cholestrol Total vs MMSE Scores:
The data is visualized as a scatter plot showing the relationship between Cholesterol Total and MMSE Scores.

![image](https://github.com/user-attachments/assets/79014c93-f177-4eb0-9b76-12d313222622)


## Prototypes

Relationship between BMI & Alzheimer's Diagnosis:
https://vizhub.com/Bashir1999/bmi_alzheimer

<img width="795" alt="Screenshot 1403-08-01 at 21 11 21" src="https://github.com/user-attachments/assets/e3e18c8d-50fe-4a7d-b112-247d14da0bb5">

In each BMI category (15-19, 20-24, 25-29, 30-34, 35-39), the number of individuals who are "Not Diagnosed" is consistently higher than those who are "Diagnosed." This indicates that, across all BMI ranges, a majority of individuals do not have an Alzheimer's diagnosis.

The chart does not show a clear trend in Alzheimer's diagnosis rates based on BMI. For example, the diagnosis rates in lower BMI categories (15-19, 20-24) are similar to those in higher BMI categories (30-34, 35-39).
This suggests that BMI may not be a strong indicator of Alzheimer's diagnosis, as there doesn’t appear to be a direct correlation between BMI and Alzheimer’s risk in this dataset.

The 20-24 BMI range has the highest number of Alzheimer's diagnoses among all categories. This could indicate a higher prevalence within this range, though it may also be reflective of the distribution of patients across different BMI categories in the dataset.





Distribution of Alzheimer's diagnosis across different age groups:
https://vizhub.com/Bashir1999/agegroup_alzheimer

<img width="792" alt="Screenshot 1403-08-01 at 21 11 48" src="https://github.com/user-attachments/assets/04b91ff7-fbe5-4d77-8cf0-585f9ecf3e77">

The chart shows an increase in the number of Alzheimer’s diagnoses (Diagnosis Positive) with age up to the 85-89 age group. This suggests that Alzheimer’s is more common in older populations, supporting the understanding that age is a significant risk factor for the disease.

The 85-89 age group has the highest number of Alzheimer’s diagnoses, indicating that this age range may be particularly vulnerable to Alzheimer’s.
After the 85-89 age group, there is a noticeable decline in both diagnosed and non-diagnosed individuals in the 90-94 group, which could reflect the reduced sample size or the challenges associated with aging.

In all age groups, the "Diagnosis Negative" count is higher than the "Diagnosis Positive" count, which is expected, as not everyone in these age groups develops Alzheimer’s.
However, the gap between "Diagnosis Negative" and "Diagnosis Positive" decreases with age, indicating a higher proportion of Alzheimer’s diagnoses in older age groups.

The decline in both diagnosed and not diagnosed cases in the 90-94 age group could be due to a smaller population reaching this age or the increased mortality associated with advancing age, reducing the number of individuals in this category.





How does the diagnosis rate vary between different genders?
https://vizhub.com/Bashir1999/genders-diagnosis

<img width="809" alt="Screenshot 1403-08-02 at 18 08 55" src="https://github.com/user-attachments/assets/c7b21874-02c4-4c3d-8a7b-29589d405c7c">

The diagnosis rates between males and females are relatively close, indicating that gender alone may not be a significant differentiating factor for Alzheimer’s diagnosis in this dataset.
Both genders have approximately the same proportion of diagnosed cases, with males slightly higher than females.

Although the difference is small, males show a marginally higher rate of Alzheimer’s diagnosis compared to females. This could suggest a minor gender-related factor, but the gap is not large enough to draw strong conclusions about gender as a risk factor.

The similar diagnosis rates suggest that Alzheimer’s may affect both genders similarly, supporting the idea that other factors such as age, lifestyle, education level, or genetics may play a more significant role in Alzheimer’s risk than gender alone.


How does educational level correlate with the risk of Alzheimer's?
https://vizhub.com/Bashir1999/education-diagnosis

<img width="807" alt="Screenshot 1403-08-02 at 18 21 27" src="https://github.com/user-attachments/assets/816b1e7e-a1f8-46f7-8f5d-b73c1aa7fdfc">

Across all education levels, a higher percentage of individuals without a diagnosis (Not Diagnosed) is evident, but the proportion of diagnosed individuals varies slightly.
The Bachelor's and Higher education groups have a slightly higher proportion of individuals who are "Not Diagnosed" compared to those with no formal education or only a high school education.

Individuals with no formal education or only a high school education tend to have a relatively higher proportion of Alzheimer’s diagnoses than those with a Bachelor's or Higher education level.
This trend suggests that lower educational attainment may be associated with an increased risk of Alzheimer’s diagnosis.

The data supports the idea of a protective effect of education against Alzheimer's, as higher education levels are associated with lower diagnosis rates. This might be due to cognitive reserve, where individuals with more education build resilience in their brain function, potentially delaying the onset or reducing the risk of Alzheimer’s.



What is the relationship between head injuries and Alzheimer's? 
https://vizhub.com/Bashir1999/head-injuries-diagnosis

<img width="793" alt="Screenshot 1403-08-02 at 19 14 44" src="https://github.com/user-attachments/assets/41169947-130a-4008-b342-9e8aa86f0c3c">

The Head Injury group has a noticeably higher proportion of patients diagnosed with Alzheimer's compared to the No Head Injury group. This suggests that a history of head injury might be associated with an increased risk of Alzheimer’s.

In the No Head Injury group, the majority of patients are in the "Not Diagnosed" category, with a smaller percentage diagnosed with Alzheimer’s.
Conversely, for those with a Head Injury, the percentage of Alzheimer’s diagnoses is higher, indicating that head injuries may play a significant role in the likelihood of developing Alzheimer’s.

These results underscore the potential long-term impact of head injuries on cognitive health. Individuals with a history of head injuries might require closer monitoring for Alzheimer’s and other cognitive issues as they age.
Preventative measures to reduce head injuries, such as promoting helmet use, fall prevention, and workplace safety, could contribute to lowering the risk of Alzheimer’s in the population.





Relationship between BMI and Diet Quality:
https://vizhub.com/Bashir1999/bmi-diet

<img width="778" alt="Screenshot 1403-08-02 at 19 33 31" src="https://github.com/user-attachments/assets/f248ef08-ac2c-42b9-9789-f456fd289a52">

The data points are widely dispersed, indicating no obvious linear or non-linear relationship between BMI and Diet Quality. This suggests that individuals with a high or low BMI can have any level of diet quality, from poor to excellent.



Avg Cholesterol by Age Group:
https://vizhub.com/Bashir1999/avgcholester

<img width="790" alt="Screenshot 1403-08-02 at 19 49 28" src="https://github.com/user-attachments/assets/13857594-8ab8-4d38-84fe-30770736a112">

The average cholesterol levels fluctuate slightly across different age groups but generally remain within a narrow range of about 220–230 mg/dL.
This suggests that while there are some variations, cholesterol levels are relatively stable as age increases in this dataset.

There is a noticeable peak in the 85-89 age group where the average cholesterol level is around 228 mg/dL, followed by a slight decline in the 90-94 age group.
The lowest average cholesterol level is observed in the 75-79 age group, where it dips below 224 mg/dL.

The line chart shows a slight downward trend in cholesterol levels from the 70-74 to the 75-79 age group, suggesting that cholesterol levels may decrease slightly in the late 70s.
However, there is a subsequent rise from the 75-79 to the 80-84 age group, followed by another increase in the 85-89 age group, indicating some variability in older age.



Relationship between Physical Activity and Alzheimer's Diagnosis:
https://vizhub.com/Bashir1999/physical-activity-alzheimers

<img width="780" alt="Screenshot 1403-08-08 at 17 15 06" src="https://github.com/user-attachments/assets/9e2ced6f-e77e-4992-b3f4-f4d402f29449">

Across all levels of physical activity (Active, Barely Active, Highly Active, Moderately Active), the "Diagnosis Negative" group consistently has a higher number of patients than the "Diagnosis Positive" group. This suggests a trend where higher physical activity levels are associated with a reduced likelihood of an Alzheimer’s diagnosis.
Among the Moderately Active and Active groups, the difference between "Diagnosis Negative" and "Diagnosis Positive" is the most pronounced, indicating that moderate to high physical activity might offer protective benefits against Alzheimer’s.

The Barely Active group has the smallest difference between "Diagnosis Negative" and "Diagnosis Positive" counts, suggesting that low physical activity levels may correlate with a higher risk of Alzheimer’s. The smaller gap in this category could imply that insufficient activity could be a potential risk factor.

The Active and Moderately Active groups both have high numbers of "Diagnosis Negative" patients, suggesting that these activity levels might be particularly beneficial for maintaining cognitive health.
Highly Active individuals also show a larger "Diagnosis Negative" count compared to "Diagnosis Positive," but the difference is less dramatic than in the Moderately Active group, possibly due to fewer people falling into this category or other confounding factors.

This data suggests that moderate to high levels of physical activity may be beneficial for reducing Alzheimer’s risk. Encouraging physical activity, particularly at moderate levels, could be a practical recommendation for promoting cognitive health and potentially lowering Alzheimer’s incidence.
The observed trend across all physical activity categories supports the idea that even some level of physical activity (as opposed to being barely active) may be protective against Alzheimer’s.






Relationship between Diet Quality and Alzheimer's Diagnosis:
https://vizhub.com/Bashir1999/diet-alzheimer

<img width="794" alt="Screenshot 1403-08-08 at 17 34 45" src="https://github.com/user-attachments/assets/c962d006-b976-4c76-a31c-2b83dd629f2a">

Patients with Excellent diet quality show fewer Alzheimer's diagnoses compared to those with lower diet quality. The "Diagnosis Negative" bars are taller than the "Diagnosis Positive" bars in this category, suggesting a potential protective effect of high diet quality.

Interestingly, Fair and Good diet quality levels have a similar pattern, with "Diagnosis Negative" counts significantly higher than "Diagnosis Positive." However, both categories also have a relatively high number of Alzheimer's diagnoses.
This suggests that while a fair or good diet quality might reduce the risk compared to poor diet quality, it may not be as protective as an excellent diet.

Among patients with Poor diet quality, there is a considerable number of Alzheimer's diagnoses, almost equaling the number of non-diagnosed patients. This indicates that poor diet quality may be associated with a higher risk of Alzheimer’s diagnosis.



What is the impact of memory complaints on Alzheimer’s diagnosis?
https://vizhub.com/Bashir1999/memory-alzheimer

<img width="800" alt="Screenshot 1403-08-08 at 17 40 54" src="https://github.com/user-attachments/assets/28960d7f-3efb-4141-ad1e-ea985093dbff">

Among patients with memory complaints (Yes), a higher number are diagnosed with Alzheimer's (Diagnosis Positive) compared to those not diagnosed (Diagnosis Negative).
This suggests that memory complaints are a potential indicator or symptom associated with Alzheimer's, as individuals reporting memory issues are more likely to receive a positive diagnosis.
Interestingly, the majority of patients who do not report memory complaints (No) are in the Diagnosis Negative category, meaning they are not diagnosed with Alzheimer's.
However, there is still a significant number of patients without memory complaints who are diagnosed with Alzheimer's, indicating that some Alzheimer's cases may not initially present with memory complaints.


What is the effect of alcohol consumption on sleep quality among Alzheimer’s patients?
https://vizhub.com/Bashir1999/alcohol-sleep-alzheimer

<img width="829" alt="Screenshot 1403-08-08 at 20 18 45" src="https://github.com/user-attachments/assets/d068640f-ae32-4c69-8770-792acab6c9a3">


This heatmap suggests that alcohol consumption does not have a significant observable impact on sleep quality scores among Alzheimer's patients in this dataset. High sleep quality (8-10) is common across all levels of alcohol intake, and there are fewer patients with lower sleep quality (4-5), regardless of their alcohol consumption levels. This may indicate that other factors, not shown here, play a larger role in determining sleep quality among these patients.





Avg Depression Rate by Ethnicity and Gender:
https://vizhub.com/Bashir1999/avgdepressionrateethnicity

<img width="792" alt="Screenshot 1403-08-08 at 22 28 12" src="https://github.com/user-attachments/assets/4e57051d-ef73-40aa-b785-e0da48e761ca">


For most ethnic groups, females show a higher average depression rate than males. This trend is evident in the "Other" and "African American" categories, where the female depression rate is significantly higher.
In the Caucasian and Asian groups, the depression rates between males and females are relatively similar, indicating less gender disparity in these groups.
"Other" Ethnicity: This group shows the highest depression rate, especially among females. This could indicate that individuals in this category are at a higher risk of depression, possibly due to unique socio-cultural or environmental factors.
African American and Asian groups show moderate depression rates, with females slightly higher than males.
Caucasian Group: This group has relatively balanced rates between genders, with both males and females showing moderate levels of depression compared to the "Other" group.


What is the relationship between Alcohol Consumption and Sleep Quality on Depressed and Non-depressed patients?
https://vizhub.com/Bashir1999/alcohol-sleep-depression

<img width="982" alt="Screenshot 1403-08-17 at 16 11 34" src="https://github.com/user-attachments/assets/b8221de7-b79f-4045-b89c-b08ee6229101">


Inverse Relationship Between Alcohol Consumption and Sleep Quality: The graph shows a downward trend, suggesting that as alcohol consumption increases, sleep quality tends to decrease. This inverse relationship may indicate that higher levels of alcohol intake have a negative impact on sleep quality.

Distribution of Depression Status: The two colors (orange and blue) represent different Depression statuses (0 and 1). It appears that data points for both depression groups are intermingled across all levels of Alcohol Consumption and Sleep Quality. However, there might be patterns worth exploring, such as potential clusters or distribution differences between these two groups.

Clustering of Data Points at Low Alcohol Consumption: A noticeable clustering of data points can be seen on the left side of the x-axis (lower values of Alcohol Consumption). This may indicate that a significant number of individuals have relatively low alcohol intake levels, with varying levels of Sleep Quality.

Overlapping Data Points: The overlapping of blue and orange data points in many regions suggests that both groups (with and without depression) experience a range of sleep qualities and alcohol consumption behaviors. This overlap might indicate that the Depression status does not solely depend on Alcohol Consumption or Sleep Quality.





How do MMSE scores vary with Age and BMI across different diagnosis statuses? (Sample 100 Data Points)

https://vizhub.com/Bashir1999/mmse-bmi

<img width="736" alt="Screenshot 1403-08-17 at 16 45 38" src="https://github.com/user-attachments/assets/75838b52-69d8-4213-a443-7a0da82b467b">



Age and MMSE Scores Trend:
There appears to be a general downward trend in MMSE scores as Age increases, indicating that older individuals tend to have lower MMSE scores, which may reflect a decline in cognitive function with age.
The distribution of lines suggests that this trend might be more pronounced for individuals diagnosed with Alzheimer's (e.g., lines in one color cluster lower in MMSE scores as Age increases).
BMI Distribution:
BMI does not exhibit a very clear relationship with MMSE scores in this plot. There is a spread of individuals with a wide range of BMIs across both high and low MMSE scores, suggesting that BMI alone might not be a strong predictor of cognitive function.
However, some patterns may exist in clustering or distribution between different Diagnosis statuses in terms of BMI values.
Variability in Cognitive Scores (MMSE):
There is significant variability in MMSE scores even among individuals of similar Age and BMI. This indicates that factors other than Age and BMI play an essential role in cognitive function, as measured by MMSE scores.
Diagnosis Status and Line Patterns:
The lines for different Diagnosis statuses (distinguished by color) appear to have different patterns. For example, individuals with Alzheimer's might show lower MMSE scores more frequently across various Age groups, while individuals without Alzheimer's may have a broader range of MMSE scores, including higher values.
This indicates that Alzheimer's diagnosis is associated with lower cognitive performance, though there is still substantial overlap, meaning that not all low MMSE scores correspond strictly to Alzheimer's diagnosis.
Potential Clusters and Overlaps:
While there are clusters of lines in certain regions (e.g., higher Age with lower MMSE scores), the overlap among lines suggests a complex relationship where Diagnosis, Age, and BMI interact. More variables or detailed clustering analyses may be needed for further differentiation.



## Milestones

- By the end of this week, three of the questions will be answered by various graphs
- Another three questions will be answered by the end of the next week
- And the last three questions will be answered by 26th of October or if sooner by, 2oth of October. 
