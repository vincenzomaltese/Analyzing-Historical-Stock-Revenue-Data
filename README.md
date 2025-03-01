# Analyzing Historical Stock and Revenue Data

![Financial data analysis dashboard](https://github.com/vincenzomaltese/Analyzing-Historical-Stock-Revenue-Data-and-Building-a-Dashboard/blob/main/images/1r.jpg?raw=true)

## Overview
This project explores the relationship between stock prices and revenue for Tesla and GameStop, visualizing trends and drawing insights into their financial performance and market behavior.

## Dataset
Historical stock prices and revenue figures were obtained from Yahoo Finance using web scraping techniques.

## Technologies Used
- BeautifulSoup
- Pandas
- Matplotlib
- Plotly

## Analysis & Findings
### Tesla
- Tesla's revenue grew exponentially from 2010 to 2021.
- The stock price followed a similar upward trend, suggesting a strong correlation between revenue growth and stock valuation.
- While revenue is not the sole factor affecting stock prices, Tesla’s price movement aligns logically with its financial performance.

### GameStop
- GameStop’s revenue peaked in 2011, followed by a steady decline and a sharp drop in 2020.
- Despite this decline, GameStop's stock price experienced extreme volatility in 2021, skyrocketing due to speculative trading.
- This suggests that the stock price became disconnected from the company's actual financial health, highlighting the speculative nature of the asset.

## Visualizations
### Tesla
![Tesla Stock and Revenue](https://github.com/vincenzomaltese/Analyzing-Historical-Stock-Revenue-Data/blob/main/images/Tesla_graph.png)

### GameStop
![GameStop Stock and Revenue](https://github.com/vincenzomaltese/Analyzing-Historical-Stock-Revenue-Data/blob/main/images/GameStop_graph.png)

## Conclusion
This analysis demonstrates how stock prices can be influenced by company fundamentals as well as external market dynamics. Tesla’s stock movement aligns with its revenue growth, while GameStop’s surge reflects market speculation rather than financial performance.

## How to Run the Notebook
1. Clone this repository.
2. Install required dependencies using `pip install -r requirements.txt` (if applicable).
3. Open `Final Assignment-v2.ipynb` in Jupyter Notebook.
4. Run the notebook to generate visualizations and insights.

## License
This project is open-source and available under the MIT License.


## Installation

To run this project locally, you will need to have Python installed along with the following libraries:

```bash
pip install pandas beautifulsoup4 yfinance plotly
