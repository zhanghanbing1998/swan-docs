---
title: AOP说明
header: develop
nav: framework
sidebar: app_service_aop
---

 

小程序的开发者或者服务商会提供一些lib库，用来代理小程序的生命周期或API等，进而想要进行一些通用逻辑的处理(例如: 打点/事件触发/统一登录等等通用逻辑)。

通常，小程序开发者们使用这些扩展包时，不得不在各个使用点（生命周期、事件触发等）处显式调用。

为解决该类问题，智能小程序在框架层提供切面。让扩展包的开发者可以在小程序运行的生命周期/事件触发/API调用等处，注入通用逻辑。



