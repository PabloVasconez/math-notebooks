# math-notebooks
A repo to store my personal math-notebooks.

## Environment

Example using `virtualenv` and `pip` to install the dependencies from the `requirements.txt` in a new environment .env on Linux:

```bash
python -m venv .env
source .env/bin/activate
python -m pip install --upgrade pip setuptools
pip install -r requirements.txt
python -m ipykernel install --user --name=math-notebooks
```

The notebooks are developed using python version 3.11.