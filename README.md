# python-dependency-checker

Just a small script to ease checking the dependencies in a requirements.txt.

## Usage

Simply run

```bash
curl -fsSL https://raw.githubusercontent.com/shaardie/python-dependency-checker/master/check_dependencies | sh
```

But be aware of the security implications!

You can further configure this script further with environment variables:

* `REQUIREMENTS`: requirements.txt file to use. Defaults to `requirements.txt`
* `VENV`: Using this virtual environment instead of creating a temporary.
