# SmallMLProject 

This is a small end-to-end Machine Learning project with a **Flask web interface**. The project demonstrates building and deploying a prediction pipeline using Python, scikit-learn, and Flask.

---
## Features

- Predicts student performance (e.g., math scores) using demographic and academic features.
- Flask web interface for user-friendly interaction.
- Modular and reusable pipeline for real-world deployment.
- Exception handling for robustness.

Example input fields:
- Gender
- Race/Ethnicity
- Parental Level of Education
- Lunch Type
- Test Preparation Course
- Reading Score
- Writing Score

---

##  How It Works

### `CustomData`
- Converts form inputs to a structured pandas DataFrame.

### `PredictPipeline`
- Loads the trained model and preprocessor.
- Transforms inputs and returns predictions.

## Initial Display:

<img width="745" height="461" alt="image" src="https://github.com/user-attachments/assets/0371841b-d213-4471-965d-3fdab578b928" />


## Final Display:

<img width="681" height="418" alt="image" src="https://github.com/user-attachments/assets/a9d90cb5-e86e-4716-941c-6062a989507d" />
