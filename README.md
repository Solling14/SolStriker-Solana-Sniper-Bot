# SolStriker Sniper Bot

**SolStriker Token Sniper Bot** that listens to new SolStriker pools and buys tokens for a fixed amount in SOL.
Depending on the speed of the RPC node, the purchase usually happens before the token is available on SolStriker UI for swapping.


Website: `https://solstriker.com/`

Free trial: `https://solstriker.com/`

Telegram: `https://t.me/solstrikerdev`


![Solstriker Logo](https://i.imgur.com/ifEHpgx.png)

- `SOL Snipe`
- `Auto-Sell`
- `TP/SL`
- `Telegram Check`
- `Website Check`
- `Twitter Check`
- `Fast Buy`

> [!NOTE]
> This is provided as is, for learning purposes.

[![TypeScript](https://badgen.net/badge/icon/python)](https://python.org)
![UPTime](https://camo.githubusercontent.com/4a67ad96d71cca235a4393b2f3b79aabb0a3d42d555030632f1110e9eedde567/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f757074696d652d3130302532352d627269676874677265656e)


## 🚀 CONFIG
Configure the script by updating `config.py` file.
1. `PUB_KEY` (your wallet private key)
2. `PRIV_KEY` (your wallet private key)
3. `RPC` (https RPC endpoint)
4. `CHECK_TWITTER` (check if new pools have twitter)
5. `CHECK_WEBSITE` (check if new pools have website)
6. `CHECK_TELEGRAM` (check if new pools have telegram)
7. `BUY_AMOUNT` (set the default buy amount)
  
## 🚀 COMMON ISSUES

> [!IMPORTANT]
> If you have an error which is not listed here, please create a new issue in this repository.
> 
> ### EMPTY TRANSACTION
> If you see empty transactions on SolScan most likely fix is to change commitment level to `finalized`.
> 
> ### UNSOPPORTED RPC NODE
> If you see following error in your log file:  
> `Error: 410 Gone:  {"jsonrpc":"2.0","error":{"code": 410, "message":"The RPC call or parameters have been disabled."}, "id": "986f3599-b2b7-47c4-b951-074c19842bad" }`  
> It means your RPC node doesn't support methods needed to execute script.
> FIX: Change your RPC node. You can use Shyft, Helius or Quicknode.

## 🛸 CONTACT
Telegram: `@SolStrikerDev`

Website: `https://solstriker.com/`

Free trial: `https://solstriker.com/`

Telegram: `https://t.me/solstrikerdev`

## 🛰 Disclaimer
Use this script at your own risk. 
