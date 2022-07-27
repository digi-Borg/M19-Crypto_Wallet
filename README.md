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

The software operates on python 3.9 with the installation package imports embedded with Anaconda3 installation. The application was developed in VSCode 1.69, using Granache and Streamlit v1.10.0. Below are installation sites and libraries for imported tools to run the program.  The application for GUI uses Streamlit to create and run the blockchain transactions, ledgers and validations. 


---

## Installation Guide

Before running the applications open your terminal to install and check for your installations. First navigate to the download instructions using the links below. Then verify if the installations have been completed. 

1. Install Anaconda and create your environment; `python` should be installed with Anaconda:
* [python](https://www.python.org/downloads/) 

2. Verify version in the terminal enter command `python` for information or download:
* [anaconda3](https://docs.anaconda.com/anaconda/install/windows/e) 

3. Install Visual Studio Code, or VS Code, IDE to write the program & run it in Streamlit app: 
* [VSCode](https://code.visualstudio.com/download)

4. Install Ganache to setup a local blockchain to test and develop smart contracts in a local environment.: 
* [Granache](https://trufflesuite.com/ganache/) 

5. Install Streamlit to run the python code for the Blockchain Ledger in a GUI as a shareable web app: 
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
import requests                                             # allows HTTP requests in order to send response data
from dotenv import load_dotenv
load_dotenv()
from bip44 import Wallet
from web3 import Account                               # Python function for accessing latest blockchain ledger info
from web3 import middleware
from web3.gas_strategies.time_based import medium_gas_price_strategy
```
libraries and mdules for fintech_finder.py: 
```
import streamlit as st                             # Python library for building web interfaces for Python apps from dataclasses import dataclass
from typing import Any, List
from web3 import Web3                              
w3 = Web3(Web3.HTTPProvider('HTTP://127.0.0.1:7545'))  # connects to Web3 and Mnemonic provider Ganache  blockchain
```

---

## Usage

This application is launched from the VSCode terminal utilizing the above imported Python libraries and tools.The program is developed in VSCode using python language **.py** file to build the `cypto_wallet` and the `fintech_finder`. `Web3` allows remote procedure call(RPC) to facilitate connection with the `crypto_wallet` and the Ethereum Blockchain network in Granache. The user of the program application operates through the Streamlit web app that provides functionality to create an Ethereum transaction and perform the following: 

- Generate a new Ethereum account instance by using the mnemonic seed phrase provided by Ganache.

- Fetch and display the account balance associated with the Ethereum account address.

- Calculate the total value of an Ethereum transaction, including the gas estimate, that pays a Fintech Finder candidate for their work.

- Digitally sign a transaction that pays a Fintech Finder candidate, and sends this transaction to the Ganache blockchain.blocks, perform the proof of work consensus protocol, and validate blocks in the chain.   

Blockchain ledger for transaction verification of the data in the ledger. 

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