# VS Code and Jupyter Python


1. Python venv

```bash
python3 -m venv venv
```

2.  Activate venv

```bash
source venv/bin/activate
```

3. install jupyter  pandas

```bash
pip install jupyter pandas lxml plotly-express
```

4. settings for vs code

.vscode/settings.json

```bash
{
    // Python PATH
    "python.pythonPath": "${worksspaceFolder}/venv/bin/python",
    // watch exclude
    "files.wacherExclude": {
        "**/venv**": true
    },
}
```
