# Wasserrakete Notebook

This folder contains a Jupyter notebook for modelling a vertical water-rocket launch and finding the filling level that maximizes the height.

## Run with uv

```bash
cd wasserrakete_uv
uv sync
uv run python -m ipykernel install --user --name wasserrakete --display-name "Python (Wasserrakete)"
uv run jupyter lab
```

Then open `Wasserrakete_vertikaler_Start.ipynb`.

If you do not want to install a kernel globally, you can also just run:

```bash
uv run jupyter lab
```

and select the project environment from Jupyter.
