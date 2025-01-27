This is an automatic news trading bot.

The logic is:
1. Continuously monitor BWE News for any new posts.
2. Use ChatGPT to identify any specific coins mentioned in the post (e.g. Solana, ETH, Doge), as well as the positivity of this message.
3. Put buy/sell order on Binance (or solana rpc) once ChatGPT has done processing the raw message. Stop loss at 0.5%.
4. Clear position after 3 minutes into trade, if stop loss is still not triggered yet.

The user can monitor account balance history, current position, and trade manually via telegram.
