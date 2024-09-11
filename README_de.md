
# BlumClicker

**BlumClicker** ist ein verbessertes Tool zur Automatisierung des Sternesammelns in Blum-Spielen. Das Programm sammelt Sterne automatisch mithilfe von zufälligen Klicksequenzen und unterstützt das automatische Starten von Spielen, bis die Tickets aufgebraucht sind. Sie können auch die Option aktivieren, eingefrorene Objekte zu sammeln.

## Hauptfunktionen:
- Vollständige Automatisierung des Sternesammelns.
- Konfigurierbare Zufälligkeit der Klicks für ein natürliches Verhalten.
- Option, eingefrorene Objekte zu sammeln.
- Automatisches Scrollen und kontinuierliches Starten von Spielen, solange Tickets vorhanden sind.

## Anforderungen:
- **Python Version 3.10 oder höher**.

### 1. Installation von Python  
Laden Sie Python Version 3.10 oder höher von [python.org](https://www.python.org/) herunter und installieren Sie es. Achten Sie darauf, die Option „Add Python to PATH“ während der Installation auszuwählen.

### 2. Überprüfung der Installation  
Öffnen Sie die Eingabeaufforderung und führen Sie die folgenden Befehle aus, um sicherzustellen, dass Python und pip korrekt installiert sind:
```bash
python --version
pip --version
```

### Installation und Einrichtung – Teil 2:

### 3. BlumClicker klonen  
Laden Sie das **BlumClicker**-Projekt von GitHub herunter.

### 4. Abhängigkeiten installieren  
Navigieren Sie über die Eingabeaufforderung zum Projektordner und installieren Sie die erforderlichen Bibliotheken:
```bash
cd /Pfad/zum/Projektordner
pip install -r requirements.txt
```

### Ausführung und Einrichtung – Teil 1:

### 5. Spiel starten  
Öffnen Sie das Blum-Spiel in Telegram Desktop oder über die Web-Version von Telegram.

### 6. BlumClicker ausführen  
Führen Sie das Skript mit dem folgenden Befehl aus:
```bash
python main.py
```

### Ausführung und Einrichtung – Teil 2:

### 7. Auswahl des Spiel-Fensters  
Die Konsole zeigt eine Liste der verfügbaren Fenster an. Wählen Sie das Blum-Spiel-Fenster aus, indem Sie die entsprechende Nummer eingeben. Achten Sie darauf, das richtige Fenster auszuwählen. Beispielsweise wähle ich normalerweise das Fenster TelegramDesktop mit Blum aus.

### 8. Einstellung der Zufälligkeit  
Geben Sie einen Wert zwischen 0 und 1 ein, um den Grad der Zufälligkeit der Klicks zu steuern. Ein Wert von 1 bedeutet, dass alle Sterne gesammelt werden, während 0,6 für das Sammeln von etwa 140–150 Sternen geeignet ist. Ich empfehle, den Wert 0,9 zu verwenden, um die effizienteste Sammlung zu gewährleisten.

### 9. AutoClicker ausführen  
Nachdem das Minispiel gestartet wurde, drücken Sie ***F6***, um zu beginnen (Erklärung: Öffnen Sie BLUM, starten Sie das Spiel jedoch noch nicht, und nachdem Sie das Fenster in der Konsole ausgewählt haben, drücken Sie ***F6***. Wenn Sie einen Laptop verwenden, drücken Sie ***FN+F6***. Der AutoClicker sollte die Play-Taste finden und das Spiel starten).

### P.S.  
Laden Sie den Ordner mit den Bildern herunter und entpacken Sie ihn in einen Ordner – Sie sollten zwei Dateien im Ordner haben (main.py und requirements.txt) sowie einen Ordner namens template_png.
