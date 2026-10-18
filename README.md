# DAG Scheduler

Deterministic topological task ordering with cycle and missing dependency checks.

## Requirements
Python 3.11+ (standard library only).

## Tests

```sh
python -m unittest discover -s . -p 'test_core.py' -v
```

- `core.py`: task DAG planner and cycle detection
- `test_core.py`: unit tests
- `.github/workflows/tests.yml`: Python 3.11–3.13 CI

This is an educational portfolio/reference implementation and not a production scheduler.
