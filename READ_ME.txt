READ ME


In my data collection, I gathered XPT files from NHANES database of national health from their 2017-2018 collection published in the year of 2020. The data was converted into a csv file, where I then conducted analysis. This analysis can be found in "Data_processing.pdf" while the research can be reproduced in the "data_analysis.Rmd" which is an R file. 

health.csv is the csv file with compiled data from the 4 XPT files.
BPX_J.XPT data is on blood pressure.
DEMO_J.XPT is data on demographics.
DIQ_J.XPT is data on diabetes.
BMX_J.XPT is data on body measures.



This has 4 different files combined into one. This here will help understand all of the notation used across all files. For the csv file, the notation will be listed following these 4 documentations.

---------------------------------------


FOR THE DEMOGRAPHICS DATA -- DEMO_J.XPT:


SEQN - Respondent sequence number
SDDSRVYR - Data release cycle
RIDSTATR - Interview/Examination status
RIAGENDR - Gender
RIDAGEYR - Age in years at screening
RIDAGEMN - Age in months at screening - 0 to 24 mos
RIDRETH1 - Race/Hispanic origin
RIDRETH3 - Race/Hispanic origin w/ NH Asian
RIDEXMON - Six month time period
RIDEXAGM - Age in months at exam - 0 to 19 years
DMQMILIZ - Served active duty in US Armed Forces
DMQADFC - Served in a foreign country
DMDBORN4 - Country of birth
DMDCITZN - Citizenship status
DMDYRSUS - Length of time in US
DMDEDUC3 - Education level - Children/Youth 6-19
DMDEDUC2 - Education level - Adults 20+
DMDMARTL - Marital status
RIDEXPRG - Pregnancy status at exam
SIALANG - Language of SP Interview
SIAPROXY - Proxy used in SP Interview?
SIAINTRP - Interpreter used in SP Interview?
FIALANG - Language of Family Interview
FIAPROXY - Proxy used in Family Interview?
FIAINTRP - Interpreter used in Family Interview?
MIALANG - Language of MEC Interview
MIAPROXY - Proxy used in MEC Interview?
MIAINTRP - Interpreter used in MEC Interview?
AIALANGA - Language of ACASI Interview
DMDHHSIZ - Total number of people in the Household
DMDFMSIZ - Total number of people in the Family
DMDHHSZA - # of children 5 years or younger in HH
DMDHHSZB - # of children 6-17 years old in HH
DMDHHSZE - # of adults 60 years or older in HH
DMDHRGND - HH ref person's gender
DMDHRAGZ - HH ref person's age in years
DMDHREDZ - HH ref person's education level
DMDHRMAZ - HH ref person's marital status
DMDHSEDZ - HH ref person's spouse's education level
WTINT2YR - Full sample 2 year interview weight
WTMEC2YR - Full sample 2 year MEC exam weight
SDMVPSU - Masked variance pseudo-PSU
SDMVSTRA - Masked variance pseudo-stratum
INDHHIN2 - Annual household income
INDFMIN2 - Annual family income
INDFMPIR - Ratio of family income to poverty





---------------------------------------

FOR THE BMX_J.XPT file, aka Blood Pressure:

SEQN - Respondent sequence number
PEASCCT1 - Blood Pressure Comment
BPXCHR - 60 sec HR (30 sec HR * 2)
BPAARM - Arm selected
BPACSZ - Coded cuff size
BPXPLS - 60 sec. pulse (30 sec. pulse * 2)
BPXPULS - Pulse regular or irregular?
BPXPTY - Pulse type
BPXML1 - MIL: maximum inflation levels (mm Hg)
BPXSY1 - Systolic: Blood pres (1st rdg) mm Hg
BPXDI1 - Diastolic: Blood pres (1st rdg) mm Hg
BPAEN1 - Enhancement used first reading
BPXSY2 - Systolic: Blood pres (2nd rdg) mm Hg
BPXDI2 - Diastolic: Blood pres (2nd rdg) mm Hg
BPAEN2 - Enhancement used second reading
BPXSY3 - Systolic: Blood pres (3rd rdg) mm Hg
BPXDI3 - Diastolic: Blood pres (3rd rdg) mm Hg
BPAEN3 - Enhancement used third reading
BPXSY4 - Systolic: Blood pres (4th rdg) mm Hg
BPXDI4 - Diastolic: Blood pres (4th rdg) mm Hg
BPAEN4 - Enhancement used fourth reading


