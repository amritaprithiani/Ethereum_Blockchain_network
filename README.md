# Fintech Finder Application

The purpose of this repository is to integrating the Ethereum blockchain network into the Fintech finder application in order to enable your customers to instantly pay the fintech professionals whom they hire with cryptocurrency.

----

## Technologies

- Language - Python

- streamlit - Library to build and share data apps.

- dataclasses - Module that provides a decorator and functions for automatically adding methods to user-defined classes. Note: Python 3.7 already includes dataclasses, Python 3.6 does not.

- typing - Module that provides support for type hints.

- datetime - Library that supplies classes for manipulating dates and times.

- hashlib - This module implements a common interface to many different secure hash and message digest algorithms

- web3 - python package for Ethereum blockchain interaction

- bip44 - Protocol for creating hierarchical deterministic wallets

- dotenv - a python package for loading environment variables

- Ganache - Ganache is a personal blockchain for rapid Ethereum and Corda distributed application development.

----

## Instalation Guide

pip install streamlit

pip install web3==5.17

pip install bip44

Install Ganache - Follow the instructions on the [Ganache download page](https://www.trufflesuite.com/ganache) to download and install this tool on your local machine.

----

## Usage

1. Open Ganache and click on Quickstart.
2. Copy and save the Mnenonic sead in .env file.

![Mnemonic seed](/Images/Mnemonic_seed.png)

3. To run the fintech finder application simply clone the repository and run the code by typing streamlit run fintech_finder.py in your GitBash terminal.

![streamlit](/Images/streamlit.png)

----

## Highlights

This application launches a user friendly web interface which allow user to make block chain transaction. In this application user can select a fintech candidates to hire for hourly rates. It utilies Ganache to test the appication.

![fintech_finder_app](/Images/fintech_finder_app.png)

Transaction testing in Ganache

![Transaction](/Images/Transactions.png)

Transaction Details

![details](/Images/transaction_details.png)

Balance left after making transactions

![Balance left](/Images/Balance_left.png)

Logs - History of transaction

![logs](/Images/Transaction_history.png)

----

## Contributors

Brought to you by Amrita Prithiani

## License

MIT
