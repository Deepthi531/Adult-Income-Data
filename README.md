# Adult-Income-Data
Objective:

The main objective of the dataset is to classify people earning <=50k or >50k based on several explanatory factors affecting the income of a person like Age, Occupation, Education, etc.

A person's annual income depends on many factors. Visually, it is influenced by the person's education level, age, gender, occupation, etc. 

This is a frequently cited Logistic Regression dataset. I encountered this during my course. This is a good entry-level example of data preprocessing and machine learning, so I'd like to share it here.

The dataset contains 15 columns : They are

1)  age: The age of an individual
2)  workclass: A general term to represent the employment status of an individual.

          * Private
          * Self-emp-not-inc
          * Self-emp-inc
          * Federal-gov
          * Local-gov
          * State-gov
          * Without-pay
          * Never-worked.
3)  fnlwgt: Final weight. In other words, this is the number of people the census believes.
4)  education: The highest level of education achieved by an individual.

           * Bachelors
           * Some-college
           * 11th
           * HS-grad
           * Prof-school
           * Assoc-acdm
           * Assoc-voc
           * 9th
           * 7th-8th
           * 12th
           * Masters
           * 1st-4th
           * 10th
           * Doctorate
           * 5th-6th
           * Preschool
5)  education-num: The highest level of education achieved in numerical form.
6)  marital-status: Marital status of an individual.

           * Married-civ-spouse
           * Divorced
           * Never-married
           * Separated
           * Widowed
           * Married-spouse-absent
           * Married-AF-spouse
7)  occupation: the general type of occupation of an individual

           * Tech-support
           * Craft-repair
           * Other-service
           * Sales
           * Exec-managerial
           * Prof-specialty
           * Handlers-cleaners
           * Machine-op-inspct
           * Adm-clerical
           * Farming-fishing
           * Transport-moving
           * Priv-house-serv
           * Protective-serv
           * Armed-Forces
8)  relationship: Represents what this individual is relative to others. For example an individual could be a Husband. Each entry only has one relationship attribute and is somewhat redundant with marital status. We might not make use of this attribute at all

           * Wife
           * Own-child
           * Husband
           * Not-in-family
           * Other-relative
           * Unmarried.	
9)  race: Descriptions of an individual’s race

           * White
           * Asian-Pac-Islander
           * Amer-Indian-Eskimo
           * Other
           * Black
10) sex: the biological sex of the individual

           * Male
           * Female
11) capital-gain: capital gains for an individual
12) capital-loss: capital loss for an individual
13) hours-per-week: the hours an individual has reported to work per week
14) native-country: country of origin for an individual

           * United-States
           * Cambodia
           * England
           * Puerto-Rico
           * Canada
           * Germany
           * Outlying-US(Guam.USVI.etc) 
           * India 
           * Japan 
           * Greece 
           * South
           * China 
           * Cuba 
           * Iran
           * Honduras 
           * Philippines 
           * Italy
           * Poland
           * Jamaica 
           * Vietnam 
           * Mexico 
           * Portugal
           * Ireland 
           * France 
           * Dominican-Republic
           * Laos
           * Ecuador 
           * Taiwan 
           * Haiti 
           * Columbia
           * Hungary 
           * Guatemala 
           * Nicaragua 
           * Scotland 
           * Thailand 
           * Yugoslavia
           * El-Salvador
           * Trinadad&Tobago
           * Peru
           * Hong 
           * Holand-Netherlands	
15) salary: whether or not an individual makes more than $50,000 annually.

           * <=50k
           * >50k

The Targeted field is "salary"
The salary is divide into two classes: <=50K and >50K
And all the remaining 14 attributes are the demographics and these features are used to describe a person

We can explore the possibility in predicting salary/income level based on the individual’s personal information.
