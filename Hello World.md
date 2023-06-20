The "Hello World" example is a traditional starting point for learning any programming language. In Solidity, it looks like this:

```
// SPDX-License-Identifier: MIT
pragma solidity >=0.8.17 <0.9.0;

contract HelloWorld {
    function sayHello() public pure returns (string memory) {
        return "Hello, World!";
    }
}
```

This code defines a contract named HelloWorld with a function `sayHello()``. The pure keyword indicates that the function doesn't modify the contract's state. When called, it returns the string "Hello, World!"
