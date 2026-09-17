[![CI](https://github.com/maXONYAR/tp-solo-1/actions/workflows/ci.yml/badge.svg)](https://github.com/maXONYAR/tp-solo-1/actions/workflows/ci.yml)

Le pipeline CI se déclenche à chaque push sur 'main' et sur toute pull request : il enchaîne un job 'lint' (flake8) puis, s'il réussit, un job 'test' (pytest avec couverture) exécuté en parallèle sur Python 3.10, 3.11 et 3.12.
