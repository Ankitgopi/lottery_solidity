## 🧾 Lottery Smart Contract (Solidity)

This contract implements a simple lottery system on Ethereum.

- The **manager** deploys the contract and controls admin-only actions.  
- Users can **participate** by sending exactly **1 ETH**, and their address is added to the players list.  
- The manager can check the **contract balance** and **pick a winner** once at least 3 players have joined.  
- A winner is chosen using a pseudo-random value derived from block data.  
- The selected winner receives the **entire contract balance**, and the players list resets for the next round.
