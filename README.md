# Test
Ich möchte Testen, ob ich ein lokales Projekt leicht nachträglich mit einem von Github zusammenführen kann

als Lösung wired im Internet gezeigt:

cd path/to/project-b
git remote add project-a path/to/project-a
git fetch project-a
git merge project-a/master # or whichever branch you want to merge
git remote remove project-a

Wenn ich dies entsprechend wie folgt umsetze:

 cd meinLocalerProjektOrdner
 
 
 git remote add hub https://github.com/easymf74/Test.git
 
 nun zeigt 'git remote -v':
 
 hub	https://github.com/easymf74/Test.git (fetch)
 hub	https://github.com/easymf74/Test.git (push)
 
 git fetch hub
 git merge hub/master
 
 führt zu folgender Fehlermeldung:
 fatal: Verweigere den Merge von nicht zusammenhängenden Historien.
 
Somit ist es aus mir bisher nicht verständlichen Gründen nicht möglich
die beiden Repositories zusammenzuführen, obwohl sie sich in keiner Weise überschneiden.
