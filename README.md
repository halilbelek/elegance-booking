# Elegance Booking

Mobilapp til Elegance Ilayda Selskabslokaler: ny booking, ret booking, se og send lejekontrakt.

Siden indeholder ingen data. Den taler med Google Apps Script-projektet "Elegance Fakturering"
(regnearket "Elegance – Fakturering") og er beskyttet af en PIN-kode, der står i regnearkets
ark Indstillinger.

`index.html` genereres fra `App.gs` (funktionen `appHtml_(apiUrl)`) – ret ikke i den direkte.
