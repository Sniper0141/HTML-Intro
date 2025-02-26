# CSS (Style your HTML!)

Du hast sicher gemerkt, dass dein HTML-Dokument etwas öde aussieht, im Vergleich zum Original-Artikel.
Das liegt daran, dass das CSS fehlt.

> CSS => **C**ascading **S**tyle **S**heets

## Wofür ist CSS?

Man verwendet CSS, um HTML-Dokumente besser zu gestalten.

- Öffne [unseren Onlineshop](https://www.digitec.ch)
- Öffne die DevTools deines Browsers und lösche den `<head>` des HTML-Codes (CSS muss weg zum demonstrieren)
    - Falls du nicht weisst, wie man das macht, hole einen von uns zu dir
- So sieht eine Website mit reinem HTML aus. Deswegen braucht man CSS!

## CSS anwenden

- Füge folgendes Element in den `<head>` ein:
```
<link rel="stylesheet" href="stylesheet.css">
```

- Erstelle im gleichen Ordner wie das HTML ein File namens `stylesheet.css`. 
- Kopiere folgenden Code in das File:
```
.this-is-a-class {
    text-align: center;
}
```
### Erklärung der Klasse 
>- Der `.` definiert, dass es eine Klasse ist.
>- `this-is-a-class` ist der Name der Klasse.
>- Die Klammern `{}` definieren den Anfang und das Ende des Stück CSS
>- Alles vor der Klammer `{` nennt man den "Selektor", weil damit Elemente "ausgewählt" werden
>    - In diesem Fall ist der Selektor folgender: `.this-is-a-class`
>- Die Zeile `text-align: center;` macht, dass Text zentriert wird.

