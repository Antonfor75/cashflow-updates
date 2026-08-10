# cashflow-updates

Hosting fuer die OTA-Updates der Handy-App **Mein Cashflow**.

Die App prueft beim Start die `manifest.json` des neuesten Releases und laedt bei
neuer Version das Bundle `cashflow.zip` herunter — ohne Neuinstallation.

Feste URLs (nicht aendern, sind in der App eingebacken):

- https://github.com/Antonfor75/cashflow-updates/releases/latest/download/manifest.json
- https://github.com/Antonfor75/cashflow-updates/releases/latest/download/cashflow.zip

Releases werden automatisch per `/push-local-app` erzeugt.