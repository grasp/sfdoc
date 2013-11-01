==how to collect data

* 数据接口和API汇总
 - http://blog.sina.com.cn/s/articlelist_2127818045_10_1.html
 - 
 

##Yahoo Limit
How many times can I call YQL in a minute/hour/day?
Rate limits in YQL are based on your authentication. 
If you use IP-based authentication, then you are limited to 
2,000 calls/hour/IP to the public YQL Web service URL (/v1/public/*) 
or 20,000 calls/hour/IP to the private YQL Web service URL (/v1/yql/*) 
that requires OAuth authorization. See the YQL Web Service URLs for the public and private URLs.
Applications (identified by an Access Key) are limited to 100,000 calls/day/key*. 
However, in order to make sure the service is available for everyone we ask that you don't call YQL 
more than 0.2 times/second or 1,000 times/hour for IP authenticated users and 2.7 times/second 
or 10,000 times/hour.


## API for ruby
https://github.com/nas/yql
