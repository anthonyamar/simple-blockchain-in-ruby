# Simple Blockchain using Ruby
Improved version of "Build your own blockchain from scratch in 20 lines of Ruby!"	from https://github.com/openblockchains/awesome-blockchains/tree/master/blockchain.rb and inspired by "Let's Build the Tiniest Blockchain In Less Than 50 Lines of Python by Gerald Nash" from https://medium.com/crypto-currently/lets-build-the-tiniest-blockchain-e70965a248b
<br>

# Run it

```
$ ruby blockchain.rb
```
It will create the first block and then, prompt you to make a transaction by asking your name, what you want to send, the quantity, and for who. <br><br>
You can set multiple transaction in one block. When you finished to write the transactions, the current block is added to the blockchain and take place in the ledger. <br>

## Live code 

Here is a live talk and programming from scratch, with explanation of what is blockchain and how work proof of work, blocks, hash, cryptography... The talk is in french for the french school The_Hacking_Project. <br>
https://www.youtube.com/watch?v=SvfluWtb8a0



# Credits
This is an improved version of https://github.com/openblockchains/awesome-blockchains/tree/master/blockchain.rb <br><br>
Thoses little blockchain are really great for understanding how blockchains works. <br><br>
I wanted to learn about blockchain, so I'd just combine those three programs into one, and added the possibility to asks user for transaction. <br><br>
I've also add dynamics instance variable name with auto incrementation so people can implement it in bigger programs or rails application and create blocks with any kind of data (just replace prompt's methods).<br><br>
Huge thanks to openblockchains, I've learned a lot by having fun with your Ruby scripts! ;-). 
