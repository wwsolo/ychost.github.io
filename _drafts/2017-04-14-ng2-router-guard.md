---
layout: post
title: Angular2 中的路由守卫
categories: [Angular, 推荐]
description: 有时在页面开发过程中需要用到权限控制，比如用户没有登录就统一转向登录页面等等，以前完成这一工作的需要后台来重定向路由但是现在前端都是做成了 SPA 的模式了，路由是前端自己控制了所以重定向的工作就交给了前端来完成，在 Angular2 中就是利用路由守卫来完成这一工作的。
keywords: Angular2, 路由守卫，重定向
tags: [Angular2, 路由守卫]
---

有时在页面开发过程中需要用到权限控制，比如用户没有登录就统一转向登录页面等等，以前完成这一工作的需要后台来重定向路由但是现在前端都是做成了 SPA 的模式了，路由是前端自己控制了所以重定向的工作就交给了前端来完成，在 Angular2 中就是利用路由守卫来完成这一工作的。

### 