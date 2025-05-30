# LiascriptTutorial

Ich lerne hier viel

![Fellow-Logo](Fellow_Icon_Schrift-unten.png)

'Abb: Fellwoships im Rahmen des Projekt Digitalisierung der Hochschulbildung in Sachsen (DHS)'

## Schritt 1: Markdown-Datei in GitLab erstellen

Damit Kurs in Liascript angezeigt werden kann: 

- Link zur Raw-Datei kopieren und bei https://liascript.github.io/ eingeben

Um die Markdown Datei leichter bearbeiten zu können, github.dev als Editor nutzen. Dort gibt es Liascript Plugins, z. B. um eine Preview anzeigen zu können. (Hinweis: Datei muss erst committed werden, damit das Verzeichnis aktualisiert wird).
Im Dev-Modus lassen sich auch workflows zur Qualitätskontrolle implementieren. Hierfür neuen Ordner anlegen github mit Unterordner Workflows: dort werden *.yaml-Datein abgelegt (z. B. spellcheck, siehe https://liascript.github.io/blog/quality-checks-on-liascript-with-github-ensuring-document-excellence/)

PDF to Markdown oder Word to Markdown  verwenden, um Dokumente aus Word oder PDF in Markdwon abzuspeichern

### Hausaufgabe
Ein Dokument von uns in Markdown umsetzen

### Markdown Sprache

Bilder einfügen `![Alt-Text](media/Dateiname.png)`

Audio einfügen `?[Alt-Text] (media/Dateiname.mp3)`

Video einfügen `!?[Alt-Text] (media/Dateiname.mov)`

Sprachausgabe hinzufügen: `{{|>}}`

Liascript-Hilfe: https://liascript.github.io/course/?https://raw.githubusercontent.com/liaScript/docs/master/README.md#1

### Workflows umsetzen
1) Im Dev-Modus neues Unterverzeichnis anlegen (so wie media) .github/workflows
2) Workflow-Code aus Blogbeitrag (https://liascript.github.io/blog/automating-liascript-transformations-on-github/) kopieren. In neue Datei deploy.yml einfügen. Änderungen hinzufügen.
