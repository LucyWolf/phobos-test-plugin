# Phobos Test-Plugin

Ein harmloses Plugin zum Ausprobieren der Plugin-Funktion in
[phobos-bot](https://github.com/LucyWolf/phobos-bot) — zum Einspielen **über einen Link**,
ohne Datei herunterzuladen.

Es legt zwei Dinge an und sonst nichts:

- einen Befehl **`!plugintest`**, der eine frei wählbare Antwort schreibt,
- eine **Level-Belohnung** auf Stufe 5.

Beides ist gefahrlos und jederzeit wieder zu entfernen.

## Einspielen

Im Dashboard unter **Einstellungen → Plugins → „Oder über einen Link einspielen"** diese
Adresse eintragen:

```
https://raw.githubusercontent.com/LucyWolf/phobos-test-plugin/main/test-plugin.json
```

Dann **Vom Link holen**. Das Plugin erscheint mit dem Icon 🧪 in der Liste.

## Durchspielen

1. **Einstellungen → Plugins** — das Plugin steht da als 🧪 Test-Plugin.
2. Darunter **„Auf einem Server anlegen"** → einen Server wählen.
3. Auf der Serverseite das Antwort-Feld ausfüllen (oder den Standard lassen) → **anlegen**.
4. In der **Server-Leiste** erscheint 🧪 Test-Plugin.
5. In Discord **`!plugintest`** tippen → der Bot antwortet mit deinem Text.
6. **Vom Server entfernen** nimmt Befehl und Belohnung sofort wieder zurück.

## Voraussetzung

Die Plugin-Funktion gibt es ab **phobos-bot 1.19.39**, das Einspielen über einen Link ab
**1.19.40**, und die Server-Leiste mit Icon und Namen ab **1.19.50**. Eine ältere
Installation zeigt den Reiter nicht — dann erst aktualisieren.

## Aktualisieren testen

Die Datei nennt sich selbst als `quelle`. Im Dashboard zeigt **„Nach Update suchen"**
deshalb, dass sie aktuell ist — und wenn hier je eine höhere `version` stünde, böte es die
neue Fassung an. So lässt sich auch der Update-Weg ausprobieren.

## Lizenz

Gemeinfrei / MIT — mach damit, was du willst.
