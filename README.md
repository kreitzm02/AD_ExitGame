Ladet euch hier Github Desktop herunter (für Windows und Mac): https://desktop.github.com/download/

Wenn irgendwelche Fragen aufkommen, sprecht mich gerne an.


So benutzt du Github Desktop:

1. Das Repository "AD_ExitGame" hinzufügen:
   
  -> 1. Öffne Github Desktop, drücke oben links auf "File" -> "Clone Repository" -> "Url" -> Gebt dort folgendes ein: github.com/kreitzm02/AD_ExitGame
  
  -> 2. Wählt im selben Fenster aus, wo das Repository auf eurem Gerät gespeichert werden soll.
  
  -> 3. Nun kannst du oben links "Current Repository" auswählen und im Dropdown AD_ExitGame auswählen.
  
   
2. Das Repository zum Arbeiten am Projekt vorbereiten:
   
  -> 1. Rechts neben dem Current-Repository Dropdown ist ein Dropdown "Current Branch". Bitte wähle dort unbedingt den Branch aus, der zu deinem Fachbereich passt.
  
  -> 2. Das ist wichtig, da du von dem dort ausgewählten Branch die Dateien auf dein Gerät herunterladen und später wieder hochladen wirst.
  
  -> 3. Drücke in derselben Leiste oben auf "Fetch Origin". Es wird jetzt nach Änderungen im Branch gesucht, die noch nicht auf deinem Gerät vorhanden sind.
  
  -> 4. Jetzt sollte dort "Pull Origin" stehen. Jetzt wird der aktuelle Branch auf dein Gerät geladen. Der Branch wird das Unreal-Engine-Projekt enthalten.
  
  -> 5. Du kannst das Projekt jetzt mit der Unreal Engine öffnen. Wenn du Änderungen am Projekt vornimmst (z.B. hinzufügen neuer Assets), dann wirst du das in Github Desktop auf der linken Seite sehen unter "Changes".
  

3. Workflow mit Github-Desktop
   
  -> 1. Wenn du anfängst Änderungen an dem Projekt vorzunehmen, drücke jedes mal "Fetch Origin" und dann "Pull Origin". Dies sorgt dafür, das dein lokaler Branch mit dem "Online"-Branch synchronisiert wird.
  
  -> 2. Wenn du fertig mit deinen Änderungen bist, dann öffne wieder Github-Desktop und überprüfe unter "Changes", ob deine Änderungen registriert wurden.
  
  -> 3. Fülle unter Changes "Summary" und "Description" aus. Beschreibe hier grob, was du gemacht hast.
  
  -> 4. Drücke danach auf den darunterliegenden blauen Button "Commit X files to (Branch Name)".
  
  -> 5. Nachdem der Commit abgeschlossen ist, wird deine Changes-Liste wieder leer sein.
  
  -> 6. Drücke dann oben in der Leiste auf "Push origin". (der Button befindet sich dort, wo sonst der Fetch origin Button wäre).
  
  -> 7. Wenn der Push abgeschlossen ist, befinden sich deine Änderungen nun auf dem jeweiligen Branch im Online-Repository.
  

4. Deine Änderungen aus deinem Branch auf den Main-Branch bringen
   
   -> 1. Der Main-Branch ist der "Release" Branch und ist besonders geschützt.
   
   -> 2. Direkte Commits auf den Main-Branch sind nicht möglich, dies wird im Repository blockiert.
   
   -> 3. Um die Änderungen deines Branches auf den Main Branch zu bringen, befolge die folgenden Schritte:
   
   -> 4. Gehe über deinen Browser auf das Repository github.com/kreitzm02/AD_ExitGame . Gehe oben links in der Leiste auf "Code".

   -> 5. Wähle im Dropdown Menü deinen Branch aus. Unter dem Dropdown wird ein blauer Text erscheinen: "This branch is X commits ahead of main"

   -> 6. Drücke auf den anklickbaren Teil des Textes (blauer Text)

   -> 7. Jetzt erscheint die "Comparing Changes"-Seite. Überprüfe ob in der Leiste mit dem grünen Text "Able to merge" folgende Branches ausgewählt sind: base:main --- compare:DeinBranchName

   -> 8. Unter dieser Leiste ist eine blaue Box mit einem grünen Button "Create Pull Request".

   -> 9. Dort können Titel und Beschreibung des Pull Requests eingegeben werden. Drücke reneut auf "Create pull request".

   -> 10. Jetzt werdet ihr sehen, das Github den Pull Request vorerst blockiert, da ein anderer User den Pull Request bestätigen muss. Andere User können diesen Pull Request jetzt auch sehen unter "Pull Requests" in der oberen Leiste, wo auch "Code" ist und können dort bestätigen.

   -> 11. Wenn bestätigt wird, dann kannst du den Pull Request ausführen und deine Änderungen landen im main-Branch.


5. Den aktuellen Stand aus dem Main Branch auf deinen persönlichen Branch bringen
   
   -> 1. Dies funktioniert genauso wie Punkt 4, nur anders herum.
   
   -> 2. Gehe über deinen Browser auf das Repository github.com/kreitzm02/AD_ExitGame . Gehe oben links in der Leiste auf "Code".

   -> 3. Wähle im Dropdown Menü deinen Branch aus. Unter dem Dropdown wird ein blauer Text erscheinen: "This branch is X commits behind main"

   -> 4. Drücke auf den anklickbaren Teil des Textes (blauer Text)

   -> 5. Jetzt erscheint die "Comparing Changes"-Seite. Überprüfe ob in der Leiste mit dem grünen Text "Able to merge" folgende Branches ausgewählt sind: base:DeinBranchName --- compare:main

   -> 6. Unter dieser Leiste ist eine blaue Box mit einem grünen Button "Create Pull Request".

   -> 7. Dort können Titel und Beschreibung des Pull Requests eingegeben werden. Drücke reneut auf "Create pull request".

   -> 8. Jetzt werdet ihr sehen, das Github den Pull Request vorerst blockiert, da ein anderer User den Pull Request bestätigen muss. Andere User können diesen Pull Request jetzt auch sehen unter "Pull Requests" in der oberen Leiste, wo auch "Code" ist und können dort bestätigen.

   -> 9. Wenn bestätigt wird, dann kannst du den Pull Request ausführen und das Projekt aus dem main-Branch landet nun in deinem persönlichen Branch. Führe nun Schritt 3 aus, um diese Änderungen mit Github Desktop auf dein lokales Gerät zu bringen.


