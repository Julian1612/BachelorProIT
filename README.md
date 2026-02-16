# 🎓 Bachelor Professional IT - Lernkarten Sammlung

> [!CAUTION]
> # 🛑 ABSOLUTE PRIORITÄT: QUALITÄT & KI-CHECK
>
> **KI ist ein Hilfsmittel, kein Ersatz für das Gehirn! Nutze sie zur Unterstützung, aber halte dich an diese Regeln:**
>
> * 🧠 **KI ERSETZT NICHT DEIN GEHIRN:** Die KI hilft beim Strukturieren, aber das echte Verstehen musst du selbst übernehmen.
> * ⚠️ **KI HALLUZINIERT STARK:** KI-Modelle erfinden Fakten. **VERTRAUE DER KI NIEMALS BLIND!**
> * 🚫 **KEIN BLINDES KOPIEREN:** Jede generierte Karte muss vor dem Import zwingend gelesen und kritisch hinterfragt werden.
> * ✅ **MANUELLE PRÜFUNG:** Kontrolliere jede Karte auf fachliche Richtigkeit. Fehlt etwas Wichtiges?
> * ✍️ **MACHE EIGENE KARTEN:** Manuell erstellte Karten sind oft der beste Weg, um komplexe Themen wirklich zu durchdringen.
> * 🔝 **QUALITÄT VOR MASSE:** Die Richtigkeit der Inhalte steht an oberster Stelle.

---

Diese Sammlung dient dazu, Lernmaterialien für den **Bachelor Professional IT (IHK)** gemeinsam zu pflegen, Zeit zu sparen und uns gegenseitig zu unterstützen.

## 📂 Inhalt des Repositories

* **`Karteikarten/ITM/` & `Karteikarten/OuP/`**: Themenspezifische Karteikarten (CSV-Format).
* **`flashCardsTemp/`**: Das Design-Template für Anki (`front.html`, `back.html`, `style.css`).
* **`Promts/`**: 
    * `NootbookLMPromt.md`: Zusammenfassungen einzelner Themen erstellen.
    * `GoogleGemPromt.md`: Karteikarten aus Texten generieren.

---

## ⚙️ Einrichtung & Konfiguration

### 1. Anki Design (Template) einrichten
Damit das Layout funktioniert, muss der Notiztyp exakt so konfiguriert sein:

1.  **Notiztyp erstellen:** Gehe in Anki auf **Werkzeuge** -> **Notiztypen verwalten** -> **Hinzufügen**. Wähle "Einfach" und nenne ihn **`BachelorProIT`**.
2.  **Felder zwingend anpassen:** Markiere den neuen Typ `BachelorProIT` und klicke rechts auf **Felder...**. 
    * Benenne die Felder exakt so um (oder füge sie hinzu):
        1. **`Kurs`**
        2. **`Thema`**
        3. **`Frage`**
        4. **`Hinwies_1`**
        5. **`Hinwies_2`**
        6. **`Antwort`**
        7. **`Extra`**
        8. **`Real_World_Case`**
        9. **`Mnemonik`**
        10. **`MC_Richtig`**
        11. **`MC_Falsch1`**
        12. **`MC_Falsch2`**
        13. **`MC_Falsch3`**
    * *Hinweis: Ohne diese exakten Namen findet das Template die Daten nicht!*
3.  **Code einfügen:** Klicke in der Notiztypen-Verwaltung auf **Karten...** und kopiere den Code aus dem Repo:
    * Inhalt von `front.html` -> **Vorderseite**
    * Inhalt von `back.html` -> **Rückseite**
    * Inhalt von `style.css` -> **Formatierung**

### 2. Karten importieren
1. Wähle in Anki **Datei** -> **Importieren**.
2. Wähle eine CSV-Datei aus dem Repo.
3. **Wichtig:** * Trennzeichen: Pipe-Symbol (**`|`**).
    * Notiztyp: **`BachelorProIT`**.
    * Stelle sicher, dass die CSV-Spalten den Feldern korrekt zugeordnet sind.

---

## 🚀 Karten erstellen

1. **Zusammenfassen:** Nutze den Prompt aus `Promts/NootbookLMPromt.md`.
2. **Karten erstellen:** Nutze den Prompt aus `Promts/GoogleGemPromt.md`.
3. **Qualitätskontrolle:** Prüfe die Karte!

> [!IMPORTANT]
> ### 🔍 Karten Prüfen
> * **Faktencheck:** Abgleich mit Skripten. Fachbegriffe müssen exakt stimmen.
> * **Atomarität:** Eine Karte = eine klare Information. 
> * **Eindeutigkeit:** Die Frage muss ohne Raten verständlich sein.
> * **Kein Datenmüll:** Multiple-Choice oder "Ja/Nein"-Karten aussortieren, wenn sie keinen Lerneffekt haben.
> * **Format-Check:** Prüfe, ob das Pipe-Symbol (`|`) korrekt sitzt, damit der Import nicht zerschossen wird.

---

## 🤝 Mitmachen & Beitragen

Dieses Repo lebt davon, dass wir uns helfen. 
* **Committen:** Gute Karten erstellt? Lade die CSV hoch!
* **Korrigieren:** Fehler gefunden? Fix ihn direkt im Repo.
* **Optimieren:** Bessere Prompts oder Design-Ideen? Her damit!

