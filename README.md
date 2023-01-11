# Gutenberg-Books-Text-Classification.
1. **Objective**

    Split the data into training and testing partitions using a random sample of 5 books written by different authors from the Gutenberg Digital Library. After that,    experiment with various transformation techniques and classification methods to accurately classify these partitions.

2. **Data Transformation**

     Data transformation is critical because of the text classification problem; we have a series of texts and their corresponding labels. However, we cannot directly use text in our model. That text must be converted into numbers or number vectors. We also used algorithms on each transformation model (BOW, and TF-IDF, n-gram).
     
3. **Modelling**

    After applying supervised algorithms such as **Support Vector Machine**, **Decision Tree** and **KNN** and **Naïve Bayes** to each transformer we have done. We comparing the results from evaluation for each transformer Choosing the champion model based on high accuracy, low variance to overcome the problem of overfitting and underfitting, high scores and high bias from our evaluation results.
    
    **Champion Model**
    
![image](https://user-images.githubusercontent.com/45748269/211860914-3ed28612-35bf-4a74-afec-58323badb5ac.png)


      **we chose Naïve Bayes model on Bag of Words (BAG) transformer with accuracy 99%. Naïve Bayes is the winner**

  
![image](https://user-images.githubusercontent.com/45748269/211862935-1577a8ad-7942-4325-ac2c-72de16f79857.png)
