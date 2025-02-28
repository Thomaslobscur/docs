Papers about algorithmic trading
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

An Investor’s Guide to Crypto
-----------------------------

We provide practical insights for investors seeking exposure to the growing cryptocurrency space. Today, crypto is much more than just bitcoin, which historically dominated the space but accounted for just a 21% share of total crypto trading volume in 2021. We discuss a wide variety of tokens, highlighting both their functionality and their investment properties. We critically compare popular valuation methods. We contrast buy-and-hold investing with more active styles. We only deem return data from 2017 representative, but the use of intraday data boosts statistical power. Underlying crypto performance has been notoriously volatile, but volatility-targeting methods are effective at controlling risk, and trend-following strategies have performed well. Crypto assets display a low correlation with traditional risky assets in normal times, but the correlation also rises in the left tail of these risky assets. Finally, we detail important custody and regulatory considerations for institutional investors.

`Read the paper <https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4124576>`__.

Low-volatility strategies for highly liquid cryptocurrencies
------------------------------------------------------------

Managing extreme price fluctuations in cryptocurrency markets are of central importance for investors in this market segment. Using a sample of highly liquid cryptocurrencies from January 2017 to June 2021, this paper proposes a dynamic investment strategy that selects cryptocurrencies based on their historical volatility and is complemented by a simple stop-loss rule. Our results reveal that investing in highly concentrated low volatility cryptocurrency portfolios with six to twelve months volatility look-back and holding period generate statistically significant excess returns. By including a simple stop-loss rule, the downside risk of cryptocurrency portfolios is reduced markedly, and the Sharpe ratios are improved significantly.

`Read the paper <https://www.sciencedirect.com/science/article/pii/S1544612321004116>`__.

How to avoid overfitting trading strategies
-------------------------------------------

Running a lossy trading strategy would be a very costly mistake, so we spend a lot of effort on assessing the expected performance of our strategies. This task gets harder when we have limited data for this evaluation or when we experiment with the strategy for a longer time and risk manually overfitting the strategy on the same out-of-sample data.

`Read the Quantlane blog post <https://quantlane.com/blog/avoid-overfitting-trading-strategies/>`__.

An Efficient Algorithm for Optimal Routing Through Constant Function Market Makers
----------------------------------------------------------------------------------

Constant function market makers (CFMMs) such as Uniswap have facilitated trillions of dollars of digital asset trades and have billions of dollars of liquidity. One
natural question is how to optimally route trades across a network of CFMMs in order
to ensure the largest possible utility (as specified by a user). We present an efficient algorithm, based on a decomposition method, to solve the problem of optimally executing
an order across a network of decentralized exchanges

`Read the paper <https://angeris.github.io/papers/routing-algorithm.pdf>`__.


Can machines learn finance?
---------------------------

Machine learning for asset management faces a unique set of challenges that differ markedly from other domains where machine learning has excelled. Understanding these differences is critical for developing impactful approaches and realistic expectations for machine learning in asset management. We discuss a variety of beneficial use cases and potential pitfalls, and emphasize the importance of economic theory and human expertise for achieving success through financial machine learning.

`Read the paper <https://joim.com/can-machines-learn-finance/>`__.


Automated Market Making and Arbitrage Profits in the Presence of Fees
---------------------------------------------------------------------

We consider the impact of trading fees on the profits of arbitrageurs trading against an
automated marker marker (AMM) or, equivalently, on the adverse selection incurred by liquidity
providers due to arbitrage. We extend the model of Milionis et al. [2022] for a general class
of two asset AMMs to both introduce fees and discrete Poisson block generation times. In our
setting, we are able to compute the expected instantaneous rate of arbitrage profit in closed
form. When the fees are low, in the fast block asymptotic regime, the impact of fees takes a
particularly simple form: fees simply scale down arbitrage profits by the fraction of time that
an arriving arbitrageur finds a profitable trade.

`Read the paper <https://moallemi.com/ciamac/papers/lvr-fee-model-2023.pdf>`__.


Momentum and trend following trading strategies for currencies and bitcoin
--------------------------------------------------------------------------

