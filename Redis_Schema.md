##stock_list##

1. symbol->name
2.id->symbol

* we can list all stock
stock_list.each do |stock_id|
end

* we can list only part of stock

stock_list[100,200].each do |stock_id|
end

- sid:00001:symbol
- sid:00001:name
- symbol: sid


* if a new stock ,new a stock id


* save redis memory by hash way
http://stackoverflow.com/questions/10004565/redis-10x-more-memory-usage-than-data

可以看到，string的类型最节省内存,可以试试

http://support.redistogo.com/kb/info/memory-costs-of-redis-data-structures



数据处理和分析结果

- sid:00001:2013-06-05:price 
- sid:00001:2013-06-05:macd
- sid:00001:2013-06-05:volume
