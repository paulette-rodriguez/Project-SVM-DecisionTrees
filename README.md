Predicting Heart Disease Dataset by SVM and Decision Trees

Introduction:
* Commonly known as Cardiovascular Disease (CVD), heart diseases are groups of
disorders in the heart and blood vessels. CVDs are the number one cause of
death globally, taking an estimated 17.9 million lives each year, according
to the World Health Organization (WHO). The different groups of heart disease
vary from coronary heart disease, cerebrovascular disease, rheumatic heart
disease and others. According to the Centers of Disease Control and
Prevention (CDC), heart disease is the leading cause of death for men, women,
and people of most racial and ethnic groups in the United States with one
person dying every 37 seconds in the U.S. Statistically speaking that’s about
647,000 Americans dying from heart diseases each year. That’s a ratio of 1
in every 4 deaths.
Not only do CVDs take millions of lives every year, but it turns out that
it’s super expensive and costs the United States over $200 billion each year.
For example, the CDC has stated that heart disease cost the United States
about $219 billion each year from 2014 to 2015. Which included the cost of
health care services, medicines, and lost productivity due to death.

The Dataset:
* The Heart Disease dataset being used for this analysis project consists of
303 individual’s data. It contains 76 attributes, using a subset of only 14
of them. The “goal” field refers to the presence of heart disease in the
patient. The data is integer valued from 0, meaning no presence of heart
disease, to 4 with number 1-4 distinguishing presence of the disease. As
stated above, the dataset contains only 14 of the 76 total attributes.

Approach:
* The use of R Programming will be used to implement different classification
models on the dataset. The following classification models that will be
implemented on the set will be: SVM and Decision Trees.
These different classification models will be used to help predict accuracy
and useful output in determining the odds of getting heart disease based on
different risk factors.

Analysis & Results:
* In the following steps, I will be using SVM and Decision Trees classification
techniques to help predict heart disease. From the set of 14 attributes we
saw above, there are more important variables that come into play in the
prediction of an individual getting heart disease. The most important
variables to predict heart failure in an individual come from whether or not
there is a reversable defect in Thalassemia followed by whether or not there
is an occurrence of chest pain. Please note, target = 1,2,3,4 implies that
the person is suffering from heart disease and target = 0 implies that the
given individual is not suffering from the disease. The variable we want to
predict is “num” with a value 0 being less than 50% and value 1 being greater
than 50%.

Conclusion:
* Throughout this analysis and model comparison, we used 14 predictor variables
from the heart disease dataset to predict whether or not a patient had
presence of heart diseases. In order to do this, we used different models.
The first model we saw was SVM which gave us a pretty high accuracy of 89%
and 83%. Then, we used Decision Trees to visualize the data in a better way.
Using the method of Decision Trees, we were able to see an output of a high
accuracy from that as well. Hence, we can conclude that from the heart
disease data results the best variables that show presence of heart disease
are “num”, “cp”, “ca”, and “thal.”
Heart disease is one of the major concerns for people all around the world
till this day. With the help of some useful techniques that were used for
this analysis, such as SVM and Decision Trees, we were able to predict the
odds of getting heart disease based on various risk factors. It helped a lot
that these techniques were done using algorithms on a computer, since doing
some analysis like this would have be difficult to achieve manually.
