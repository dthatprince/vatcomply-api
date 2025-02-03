# DataGadgets Currency Conversion Project using VAT Comply Exchange Rate API

## Project Description
As part of expanding our successful gadget webshop, `DataGadgets`, into the UK and Europe, we encountered a challenge with our in-house reporting system. Transactions are now processed in multiple currencies (USD, EUR, and GBP), and we need to convert all transactions to USD for accurate financial reporting.

This project automates the process of converting non-USD transactions to USD using real-time exchange rates from [VAT Comply's Currency Exchange API](https://www.vatcomply.com/documentation#rates). 

The goal is to:
- Load a CSV file with e-commerce transactions in various currencies.
- Fetch exchange rates from the VAT Comply API for the transaction date.
- Convert all non-USD transactions into USD.
- Calculate the total USD sales from all transactions.
