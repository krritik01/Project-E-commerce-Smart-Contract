
# Project Ethereum E-commerce Smart Contract
![63523accd4d7d-Decentralized-Ecommerce-Platform jpgDecentralized-Ecommerce-Platform](https://github.com/krritik01/Project-E-commerce-Smart-Contract/assets/98963769/ff07244d-d9d7-4d77-b5b9-1c14d46e01d4)
This repository contains a Solidity smart contract for an Ethereum-based Ecommerce platform. This smart contract enables users to register products for sale, purchase products, confirm product delivery, and allows the manager to destroy the contract.

## Features
➡Product Registration: Users can register products for sale by providing a title, description, and price.

➡Product Purchase: Users can purchase products by sending the exact price in Ether to the contract. The seller cannot buy their own products.

➡Product Delivery Confirmation: Buyers can confirm product delivery, which triggers a transfer of the product's price to the seller.

➡Contract Destruction: The contract manager can destroy the contract, transferring its balance to themselves, effectively ending its existence.

## Prerequisites
You need access to an Ethereum development environment, such as Remix or Truffle, to deploy and interact with this contract.
Usage
Deploy the contract on the Ethereum network.

## Interact with the contract by using the provided functions:

➡registerProduct: Register a product for sale.

➡buy: Purchase a product.

➡delivery: Confirm the delivery of a purchased product.

➡destroy: Destroy the contract (only callable by the manager).

The contract includes modifiers to ensure it is not destroyed before performing certain actions.

## Note
Ensure that the contract manager is set correctly before deploying the contract.
This code is provided as-is and should be used for educational purposes. Ensure proper testing and security measures when deploying on the Ethereum mainnet.

### Disclaimer

This code is provided for informational and educational purposes only. Use it at your own risk. The authors and maintainers are not responsible for any misuse or loss of funds that may occur as a result of using this code.







### ETHEREUM DOCUMENTATION

[Documentation](https://ethereum.org/en/developers/docs/)


## License
This code is open-source and available under the MIT License. See the [LICENSE](https://choosealicense.com/licenses/mit/) file for more details

