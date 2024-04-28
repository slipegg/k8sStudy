# K8s 学习记录

记录自己k8s学习的过程。目前主要参考的资料有：
* [Kubernetes(K8S) 入门进阶实战完整教程，黑马程序员K8S全套教程（基础+高级）](https://www.bilibili.com/video/BV1Qv41167ck)
* @[冰糖没糖](https://space.bilibili.com/91817852)的黑马教程学习笔记：<https://www.aliyundrive.com/s/kxsuGkfpvBJ>

## 关于存储
目前已经构建了nfs，10.60.150.179是主服务器，master和node1的/data目录是和10.60.150.179:/data 关联到了一起。