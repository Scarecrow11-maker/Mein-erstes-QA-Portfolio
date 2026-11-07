# QA Portfolio: Testfälle für Login-Funktion

## TC-001: Erfolgreicher Login mit validen Daten
* **Beschreibung:** Überprüfen, ob sich ein registrierter Benutzer erfolgreich einloggen kann.
* **Voraussetzung:** Der Benutzer besitzt ein aktives Konto.

### Testmatrix:

| Schritt | Beschreibung | Testdaten | Erwartetes Ergebnis | Status |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Navigiere zur Login-Seite | URL der App | Login-Maske wird geladen | Pass |
| 2 | E-Mail-Adresse eingeben | `testuser@qa.com` | Feld nimmt Text an | Pass |
| 3 | Korrektes Passwort eingeben | `SicheresPasswort123!` | Zeichen werden maskiert (••••) | Pass |
| 4 | Auf "Einloggen" klicken | - | Weiterleitung zum Dashboard & Willkommensgruß | Pass |
