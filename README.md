Ladet euch hier Github Desktop herunter (für Windows und Mac): https://desktop.github.com/download/

Wenn irgendwelche Fragen aufkommen, sprecht mich gerne an.


So benutzt du Github Desktop:

Ladet euch hier Github Desktop herunter (für Windows und Mac): https://desktop.github.com/download/

Wenn irgendwelche Fragen aufkommen, sprecht mich gerne an.


So benutzt du Github Desktop:

1. Das Repository "AD_ExitGame" hinzufügen:

- Öffne Github Desktop, drücke oben links auf "File" -> "Clone Repository" -> "Url" -> Gebt dort folgendes ein: github.com/kreitzm02/AD_ExitGame
- Wählt im selben Fenster aus, wo das Repository auf eurem Gerät gespeichert werden soll.
- Nun kannst du oben links "Current Repository" auswählen und im Dropdown AD_ExitGame auswählen.

 
   
3. Das Repository zum Arbeiten am Projekt vorbereiten:

- Rechts neben dem Current-Repository Dropdown ist ein Dropdown "Current Branch". Bitte wähle dort unbedingt den Branch aus, der zu deinem Fachbereich passt.
- Das ist wichtig, da du von dem dort ausgewählten Branch die Dateien auf dein Gerät herunterladen und später wieder hochladen wirst.
- Drücke in derselben Leiste oben auf "Fetch Origin". Es wird jetzt nach Änderungen im Branch gesucht, die noch nicht auf deinem Gerät vorhanden sind.
- Jetzt sollte dort "Pull Origin" stehen. Jetzt wird der aktuelle Branch auf dein Gerät geladen. Der Branch wird das Unreal-Engine-Projekt enthalten.
- Du kannst das Projekt jetzt mit der Unreal Engine öffnen. Wenn du Änderungen am Projekt vornimmst (z.B. hinzufügen neuer Assets), dann wirst du das in Github Desktop auf der linken Seite sehen unter "Changes".



3. Workflow mit Github-Desktop

- Wenn du anfängst Änderungen an dem Projekt vorzunehmen, drücke jedes mal "Fetch Origin" und dann "Pull Origin". Dies sorgt dafür, das dein lokaler Branch mit dem "Online"-Branch synchronisiert wird.
- Wenn du fertig mit deinen Änderungen bist, dann öffne wieder Github-Desktop und überprüfe unter "Changes", ob deine Änderungen registriert wurden.
- Fülle unter Changes "Summary" und "Description" aus. Beschreibe hier grob, was du gemacht hast.
- Drücke danach auf den darunterliegenden blauen Button "Commit X files to (Branch Name)".
- Nachdem der Commit abgeschlossen ist, wird deine Changes-Liste wieder leer sein.
- Drücke dann oben in der Leiste auf "Push origin". (der Button befindet sich dort, wo sonst der Fetch origin Button wäre).
- Wenn der Push abgeschlossen ist, befinden sich deine Änderungen nun auf dem jeweiligen Branch im Online-Repository.



4. Deine Änderungen aus deinem Branch auf den Main-Branch bringen

- Der Main-Branch ist der "Release" Branch und ist besonders geschützt.
- Direkte Commits auf den Main-Branch sind nicht möglich, dies wird im Repository blockiert.
- Um die Änderungen deines Branches auf den Main Branch zu bringen, befolge die folgenden Schritte:
- Gehe über deinen Browser auf das Repository github.com/kreitzm02/AD_ExitGame . Gehe oben links in der Leiste auf "Code".
- Wähle im Dropdown Menü deinen Branch aus. Unter dem Dropdown wird ein blauer Text erscheinen: "This branch is X commits ahead of main"
- Drücke auf den anklickbaren Teil des Textes (blauer Text)
- Jetzt erscheint die "Comparing Changes"-Seite. Überprüfe ob in der Leiste mit dem grünen Text "Able to merge" folgende Branches ausgewählt sind: base:main --- compare:DeinBranchName
- Unter dieser Leiste ist eine blaue Box mit einem grünen Button "Create Pull Request".
- Dort können Titel und Beschreibung des Pull Requests eingegeben werden. Drücke reneut auf "Create pull request".
- Jetzt werdet ihr sehen, das Github den Pull Request vorerst blockiert, da ein anderer User den Pull Request bestätigen muss. Andere User können diesen Pull Request jetzt auch sehen unter "Pull Requests" in der oberen Leiste, wo auch "Code" ist und können dort bestätigen.
- Wenn bestätigt wird, dann kannst du den Pull Request ausführen und deine Änderungen landen im main-Branch.


5. Den aktuellen Stand aus dem Main Branch auf deinen persönlichen Branch bringen

- Dies funktioniert genauso wie Punkt 4, nur anders herum.
- Gehe über deinen Browser auf das Repository github.com/kreitzm02/AD_ExitGame . Gehe oben links in der Leiste auf "Code".
- Wähle im Dropdown Menü deinen Branch aus. Unter dem Dropdown wird ein blauer Text erscheinen: "This branch is X commits behind main"
- Drücke auf den anklickbaren Teil des Textes (blauer Text)
- Jetzt erscheint die "Comparing Changes"-Seite. Überprüfe ob in der Leiste mit dem grünen Text "Able to merge" folgende Branches ausgewählt sind: base:DeinBranchName --- compare:main
- Unter dieser Leiste ist eine blaue Box mit einem grünen Button "Create Pull Request".
- Dort können Titel und Beschreibung des Pull Requests eingegeben werden. Drücke reneut auf "Create pull request".
- Jetzt werdet ihr sehen, das Github den Pull Request vorerst blockiert, da ein anderer User den Pull Request bestätigen muss. Andere User können diesen Pull Request jetzt auch sehen unter "Pull Requests" in der oberen Leiste, wo auch "Code" ist und können dort bestätigen.
- Wenn bestätigt wird, dann kannst du den Pull Request ausführen und das Projekt aus dem main-Branch landet nun in deinem persönlichen Branch. Führe nun Schritt 3 aus, um diese Änderungen mit Github Desktop auf dein lokales Gerät zu bringen.


