# sam-robson-testing

Run the unit tests locally with:

```sh
python -m unittest discover -s tests
```

## Code coverage

Install the `coverage` package and run the tests with coverage enabled:

```sh
pip install coverage
coverage run -m unittest discover -s tests
coverage report
```

Generate a Cobertura XML report (used by CI and IDE integrations) with:

```sh
coverage xml -o coverage.xml
```
