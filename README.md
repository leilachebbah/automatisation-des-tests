# automatisation-des-tests
toutes les démarches pour pouvoir faire de l’automatisation des tests

JAVA

telecharger et installer JDK et JRE (java)

telecharger et installer la derniere version de JAVA (on dois retrouver le fichier java dans c:/program files/java) pour ne pas avoir de probleme de librairie par la suite https://www.oracle.com/technetwork/java/javase/downloads/jdk13-downloads-5672538.html

ECLIPSE

installation d'eclipse IDE for j2EE developers: https://www.eclipse.org/downloads/

telechargement de: chromedriver.exe ou (firefoxdriver.exe & gickodriver.exe) suivant avec quel navigateur vous allez tester et l'ajouter dans eclipse 
https://github.com/mozilla/geckodriver/releases/tag/v0.26.0
https://www.softwaretestinghelp.com/geckodriver-selenium-tutorial/

SELENIUM

installation de selenium : https://www.seleniumhq.org/download/

telechargement les dernieres versions de selenium-server-standalone & selenium-server.zip voir les videos pour les ajouter dans ecplise:
https://www.youtube.com/watch?v=5FUdrBq-WFo&list=PL9ooVrP1hQOFP9H8Y15DVGCA6GavhgJ8a&index=1 à visioner a partir de 1:45

TestNG

TestNG permet d'avoir un rapport de tests, c'est plus lisible de voir une liste avec les tests OK et KO,
pour l'installation de TestNG il y a plusieus methodes, celle qui a fonctionner pour moi c'est celle ci (voir la video: https://www.youtube.com/watch?v=yyUyi8s42dE )

Depuis decembre 2019 le lien: http://beust.com/eclipse-beta n'es plus accessible, le lien utilisé actuellement pour installer TestNG sur eclipse 2019 est http://dl.bintray.com/testng-team/testng-eclipse/ 

Ce lien contient le fichier jar complet pour testng: http://www.java2s.com/Code/Jar/t/Downloadtestng685jar.htm

SIKULI

eclipse et selenium ne permettent pas de faire des tests en utilisant des images, mais c'est possible en ajoutant sikuli:
telecharger sikuli-setup.jar au moment de l'installation preciser java > next> next...>next
il y aura un fichier de crée sikuli-java.jar
pour plus d'explications voir la video suivante https://www.youtube.com/watch?v=_sWcXaic-bw&list=PL9ooVrP1hQOFP9H8Y15DVGCA6GavhgJ8a&index=15 

en plus:

Selenium Grid

il y a un outil qui permet de faire les tests simultanement et sur plusieurs machines a la fois, selenium Grid, voir le lien :
https://github.com/SeleniumHQ/selenium/wiki/Grid2

Selenium RC
permet de faire des tests sur plusieurs navigateurs au meme temps.en utilisant un (Remote Control Server)

comment generer une cle ssh sur eclips 
https://shanemcd.org/2019/01/06/creating-ssh-keys-in-eclipse-on-windows-10/

pour telecharger geckodriver (wendriver de firefox :https://github.com/mozilla/geckodriver/releases/tag/v0.26.0
