Project description:

The Ethereum is the second most popular cryptocurreny after the Bitcoin. It has gain a lot of attention last year. But while some see it as another potential investment, others predict it to be a more sophisticated version of its predecessor. The reason why leads in the general use of this technolgoies: Bitcoin is used a currency and Ethereum as "a ledger technology that companies are using to build new programs" (source: https://hackernoon.com/the-primary-difference-between-ethereum-and-bitcoin-a-beginners-guide-8a892afb7a4). In addition of feeding the aspirations of a large crowd, Ethereum drew the attention of a group called 'The Enterprise Ethereum Alliance', which is super-group of "Fortune 500 companies that have all agreed to work together to learn and build upon Ethereum’s blockchain technology — otherwise referred to as “smart contract” technology".

This time, we will solely look at Ethereum as a cryptocurrency and its market value.

Our main assumption is: The Ethereum value can be predicted with historical values, other cryptocurrencies'indexes or other markets

Previous Analysis

Most of the existing analysis on cryptocurrencies focus on the Bitcoin.

MIT computer Scientists have predicted the fluctuations of the Bitcoin and have bet every two seconds accordindly to the predictions. (http://news.mit.edu/2014/mit-computer-scientists-can-predict-price-bitcoin) “We needed publicly available data, in large quantities and at an extremely fine scale,” says Shah, the Jamieson Career Development Associate Professor of Electrical Engineering and Computer Science. “We were also intrigued by the challenge of predicting a currency that has seen its prices see-saw regularly in the last few years.” They used historical data for it.

Predicting the fluctuations with Twitter Sentiment Analysis (http://www.diva-portal.org/smash/get/diva2:1110776/FULLTEXT01.pdf)

Predicting Bitcoin index with Forum's comments http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0177630#sec003

Using TensorFlow https://nicholastsmith.wordpress.com/2017/11/13/cryptocurrency-price-prediction-using-deep-learning-in-tensorflow/

Predicting with Google Search https://qz.com/1052656/bitcoin-price-google-trends-can-help-you-figure-where-bitcoins-price-is-headed/

Approach

This project will focus on time-series analysis. It includes:

Exploring the data and comparing it to the Bitcoin fluctuations
Assessing if the data is stationary or not
Making the series stationary
Data

Our data come from http://coinmarketcap.com.


