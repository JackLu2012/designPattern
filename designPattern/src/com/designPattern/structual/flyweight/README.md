# 享元模式

## 意图

运用共享技术有效地支持大量细粒度的对象。


## 解析


![](../../../../../img/flyweight.png)


## 总结

享元模式本质也就是个共享池，你肯定知道线程池、连接池等，其实是一个道理，目的是为了达到共享复用，另外也算是将职能独立出来。

为了统一管理享元对象，使用了简单工厂（FlyweightFactory）统筹处理对象。




