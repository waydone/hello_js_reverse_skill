# Node Request Template

纯 Node.js 协议请求模板，适合签名算法可以用 `crypto` / `crypto-js` 直接还原的场景。

1. 复制本目录到项目工作区。
2. 在 `config/headers.json` 放目标请求头，在 `config/keys.json` 放非敏感占位密钥。
3. 修改 `main.js` 和 `utils/encrypt.js` 后运行 `npm install && npm start`。
