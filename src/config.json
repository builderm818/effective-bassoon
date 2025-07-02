// CDA: CBX Config Module
require('dotenv').config();

module.exports = {
  solanaRpcUrl: process.env.SOLANA_RPC_URL,
  walletPrivateKey: process.env.WALLET_PRIVATE_KEY,
  arbitrage: {
    minProfitThreshold: 0.01,
    maxSlippage: 0.003
  },
  monitoring: {
    pairs: ['SOL/USDC', 'ETH/USDC'],
    pollingInterval: 5000
  },
  watchdog: {
    enabled: true,
    sandbox: true
  }
};