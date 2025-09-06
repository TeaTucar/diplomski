To recreate the used environment run:
micromamba env create -f environment.yml
micromamba activate gnn

Install this to run gcn.ipynb:
python -m ipykernel install --user --name gnn --display-name "Python (gnn)"
The notebook will download necessary data files (LRGB, PascalVOC-SP dataset)