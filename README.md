# Gender Classification & Algorithmic Bias

## Overview
This repository contains a Python implementation of a simple **gender classification system**.  
It is designed as an **educational activity for law students** to explore how **data biases** affect AI performance, particularly in the context of **algorithmic misgendering**.

The project uses the **CelebA dataset**, a widely used facial attribute dataset, to demonstrate how imbalances in training data can reinforce societal prejudices and lead to biased outcomes.

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

## Installation
Clone the repository and install dependencies:

```bash
git clone https://github.com/yourusername/gender-classification-bias.git
cd gender-classification-bias
pip install -r requirements.txt
```

## Usage
Open the Jupyter notebook **`GCS_Law_and_AI.ipynb`** to train and evaluate the classifier interactively.  

Within the notebook, you can adjust the following parameters:  
- **`epochs`**: number of training epochs  
- **`batch_size`**: batch size for training  
- **`plot`**: generate visualizations of attribute distributions  

A pre-trained model is already available in **`gender_recognition.keras`**, so you can load and use it directly without retraining if desired.  

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
