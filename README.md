# ducoment
异常：<tr/>
com.alibaba.rocketmq.remoting.exception.RemotingConnectException: connect to <172.17.0.1:10911> failed<tr/>
解决方法：<tr/>
  broker-a.properties<tr/>
  设置固定ip<tr/>
  brokerIP1=192.168.232.23<br/>
  namesrvAddr=192.168.232.23:9876<tr/>
参考：http://valleylord.github.io/post/201607-mq-rocketmq/
