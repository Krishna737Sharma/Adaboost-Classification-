# Adaboost Classification on UCI Zoo Dataset  

## Objective  
To implement and evaluate the Adaboost classifier for multi-class classification using the UCI Zoo dataset. The implementation includes creating the Adaboost algorithm from scratch for binary classification and applying the One-vs-All technique for multi-class classification. Results are compared with Scikit-learn’s implementation.

---

## Tasks  

### **Task 1: Load the Dataset**  
- Loaded the UCI Zoo dataset from [UCI Zoo Dataset](https://archive.ics.uci.edu/dataset/111/zoo).  

### **Task 2: Handle Missing or Duplicate Values**  
- Checked for missing or duplicate values.  
- Handled them appropriately by dropping duplicates and imputing missing values if any.  

### **Task 3: Class Distribution**  
- Visualized the class distribution using a bar plot.  

### **Task 4: Data Splitting**  
- Split the dataset into training (80%) and test (20%) sets.  

### **Task 5: Adaboost Implementation (Binary Classification)**  
- Implemented Adaboost from scratch for binary classification.  
- Used decision tree stumps (`DecisionTreeClassifier` with max depth = 1) as the base estimator.  
- Tuned the number of base estimators for optimal performance.  

### **Task 6: One-vs-All Multi-Class Classification**  
- Trained 7 binary Adaboost classifiers for the 7 classes using the One-vs-All technique.  
- Predicted the test set class labels by choosing the class corresponding to the maximum weighted sum of predictions across the 7 classifiers.  

### **Task 7: Compute Classification Metrics**  
- Computed **accuracy**, **precision**, and **recall** for the from-scratch Adaboost implementation.  

### **Task 8: Classification with Scikit-learn’s Adaboost**  
- Used Scikit-learn's `OneVsRestClassifier` with `AdaBoostClassifier` as the base estimator for classification.  

### **Task 9: Performance Comparison**  
- Compared the performance of the from-scratch Adaboost implementation with Scikit-learn’s implementation.  

---

## Results  

### **Performance Metrics (From-Scratch Implementation)**  
- **Accuracy**: `<value>`  
- **Precision**: `<value>`  
- **Recall**: `<value>`  

### **Performance Metrics (Scikit-learn Implementation)**  
- **Accuracy**: `<value>`  
- **Precision**: `<value>`  
- **Recall**: `<value>`  

---

## Visualizations  

- **Bar Plot**: Class distribution of the dataset.  
- **Comparison Table**: Metrics comparison between the from-scratch and Scikit-learn implementations.  

---

## How to Run  

1. Install required libraries:  
   ```bash
   pip install numpy pandas matplotlib scikit-learn
