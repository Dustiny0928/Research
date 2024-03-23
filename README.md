# Exploring the Relationship Between Non-High-Density Lipoprotein Cholesterol to High-Density Lipoprotein Cholesterol Ratio (NHHR) and Sleep Disorders (OSA and Sleep Apnea) by using NHANES Data

This research aims to investigate the association between the non-high-density lipoprotein cholesterol to high-density lipoprotein cholesterol ratio (NHHR) and two common sleep disorders, obstructive sleep apnea (OSA) and insomnia, using data from the National Health and Nutrition Examination Survey (NHANES).

## Study Design

NHANES cycle: (Need to merge two cycles)
- 2005-2006
- 2006-2007

### Demographic Data Included
- Age
- Gender
- Race
- Marital status - Married, unmarried
- Education level (less than 9th grade, 9-11th grade, high school, some college, college graduate)
- Smoking status:
  - Never-smoker
  - Former smoker (smoking <100 cigarettes in the lifetime)
  - Yes (smoking ≥ 100 cigarettes in the lifetime)
- Alcohol consumption:
  - No alcohol use
  - 1-4 drinks per week
  - >4 drinks per week
- Physical activity:
  - Physically active
  - Physically inactive
- Dietary intake of cholesterol:
  - 24h recall survey
  - Total dietary cholesterol intake extracted from the total nutrient intake files using the mean amounts of two 24-h dietary recalls.
- BMI
- Blood pressure & Cholesterol
- History of diabetes:
  - Self-reported, physician diagnosis, or current insulin use
- History of hypertension:
  - Self-reported, physician diagnosis, or BP exceeded 140/90 mmHg
- Cholesterol - HDL
- Cholesterol - LDL, Triglyceride & Apolipoprotein (ApoB)
- Cholesterol - Total

### Questionnaire: Sleep Disorder (n=6139)
- How much sleep do you get (hours)
- How long to fall asleep
- How often do you snore
- How often do you snort/stop breathing?
- Ever told doctor had trouble sleeping?
- Ever told by doctor have sleep disorder?
- What was the sleep disorder?
  - Sleep apnea - n=201
  - Insomnia - n=78
  - Restless legs - n=25
  - Other - n=62
- How often have trouble falling asleep?
- How often wake up during the night?
- How often wake up too early in the morning?
- How often feel unrested during the day?
- How often feel overly sleepy during the day?
- How often did you not get enough sleep?
- How often take pills to help you sleep?
- How often have leg jerks while sleeping?
- How often have legs cramp while sleeping?
- Difficulty concentrating when tired?
- Difficulty remembering when tired?
- Difficulty eating when tired?
- Difficulty with a hobby when tired?
- Difficulty getting things done?
- Difficulty with finance when tired?
- Difficulty at work because tired?
- Difficulty on phone when tired?

### Literature search

**1. "The association between non-high-density lipoprotein cholesterol to high-density lipoprotein cholesterol ratio (NHHR) and prevalence of periodontitis among US adults: a cross-sectional NHANES study"**

