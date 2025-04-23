# Solana dApp Scaffold Next

A modern, production-ready scaffold for building Solana dApps using Next.js. This scaffold provides a robust foundation for developing decentralized applications on the Solana blockchain with an emphasis on developer experience and best practices.

Responsive                     |  Desktop
:-------------------------:|:-------------------------:
![](scaffold-mobile.png)  |  ![](scaffold-desktop.png)

## 🚀 Features

- ✅ Full Wallet Adapter integration with auto-connect and network switching
- ✅ Modern Next.js 13+ features and App Router support
- ✅ Comprehensive state management setup
- ✅ Solana Web3.js integration with connection provider
- ✅ Responsive design and mobile-first approach
- ✅ TypeScript for enhanced developer experience
- ✅ Tailwind CSS for modern styling
- ✅ Built-in notification system
- ✅ Component library integration
- ✅ Easy-to-use hooks for Solana interactions

## 🛠 Quick Start

1. **Clone and Install**
```bash
git clone <your-repo-url>
cd solana-scaffold-main
npm install
# or
yarn install
```

2. **Set Up Environment**
```bash
cp .env.example .env.local
# Configure your environment variables
```

3. **Run Development Server**
```bash
npm run dev
# or
yarn dev
```

Visit [http://localhost:3000](http://localhost:3000) to see your app.

## 📁 Project Structure

```
├── public/          # Static assets
├── src/
│   ├── app/         # Next.js 13+ App Router pages
│   ├── components/  # Reusable UI components
│   ├── contexts/    # React contexts
│   ├── hooks/       # Custom React hooks
│   ├── models/      # TypeScript interfaces and types
│   ├── stores/      # State management
│   ├── styles/      # Global styles
│   └── utils/       # Helper functions and constants
├── .env.example     # Environment variables template
├── next.config.js   # Next.js configuration
└── tailwind.config.js # Tailwind CSS configuration
```

## 🔗 Solana Integration

This scaffold includes several key Solana integrations:

- **Wallet Adapter**: Full support for Solana wallets with auto-connect capability
- **Transaction Handling**: Simplified transaction creation and signing
- **Network Support**: Easy switching between mainnet, testnet, and devnet
- **Program Integration**: Ready-to-use hooks for interacting with Solana programs

## 🧩 Key Components

- Wallet connection manager
- Transaction notification system
- Network status indicator
- Balance display
- NFT gallery example
- Token transfer interface

## 🛠 Development

### Prerequisites

- Node.js 16+ and npm/yarn
- Solana CLI tools (optional)
- A modern web browser

### Recommended Tools

- VS Code with Solidity and React extensions
- Solana Playground for program development
- Phantom or Solflare wallet browser extension

## 📚 Resources

- [Solana Cookbook](https://solanacookbook.com/)
- [Solana Documentation](https://docs.solana.com/)
- [Next.js Documentation](https://nextjs.org/docs)
- [Wallet Adapter Documentation](https://github.com/solana-labs/wallet-adapter)

## 🚀 Deployment

This project can be deployed on any platform that supports Next.js applications. We recommend:

1. **Vercel** (Recommended)
   - Connect your repository
   - Configure environment variables
   - Deploy automatically

2. **Manual Deployment**
```bash
npm run build
npm run start
```

## 🤝 Contributing

Contributions are welcome! Please read our [Contributing Guide](CONTRIBUTING.md) for details on our code of conduct and the process for submitting pull requests.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## ⭐️ Support

If you find this scaffold helpful, please give it a star on GitHub and share it with others!
