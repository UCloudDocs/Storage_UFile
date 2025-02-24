

# 地域和域名

US3 对象存储提供外网、内网域名两种访问方式：外网域名可响应所有来自于互联网的访问请求，内网域名可响应来自于同一地域下的 UCloud 公有云服务的访问请求（如：UHost 云主机、UK8S 容器云等）。

***若使用外网域名对数据进行访问，会产生外网流出流量费用。***

在您创建存储空间后，您存储空间的访问域名地址格式为：`<存储空间名称>.<域名地址>`。

**公有云下US3各地域访问域名（Endpoint）如下：**

| 地域 | 外网域名 | 内网域名 |
| ---- | -------- | -------- |
| 华北一  | cn-bj.ufileos.com      | ufile.cn-north-02.ucloud.cn      |
| 华北二  | cn-wlcb.ufileos.com      | internal-cn-wlcb.ufileos.com      |
| 上海二 | cn-sh2.ufileos.com      | internal-cn-sh2-01.ufileos.com      |
| 广州  | cn-gd.ufileos.com      | internal-cn-gd-02.ufileos.com      |
| 香港  | hk.ufileos.com      | internal-hk-01.ufileos.com     |
| 洛杉矶 | us-ca.ufileos.com      | internal-us-ca-01.ufileos.com     |
| 新加坡 | sg.ufileos.com      | internal-sg-01.ufileos.com     |
| 雅加达 | idn-jakarta.ufileos.com      | internal-idn-jakarta-01.ufileos.com     |
| 台北  | tw-tp.ufileos.com      | internal-tw-tp.ufileos.com     |
| 拉各斯 | afr-nigeria.ufileos.com      | internal-afr-nigeria.ufileos.com     |
| 圣保罗 | bra-saopaulo.ufileos.com      | internal-bra-saopaulo.ufileos.com     |
| 迪拜  | uae-dubai.ufileos.com      | internal-uae-dubai.ufileos.com     |
| 法兰克福  | ge-fra.ufileos.com     | internal-ge-fra.ufileos.com     |
| 胡志明市  | vn-sng.ufileos.com      | internal-vn-sng.ufileos.com     |
| 华盛顿  | us-ws.ufileos.com      | internal-us-ws.ufileos.com     |
| 孟买  | ind-mumbai.ufileos.com      | internal-ind-mumbai.ufileos.com     |
| 首尔  | kr-seoul.ufileos.com      | internal-kr-seoul.ufileos.com     |
| 东京  | jpn-tky.ufileos.com      | internal-jpn-tky.ufileos.com     |
| 曼谷  | th-bkk.ufileos.com      | internal-th-bkk.ufileos.com     |
| 英国	| uk-london.ufileos.com | internal-uk-london.ufileos.com |
| 莫斯科 | rus-mosc.ufileos.com | internal-rus-mosc.ufileos.com |

**注意：**

**1. 由于存储集群所在地域不同，跨国访问可能会存在响应延迟或失败的情况，海外加速服务功能处于内测阶段，如需使用请联系技术支持。** 

**2. 兼容支持AWS S3协议的访问域名请参见[AWS S3协议支持说明](/ufile/s3/s3_introduction)。**


