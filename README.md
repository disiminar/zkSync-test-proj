# zkSync-test-proj
This is my first zkSync era dApp. It was build on testnet. The smart-contract adress on block explorer: [0xF7087df5b2A49205d43A8B3B7bc32b0C28C45179](https://goerli.explorer.zksync.io/address/0xF7087df5b2A49205d43A8B3B7bc32b0C28C45179)
This is a simple smart contract, that let you change the output on the page. Sceenshots below.
![](https://i.imgur.com/xbjo7kE.png)
![](https://i.imgur.com/baWojqb.png)
![](https://i.imgur.com/rkNfxcw.png)
![](https://i.imgur.com/7jcHF6z.png)
![](https://i.imgur.com/r13vHLd.png)
![](https://i.imgur.com/pj05pUf.png)

So basically me made a transaction that changes value of variable `_greeting`. We can see it on explorer by Transaction hash 0xe7a246616012bde16d026717071317ca54b7f9d212398e1588a2e2875cb6ed50 or [this link](https://goerli.explorer.zksync.io/tx/0xe7a246616012bde16d026717071317ca54b7f9d212398e1588a2e2875cb6ed50)

Here is the general info, for example we can see on in which block the transaction took place, and we can look at it if its needed. Block number `12600927` , we can search it on explorer or visit [this link](https://goerli.explorer.zksync.io/block/12600927)
![](https://i.imgur.com/jaCOgrp.png)
![](https://i.imgur.com/63QodW6.png)

Also,  it is worth adding to the screenshot where general information about the transaction was shown, that we can both view the current value of `_greeting` and change its value directly in the smart contract on ***Explorer***. To do this, go to the ***Contract*** and click ***Read*** or ***Write***, depending on what we need.

Everything would be shown below.

- Opening a smart contact
![](https://i.imgur.com/m2sx9rw.png)
- Going to the ***Contract*** tab
![](https://i.imgur.com/Q9RVYuC.png)
> Read
![](https://i.imgur.com/kJwaR90.png)
![](https://i.imgur.com/VKM14TW.png)
- It shows us current value of `_greeting`, but the function is called ***greet***
![](https://i.imgur.com/mARnJWy.png)
- Now lets try to write
![](https://i.imgur.com/6gO9tAX.png)
![](https://i.imgur.com/h8FcnCA.png)
![](https://i.imgur.com/QvbID5V.png)
- Now we sign a transaction
![](https://i.imgur.com/A0Elo57.png)
- Now we get the transaction hash [0x118244af91773dc1390bb555fda10878195e5d4f073a3e27baaf848857d6aa47](https://goerli.explorer.zksync.io/tx/0x118244af91773dc1390bb555fda10878195e5d4f073a3e27baaf848857d6aa47)
![](https://i.imgur.com/VfFmYDX.png)
- Lets check transaction that was shown to us
![](https://i.imgur.com/DCFmuuD.png)
- Everything seems alright. now lets ***Read*** the value of `_greeting`, becouse we just changed it
![](https://i.imgur.com/pIj3yid.png)
### Perfectly! everything worked out for us! :)
