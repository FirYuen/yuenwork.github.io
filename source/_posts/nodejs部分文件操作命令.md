---
title: nodejs部分文件操作相关命令
date: 2018-05-13 15:55:40
tags:
---
写几个Git基础命令。




### 获取当前文件目录

``` JavaScript
process.cwd()
```


### 进入指定目录
```javascript
process.chdir()
```

## 创建文件夹
```Javascript
var fs = require('fs');
fs.mkdirSync('./aaa');
```

## 创建文件
```Javascript
var fs = require('fs');
fs.writeFileSync('./aaa/hello','hello world!');
```