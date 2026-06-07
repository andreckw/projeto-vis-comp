# A1 Visão Computacional

O cenario utilizado para este projeto foi o cenário A: Inspeção de frutas em uma central de distribuição

## Comandos necessários

### venv e bibliotecas necessárias

- Para linux
```bash
python -m venv .venv; source .venv/bin/activate; pip install -r requirements.txt
```

- Para Windows
```shell
python -m venv .venv; .venv/Scripts/activate.bat; pip install -r requirements.txt
```

### Rodar os notebooks

```bash
jupyter nbconvert --to notebook --execute notebooks/01_segmentacao.ipynb notebooks/02_features.ipynb notebooks/03_classificacao.ipynb 
```