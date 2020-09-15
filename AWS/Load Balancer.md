# Load Balancer

## 定义

Elastic Load Balancing 可以在单个可用区或多个可用区内的多个目标（Amazon EC2 实例、容器和 IP 地址）之间自动分配流量。

## 三种类型的LB的区别

- Application Load Balancer

- Network Load Balancer 

- Classic Load Balancer

  参考资料

https://amazonaws-china.com/cn/elasticloadbalancing/features/#compare

Elastic Load Balancing 可以检测无法正常运行的目标、停止向它们发送流量，然后将负载分散到剩余的正常运行的目标上。未能对可配置的连续次数完成运行状况检查的实例被视为不正常。负载均衡器将不再向实例发送请求，直到它通过另一次运行状况检 查。

