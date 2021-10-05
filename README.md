This notebook explores the Heart Disease dataset. And develops a model to predict positive and negative. I also tune the alpha by hand to maximize the accuracy.

Libraries:

Pandas

Numpy

Matplotlib

Sklearn

Algorithms:

Decision Tree

Understand the Dataset:

X:

ge: age in years

sex: sex (1 = male; 0 = female)

cp: chest pain type

-- Value 1: typical angina

-- Value 2: atypical angina

-- Value 3: non-anginal pain

-- Value 4: asymptomatic

trestbps: resting blood pressure (in mm Hg on admission to the hospital)

chol: serum cholestoral in mg/dl

fbs: (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)

restecg: resting electrocardiographic results

-- Value 0: normal

-- Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)

-- Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria

halach: maximum heart rate achieved 

exang: exercise induced angina (1 = yes; 0 = no)

oldpeak = ST depression induced by exercise relative to rest

slope: the slope of the peak exercise ST segment

-- Value 1: upsloping

-- Value 2: flat

-- Value 3: downsloping

ca: number of major vessels (0-3) colored by flourosopy

thal: 3 = normal; 6 = fixed defect; 7 = reversable defect

Y:

num: diagnosis of heart disease (angiographic disease status), so anything large than 0 means have heart disease

update y with only 0 and 1


