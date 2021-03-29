# Java实现SSO单点登录

## 课程目标

- 认识并理解SSO及其应用，并能根据其实现原理自行实现SSO。

## 学习内容

1. SSO的介绍和应用体验
2. SSO的分类介绍的实现探讨
3. 各种SSO的具体实现介绍的代码示例

## SSO核心技术分析

### SSO的实现步骤和原理

关键：存储票据，查验票据

核心技术点的实现原理：cookie

## 同域SSO

```log
http://localhost/demo1/main.action
http://localhost/demo2/main.action

准备工作：
1.SSM环境（Spring Boot）
2.通用的工具类
```

## 域不同，但是父域相同

```log
http://demo1.x.com/demo1/main.action
http://demo2.x.com/demo2/main.action

统一校验接口：http://check.x.com/checkCookie.action

准备工作：
1.SSM环境
2.修改Host文件
3.tomcat配置
```
