# IPFS 学习笔记

IPFS 相关学习笔记，包括：
- 基本概念
- 常用命令
- 测试实验

* [Introduction](README.md)
* [IPFS](ipfs/readme.md)
    * [supervisor 管理 ipfs](ipfs/supervisor.md)
* [IPFS Cluster](ipfs-cluster/readme.md)
    * [概述](ipfs-cluster/overview.md)
    * [多集群通信](ipfs-cluster/cluster-of-clusters.md)
    * [supervisor 管理 ipfs-cluster-service](ipfs-cluster/supervisor.md)
    * [集群启动方式一：预设置集群节点](ipfs-cluster/peerset.md)
    * [集群启动方式二：动态添加新节点](ipfs-cluster/bootstrap.md)
    * [两种集群启动方式比较](ipfs-cluster/compare.md)
    * [实验：存储和回收](ipfs-cluster/storage.md)
    * [实验：集群节点故障](ipfs-cluster/peer-down.md)
    * [实验：pin add 不同大小的文件](ipfs-cluster/differentsize.md)
    * [实验：多并发 pin add 操作](ipfs-cluster/pressure.md)
    * [实验：自定义某文件副本数](ipfs-cluster/custom-replication.md)

* [参考文献](reference.md)


### Author

csxuejin@gmail.com

[github](https://github.com/csxuejin/ipfsnote)

[gitbook](https://csxuejin.gitbooks.io/ipfsnote/content/)