Momentum trading strategies are thoroughly described in the academic literature and used in many trading strategies by hedge funds, asset managers, and proprietary traders. Baz et al. (2015) describe a momentum strategy for different asset classes in great detail from a practitioner’s point of view. Using a geometric Brownian Motion for the dynamics of the returns of financial instruments, we extensively explain the motivation and background behind each step of a momentum trading strategy. Constants and parameters that are used for the practical implementation are derived in a theoretical setting and deviations from those used in Baz et al. (2015) are shown. The trading signal is computed as a mixture of exponential moving averages with different time horizons. We give a statistical justification for the optimal selection of time horizons. Furthermore, we test our approach on global currency markets, including G10 currencies, emerging market currencies, and cryptocurrencies. Both a time series portfolio and a cross-sectional portfolio are considered. We find that the strategy works best for traditional fiat currencies when considering a time series based momentum strategy. For cryptocurrencies, a cross-sectional approach is more suitable. The momentum strategy exhibits higher Sharpe ratios for more volatile currencies. Thus, emerging market currencies and cryptocurrencies have better performances than the G10 currencies. This is the first comprehensive study showing both the underlying statistical reasons of how such trading strategies are constructed in the industry as well as empirical results using a large universe of currencies, including cryptocurrencies.

`Read the paper <https://papers.ssrn.com/sol3/papers.cfm?abstract_id=2949379>`__.

Momentum trading in cryptocurrencies: short-term returns and diversification benefits
-------------------------------------------------------------------------------------

We test for the presence of momentum effects in cryptocurrency market and estimate dynamic conditional correlations (DCCs) of returns between momentum portfolios of cryptocurrencies and traditional assets. First, investment portfolios are constructed adherent to the classic J/K momentum strategy, using daily data from twelve cryptocurrencies for over a period of three years. We identify the existence of momentum effect, which is highly significant for short-term portfolios but disappears over the longer term. Second, we show that cross correlations of weekly returns between momentum portfolio of cryptocurrencies and traditional assets are unlike correlations of returns between traditional assets. Third, we find that momentum portfolios of cryptocurrencies not only offer diversification benefits but also can be a hedge and safe haven for traditional assets.


`Read the paper <https://sussex.figshare.com/articles/journal_contribution/Momentum_trading_in_cryptocurrencies_short-term_returns_and_diversification_benefits/23472263>`__.

On technical trading and social media indicators for cryptocurrency price classification through deep learning
--------------------------------------------------------------------------------------------------------------

Predicting the prices of cryptocurrencies is a notoriously challenging task due to high volatility and new mechanisms characterising the crypto markets. In this work, we focus on the two major cryptocurrencies for market capitalisation at the time of the study, Ethereum and Bitcoin, for the period 2017–2020. We present a comprehensive analysis of the predictability of price movements comparing four different deep learning algorithms (Multi Layers Perceptron (MLP), Convolutional Neural Network (CNN), Long Short Term Memory (LSTM) neural network and Attention Long Short Term Memory (ALSTM)). We use three classes of features, considering a combination of technical (e.g. opening and closing prices), trading (e.g. moving averages) and social (e.g. users’ sentiment) indicators as input to our classification algorithm. We compare a restricted model composed of technical indicators only, and an unrestricted model including technical, trading and social media indicators. We found an increase in accuracy for the daily classification task from a range of 51%–55% for the restricted model to 67%–84% for the unrestricted one. This study demonstrates that including both trading and social media indicators yields a significant improvement in the prediction and accuracy consistently across all algorithms.

`Read the paper <https://arxiv.org/pdf/2102.08189.pdf>`__.

Data Resampling for Cryptocurrency Investment with Ensemble of Machine Learning Algorithms
------------------------------------------------------------------------------------------

This work proposes a system based on machine learning aimed at creating an investment strategy capable of trading on the volatile cryptocurrency exchange markets with the highest returns and lowest risk. With the former goal in mind, several methods are employed for resampling the original financial data into a time series more prone of obtaining higher returns and the final results are compared to the obtained with commonly utilized time sampled series. These methods resample the original financial time series according to price action rather than a fixed time period. Simply put, the original samples are grouped as the closing value surpasses a threshold variation of quote currency. Three experimental thresholds were analysed: percentual value, fixed amount and fixed logarithmic amount.

`Read the paper <https://fenix.tecnico.ulisboa.pt/downloadFile/563345090417208/FinalThesis.pdf>`__.

Pure Momentum in Cryptocurrency Markets
---------------------------------------

