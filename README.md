# cross_notebooks

Jupyter notebook collection for the CROSS project. The notebooks can be used on 
Google Colab or locally. Notebooks are located in the folder `/notebooks` and 
contain a link to run them in Colab.

For local installation [uv](https://docs.astral.sh/uv/getting-started/installation/)
is the most convenient approach.

```bash
git clone https://github.com/sweet-cross/cross_notebooks.git
cd cross_notebooks
uv sync
```

Alternatively, create a virtual environment, activate it, and install using pip:

```bash
git clone https://github.com/sweet-cross/cross_notebooks.git
cd cross_notebooks
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install -e .
```

