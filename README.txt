UKM GITHUB PAGES – GEPRÜFTE VERSION

Diese Version ist vollständig statisch und funktioniert direkt auf GitHub Pages.

ENTHALTEN:
- index.html
- 404.html
- .nojekyll
- .github/workflows/pages.yml
- README.txt

EMPFOHLENE VERÖFFENTLICHUNG:
1. Neues GitHub-Repository erstellen.
2. Alle Dateien aus diesem ZIP in das Repository hochladen.
3. Repository -> Settings -> Pages.
4. Unter "Build and deployment" bei "Source" auswählen:
   GitHub Actions
5. Danach einmal auf den Reiter "Actions" gehen.
   Der Workflow "Deploy GitHub Pages" startet bei einem Push auf main automatisch.
6. Nach erfolgreichem Lauf erscheint der Pages-Link unter Settings -> Pages.

URL:
Wenn dein Repository "meinname.github.io" heißt:
https://meinname.github.io/

Wenn dein Repository z.B. "UKM-Ausbildung" heißt:
https://meinname.github.io/UKM-Ausbildung/

TEST-LOGIN:
Dienstnummer: UKM-000001
Passwort: admin123

TECHNISCHE PRÜFUNG:
- JavaScript-Syntax: OK
- keine externen relativen CSS-/JS-Dateien erforderlich
- keine absoluten Pfade vorhanden
- funktioniert deshalb sowohl im Root als auch in einem Repository-Unterpfad
- .nojekyll vorhanden
- 404-Fallback vorhanden
- GitHub-Pages-Actions-Workflow vorhanden

WICHTIG:
GitHub Pages hat kein Backend. Mitarbeiterkonten, Passwörter, Ausbildungen
und Adminänderungen werden in dieser Version nur im Browser/localStorage
gespeichert. Sie ist technisch lauffähig auf GitHub Pages, aber nicht für
echte vertrauliche Mitarbeiterzugänge geeignet.
