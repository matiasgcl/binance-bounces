# binance-bounces

This script will quantify and summarize several

Why this would matter?

> Relative strength (time elapsed for a bounce and amplitude of the bounce).

Just fill the information required (follow the given examples, I never handle exceptions on my own code! sorry :-))
1. How many coins you want to see (at the beginning it will tell you how many are possible, your size will tell you how many you need to see).
2. Timeframe for computations (i.e. TF for the retrieved Klines).
3. Initial date-time for computations.
4. Final date-time for computations.
5. Wait for the output.
6. Open the spreadsheet on your favorite program!

Some definitions for what you will see:
1. Time Low (Open): Date-time when the candle where the bottom is captured OPENS.
2. Time High (Close): Date-time when the candle where the peak is captured CLOSES. By definition this time is ALWAYS after the low (algorithmically, we catch the low and eliminate all the candles before, so in this way we actually capture the bounce FROM the bottom).
3. T low - T high: The difference (measured in hours:minutes:seconds) between Time Low (Open) and Time High (Close) (>=0 by definition), the smaller the timeframe, the more precise this quantity is with respect to the exact time elapsed from bottom to peak.

Example:

![Example](Example.png)
