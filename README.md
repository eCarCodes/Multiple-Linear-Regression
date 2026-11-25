# Multiple-Linear-Regression
This project is a from-scratch implementation of a multi-variate linear regression model trained on real data from Kaggle.
The purpose of the project is to explore linear regression behind the scenes by training a model from scratch to predict an index output (0-100) of student performance based on various factors such as hours studied, previous scores, extracurricular activities, sleep hours, and sample question papers practiced. 

Kaggle dataset credits to Nikhil Narayan (nikhil7280)

## Tech Stack & Libraries
- Python 3.10+
- NumPy
- Matplotlib
- Jupyter Notebook

## Installation

### Prerequisites
- [Python 3.10+](https://www.python.org/downloads/)
- [Git](https://git-scm.com/downloads)

### 1. Clone the repository
```bash
git clone https://github.com/eCarCodes/Multiple-Linear-Regression.git
cd Multiple-Linear-Regression
```

### 2. (Recommended) Create a virtual environment
```bash
python -m venv venv
```
Activate it:
- **Windows:** `venv\Scripts\activate`
- **macOS/Linux:** `source venv/bin/activate`

### 3. Install the dependencies
```bash
python -m pip install -r requirements.txt
```
> **Note:** On macOS/Linux, you may need to use `python3` instead of `python`.

### 4. Launch Jupyter Notebook
```bash
jupyter notebook
```
Then open `Multivariate_LR.ipynb` in your browser and run all cells (**Run → Run All Cells**).

The dataset is included in `data/Student_Performance.csv`, so you don't need to download anything from Kaggle.

## Demo
Model trained on 1500 iterations of gradient descent:

![Predicted vs. actual performance index after 1500 iterations of gradient descent](image.png)
