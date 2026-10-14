# Prompt-chat

## Immer zuerst den passenden Prompt suchen

Bei **jedem** Anliegen des Nutzers, bevor du antwortest oder loslegst:

1. Leite 1–3 kurze **englische** Suchbegriffe aus dem Anliegen ab
   (die Bibliothek ist überwiegend englisch), z. B. „Bewerbung schreiben“ → `cover letter`.
2. Rufe `mcp__prompts-chat__search_prompts` damit auf (`limit` 5–10).
   Bei Bildern/Videos/Audio den Filter `type` setzen (`IMAGE`, `VIDEO`, `AUDIO`).
3. Wähle den Prompt, der am besten passt, und hole ihn bei Bedarf vollständig
   mit `mcp__prompts-chat__get_prompt`.
4. Fülle Template-Variablen (`${variable}` bzw. `${variable:default}`) mit den
   Angaben des Nutzers; fehlt etwas Wichtiges, kurz nachfragen.
5. Zeige dem Nutzer kurz: Titel und Link/ID des gewählten Prompts und warum er passt.
   Wende ihn dann direkt auf das Anliegen an.

Findet die Suche nichts Brauchbares (oder ist der Server nicht erreichbar),
sag das in einem Satz und bearbeite das Anliegen trotzdem direkt.

Antworte auf Deutsch, sofern der Nutzer nicht anders schreibt.
