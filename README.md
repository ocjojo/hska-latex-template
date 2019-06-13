# LaTeX Vorlage für Arbeiten an der Hochschule Karlsruhe – Technik und Wirtschaft

Die Vorlage ist während meiner Arbeiten entstanden. Fühlt euch frei sie zu verwenden.

[Vorschau](https://github.com/ocjojo/hska-latex-template/blob/master/document.pdf)

## Verwendung

In [Overleaf](https://de.overleaf.com) Upload einer externen Datei wählen und die `hska.cls` importieren.

Lokal die `hska.cls` im Projekt Ordner ablegen.

Die Klasse erbt von [`article`](https://ctan.org/pkg/article) und verfügt über deren Optionen.

Packages, die man in meinen Augen häufig verwendet, hab ich direkt in die Klasse gepackt.

### Beispiel

```latex
% Dokument.tex
% hska Klasse benutzen
\documentclass[12pt,digital]{hska}
\begin{document}
Hallo Welt
\end{document}
```

Weiteres findet ihr im Beispiel `document.tex`. Die Kommentare könnten hilfreich sein und Google ist euer Freund.

Ihr könnt gerne das gesamte Projekt klonen und damit schreiben.

## Issues

Erstellt gerne Issues und Pull Requests, falls ihr Verbesserungsvorschläge habt oder Anpassungen vornehmt, die für alle sinnvoll sind.

## Disclaimer

Die Klasse ist keine offizielle Vorlage, da es sowas meines Wissens nach nicht gibt.
Die Nutzung erfolgt auf eigene Gefahr 😁.
