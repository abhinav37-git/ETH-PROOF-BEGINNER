# ETH-PROOF-BEGINNER

License This contract is using the MIT License.

Prerequisites Solidity ^0.8.18

<Challenge

For the assessment, we will create a contract together to fulfill the following requirements:

Your contract will have public variables that store the details about your coin (Token Name, Token Abbrv., Total Supply)
Your contract will have a mapping of addresses to balances (address => uint)
You will have a mint function that takes two parameters: an address and a value. The function then increases the total supply by that number and increases the balance of the address by that amount.
Your contract will have a burn function, which works the opposite of the mint function, as it will destroy tokens. It will take an address and value just like the mint functions. It will then deduct the value from the total supply and from the balance of the address.
Lastly, your burn function should have conditionals to make sure the balance of account is greater than or equal to the amount that is supposed to be burned.

<Explanation of Contract

The contract defines the public variables Token, Abbrev, and total to store the details about the token.
It includes a mapping balance that maps addresses to their respective token balances.
The mint function takes an address _add and a value _val as inputs. It increases the total supply (total) by _val and increases the balance of the _add address by _val.
The burn function takes an address _add and a value _val as inputs. It checks if the balance of the _add address is greater than or equal to _val. If so, it deducts _val from the total supply (total) and from the balance of the _add address.
The burn function includes conditionals to ensure that the balance of the _add address is greater than or equal to the amount being burned.
Now, let's test the contract:

Deploy the contract with suitable values for the token name, abbreviation, and total supply.
Use the mint function to mint tokens to a specific address and verify that the total supply and the balance of the address increase accordingly.
Use the burn function to burn tokens from a specific address and verify that the total supply and the balance of the address decrease accordingly.

>Video Walkthrough

https://www.loom.com/share/6e90136789a14cb8a3a0e81e1923a321
