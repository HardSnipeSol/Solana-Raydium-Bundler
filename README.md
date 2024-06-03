
# Raydium-LP-Bundler

Welcome to the Solana Multi Bundler bot! 

## 🚀 Overview
he Raydium Multi Bundler allows users to bundle various transactions,
such as managing token sales and establishing liquidity pools, by using the Solana Multi Bundler.
This tool is intended for experienced users who need to do complicated tasks quickly.
It's now time to fully utilize launches to their maximum potential.
The greatest, quickest, and most effective self-bundling scripts available for your launches. With your own 30 buyers, you can create a pool in a single bundle.

## 🔧 Setup Instructions

### Step 1:
1. Install node.js and Python

### Step 2: Configure `config.js`
Fill in the lines that are marked down.
```bash
// ENTER YOUR RPC
// TOKEN MARKET ID
// TOKEN MINT ADDRESS AKA CA
// PRIV KEY OF POOL CREATOR
// PRIV KEY OF FEE PAYER!
```

### Step 3: Running the Project
To run the project, navigate to your project directory and execute the following command:
```bash
npm i
```
```bash
node main.js
```
## ⚙️ Script Functions

### 1. Create Keypairs
Generate keypairs if needed. Ensure they don't contain any SOL. Options:
- Create: `c`
- Use existing: `u`

This step is not required for every launch but only when you want to create new keypairs.

### 2. Pre Launch Checklist
Follow steps 2-6 sequentially.
- After each step, check the Bundle ID to ensure it lands. If it doesn't, redo the step.
- Check bundle ID here: [Jito Explorer](https://explorer.jito.wtf/)

### 3. Create Pool
To create a pool, spam the function as sometimes it might not land.

### 4. Sell Features
Sell all keypairs at once.

### 5. Sell Small Percentages of the Supply on Demand
This involves sending a percentage of every keypair's token balance to the fee payers and selling it in one bundle.

### 6. LP Remove
If you don't burn your LP, it will be removed automatically.


## Contact
For full version message me on: 
Telegram: devsharplabs or 
Discord: @devsharplabs or user id: (782226818441936906)
