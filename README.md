## 🧠 Parkinson’s Disease Detection Using Machine Learning

### 📌 Situation

Early detection of Parkinson’s disease was required using a **small biomedical voice dataset**, where **overfitting** was a major concern due to limited samples.

---

### ⚙️ Steps / Actions Performed

1. Removed non-informative identifier columns from the dataset
2. Performed **Exploratory Data Analysis (EDA)** to compare voice features between:

   * Healthy individuals
   * Parkinson’s patients
3. Analyzed key biomedical voice features such as:

   * Jitter
   * Shimmer
   * Fundamental frequency measures
4. Scaled numerical features using **StandardScaler** to ensure equal feature contribution
5. Applied **feature selection** techniques to reduce redundancy and improve generalization
6. Used **Stratified Train-Test Split** to preserve class distribution
7. Trained a **Support Vector Machine (SVM)** classification model
8. Tuned model parameters to reduce overfitting

---

### 📊 Model Evaluation

* Evaluation Metric: **Accuracy Score**
* Training Accuracy: **Above 85%**
* Testing Accuracy: **Above 85%**
* Balanced performance indicated good generalization and minimal overfitting

---

### 🔍 One Key Finding

Parkinson’s patients exhibit **higher voice instability**, reflected by **increased jitter and shimmer values**, making these features strong indicators for early detection.

---

### 🧾 Conclusion

The SVM model effectively classified Parkinson’s disease using voice-based biomedical features, achieving strong accuracy while maintaining generalization despite a small dataset.

---


```markdown
### Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
