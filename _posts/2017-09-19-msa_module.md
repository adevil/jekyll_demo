---
layout: post
keywords: web 架构 SOA 微服务
description: 微服务 模块
title: 关于微服务边界及模块划分
categories: [架构]
tags: [架构,  总结]
group: archive
icon: file-alt
---
{% include site/setup %}

- 按照领域驱动设计的思想拆分，所谓领域，指的是业务方不需要了解技术的情况下对业务的表达
- 系统架构最终将与组织架构保持一致
- 初期按组织结构分，产品(订单) 运营(用户) 财务(账户/结算) 风控(风控) 技术(基础功能模块)......
- 随着业务的发展，当模块的某个独立功能业务量足够大，会独立成一个服务，组织结构也会配置专人负责
