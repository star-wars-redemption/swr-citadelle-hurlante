# La Citadelle Hurlante - Campagne Star Wars Redemption

## Synopsys


## License
![image](http://www.wtfpl.net/wp-content/uploads/2012/12/wtfpl-badge-1.png)

## Contributions

### Pré-requis LaTeX
Avant toutes chose, il faut installer XeLaTeX et quelques dépendances pour pouvoir compiler :

```shell
apt install --no-install-recommends texlive-base texlive-bibtex-extra texlive-extra-utils texlive-font-utils texlive-fonts-recommended texlive-lang-french texlive-latex-extra texlive-latex-recommended texlive-pictures texlive-xetex latexmk lmodern biber 
```

### Build

```shell
latexmk
```

for dev mode

```shell
latexmk -pvc
```
