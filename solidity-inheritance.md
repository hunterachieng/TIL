# Inheritance

In Solidity, it is considered a good practice to seperate code into various contracts as a single contract tends to get pretty long.


SInce code will be broken and used to create new contracts, it is a good idea to use inheritance to allow the new contract to extract some functions from
the previous contract.

```
contract Doge{
function add () public{
//write something
}
}
```

The above contract contains funciton add that does something. When we use inheritance, we will have to call the contract into a new contract.

```

import './somefile.sol';

contract BabyDoge is Doge{
function subtract(){
//Write something
}
}
```


The above contract explains how inheritance is carried out in solidity. Before inheritance happens, the contract to be inheritted must be imported into the new contract file. 

This means that `BabyDoge contract` has inherited from `Doge` and when compiled, it will have
access to all public functions in the  `Doge` contract. 
