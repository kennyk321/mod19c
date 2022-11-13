# mod19c
### Package Requirments & Versions
* import streamlit as st
* from dataclasses import dataclass
* from typing import Any, List
* from web3 import Web3
* from crypto_wallet import generate_account, get_balance, send_transaction
* import os
* import requests
* from dotenv import load_dotenv
* load_dotenv()
* from bip44 import Wallet
* from web3 import Account
* from web3 import middleware
* from web3.gas_strategies.time_based import medium_gas_price_strategy


### Purpose of Use
* Integrate Ethereum blockchain network into application "Fintech Finder" to allow customers to instantly pay fintech professional they hire with cryptocurrency. 

* The code is multiple parts:
    1. Import Ethereum transaction functions into Fintech Finder App
    2. Sign and execute payment transaction
    3. Inspect transaction on Ganache 
    
    
    
### Files Navigation
* `fintech_finder.py`
* `crypto_wallet.py`
* to launch applications, type streamlit run fintech_finder.py


### Transaction Inspections on Ganache 

# Fintech Professional


# Validated Transaction Hash 


# Sample Account


# Sample Transaction 


# Transaction Details 