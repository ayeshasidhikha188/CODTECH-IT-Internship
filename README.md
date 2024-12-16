# CodTech IT Internship Repository

Welcome to the **CodTech IT Internship in Artificial Intelligence** Repository!  
This repository showcases two major projects that demonstrate practical applications of **Natural Language Processing (NLP)** and **Computer Vision**, two critical subfields of Artificial Intelligence. Each project focuses on solving real-world problems using cutting-edge AI techniques.

---

## **Task Three: Natural Language Processing (NLP) - Sentiment Analysis of Flipkart Product Reviews**

### Objective:
Analyze customer reviews for the *"YONEX MAVIS 350 Nylon Shuttle"* on Flipkart to:
1. **Classify reviews** as positive or negative.
2. **Extract insights** from negative reviews to identify common customer pain points, aiding product improvement strategies.

### Key Steps:
1. **Dataset**:
   - **Size**: 8,518 reviews.
   - **Attributes**: Includes *Rating*, *Review Text*, *Up Votes*, and *Down Votes*.

2. **Model Selection**:
   - **For faster training and decent accuracy**: Naive Bayes with Bag-of-Words (BoW).
   - **For higher accuracy**: 
     - Logistic Regression with BERT.
     - Random Forest with TF-IDF.

3. **Final Recommendation**:
   - **Logistic Regression with BERT** is the optimal choice due to:
     - **High accuracy** (F1 score).
     - **Efficient training times**.
     - **Minimal latency** for real-time applications.
   - This combination ensures a balance of performance and efficiency, making it ideal for deployment in practical scenarios.

---

## **Task Four: Computer Vision - Image Classification Using the MNIST Dataset**

### Objective:
Develop a model to classify handwritten digits (0-9) using the MNIST dataset. This enables accurate recognition of digits for potential automation in various industries.

### Key Steps:
1. **Dataset**:
   - **Size**: 372,000 images.
   - **Image Dimensions**: Each image is 28x28 pixels in grayscale.

2. **Approach**:
   - Train machine learning models to classify digits based on their pixel values.
   - Apply computer vision techniques to achieve high recognition accuracy.

3. **Outcome**:
   - The model demonstrated high accuracy in digit recognition, making it suitable for applications like automated data entry and digit-based systems.

---

## **Conclusion**

The projects in this repository highlight the versatility and power of Artificial Intelligence in solving diverse real-world challenges.

1. **Task Three** demonstrates the use of **NLP** for sentiment classification and extracting actionable insights to enhance customer experiences and guide product improvements.
2. **Task Four** showcases **Computer Vision** techniques for digit recognition, enabling automation in digit-based applications.

These tasks reflect the practical applications of AI in both text and image data domains, providing valuable solutions to modern-day challenges.

---

### **Repository Contents**
- `Task_Three_NLP_Flipkart_Reviews.ipynb`: Code and analysis for Task Three.
- `Task_Four_Computer_Vision_MNIST.ipynb`: Code and implementation for Task Four.

---

Feel free to explore the projects and gain insights into how AI can address real-world problems efficiently and effectively!
