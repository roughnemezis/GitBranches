# Dépôt pédagogique sur les branches git

## Sources:

- [Git - Branches in a Nutshell - From git-scm](https://git-scm.com/book/en/v2/Git-Branching-Branches-in-a-Nutshell)


## Actions

### Fast forward merge

Création d'une branche hotfix 

```bash
git checkout -b hotfix
# add, commit ...
git merge hotfix
```

Résultat: les branches n'ayant pas divergé, il n'y a pas de création de commit du merge,mais git avance le pointeur master sur le nouveau commit.
