# VM Sandbox Template

Node.js VM 沙箱模板，适合服务端下发混淆 JS 生成 Cookie、Token 或中间签名的场景。

1. 复制本目录到项目工作区。
2. 修改 `main.js` 的两阶段请求配置，并在 `utils/sandbox.js` 补目标环境。
3. 运行 `npm install && npm start` 验证动态 JS 执行和 Cookie 提取。
