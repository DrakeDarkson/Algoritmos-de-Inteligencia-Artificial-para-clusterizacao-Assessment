# Algoritmos de IA para Clusterização — Parte 1 (Infraestrutura)

## Ambiente
- **Python:** 3.10.19  
- **Ambiente:** Conda (`ia-clusterizacao`)
- **Kernel Jupyter:** Python (ia-clusterizacao)

## Como reproduzir o ambiente
```bash
conda create -n ia-clusterizacao python=3.10 -y
conda activate ia-clusterizacao
pip install -r requirements.txt
python -m ipykernel install --user --name ia-clusterizacao --display-name "Python (ia-clusterizacao)"
jupyter lab
