
# Model Accuracy Report

## 🔍 Training LogisticRegression...
**✅ Accuracy:** `0.8540`

| Class   | Precision | Recall | F1-score | Support |
|---------|-----------|--------|----------|---------|
| <=50K   | 0.88      | 0.93   | 0.91     | 7479    |
| >50K    | 0.73      | 0.59   | 0.66     | 2290    |
| **Overall Accuracy**     |        |        | **0.85**     | **9769**  |
| Macro Avg | 0.81    | 0.76   | 0.78     | 9769    |
| Weighted Avg | 0.85 | 0.85   | 0.85     | 9769    |

---

## 🔍 Training RandomForest...
**✅ Accuracy:** `0.8487`

| Class   | Precision | Recall | F1-score | Support |
|---------|-----------|--------|----------|---------|
| <=50K   | 0.89      | 0.91   | 0.90     | 7479    |
| >50K    | 0.69      | 0.64   | 0.66     | 2290    |
| **Overall Accuracy**     |        |        | **0.85**     | **9769**  |
| Macro Avg | 0.79    | 0.78   | 0.78     | 9769    |
| Weighted Avg | 0.84 | 0.85   | 0.85     | 9769    |

---

## 🔍 Training KNN...
**✅ Accuracy:** `0.8414`

| Class   | Precision | Recall | F1-score | Support |
|---------|-----------|--------|----------|---------|
| <=50K   | 0.88      | 0.91   | 0.90     | 7479    |
| >50K    | 0.68      | 0.61   | 0.64     | 2290    |
| **Overall Accuracy**     |        |        | **0.84**     | **9769**  |
| Macro Avg | 0.78    | 0.76   | 0.77     | 9769    |
| Weighted Avg | 0.84 | 0.84   | 0.84     | 9769    |

---

## 🔍 Training SVM...
**✅ Accuracy:** `0.8610`

| Class   | Precision | Recall | F1-score | Support |
|---------|-----------|--------|----------|---------|
| <=50K   | 0.88      | 0.94   | 0.91     | 7479    |
| >50K    | 0.76      | 0.59   | 0.66     | 2290    |
| **Overall Accuracy**     |        |        | **0.86**     | **9769**  |
| Macro Avg | 0.82    | 0.77   | 0.79     | 9769    |
| Weighted Avg | 0.85 | 0.86   | 0.85     | 9769    |

---

## 🔍 Training GradientBoosting...
**✅ Accuracy:** `0.8739`

| Class   | Precision | Recall | F1-score | Support |
|---------|-----------|--------|----------|---------|
| <=50K   | 0.89      | 0.95   | 0.92     | 7479    |
| >50K    | 0.79      | 0.62   | 0.70     | 2290    |
| **Overall Accuracy**     |        |        | **0.87**     | **9769**  |
| Macro Avg | 0.84    | 0.79   | 0.81     | 9769    |
| Weighted Avg | 0.87 | 0.87   | 0.87     | 9769    |

---

## 🏆 Best Model: `GradientBoosting`  
**✅ Best Accuracy:** `0.8739`  
**📦 Saved as:** `best_model.pkl`
