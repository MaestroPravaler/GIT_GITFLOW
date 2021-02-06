## Comandos Básicos do Git / Gitflow
Este repositório está relacionado a [playlist](https://www.youtube.com/playlist?list=PLQvwSWYdLssx2xmuBSpOEVTjb2SQvR1_b) do meu canal no youtube onde ensino os comandos básicos do git e do gitflow.

## GitFlow e seu fluxo de Trabalho
![](assets/images/capa_gitflow.png)

1. Inicializando um repositório com o gitflow
```
git flow init
```
2. Criando e finalizando uma Feature
```
git flow feature start 'nomedafeature' # Criando a feature

git flow feature finish 'nomedafeature' # Finalizando a feature
```
3. Criando e finalizando um Release
```
git flow release start 'geralmentenumerodaversão'

git flow release finish 'geralmentenumerodaversão'
```
4. Realizando um hotfix
```
git flow hotfix start 'nomedohotfix'

git flow hotfix finish 'nomedohotfix'
```


