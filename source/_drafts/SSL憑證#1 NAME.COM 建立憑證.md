title: SSL憑證#1 NAME.COM 建立憑證
author: John Doe
date: 2022-06-13 11:48:21
tags:
---
# 更新憑證#1 NAME.COM SSL 憑證更新


## 前言

待補!

---

## 準備

待補!

---

## 開始

### 第一步、產生 SSL 憑證簽署要求（CSR）

```Linux=
sudo openssl req -nodes -newkey rsa:2048 -sha256 -keyout myserver.key -out myserver.csr -utf8
```

* -newkey rsa:2048： 產生 CSR 與一個 2048 位元的 RSA 密鑰；

* -sha256：使用 SHA-2，SHA256 雜湊演算法（hash algorithm）

* -keyout myserver.key：將密鑰儲存在當下目錄的「myserver.key」檔案中。

* -out myserver.csr：將 CSR 檔案儲存在當下目錄的「server.csr」檔案中。

執行命令之後，系統會提示您輸入資料，這資料是憑證驗證單位在驗證憑證時會查閱的個人資料

![建置完成範例圖](1651734577669_2.jpg)


### Thank you! :smile:
---

參考

- [Vue Router](https://router.vuejs.org/guide/essentials/history-mode.html)