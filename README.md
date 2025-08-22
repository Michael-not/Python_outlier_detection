Stock Candlestick Simulator
This project is a simple Python simulator for intraday stock price movements with a candlestick chart visualization.
It allows you to generate realistic stock price data, detect or remove outliers, and plot them in either hourly or minute intervals.
Features:
Generate intraday stock data: Simulates a single trading day (9:30 AM – 4:00 PM) with small price fluctuations and optional outliers.
Candlestick charts: Visualize stock movements as candlesticks using matplotlib.
Flexible timeframe: Choose between "hour" or "minute" candlestick intervals.

Outlier handling:
"detect" → marks outliers on the chart.
<img width="854" height="672" alt="image" src="https://github.com/user-attachments/assets/46b3d786-86f3-4e87-a888-1dd35fca82de" />

"remove" → removes outliers before plotting.
the same image but with removed outliers ->
<img width="851" height="677" alt="image" src="https://github.com/user-attachments/assets/23574a0f-2b91-4bea-bce9-e61f0821684e" />

