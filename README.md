# Szkolenie dla Komisji ds. Informatyzacji

1. 
```
git add Workfile 
git commit -m "Init Workfile"
```
2.
```
git commit -a -m "Add Element 2."
```
3.
```
git commit -a -m "Add Element 3."
```
4.
```
git reset --soft HEAD~1
git commit -a -m "Add Element 3."
```
5.
```
git commit -a -m "Maly refactor stazysty"
```
6.
```
git reset --hard HEAD~1
git push
```
7.
```
git commit -a -m "Add Element 4."
git push
```
8.
```
git commit -a -m "Fix Element 4."
git rebase -i HEAD~2
git push --force
```
9.
```
git checkout -b element-1-1
git commit -a -m "Update Element 1 to 1.1"
git push
git checkout main
```
10.
```
git commit -a -m "Add Element 5."
git push
```
11.
```
git revert HEAD
git push --force
```
12.
```
git log
git push --force origin element-1-1
git checkout element-1-1
git reset --hard origin/element1-1
git cherry-pick <hash commitu ze zmianami>
git push
```
13.
```
git checkout main
git commit -a -m "Update Element 2 to 2.1"
git push
```
14.
```
git checkout element-1-1
git rebase main
git push --force
```
15.
```
git checkout main
git pull
git checkout -b element-3-2-and-5
git commit -a -m "Update Element 3 to 3.1 and add Element 5"
git push

```
16.
```
git checkout main
git commit -a -m "Add Element 5.1"
git push
```
17.
```
git checkout element-3-2-and-5
git rebase main
<tu powinien wystąpić merge conflict>
git push --force
```
18. Dodać coś do node_modules, wcześniej usuwając .gitignore
19. Tokeny i klucze w repozytorium
20. HTTP a SSH

