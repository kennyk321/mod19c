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


![Fintech Professional](https://user-images.githubusercontent.com/95942698/201545865-442e8e0f-f266-4e6f-8055-88e6024c8d29.png)


# Validated Transaction Hash 


![Validated Transaction Hash ](https://user-images.githubusercontent.com/95942698/201545882-294d54da-0ddc-46f3-b0f8-cdaceb853378.png)


# Sample Account


<img width="1432" alt="sample account" src="https://user-images.githubusercontent.com/95942698/201545890-19fcbd26-14df-413e-baca-0a20bce7ce67.png">


# Sample Transaction 

<img width="1427" alt="transaction" src="https://user-images.githubusercontent.com/95942698/201545899-fbbbe2e1-9c46-44d8-ba72-533c95413eaa.png">

# Transaction Details 


<img width="1427" alt="transaction details " src="https://user-images.githubusercontent.com/95942698/201545907-2a5b1d90-1469-4b39-adb3-ed021aa63f47.png">

