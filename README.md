# GuardianDAO
A decentralized emergency response system powered by DAOs, smart contracts, and blockchain identity."
GuardianDAO/  
├── contracts/           # Smart Contracts (Solidity)
│   ├── EmergencyFund.sol  # Manages crisis funding
│   ├── GuardianDAO.sol    # DAO governance logic
│   └── ReputationNFT.sol # SBTs for verified responders
│
├── frontend/            # Web3 Frontend (React/Next.js)
│   ├── public/          # Assets (logos, etc.)
│   ├── src/             # Main app
│   │   ├── components/  # UI (Proposals, Voting, etc.)
│   │   └── pages/       # Next.js routes
│   └── package.json
│
├── scripts/             # Deployment & utility scripts
│   ├── deploy.js        # Hardhat/Foundry scripts
│   └── verify.js        # Contract verification
│
├── docs/                # Pitch deck, diagrams, whitepaper
│   ├── GuardianDAO_Pitch.pdf
│   └── Architecture.png
│
├── .env.example         # Environment variables (API keys)
├── README.md            # Project overview
├── LICENSE              # MIT
└── package.json         # Node.js dependencies
