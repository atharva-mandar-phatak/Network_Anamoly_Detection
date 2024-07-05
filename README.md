# Network Anomaly Detection

## Overview

This project focuses on detecting network anomalies, specifically Neptune attacks, using machine learning. A Neptune attack, or SYN flood attack, is a type of denial-of-service (DoS) attack where an attacker overwhelms a target system with a high number of SYN requests, causing the system to become unresponsive to legitimate traffic. The goal is to classify network activities as normal or as a Neptune attack.

## Problem Statement

The dataset contains detailed records of network activities, capturing various attributes associated with network connections. Each record is labeled to indicate whether the activity is normal or a "Neptune" attack, providing a foundation for binomial classification.

- **Normal Activity**: No attack (Attack = 0)
- **Neptune Attack**: SYN flood attack (Attack = 1)

## Dataset

- **Training Set**: 86,845 rows
- **Test Set**: 21,712 rows
- **Target Variable**: `Attack`
  - `0`: Normal activity
  - `1`: Neptune attack

## Project Structure

- `data/`: Contains the training and test datasets
- `notebooks/`: Jupyter notebooks for data exploration and model training
- `src/`: Source code for data preprocessing, model training, and evaluation
- `models/`: Saved machine learning models
- `results/`: Evaluation results and visualizations

## Usage

### 1. Clone the Repository

```bash
git clone https://github.com/atharva-mandar-phatak/Network_Anamoly_Detection.git
cd Network_Anamoly_Detection
```

### 2. Install Dependencies

Ensure you have Python 3.x installed. Then, install the required packages:

```bash
pip install -r requirements.txt
```

### 3. Run the Project

You can start by exploring the data and training the model using the provided Jupyter notebooks in the `notebooks/` directory. Alternatively, you can use the scripts in the `src/` directory to preprocess the data, train the model, and make predictions.


## Contributing

Contributions are welcome! Please create a pull request or open an issue to discuss any changes or additions.

## Acknowledgements

This project is based on a dataset of network activities aimed at detecting anomalies such as Neptune attacks. Special thanks to the creators and maintainers of this dataset.

