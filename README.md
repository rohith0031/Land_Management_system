# Land_Management_system
BlockChain Project - Land Management System using Proof of work Consensus algorithm
Programming Language used: Python
Requirements to be installed:
>ipython 
>pip
Working of the BlockChain:
1) A block contains:
2) Block Index 
3) Hash value of the previous block
4)Nonce 
5) TimeStamp
6) Name of the buyer 
7) Name of the seller
8) Merkle root
The difficulty level of the block:
A valid hash using SHA256 should have four leading zeros.
During verification, two constraints are checked for the validity of blockchain:
1) If the buyer and seller are already registered in the system.
2) Seller needs to be the latest owner of the land which he is selling.
Commands for running the code:
1)ipython
2)import filename(blockchain)
3) bc=blockchain.blockchain()
4)bc.mine_a_block("Name of the owner",Id of the land) in order to register a user with a property
5) bc.mine_a_transaction("Name of the seller","Name of the buyer",id of the property) in order to 
perform the operation
6)bc.view_transaction(Id of the property) Viewing the transaction history of the property