- **Authors:** Hou K, Song W, He J, Ma Z
- **Journal:** Sci Rep. 2024 Mar 6;14(1):5558
- **DOI:** [10.1038/s41598-024-56276-y](https://doi.org/10.1038/s41598-024-56276-y)
- **PMID:** 38448487
- **PMCID:** PMC10918089

**Clinical feature included:** BMI, marital status, smoking, alcohol drinking, hypertension, hyperglycaemia, HDL-C, total cholesterol ⇒ NHHR.

This study uses logistic regression analysis, which demonstrated a positive association between NHHR and periodontitis.

**Conclusion:** There is a positive correlation between NHHR and increased prevalence of periodontitis.

**2. "The association between non-high-density lipoprotein cholesterol to high-density lipoprotein cholesterol ratio (NHHR) and risk of depression among US adults: A cross-sectional NHANES study"**

NHHR was calculated using the participant's lipid profiles. The equation was: NHHR = Non-HDL-C/HDL-C. Non-HDL-C=Total cholesterol (TC) - HDL-C

**3. "Genetic study of the causal effect of lipid profiles on insomnia risk: a Mendelian randomisation trial"**

- **Authors:** Gong, Q., Guo, C
- **Journal:** BMC Med Genomics 16, 325 (2023)
- **DOI:** [10.1186/s12920-023-01761-y](https://doi.org/10.1186/s12920-023-01761-y)

Genetic datasets of lipid profiles included: TG, ApoA-1, ApoB, LPA from the European population (from UK Biobank)

This MR study demonstrates elevated levels of ApoA-1 and LPA were causally associated with the risk of insomnia, suggesting that elevated ApoA-1 and LPA levels may contribute to a reduced risk of insomnia.

ApoA-1 is a protective factor of insomnia, which is a major protein skeleton of HDL (~70% of HDL structural proteins).

**4. "Insomnia symptoms Are Not associated with dyslipidaemia: A population-based study"**

LDL-C, triglycerides, HDL-C were selected from NHANES database.

Insomnia symptoms were not associated with dyslipidaemia, but receipt of sleeping pills in the setting of insomnia was associated with elevated LDL-C.

**5. "Insomnia symptom frequency and hypertension risk: a population-based study"**

- **Author:** Vozoris NT
- **Journal:** J Clin Psychiatry. 2014 Jun;75(6):616-23
- **DOI:** [10.4088/JCP.13m08818](https://doi.org/10.4088/JCP.13m08818)
- **PMID:** 25004185

12643 patients with sleep quality questions were selected from NHANES 2005-2008.

There were generally no significant positive associations between objectively measured systolic and diastolic hypertension and insomnia symptoms regardless of symptom frequency.

**6. "Obstructive sleep apnea (OSA) is associated with increased risk of early-onset sarcopenia and sarcopenic obesity: Results from NHANES 2015-2018"**

- **Authors:** Tao, X., Niu, R., Lu, W. et al.
- **Journal:** Int J Obes (2024)
- **DOI:** [10.1038/s41366-024-01493-8](https://doi.org/10.1038/s41366-024-01493-8)

Sample weights were taken into account. New sample weights were calculated by dividing the 2-year cycle sample weights by two according to the NHANES guidelines.

Participants were selected from two NHANES cycles: 2015-2016 and 2017-2018. A total of 19225 were included and final sample is N=3985.

**7. "Obstructive Sleep Apnea Risk is Associated with Severity of Metabolic Syndrome: NHANES 2015–2018"**

- **DOI:** [10.1097/JCN.0000000000000868](https://doi.org/10.1097/JCN.0000000000000868)

Multivariable apnoea prediction (MAP) index, an algorithm that uses frequency of sleep apnoea symptoms, BMI, age and gender to estimate the risk of OSA, is a validated screening tool for OSA risk.

**8. "Antimony and Sleep-related disorders: NHANES 2005-2008"**

The NHANES 2005-2006 and 2007-2008 are the only cycles where a complete questionnaire about sleep habit and disorders were performed, so that several outcomes could be defined. Two cycles are then merged together using the NCHS recommendations.

OSA: characterised according to Healthy People 2020 and was defined as any of the following:

- Doctor diagnosed sleep apnoea
- Snoring 3 or more nights per week
- Snorting, gasping or stopping breathing 3 or more nights per week
- OR (feeling excessively sleepy during the day 16-30 times per month despite sleeping around 7 or more hours per night on weekdays or work nights)

Sleep-onset latency: Categorised as normal (6-30 minutes/night), prolonged (>30 minutes/night), or short (≤ 5 minutes/night), which may be indicative of having a sleep disorder.

Sleep problems: Considered frequent if self-reported "often" or more (≥ 5 times/month) in response to any of the following questions from the NHANES sleep questionnaire:

- Have you ever told a doctor or other health professional that you have trouble sleeping?
- In the past month, how often did you have trouble falling asleep?
- In the past month, how often did you wake up during the night and had trouble getting back to sleep?
- In the past month, how often did you wake up too early in the morning and were unable to get back to sleep?

Day sleepiness considered frequent if self-reported “often” or more (≥ 5 times/month) in response to any of the following questions from the NHANES sleep questionnaire:

- “In the past month, how often did you feel unrested during the day, no matter how many hours of sleep you have had?”
- “In the past month, how often did you feel excessively or overly sleepy during the day?”.
