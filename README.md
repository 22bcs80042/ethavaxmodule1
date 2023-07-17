# ethavaxmod1
#  Error Handling in solidity
This repository is made for my ethereum intermediate avax project which is used to execute Error Handling process in Solidity. 

## Problem Statement

create a contract  to  deploy error handling process in solidity by using revert(), assert() and require() statement.


## Description
This program  written in Solidity by using a simple contract, solidity is  a programming language used for developing smart contracts on the Ethereum blockchain.
This contract with name (MyContract) has 3 function to show the use of revert , assert and require statement in error handling process .
first we create a function name with (votingElibility) that will demonstrate the use of "require()" method , in this function we will pass 1 parameter(age) with a condition if this condition is true then the execution of the function will continue ,if not then the function will terminate and gives error message that is the second statement in require function.
Next we define a function with name (children) to demonstrate the use of "assert()" function ,in this function we pass 1 parameter as a condition if this condition will false  it will not display any error message 
Then lastly we define a function with name (old) demonstrate the use of "require()" function, in this function we put a message that will display after (if) statement is true other it will continue with else statement.

## Getting Started

### Executing Program

To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at (https://remix.ethereum.org/.)

Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., error.sol). Copy and paste the following code written by me into the file.

To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set heigher to "0.8.1" (or another compatible version), and then click on the "Compile error.sol" button.

Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the "MyContract" contract from the dropdown menu, and then click on the "Deploy" button.

After deployment of  the contract call the function VotingEligibility() , children() and ol() by providing value, it perform error handling process by  using revert, assert, require statement. 


## Author

Sulochana

## License

This project is licensed under the MIT License - see the LICENSE file for details
