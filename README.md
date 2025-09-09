## Environment setup and running the notebook:

```bash
micromamba env create -f environment.yml
micromamba activate gnn
python -m ipykernel install --user --name gnn --display-name "Python (gnn)"

# The notebook will download necessary data (Wiki-CS dataset)
