# Aequitas Excercise

## Poetry and Jupyter

You will need to make your Poetry virtual environment available to Jupyter.
To do this, install the kernel by path:

```
~/Source/udacity-aequitas-exercise/.venv/bin/python -m ipykernel install --name 'poetry' --user
```

The above makes a lot of assumptions about where you have your Poetry
virtual environment stored. Suffice to say, that path needs to point to the
`python` file.
