# IR-Gateway

Ethernet (WiFi) to IR-Code Gateway to connect normal HiFi devices to the IoT.
Firmware is a fork of https://github.com/mdhiggins/ESP8266-HTTP-IR-Blaster and modified for a special Hardware.

Versions:
0.1 - development prototype on breadboard
0.2 - flying prototype with construction parts, transmitter only, longtime-test passed
0.3 - with custom back pcb and 3D case, wip

 
Kurze Übersicht der wichtigen Git-Befehle/Workflow:

1. bevor gearbeitet wird, Arbeitskopie aktualisieren:
	git pull
	
2. am Projekt arbeiten, nicht zu viel auf einmal
	
3. Änderungen überprüfen:
	git status
	
4. alle Änderungen zum Index hinzufügen:
	git add *
	
5. anschließend Änderungen im Index einchecken, mit kurzer Beschreibung:
	git commit -m "Commit-Nachricht"
	
6. jetzt noch die Änderungen zu bitbucket hochladen:
	git push
	

Release Versionen benennen (Tagging):

1. Versionsnummer in der main.c ändern (Schema "1.0")

2. compilieren und einen commit erstellen (wie oben)

3. den commit taggen: git tag -a v1.0 -m "release of version 1.0"

4. git push und git push --tags ausführen um den Tag auf den Server zu schieben