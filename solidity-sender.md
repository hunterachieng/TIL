## Msg.sender

Every function within a solidity contract sits doing nothing until it is called externally. 

To make this happpen, `msg.sender` is used to call the fuction.

`msg. sender` referes to the adreess or smart contract that calls the current solidity contract.


Using `msg.sender` gives the application Ethereum's security as one cannot tamper with the sender's data unless they have their private key