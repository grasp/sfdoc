## signal

- macd signal
- price signal
- volume signal

* then generate signal file

* read signal file

* back test by signal and policy during some day
* 

#价格涨跌分析
一天后价格涨跌
二天后价格涨跌
三天后价格涨跌
。。。。。
[1,2,3,4,5,6,7,8,9,10]

这样看来还是需要关系数据库的帮忙的



##单个组合分析

多个组合会有多个 true false 组合

有一些可能会相同，而有一些会不同

同一个组合可能会有不同的结果

一个组合可能会涨，也可能会跌

出现的总次数，赢的次数，输的次数，那么结果就出来了


报告格式
[0] [true,false,...]  [total,win,loss,win_percent,loss_pecent]
[1] [true,false,...]  [total,win,loss,win_percent,loss_pecent]

报告处理

report win_percent(symbol,percent)
report loss_percent(symbol,percent)



