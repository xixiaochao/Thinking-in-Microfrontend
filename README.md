# Thinking-in-Microfrontend

微前端的那些事儿

## 什么是微前端

> 背景；
> - 前端应用越来越复杂

> 导致：
> - 人力成本压力
> - 维护成本高
> - 迭代成本高
> - 需求变更影响范围大
> - 持续化投入产出比不足

> 所以：
> - 面对这种情况【其他人（后端）】是如何处理的？

> 答案：
> - 重新洗牌（先拆后合）

> 优点：
> - 隔离（服务，IDC）
> - 弹性/扩展性（如：扩容）
> - 增强稳定性
> - 降低成本（人力，上线，回归，需求）
> - 。。。。

> 注意事项：
> - 测试
> - 部署
> - 服务拆分标准
> - 过于分散/密集

> 名词解释：
> - 微前端就是后端微服务思想在前端的映射

> 问题：
> - 微前端如何在浏览器中落地？

## 微内核架构

> 微内核架构
> - Windows，macOS操作系统架构

> 组成部分
> - 系统核心
> - 系统服务
> - 插件系统（可执行程序）

> 为什么选择它？
> - 服务间高度解耦
> - 统一的插件标准
> - 轻量级的事件机制
> - 单一容器应用的最佳选择
> - 对业务更低的侵入性
> - 渐进式开发

git clone https://github.com/YataoZhang/my-single-spa
https://single-spa.js.org/docs/getting-started-overview

https://microfrontends.cn/ 
Micro-frontend Architecture in Action-微前端的那些事儿
