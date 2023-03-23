# Uncertainty-Based-Offline-RL-with-Diversified-Q-Ensemble

This is a blog based on the EDAC paper: [Uncertainty-Based Offline Reinforcement Learning with Diversified Q-Ensemble](https://arxiv.org/abs/2110.01548)

There are several implementations:
* [official](https://github.com/snu-mllab/EDAC)
* [CORL (Clean Offline Reinforcement Learning)](https://github.com/tinkoff-ai/CORL) or our [fork](https://github.com/JonasLoos/CORL)
* [our own implementation](https://github.com/Safe-RL-Team/Uncertainty-Based-Offline-RL-with-Diversified-Q-Ensemble-Implementation)

## run blog locally

### install

* install [Quarto](https://quarto.org/docs/download/)
* clone this repo

```bash
pip install -r blog/requirements.txt
```

### run

```bash
quarto preview blog/blog.ipynb
```


### writing

The main content is in `blog/blog.ipynb`, the references are in `blog/references.bib` and the images are in `blog/figures/`.
