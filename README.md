# sheets-utilities

## At a glance

A collection of .gs snippets for making the live of the fusion of NFT + Google Sheets easier. Includes several different APIs such as OpenSea, Etherscan, Poloniex, etc. For some, but not all, API keys are required. All endpoints used, use the freely available endpoints. Rate limits may apply, depending on the API (e.g. OpenSea).

### Fetch collection information

Fetch information from Opensea about a collection. Useful if one wants to include e.g. floor price in their sheet. 

### Fetch historic ETH price

Fetch historic ETH/USDT price, to have an overview over how much your ETH was worth at a specific point in time. 

### Fetch transactions from etherscan.io

Fetch all transactions of a specific wallet. Unfortunately, the available endpoint does not include information about the type of transaction. 

## How to use

To use these snippets you need to use the API Scripts editor of Google. This is available in your Google Sheet under Extensions > Apps Scripts
