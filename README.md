# Fairness-AI-Classifier

## Overview
This project implements and evaluates an AI classifier with a focus on **fairness** across different demographic groups.  
It includes:
- Data preprocessing
- Model training
- Fairness metrics evaluation
- Performance comparison
- Result analysis & conclusions

The project is implemented using **Python** and **Jupyter Notebooks**.

---

## Project Structure

```
.
├── project.ipynb              # Main project notebook
├── train_classifieur.ipynb    # Notebook for training classifier
├── train_classifieur.py       # Python script for classifier training
├── train_classifieur.sh       # Shell script for training automation
└── README.md                  # Project documentation
```

---

## Usage

### Running the main notebook
Open Jupyter Notebook or Jupyter Lab:
```bash
jupyter notebook
```
Then open `project.ipynb` and run the cells step by step.

### Running the training script
```bash
python train_classifieur.py
```

### Running with shell script
```bash
bash train_classifieur.sh
```

---

## Features Implemented
- **Data preprocessing** with missing value handling & normalization
- **Model training** with fairness-aware evaluation
- **Metrics**:
  - Accuracy
  - Recall
  - Precision
  - F1-score
  - Fairness-specific metrics (Statistical parity, Equal opportunity, etc.)
- **Bias analysis** and mitigation strategies

---

## Results
- Detailed performance metrics for each tested model
- Fairness evaluation across subgroups
- Insights on bias mitigation strategies

---

## Current Limitations
- Optimization possible for faster training
- Dataset may not cover all bias scenarios
- Further testing needed with real-world data

---

## License
This project is for academic/research purposes.  
Please cite the repository if you use it.

---

## Author
**Firdaous Elouadi**  
Email: firdaouselouadi@gmail.com
