# 车联网项目

## Overview

## 项目结构分基础架构、业务项目
### 基础架构及组件
```
├── micro-framework-parent - 基础架构顶级工程
│   └── micro-common-utils - 公用工具模块
│   └── micro-exception - 异常处理模块
│   └── micro-filesystem - 文件上传模块(oss)
│   └── micro-message-push - 极光消息推送模块
│   └── micro-mongodb - mongodb非关系数据库连接模块
│   └── micro-oauth2 - oauth2权限认证模块
│   └── micro-rediscache - redis连接及api封装模块
│   └── micro-sms - 短信发送模块
│   └── micro-verify-realname - 身份证、行驶证实名认证模块
│   └── micro-web-framework - web项目分布、数据库连接模块
│
```
### 业务项目结构
```
├── isuzu-gateway-网关项目
│   └── isuzu-upms-sdk-权限模块
│── isuzu-portal-门户网站接口应用
│   └── portal-api-对外接口模块
│   └── portal-dao-数据操作层模块
│   └── portal-model-实体模块
│   └── portal-service-提供接口服务模块
│
│── isuzu-portal-门户网站接口项目
│   └── portal-api-对外接口模块
│   └── portal-dao-数据操作层模块
│   └── portal-model-实体模块
│   └── portal-service-提供接口服务模块
│
│── isuzu-product-app-生产APP接口项目
│   └── product-app-api-对外接口模块
│   └── product-app-dao-数据操作层模块
│   └── product-app-model-实体模块
│   └── product-app-service-提供接口服务模块
│
│── isuzu-mobile-app-手机APP接口项目
│   └── mobile-app-api-对外接口模块
│   └── mobile-app-dao-数据操作层模块
│   └── mobile-app-model-实体模块
│   └── mobile-app-service-提供接口服务模块
│
│── isuzu-tsp- TSP运营平台接口项目
│   └── tsp-api-对外接口模块
│   └── tsp-dao-数据操作层模块
│   └── tsp-model-实体模块
│   └── tsp-service-提供接口服务模块
│
│── isuzu-localtion-车辆轨迹位置项目
│   └── localtion-api-对外接口模块
│   └── localtion-dao-数据操作层模块
│   └── localtion-model-实体模块
│   └── localtion-service-提供接口服务模块
```
### 项目环境搭建
#### 1.确保JDK1.8
![](https://raw.githubusercontent.com/fengbinking/config-repo/master/isuzu/images/jdk.png)
)
#### 2.
