+++ 
title = 'Host di un sito web'
date = "2020-03-22"
slug = 'Host' 
image = 'images/post10/post10.png' 
description = ''
disableComments = false
+++

Per effettuare l'host di un sito internet utilizzeremo due servizi, github e netlify, e tramite semplici operazioni saremo in grado di mettere online il proprio sito.

Creare un account Github
-------------

Il primo step per hostare il proprio sito online è creare un account github su [github.com](https://github.com/)
<div align="center">
<a class="image main" href="https://res.cloudinary.com/maltob03/image/upload/v1584891166/post10/1_jgp2x2.jpg" data-lightbox="post2"><img class="image main" src="https://res.cloudinary.com/maltob03/image/upload/v1584891166/post10/1_jgp2x2.jpg" alt="" width="" height="" /></a>


Creazione di una repository
--------------
Una volta creato un account il primo passo è creare una repository (un contenitore dove inserire i file).Cliccando su start a project nella finestra che si apre basterà inserire il nome della repository nella casella repository name ed infine cliccare su create repository. Ora abbiamo una repository nella quale dobbiamo caricare i nostri file 

<div align="center">
<a class="image main" href="https://res.cloudinary.com/maltob03/image/upload/v1584891166/post10/2_jytbmz.jpg" data-lightbox="post2"><img class="image main" src="https://res.cloudinary.com/maltob03/image/upload/v1584891166/post10/2_jytbmz.jpg" alt="" width="" height="" /></a>
</div>


<div align="center">
<a class="image main" href="https://res.cloudinary.com/maltob03/image/upload/v1584891166/post10/3_bjfknj.jpg" data-lightbox="post2"><img class="image main" src="https://res.cloudinary.com/maltob03/image/upload/v1584891166/post10/3_bjfknj.jpg" alt="" width="" height="" /></a>
</div>




Caricare il codice
---------------
Per caricare il codice se utilizziamo come sistema operativo windows 10 dobbiamo scaricare [gitbash](https://gitforwindows.org/).  
Una volta terminata la fase di installazione apriamo gitbash e ci troveremo dinanzi ad una finestra nera con scritte verdi in stile matrix,potrebbe essere spaventosa ma si supera facilmente il primo impatto.Ora inizia la fase principale in cui dobbiamo dare una serie di comandi:  

cd desktop (questo fa si che la cartella si creerà sul desktop)  
git clone (tra parentesi dovete inserire l'url del vostro repository)  
ora sul desktop dovrebbe essere comparsa una cartella vuota con il nome della vostra repository.Inserite all'interno i file del vostro sito  
cd (nome cartella)  
git add *  
git commit -m "first commit"  
git push origin master  
Inserire la mail  
Inserire la passsword  
Ora se tutto è stato fatto correttamente aggiornando la pagina della repository dovreste vedere tutti i file 
(dovrste avere una pagina simile a questa)
<div align="center">
<a class="image main" href="https://res.cloudinary.com/maltob03/image/upload/v1584891166/post10/4_pgoenc.jpg" data-lightbox="post2"><img class="image main" src="https://res.cloudinary.com/maltob03/image/upload/v1584891166/post10/4_pgoenc.jpg" alt="" width="" height="" /></a>
</div>



Host di un sito statico
-------------
In questa fase avviene il vero è proprio caricamento del sito in internet.Innanzitutto dobbiamo creare un'account su [netlify](https://app.netlify.com/signup?_ga=2.182359655.1154193920.1584887934-166591048.1584634381) potete usare il vostro account github per accedere o crearne uno nuovo con la mail.  
Una volta effettuata la registrazione bisognerà cliccare su new site from git.
Basterà inserire le proprie credenziali scegliere la repository che abbiamo creato precedentemente e infina click su deploy site.


<div align="center">
<a class="image main" href="https://res.cloudinary.com/maltob03/image/upload/v1584891166/post10/5_sdczd9.jpg" data-lightbox="post2"><img class="image main" src="https://res.cloudinary.com/maltob03/image/upload/v1584891166/post10/5_sdczd9.jpg" alt="" width="" height="" /></a>
</div>

Ultima fase:deploy
-----------
Questo sito si occuperà di effettuare il eseguire il codice e metterlo online. Una volta terminata la fase di sviluppo il sito hosterà il codice su un dominio in automatico (come vedete evidenziato nell'immagine sottostante) che possiamo cambiare a piacere con uno comprato.



<div align="center">
<a class="image main" href="https://res.cloudinary.com/maltob03/image/upload/v1584891166/post10/6_su2j9k.jpg" data-lightbox="post2"><img class="image main" src="https://res.cloudinary.com/maltob03/image/upload/v1584891166/post10/6_su2j9k.jpg" alt="" width="" height="" /></a>
</div>


