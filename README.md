# Lumite
In-browser wallet for [Stellar](https://stellar.org/) blockchain. Supports receiving and sending XLM with custom fee limit and transaction memos. Progressive web app using [Next.js](https://nextjs.org/), fully client-side, communicates directly with [Horizon API](https://developers.stellar.org/api) servers.

Demo available [here](https://ebra.dev/lumite/)! You need an existing Stellar account/keypair to use lumite.

## Screenshots
<img src="https://raw.githubusercontent.com/beans42/lumite/master/demo1.png" alt="mobile screenshot" height="300px"> <img src="https://raw.githubusercontent.com/beans42/lumite/master/demo2.png" alt="desktop screenshot" height="300px">

## Usage

```bash
npm i
npm run build:ssg
```

Then, use any web server to host the `docs` directory.
```bash
http-server -p 80 docs
```
