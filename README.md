# Child Mind Institute - Detect Sleep States 

**Authors**: ABDI Feriel, BENKORTEBI Manel, GBABOUA Cassandra, LEBIB Inès

## Summary

### Project Overview
This project is an intersection of academic coursework and competitive research. It falls under the [`BQ4CY030 Apprentissage, Intelligence artificielle et Optimisation 1`](https://moodle.u-paris.fr/course/view.php?id=4162) course at Paris Cité University and is also part of a code [`competition`](https://www.kaggle.com/competitions/child-mind-institute-detect-sleep-states/overview) hosted by the Child Mind Institute.

#### Objectives

- **Academic:** To explore and implement machine learning algorithms such as Recurrent Neural Networks (RNN), Convolutional Neural Networks (CNN), Random Forest, and Logistic Regression for sleep state detection.
  
- **Competitive:** To focus on the average precision of detected sleep and wake events as per the competition’s evaluation metric.

#### Impact

The work aims to enhance the reliability of large-scale sleep studies. It holds particular significance for healthcare, especially concerning mood and behavior difficulties in children and adolescents.

## System Requirements
This program is compatible with macOS and UNIX-based operating systems. Windows users can run this project using Windows Subsystem for Linux (WSL).
This program require a Python 3.11.5 version.

## Installation

### Clone Repository
To clone the repository, run the following command:

`git clone https://github.com/cgbaboua/AIAO_Sujet2.git`

## Clone the competition repository

To access the raw data and run the scripts, visit the [Kaggle - Child Mind Institute Competition](https://www.kaggle.com/competitions/child-mind-institute-detect-sleep-states/data) to download the data.

Alternatively, you can use the following command:
`kaggle competitions download -c child-mind-institute-detect-sleep-states`


### Repository Contents
[AIAO_Sujet2/](https://github.com/cgbaboua/AIAO_Sujet2)
  - [README.md](https://github.com/cgbaboua/AIAO_Sujet2blob/main/README.md)
  - [Documents/](https://github.com/cgbaboua/AIAO_Sujet2/tree/main/Documents)
    - [Presentation](https://github.com/cgbaboua/AIAO_Sujet2/blob/main/Documents/Presentation)
    - [Report](https://github.com/cgbaboua/AIAO_Sujet2/blob/main/Documents/Report)
  - [Python/](https://github.com/cgbaboua/AIAO_Sujet2/tree/main/Python)
    - [preprocessing.py](https://github.com/cgbaboua/AIAO_Sujet2/blob/main/Python/preprocessing.py)
    - [rnn_padding.py](https://github.com/cgbaboua/AIAO_Sujet2/blob/main/Python/rnn_padding.py)
    - [lstm_windows.py](https://github.com/cgbaboua/AIAO_Sujet2/blob/main/Python/lstm_windows.py)
    - [regression_logistique.py](https://github.com/cgbaboua/AIAO_Sujet2/blob/main/Python/regression_logistique.py)
    -  [acp.py](https://github.com/cgbaboua/AIAO_Sujet2/blob/main/Python/acp.py)
  - [Results/](https://github.com/cgbaboua/AIAO_Sujet2/tree/main/Results)
     - [ACP.png](https://github.com/cgbaboua/AIAO_Sujet2/blob/main/Results/ACP.png)
    - [ConfusionMatrix_predict.png](https://github.com/cgbaboua/AIAO_Sujet2/blob/main/Results/ConfusionMatrix_predict.png)
    - [data_to_analyze_RNN.csv](https://github.com/cgbaboua/AIAO_Sujet2/blob/main/Results/data_to_analyze_RNN.csv)
    - [Ind_Better_predict.png](https://github.com/cgbaboua/AIAO_Sujet2/blob/main/Results/Ind_Better_predict.png)
    - [Ind_Results_1.png](https://github.com/cgbaboua/AIAO_Sujet2/blob/main/Results/Ind_Results_1.png)
    - [RNN_2.png](https://github.com/cgbaboua/AIAO_Sujet2/blob/main/Results/RNN_2.png)
    - [RNN_results_1.png](https://github.com/cgbaboua/AIAO_Sujet2/blob/main/Results/RNN_results_1.png)
    - [RNN_results_2.png](https://github.com/cgbaboua/AIAO_Sujet2/blob/main/Results/RNN_results_2.png)
    - [RNN.png](https://github.com/cgbaboua/AIAO_Sujet2/blob/main/Results/RNN.png)


## Getting Started

### Basic Usage
To run the program, navigate to the Python directory and execute the following:

- For Preprocessing: `python3 preprocessing.py`
- For RNN: `python3 rnn_padding.py`
- For LSTM: `python3 lstm_windows.py`
- For Logistic Regression : `python3 regression_logistique.py`
- For ACP : `python3 


### Packages Used
- `numpy`
- `scikit-learn`
- `tensorflow`
- `pandas`
- `Keras`
- `seaborn`
- `pyarrow`
- ...






