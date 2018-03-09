# rabbitmq-inform
This is the repository for make docker image of rabbitmq used by the inform system of CBIM.

# 启动命令
~~~
docker run -d -p 1883:1883 -p 4369:4369 -p 5671:5671 -p 5672:5672 -p 15671:15671 -p 15672:15672 -p 25672:25672 --hostname my-rabbitmq --name rabbitmq-test rabbitmq-inform:0.1
~~~

# 
