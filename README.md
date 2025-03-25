# RTSP-Service

> 这是运行在Linux平台，由C代码编写的简单RTSP Service端。

#### RTSP/RTP/RTCP协议

​	RTSP是一个网络通信协议，本身并不具备传输流的功能，主要用于协商发起通信。

​	RTP用于传输流媒体，支持TCP/UDP，一般是用UDP来传输TS流/MP4。

​	RTCP是用于监控RTP的传输质量的。

##### 代码实现的基本思路

> 1. 动态获取自己的IP
> 2. 