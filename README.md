# ycsocket
基于 swoole 和 ycdatabase 的 websocket 框架，各位可以自己扩展到 TCP/UDP，HTTP，全异步协程，全池化，能够支撑较高并发

环境：
PHP7+
ycdatabase   //一个C语言扩展的ORM，本框架协程数据库需要该扩展支持，https://github.com/caohao-php/ycdatabase
swoole

我写游戏后端的时候写的

客户端是一个聊天窗口

支持 Redis 协程线程池，源码位于 system/RedisPool，支持失败自动重连

支持 MySQL 协程连接池， 源码位于 system/MySQLPool，支持失败自动重连

支持共享内存 entity
