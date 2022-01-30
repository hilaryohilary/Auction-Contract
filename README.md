# Auction-Contract
This is a simple ethereum auction smart contract written with solidity and truffle framework

To clone the repository run the command : git clone https://github.com/hilaryohilary/Auction-Contract.git in your cli.

Make sure that your solidity compiler is ^0.8.9.
All the code for this smart contract can be found in contract/auctionContract.sol.

Note: This program is a simple implementation of an smart auction on ethereum blockchain.
It is not optimized for production and is not intended for such purposes. 

This auction program enable different people to bid for an item with ethereum for a limited amount of time.
This contract stores the address of bidders and the amounts they have bid and also the highest bid.
The address with the highest bid wins the auction and funds of the other bidders can be withdrawn by them.
