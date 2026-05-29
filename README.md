# buggy-calc

A small Python utility library with intentional bugs. Used as a test target
for the [bug-fixer](https://github.com/timuryesm/bug-fixer) project.

## Running tests

```bash
python -m venv .venv
source .venv/bin/activate
pip install pytest
pytest -v
```

Some tests will fail — that's the point. Each failure corresponds to an
open issue in this repo describing a bug for an AI fixer to resolve.