# Would you trust a system where no one is IN CHARGE?

## Introduction
If you have heard of blockchain, you must know that one of the selling point is **decentralization**. This would mean that, if no one is in charge for things to run smoothly, the system must be very **perfect**. You might have heard terms like consensus, cryptographic hashing, private key and public key and so many other terms in relation to this technology. Well, in this article I will explore what makes blockchain technology secure and establish  if there is a chance of **breaking** it. 

## Learning outcomes
1. Understand how information in blockchain is stored securely.
2. Know the factors that might compromise blockchain security.

## Old storage of information
If you have a very important information like record of payments, certificates, contracts etc. you might want to store them securely. If you are rich, you can buy a safe and store it there. That way you are sure that its only you who can access the information. If you continue adding more information, eventually the safe will be full and you will need to either discard the old information to make space for the new information or buy another safe to store the new information. Think of a place like a land registry, where we need to have the records of all the lands and we need to keep updating who owns the land during a particular period. That is how information is stored traditionally. There are risks of information being altered or even getting lost hence credibility is lost.

## New safe
In this digital era, blockchain technology has come to rescue us from this. Just like information is stored in a safe, in blockchain information is stored in a block. Once the block is full, another block is created and its linked to the previous block. Well, that's just part if it. 

### How does the linking of blocks happen?
When this data is full in one block, it is bundled together and its given a unique serial number. In blockchain we call this a **hash**. This has been obtained through computation of mathematical algorithms through a process called **Cryptographic hashing**. Any new block added must be linked to the previous block. This makes the information **Chronological**.

#### Why is the hash important?
This has is the one that is stored in the next block so that a link between the two blocks is established(*the chain*). Any time you change the information in a particular block, this hash changes. If there is a difference between the hashes, that means that information was tampered with. This guarantees **Immutability**, meaning once information is stored in a block it cannot be changed. You will be able to know if the information is credible or not. This is useful in verification systems like in payments, voting and other applications.

#### How does hashing guarantee security?
For a block to be linked to the next block, a lot of work has been done by special people called the **Miners who are also validators**. These are the people who are responsible for adding the information to the blocks and adding valid blocks to the chain. They do some mathematical computations to verify information and create a new block to be added to the chain. They have invested heavily on hardware infrastructure to make sure the mathematical calculations are done faster. The process of computing mathematical computations to show some work done is called **proof-of-work**. Only valid blocks are added. 
The longer the chain, the harder the process and more power to compute is need. That makes it hard for someone to do computations for all the blocks available  to change or access the information. That is security.

## What if I want to change the information?
Since blockchain is decentralized, you might want to cheat and change the information in a particular block. However, this can be difficult because every participant in the blockchain have the same record of all the blocks present in the chain. If one of the participants has a different record, it can be compared to the other participants its rejected. This is possible through **Consensus Mechanism**. 

However, if there are **50 + 1** participants with same record the information is changed. This is **Feasibly Impossible**. You would need a lot of computational power to be able to change all the records of all the participants in the network and this is very expensive. That is why governments fear it  so much.

### What if the validators(miners) are compromised?
Every human has a greedy part and might want the power to control the chain for their own benefits. In blockchain the honest validators are rewarded. This is how they make their money. No one wants to break a hand that feeds them. 
They also spend so much resources to validate the blocks and its their investment. Being compromised would only mean losses for them. This **Incentives** is a reward mechanism for honest validators. 

## How do I interact with information in a blockchain?
Unlike information stored in the safe where you are the only one who can guarantee that whatever I claim is true, in blockchain there is **Private and Public keys**.
**Private key** is used to sign the information. Just like a message is sign by the sender.
This should be private as the word suggests. This is like a key to access the safe and access your information that was stored.
**Public key** This is visible to the public. Think of it like an address of safe that is made public.
Anyone with your public key can write to you some information.
To be able to read the information written to you, you use your private key to access it.
The combination of this make sharing information in a blockchain secure. Once you lose your private key, you lose your information because there is no way to claim you are the owner.

# Conclusion
While blockchain technology is here with us, its good to know where issues may arise and compromise the security of your data.I remember the way I was scammed 98$ was through me sharing my private key in the name of bitcoin mining.I was naive and I didn't know. I was just a freshman in campus. This information helps you understand that blockchain systems have security mechanisms but might be compromised in one way or another. You need to be very careful how you interact with this systems.
1. There are a lot scams related to mining. Now you know that you need a lot of resources to become a miner. If someone is telling you he will do it for you for 100$, think twice!
2. There are still risks of attacks. Phishing and social engineering becoming more prevalent as the blockchain is difficult to hack.
- [Nobitex Attack 2025](https://www.techopedia.com/crypto-hacks-low-tech-exploits-rise)

-[The Bybit- The Billion Dollar attack](https://en.wikipedia.org/wiki/Bybit). On February 21, 2025, Bybit announced on X that it had been hacked.[4] According to Bybit, about 400,000 Ethereum was stolen,[11][12] which had an approximate notional value of $1.4 billion, making it the largest cryptocurrency exchange hack to date. 

Blockchain has so much hope, I still believe we should be on-chain. As a secure way to store information, provide governance and as a solution to social problems like corruption. 
**Yes, Trust the protocol(the system)**

Engage with me on my socials [LinkedIn](www.linkedin.com/in/elijah-gathanga-88b601262) [on X](https://x.com/charagu_elijah)
Have a look at my [Github](https://github.com/GathangaElijah)
