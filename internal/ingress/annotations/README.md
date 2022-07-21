# annotations
1. Informer 机制：每一个k8s Resource 都实现了Informer 机制，均有 Informer 和 Lister 方法
2. [注释](https://kubernetes.io/zh-cn/docs/concepts/overview/working-with-objects/annotations/)：注解为对象附加任意的非标识的元数据。客户端程序（例如工具和库）能够获取这些元数据信息