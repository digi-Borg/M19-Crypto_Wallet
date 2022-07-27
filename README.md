# M19-Crypto_Wallet 

![M19Title](./Images/M19Title_2022-07-24235319.png)

*"Developing a Blockchain ledger for financial transactions with counterparty financial institutions for data verification."* 


## Background 

You work at a startup that is building a new and disruptive platform called Fintech Finder. Fintech Finder is an application that its customers can use to find fintech professionals from among a list of candidates, hire them, and pay them. As Fintech Finder’s lead developer, you have been tasked with integrating the Ethereum blockchain network into the application in order to enable your customers to instantly pay the fintech professionals whom they hire with cryptocurrency.

The code enables your customers to send cryptocurrency payments to fintech professionals. To develop the code and test it out, you will assume the perspective of a Fintech Finder customer who is using the application to find a fintech professional and pay them for their work. 

---
## Evaluation Results


Review the transaction hash code associated with the validated blockchain transaction.

Once you receive the transaction’s hash code, you will navigate to the Transactions section of Ganache to review the blockchain transaction details. To confirm that you have successfully created the transaction, you will save screenshots to the README.md file of your GitHub repository for this Challenge assignment.

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

---
## Technologies

The software operates on python 3.9 with the installation package imports embedded with Anaconda3 installation. The application was developed in Jupyter Lab 3.4.4 notebook, using Granache and Streamlit v1.10.0. Below are installation sites and libraries for imported tools to run the program.  The application for GUI uses Streamlit to create and run the blockchain transactions, ledgers and validations. 


---

## Installation Guide

Before running the applications open your terminal to install and check for your installations. First navigate to the download instructions using the links below. Then verify if the installations have been completed. 

1. Install Anaconda and create your environment; `python` should be installed with Anaconda:
* [python](https://www.python.org/downloads/) 

2. Verify version in the terminal enter command `python` for information or download:
* [anaconda3](https://docs.anaconda.com/anaconda/install/windows/e) 

3. Install Ganache to setup a local blockchain to test and develop smart contracts in a local environment.: 
* [Granache](https://trufflesuite.com/ganache/) 

4. Install Streamlit to run the python code for the Blockchain Ledger in a GUI as a shareable web app: 
* [streamlit](https://docs.streamlit.io/library/get-started/installation)



```
python libraries
pip install web3==5.17                         # connects and performs operations on Ethereum-based blockchains.
pip install eth-tester==0.5.0b3                # provides access to the tools to test Ethereum applications.
pip install mnemonic                           # generates BIP-39 standard 12 or 24-word mnemonic seed phrases.
pip install bip44                              # derives hierarchical deterministic wallets from a seed phrase.
```
libraries and modules for crypto_wallet.py:
```
import os
import requests
from dotenv import load_dotenv
load_dotenv()
from bip44 import Wallet
from web3 import Account
from web3 import middleware
from web3.gas_strategies.time_based import medium_gas_price_strategy
```
libraries and mdules for fintech_finder.py: 
```
import streamlit as st                             # Python library for building web interfaces for Python apps from dataclasses import dataclass
from typing import Any, List
from web3 import Web3                            # Python function for accessing latest blockchain ledger info  
w3 = Web3(Web3.HTTPProvider('HTTP://127.0.0.1:7545'))  # connects to Web3 and Mnemonic provider Ganache  blockchain
```

---

## Usage

This application is launched from the VSCode terminal utilizing Pandas and scikitlearn `StandardScaler` to preprocess data for categorical variables in the ML algorithm model computations. Scikit ML models are tunable by adjusting input features to find parameters that result in the best outcomes for different trading strategies and adapt to market environments. While `classification_report` illustrates the evaluation metrics such as accuracy, precision and recall.    

The program is developed in VSCode using python language **.py** file. The Python library makes it possible to utilize pandas, numpy and pathlib to build this Blockchain ledger for transaction verification. The design applies the model-fit-predict process to make a binary classification of whether a startup is successful or not.
 

![]()
![]() 



```
python 
crypto_wallet.py
fintech_finder.py 

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