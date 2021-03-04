# zabbix-TOPSEC TOS NGFW SNMPv2
天融信防火墙zabbix监控模板

基于老tos系统，需设备开启snmp v2c服务
### 系统监控常见参数
- 延迟丢包
- 系统支持最大会话数（系统固定参数）
- 序列号（根据序列号判断主备切换）
- 系统类型及版本
- 系统会话数
- CPU、内存负载


### 基于LLD的端口检测及告警，包含
- 端口发送速度
- 端口接收速度
- 端口双工状态（vlan接口存在半双工问题）
- 端口入丢包
- 端口入错误包
- 端口状态
- 端口出丢包
- 端口出错误包
- 端口速度


感谢[Traveller](https://github.com/TravellerXi)提供zabbix 4.0支持
