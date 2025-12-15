## Credit Card Default Prediction using SVM and KNN (R)
## Dataset
The dataset (`credit_card_data-headers.txt`) contains multiple numerical features related to credit card customers and a binary target variable indicating default status.

- Features: Customer and transaction-related attributes
- Target Variable: Credit card default (binary classification)

## Methods Used
### Support Vector Machine (SVM)
- Linear kernel (vanilladot)
- Radial Basis Function (RBF) kernel (rbfdot)
- Hyperparameter tuning using different values of **C**
- Model evaluation using accuracy

### K-Nearest Neighbors (KNN)
- Tested with multiple values of **k**
- Cross-validation to determine the best k
- Accuracy-based performance comparison

## Model Evaluation
- Accuracy comparison between SVM (Linear), SVM (RBF), and KNN
- Selection of best-performing model
- Additional train–test split (70/30) evaluation

## Results
The models are compared based on classification accuracy, and the best-performing approach is reported. Results demonstrate the effectiveness of kernel-based SVMs and KNN for credit card classification tasks.

## How to Run
1. Clone or download this repository.
2. Ensure the following R libraries are installed:
   - `kernlab`
   - `kknn`
3. Place the dataset and R script in the same directory.
4. Open the R script in RStudio.
5. Run the script to view model outputs and accuracy results.

## Files in This Repository
- `Credit-Card-Default-Modeling-Using-Linear-RBF-SVMs-and-KNN.R` – Main R script implementing SVM and KNN models
- `credit_card_data-headers.txt` – Dataset with headers
- `README.md` – Project overview
- `writeup.pdf` - Project documentation

## Tools & Libraries
- R
- kernlab
- kknn
