# sam-robson-testing

Run the unit tests locally with:

```sh
python -m unittest discover -s tests
```

## Code coverage

Coverage is measured with [coverage.py](https://coverage.readthedocs.io/), configured in `.coveragerc`.

```sh
pip install coverage
coverage run -m unittest discover -s tests
coverage report
coverage xml   # generates coverage.xml (Cobertura format)
```

Most IDEs (PyCharm, VS Code) can pick up `.coveragerc` automatically to show
per-line coverage while editing.
