
# MyToken Contract


This is a straightforward Solidity smart contract that generates a token with the name "TOCKEN" and the initials "TOC." It employs a mapping of addresses to balances to keep track of how many tokens each address possesses and has a total supply that starts at 0.

Two functions, mint and burn, are included in the contract.


## Description

This program is a straightforward contract written in remix. The contract lets you to modify the account address by adding and removing values.
 

## Requirements

1)There are three public variables in the contract that record information about the coin: tokenName, tokenAbbrv, and totalSupply.

2)The contract employs an address-to-balance mapping: mapping(address => uint) public balances.

3)The mint function raises the overall supply by the specified amount and the balance of the specified address by the same amount.

4)The burn function subtracts the specified amount from the overall supply as well as the balance of the specified address.

5)The burn function has conditionals to ensure that the balance of the provided address is more than or equal to the amount to be burnt.

## Usage

To use this contract, you can deploy it to a Ethereum network (such as the mainnet, Ropsten, or a local testnet) using a Solidity compiler and an Ethereum client (such as Remix or Truffle). Then you can interact with the contract using a web3 provider (such as MetaMask) or a smart contract wallet (such as Gnosis Safe).
## License

This code is licensed under the [MIT](https://choosealicense.com/licenses/mit/) license.See the LICENSE file for more information.


## Acknowledgements

I would like to acknowledge the Remix Tutorials and the Remix website for providing helpful resources and tools for learning and developing smart contracts on the Ethereum network. Their tutorials and user-friendly interface have been instrumental in my understanding and development of Solidity smart contracts. Thank you for your valuable contributions to the blockchain community!
