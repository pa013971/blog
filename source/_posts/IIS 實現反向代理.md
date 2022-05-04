title: IIS 實現反向代理
tags: []
categories: []
date: 2022-05-04 20:02:00
---
# IIS 實現反向代理


## 前言



---

## 準備

IIS

Application Request Routing
下載網址：https://www.iis.net/downloads/microsoft/application-request-routing

URL Rewrite
下載網址：https://www.iis.net/downloads/microsoft/url-rewrite

---

### 開始

當下載並安裝完成後 IIS 會多出兩個功能
![準備完成樣子](\images\1651667908894_new.jpg\)


第一步、啟動代理
![點擊設置](\images\1651667908894_1.jpg\)

![點擊反向代理設定](\images\1651668036918_2.jpg\)

![將反向代理開啟](\images\1651668062343_3.jpg\)

第二步、新增反向代理，設置 URL 規則

![點擊站台設定URL Rewrite](\images\1651668152705_1.jpg\)

![新增規則 / 空白規則](\images\1651668152705_2.jpg\)

![設定並套用](\images\1651668152705_3.jpg\)

設置完畢即完成