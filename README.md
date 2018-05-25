# testing-in-python
An example about testing in python.


## Important Note
1. filename of the test file must begin with "test" in lowercase (ex. test_math_util.py)
2. test class must inherit unittest.Testcase
3. test method must begin with "test" in lowercase

## Precondition
```sh
virtualenv -p python3 envname
source venv/bin/activate
pip install -r requirements.txt
```

## Run Test
```sh
nose2 -v
```

## Run Test With Coverage Report
```sh
nose2 -v --with-coverage --coverage-report html --coverage src
```
