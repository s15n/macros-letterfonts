Nützliches für TeX (Deutsch)

How to use (in einer git-repository):
```bat
git submodule add https://github.com/simon14264/macros-letterfonts.git
```
zum Aktualisieren:
```bat
git submodule update --remote
```


How to use (im .tex Dokument):
```tex
\input{macros-letterfonts/letterfonts}
\input{macros-letterfonts/macros}
```

Benötigte Packages:
* `amsmath`
* `amssymb`
* `euscript` für `\Eu_` commands
* `dsfont` für `\bbid`
* Für `\kk` eine Schrift, die `\mathbb{k}` unterstützt. Sonst benutze `\Bbbk`