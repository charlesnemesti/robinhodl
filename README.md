# RobinHodl ($HODL)

Single-page Web3 landing for **RobinHodl** — a cypherpunk meme token on **Robinhood Chain**, launched via [NOXA Fun](https://fun.noxa.fi/robinhood).

> We take from the jeets and give to the HODLers.

## Stack

- HTML5 + Tailwind CSS (CDN)
- Vanilla JavaScript
- Live stats from NOXA Fun API

## Local dev

```bash
npx serve .
```

Open `http://localhost:3000`.

## Configure contract

After launching on NOXA Fun, set your token address in `script.js`:

```js
tokenAddress: '0xYOUR_CONTRACT_ADDRESS',
```

## Deploy

Connected to GitHub + Vercel. Push to `main` to trigger redeploys when Git integration is enabled.
