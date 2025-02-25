# HTML

## Was ist HTML?

- HTML (**H**yper**T**ext **M**arkup **L**anguange) ist eine Sprache, mit der du Sachen notieren und "markieren" kannst.
- Sie ist _keine_ Programmiersprache!!! (Wo ist das Programm?)
- Sie hilft dir, Dokumente strukturiert und geordnet zu gestalten. 
- Auf ihr basiert _fast_ das ganze Internet!

## Wie verwende ich HTML?

- Als erstes brauchst du den passenden Text-Editor. 
    - z.B. [Visual Studio Code](https://code.visualstudio.com/) von Microsoft
    - Theoretisch geht auch der normale Text-Editor
- Erstelle einen neuen Ordner `/intro-code` im Root dieses Projekts (Root ist `HTML-intro`)
- Erstelle eine Datei mit dem Namen `index.html` im Ordner `/intro-code`
- Füge folgenden HTML-Code in das File ein:
```
<p> Dies ist ein Paragraph! </p>
```
- Speichere deine Änderungen mit [CTRL + S]
- Öffne das File mit dem Browser
- Tadaa!

## Was sind HTML-Elemente?
In HTML-Elementen liegt der ganze Sinn von HTML.  
Sie ermöglichen die Unterteilung des Inhaltes.

- Sie haben meistens einen **öffnenden** "Tag" (z.B. `<p>`)
- ... oft einen Text oder weitere HTML-Elemente dazwischen
- ... und einen **schliessenden** Tag (z.B. `</p>`). Das `/` signalisiert das Ende.

> Es gibt noch eine **dritte** Variante, bei der man keinen Text oder weitere Elemente einfügen kann.  
> Ein Beispiel für ein solches Element wäre der "Line-Break", der wie folgt aussieht: `<br/>`  
> Bei diesen steht das `/` rechts am Ende, um zu signalisieren, dass das HTML-Element endet.


### Die wichtigsten Elemente:

| Element-Name | Beispiel | Beschreibung |
| ------------ | ---- | ------------ |
| Division | `<div> </div>` | Elemente unterteilen |
| Paragraph | `<p> Text </p>` | Texte strukturieren |
| Line-Break | `<br/>` | (= 1 mal Enter drücken) |
| Heading 1 | `<h1> Überschchrift </h1>` | Überschrift 1 |
| Heading 2 | `<h2> Überschchrift </h2>` | Überschrift 2 |
| List | `<ul> <li></li> </ul>` | Liste (mit Listen-Items drin) |
| List Item | `<li> Dies ist ein list item </li>` | - Punkt einer Liste | 

+ [Vollständige Liste der Elemente](https://www.w3schools.com/html/default.asp)