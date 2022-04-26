## Msg.sender

Every function within a solidity contract sits doing nothing until it is called externally. 

To make this happpen, `msg.sender` is used to call the fuction.

`msg. sender` referes to the adreess or smart contract that calls the current solidity contract.


Using `msg.sender` gives the application Ethereum's security as one cannot tamper with the sender's data unless they have their private key

## Require

Whenever an a user activate's a contract's functions using `msg.sender` they are able to reactivate is as many times as they want.

In other scenarios, making a contract's functions open to the user to call at anytime may not be ideal depending on what the contract does.

To limit the freedom of a user when calling a function, `require` is used to verify the truthness or falsness of a statement which then determines the deneial or acceptance to continue calling the function.
