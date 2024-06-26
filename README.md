# bc-workshop-git

Dieses Repository beinhaltet eine Webseite bestehend aus Demo-Komponenten, die dazu dienen soll, den Umgang mit Git zu üben.
Im Projekt ist Tailwind ([https://tailwindcss.com/](https://tailwindcss.com/)) eingebunden. Für die Übung ist der Inhalt der Webseite egal.

Eine Übersicht über die wichtigsten Git-Kommandos zum nachschauen findest du unter [https://training.github.com/downloads/de/github-git-cheat-sheet/](https://training.github.com/downloads/de/github-git-cheat-sheet/)

## Aufgaben:

1)	Erstelle einen Fork dieses Repositorys. Achte darauf, alle Branches zu erhalten und nicht nur den Main-Branch zu übernehmen
2)	Klone deinen persönlichen Fork in einen Ordner auf deinem Rechner
3)	Passe ggf. deine Einstellungen bzgl. Name und E-Mail Adresse an (git config user.name / user.email)
4)	Lege in deinem GitHub-Projekt ein Issue an. Ggf. müssen Issues in deinem Projekt erst noch aktiviert werden.
5)	Checke den Branch develop aus
6)	Vom Branch develop ausgehend, erstelle deinen eigenen Feature-Branch
7)	Die Datei package-lock.json und die dependencies des Projekts im node_modules-Ordner werden üblicherweise nicht ins Repository mit eingebunden, da diese über npm generiert werden können. Füge eine .gitignore-Datei hinzu, die die Datei package-lock.json sowie den Ordner node_modules ausschließt, committe deine Änderungen und verlinke in der Commit-Message dein angelegtes Issue
8)	Entferne die in der .gitignore aufgeführten Dateien aus dem Repository und committe
9)	Pushe deinen Feature-Branch auf GitHub
10)	Merge deinen Feature-Branch in den Develop-Branch indem du auf Github einen Pull-Request eröffnest. Achte darauf, dass du den develop-branch deines eigenen Repositorys auswählst!
11)	Jetzt soll der Develop-Branch in main gemerged werden, um ein Release zu veröffentlichen. In der Zwischenzeit ist jedoch ein Hotfix für einen Bug veröffentlicht worden.
-	Eröffne einen Pull Request, um den Develop-Branch in den Main-Branch zu mergen. Du wirst hier Konflikte feststellen. Löse diese, sodass die Änderungen in features.html aus dem Main-Branch übernommen werden und in index.html aus dem develop-Branch.
-	Sobald alle Merge-Konflikte behoben sind, schließe den Pull-Request ab.


## Zusatz:
1)	Erstelle jetzt ein Release mit dem aktuellen Stand mit dem Tag v1.0.0
2)	Führe lokal einen Pull aus, um die Änderungen von Github lokal zu übernehmen. Führe einen rebase deines lokalen develop-Branches auf den Stand von origin/main durch und pushe diesen erneut auf GitHub (Hier ist jetzt ein Force-Push erforderlich)
