# A-model-for-physician-evaluation
SSC2022 case1

# Abstract
Since the last century, many efforts have been spent developing the ability of a
health care system, focusing on patients in the intensive care unit (ICU). Traditionally
physicians participate in 360 evaluations by answering questions scoring
from 1 to 5, but this method fails to incorporate patient information and thus can
be biased. Assessment of physicians performance depends on various factors such
as professional knowledge level and behaviour competence, therefore, we seek
to develop a new model that includes patient information to evaluate physician
performance.

# Code
The R script and html output are inside the folder: raw_data, 
the original data is also located there.

# Output

![This is an image] (thepaper/classificationTree.png)


# Conclusion
We developed a machine learning model that predicts whether a given patient will survive, assigning
to a particular physician. From our analysis, we can conclude whether a patient is alive after
treatment can significantly affect the score of the physician.
In particular, the ’alive outcome’ variable is the most influential factor to a physicians’ score, but
most of the time, we can only forecast with a 70% correct rate. Also, the average scores on 360
evaluation which contains professional knowledge and behavioural competence score do not have
large impact on the ’alive outcome’. As a result, the reserve of professional knowledge is not the
necessary condition to save the patient. Another observation that worth mentioning is that whether
the patient is above 60 years old has a direct effect on death rates, corresponding to the common sense.
Future work will include analysis of categorical variables, such as further distinguishing whether the
physician is bedside or non-bedside to refine our model.
