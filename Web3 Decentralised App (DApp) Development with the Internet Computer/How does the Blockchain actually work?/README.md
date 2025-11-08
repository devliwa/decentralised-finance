# ⛓️ How Does the Blockchain Actually Work?

**Blockchain** is a type of **digital ledger** — like a database — that stores information in a way that makes it **secure, transparent, and nearly impossible to alter**.  
It’s the technology that powers **cryptocurrencies**, **Web3**, and **smart contracts**.

---
## Resources

- [Caesar Cipher](https://csis.gmu.edu/albanese/labs/caesar_cypher.php)
- [SHA-265](https://www.movable-type.co.uk/scripts/sha256.html)
- [Blockchain Demo](https://guggero.github.io/blockchain-demo/#!/block)
- [Comparing the Difficulty of Factorization and
Discrete Logarithm: a 240-digit Experiment](https://eprint.iacr.org/2020/697.pdf)


---

## 🧱 1. The Basic Idea

Think of blockchain as a **chain of digital “blocks”**, where each block stores a list of transactions or data.  
Once a block is filled, it’s **linked to the previous one** — forming a chronological chain.

Each block contains:

1. **Data** – e.g., details of a transaction (sender, receiver, amount).  
2. **Hash** – a unique digital fingerprint of the block.  
3. **Previous Block’s Hash** – connects it to the block before it.  

If someone tries to change a block’s data, its hash changes — breaking the chain.  
This is what makes blockchain **tamper-resistant**.

---

## 🔐 2. Step-by-Step: How Blockchain Works

1. **Transaction is Requested:**  
   A user sends data or value (like a Bitcoin transfer or a smart contract action).  

2. **Transaction is Broadcast to the Network:**  
   The transaction goes to a **peer-to-peer (P2P)** network of computers called **nodes**.  

3. **Verification by Nodes:**  
   The nodes validate the transaction using **consensus mechanisms** (like Proof of Work or Proof of Stake).  

4. **Block Creation:**  
   Once verified, the transaction is combined with others to form a new **block**.  

5. **Block is Added to the Chain:**  
   The new block is linked to the existing chain using cryptography.  

6. **Transaction Complete:**  
   The blockchain is updated across all nodes, and the record becomes permanent.

---

## ⚙️ 3. Consensus Mechanisms

These are the methods used to **agree on which transactions are valid**:

- **Proof of Work (PoW):**  
  Miners compete to solve complex puzzles. Used by Bitcoin.  
- **Proof of Stake (PoS):**  
  Validators are chosen based on how much cryptocurrency they hold. Used by Ethereum.  

Consensus ensures that everyone agrees on one version of the truth.

---

## 🛡️ 4. Why Blockchain is Secure

- **Decentralized:** No single point of failure.  
- **Immutable:** Once recorded, data can’t be changed easily.  
- **Transparent:** Everyone can view transactions on the public ledger.  
- **Encrypted:** Uses advanced cryptography for privacy and integrity.  

---

## 💡 5. Real-World Uses of Blockchain

- **Cryptocurrencies:** Bitcoin, Ethereum, Solana, etc.  
- **Smart Contracts:** Automate agreements (e.g., DeFi apps).  
- **Supply Chain Tracking:** Trace goods from origin to delivery.  
- **Digital Identity:** Secure, self-owned online identity.  
- **Voting Systems:** Transparent and tamper-proof elections.  

---

> 🧠 **In short:**  
> Blockchain is a distributed, transparent ledger that records information securely — without needing a central authority.
