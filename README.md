# cuenta · mova nfc

Página estática que muestra y copia un número de cuenta guardado en un chip NFC creado con **mova nfc**.

**Privacidad:** los datos viajan en el fragmento de la URL (`#c=...&t=...&b=...`). Los navegadores nunca envían el fragmento al servidor, y la página prohíbe cualquier conexión de red mediante Content-Security-Policy (`default-src 'none'`). Nada se guarda ni se envía: todo ocurre en el teléfono de quien escanea.

Formato: `https://moca9801.github.io/cuenta/#c=<cuenta>&t=<titular>&b=<banco>`
