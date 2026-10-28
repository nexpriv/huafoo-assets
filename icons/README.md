# HuaFoo Favicon-Set

Erstellt aus der bereitgestellten favicon-512x512.png (512 × 512 Pixel).
Logo, Seitenverhältnis und Markenfarben bleiben erhalten. Hintergrund #080d1c,
Schrift #a5b4fc. Die SVG-Dateien sind aus dieser PNG-Vorlage nachgezeichnete
Vektorpfade; sie ersetzen keine höher aufgelöste Original-Vektordatei.

## Einbindung

1. Die Dateien dieses Ordners auf der Website unter `/icons/` bereitstellen.
   Der lokale Speicherort P:\huafoo-assets\icons stellt allein noch keine Web-URL bereit.
2. Den Inhalt von `favicon-head.html` in den HTML-`<head>` übernehmen.
3. Bei anderer öffentlicher URL die Pfade in `favicon-head.html` und
   `browserconfig.xml` anpassen. Die Icon-Pfade in `site.webmanifest` sind relativ.
   Bei einem eigenen Manifest dessen Einstellungen beibehalten und die Icons ergänzen.
   `name`, `short_name`, `id`, `start_url`, `scope` und `display` vor Nutzung prüfen,
   insbesondere wenn die Website nicht unter `/` betrieben wird.
4. Für automatisch suchende ältere Browser zusätzlich `favicon.ico` im Website-Root
   bereitstellen oder `/favicon.ico` auf `/icons/favicon.ico` weiterleiten.
   Optional gilt dasselbe für `/apple-touch-icon.png`.
5. Browser-Cache nach dem Austausch leeren bzw. Dateiversionen verwenden.
   Ein vorhandener Content-Security-Policy-Header muss Icon- und Manifest-URLs erlauben.
   Das Manifest allein macht die Website nicht automatisch als PWA installierbar.

## Enthaltene Varianten

- Browser: Mehrgrößen-ICO (16, 24, 32, 48, 64, 128, 256 px), SVG und
  PNG (16, 24, 32, 48, 64, 96, 128, 192, 256, 512 px).
- iPhone/iPad: deckende Apple-Touch-Icons ohne vorgegebene runde Ecken
  (57, 60, 72, 76, 114, 120, 144, 152, 167, 180 px).
- Android/PWA/ChromeOS/Desktop-Web-Apps: 192 und 512 px sowie separate
  maskierbare Varianten mit vollständig sichtbarem Logo innerhalb der sicheren Kreisfläche.
- Monochromes 512-px-Icon und Safari-Pinned-Tab-SVG mit transparentem Hintergrund.
- Ältere Windows-/IE-/Edge-Kacheln: 70, 144, 150 und 310 px sowie 310 × 150 px;
  browserconfig.xml. Moderne Edge-Versionen verwenden die Browser-/PWA-Icons.

Der vollständige Schriftzug wird bei 16 × 16 Pixeln naturgemäß sehr klein.
Die gelieferten Dateien decken die üblichen Browser- und Geräteformate ab;
die tatsächliche Darstellung wurde nicht auf jedem realen Gerät geprüft.
Vorhandene Dateien `favicon.png`, `favicon.svg` und die Original-Logos im
Zielordner werden nicht ersetzt. Deshalb verweist die neue Einbindung ausdrücklich
auf `huafoo-favicon.svg`.

## Referenzen

- https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/link
- https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps/Manifest/Reference/icons
- https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps/How_to/Define_app_icons
- https://developer.apple.com/library/archive/documentation/AppleApplications/Reference/SafariWebContent/pinnedTabs/pinnedTabs.html
