# Test of MCP

## Installation

### Windows

Open a powershell:
```
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
```

Close the shell and open a new one. Then, at the root of your project:
```
uv init
```

Then, execute the following commands:
```
> uv venv
> .venv/Scripts/activate
> uv add "mcp[cli]"
```

Finally, run the server with:
```
mcp dev server.py
```

