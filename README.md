[![CI](https://github.com/maXONYAR/tp-solo-1/actions/workflows/ci.yml/badge.svg)](https://github.com/maXONYAR/tp-solo-1/actions/workflows/ci.yml)

Le pipeline CI se déclenche à chaque push sur 'main' et sur toute pull request : il enchaîne un job 'lint' (flake8) puis, s'il réussit, un job 'test' (pytest avec couverture) exécuté en parallèle sur Python 3.10, 3.11 et 3.12.

docker images                                                                     
IMAGE                ID             DISK USAGE   CONTENT SIZE   EXTRA
dockerfile:1.0       af69082f0c1c        232MB         57.8MB    U
dockerfile:1.1       61cc5145cff0        232MB         57.8MB
dockerfile:2.0       a8e0b4d41b34        224MB         54.5MB    U
dockerfile:naive     31e5f20637db        223MB         53.9MB    U
dockerfile:prod      02c7b00ff296        223MB         53.9MB    U
hello-world:latest   5e2309035332       25.9kB         9.49kB
