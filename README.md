# sam-robson-testing

Run the unit tests locally with:

```sh
python -m unittest discover -s tests
```

Run the tests with code coverage (requires the `coverage` package, `pip install coverage`):

```sh
python -m coverage run -m unittest discover -s tests
python -m coverage report
```

Generate an XML coverage report (e.g. for IDE integration):

```sh
python -m coverage xml
```
