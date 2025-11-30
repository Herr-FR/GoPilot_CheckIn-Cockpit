# GoPilot_CheckIn-Cockpit

🧭 Lern-Check-In & Reflexionsbogen

Ein interaktives, browser-basiertes Tool zur Unterstützung von Lerncoachings und Reflexionsgesprächen zwischen Lehrkräften und Schülern. Diese "Single-Page-Application" (SPA) ersetzt klassische Papierbögen durch eine dynamische, visuelle Oberfläche.

✨ Funktionen

Der Bogen führt in 5 Schritten durch das Reflexionsgespräch:

1. Status Quo: Interaktive Schieberegler für Energie-Level ("Lern-Akku") und Motivation sowie Auswahl aktueller Gefühle.

2. Rückblick: Erfassung von Erfolgserlebnissen ("High Five") und Hürden inkl. Ursachenanalyse.

3. Strategie: Checkliste genutzter Lernmethoden und Selbsteinschätzung der kognitiven Tiefe (Bulimie-Lernen vs. Verstehen).

4. Der Plan: Konkrete Maßnahmenableitung nach der "Start / Stop / Continue"-Methode, inklusive eines freien Notizfeldes und Hauptziels.

5. Cockpit (Auswertung): Automatisch generierte Zusammenfassung mit einem Radar-Diagramm (Balance-Check) und allen Texteingaben, optimiert für den Ausdruck oder Export als PDF.

🚀 Nutzung

Voraussetzungen

- Ein Gerät mit einem modernen Webbrowser (Tablet, Laptop, PC oder Smartphone).

- Eine aktive Internetverbindung (für das Laden der Design- und Diagramm-Bibliotheken).

Starten der Anwendung

1. Lade die Datei Reflexionsbogen_App.html herunter.

2. Öffne die Datei per Doppelklick (oder Rechtsklick -> Öffnen mit...) in deinem Standard-Browser (Chrome, Safari, Edge, Firefox).

3. Die App ist sofort einsatzbereit.

Drucken / PDF Speichern

1. Am Ende des Gesprächs kann im Reiter "Cockpit" der Button "🖨️ Drucken / PDF" geklickt werden.

2. Wähle im Druckdialog unter "Ziel" die Option "Als PDF speichern", um das Ergebnis digital zu archivieren.

3. Das Layout ist so optimiert, dass unnötige Elemente (Navigation, Footer) beim Druck ausgeblendet werden.

🔒 Datenschutz & Technik

Wichtiger Hinweis für den schulischen Einsatz:

1. Keine Datenspeicherung: Diese Anwendung besitzt keine Datenbank und sendet keine Daten an einen Server.

2. Session-basiert: Alle Eingaben existieren nur temporär im Arbeitsspeicher des Browsers. Sobald der Tab geschlossen oder die Seite neu geladen wird, sind alle Daten gelöscht.

3. Sicherheit: Da die Daten das Gerät des Nutzers nie verlassen, ist das Tool datenschutzrechtlich unbedenklich (Client-Side Only).

Verwendete Technologien

- HTML5 / JavaScript: Basis-Struktur und Logik.

- Tailwind CSS (via CDN): Für das moderne, responsive Design.

- Chart.js (via CDN): Für das Radar-Diagramm im Cockpit.

🛠️ Anpassung (Für Fortgeschrittene)

Da der gesamte Code in einer einzigen Datei liegt, können Anpassungen leicht vorgenommen werden. Öffne die .html Datei in einem Texteditor (z.B. Notepad++, VS Code).

- Fragen/Texte ändern: Suche einfach nach dem entsprechenden Text im Code und ersetze ihn.

- Auswahlmöglichkeiten ändern: Im JavaScript-Bereich (unten in der Datei) findest du das Objekt config. Dort kannst du Listen wie hurdleCauses oder strategies anpassen.

// Beispiel: Neue Strategie hinzufügen
strategies: [
    { id: 'summary', label: '📝 Zusammenfassung' },
    // ...
    { id: 'new_item', label: '🎧 Podcast hören' } // Neu hinzugefügt
]


📄 Lizenz

Frei zur Nutzung im Bildungskontext.

Eine kommerzielle Nutzung oder Weiterverbreitung bedarf der Zustimmung des Autors.

