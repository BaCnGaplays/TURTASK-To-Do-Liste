# TURTASK – To-Do-Liste mit Ende-zu-Ende-Verschlüsselung

TURTASK ist eine deutschsprachige To-Do-Listen-Anwendung, die vollständig in einer einzigen HTML-Datei ausgeliefert wird. Der Name verbindet „turtle“ (Schildkröte) und „task“ (Aufgabe): So wie die Schildkröte ihren Panzer trägt, legt TURTASK die Aufgaben in eine schützende, verschlüsselte Hülle.

## Funktionen

- **Lokal und serverlos:** Alle Daten verbleiben ausschließlich im lokalen Speicher des Browsers. Es gibt keinen Server, kein Benutzerkonto und keine Datenübertragung.
- **Optionale Ende-zu-Ende-Verschlüsselung (256 Bit):** Beim Aktivieren der Verschlüsselung werden zwei Recovery-Codes erzeugt. Ein Recovery-Code wird bei jedem Öffnen der Anwendung abgefragt; der zweite dient als Backup, falls der erste nicht mehr zur Verfügung steht (vergleichbar mit dem Zusammenspiel von TAN und PUK).
- **Automatische Sperre:** Im Verschlüsselungsmodus sperrt sich die Anwendung nach 15 Minuten Inaktivität automatisch.
- **PIN-Schutz für Notizen:** Einzelne Notizen lassen sich zusätzlich mit einer vierstelligen PIN versehen. Dies ist ausdrücklich kein kryptografisches Sicherheitsmerkmal, sondern ein niedrigschwelliger Schutz vor flüchtigen Einblicken, etwa durch Kollegen am selben Arbeitsplatz.
- **Einzeldatei:** Die gesamte Anwendung besteht aus der Datei `index.html`.

## Verwendung

1. Repository klonen oder `index.html` herunterladen:

   ```bash
   git clone https://github.com/BaCnGaplays/TURTASK-To-Do-Liste.git
   ```

2. `index.html` in einem aktuellen Browser öffnen.
3. Optional die Verschlüsselung aktivieren und beide Recovery-Codes sicher aufbewahren.

## Wichtige Hinweise

- Die Daten liegen ausschließlich im lokalen Speicher des Browsers. Werden die Browserdaten gelöscht, ist die To-Do-Liste unwiederbringlich verloren.
- Ohne die Recovery-Codes ist kein Zugriff auf die verschlüsselten Daten möglich. Eine Wiederherstellung durch Dritte ist konstruktionsbedingt ausgeschlossen, da es keinen Server und keine Hintertür gibt. Bewahren Sie die Recovery-Codes sicher und getrennt auf.
- Die Anwendung wird ohne jegliche Gewährleistung bereitgestellt (vgl. Abschnitte 15 und 16 der Lizenz).

## Lizenz

Copyright (c) 2026 BaCnGaplays

Dieses Projekt steht unter der GNU Affero General Public License v3.0 (AGPL-3.0), siehe Datei [LICENSE](LICENSE). Die Software darf frei verwendet, untersucht, verändert und weitergegeben werden. Abgeleitete Werke müssen unter derselben Lizenz veröffentlicht werden – auch dann, wenn die Software als Web-Dienst betrieben wird. Damit bleibt TURTASK dauerhaft Open Source.

---

# TURTASK – To-Do List with End-to-End Encryption

TURTASK is a German-language to-do list application shipped as a single HTML file. The name combines “turtle” and “task”: just as a turtle carries its shell, TURTASK keeps your tasks inside a protective, encrypted shell.

## Features

- **Local and serverless:** All data stays in the browser’s local storage. There is no server, no account, and no data transmission.
- **Optional end-to-end encryption (256-bit):** When you activate encryption, two recovery codes are generated. One recovery code is requested each time the application is opened; the second one serves as a backup in case the first is no longer available (comparable to the TAN/PUK concept).
- **Automatic lock:** In encryption mode, the application locks itself automatically after 15 minutes of inactivity.
- **PIN protection for notes:** Individual notes can additionally be protected with a four-digit PIN. This is explicitly not a cryptographic security feature, but a low-threshold guard against casual snooping, for example by colleagues sharing the same workstation.
- **Single file:** The entire application consists of the file `index.html`.

## Usage

1. Clone the repository or download `index.html`:

   ```bash
   git clone https://github.com/BaCnGaplays/TURTASK-To-Do-Liste.git
   ```

2. Open `index.html` in a current browser.
3. Optionally activate encryption and keep both recovery codes in a safe place.

## Important Notes

- All data is stored exclusively in the browser’s local storage. Deleting the browser data will irretrievably delete your to-do list.
- Without the recovery codes, encrypted data cannot be accessed. Recovery by third parties is impossible by design, since there is no server and no backdoor. Store your recovery codes safely and separately.
- The application is provided without any warranty (see sections 15 and 16 of the license).

## License

Copyright (c) 2026 BaCnGaplays

This project is licensed under the GNU Affero General Public License v3.0 (AGPL-3.0); see the [LICENSE](LICENSE) file. You may use, study, modify, and redistribute the software freely. Derivative works must be released under the same license – including when the software is offered as a network service. This keeps TURTASK permanently open source.
