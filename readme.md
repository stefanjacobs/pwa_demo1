# PWA Tutorial

PWA Tutorial aus iX 10/2018. Erst mal nur ein hello-world.

## Installation

```bash
npm i -g workbox-cli lite-server
workbox wizard
```

Die Ausführung von ```workbox wizard``` war erst nach Anlegen der ```index.html``` möglich. Ansonsten waren überall die default settings angemessen.

## Build

```bash
workbox generateSW workbox-config.js
```

Hiermit wird die serviceworker ```sw.js``` angelegt.

## Run

```bash
lite-server
```

Der Lite Server startet und öffnet automatisch den Standardbrowser mit der index.html im PWA Modus. D.h. beim beenden des lite-server verbleibt die WebApp im Caches und die hinterlegte index.html wird weiterhin durch den Browser bedient.

# Referenz

[Progressive Web App mit Workbox](https://developers.google.com/web/tools/workbox/ "Google's Workbox Framework")
