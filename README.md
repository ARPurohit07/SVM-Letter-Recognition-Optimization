# SVM Letter Recognition Optimization

This project applies Support Vector Machine (SVM) classification to the UCI Letter Recognition Dataset. It includes hyperparameter tuning using GridSearchCV and convergence analysis through random search.

## Files

- `test.ipynb` – Jupyter Notebook with all code for training, optimization, and plotting
- `letter-recognition.data` – Dataset file from UCI
- `convergence.png` – Convergence plot showing accuracy across iterations

## Method

- Created 10 random 70/30 train-test splits
- Used GridSearchCV to tune SVM parameters: `kernel`, `C`, and `gamma`
- Selected the best-performing sample for further convergence analysis
- Ran a 100-iteration random search to plot accuracy improvements

## Libraries Used

- Python
- scikit-learn
- pandas
- matplotlib

## How to Run

1. Clone the repository
2. Open `test.ipynb` in Jupyter or VS Code
3. Run all cells to train and visualize results
