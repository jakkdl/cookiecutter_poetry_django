# cookiecutter_poetry_django

python django project template with pre-configured development tools:
 - poetry: Dependency Management for Python
 - tox: automation tool with preconfigured test script (tox.ini)
 - pytest: powerful testing framework
     - pytest-cov: check code coverage
     - pytest-django: make it work with django
 - pre-commit
     - black: Code Formatter
     - blacken-docs: Check code fragments in docs
     - pre-commit-hooks: various small checks
     - autoflake: remove unused imports and variables
     - reorder-python-imports: sort imports and put one on each line to avoid merge conflicts
     - flake8: static code analysis
       - flake8-bandit: security testing built right into your workflow
       - flake8-django: django-specific checks
       - flake8-bugbear: finding likely bugs and design problems in your program
       - flake8-builtins: Check for python builtins being used as variables or parameters
       - flake8-comprehensions: write better list/set/dict comprehensions
       - flake8-eradicate: find commented out (or so called "dead") code
       - flake8-mutable: check mutable default argument
       - pep8-naming: Check your code against PEP 8 naming conventions
     - mypy: Static Typing for Python
       - django-stubs: typing stubs for django
       - django-stubs-ext: runtime monkey-patching for e.g. generic django classes

 
## usage
 1. install [cookiecutter](https://cookiecutter.readthedocs.io/en/1.7.2/installation.html) and [poetry](https://python-poetry.org/docs/)
 `pip install --user cookiecutter poetry`
 2. create project: `cookiecutter gh:jakkdl/cookiecutter_poetry_django`
 3. Follow instructions in project README.md