---------------------------------------

For the Body Measures Data -- BMX_J.XPT:

SEQN - Respondent sequence number
BMDSTATS - Body Measures Component Status Code
BMXWT - Weight (kg)
BMIWT - Weight Comment
BMXRECUM - Recumbent Length (cm)
BMIRECUM - Recumbent Length Comment
BMXHEAD - Head Circumference (cm)
BMIHEAD - Head Circumference Comment
BMXHT - Standing Height (cm)
BMIHT - Standing Height Comment
BMXBMI - Body Mass Index (kg/m**2)
BMXLEG - Upper Leg Length (cm)
BMILEG - Upper Leg Length Comment
BMXARML - Upper Arm Length (cm)
BMIARML - Upper Arm Length Comment
BMXARMC - Arm Circumference (cm)
BMIARMC - Arm Circumference Comment
BMXWAIST - Waist Circumference (cm)
BMIWAIST - Waist Circumference Comment
BMXHIP - Hip Circumference (cm)
BMIHIP - Hip Circumference Comment

---------------------------------------

Diabetes -- DIQ_J.XPT:

SEQN - Respondent sequence number
DIQ010 - Doctor told you have diabetes
DID040 - Age when first told you had diabetes
DIQ159 - CHECK ITEM
DIQ160 - Ever told you have prediabetes
DIQ170 - Ever told have health risk for diabetes
DIQ172 - Feel could be at risk for diabetes
DIQ175A - Family history
DIQ175B - Overweight
DIQ175C - Age
DIQ175D - Poor diet
DIQ175E - Race
DIQ175F - Had a baby weighed over 9 lbs. at birth
DIQ175G - Lack of physical activity
DIQ175H - High blood pressure
DIQ175I - High blood sugar
DIQ175J - High cholesterol
DIQ175K - Hypoglycemic
DIQ175L - Extreme hunger
DIQ175M - Tingling/numbness in hands or feet
DIQ175N - Blurred vision
DIQ175O - Increased fatigue
DIQ175P - Anyone could be at risk
DIQ175Q - Doctor warning
DIQ175R - Other, specify
DIQ175S - Gestational diabetes
DIQ175T - Frequent urination
DIQ175U - Thirst
DIQ175V - Craving for sweet/eating a lot of sugar
DIQ175W - Medication
DIQ175X - Polycystic ovarian syndrome
DIQ180 - Had blood tested past three years
DIQ050 - Taking insulin now
DID060 - How long taking insulin
DIQ060U - Unit of measure (month/year)
DIQ065 - CHECK ITEM
DIQ070 - Take diabetic pills to lower blood sugar
DIQ229 - CHECK ITEM
DIQ230 - How long ago saw a diabetes specialist
DIQ240 - Is there one Dr you see for diabetes
DID250 - Past year how many times seen doctor
DID260 - How often check blood for glucose/sugar
DIQ260U - Unit of measure (day/week/month/year)
DIQ275 - Past year Dr checked for A1C
DIQ280 - What was your last A1C level
DIQ291 - What does Dr say A1C should be
DIQ295 - CHECK ITEM
DIQ300S - What was your recent SBP
DIQ300D - What was your recent DBP
DID310S - What does Dr say SBP should be
DID310D - What does Dr say DBP should be
DID320 - What was most recent LDL number
DID330 - What does Dr say LDL should be
DID341 - Past year times Dr check feet for sores
DID350 - How often do you check your feet
DIQ350U - Unit of measure (day/week/month/year)
DIQ360 - Last time had pupils dilated for exam
DIQ080 - Diabetes affected eyes/had retinopathy

---------------------------------------

The CSV file which was processed:

Race - Ethnicity of person
Sex - Sex of person
Age - How old a person is, with 0 being just born
PULSE_PM - Pulse in beats per minute
PULSE_TYPE - If one's heartbeat is regular or irregular
BLD_PRE_S - Blood pressure systolic readings
BLD_PRE_D - Blood pressure dyastolic readings
DIABETES - If one is diagnosed with diabetes
