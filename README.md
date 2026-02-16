🎓 Bachelor Professional IT - Lernkarten Sammlung
=================================================

Dieses Repository ist eine einfache Sammlung von Lernmaterialien für den **Bachelor Professional IT (IHK)**. Die Idee dahinter: Wir teilen unsere Karteikarten und Workflows, damit nicht jeder das Rad neu erfinden muss und wir alle Zeit und Energie sparen.

Es geht hier nicht um Masse, sondern um Qualität. Ziel ist es, gezielt wichtige Themen aufzubereiten, anstatt einfach nur ganze Skripte zu kopieren.

📂 Was findest du hier?
-----------------------

-   **`ITM/` & `OuP/`**: Themenspezifische Karteikarten (CSV-Format), die du direkt in Anki importieren kannst.

-   **`flashCardsTemp/`**: Ein einfaches HTML/CSS-Design, damit die Karten in Anki sauber und einheitlich aussehen.

-   **`Promts/`**:

    -   `NootbookLMPromt.md`: Um gezielt Zusammenfassungen von einzelnen Themen aus Skripten zu erstellen.

    -   `GoogleGemPromt.md`: Um aus diesen Infos hochwertige Karteikarten im richtigen Format zu generieren.

* * * * *

⚙️ So stellst du alles ein
--------------------------

### 1\. Anki Design (Template)

Damit das Layout passt, musst du den Notiztyp in Anki einmalig anlegen:

1.  Gehe in Anki auf **Werkzeuge** -> **Notiztypen verwalten** -> **Hinzufügen**.

2.  Wähle "Einfach" und nenne ihn z.B. `BachelorProIT`.

3.  Klicke auf **Karten...** und kopiere die Inhalte aus dem Ordner `flashCardsTemp/` in die Felder:

    -   `front.html` -> **Vorderseite**

    -   `back.html` -> **Rückseite**

    -   `style.css` -> **Formatierung**

### 2\. Karten importieren

1.  Klicke in Anki auf **Datei** -> **Importieren**.

2.  Wähle eine CSV-Datei aus dem Repo aus.

3.  Wichtig: Wähle als Trennzeichen das Pipe-Symbol (`|`) und nutze den oben erstellen Notiztyp `BachelorProIT`.

* * * * *

🚀 Der Workflow: Qualität statt Masse
-------------------------------------

Wir nutzen KI, um gezielt Themen zu erarbeiten, nicht um blind Texte zu kopieren.

1.  **Thema wählen:** Such dir ein Thema aus dem Skript, das wirklich wichtig ist.

2.  **Zusammenfassen:** Mit dem Prompt aus `Promts/NootbookLMPromt.md` erstellst du in NotebookLM eine kurze, knackige Zusammenfassung des Themas.

3.  **Karten erstellen:** Den Text kopierst du zusammen mit dem Prompt aus `Promts/GoogleGemPromt.md` in Google Gemini. Du erhältst fertige Karten für den Import.

4.  **Check:** Kurz drüberschauen, ob alles passt, und ab in Anki.

* * * * *

🤝 Mitmachen
------------

Das Ganze funktioniert am besten, wenn wir uns gegenseitig unterstützen. Wenn du für ein Thema gute Karten erstellt hast, lade sie hier hoch.

-   **Korrigieren:** Fehler gefunden? Einfach korrigieren und commiten.

-   **Erweitern:** Neue Themen-CSVs hinzufügen.

-   **Verbessern:** Wenn du die Prompts oder das Design optimiert hast, lass es alle wissen.

Wenn alle mitmachen, haben wir am Ende eine top Vorbereitung für die Prüfung und sparen uns das nervige Abtippen. Viel Erfolg beim Lernen!