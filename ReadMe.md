# Buidler DAO Course Series: Flash Loan Fundamentals
- Speaker: Wiger https://twitter.com/JizhouW
- Code writing: Soth https://twitter.com/Soth76267980
- Teaching and Research Assistant: Spinach Spinach!
- Teaching Assistant: Niel

## Kovan Faucets
- Kovan Link: https://faucets.chain.link/
- Kovan: https://gitter.im/kovan-testnet/faucet

## Learning materials
1. Flash loan source code: https://github.com/Wiger123/BuidlerDao-FlashLoan
2. Classic attack recurrence: https://github.com/Rivaill/CryptoVulhub
3. Lightning Arbitrage: https://github.com/paco0x/amm-arbitrageur
4. Uniswap Flash Loan: https://medium.com/uv-labs/flash-swap-5bcdbd9aaa14

## Basic Demo
1. PPT explanation
2. Basic Demo: write => compile => input constructor 0x506B0B2CF20FAA8f38a4E2B524EE43e1f4458Cc5 deploy => verify contract 000000000000000000000000506b0b2cf20faa8f38a4e2bcc524ee43e1f4458
3. Kovan Etherscan call: https://kovan.etherscan.io/address/0xbAECCE8aC87fd22e93f682565B392B029071bd61
4. Pass in DAI / AAVE / ... in advance as a handling fee
5. Input parameter: 0xFf795577d9AC8bD7D90Ee22b6C1703490b6512FD 1000000000000000000000
6. Complete the Flash Loan Basic Demo

## Pro Demo
1. TokenA: 0xdcD910430D64E00207D7B6aC0f3F7458F7464581; TokenB: 0x6DC4FD9335eF0F5fe10Db08D0dea8426808B087F
2. Create 3 pools: DAI - Token1, Token1 - Token2, Token2 - DAI
3. DAI => TokenA => TokenB
4. Authorization => Transaction
5. Pay back => transfer profit
6. Kovan Etherscan call: https://kovan.etherscan.io/address/0x87288733ef6f556d22221ee05734e454daac38e4
5. Input parameter: 0xFf795577d9AC8bD7D90Ee22b6C1703490b6512FD 1000000000000000000000
6. Complete the Flash Loan Pro Demo

## address
1. DAI contract address
address public dai = 0xFf795577d9AC8bD7D90Ee22b6C1703490b6512FD;
2. TokenA contract address
address public tokenA = 0xdcD910430D64E00207D7B6aC0f3F7458F7464581;
3. TokenB contract address
address public tokenB = 0x6DC4FD9335eF0F5fe10Db08D0dea8426808B087F;
4. Uniswap V2 routing address
address public router = 0x7a250d5630B4cF539739dF2C5dAcb4c659F2488D;