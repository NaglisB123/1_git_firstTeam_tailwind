# Steps

1. `git init` - inicializacija
2. `git add .` - prideti visus failus i staged, pazymeti sekimui su git.
3. `git commit -m "init commit"` - padarom comita

## prijungti github repo prie musu localios

4. `git remote add origin https://github.com/MariusCodeAcademy/1_git_firstTeam_tailwind.git`
5. `git branch -M main`
6. `git push -u origin main`

## branch

7. `git checkout -b development` - sukurti ir pereiti i nauja saka
8. `git push -u origin development` - publikuoki saka

## reset

9. `git reset <shacodas>` - atstadyti iki nurodyto comit (pakeitimai lieka)
10. `git reset HEAD~1` - atstadyti paskutini comita (pakeitimai lieka)
11. `git reset --hard HEAD~1` - atstadyti paskutini comita (pakeitimu nelieka)