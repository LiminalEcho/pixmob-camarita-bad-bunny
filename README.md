# PixMob DTMF - Bad Bunny Camera Control (Android)
### Controla la Camarita DTMF de Bad Bunny con tu Celular Android

> Tested with a **Bad Bunny "Debí Tirar Más Fotos"** PixMob badge and a **Xiaomi 14T Pro**. Color codes also confirmed working on Taylor Swift era bracelets by the community.
>
> Probado con una camarita PixMob del tour **"Debí Tirar Más Fotos"** de Bad Bunny y un **Xiaomi 14T Pro**. Códigos de colores también confirmados en pulseras de Taylor Swift por la comunidad.

---

## Files / Archivos

| File | Description / Descripción |
|---|---|
| `pixmob_remote.irplus` | Ready-to-import irplus file / Archivo listo para importar en irplus |

---

---

# 🇬🇧 English

## Requirements

- Android phone with **built-in IR blaster** (most Xiaomi, Redmi, Poco models)
- **irplus** app: `play.google.com/store/apps/details?id=net.binarymode.android.irplus`
- PixMob badge with working **CR2032** batteries

> Not sure if your phone has an IR blaster? Search your model name + "IR blaster" online.

---

## Step 1 - Check Your Batteries

If you received the badge at a concert more than a few days ago, the batteries may be dead. Most PixMob badges use **CR2032** batteries. Look for a small cover on the back you can open with a coin.

---

## Step 2 - Install irplus

Download **irplus** from the Play Store and if you have a Xiaomi phone do this after installing:
- Settings > Apps > irplus > Battery → **No restrictions**
- Settings > Apps > irplus > Permissions → **enable all**

---

## Step 3 - Download and Import

1. Download `pixmob_remote.irplus` from this repo to your Downloads folder
2. Open irplus → tap **⋮** → **Import remote** → select the file
3. The remote will appear with all buttons

> If you get "invalid or no device" make sure the file extension is `.irplus` not `.xml` or `.txt`

---

## Step 4 - Control Your Badge

- Point the **top edge** of your phone at the badge from **20-50cm**
- Tap any color button
- Use **fade variants** for longer glow per tap
- Tap **PROGRAM** first, then immediately a color for a persistent effect

---

## What Works and What Doesn't

| Feature | Status |
|---|---|
| Single color flash | ✅ Confirmed working |
| Color fade effects | ✅ Confirmed working |
| PROGRAM command | ✅ Confirmed working |
| Autonomous loop (badge blinks on its own) | ❌ Not yet available |

The autonomous loop seen after concerts is pre-programmed by the venue's professional IR transmitters during the show. That exact signal has not been publicly captured yet for the Bad Bunny badge. If you attended a show with a Flipper Zero, capturing and sharing the IR signal would help the community enormously.

---

## Troubleshooting

**"Invalid or no device" when importing** → check the file extension is `.irplus`

**Badge does not respond** → check batteries (CR2032) first

**Badge turns off** → you sent a reset command accidentally, wait 10-15 seconds and try a color again

**Colors fade too quickly** → use the fade variant buttons or tap repeatedly

**irplus crashes on Xiaomi** → Settings > Apps > irplus > Battery > No restrictions

---

---

# 🇪🇸 Español

## Requisitos

- Celular Android con **infrarrojo integrado** (la mayoría de Xiaomi, Redmi, Poco)
- App **irplus**: `play.google.com/store/apps/details?id=net.binarymode.android.irplus`
- Camarita PixMob con batería **CR2032** funcionando

> ¿No sabes si tu celular tiene infrarrojo? Busca el modelo + "IR blaster" en Google.

---

## Paso 1 - Verifica la batería

Si recibiste la camarita en el concierto hace más de unos días, la batería puede estar agotada. La mayoría usan baterías **CR2032**. Busca una pequeña tapa en la parte trasera que puedas abrir con una moneda.

---

## Paso 2 - Instala irplus

Descarga **irplus** desde Play Store. Si tienes un celular Xiaomi haz esto después de instalar:
- Ajustes > Apps > irplus > Batería → **Sin restricciones**
- Ajustes > Apps > irplus > Permisos → **activar todos**

---

## Paso 3 - Descarga e importa

1. Descarga `pixmob_remote.irplus` desde este repositorio a tu carpeta de Descargas
2. Abre irplus → toca **⋮** → **Importar control** → selecciona el archivo
3. Aparecerá el control con todos los botones

> Si aparece "dispositivo inválido" verifica que el archivo termine en `.irplus` y no en `.xml` o `.txt`

---

## Paso 4 - Controla tu camarita

- Apunta el **borde superior** del celular a la camarita desde **20-50cm**
- Toca cualquier botón de color
- Usa los botones **fade** para que dure más por toque
- Toca **PROGRAM** primero y luego inmediatamente un color para un efecto persistente

---

## Qué funciona y qué no

| Función | Estado |
|---|---|
| Color fijo | ✅ Confirmado funcionando |
| Efectos fade | ✅ Confirmado funcionando |
| Botón PROGRAM | ✅ Confirmado funcionando |
| Loop autónomo (camarita parpadea sola) | ❌ Aún no disponible |

El loop autónomo que ves después del concierto es pre-programado por los transmisores IR profesionales del venue durante el show. Esa señal exacta no ha sido capturada públicamente todavía para la camarita de Bad Bunny. Si fuiste al concierto con un Flipper Zero, capturar y compartir la señal IR ayudaría mucho a la comunidad.

---

## Solución de problemas

**"Dispositivo inválido" al importar** → verifica que el archivo termine en `.irplus`

**La camarita no responde** → revisa la batería (CR2032) primero

**La camarita se apaga** → enviaste un comando de reset, espera 10-15 segundos y prueba un color de nuevo

**Los colores duran poco** → usa los botones fade o toca repetidamente

**irplus se cierra solo en Xiaomi** → Ajustes > Apps > irplus > Batería > Sin restricciones

---
iOS is not supported with this method. iPhone has no built-in IR blaster. A possible workaround exists using an IR blaster dongle but has not been tested with the Bad Bunny badge.
---

## Credits / Créditos

- Color codes / Códigos de colores: [danielweidman/pixmob-ir-reverse-engineering](https://github.com/danielweidman/pixmob-ir-reverse-engineering)
- PROGRAM button: community irplus files for Taylor Swift EOC badges
- Real-world testing / Pruebas reales: [@LiminalEcho](https://github.com/LiminalEcho)
- PIXMOD Discord: `-`
---



*#dtmf #badbunny #camaritabadbunny #pixmob #debitirarmasfotos #irplus #pixmod*
