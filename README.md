# Pre-commit config file for python projects

Install [pre-commit](https://pre-commit.com/):

```console 
$ python -m pip install pre-commit
```
Update all hooks in config file:

```console
$ python -m pre-commit autoupdate
```

For manual run all git hooks before commit (every time for each run):

```console
$ python -m pre-commit run
```

For auto run all git hooks before commit (once for all runs):

```console
$ python -m pre-commit install
```