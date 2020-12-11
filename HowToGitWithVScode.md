# How to git with VS Code

Am besten klappt bisher der folgende Workflow:

## Ausgang: es gibt bereits ein repository in Github

Dann ist in der Regel auf local ein _directory_ erstellt worden, das bei _Github_ initialisiert wurde.

+ Da in _iterm_ mit _cd_ reingehen 
+ und über den Befehl `code . ` _VS Code_ aufrufen, da sollte dann schon im Terminal links der _grüne Master_ zu sehen sein.
+ nach den Änderungen, die auch 
  + Änderungen an einer Datei
  + Anlegen einer neuen Datei
  umfassen können (Speichern nicht vergessen), dann das Ausführen der folgenden _Git_-Befehle
    + `git status`
      + checkt, wo es Änderungen gab
    + `git add --all`
      + bringt alle geänderten Files in den _stage_-Bereich
    + `git commit -m 'commit Text'`
      + manifestiert die Änderungen
    + `git push --all`
      + pushed die Files aus dem _stage_-Bereich in das **Github**-Repository
  
Das ist bisher geprüft, indem zuerst in das **Github**-Repository eingeloggt wurde und dann im Terminal in den entsprechenden Git.local cd`d wurde.

Noch zu prüfen ist, was passiert, wenn man sich nicht zuerst in das **Github**-Repository eingeloggt, sonder zuerst in Git.local geht, die Änderungen vornimmt und dann in das **Github**-Repository `pushed`.

