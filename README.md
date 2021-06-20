## Setup

```
git clone git@github.com:osman199/dvc.git

```

```
pipenv install --dev
```

```
git checkout pre-dvc
```

## DVC

Initialize DVC

```
dvc init
```

and add remote storage (local in this case)

```
dvc remote add -d localremote /tmp/dvc-storage
```

disable analytics (optional)

```
dvc config core.analytics false
```
## License
MIT
