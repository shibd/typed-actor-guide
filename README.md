<!--
暂时注释
# 前言
-->

# 一. Typed 目录

### 1. [Actor 和 Behavior](/doc/1-actor-behavior.md)
- (1). 定义
- (2). 为什么是 Behavior, 为什么需要 Typed
- (3). API 变更
- (4). Actor 类型变更
- (5). 测试用例
### 2. [ActorSystem](/doc/2-actor-system.md)
- (1). API 变更
- (2). 测试用例
### 3. [Actor 交互模式 / 发现](/doc/3-actor-interaction.md)
- (1). Akka 交互模式
- (2). 消息适配器
- (3). Actor 发现, 如何获取 ActorRef
### 4. [持久化 Actor](/doc/4-eventsoured-actor.md)
- (1). 经典 Actor 事件溯源
- (2). Typed 事件溯源
- (3). Akka 持久化内部保证及其他功能
### 5. [集群 Actor](/doc/5-cluster.md)
- (1). 集群
- (2). 集群分片
- (3). 集群单例

# 二. Akka 消息交付可靠性

### 1.[Akka 消息投递一般原则](/doc/delivery/1-message-delivery-reliability.md)
- (1). 交付语义 
- (2). 一般原则 
- (3). Akka 为什么不对消息的投递做保证
- (4). Akka 消息排序的保证
- (5). 可靠交付保证
### 2.[经典 Actor 可靠交付](/doc/delivery/2-classic-reliable-delivery.md)
- (1). API
- (2). 特性,注意事项
- (3). 案例
### 3.[Typed 可靠交付通用原则](/doc/delivery/3-typed-reliable-delivery.md)
- (1). 特性
- (2). 交付语义
- (3). 时序图
### 4.[Typed 可靠交付 (一): 点对点模式](/doc/delivery/4-typed-reliable-delivery-p2p.md)
- (1). 特性 
- (2). 交付语义
- (3). API
- (4). 案例
### 5.[Typed 可靠交付 (二): 工作拉取模式](/doc/delivery/5-typed-reliable-delivery-pull.md)
- (1). 特性
- (2). 交付语义
- (3). API
- (4). 案例
### 6.[Typed 可靠交付 (三): 分片模式](/doc/delivery/6-typed-reliable-delivery-sharding.md)
- (1). 特性
- (2). 交付语义
- (3). API
- (4). 案例
