# SKlearn_digits_dataset_logistic_Regression

# Digits Classification using Logistic Regression

## Overview
This project implements a Logistic Regression model to classify handwritten digits using the popular Scikit-learn digits dataset. The model is enhanced with standard scaling for feature normalization and includes comprehensive confusion matrix analysis for performance evaluation.

## Dataset
The project uses the digits dataset from Scikit-learn, which includes:
- 1797 samples of handwritten digits (0-9)
- 64 features (8x8 grayscale images)
- Target: Digits from 0 to 9

## Implementation Details

### Data Preprocessing
- Standard Scaling applied using `StandardScaler` to normalize features
- Data split into training and testing sets (80-20 split)

### Model Architecture
- Algorithm: Logistic Regression
- Multi-class classification using One-vs-Rest strategy

### Performance Analysis
- Confusion Matrix visualization
- Classification metrics:
  - Accuracy score

## Requirements
```
numpy
pandas
scikit-learn
matplotlib
seaborn
```

## Usage
1. Clone the repository:
```bash
git clone https://github.com/MasterShomya/SKlearn_digits_dataset_logistic_Regression.git
cd SKlearn_digits_dataset_logistic_Regression
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

3. Run the Jupyter notebook or Python script:
```bash
jupyter notebook digits-logistic-regression.ipynb
```

## Results
- Model achieves 0.97 accuracy on the test set
- Detailed performance metrics available in the confusion matrix visualization
- Individual digit recognition rates shown in the classification report

## File Structure
```
├── digits_classification.ipynb   # Main notebook with analysis
├── digits_classification.py      # Python script version
├── requirements.txt             # Required packages
├── README.md                    # This file
└── results/                     # Confusion matrix plots and metrics
```

## Contributing
Feel free to fork this repository and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](https://choosealicense.com/licenses/mit/)

## Contact
Your Name - sonejishomya@gmail.com
Project Link: [https://github.com/MasterShomya/SKlearn_digits_dataset_logistic_Regression]
