# Moonshot Swap Transaction Backend

This is a Node.js and Express backend project that facilitates moonshot swap transactions using moonshot-sdk, TypeScript, Solana web3, and solana/spl-token. It listens for swap (buy/sell) requests and creates transactions accordingly. The project is deployable to Vercel.

## Features
- Handle swap (buy/sell) requests.
- Create moonshot swap transactions.
- Integration with Solana blockchain.
- Deployable to Vercel.

## Technologies
- Node.js
- Express.js
- TypeScript
- moonshot-sdk
- @solana/web3.js
- @solana/spl-token

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/dappsol/moonshot-swap.git
   cd moonshot-swap
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Update the `config.ts` file with any additional configuration settings as needed.

## Usage

### Starting the Project
To start the project, run:
```bash
npm start
```
or
```bash
yarn start
```

The project will run at:
```
http://localhost:9000
```

### Swap Endpoint
The swap endpoint is available at:
```
http://localhost:9000/api/moonshot/swap
```

### Creating Transactions
To create a transaction, use the following parameters:

- `mintAddress`: Token mint address for buying/selling.
- `amount`: When buying, input SOL amount; when selling, omit this value.
- `tradeDirection`: Use `"BUY"` for buying and `"SELL"` for selling.
- `slippageBps`: Default is `100` and can be omitted.

## Contact

### Please fork to use it and follow me on github.

### If you want more customized app, please contact [@s0lb0t](https://t.me/s0lb0t) in Telegram and [.s0lb0t](https://discordapp.com/users/1074553493974691840) in Discord
