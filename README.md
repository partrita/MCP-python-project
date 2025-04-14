# MCP-python-project

MCP to your python project

# How to use

## Install dependancy

```bash
brew install node
brew install uv
```

```bash
uv sync
uv run mcp dev server.py

# Add dependencies
uv run mcp dev server.py --with pandas --with numpy

# Mount local code
uv run mcp dev server.py --with-editable .
```
