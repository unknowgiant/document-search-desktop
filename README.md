# 文档寻迹

Windows 桌面全文检索应用（Electron）：对本地 PDF / Word / TXT 文档做全文关键字检索并定位展示。

- 源码：`desktop/`（`main.js` 窗口壳 + `document-search.html` 单文件界面）
- 开发：`cd desktop && npm install && npm start`
- 打包：`npm run dist`（electron-builder，portable 形态）
- 说明：PDF / Word 解析组件（pdf.js、mammoth）通过 CDN 在线加载，离线环境暂不支持

构建产物与浏览器测试资料不入库（见 `.gitignore`）。

> AI生成
