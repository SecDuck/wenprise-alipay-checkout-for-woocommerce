﻿# Wenprise Alipay Gateway For WooCommerce #
Contributors: iwillhappy1314
Donate link: https://www.wpzhiku.com/
Tags: Alipay, WooCommerce, woocommerce, payment, payment gateway, gateway, 支付宝, 支付宝支付, Alipay payment gateway, Wechat gateway, credit card, pay, online payment, shop, e-commerce, ecommerce
Requires PHP: 7.1
Requires at least: 3.9
Tested up to: 6.1
Stable tag: 1.2.5
License: GPL-2.0+
WC requires at least: 3.6
WC tested up to: 6.5

Alipay payment gateway for WooCommerce, WooCommerce 支付宝免费全功能支付网关。

## Description ##
**功能更全面的 WooCommerce 免费支付宝支付网关**，企业版，需要支付宝企业认证才可以使用。支持功能如下：

* 支持所有 WooCommerce 产品类型
* PC端扫码或登录账户支付
* 移动端调起支付宝APP、登录wap版支付宝支付
* 支持支付宝同步回调和异步回调
* 支持主动查询支付宝订单完成状态的功能
* 支持在 WooCommerce 订单中直接通过支付宝支付退款，退款原路返回
* 由于支付宝在微信中被屏蔽掉了，支付宝支付在微信中自动隐藏
* 货币不是人民币时，可以设置一个固定汇率
* 支持设置订单前缀

### 插件设置方法及使用教程 ###
[Wenprise Alipay Gateway For WooCommerce 插件设置教程](https://www.wpzhiku.com/wenprise-alipay-gateway-for-woocommerce-document/)

### 付费设置服务 ###
如果你不想自己动手设置，或者自己设置有困难，可以购买我们的付费设置服务。
[WooCommerce支付宝插件设置服务](https://www.wpzhiku.com/product/woocommerce-alipay-service/)

### 微信支付网关 ###
[Wenprise WeChatPay Payment Gateway For WooCommerce](https://wordpress.org/plugins/wenprise-wechatpay-checkout-for-woocommerce/)

### Support 技术支持 ###

Email: amos@wpcio.com

## Installation ##

1. 上传插件到`/wp-content/plugins/` 目录，或在 WordPress 安装插件界面搜索 "Wenprise Alipay Gateway For WooCommerce"，点击安装。
2. 在插件管理菜单激活插件

## Upgrade Notice ##

更新之前，请先备份数据库。


## Frequently Asked Questions ##

### 支持支付宝海外版吗？ ###
这个插件只支持支付宝国内版，海外版需要另外的插件支持，后续会发布另外一个插件。

### 支持在微信中使用吗？###
因为微信无耻的屏蔽掉了支付宝支付，所以本插件不支持在微信中使用，在微信中支付时，插件会自动屏蔽掉自己，以免不能支付带来不好的用户体验。

## Screenshots ##
* Setting
* payment

## Changelog ##
### 1.2.5 ###
* 支持当面付
* bugfix

### 1.2.0 ###
* 支持当面付
* bugfix

### 1.1.3 ###
* 修复重新支付页面中，选择其他支付方法也会打开微信支付页面的 Bug

### 1.1.2 ###
* 增加支付跳转中间页面

### 1.1.1 ###
* 实现重新支付按钮在新表页中打开

### 1.1.0 ###
* 通过 checkout.js triggerHandler 方法解决支付宝弹窗被屏蔽的问题。
* 添加订单号前缀功能

### 1.0.9 ###
* 修复电脑网站支付弹窗被屏蔽的问题
* 修复生成订单后，购物车没有被正确清空的问题

### 1.0.8 ###
* 修复 Block UI 弹窗在移动端显示不全的问题

### 1.0.7 ###
* 防止 WooCommerce 禁用时报错

### 1.0.6 ###
* 同步验证出错时，提示信息而不是显示空白页面

### 1.0.5 ###
* 修复某些情况下，图标不显示的问题

### 1.0.4 ###
* 修复某些情况下未支付时，显示支付成功的 Bug

### 1.0.3 ###
* 修改支付宝跳转方式为站内页面代理，以便在在新窗口中打开、同时弹出支付确认窗口
* 增加主动查询功能、以便在其他验证方式不可用时，验证订单是否支付

### 1.0.2 ###
* Bugfix

### 1.0 ###
* 初次发布