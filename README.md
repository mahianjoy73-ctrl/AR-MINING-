# AR MINING — Crypto-only Mini App prototype

English UI. This starter switches the payment concept to crypto-only (USDT network selector for TRC20 and BEP20). It has no bKash or Nagad options.

## Current status
- Frontend prototype only.
- Mining balance and task rewards are demo points stored locally in the browser.
- No wallet address is generated and no real deposits, withdrawals, blockchain checks, or crypto transfers are enabled.
- Never send crypto to a demo app or placeholder address.

## Publish as a Telegram Mini App
1. Upload `index.html`, `style.css`, and `app.js` to an HTTPS static host.
2. Create a Telegram bot with the official BotFather.
3. Configure the bot's Mini App URL to the HTTPS URL.
4. For production, build a backend and database; validate Telegram `initData` on the server.
5. Use a legitimate wallet/custody provider or secure server-side wallet infrastructure; verify incoming deposits on-chain, and use withdrawal limits, manual review, audit logs, and anti-abuse controls.
6. Only offer redeemable rewards if there is a real funding source and the activity complies with applicable laws and platform/payment-provider rules.

## Security
Never place a private key, seed phrase, or withdrawal-signing secret in frontend JavaScript or a public repository. Use testnet first. Check the selected chain carefully: USDT on TRC20 and BEP20 are different networks.
