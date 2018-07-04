
# Q：
> com.alibaba.rocketmq.remoting.exception.RemotingConnectException: connect to <172.17.0.1:10911> failed

# A:
* broker-a.properties 设置固定ip 

```
brokerIP1=192.168.1.10
namesrvAddr=192.168.1.10:9876
```
# R:
> http://valleylord.github.io/post/201607-mq-rocketmq/
