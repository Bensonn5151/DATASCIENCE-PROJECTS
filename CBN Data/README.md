This project focuses on analyzing exchange rate data obtained from the Central Bank of Nigeria (CBN). The analysis aims to uncover trends, patterns, and relative strengths of different currencies against the Nigerian Naira.

Technologies Used

Python
Pandas
Matplotlib
Seaborn
Plotly

Analysis Overview

Data Loading and Preprocessing: The project begins with loading the exchange rate data from a CSV file. The index is reset to handle mismatches, and the columns are rearranged for consistency. The rate date is converted to datetime format, and the months are mapped from strings to numerical values.
Visualization: Several visualizations are created to explore the data, including line plots of rate date vs. buying rate, bar plots of rate year vs. selling rate, and bar plots of rate year vs. mean buying rate.
Currency Strength Analysis: Normalized rates and relative currency strengths are calculated to compare different currencies against a reference currency (e.g., US Dollar). Currency strength over time is visualized using line plots.
Results

The analysis reveals interesting insights into the exchange rate trends, volatility, and relative strengths of different currencies against the Nigerian Naira. Key findings are presented along with visualizations to support the results.

Future Work

Explore additional statistical analyses and machine learning models to predict exchange rate movements.
