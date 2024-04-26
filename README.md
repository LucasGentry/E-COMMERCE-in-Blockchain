## 1. Introduction
This is backend project which interact with MetaMarket's smart contracts.  
Production (BSC): https://metamarket.top  
Staging (BSC testnet): https://testnet.metamarket.top

an e-commerce platform using blockchain technology for tracking and supply chain management.

In this platform, the NFTs ERC721, ERC1155, and ERC721Aand users will mint the NFT from our smart contract through our user interface, and after getting ownership of the NFT, they can buy products from our platform as well as from our local stores.

For minting NFT, we are planning to use our custom ERC20 tokens, and these tokens can be used to transfer, sell, or buy.

## 2. Requirements

Python 3.7 or higher.

## 3. How to run the project

1. `cd` into the project and then run `virtualenv venv`

#### If you are using MacOS, Linux or Ubuntu

2. Run `source venv/bin/activate`
3. Run `pip install -r requirements.txt`
4. Install Ganache and download BSC testnet network into your local computer by running `python setup_ganache.py`
5. Run `python manage.py migrate`
6. (optional) Run `python manage.py createsuperuser`
7. Run `python manage.py runserver`

#### If you are using Windows

2. If Windows, run `venv\Scripts\activate`
3. Run `pip install -r requirements_windows.txt`
4. Install Ganache and download BSC testnet network into your local computer by running `python setup_ganache_windows.py`
5. Run `python manage.py migrate`
6. (optional) Run `python manage.py createsuperuser`
7. Run `python manage.py runserver`
