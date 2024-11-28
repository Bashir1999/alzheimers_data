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
 * How do the average values of key lifestyle, cognitive, and demographic variables differ between individuals diagnosed with Alzheimer's (Diagnosis = 1) and those not diagnosed (Diagnosis = 0)? -- DONE
 * What is the relationship between head injuries and Alzheimer's? -- DONE
 * How do MMSE scores vary with Age and BMI across different diagnosis statuses? -- DONE
 * What is the effect of alcohol consumption on sleep quality among Alzheimer’s patients? -- DONE
 * How do physical activity interact to affect Alzheimer’s diagnosis? -- DONE
 * How do diet interact to affect Alzheimer’s diagnosis? -- DONE
 * What is the impact of memory complaints on Alzheimer’s diagnosis? -- DONE
 * Avg Cholesterol by Age Group -- DONE
 * What is the relationship between Alcohol Consumption and Sleep Quality on Depressed and Non-depressed patients? -- DONE
 * How does alcohol consumption vary by education level, and how does it differ across racial or ethnic groups within each education level? -- DONE
 * How does the combination of smoking status and cholesterol levels influence the prevalence of cardiovascular disease (CVD)? -- DONE
 * How does physical activity level vary with depression status, and does it differ between males and females? -- DONE

## Sketches


### Distribution of Age by Alzheimer's Diagnosis:
This graph can answer the first question: What is the distribution of Alzheimer's diagnosis across different age groups?
By using variables such as age and percentage of those who are diagnosed, we can see which age group has the highest percentage of Azheimer's diagnosis, considering the fact, that there might be more people in one age group then other, which is why it is better to use average. 

