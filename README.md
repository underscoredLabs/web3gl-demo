# web3gl-demo


https://ipfs.io/ipfs/QmRTLk56bniAxTF4BnSGZQsTyNAZpESrNoTxP7jdtKg13a/

https://youtu.be/WkWYPuFHM5k


```solidity
/*
ABI
[ { "inputs": [], "name": "increment", "outputs": [], "stateMutability": "nonpayable", "type": "function" }, { "inputs": [], "name": "x", "outputs": [ { "internalType": "uint256", "name": "", "type": "uint256" } ], "stateMutability": "view", "type": "function" } ]

Rinkeby Contract
0xB6B8bB1e16A6F73f7078108538979336B9B7341C
*/

pragma solidity >=0.7.0 <0.9.0;

contract Increment {
    uint public x = 0;
    
    function increment() public {
        x++;
    }
}
```

```json
[
	{
		"inputs": [],
		"name": "increment",
		"outputs": [],
		"stateMutability": "nonpayable",
		"type": "function"
	},
	{
		"inputs": [],
		"name": "x",
		"outputs": [
			{
				"internalType": "uint256",
				"name": "",
				"type": "uint256"
			}
		],
		"stateMutability": "view",
		"type": "function"
	}
]
```
