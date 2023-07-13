# TOKEN CREATION
This readme file provides a step-by-step guide on how to create a token.

## DESCRIPTION
In this we have tokenName, tokenabbreviation and totalSupply.

1.tokenName:
It is a string data type that represent our token name.

2.tokenAbbrev:
It is also a string data type which represents the abbrevation of token.

3.totalSupply:
It is  an unsigned integer that will make sure that our totalSupply can never be negative.

### MAPPING: 
This will h map our addresses to balances:

#### Implementation:
1)For token creation:
To creat token we need mintfunction that will increase our addresses value and balance factor. 

2)For Destruction:
To perform destruction we have to creat burnfunction which will decrease our addresses value as well as balance factor.It also has a condition to check that the balance of the count must be greater than equal to amount we suppose to burn.

##### License
This project is licensed under the Solidity Assessment License - see the LICENSE.md file for details.
