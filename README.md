# Herzlich Willkommen bei SEW3 im SJ 2016/17!

## 0. Wichtige Links
* Sollten Fehler im bereitgestellten Material auftreten, bitte bei meinen ["GitHub Issues"](https://github.com/Javaw0cky/SEW3_SJ_2016-17/issues) eintragen
* Deine Repository: [3HIT Classroom](https://classroom.github.com/assignment-invitations/64b2a6058b562cb7d76ade57dc8e6938)
* Hilfe bekommst du hier:
	+ "Diskussionsforum zum Unterricht:" [![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/SEW3?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)
	+ [Stack Overflow](http://stackoverflow.com)

## 1. Source Code Verwaltung mit git

Arbeite folgende Links durch, um mit git bzw. GitHub vertraut zu machen:
* [git - Der einfache Einstieg](https://rogerdudler.github.io/git-guide/index.de.html)
* [git Cheat Sheet](https://rogerdudler.github.io/git-guide/files/git_cheat_sheet.pdf)
* [git für Einsteiger](https://svij.org/blog/2014/10/25/git-fur-einsteiger-teil-1/)
* [GitHub Guide](https://guides.github.com/activities/hello-world/)
* [git Reference](https://git-scm.com/docs)

### 1.1 Git in SEW
Sämtliche Programmierarbeit ist auf GitHub "abzugeben". Sofern Programmieraufgabe gestellt werden, sind diese nach Beendigung der letzten SEW Stunde an diesem Tag in die Repository zu pushen. Selbiges gilt auch für Hausübungen und Projekte.

Dazu ist es notwendig EIN Verzeichnis zu erstellen, wo ALLE IntelliJ Projekte in Unterordner enthalten sind.

Bei korrekter Konfiguration erkennt auch IntelliJ in den Unterprojekten, dass es unter GIT Kontrolle steht. Die Einstellung findest du unter "Preferences - Version Control" - hier kann das VCS root-Verzeichnis angegeben werden, d.h. das ist euer "IntelliJ"-Ordner, in dem alle Projekte enthalten sind.

### 1.2 Erstelle deine Repository
Deine persönliche Repository für dieses Schuljahr findest du hier: [3HIT Classroom](https://classroom.github.com/assignment-invitations/64b2a6058b562cb7d76ade57dc8e6938)

### 1.3 ".gitignore"
git kann mittels der Datei ".gitignore" mitgeteilt werden, welche Dateien bzw. Ordner NICHT unter git-Kontrolle stehen. Das ist natürlich sinnvoll, denn Beispielsweise .class Dateien oder IntelliJ Projekteinstellungen sollten nicht hochgeladen werden.

Daher erstelle eine Datei ".gitignore" im deinem Hauptordner (dort findest du auch einen Ornder ".git") mit folgendem Inhalt:
```
## Java
*.class
*.war
*.ear
hs_err_pid*

## Intellij
.idea/
*.ipr
*.iws
*.iml
out/
com_crashlytics_export_strings.xml

## OS Specific
.DS_Store
Thumbs.db
```

### 1.4 README.md
Lies nun bitte die Vereinbarung im nächsten Kapitel. Bestätige den Inhalt, in dem du eine Datei <b>README.md</b> mit folgendem Inhalt erstellst:
```
# SEW 3 - SJ 2xxx/xx
----
Name: Vorname Nachname
```
Damit ist es mir schneller möglich dich mit deinem richtigen Namen zu identifizieren - die Repos kommen beim clonen immer mit deinem GitHub-Usernamen an. Daraus läßt sich unter Umständen nicht schließen, von wem die Arbeit kommt.

### 2. Vereinbarung 

* Softwareentwicklung und Programmieren können nur durch regelmäßiges (wöchentliches, mind. 2-4 Stunden) Training und Üben anhand von Übungsbeispielen erlernt werden.

* Programmierbeispiele, die, sowohl im Unterricht in der Schule als auch zu Hause durchzuführen sind, sind ein wesentlicher Bestandteil, damit ich Programmieren erlernen kann.

* Nur wenn ich diese Übungen regelmäßig selbst mache, 
	+ Kann ich Programmieren erlernen und 
	+ das Fach Softwareentwicklung positiv abschließen.

* Sollte ich einmal krank sein oder aus anderen Gründen fehlen, so habe ich diese Übungen bis zur nächsten Stunde nachzuholen.

* Für alle Übungen gibt es einen Endtermin, an dem die Übungen fertiggestellt sein müssen. 

* Ich kümmere mich selbst darum, dass ich die Übungsangaben rechtzeitig bekomme. (Diese befinden sich entweder im bereitgestellten, im SEW Repository oder meinem Vorlagenlaufwerk)

* Ich bin jederzeit bereit, diese Übungen der Lehrkraft vorzuführen.

* Wenn ich inhaltlich etwas nicht verstanden habe, muss ich aktiv werden und entweder meine Mitschüler oder die Lehrkraft um Hilfe bitten.

* Ich besitze einen betriebsbereiten Laptop, der alle für die Softwareentwicklung notwendigen Programme (Entwicklungsumgebung) sowie meine sämtlichen ausprogrammierten Beispiele enthält. Ich kann diese Programme jederzeit vorführen.

* Ich bin für alle genannten Punkte selbst verantwortlich und muss mich selbstständig um deren Einhaltung kümmern!

* Ich habe alle Punkte durchgelesen und auch verstanden. 

* Auch meine Eltern haben diese Vereinbarung gelesen. 