Momentum is one of the most widespread, persistent, and puz- zling phenomenon in asset pricing. The prevailing explanation for momentum is that investors under-react to new information, and thus asset prices tend to drift over time. We use a unique fea- ture of cryptocurrency markets: the fact that they are open 24/7, and report returns over the last 24 hours. Thus, the one-day re- turn is subject to predictable fluctuations based on the removal of lagged information. We show that investors respond positively to changes in reported returns that are unrelated to any new release of information, or change in the asset fundamentals. We call this behavioral anomaly “Pure Momentum”.

`Read the paper <https://assets.ctfassets.net/c5bd0wqjc7v0/4RzmvaUG64ixNPXWuZGXbo/7115cc7bef963d2ff5abbacf879f5b1e/SSRN-id4138685.pdf>`__.

Dissecting Investment Strategies in the Cross Section and Time Series
---------------------------------------------------------------------

We contrast the time-series and cross-sectional performance of three popular investment
strategies: carry, momentum and value. While considerable research has examined the perfor-
mance of these strategies in either a directional or cross-asset settings, we offer some insights
on the market conditions that favor the application of a particular setting.

`Read the paper <https://assets.ctfassets.net/c5bd0wqjc7v0/4RzmvaUG64ixNPXWuZGXbo/7115cc7bef963d2ff5abbacf879f5b1e/SSRN-id4138685.pdf>`__.

Can Day Trading Really Be Profitable?
-------------------------------------

The validity of day trading as a long-term consistent and uncorrelated source of income for traders and investors is a matter of debate. In this paper, we investigate the profitability of the well-known Opening Range Breakout (ORB) strategy during the period of 2016 to 2023. This period encompasses two bear markets and a few events with abnormal volatility. Our results suggest that with the proper use of leverage or leveraged products (such as 3x leveraged ETFs), day trading can empirically produce significant returns when compared to a standard buy and hold strategy on benchmark indexes in the US public equity markets (Nasdaq or NYSE). Without any loss of generality, we studied the results of an ORB strategy implemented in QQQ. By comparing the results of the active day trading approach with a passive exposure in QQQ, we prove that it is possible for the ORB portfolio to significantly outperform the passive investment. In fact, the day trading portfolio produced an annualized alpha of 33% (net of commissions). Nevertheless, due to leverage constraints enforced by brokers, an active trader would have capped the full upside potential given by the ORB strategy. To overcome this issue, we introduced the use of TQQQ, a leveraged ETF of QQQ, which allows day traders to fully exploit the benefit of the active strategy while adhering to leverage constraints. The resulting portfolio would have earned an outstanding return of 1,484% during the same period of 2016 to 2023, while an investment in the QQQ ETF would have earned only 169%.

`Read the paper <https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4416622>`__.


Multi-source aggregated classification for stock price movement prediction
--------------------------------------------------------------------------

Predicting stock price movements is a challenging task. Previous studies mostly used numerical features and
news sentiments of target stocks to predict stock price movements. However, their semantics-based sentiment
analysis is sub-optimal to represent real market sentiments. Moreover, only considering the information of
target companies is insufficient because the stock prices of target companies can be affected by their related
companies. Thus, we propose a novel Multi-source Aggregated Classification (MAC) method for stock price
movement prediction. MAC incorporates the numerical features and market-driven news sentiments of target
stocks, as well as the news sentiments of their related stocks. To better represent real market sentiments from
the news, we pre-train an embedding feature generator by fitting the news to real stock price movements.
Embeddings given by the pre-trained sentiment classifier can represent the sentiment information in vector
space. Moreover, MAC introduces a graph convolutional network to capture the news effects of related
companies on the target stock. Finally, MAC can predict stock price movements for the next trading day based
on the aforementioned features. Extensive experiments prove that MAC outperforms state-of-the-art baselines
in stock price movement prediction, Sharpe Ratio, and backtesting trading incomes

`Read the paper <https://www.sciencedirect.com/science/article/abs/pii/S1566253522002019>`__.

From Man vs. Machine to Man Machine: The Art and AI of Stock Analyses
----------------------------------------------------------------------

We train an AI analyst that digests corporate disclosures, industry trends, and macroeconomic
indicators to the extent it beats most analysts. Human wins the “Man vs. Machine”
contest when a firm is complex with intangible assets, and AI wins when information is
transparent but voluminous. Analysts catch up with machines over time, especially after
firms are covered by alternative data and their institutions build AI capabilities. AI power
and human wisdom are complementary in generating accurate forecasts and mitigating extreme
errors, portraying a future of “Man + Machine” (instead of human displacement) in
financial analyses, and likely other high-skill professions.

`Read the paper <https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3840538>`__.