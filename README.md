# 🐾 OnePet Game

**OnePet** is a Web3-powered virtual pet simulation game where players adopt, care for, and evolve futuristic cats.  
Each cat is an **on-chain NFT** with unique traits, enabling players to truly own, trade, and interact with their digital pets.

> 🎯 Built for **OneHack 2025** — OneChain’s Web3 hackathon series.  
> Author: [One Milky Way](https://github.com/onemilkyway)  
> Solo Submission

---

## 🚀 Pitch
OnePet brings nostalgic virtual pet gameplay into Web3.  
Players can adopt AI-driven cats, interact, feed, and train them — all stored securely on-chain using **OneWallet** for authentication and transactions.

---

## 🎮 Core Gameplay
- 🐱 **Adopt a Cat:** Mint your own NFT cat with unique metadata.  
- 🍖 **Care & Feed:** Feed and play to keep your cat happy and healthy.  
- 💎 **Earn Rewards:** Gain tokens or collectibles for daily interaction.  
- 🔗 **Own it Forever:** Every pet exists as an NFT stored on OneChain.  
- 👛 **OneWallet Integration:** Seamless login and transaction signing.

---

## 💡 Key Features
| Feature | Description |
|----------|--------------|
| Web3 Login | Connect via OneWallet to authenticate player |
| NFT Ownership | Each cat minted as NFT with unique ID and traits |
| On-chain Progress | Pet stats (e.g. hunger, level) stored partially on-chain |
| Simple Play UI | Lightweight HTML/JS interface for quick demo |
| Expandable | Future-ready for marketplace, breeding, or token staking |

---

## 🧩 Tech Stack
- **Frontend:** HTML, CSS, JavaScript (Vite)
- **Web3 Library:** ethers.js
- **Wallet:** OneWallet SDK
- **Blockchain:** OneChain Layer 1
- **Storage:** IPFS / static JSON metadata

---

## 🎥 Demo Video
🎬 [Watch the 3-minute demo video](https://bit.ly/4hlt8ht)

---

## 💻 How to Run Locally

```bash
# 1️⃣ Clone the repository
git clone https://github.com/onemilkyway/OnePet-Game.git
cd OnePet-Game

# 2️⃣ Install dependencies
npm install

# 3️⃣ Add your environment variables (create .env)
echo "REACT_APP_RPC_URL=<ONECHAIN_RPC_URL>" >> .env
echo "REACT_APP_CONTRACT_ADDRESS=<NFT_CONTRACT_ADDRESS>" >> .env

# 4️⃣ Start the app
npm run dev
