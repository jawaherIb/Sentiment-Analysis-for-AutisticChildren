# Sentiment Analysis for Autistic Children
## Problem Description 
Autistic people are members of our society who need support and care. Having an accurate sentiments analysis of such people helps us to improve their support and understanding, and to create a society that works for autistic people. Autistic people often have attention deficit hyperactivity disorder (ADHD), dyslexia, anxiety, depression, and epilepsy. This means they may find it hard to look after themselves and need help with daily life. Autism is not a medical condition with treatments or a "cure". But some people need support to help them with certain things.
However, learning about children's sentiments with autism poses a particular challenge facing the caregiver (such as parents, teachers, nurses, etc…). In fact, they usually have difficulty interpreting their certain facial expressions, emotions, or tone of voice. This hinders their social interactions and the development of their language and behavioral skills. Therefore, in this work we seek to address the following question: How people shall behave with the autistic people to they not feel socially discomfortable?
## Proposed Solution
Our proposed solution consists of proposing a system named “Society for Autistic People”. Anyone who has social interaction with a child with autism can use our system to upload a photo and/or video of the child with autism to learn about their feelings. This technology has the potential to change how we examine and monitor the development of children to develop their skills and understand their feelings with People who have social interactions with autistic people.
## Project Objectives
This project enables medical practitioners, parents, nurses, teachers, etc… to upload the facial images of the autistic children to have a quick diagnosis of their feelings/sentiments. In addition, our system presents for them some recommendations and advice to more understand autistic people and interact with them.

## Methodology
![image](https://github.com/jawaherIb/Sentiment-Analysis-for-AutisticChildren/assets/136590920/9a8537b6-d779-4c02-b040-ecd4b4d1b18c)
                                                 
                                                       Use Case Diagram 
## Used Dataset Description
This project uses an open dataset, which contains 830 images for autistic-children with different emotions. This dataset makes use of a collection of emotion-specific, cleaned photos of autistic kids and the duplicated images and the stock images have been removed. Then, dataset has been categorized into six facial emotions: anger, fear, joy, natural, sadness, and surprise. The six primary emotions used are shown in Figure below

![The six primary used emotions](https://github.com/jawaherIb/Sentiment-Analysis-for-AutisticChildren/assets/136590920/86320784-d4f9-4605-95fb-16160c9ba760)

This project used 758 images for training (Anger: 67, Fear: 30, Joy: 350, Natural: 48, Sadness: 200, Surprise: 63) and 72 images for testing (Anger: 3, Fear: 3, Joy: 42, Natural: 7, Sadness: 14, Surprise: 6).

## Data Preparation
In this work, we have used Python programming language because it is the most popular programming language for data science and machine learning.

## Model Building Phases
The model building process involves several steps, including:

1. Resampling
2. Data Splitting (Train and Test)
3. Data Scaling and Dimensionality Reduction
4. Logistic Regression
5. Support Vector Machines
6. Random Forest
7. Stacking Classifiers
8. Model Building
9. Recommendation Making

## System Prediction Cycle
![image](https://github.com/jawaherIb/Sentiment-Analysis-for-AutisticChildren/assets/136590920/3d015930-cff7-485e-806d-cdc5ac5f28f9)

## Model Prototype & Results

"Natural Child"

As shown in the following Short Video, if the picture represents a normal case, our model can predict a natural child’s emotion and the appropriate recommendations for his/her parents.


https://github.com/jawaherIb/Sentiment-Analysis-for-AutisticChildren/assets/136590920/33b752e7-8da7-4c87-87dc-9bcf7a805030



"Angry Child"

As shown in the following Short Video, if the picture represents an abnormal case, our model can predict an angry child’s emotion and the appropriate advice for his/her parents.


https://github.com/jawaherIb/Sentiment-Analysis-for-AutisticChildren/assets/136590920/631d0a27-07c8-46f8-b750-9294b6c91e82



"Frightened Child"

As shown in the following Short Video, if the picture represents an abnormal case, our model can predict a fear child’s class and the appropriate recommendations for his/her parents.


https://github.com/jawaherIb/Sentiment-Analysis-for-AutisticChildren/assets/136590920/583663e0-d2a9-41c7-8417-e3f6524d41b0



"Cheerful Child"

As illustrated in the following Video, if the picture represents an abnormal case, our model can predict a joy child’s class and the appropriate advice for his/her parents.


https://github.com/jawaherIb/Sentiment-Analysis-for-AutisticChildren/assets/136590920/f1531893-7854-4080-8d7b-c0fec6e6d33a



"Sadness Child"

As illustrated in the following Video, if the picture represents irregular case, our model can predict a sad child’s emotion and the appropriate recommendations for his/her parents.


https://github.com/jawaherIb/Sentiment-Analysis-for-AutisticChildren/assets/136590920/1a59599b-e4be-4531-b312-d210cf881f5f



"Surprised Child"

As illustrated in the following Video, if we have an abnormal case, our model can predict a surprised child’s emotion and the appropriate advice for his/her parents.


https://github.com/jawaherIb/Sentiment-Analysis-for-AutisticChildren/assets/136590920/4b50e45d-1018-4084-9ab7-ed96b787f75a





![image](https://github.com/jawaherIb/Sentiment-Analysis-for-AutisticChildren/assets/136590920/9388ae84-3f75-4ef0-9f7f-f57506363f10)
![image](https://github.com/jawaherIb/Sentiment-Analysis-for-AutisticChildren/assets/136590920/8d2d6b4c-b850-4cb6-880b-3c9d3e0de989)

## Model Performance Evaluation
The percentage of correct predictions is (precision) 93%.

The model(f1- score) is 87% accurate.


## Conclusion
In this work, we first defined the problem, the objectives, and the proposed solution after explaining the background. Next, we reviewed some existing works of literature similar to ours. Then, we analyzed our proposal and identified the functional and non-functional requirements and classified the end-users. After that, we designed the functions of our system through some UML diagrams. Next, we prepared data by resampling, splitting, scaling, and reducing its dimensionality by using a set of machine learning algorithms. We adopted then linear regression, SVM, random forest, and stacking classifier. After, we built our machine learning model used to make predictions. Finally, we evaluate our model by downloading some pictures representing normal and abnormal cases in predicting the different children’s emotions and presenting the appropriate recommendations for their parents.
In the future, we plan to develop our site and share it in order to achieve widespread use of different search engines. Furthermore, we hope to provide a highly accurate sentiment analysis results for autistic children.

### Due by
Jawaher Ibrahim Almotiran
### Supervised by:
Dr. Molka Lotfi Rekik
## Dataset Source 
From Kaggle Autistic Children Emotions - Dr. Fatma M. Talaat. (2023, February 16). Kaggle.
 
