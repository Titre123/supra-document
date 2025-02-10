# Supra DApp Starter Pack Documentation

## Overview

Supra Starter Packs provide boilerplate templates for rapid DApp development, incorporating essential configurations, libraries, and industry best practices. These packs enable developers to bypass time-consuming setup processes and focus on building core application functionality.

## Key Features

### Development Efficiency
- Pre-configured development environment
- Built-in testing framework
- Hot-reloading for faster development
- Automated build pipelines
- Code linting and formatting tools

### Framework Support
- Vue.js
- React
- Next.js
- Angular

### Integrated Technologies
- Starkey Wallet integration
- Web3 libraries (ethers.js, viem, starknet.js)
- Modern UI frameworks (Tailwind CSS, Material UI)
- TypeScript support
- Smart contract development tools

## Available Starter Packs

### 1. Vue DApp Starter
Perfect for developers preferring Vue.js ecosystem
```bash
git clone https://github.com/supra-labs/dapp-starter-vue.git
```

### 2. React DApp Starter
Ideal for React-based applications
```bash
git clone https://github.com/supra-labs/dapp-starter-react.git
```

### 3. Next.js DApp Starter
Optimized for server-side rendering and static generation
```bash
git clone https://github.com/supra-labs/dapp-starter-nextjs.git
```

### 4. Angular DApp Starter
Enterprise-ready Angular template
```bash
git clone https://github.com/supra-labs/dapp-starter-angular.git
```

### 5. Smart Contract Starter
Foundation for blockchain development
```bash
git clone https://github.com/supra-labs/smart-contract-starter.git
```

## Getting Started

### Prerequisites
- Node.js (v16.0.0 or higher)
- npm or yarn package manager
- Git

### Installation Steps

1. Clone your chosen starter pack:
```bash
git clone https://github.com/supra-labs/dapp-starter-[framework].git my-dapp
cd my-dapp
```

2. Install dependencies:
```bash
npm install
# or
yarn install
```

3. Configure environment variables:
```bash
cp .env.example .env
```

4. Start development server:
```bash
npm run dev
# or
yarn dev
```

## Project Structure

```
my-dapp/
├── src/
│   ├── components/        # Reusable UI components
│   ├── pages/            # Route components/pages
│   ├── contracts/        # Smart contract interfaces
│   ├── hooks/            # Custom hooks
│   ├── utils/            # Helper functions
│   └── config/           # Configuration files
├── public/               # Static assets
├── tests/                # Test files
├── .env.example          # Environment variables template
└── package.json          # Project dependencies
```

## Features in Detail

### Wallet Integration
- Built-in Starkey Wallet connection
- Account management
- Transaction signing
- Balance checking
- Network switching

### Smart Contract Integration
- Contract deployment scripts
- ABI management
- Contract interaction utilities
- Event listening

### UI Components
- Wallet connection button
- Transaction status indicators
- Network selector
- Account display
- Balance display

## Development Guidelines

### Code Style
- Follow the established project structure
- Use TypeScript for type safety
- Implement proper error handling
- Write unit tests for critical functions
- Document complex logic

### Testing
```bash
# Run unit tests
npm run test

# Run e2e tests
npm run test:e2e

# Generate coverage report
npm run test:coverage
```

### Building for Production
```bash
# Build the application
npm run build

# Preview production build
npm run preview
```

## Troubleshooting

### Common Issues

1. **Wallet Connection Failed**
   - Ensure Starkey Wallet is installed
   - Check network configuration
   - Verify correct RPC endpoints

2. **Build Errors**
   - Clear node_modules and reinstall
   - Update dependencies
   - Check TypeScript compatibility

3. **Contract Interaction Issues**
   - Verify contract addresses
   - Check network configuration
   - Ensure sufficient gas

## Support and Resources

- GitHub Repository: [https://github.com/supra-labs](https://github.com/supra-labs)
- Documentation: [https://docs.supra.com](https://docs.supra.com)
- Community Discord: [https://discord.gg/supralabs](https://discord.gg/supralabs)
- Technical Support: support@supra.com

## Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to your fork
5. Submit a pull request

## License

MIT License - see LICENSE.md for details
