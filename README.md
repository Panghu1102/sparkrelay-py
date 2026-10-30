# sparkrelay-py

Initial packaging scaffold for SparkRelay. No functional API has been implemented yet.

## Development

```bash
python -m pip install -e .
python -c "import sparkrelay; print(sparkrelay.__version__)"
python -m pip install build
python -m build
```

## PyPI publishing

Configure PyPI trusted publisher: project `sparkrelay-py`, owner `Panghu1102`, repository `sparkrelay-py`, workflow `publish.yml`, environment `pypi`. Create the matching GitHub Actions environment.

When ready, update versions in `pyproject.toml` and `src/sparkrelay/__init__.py`, then push a matching tag like `v0.1.0`. Do not publish this placeholder package before adding the actual implementation.
