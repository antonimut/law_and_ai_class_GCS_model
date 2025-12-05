# Gender Classification & Algorithmic Bias

## Overview
This repository contains a Python implementation of a simple **gender classification system**.  
It is designed as an **educational activity for law students** to explore how **data biases** affect AI performance, particularly in the context of **algorithmic misgendering**.

The project uses the **CelebA dataset**, a widely used facial attribute dataset, to demonstrate how imbalances in training data can reinforce societal prejudices and lead to biased outcomes.

## Content 

The repository includes the following files and their uses:

- **Notebook**: Demonstrates step-by-step how to use the model.  
- **PowerPoint presentation**: Designed for classroom use to explain how the model works and to present the activity.  
- **PDF document**: Contains the activity we completed last year.  
- **LaTeX repository (ZIP file)**: Provides the source files in case you want to modify the activity.  
- **Set of pictures**: Useful for recreating the activity in class.  
- **Example picture**: Used to run the demonstration.
- **CSV File**: Contains data on the pictures used to train the model (useful for identifying potential biases).

## Objectives
- Understand how AI training datasets contribute to biased outcomes.  
- Analyze statistical distributions in datasets to predict potential algorithmic biases.  
- Explore correlations between facial attributes and gender labels.  
- Develop critical thinking around **ethical AI development** and **legal implications** of biased systems.  

## Why Law Students?
AI systems increasingly influence areas of law, policy, and human rights.  
By experimenting with this project, law students can:
- Recognize how **technical design choices** impact fairness.  
- Debate the **legal responsibility** of developers and institutions deploying biased AI.  
- Connect **data bias** to broader issues of discrimination and equality.  

## Usage

- Open the Jupyter notebook **`step-by-step_guide.ipynb`** to use the GCS interactively.  
- The pre-trained model is available for direct use without retraining:
  
  - **Download Link:** [gender_recognition.keras](https://www.dropbox.com/scl/fi/8gyk05ovq3x97xb6iy4s4/gender_recognition.keras?rlkey=siwtgf3pho8isp6uvx2atcwr4&st=nxpg542o&dl=0)  

You can load the model in your notebook or script with:  

```python
from tensorflow import keras

# Load the pre-trained model
model = keras.models.load_model("gender_recognition.keras")

# Use the model for inference
predictions = model.predict(your_input_data)
```

This allows you to skip the training step and immediately run evaluations or integrate the model into your application.  

---

## Example Analysis
The code includes tools to:
- Examine the distribution of the **Male** label across attributes (e.g., lipstick, facial hair, hairstyle).  
- Visualize correlations that may lead to **misgendering**.  
- Discuss how these imbalances affect classification accuracy.  

## Ethical Disclaimer
This project is **not intended for real‑world deployment**.  
It is an **academic exercise** to highlight risks of biased AI systems.  
The classifier may misgender individuals and should only be used for **critical analysis and discussion**.

---

## License
This repository is released under the MIT License.  
Feel free to use and adapt it for educational purposes.

---
