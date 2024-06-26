SimpleStorage is point of reference smart contract written in Solidity version 0.8.0, licensed with MIT license, that stores and
manipulates a single unsigned integer (storedValue) which has an exact size of 256 bits as determined by the keyword uint. 
The contract has three public functions: setValue(uint256 _value) that stores the value of _value; getValue() a view function to 
receive in-state stored final and doubleValue() calculates twice as much. This contract shows the most simplest form of state management
and interaction in Solidity, with functionality to Set a value that can be later retrieved or further updated.
