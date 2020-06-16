# BlockChain implementation in python

BlockChain is **public database where data (in the form of groups of transactions) is stored in a container called a block and these blocks are added to form an immutable chain (hence blockchain) with data added in the past**.BlockChain provides an **alternative** to individuals who believe that **today’s banking systems are a scam or subject to failure**.There are varied applications of it in the finance , insurance and  medical industry because of it's unique features.

![](/images/BlockChain.png)

Features are as below :

1.Data stored in blockchain is **immutable** and cannot be changed easily.  
2.**Ensures transparency** as it is **decentralized** as well as an **open ledger**.  
3.Removes requirement of third party authorisation , thereby helps in **fastening the process** as well as **reduction in costs**.  

Through the notebook , I have implemented basic blockchain in python.Steps followed are :-

1. Importing the required libraries such as **Hasher (for hash values) and Datetime (for timestamp).**
2. Defining the **block structure**. A block comprises of index , timestamp , data , hash value of the previous block and hash value of the current block.
3. Creating **first block of the blockchain**. It is also known as the genesis block.
4. Storing the transaction sent by the user in an appropriate format.
5. **Solving a puzzle** to mine a new block (to store the transaction) using **proof of work algorithm**.
6. **Rewarding the miner** with a digital curreny coin for the work done.
7. Accumulating all the other details for the mined block like timestamp , hash value of previous block to the mined block 
8. **Chaining the mined block with the rest of the blocks.**
9. **Broadcast each node's version of the chain** to the others and **maintaining the largest chain as the single exisitng chain** in case of more than one version of the chain.

References :

https://medium.com/crypto-currently/lets-build-the-tiniest-blockchain-e70965a248b

https://medium.com/crypto-currently/lets-make-the-tiniest-blockchain-bigger-ac360a328f4d
