# Scikit-Learn & ML Pipeline Construction

[&larr; Back to Dashboard](../../index.html)

## Requirements

### Read Scikit-Learn User Guide on Pipelines & Preprocessing
**Resource:** [https://scikit-learn.org/stable/modules/compose.html](https://scikit-learn.org/stable/modules/compose.html)

**Acceptance Criteria:**
- [ ] Read Pipeline and ColumnTransformer documentation
- [ ] Understand how to chain preprocessing + model
- [ ] Know how to use make_pipeline and Pipeline

**Deliverable:** Notes with pipeline examples

---

### Complete Kaggle Intermediate Machine Learning Course
**Resource:** [https://www.kaggle.com/learn/intermediate-machine-learning](https://www.kaggle.com/learn/intermediate-machine-learning)

**Acceptance Criteria:**
- [ ] Complete all tutorials and exercises
- [ ] Learn about missing values, categorical variables, pipelines
- [ ] Submit predictions to exercise competitions

**Deliverable:** Kaggle Learn completion badge

---

### Build automated data imputation, scaling (StandardScaler), & encoding pipelines
**Resource:** *(Internal / See study guide below)*

**Acceptance Criteria:**
- [ ] Build Pipeline with SimpleImputer for missing values
- [ ] Add StandardScaler or MinMaxScaler step
- [ ] Add OneHotEncoder for categorical features using ColumnTransformer
- [ ] Chain preprocessing with a model in one Pipeline

**Deliverable:** Python code with a multi-step sklearn Pipeline

---

### Mini-Project: Save trained Scikit-Learn pipeline to disk with joblib & serve API
**Resource:** *(Internal / See study guide below)*

**Acceptance Criteria:**
- [ ] Save trained Pipeline to disk with joblib.dump()
- [ ] Load the Pipeline and make predictions
- [ ] Create a minimal FastAPI endpoint that loads the model
- [ ] Endpoint accepts JSON input and returns predictions

**Deliverable:** Saved .joblib file + FastAPI script

---

