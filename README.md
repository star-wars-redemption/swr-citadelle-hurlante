# La Citadelle Hurlante - Campagne Star Wars Redemption

## Synopsys


## License
![image](https://git.framasoft.org/sw-redemption/latex-swr-class/raw/master/_img/wtfpl-badge.png)

## Contributions

### Pré-requis LaTeX
Avant toutes chose, il faut installer XeLaTeX et quelques dépendances pour pouvoir compiler :

```
# apt install --no-install-recommends gv texlive-base texlive-bibtex-extra texlive-extra-utils texlive-font-utils texlive-fonts-recommended texlive-lang-french texlive-latex-extra texlive-latex-recommended texlive-pictures texlive-xetex latexmk lmodern biber 
```

### Build

```
latexmk -f -r swr-class/latexmkrc 
```
