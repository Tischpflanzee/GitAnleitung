# Git Anleitung

Die Git anleitung ist wenniger eine Anleitung und mehr eine Einleitung zu git und Github um zu ermöglichen das jemand ohne erfarung einfacher, in ein Projekt das mit Git gemanget wird, einsteigen kann.

# Projekt 

## Latex 

Der Latex text wird mit Latexmk und Livetex gebaut. Da das paket svg genutz wird. Entsteht die abhänigkeit von Inkscape

Dependecies for nix

```nix
nix-shell -p texliveFull inkscape
```

Building Latex:

```bash
latexmk --shell-escape 
```


## Mermaid

Mermaid wird mit Mermaid-cli gebaut:

[Mermaid-Cli](https://github.com/mermaid-js/mermaid-cli)

```bash
mmdc -i inputFile.mmd -o outputFile.svg
```
