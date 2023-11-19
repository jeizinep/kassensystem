# Kassensystem mit GUI für modul Einführung in die Programmierung FHNW - Pascal Jeiziner

## Installation
### Windows:
1. Installieren Sie Python von der offiziellen Webseite: https://www.python.org/downloads/
2. Laden Sie das Projekt herunter und navigieren Sie in das Projektverzeichnis.
3. Installieren Sie die benötigten Python-Pakete mit dem Befehl: pip install -r requirements.txt
4. Starten Sie das Programm mit dem Befehl: python Kassensystem.py

### Linux:
1. Installieren Sie Python mit dem Befehl: sudo apt-get install python3
2. Laden Sie das Projekt herunter und navigieren Sie in das Projektverzeichnis.
3. Installieren Sie die benötigten Python-Pakete mit dem Befehl: pip3 install -r requirements.txt
4. Starten Sie das Programm mit dem Befehl: python3 Kassensystem.py

### Docker implementation (Getestet auf WSL2, Windows nicht unterstützt)
1. Stellen Sie sicher, dass Docker auf Ihrem System installiert ist
2. Laden Sie das Projekt herunter und navigieren Sie in das Projektverzeichnis. 
3. docker build -t test . && docker run -it -e DISPLAY=:0 -v /tmp/.X11-unix:/tmp/.X11-unix test