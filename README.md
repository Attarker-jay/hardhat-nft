We will be developing 3 contracts

1. Basic NFT
2. Random IPFS NFT
   pros: cheap
   cons: someone needs to pin our data

3. Dynamic SVG NFT
   pros: the data is on chain!
   cons: much more expensive!

If the price of ETH is above X -> Happy face
else it's below -> Frowny face

essentials
............
yarn add --dev @nomiclabs/hardhat-ethers@npm:hardhat-deploy-ethers ethers @nomiclabs/hardhat-etherscan @nomiclabs/hardhat-waffle chai ethereum-waffle hardhat hardhat-contract-sizer hardhat-deploy hardhat-gas-reporter prettier prettier-plugin-solidity solhint solidity-coverage dotenv
