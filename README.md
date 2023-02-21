# HelloLWBWorld
Nur zum Testen von Github, macht was ihr wollt hier.

Anleitung zum Einrichten:

1. Github Account anlegen
2. Von Projekt-Owner hinzufügen lassen.
3. Token zum Synchronisieren generieren: Rechts oben auf das Profil -->
Settings --> links unten auf Developer Settings --> Token --> Classic --> 
generate new token
--> Das gut speichern, wird nich nochmal angezeigt. Braucht man später als
Passwort
4. Lokal einen Ordner machen 
5. Konsole: git init
6. git fetch https://github.com/phliehm/HelloLWBWorld.git		
7. git pull https://github.com/phliehm/HelloLWBWorld.git main
8. Eventuell muss jetzt noch der Username und Emailadresse gesetzt werden, 
das wird aber angezeigt wie das geht.
9. Jetzt braucht man möglicherweise das Token (irgendwo her kopieren)

Branching (eigenen Arbeitszweig aufmachen):
git branch "NeuerBranch" 	// kreiert neuen Zweig
git checkout "NeuerBranch"	// wechselt zu neuem Zweig
git add	geänderte Datei		// sagt git welche Datei man geändert hat
git commit -m "Neuer Commit lala"
git push // läd Änderungen auf den Server hoch

