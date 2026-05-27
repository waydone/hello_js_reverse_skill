# Python Request Template

纯 Python 协议请求模板，适合用 `hashlib` / `pycryptodome` 还原签名算法的场景。

1. 复制本目录到项目工作区。
2. 在 `config/headers.json` 放目标请求头，在 `config/keys.json` 放非敏感占位密钥。
3. 修改 `main.py` 和 `utils/sign.py` 后运行 `pip install -r requirements.txt && python main.py`。
