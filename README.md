# POSIX 多线程程序设计

## [概述](./doc/01_overview.md)

- [术语定义](./doc/01_overview.md#术语定义)
- [线程的好处](./doc/01_overview.md#线程的好处)
- [线程的代价](./doc/01_overview.md#线程的代价)
- [选择线程还是不用线程](./doc/01_overview.md#选择线程还是不用线程)
- [POSIX 线程概念](./doc/01_overview.md#POSIX 线程概念)
- [异步编程举例](./doc/01_overview.md#异步编程举例)

## 线程

- 建立和使用线程
- 线程生命周期

## 同步

- 不变量、临界区和谓词
- 互斥量
- 条件变量

## 使用线程方式

- 流水线
- 工作组
- 客户/服务器

## 线程高级编程

- 一次性初始化
- 线程属性
- 取消取消
- 线程私有数据
- 线程实时调度

## POSIX 针对线程的调整

- 多线程与fork
- 多线程与exec
- 多线程与signal
- 多线程与stdio
- 进程结束
- 线程安全函数

## 线程扩展

- 栅栏（Barriers）
- 读/写锁（Read-Write Lock）
- 自旋锁（Spin Locks）
- 信号量（Semaphore）

## 线程同步精要

- 线程同步四项原则
- 互斥器
- 条件变量
- 不要使用读写锁和信号量