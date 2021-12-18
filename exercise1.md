# Language choosen : Python

1) Tools used for testing in python are  pytest, unittest,  nose ​,pytest-cov (for evaluating test coverage), BuildBot (for automated test cycle to validate the changes).

    Tools used for linting in python are Flake8, Pylint, PyFlakes, pycodestyle, pydocstyle, Bandit,MyPy etc

    Python is an intrepreted language so its build mainly involves testing and execution but not compilation so specific transpiling tools like webpack in Javascript are not required.

2) Alternative  CI tools besides Jenkins and GitHub Actions are Circle CI, Travis CI,  Gitlab, Bazel ,Tox.  etc.

3) Setups like Circle CI  provides self hosted infrastructure along with Circle CI cloud support . Travis CI also provides self hosted solution like Travis CI Enterprise along cloud hosted infrastructure.
There are specific cases to consider whether to use the self hosted or cloud hosted infrastructure. Self hosted setups mentioned above are used in cases where we need more resources or if there are custom needs that cloud hosted solution could not provide etc.
Otherwise from other points considering maintenance cost , provisioning , setup duration etc, cloud hosting is the way to go.