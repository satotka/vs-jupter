# VS Code and Jupyter Python

## require

- python3

## setup - linux

1. Python venv

```bash
python3 -m venv venv
```

2.  Activate venv

```bash
source venv/bin/activate
```

3. install jupyter  pandas etc,

```bash
pip install jupyter pandas lxml plotly-express
```

4. settings for vs code

See: .vscode/settings.json

- Python PATH for venv
- file watch exclude for venv

## setup - windows

1. Python venv

```powershell
python -m venv venv
```

or

```powershell
py -m venv venv
```

2.  Activate venv

```powershell
Set-ExecutionPolicy RemoteSigned
venv\Scripts\activate.ps1
```

3. install jupyter  pandas etc,

```powershell
pip install jupyter pandas lxml plotly-express
```

- Proxy有りの場合、pip失敗する。回避方法は調査中。
  - SSL: CERTIFICATE_VERIFY_FAILED : ProxyがSSL証明書を置き換えている？ Proxyサービスが提供しているCAを追加する必要あり。

