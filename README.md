# Intrusion Detection using Multi-Model Decision Trees

## Overview

This project implements a Network Intrusion Detection System (NIDS) using a multi-model decision tree ensemble approach on the KDD dataset. The system is designed to enhance the reliability and effectiveness of network intrusion detection while reducing false positives.

## Methodology

The project employs a comprehensive approach including:
- Data pre-processing
- Feature selection and weighting
- Training multiple decision tree models using different feature subsets
- Ensemble prediction using voting mechanisms

The system detects four main categories of network attacks:
- Denial of Service (DoS) attacks
- Probe attacks
- Remote to Local (R2L) attacks
- User to Root (U2R) attacks

## Dataset

The KDD Cup dataset used contains:
- Training set: 125,973 records
- Test set: 22,544 records
- 42 features per record
- Multiple attack types and normal traffic patterns

## Performance Results

The ensemble model achieves exceptional accuracy across attack categories:

| Attack Type | Accuracy | Precision | Recall | F-measure |
|------------|----------|-----------|---------|------------|
| DoS        | 99.74%   | 99.69%    | 99.71%  | 99.70%     |
| Probe      | 99.09%   | 98.67%    | 98.47%  | 98.57%     |
| R2L        | 97.46%   | 96.69%    | 96.09%  | 96.38%     |
| U2R        | 99.65%   | 87.54%    | 89.54%  | 87.73%     |

### Visualization of Results

![performance_heatmap](https://github.com/user-attachments/assets/7e3ae68d-c48d-4b60-9e5d-1e0dcb00f01e)

![line_graph](https://github.com/user-attachments/assets/2c53c70a-1888-4b0e-8f58-99362cdb4562)

## Technical Requirements

- Python 3.x
- pandas
- numpy
- scikit-learn
- IPython
- pydotplus

## Installation & Usage

1. Clone the repository
2. Install required dependencies:
3. Ensure you have the dataset files:
   - KDDTrain_2.csv
   - KDDTest_2.csv
4. Run the Jupyter notebook:


## Project Structure

The implementation follows these key steps:
1. Data preprocessing and cleaning
2. Feature engineering and selection using RFE
3. Model training with multiple decision trees
4. Ensemble prediction combination
5. Performance evaluation and visualization

## Contributing

Contributions to improve the project are welcome. Please feel free to fork the repository and submit pull requests.
