# Smart Contract Sample -- ERC20

## How to play around

```bash
$ npm i -g truffle
$ git clone https://github.com/ngo275/ERC20-sample.git
$ cd ERC20-sample
$ truffle compile
$ truffle develop

$ > migrate
$ > let token = await ERC20Basic.deployed()
$ > let accounts = await web3.eth.getAccounts()
$ > token.balanceOf(accounts[1])
$ > token.transfer(accounts[1], 1000)
$ > token.balanceOf(accounts[1])
```

