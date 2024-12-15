This repository contains a re-upload of the [Bitcoin +233 Crypto Coins Prices](https://www.kaggle.com/datasets/olegshpagin/crypto-coins-prices-ohlcv) dataset created by [Oleg Shpagin](https://www.kaggle.com/olegshpagin).

## About the Dataset

The dataset provides price and OHLCV (Open, High, Low, Close, Volume) data for Bitcoin and 233 other cryptocurrencies. It is a valuable resource for crypto market analysis, algorithmic trading, and data visualization projects.

## Usage

Feel free to use this dataset in your research or projects. Be sure to credit the original creator, [Oleg Shpagin](https://www.kaggle.com/olegshpagin), when utilizing this data.

## Credits

- Original dataset by [Oleg Shpagin](https://www.kaggle.com/olegshpagin)
- Kaggle dataset link: [Bitcoin +233 Crypto Coins Prices](https://www.kaggle.com/datasets/olegshpagin/crypto-coins-prices-ohlcv)

---

# Cryptocurrency 234 Coins Altcoins Prices
Bitcoin, Ethereum, Tether, Binance Coin, XRP, Cradano, Ripple, Dogecoin and more... 

This Dataset contains 234 Crypto Coins/Altcoins with historical Open, High, Low, Close, and Volume (OHLCV) prices traded in the Binance Exchange. You can use price movements and trading volumes for coins price predictions.

### ~7 Gb of market data for you and your analysis with NN or other methods 

Here is the link to kaggle dataset [Bitcoin +233 Crypto Coins Prices](https://www.kaggle.com/datasets/olegshpagin/crypto-coins-prices-ohlcv) (weekly updates)

#### 1638 CSV files for W1, D1, H4, H1, M30, M15 and M5 timeframes

```

Bitcoin D1 Daily timeframe
     datetime     open     high      low    close       volume
0  2017-08-17  4261.48  4485.39  4200.74  4285.08   795.150377
1  2017-08-18  4285.08  4371.52  3938.77  4108.37  1199.888264
2  2017-08-19  4108.37  4184.69  3850.00  4139.98   381.309763
3  2017-08-20  4120.98  4211.08  4032.62  4086.29   467.083022
4  2017-08-21  4069.13  4119.62  3911.79  4016.00   691.743060

... ... ... ... ... ... ... ...

        datetime      open      high       low     close        volume
2396  2024-03-09  68124.20  68541.10  67861.10  68313.27  19872.897430
2397  2024-03-10  68313.28  69887.61  68094.75  68955.88  38404.668350
2398  2024-03-11  68955.88  72800.00  67024.96  72078.10  75292.825726
2399  2024-03-12  72078.10  73000.00  68620.82  71452.01  68783.546691
2400  2024-03-13  71452.00  73650.25  71333.31  73072.41  52659.711647



Bitcoin H1 Hourly timeframe
              datetime     open     high      low    close     volume
0  2017-08-17 04:00:00  4261.48  4313.62  4261.32  4308.83  47.181009
1  2017-08-17 05:00:00  4308.83  4328.69  4291.37  4315.32  23.234916
2  2017-08-17 06:00:00  4330.29  4345.45  4309.37  4324.35   7.229691
3  2017-08-17 07:00:00  4316.62  4349.99  4287.41  4349.99   4.443249
4  2017-08-17 08:00:00  4333.32  4377.85  4333.32  4360.69   0.972807

... ... ... ... ... ... ... ...

                  datetime      open      high       low     close      volume
57506  2024-03-14 14:00:00  71884.82  72536.03  71215.00  71690.00  4628.07838
57507  2024-03-14 15:00:00  71689.99  72068.96  70543.64  70844.01  5356.46500
57508  2024-03-14 16:00:00  70844.00  71445.00  69880.00  71337.63  6369.77109
57509  2024-03-14 17:00:00  71337.64  71458.00  70700.00  71036.01  2805.73236
57510  2024-03-14 18:00:00  71036.00  71036.01  69309.38  70098.50  4914.97579

```

If you want to download actual data - on today for example, then you can use python code from my github.

**Feel free to write in comments which coins/altcoins prices you are interested most, may be it is possible to download their prices too.** 

top_coins = ['BTCUSDT', 'ETHUSDT', 'BCHUSDT', 'XRPUSDT', 'EOSUSDT', 'LTCUSDT', 'TRXUSDT', 'ETCUSDT', 'LINKUSDT', 'XLMUSDT', 'ADAUSDT', 'XMRUSDT', 'DASHUSDT', 'ZECUSDT', 'XTZUSDT', 'BNBUSDT', 'ATOMUSDT', 'ONTUSDT', 'IOTAUSDT', 'BATUSDT', 'VETUSDT', 'NEOUSDT', 'QTUMUSDT', 'IOSTUSDT', 'THETAUSDT', 'ALGOUSDT', 'ZILUSDT', 'KNCUSDT', 'ZRXUSDT', 'COMPUSDT', 'OMGUSDT', 'DOGEUSDT', 'SXPUSDT', 'KAVAUSDT', 'BANDUSDT', 'RLCUSDT', 'WAVESUSDT', 'MKRUSDT', 'SNXUSDT', 'DOTUSDT', 'DEFIUSDT', 'YFIUSDT', 'BALUSDT', 'CRVUSDT', 'TRBUSDT', 'RUNEUSDT', 'SUSHIUSDT', 'SRMUSDT', 'EGLDUSDT', 'SOLUSDT', 'ICXUSDT', 'STORJUSDT', 'BLZUSDT', 'UNIUSDT', 'AVAXUSDT', 'FTMUSDT', 'HNTUSDT', 'ENJUSDT', 'FLMUSDT', 'TOMOUSDT', 'RENUSDT', 'KSMUSDT', 'NEARUSDT', 'AAVEUSDT', 'FILUSDT', 'RSRUSDT', 'LRCUSDT', 'MATICUSDT', 'OCEANUSDT', 'CVCUSDT', 'BELUSDT', 'CTKUSDT', 'AXSUSDT', 'ALPHAUSDT', 'ZENUSDT', 'SKLUSDT', 'GRTUSDT', '1INCHUSDT', 'CHZUSDT', 'SANDUSDT', 'ANKRUSDT', 'BTSUSDT', 'LITUSDT', 'UNFIUSDT', 'REEFUSDT', 'RVNUSDT', 'SFPUSDT', 'XEMUSDT', 'BTCSTUSDT', 'COTIUSDT', 'CHRUSDT', 'MANAUSDT', 'ALICEUSDT', 'HBARUSDT', 'ONEUSDT', 'LINAUSDT', 'STMXUSDT', 'DENTUSDT', 'CELRUSDT', 'HOTUSDT', 'MTLUSDT', 'OGNUSDT', 'NKNUSDT', 'SCUSDT', 'DGBUSDT', '1000SHIBUSDT', 'BAKEUSDT', 'GTCUSDT', 'BTCDOMUSDT', 'IOTXUSDT', 'AUDIOUSDT', 'RAYUSDT', 'C98USDT', 'MASKUSDT', 'ATAUSDT', 'DYDXUSDT', '1000XECUSDT', 'GALAUSDT', 'CELOUSDT', 'ARUSDT', 'KLAYUSDT', 'ARPAUSDT', 'CTSIUSDT', 'LPTUSDT', 'ENSUSDT', 'PEOPLEUSDT', 'ANTUSDT', 'ROSEUSDT', 'DUSKUSDT', 'FLOWUSDT', 'IMXUSDT', 'API3USDT', 'GMTUSDT', 'APEUSDT', 'WOOUSDT', 'FTTUSDT', 'JASMYUSDT', 'DARUSDT', 'GALUSDT', 'OPUSDT', 'INJUSDT', 'STGUSDT', 'FOOTBALLUSDT', 'SPELLUSDT', '1000LUNCUSDT', 'LUNA2USDT', 'LDOUSDT', 'CVXUSDT', 'ICPUSDT', 'APTUSDT', 'QNTUSDT', 'BLUEBIRDUSDT', 'FETUSDT', 'FXSUSDT', 'HOOKUSDT', 'MAGICUSDT', 'TUSDT', 'RNDRUSDT', 'HIGHUSDT', 'MINAUSDT', 'ASTRUSDT', 'AGIXUSDT', 'PHBUSDT', 'GMXUSDT', 'CFXUSDT', 'STXUSDT', 'COCOSUSDT', 'BNXUSDT', 'ACHUSDT', 'SSVUSDT', 'CKBUSDT', 'PERPUSDT', 'TRUUSDT', 'LQTYUSDT', 'USDCUSDT', 'IDUSDT', 'ARBUSDT', 'JOEUSDT', 'TLMUSDT', 'AMBUSDT', 'LEVERUSDT', 'RDNTUSDT', 'HFTUSDT', 'XVSUSDT', 'ETHBTC', 'BLURUSDT', 'EDUUSDT', 'IDEXUSDT', 'SUIUSDT', '1000PEPEUSDT', '1000FLOKIUSDT', 'UMAUSDT', 'RADUSDT', 'KEYUSDT', 'COMBOUSDT', 'NMRUSDT', 'MAVUSDT', 'MDTUSDT', 'XVGUSDT', 'WLDUSDT', 'PENDLEUSDT', 'ARKMUSDT', 'AGLDUSDT', 'YGGUSDT', 'DODOXUSDT', 'BNTUSDT', 'OXTUSDT', 'SEIUSDT', 'BTCUSDT_231229', 'ETHUSDT_231229', 'CYBERUSDT', 'HIFIUSDT', 'ARKUSDT', 'FRONTUSDT', 'GLMRUSDT', 'BICOUSDT', 'BTCUSDT_240329', 'ETHUSDT_240329', 'STRAXUSDT', 'LOOMUSDT', 'BIGTIMEUSDT', 'BONDUSDT', 'ORBSUSDT', 'STPTUSDT', 'WAXPUSDT', 'BSVUSDT', 'RIFUSDT', 'POLYXUSDT', 'GASUSDT', 'POWRUSDT', 'SLPUSDT', 'TIAUSDT', 'SNTUSDT', 'CAKEUSDT', 'MEMEUSDT', 'TWTUSDT', 'TOKENUSDT', 'ORDIUSDT', 'STEEMUSDT', 'BADGERUSDT', 'ILVUSDT', 'NTRNUSDT', 'MBLUSDT', 'KASUSDT', 'BEAMXUSDT', '1000BONKUSDT', 'PYTHUSDT', 'SUPERUSDT', 'USTCUSDT', 'ONGUSDT', 'ETHWUSDT', 'JTOUSDT', '1000SATSUSDT', 'AUCTIONUSDT', '1000RATSUSDT', 'ACEUSDT', 'MOVRUSDT', 'NFPUSDT', 'BTCUSDT_240628', 'ETHUSDT_240628']
