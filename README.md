# pastierrefined1k-kit

Summarize numeric CSV columns (n / min / max / mean).

Small, dependency-free Python utility package generated for day-to-day file chores.
Standard library only — no third-party imports.

## Install

```bash
pip install -e .
```

## Usage

```bash
python -m pastierrefined1k_kit.cli --help
```

```python
from pastierrefined1k_kit.core import Pastierrefined1kTool

tool = Pastierrefined1kTool()
print(tool)
```

## Layout

```
pastierrefined1k_kit/
  __init__.py
  core.py
  cli.py
tests/
  test_core.py
```

## License

MIT © 2026 pastierrefined1k
