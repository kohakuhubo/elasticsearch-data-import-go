# elasticsearch-data-import-go
ES索引数据导入

描述：该项目主要在分布式系统环境下，实现安全的、并发的、全量的倒入ES索引数据

主要功能：
1、支持分布式全量并发倒入ES索引数据
2、全量并发部分分片失败后，支持以分片为维度的重新倒入
3、支持在非全量倒入情况下的，以分片为维度的倒入数据
4、支持增量倒入数据，并且支持在全量和增量并行的情况下的双写

主要目的：该项目主要是总结了工作经验，并且进一步完善，使用Go语言来实现（主要是为了验证自己的Go语言知识）
