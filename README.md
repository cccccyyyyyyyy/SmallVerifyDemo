# SmallVerifyDemo

一个最小的静态页面，用于部署链路验证。

## 内容

- `index.html` — Hello World 页面（纯静态，无依赖）

## 本地预览

直接双击 `index.html`，或：

```bash
python3 -m http.server 8080
# 打开 http://localhost:8080
```

## 部署

任意静态服务器（Nginx / Apache / S3）把 `index.html` 放上去即可。
