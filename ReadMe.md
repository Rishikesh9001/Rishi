Project Name : Heart Disease Analysis
Table Contents :
	1) Age: age of the patient [years]
	
	
	2) Sex: sex of the patient [M: Male, F: Female]
	3) ChestPainType: chest pain type [TA: Typical Angina, ATA: Atypical 	Angina, NAP: Non-Anginal Pain, ASY: Asymptomatic]
	4) RestingBP: resting blood pressure [mm Hg]
	5) Cholesterol: serum cholesterol [mm/dl]
	6) FastingBS: fasting blood sugar [1: if FastingBS > 120 mg/dl,0:otherwise]
	7) RestingECG: resting electrocardiogram results [Normal: Normal,ST: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV), LVH: showing probable or definite left ventricular hypertrophy by Estes' criteria]
	8) MaxHR: maximum heart rate achieved [Numeric value between 60 and 202]
	9) ExerciseAngina: exercise-induced angina [Y: Yes, N: No]
	10) Oldpeak: oldpeak = ST [Numeric value measured in depression]
	11) ST_Slope: the slope of the peak exercise ST segment [Up:upsloping, Flat: flat, Down: downsloping]
	12) HeartDisease: output class [1: heart disease, 0: Normal]

Pandas Methods which are used in these project :
	. head(),tail()
	. isna(),sum()
	. info()
	. describe()
	. value_counts()
	. quantile()

Graph which are used : (plotting i have used matplotlib.pyplot and seaborn)
	. Countplot
	. Pie Chart
	. Bar graph
	. line Plot
	. Box Plot

Conclusion : 
	. Dataset has 918 peoples data with there medical health.
	. 508 people are suffering from heart Heart Disease with 458 are Male
		and 50 female.
	. There are average of 53.5 years old people with the youngest one is 28 and oldest one is 77.
	. There are 285 prople which have Normal ECG but they still suffer from the Heart disease.
	. 54.03% of people they suffer from ASY Chest pain .
	. There is a positive corrilation with respect to Age and ST_Slope.

Result : 
	. Most of the male suffer from heart disease.
	. Even if you have normal ECG you can still suffer from heart disease.
	. More then half of the people have ASY Chest pain type.
