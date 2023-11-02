# `unittest`

`unittest` is a built into the standard Python library. A few things to keep in mind:

- The naming convention for the test file is `test_<python file to be tested>.py`, hence `test_calc.py`
- Tests must be structured as methods in a class
- Class name can be anything
- Method names must start with "test...", otherwise they won't be run
- Test assertions must use `self.assertEqual()`
- Adding a call to `unittest.main()` simplifies the entry point to be `python3 test_calc.py`
- Alternatively, entry point can be `python3 -m unittest test_calc.py`
