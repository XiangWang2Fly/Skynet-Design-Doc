- Failure Mode and Effects Analysis

|Num|Failure|Module|Sevrty|Liklhd|Plan|Do|Check|Act|
|---|---|---|---|---|---|---|---|---|
|1|if big rise happens on one day,the next day it needs drop 50% to reach 2dayfall condition|Indicator|4|10|||||
|2|no simulation test result comparison between each released version|Overall|6|10|||||
|3|抓不到特别大的变化，比如20天50%的涨幅|Monitor|6|10|这是小概率的事件，如果每年涨30%，7年就6倍了。为小概率加大风险不值得|None|||
|4|表现落后，又不能挣钱的板块，资金随时可能撤离，shortday离场有点慢|MarketSelector|4|10|改进并追踪结果|Ver.159|有效次数: 1 无效次数: 0|更新日期：2019-4-9|
