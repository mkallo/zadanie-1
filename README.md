# Zadanie

Vytvorte jednoduchú .NET aplikáciu, ktorá:
* bude slúžiť na evidenciu používateľov
* bude poskytovať funkcie na:
  * zobrazenie zoznamu používateľov
  * pridanie nového používateľa
  * zobrazenie detailu používateľa
  * aktualizácia údajov používateľa
  * vymazanie používateľa
* bude evidovať nasledujúce údaje o používateľoch:
  * meno
  * priezvisko (povinné)
  * email
  * login (povinné)
  * heslo (povinné)
* bude ukladať údaje do databázy v Microsoft SQL Server (môže byť LocalDB edícia) s využitím ORM (ideálne Entity Framework)
* bude mať webové rozhranie (ideálne ASP.NET MVC)

Pokyny k riešeniu:
* vytvorte si Git repozitár na https://github.com/
  * môže byť aj privátny, ale je potom potrebné do Collaborators pridať miroslav.kallo@alanata.sk
* zmeny commitujte postupne, nie ako jeden veľký commit na konci
* voliteľné: namiesto code-first approach použite database first approach a definíciu databázovej schémy priložte do repozitára ako sadu SQL skriptov alebo ako Visual Studio SQL Server Database Project
* voliteľné: vytvorte aplikáciu tak, aby bežala v Docker kontajneri
* odošlite odkaz na GitHub repozitár obsahujúci Vaše riešenie na adresy miroslav.kallo@alanata.sk a daniela.karabinosova@alanata.sk
