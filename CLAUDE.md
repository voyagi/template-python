# Project Instructions

## Language: Python

## Build & Test

- Test: `py -m pytest`
- Lint: `ruff check .`
- Lint + fix: `ruff check --fix .`
- Format: `ruff format .`
- Type check: `mypy .`

## Conventions

- Use type hints for function signatures
- Use `ruff` for linting and formatting (replaces flake8 + black + isort)
- Use `pytest` for testing with descriptive test names
- Prefer pathlib over os.path
- Use dataclasses or Pydantic for structured data
- Handle errors explicitly, never bare `except:`
