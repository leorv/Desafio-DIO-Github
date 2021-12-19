# Desafio-DIO-Github

Desafio onde vou inserir toda a minha aprendizagem com o Github por meio da DIO.
Espero que esta lista de comando também seja útil aos que estão começando.

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

### Voltar para o último commit

> git checkout <nome do branch>

### Associar nosso repositório local ao repositório remoto, dando o apelido de "origin" a ele

> git remote add origin <URI>

### Associar nosso repositório local a um outro repositório remoto, porém mantendo o mesmo apelido

> git remote set-url origin <URI>

### Clonar repositório

> git clone <URI>

Atenção, ao copiar arquivos, não traz o histórico de commits junto.

### Atualizar o repositório local

> git pull origin master (ou main)

### Para criar um branch e mudar para ele ao mesmo tempo

> git checkout -b iss53

obs: iss53 é o nome do branch

### Ou apenas criar o branch

> git branch iss53

### Mudar para o branch

> git checkout iss53

### Estando no main/master, pode fazer o merge

> git merge iss53

### Deletar o branch

> git branch -d iss53