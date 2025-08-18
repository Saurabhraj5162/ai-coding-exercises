# Stage 1 - Q1: Data Preprocessing (Feature Engineering & Pipelines)

## Problem Statement
You are given a CSV dataset with the following columns:

customer_id, age, gender, city, salary, purchased


- `age` has missing values.
- `gender` is categorical (Male/Female).
- `city` is categorical with many unique values (e.g., New York, London, Paris).
- `salary` is numeric but needs normalization.
- `purchased` is the target (0/1).

### Tasks
1. Load the dataset using `pandas`.
2. Impute missing values in `age` with the **median**.
3. Encode `gender` as binary.
4. Encode `city` using **one-hot encoding**.
5. Normalize `salary` with **standard scaling**.
6. Wrap all these steps into a **scikit-learn Pipeline** for reusability.

---

## Expected Output
- A fully preprocessed dataset ready for ML models.
- A reusable scikit-learn `Pipeline` that automates preprocessing.

---

## Learning Objectives
- Practice handling missing values.
- Apply categorical encodings.
- Normalize numerical features.
- Understand and implement `Pipeline` in scikit-learn.

---

## Extensions (Optional)
- Try `ColumnTransformer` instead of manually applying preprocessing.
- Save the pipeline using `joblib` for reuse in model training.
