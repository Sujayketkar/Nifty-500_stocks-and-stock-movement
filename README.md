# Nifty-500_stocks-and-stock-movement
Project Overview:

I chose to conduct an exploratory analysis on Nifty-500. With Pandas, examining price and volume trends over a specific timeframe and computing rolling averages becomes a straightforward task. Recently, I utilized Yahoo Finance as a reliable data source to delve into various NSE stock scripts.

Key Highlights:

Yahoo Finance proves to be an excellent tool for downloading script values directly into a Jupyter notebook.
The market capitalization (Mcap) data, retrieved as of March 23, was downloaded from the Nifty website.
Data for Nifty 500 and all listed stocks were also obtained from the Nifty website.
Utilizing the merge feature, we combined both datasets, addressing the absence of Mcap data in the Nifty-500 dataset by merging it with Mcap data from Nifty-all listed CSV.
Employing the groupby function allows us to identify sectors with the highest influence on the Nifty-500 Index, which are financial services, capital goods, and healthcare.
Comparative analysis of stock movement and volume trends provides insights into stock volatility.
Examining the Jupyter notebook data for Coal India and LT reveals distinctive patterns—Coal India exhibits slow movement with low volume trades, while LT demonstrates significant upward movement with substantial volume changes.
The 30-day rolling average proves valuable in summarizing how a stock evolves over time.