![image](https://github.com/user-attachments/assets/443e338c-9790-4c94-94da-c65779228977)



  
<br /> ### Memory Complaints Progression with Age:
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

<img width="804" alt="Screenshot 1403-08-30 at 14 34 00" src="https://github.com/user-attachments/assets/fa6204db-59c0-4949-8299-61d4741f10d6">


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

<img width="837" alt="Screenshot 1403-08-30 at 14 38 03" src="https://github.com/user-attachments/assets/d9968d00-dc3f-4c5c-967f-20fcacb570e9">



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


<img width="959" alt="Screenshot 1403-08-30 at 14 47 33" src="https://github.com/user-attachments/assets/f5e67939-d405-4be5-8541-be240952bc3e">



Inverse Relationship Between Alcohol Consumption and Sleep Quality: The graph shows a downward trend, suggesting that as alcohol consumption increases, sleep quality tends to decrease. This inverse relationship may indicate that higher levels of alcohol intake have a negative impact on sleep quality.

Distribution of Depression Status: The two colors (orange and blue) represent different Depression statuses (0 and 1). It appears that data points for both depression groups are intermingled across all levels of Alcohol Consumption and Sleep Quality. However, there might be patterns worth exploring, such as potential clusters or distribution differences between these two groups.

Clustering of Data Points at Low Alcohol Consumption: A noticeable clustering of data points can be seen on the left side of the x-axis (lower values of Alcohol Consumption). This may indicate that a significant number of individuals have relatively low alcohol intake levels, with varying levels of Sleep Quality.

Overlapping Data Points: The overlapping of blue and orange data points in many regions suggests that both groups (with and without depression) experience a range of sleep qualities and alcohol consumption behaviors. This overlap might indicate that the Depression status does not solely depend on Alcohol Consumption or Sleep Quality.





How do MMSE scores vary with Age and BMI across different diagnosis statuses? (Sample 100 Data Points)

https://vizhub.com/Bashir1999/mmse-bmi


<img width="762" alt="Screenshot 1403-08-30 at 14 50 51" src="https://github.com/user-attachments/assets/31b110eb-cdf9-40c4-9065-aa3bb09a4e0e">


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




How do the average values of key lifestyle, cognitive, and demographic variables differ between individuals diagnosed with Alzheimer's (Diagnosis = 1) and those not diagnosed (Diagnosis = 0)
https://vizhub.com/Bashir1999/radialchart

<img width="602" alt="Screenshot 1403-08-30 at 14 56 08" src="https://github.com/user-attachments/assets/60dd0080-ccbb-4ab7-bc32-d9df1fbb89a3">



Sleep Quality Difference:
There is a noticeable difference in the SleepQuality scores between individuals with a Diagnosis of 1 (orange) and those with a Diagnosis of 0 (blue). The orange line extends significantly higher, suggesting that those diagnosed with Alzheimer's tend to have better average SleepQuality scores compared to those not diagnosed with the disease.
This result might be unexpected or indicate data nuances, such as differences in sleep perception, measurement errors, or a confounding relationship worth further exploration.

Physical Activity:
There is a slight difference in PhysicalActivity between the groups, with the orange line (Diagnosis 1) slightly higher than the blue line (Diagnosis 0). This suggests that individuals diagnosed with Alzheimer's might have marginally higher average physical activity.
However, this difference appears small, indicating that physical activity levels between the two groups do not differ dramatically in this dataset.

BMI and Age:
The BMI and Age values for both groups appear to be relatively similar, with minimal differences in the chart. This suggests that, in this dataset, there is no significant variation in these demographic factors between individuals diagnosed with Alzheimer's and those without the diagnosis.
If there are differences, they are subtle, indicating that these factors alone may not be the primary distinguishing characteristics.

MMSE Scores:
There is a clear distinction in MMSE (Mini-Mental State Examination) scores between the groups. The line for Diagnosis 0 (blue) is higher than Diagnosis 1 (orange), indicating that individuals not diagnosed with Alzheimer's tend to have higher average cognitive function scores compared to those diagnosed.
This aligns with the expectation that Alzheimer's is associated with cognitive decline, as reflected in lower MMSE scores.



How does alcohol consumption vary by education level, and how does it differ across racial or ethnic groups within each education level?

https://vizhub.com/Bashir1999/alcohol_education


<img width="956" alt="Screenshot 1403-08-30 at 14 59 51" src="https://github.com/user-attachments/assets/252825d6-58b6-4ba2-9b2f-2514c5b624c3">



Education Levels: There are four levels represented: None, High School, Bachelor's, and Higher.
Alcohol Consumption (x-axis): The horizontal axis represents the extent of alcohol consumption, with wider bars indicating higher consumption.
Racial/Ethnic Groups (Color Segments): Different colors indicate the proportions of alcohol consumption attributable to various racial or ethnic groups (e.g., Caucasian, African American, Asian, and Other).
Key Observations:
For those with no education, the majority of alcohol consumption appears to come from Caucasian and African American groups.
Among individuals with a high school education, there is a more diverse distribution, with significant consumption from all represented racial groups.
For bachelor's degree holders, consumption is largely driven by the Caucasian group, with smaller contributions from others.
Individuals with higher education tend to have a varied but noticeably concentrated alcohol consumption in the Caucasian and Asian groups.



How does the combination of smoking status and cholesterol levels influence the prevalence of cardiovascular disease (CVD)?


https://vizhub.com/Bashir1999/smokingcvd


<img width="956" alt="Screenshot 1403-08-30 at 15 13 28" src="https://github.com/user-attachments/assets/a1a5450a-e934-4eab-ac0b-e9134b1b03c9">



Among smokers (Yes), there is a substantial proportion of individuals with higher cholesterol levels who have CVD (indicated by the orange segment), suggesting a higher risk of CVD with increased cholesterol levels among smokers.
Among non-smokers (No), a relatively large orange segment is also observed as cholesterol levels increase, though there is also a significant portion of individuals without CVD (blue segment).
Overall, CVD prevalence (orange bars) appears to be higher with increasing cholesterol levels, more pronounced among smokers compared to non-smokers.



How does physical activity level vary with depression status, and does it differ between males and females?

https://vizhub.com/Bashir1999/depressionphysical


<img width="955" alt="Screenshot 1403-08-30 at 15 16 24" src="https://github.com/user-attachments/assets/b481b250-4c2b-42fc-89e9-824d70d679c9">


Among those with no depression, both males and females appear to engage in varying levels of physical activity. However, females generally show higher physical activity levels compared to males, as indicated by the longer orange segment on the right.
Among individuals with depression, there is generally lower physical activity observed, and the majority of this group is male (indicated by the blue segment).
Insights:
Physical Activity and Depression: Lower physical activity levels appear to be associated with individuals experiencing depression. Those without depression tend to engage in higher physical activity levels.
Gender Differences: Among individuals with no depression, females tend to be more physically active than males. However, among those with depression, males dominate the lower end of physical activity levels, which may suggest a stronger association between lower physical activity and depression in males.




Impact of Age on Functional Assessment:

https://vizhub.com/Bashir1999/functionalassessment

<img width="826" alt="Screenshot 1403-08-30 at 14 26 53" src="https://github.com/user-attachments/assets/ea8cd6aa-254a-47ee-8ecc-0ad968b8e4d8">

Consistency Across Ages:

The average FunctionalAssessment remains relatively stable across the age range of 60 to 90.
This suggests that age does not have a significant influence on the FunctionalAssessment variable.
Fluctuations:

Small fluctuations are observed between different ages, indicating some degree of variability in the average FunctionalAssessment values for certain age groups.
These fluctuations might be due to sample size or external factors affecting the FunctionalAssessment values for specific ages.
Peaks and Valleys:

Minor peaks and valleys in the graph, such as those around ages 63, 78, and 85, may highlight anomalies or unique behavior within those age groups.
This could warrant a closer investigation to determine the causes (e.g., external interventions or conditions specific to these age groups).
Overall Range:

The FunctionalAssessment values generally fall between 4 and 6, indicating a narrow range of variation.
This implies a consistent measure of functionality assessment irrespective of age, with no outliers visible.
No Significant Trend:

There is no upward or downward trend across the age spectrum, which suggests that the relationship between age and FunctionalAssessment is likely weak or non-linear.


Responsive Plots:

https://vizhub.com/Bashir1999/responsivep



