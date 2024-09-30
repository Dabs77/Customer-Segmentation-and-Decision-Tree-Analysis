# Customer Segmentation and Decision Tree Analysis

### Authors:
- **Anamaria Leguizamón Alarcón**
- **Juan David Lopez Becerra**
- **Daniel Andrés Becerra Sierra**

---

## Project Overview

This repository contains a comprehensive notebook for **customer segmentation** using the **K-Means algorithm**, complemented by a **decision tree model** for enhanced understanding of the identified customer segments.

### 📊 **Project Objective**

The goal of this project is to apply advanced segmentation techniques to group customers based on behavioral and demographic data. By creating **homogeneous groups**, companies can tailor their marketing strategies, enhancing customer satisfaction and loyalty. 

The dataset includes key variables such as:
- **Age**
- **Annual Income**
- **Purchase Frequency**
- **Customer Satisfaction**
- **Total Spending**
- ... and more!

We utilize the **elbow method** to determine the optimal number of clusters, followed by **K-Means** to segment customers into **7 distinct groups**.

---

## 🔑 **Key Features**

### 1. **Descriptive Analysis & Visualization**
We explore dataset variables using a series of visualizations that reveal patterns in customer behavior. Some examples include:
- The relationship between **annual income** and **total spending**.
- How **purchase frequency** correlates with **average purchase value**.

### 2. **Data Transformation**
To ensure the dataset is optimized for the K-Means algorithm:
- **Numerical variables** are standardized.
- **Categorical variables** are one-hot encoded.

### 3. **K-Means Segmentation**
The K-Means algorithm is applied to divide the customer base into **7 clusters**. Each cluster is analyzed in detail to uncover unique customer characteristics and behaviors. 

### 4. **Prediction with Decision Trees**
A **decision tree model** is trained to predict the group membership of customers based on the previously identified clusters. This helps to interpret which features have the most influence on the segmentation process.

### 5. **Model Improvements & Evaluation**
To address issues such as overfitting and improve the model’s performance:
- **Undersampling** was applied to balance the dataset.
- **Tree pruning** was used to reduce model complexity and enhance interpretability.

---

## 🚀 **Use Case**

This project is particularly valuable for businesses aiming to:
- **Optimize marketing strategies** by understanding customer groups.
- Focus resources on the **most valuable customer segments**.
- Design **targeted promotions** to enhance customer experience.
  
Through this segmentation, businesses can unlock new **market opportunities**, identify **customer preferences**, and develop more **personalized approaches**.

---

## 📁 **Repository Structure**
- `notebook.ipynb`: The main notebook with all analysis, segmentation, and decision tree modeling.
- `report`: The report with the conclusions and different analyses.
- `README.md`: Project overview and instructions (this file).

---

### 📧 **Contact**
For questions or collaboration, feel free to reach out to the authors via GitHub.
