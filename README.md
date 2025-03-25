# GRAPH-project-2025

## Télechargement des données

### Facebook graph

download the facebook graph data from the [url](https://snap.stanford.edu/data/ego-Facebook.html) : 

sous linux : 

```bash
mkdir -p data
wget https://snap.stanford.edu/data/facebook_combined.txt.gz
wget https://snap.stanford.edu/data/facebook.tar.gz
gunzip facebook_combined.txt.gz -d data/facebook_combined.txt
tar -xvzf facebook.tar.gz -C data/
rm facebook.tar.gz
rm facebook_combined.txt.gz
```

### bio graph

```bash
mkdir -p data
wget https://snap.stanford.edu/biodata/datasets/10000/files/PP-Pathways_ppi.csv.gz
mv PP-Pathways_ppi.csv.gz data/
```