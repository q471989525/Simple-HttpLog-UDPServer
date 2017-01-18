# Simple-HttpLog-UDPServer\n
LogServer\n
为实现多个小型业务用户访问轨迹记录，而开发此简单的服务端。如有需求会持续优化。\n
功能描述：在http项目中，使用过滤器拦截路径，记录所有请求信息，发送给此服务读记录用户日志。\n
服务端功能：udp接受数据，记录到mongodb中。\n
实现功能：高性能udp服务，心跳检查服务状态，Map序列号传输，批量插入mongodb。\n
