# Proxy

## 动机(Motivation)
+ 在面向对象系统中，有些对象由于某种原因(比如对象创建的开销很大，或者某些操作需要安全控制，或者需要进程外的访问等)，
直接访问会给使用者、或者系统结构带来很多麻烦。
+ 如何在不失去透明操作对象的同事来管理/控制这些对象特有的复杂性？增加一层间接层是软件开发中常见的解决方式。

## 模式定义
为其他对象提供一种代理以控制(隔离，使用接口)对这对象的访问。
——《设计模式》GoF

## 要点总结
+ Proxy并不一定要求保持接口完整的一致性，只要能够实现间接控制，有时候损及一些透明性是可以接受的。