# Sneakerpunk NFT store
## DEMO VIDEO

https://user-images.githubusercontent.com/81568615/176022936-90c189a5-1750-447a-89e2-ab5136496acd.mp4

##  Metamask Wallet

https://user-images.githubusercontent.com/81568615/176025390-e2a59d71-8772-4b14-8f73-e74e56071352.mp4





## PREVIEW
![Screenshot from 2022-06-23 15-36-20](https://user-images.githubusercontent.com/81568615/175301654-712d098e-c277-4732-a8c5-93d989324816.png)



### Marketplace features :bulb:

- [x] Mint & List Nft.
- [x] Buy NFT.
- [x] Sell NFT.
- [x] Connect with wallet.


### Tech stack & packages used 📦

| package                                                             | explain                                                               |
| ------------------------------------------------------------------- | --------------------------------------------------------------------- |
| [Next.js](https://nextjs.org/docs/getting-started)                  | framework                                                             |
| [ipfs-http-client ](https://www.npmjs.com/package/ipfs-http-client) | Http Client to Connect Application with IPFS                          |       
| [openzeppelin](https://www.npmjs.com/package/@openzeppelin/contracts) | For creating ERC-721 token.                                         |
| [ether.js](https://docs.ethers.io/v5/)                              | Web3 client.                                                          |
| [Chai](https://www.npmjs.com/package/chai)                          | javascript testing framework.                                         |
| [react-toastify](https://www.npmjs.com/package/react-toastify)      | For Notification.                                                     |   
| [hardhat](https://www.npmjs.com/package/hardhat)                    | Ethereum development environment.                                     | 
| [Redux](https://www.npmjs.com/package/hardhat)                      | For managing and centralizing application state.                      |   


---

- Run hardhat node
  ```
  npx hardhat node
  ```
- Run test cases
  ```
  npx hardhat test
  ```
- Deploy contract in local hardhat node
  ```
  npx hardhat run scripts/deploy.js --network localhost
  ```
- Connect hardhat with metamask
- Run react frontend
  ```
  cd client
  npm start
  ```

[ERC-721 token details](https://github.com/OpenZeppelin/openzeppelin-contracts/tree/master/contracts/token/ERC721)

[Ethers.js documentation](https://docs.ethers.io/v5/getting-started/)

```shell
npx hardhat accounts
npx hardhat compile
npx hardhat clean
npx hardhat test
npx hardhat node
npx hardhat help
npx hardhat run scripts/deploy.js --network localhost

connect your wallet in the .env file
```
To deploy on vercel check out this link
https://vercel.com/docs/concepts/deployments/overview