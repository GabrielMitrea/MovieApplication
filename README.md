# MovieApplication

Deorece urmaresc multe filme/seriale, m-am gandit la o aplicatie in aceasta zona. Aceasta  va fi o aplicatie care stocheaza informatie despre filmele de urmarit/placute/ce urmeaza. Aceasta aplicatie va putea:  stoca informatie despre un anumit film/serial,  va include functie de search si edit/delete/details atunci cand esti logat, totodata avand imagine/poster la fiecare film/serial si un link catre trailer-ul acestora.


Baza de date a aplicatiei va contine : Id-ul filmului/serialului, titlul, directorul, data de lansare, rating-ul, un scurt rezumat, durata, genul filmului, iar in plus pentru seriale am putea adauga numarul de sezoane/episoade etc. 


## Database Diagram Schema

![diag](https://user-images.githubusercontent.com/61286589/85062853-e9ea5e00-b1b1-11ea-8fa2-fee80c195d0c.png)



In aceasta aplicatie am folsit urmatoarele tabele in baza de date:

* Users
* Films
* Serialss
* ComingSoon
* Genres
* DivertismentTypes

Deoarece Genul, tipul de divertisment si user-ul le folosim la mai multe tabele, am creat cate o cheie straina pentru Gen, Tipul de divertisment si user.
