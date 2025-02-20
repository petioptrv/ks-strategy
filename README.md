# ks-strategy

## Initial Requirements

[Link](https://discord.com/channels/@me/1341774390768963685/13417824269757317130) to message.

For logic and main parameters, I believe the below are main params we are looking for:
1) USDT amount - trade amount in USDT for each trade
2) Trade Frequency - in seconds, how frequent the trades are placed. For example 1 sec = each second a buy order is placed, next second sell order is places, next second buy order etc.
3) Max Buy and Min Sell prices in usdt - this is for risk managment purposes. For example if Max Buy price is 1 - if the price of token goes to 1.1 bot stops buying and only does sells.
   Alternatively, if Min sell = 0.5 and price goes below this price - bot stops selling and only using buys.
   Inside the interval it buys and sells
4) Would be good to have a feature like Auto Mode and Manual Mode - for example in Auto Mode it starts working as desribed above placing orders. In Manual mode it place one order and stops. Auto Mode is now priority for our purposes
