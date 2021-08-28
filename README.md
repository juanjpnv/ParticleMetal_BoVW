# Sobre
Codificação em python do método Bag of Visual Words para classificação de imagens de metal particulado, baseado no artigo de DeCost e Holm.

# Cite
Se parte do código ou das imagens deste repositório lhe foi util de alguma forma, por favor, cite o seguinte artigo
```
Após publicado, aqui estará a citação em formato ABNT
```

```
Após publicado, aqui estará a citação em formato BibTex
```

# Bag Of Visual Words (BoVW)
O BoVW é um método de extração de características composto, que consiste em usar um extrator mais simples (SIFT, ORB, SURF, LBP, ou outro a sua escolha) e um método de agrupamento (K-Mean, KNNClustering, ou outro). Cada características extraída é considerada uma "palavra visual" e o método de agrupamento é usado para gerar um "dicionário de palavras visuais".

> Esquema básico do BoVW
> 
> ![plot](./BoVW_fluxogramaMeu.png)
> 
> Fonte: [Link pro artigo publicado no POSMEC](). Baseado na imagem presente em [L. Fei-Fei; P. Perona](https://ieeexplore.ieee.org/document/1467486)

# Base de dados
Utilizamos a base de dados Synthetic SEM Images of Powder Materials disponibilizada gratuitamente pelos autores. Se deseja utilizar a base de dados refira-se ao artigo original.

Artigo da base de dados: [A large dataset of synthetic SEM images of powder materials and their ground truth 3D structures
](https://www.sciencedirect.com/science/article/pii/S2352340916306382?via%3Dihub). 

# Licensa
Todo este repositório, incluindo códigos, notebooks, imagens, arquivos e etc. está sobre a licensa GPLv3.
