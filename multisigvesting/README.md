# Claiming Tokens from idexo Vesting Contracts Using Gnosis Safe

In order to claim your vested tokens from an idexo vesting contract from a Gnosis safe, you need the following things: 

The vesting contract ABI. 

The address on the blockchain of your deployed vesting contract. 

## The vesting contract ABI

The ABI for the vesting contract is contained in this folder and named VestingContractABI. 

## Your deployed contract address

To obtain your deployed vesting contract address please speak to the idexo team to obtain this. 

## How to use them

When in your Gnosis safe, choose 'New transaction' and then 'Contract interaction'.

From the 'Contract interaction' from paste in your Contract Address in the form field presented and then paste in your ABI (the entirety of what is in the file included in this repository folder). 

Once you do this successfully a number of contract methods will be presented to you. Choose the 'claim' method and enter in the number of $IDO tokens you would like to claim. Make sure to add 18 zeros to the end of the amount as this form does not do wei conversions. 

Once you submit this transaction it will then need to be confirmed by however many other signers as is set in the settings of the Gnosis safe you are using. 