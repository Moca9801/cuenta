# cuenta · mova nfc

Página estática que muestra y copia un número de cuenta guardado en un chip NFC creado con **mova nfc**.

**Privacidad:** los datos viajan en el fragmento de la URL (`#c=...&t=...&b=...`). Los navegadores nunca envían el fragmento al servidor, y la página prohíbe cualquier conexión de red mediante Content-Security-Policy (`default-src 'none'`). Nada se guarda ni se envía: todo ocurre en el teléfono de quien escanea.

Formato: `https://pago.mocadev.site/#c=<cuenta>&t=<titular>&b=<código del banco>` (la dirección anterior `moca9801.github.io/cuenta/` redirige aquí).

## Logotipos

Los íconos de `logos/` son los íconos públicos de las apps oficiales de cada banco en Google Play. Se incluyen en el repositorio (no se cargan de terceros) para que nadie más se entere de cuándo se escanea un chip. Son marcas de sus respectivos dueños; mova nfc no está afiliada a ningún banco.
