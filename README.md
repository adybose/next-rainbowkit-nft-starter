# next-rainbowkit-nft-starter

A Next.js boilerplate dapp to mint NFTs bootstrapped with Rainbowkit, Wagmi, and ethers.js.

## Smart Contract
The smart contract is deployed on the Goerli Ethereum Testnet at address [0x2c5d31E87bb77eafcb573DaAD98FF742Fbe0a2b0](https://goerli.etherscan.io/address/0x2c5d31e87bb77eafcb573daad98ff742fbe0a2b0).

Make sure you have a wallet like Metamask to connect and sign transactions from your Ethereum account on the Goerli Test Network.

## Getting Started

- First, create a new app on Alchemy, and add the API key to a `.env` file in the project root like:
```
ALCHEMY_ID=<YOUR_ALCHEMY_APP_API_KEY>
```
- Install the dependencies:
```bash
npm install
# or
yarn install
```

- Finally, run the development server:
```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.js`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
