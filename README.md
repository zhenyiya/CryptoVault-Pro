# CryptoVault Pro

Crypto Wallet Application.

## Features

- Secure wallet address generation
- QR code integration
- Real-time transaction monitoring
- Advanced encryption
- Send & Receive
- Portfolio Management
- Real-time Price Monitoring
- Staking Options
- Swaps
- Live market data and pricing
- Trading Interface
- Transaction History

## Technology Stack

- React Native
- Expo
- TypeScript
- React Navigation
- Recoil

## Quick Start

### Prerequisites

- Node.js (v14 or higher)
- npm or Yarn package manager
- Expo CLI
- iOS Simulator or Android Emulator (for testing)

### Installation

1. **Clone the repository**

    ```bash
    git clone <https://github.com/zhenyiya/cryptovault-pro.git>
    cd cryptovault-pro
    
    ```

2. **Install dependencies**

    ```bash
    # Using npm
    npm install
    ```

3. **Start the development server**

    ```bash
    # Using npm
    npm start
    ```

4. **Run on your preferred platform**

    ```bash
    # iOS
    npm run ios
    
    # Android
    npm run android
    
    # Web
    npm run web
    ```


## Structure

```
cryptovault-pro/
├── app/
│   ├── hooks/            
│   ├── navigation/       
│   ├── screens/          
│   │   ├── Exchange.tsx  # Trading interface
│   │   ├── Home.tsx      # Main dashboard
│   │   ├── Profile.tsx   # User profile
│   │   ├── Receive.tsx   # Receive cryptocurrency
│   │   ├── Send.tsx      # Send cryptocurrency
│   │   ├── Swap.tsx      # Token swapping
│   │   └── Trade.tsx     # Trading platform
│   └── styles/           
├── App.tsx              
├── package.json          
└── tsconfig.json         

```