# python-requests
Open-Meteo Python Library using `requests`




### Development

```bash
pip3 install .
pip3 install ".[test]"
pip3 install pytest-xdist
pre-commit install

black .
flake8
bandit -r openmeteo_requests/
pylint openmeteo_requests/
python3 -m pytest tests/
pre-commit run --all-files
```
