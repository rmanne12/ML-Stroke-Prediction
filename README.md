# ML-StrokePrediction Team 19

Members: Max Yuan, Ishan Kulkarni, Rohan Manne, Rahul Komatineni, Yoon Ji Cho

### Introduction:
Strokes are a medical emergency that occur when blood flow to the brain is stalled or interrupted, preventing brain cells from receiving oxygen and nutrients. Without proper blood flow, these cells begin dying within minutes, making recognition, transportation, and immediate treatment crucial to minimizing brain damage (Johns Hopkins Medicine, 2022).

According to the World Health Organization strokes were responsible for 11% of total deaths worldwide, making it the 2nd leading cause of death in 2019 (2022). It’s also a leading cause of long term adult disability among stroke survivors aged 65 years or older (Boehme et. al. 2017). Survivors are often left with complications that affect them for the rest of their lives including paralysis, weakness on one side of the body, memory loss, and speech problems.

### Problem definition:
Due to the urgent nature of this condition, prompt recognition and treatment is crucial to minimizing any debilitating effects. This can be difficult however, as symptoms are often mistaken for other conditions. Additionally, stroke symptoms present themselves differently in men and women, making it even more confusing to identify as it’s occurring. Our goal is to apply machine learning models to detect whether someone is likely to have a stroke based on various medical and lifestyle factors. Early detection would allow medical professionals more time to intervene and potentially improve a patient’s outcome.

### Methods:

Our proposal implements a model stacking machine learning algorithm with a Random Forest, SVM, KNN, and a vanilla Neural Network. The proposed algorithm would combine the predictions from the individual models and pass them through a meta-learner which will minimize the weaknesses and maximize the strengths of the individual machine learning algorithms used and then outputs a final prediction using a decision tree. Then, our team will analyze and compare the results from the stacked model against the results from the individual machine learning algorithms that were implemented.

The libraries that our team are planning on using to create the machine learning models include: Sci-Kit Learn, Tensorflow, Pandas, and NumPy.

### Potential Results/Discussion:

We intend to compare the results between the stacked model and the individual machine learning algorithms (SVM, KNN, Vanilla Neural Network, and Random Forest) using the metrics: accuracy, precision, and recall. Accuracy quantifies the proportion of measured positives to total data, precision measures the ratio of true positives to total predicted positives, and recall measures the proportion of true positives to total actual positives. We will compare and contrast the strengths and weaknesses of each model to find the model most capable of predicting if someone has had a stroke.

<p align="center">
References
</p>

Boehme, A. K., Esenwa, C., & Elkind, M. S. V. (2017, February 3). _Stroke risk factors, genetics, and prevention_. Circulation research. Retrieved October 8, 2022, from https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5321635/ 

_Stroke_. Johns Hopkins Medicine. (n.d.). Retrieved October 8, 2022, from https://www.hopkinsmedicine.org/health/conditions-and-diseases/stroke

World Health Organization. (n.d.). _The top 10 causes of death_. World Health Organization. Retrieved October 8, 2022, from https://www.who.int/news-room/fact-sheets/detail/the-top-10-causes-of-death 
