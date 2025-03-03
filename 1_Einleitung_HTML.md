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

### Wichtigsten Elemente

| Element-Name | Beispiel | Beschreibung |
| ------------ | ---- | ------------ |
| Division | `<div> Inhalt </div>` | Elemente unterteilen |
| Paragraph | `<p> Text-Inhalt </p>` | Texte strukturieren |
| Line-Break | `<br/>` | (= 1 mal Enter drücken) |
| Heading 1 | `<h1> Überschrift </h1>` | Überschrift 1 |
| Heading 2 | `<h2> Überschrift </h2>` | Überschrift 2 |
| List | `<ul> <li></li> </ul>` | Liste (mit Listen-Items drin) |
| List Item | `<li> Dies ist ein list item </li>` | - Punkt einer Liste | 
| Image | `<img src="image.png"/>` | Bild-Element mit Bildquelle | 

+ [Vollständige Liste der Elemente](https://www.w3schools.com/html/default.asp)  

~  
~  
~  
~  
~  
~  
~  
~  
~  
~  
~  
~  
~  
~  
~  
~  
~  
~  
~  
~  
~  

### Beispiele für die Anwendung *(Code und Resultat)*

#### -> Ein Div mit zwei Paragraphen und einem Line-Break dazwischen
```
<div>
    <p>Das hier ist ein Text-Paragraph</p>
    <br/>
    <p>Das hier ist ein Text-Paragraph</p>
</div>
```
> Das hier ist ein Text-Paragraph
> 
> Das hier ist ein Text-Paragraph


#### -> Eine (ungeordnete) Liste und ein Paragraph
```
<p>Folgende Sachen sind sehr wichtig:</p>
<ul>
    <li>Dies</li>
    <li>Das</li>
    <li>Jenes</li>
</ul>
```
> Folgende Sachen sind sehr wichtig:
> - Dies
> - Das
> - Jenes

#### -> Ein Bild.
```
<img src="./resources/dog.jpg">
```
> ![Hund](./resources/dog.jpg)