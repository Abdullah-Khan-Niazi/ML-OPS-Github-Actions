# ML-OPS-Github-Actions

A small Python library with basic math operations and automated tests.

What it does:

- Provides `add` and `sub` functions.
- Includes pytest tests that verify behavior.

GitHub Actions:

- CI workflow runs pytest on push/PR.

Project layout:

- `src/math_operations.py`: implementation.
- `tests/test_operation.py`: unit tests.
- `.github/workflows/python-app.yml`: CI workflow that runs tests on push/PR.
