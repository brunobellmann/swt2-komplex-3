# swt2-komplex-3

##Aufgabe 3:
Überführung in Maven Projekt gemäß der Dokumentation:
https://www.jetbrains.com/help/idea/convert-a-regular-project-into-a-maven-project.html

manifest file muss manuell erstellt werden?


##Aufgabe 4:
Konfiguration gemäß Dokumentation:
https://www.jetbrains.com/help/idea/junit.html

Änderungen an pom.xml --> Einfügen der Dependency für jUnit 5

##Aufgabe 5:
prüfen beide Run-Code auf Testcodeabdeckung


##Fehler:
- Semikolon auf Zeile 34
- hasNext prüft auf current und nicht auf next Zeile 54
- Erster Aufruf von Iter.next() gibt nun tatsächlich das erste Element zurück
