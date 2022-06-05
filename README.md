# Full Bitcoin Price History

*Keywords*

Bitcoin, price data, price history, complete price history,
complete price history, candles, full history

## Description ##

This repository contains the full Bitcoin price history up to June 4th, 2022.

The data comes from the
[cryptowat.ch API for OHLC candlesticks](https://docs.cryptowat.ch/rest-api/markets/ohlc).

Data from this API is not aggregate; candlestick data is specific to
exchanges. The aggregate data in `aggregate-data.json` is pieced together from
candlestick data from three exchanges:


| Exchange | Starting          | Ending            | Starting Timestamp | Ending Timestamp |
|----------|-------------------|-------------------|--------------------|------------------|
| MtGox    | July 18th 2010    | April 22nd 2013   | 1279497600         | 1366675200       |
| Bitstamp | April 23rd 2013   | January 25th 2015 | 1366761600         | 1422230400       |
| Coinbase | January 26th 2015 | June 4th 2022     | 1422316800         | 1654387200       |

The individual price data files per exchange are not clipped and contain their
full histories, which are overlapping.
