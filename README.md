# Car Evaluation Decision Tree from Scratch

A Decision Tree Classifier implemented from scratch using Python and NumPy, without relying on machine learning libraries for the core algorithm.

## Project Overview

This project implements a Decision Tree classification algorithm from the ground up using the Car Evaluation dataset from the UCI Machine Learning Repository.

The main objective is to understand how Decision Trees work internally by implementing key concepts such as entropy, information gain, optimal splitting, and recursive tree construction.

## Dataset

The project uses the **Car Evaluation Dataset** from the UCI Machine Learning Repository.

- **Source:** [UCI Machine Learning Repository – Car Evaluation Dataset](https://archive.ics.uci.edu/dataset/19/car+evaluation)
- **Total instances:** 1,728
- **Input features:** 6
- **Target variable:** `class`
- **Classification type:** Multiclass classification

### Features

The dataset contains the following input features:

| Feature | Description |
|---|---|
| `buying` | Buying price |
| `maint` | Maintenance cost |
| `doors` | Number of doors |
| `persons` | Passenger capacity |
| `lug_boot` | Luggage boot size |
| `safety` | Safety level |

### Target Classes

The target variable contains four classes:

- `unacc` – Unacceptable
- `acc` – Acceptable
- `good` – Good
- `vgood` – Very Good

## Implementation

The Decision Tree algorithm is implemented from scratch using Python and NumPy.

The implementation includes:

- Entropy calculation
- Weighted entropy calculation
- Information gain calculation
- Finding the best feature and split
- Recursive tree construction
- Prediction for individual samples
- Prediction for multiple samples
- Custom accuracy calculation
- Custom confusion matrix implementation

## Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn (for train-test splitting and accuracy verification)

**Note:** Scikit-learn is not used to build or train the Decision Tree model. The core Decision Tree algorithm is implemented from scratch.

## Model Evaluation

The dataset is divided into training and testing sets using an 80:20 split.

| Dataset | Number of Samples |
|---|---:|
| Training set | 1,382 |
| Testing set | 346 |

### Accuracy

The implemented Decision Tree achieved the following test accuracy:

**98.55%**

The custom accuracy function was also compared with Scikit-learn's `accuracy_score` to verify the result.

A custom confusion matrix was implemented to examine the model's classification results across the four target classes.

## Project Structure

```text
Car_Evaluation_decision_tree_scratch/
│
├── Car_Evaluation_decision_tree_scratch.ipynb
├── car.c45-names
├── car.data 
├── car.names
└── README.md
```

## How to Run

1. Clone this repository:

```bash
git clone https://github.com/Dulsaraabeybandara/Car_Evaluation_decision_tree_scratch.git
```

2. Navigate to the project directory:

```bash
cd Car_Evaluation_decision_tree_scratch
```

3. Install the required libraries:

```bash
pip install numpy pandas scikit-learn jupyter
```

4. Launch Jupyter Notebook:

```bash
jupyter notebook
```

5. Open `Car_Evaluation_decision_tree_scratch.ipynb` and run the cells.

## Learning Objectives

Through this project, I aim to strengthen my understanding of:

- Decision Tree algorithms
- Entropy and Information Gain
- Recursive algorithms
- Multiclass classification
- Model evaluation techniques
- Implementing machine learning algorithms from scratch

## Future Improvements

- Implement Precision, Recall, and F1-score.
- Improve model evaluation and analysis.
- Experiment with different train-test splits.

---

## Author

**Dulsara Abeybandara**
GitHub: [Dulsaraabeybandara](https://github.com/Dulsaraabeybandara)
