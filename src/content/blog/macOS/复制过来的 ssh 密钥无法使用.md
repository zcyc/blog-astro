---
title: "复制过来的 ssh 密钥无法使用"
author: "Charles"
description: ""
tags:
  - blog
ogImage: ""
postSlug: "ssh-key-copy-not-work"
pubDatetime: 2022-06-28T17:11:11.000Z
upDatetime: 2022-11-14T14:50:08.000Z
featured: false
draft: false
---

不同系统之间复制 ssh 密钥需要赋予正确的权限，以 mac 为例：

```bash
chmod 0600 id_rsa
```
