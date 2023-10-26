# Rappel Git/GitHub

Savoir sur quelle branche on est :

```bash
$ git branch
* main
$
```

Savoir s’il y a des modification à _commiter_ :

```bash
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
	modified:   index.html

no changes added to commit (use "git add" and/or "git commit -a")
$
```

Pour faire un _commit_ et l’envoyer sur GitHub :

1. Ajouter tous les fichiers au _commit_ :
   ```bash
   $ git add .
   ```
1. rédiger le message du _commit_ puis faire le commit:
   ```bash
   $ git commit -m "Add comments"
   ```
1. _push_ le _commit_ vers GitHub :
   ```bash
   $ git push origin main
   ```
