## Linting (mandatory)

All Python code MUST pass Ruff without warnings.

Before finishing:
- Run: `uv run ruff check .`
- If auto-fixable issues exist, run: `uv run ruff check . --fix`
- Do not consider the task complete if Ruff reports any errors.
- Ruff config is defined in `pyproject.toml`. Follow it strictly.
