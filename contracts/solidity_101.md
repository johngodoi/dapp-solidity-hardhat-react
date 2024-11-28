// SPDX-License-Identifier: MIT
``` solidity
pragma solidity ^0.8.4;

import "filename";
```

// this is a single line comment

/*
this is a
multi line comment
*/

1. state variables

``` solidity
contract Test {
    uint storedData;
    constructor() public {
        storedData = 10;
    }
}
```

2. local variable
``` solidity
contract Test {
    uint storedDAta;

    constructor() public {
        storedData = 10;
    }

    function getResult() public view returns(uint) {
        uint a = 1;
    }
}
```

3. global variables
``` solidity
block.number();
blockhash();
block.gaslimit();
```



4. types
``` solidity
bool flag = true / false


int8 to int256
uint8 to uint256

string name = "john"

address coinbaseWallet (20 bytes) = 0x2122343...
```
5. operators

``` solidity
5 + 4
+ = operator
```
5.1. arithmetic operators
``` solidity
+, -, /, *, %, ++, --
```
5.2. comparison operators
``` solidity
==, !=, >, <, >=, <=
```
5.3. logical operators
``` solidity
&&, ||, !
```
5.4. bitwise operators
``` solidity
&, |, ^, >>, <<
```
5.5. assignment operator
``` solidity
=, +=, -=, /=, *=
```
5.6. conditional
``` solidity
if condition if true? do true : false;
```
5.7. conditionals
``` solidity
if, if else, else 
if somethin else if something else 
```
6. loops
6.1. while loop
``` solidity
int n = 10
while n> 0:
 n--;
```
6.2. do while loop
``` solidity
int n = 10;
do {
    n--;
} while (n>0)
```
6.3 for loop 
``` solidity
int n = 10;
for(int i =0; i<n: i++){
    // do something with i
}
```
7 functions
``` solidity
function getSum(int a, int b) public view returns(int){
    return a+b;
}

int a = 10;
function setValue(int x) {
    a=x;
}
```