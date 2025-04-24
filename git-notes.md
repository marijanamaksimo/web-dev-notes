ovo će biti GIT guide za sve što je važno znati o GIT-u

| Komanda                        | Objašnjenje                                               |
|---------------------------------|-----------------------------------------------------------|
| `git init`                      | Kreira novi Git repozitorijum                             |
| `git clone <url>`               | Preuzima (klonira) repozitorijum sa udaljenog servera     |
| `git status`                    | Prikazuje status fajlova (da li su izmenjeni, dodati...) |
| `git add <fajl>`                | Dodaje fajl u staging (pripremu za commit)                |
| `git commit -m "poruka"`        | Snima promene sa porukom                                  |
| `git log`                       | Prikazuje istoriju commit-ova                             |
| `git diff`                      | Prikazuje razlike između fajlova                         |
| `git branch`                    | Prikazuje sve lokalne branch-eve                          |
| `git checkout <branch>`         | Prelazi na drugi branch                                  |
| `git checkout -b <novi-branch>` | Pravi novi branch i odmah prelazi na njega                |
| `git merge <branch>`            | Spaja <branch> u trenutni branch                          |
| `git pull`                      | Povlači promene sa udaljenog repozitorijuma               |
| `git push`                      | Šalje lokalne promene na udaljeni repozitorijum           |
| `git remote -v`                 | Prikazuje povezane udaljene repozitorijume i njihove URL-ove |
| `git reset --hard master`       | Vraća trenutni branch na stanje koje je na `master` branch-u, gubi sve lokalne promene |
| `git fetch --all`               | Preuzima sve promene sa svih udaljenih repozitorijuma bez spajanja sa lokalnim radnim direktorijumom |
| `git new`                       | Kreira novi Git repozitorijum (nije standardna komanda, može biti alias ili skripta) |
| `git start`                     | Pokreće novi Git repozitorijum ili inicijalizuje rad sa novim projektom (može biti alias ili skripta) |
| `git add -A`                    | Dodaje sve izmenjene fajlove (dodate, izbrisane ili promenjene) u staging |
| `git commit --fix`              | Popravlja prethodni commit (nije standardna komanda, može biti alias ili skripta) |
| `git commit --quickfix`         | Brzo rešava greške i pravi commit (nije standardna komanda, može biti alias ili skripta) |
| `git commit --modify`           | Modifikuje prethodni commit (nije standardna komanda, može biti alias ili skripta) |
| `git commit --amend`            | Menja poslednji commit (dodaje ili menja poruku, ili menja sadržaj) |
