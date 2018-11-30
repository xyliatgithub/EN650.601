# EN650.601 Lab Assignment 3

## Introduction
Since the advent of Bitcoin, there have been lots of blockchain frameworks and implementations invented. Generally, they fall into two categories, one is the permission ( private ) blockchain, and the other is the public blockchains. The permission blockchains only allow authorized people to join, while public blockchains allow anyone to be its member. This is the most prevailing way that people classify blockchains. 

However, some people are not satisfied with this categorization because they think a permission blockchain is not even a real "blockchain". The trust is no more decentralized and transparent, and it is hard to find any difference between permission blockchains and decentralized database. 

In this lab, you are going to explore either Bitcoin or Hyperledger Fabric, a private blockchain framework implementation, and provide your opinions on this debate. Read the following two lab instructions and make your decision.

## Bitcoin: Reaching consensus in distributed systems

The instructions can be found [here](https://witestlab.poly.edu/blog/get-rich-on-fake-bitcoins/). Similar to the second lab, this lab will be done on the geni platform. Follow the instructions closely and screenshot representive procedures or observations during the process. In addition, answer the following three questions in your report.  

1. What is the formal definition of crash failure and Byzantine failure? Use real world examples to show their diffences. How does proof of work in Bitcoin prevent such failures?
2. List at least two factors determining the probability of winning a new block in Bitcoin and justify your answer. 
3. In the Bitcoin script, there is no absolute restriction on how a machine mines a block. For example, a miner can choose not to publish the block after he successfully found prefix that meet the proof of work requirement. By customizing its own mining strategy, is there any way for a miner to increase the probability of winning a new block? If yes, decribe the strategy. If not, justify your answer.

## Hyperledger Fabric: Managaging digital certificates using private blockchain 

In this lab, you will try to build a certificate management application using smart contract in Hyperledger Fabric. You will first build the environment, run their sample code, Fabcar, then finally rewrite/replace some of the code in it. The instruction can be found [here](module2). It is recommended that you you run this lab on a virtual machine with ubuntu18.04 operating system. There is no guaranteed technical support if you choose to run it on macOS or Windows. As you did previously, screenshot periodically and include them in your report.

## Submission Instructions
- This assignment is due on December 17th (Monday) by 11:59 PM. 
- You will work in a group (to be discussed in class) for this assignment.
- Pick either one of the two modules and Submit your result at BlackBoard in one PDF file.
- Include your opinion(1 - 2 paragraph) on the debate aforementtioned in your report.
- Only one report is needed from a group. 
- Please list group members in your report explicitly. 
- Please type your solutions. In general NO hand-written report is accepted.

