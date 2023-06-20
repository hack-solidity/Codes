Below is an example of a simple Solidity contract that represents a basic application:

```
// SPDX-License-Identifier: MIT
pragma solidity >=0.8.17 <0.9.0;

contract MyFirstApp {
    uint256 public myNumber;

    function setNumber(uint256 _number) public {
        myNumber = _number;
    }

    function getNumber() public view returns (uint256) {
        return myNumber;
    }
}
```

In this contract, we have a state variable `myNumber` of type `uint256`, which can store unsigned integers. The `setNumber()` function allows us to update the value of `myNumber`, and `getNumber()` retrieves its current value.
