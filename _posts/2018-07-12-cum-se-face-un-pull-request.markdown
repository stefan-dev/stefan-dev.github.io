---
layout: post
title:  "Cum se face un pull request?"
date:   2016-02-20 18:02:03
categories: jekyll update
---

     1. Ne logam pe github

     2. Clonam repozitoriul caruia vrem sa-i dam pull request cu :

git clone <url> , unde
<url> = Link-ul repozitoriului

     3. Listam fisierele si dupa aia schimbam locatia in interiorul repozitoriului 
ls
cd <repo>, unde
<repo> = repozitoriul din link

     4. Editam un fisier din repozitoriu cu un editor de text.

     5. Il adaugam pentru a ii da commit in repo :

git add <directoryurl> , unde 
<directoryurl> = locatia fisierului din calculator

     6. Fork
Pentru a ii da commit la fisier trebuie sa ii dam fork repozitoriului
din care vrem sa editam

git remote add <name> <url> , unde
<name> nume pentru clona ,
<url> Linkul repozitoriului la care am dat fork de pe contul nostru

     7. Ii dam commit si push
git commit -m <Mesaj>, unde 
<Mesaj> = Text in ghilimele pentru denumirea commit-ului si
git push <name> , pentru <name> - vezi 6

     8. Pull request
Ultimul pas este sa-i dam pull request din github, iar pentru asta trebuie
sa intram pe url-ul initial cu repozitoriul pe care am vrut sa-l editam si ii dam pull request
pentru a aplica si acolo schimbarile

