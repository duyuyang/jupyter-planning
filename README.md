# Planning data analysis

## Setup

- Create virtual environment & Install required packages

```s
$ conda create -n venv -y --file package-list.txt

# -n: Create new virtual environment
# -y: Do not ask for confirmation
# --file: Install the packages from the file
```

- Activate virtual environment

```s
$ source activate venv
```

- Start jupyter

```s
$ jupyter notebook
```

## Clean up

- deactivate virtual environment

```s
$ source deactivate
```
