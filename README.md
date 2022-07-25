# M19-Crypto_Wallet 

![M19Title](./Images/M19Title_2022-07-24235319.png)

*"Developing a Blockchain ledger for financial transactions with counterparty financial institutions for data verification."* 


## Background 

A fintech engineer working at one of the five largest banks in the world is recently promoted to act as the lead developer on the decentralized finance team. The task is to build a blockchain-based ledger system, complete with a user-friendly web interface. The ledger should allow partner banks to conduct financial transactions and to verify the integrity of the data in the ledger.

The FinTech technology in this program utilizes ScikitLearn ML algorithm software tools. The tools are used to build algorithmic models by adjusting inputs for buy, sell or hold signals; these signals are derived from a technical indicator called simple moving average(SMA). SMA's calculate the average stock prices over a rolling time period designating a number of days in time windows. 

Adjusting the ML algorithm inputs one can put together models, tune them, visualize performance on charts, and backtest them for evaluation on a Classification Report. Additionaly, other classes of ML models are available for backtesting and predicting outcomes before applying them to your strategies.  

---

## Evaluation Results

The following illustrations describes the utilizing the streamlit app to tests the blockchain ledgers storage of records. 

* The user interface of the steamlit app for 'Sender', 'Receiver' and 'Amount' inputs with 'Add Block and "Validation' buttons to activate the blockchain ledger process:
![StlitUI](Images/M18p1_2022-07-20213046.png) 
--

* A) 4. Verify the block contents and hashes in the Streamlit drop-down menu. Take a screenshot of the Streamlit application page, which should detail a blockchain that consists of multiple blocks. Include the screenshot in the README.md file for your Challenge repository: 
![StlitMultiBlock](Images/M18p3_2022-07-20215202.png)  

![StlitMultiBlock2](Images/M18p5_2022-07-20235351.png)
--
  
* B) 5. Test the blockchain validation process by using the web interface. Take a screenshot of the Streamlit application page, which should indicate the validity of the blockchain:
![StlitValidity](Images/M18p4_2022-07-20215455.png)
--

* C) Streamlit video of testing the blockchain validation process by using the PyChain ledger:
![StVid](Images/M18vid-streamlit-pychain-2022-07-20.webm)

 
 ### **Tune the Baseline Trading Algorithm**
 1.  

___

## Technologies

The software operates on python 3.9 with the installation package imports embedded with Anaconda3 installation. The application was developed in VSCode 1.69.2, using the python 3.10 language and Streamlit v1.10.0. Below are installation sites and libraries for imported tools to run the program.  The application for GUI uses Streamlit to create and run the blockchain ledger and validate it. 


---

## Installation Guide

Before running the applications open your terminal to install and check for your installations. First navigate to the download instructions using the links below. Then verify if the installations have been completed. 

* [python](https://www.python.org/downloads/)

* [anaconda3](https://docs.anaconda.com/anaconda/install/windows/e) 

* [VSCode](https://code.visualstudio.com/download) 

* [streamlit](https://docs.streamlit.io/library/get-started/installation)



```
python libraries
pip install web3==5.17                         # connects and performs operations on Ethereum-based blockchains.
pip install eth-tester==0.5.0b3                # provides access to the tools to test Ethereum applications.
pip install mnemonic                           # generates BIP-39 standard 12 or 24-word mnemonic seed phrases.
pip install bip44                              # derives hierarchical deterministic wallets from a seed phrase.
```
```
import pandas as pd
import streamlit as st                             # Python library for building web interfaces for Python apps from dataclasses import dataclass
from typing import Any, List
import datetime as datetime
import pandas as pd
import hashlib                                   
```

---
# Usage

This application is launched from the VSCode terminal utilizing Pandas and scikitlearn `StandardScaler` to preprocess data for categorical variables in the ML algorithm model computations. Scikit ML models are tunable by adjusting input features to find parameters that result in the best outcomes for different trading strategies and adapt to market environments. While `classification_report` illustrates the evaluation metrics such as accuracy, precision and recall.    

The program is developed in VSCode using python language **.py** file. The Python library makes it possible to utilize pandas, numpy and pathlib to build this Blockchain ledger for transaction verification. The design applies the model-fit-predict process to make a binary classification of whether a startup is successful or not.
 

![]()
![]() 



```
python
pychain.py
```
 

---

## Contributors

*Provided to you by digi-Borg FinTek*, 
Dana Hayes: nydane1@gmail.com

---

## License
Columbia U. Engineering 
--
[BSD 2-Clause LicenseCopyright (c) 2022, digi-Borg
All rights reserved.](/LICENSE)