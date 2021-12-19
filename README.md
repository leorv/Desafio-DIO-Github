# Desafio-DIO-Github

Desafio onde vou inserir toda a minha aprendizagem com o Github por meio da DIO.

## Links Úteis

[Sintaxe Básica Markdown](https://www.markdownguide.org/basic-syntax/)

## Comandos relevantes

### Adicionando um README.md

> git add README.md

> git push -u origin main

> git remote -v

> git log

> git log --oneline

### Para sair do VIM (sim, no começo pode dar o desespero e simplesmente fecharmos o terminal, hehe)

> ESC + :q! + ENTER

### Descartar modificações, voltando ao estado do commit atual

> git clean -df
> git checkout --

### Remover o último commit mantendo as alterações nos arquivos

> git reset --soft HEAD~1

### Remover o último commit INCLUSIVE as alterações nos arquivos (PERIGO)

> git reset --hard HEAD~1

### Navegar entre commits, alterando os arquivos temporariamente

> git checkout <código do commit>
