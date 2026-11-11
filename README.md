# Fortnite Treasure Simulator 2.0

PWA instalable en Android. No necesita cuenta ni servidor de juego.

## Mejoras incluidas
- Hasta 12 perfiles independientes, cada uno con nivel, tipo, cofres, premios e historial.
- Animación CSS al abrir un cofre.
- Aperturas x1, x10, x100, x1.000 y x10.000.
- Catálogo de siete categorías de recompensa, rarezas y probabilidades.
- Reglas de objetos únicos: los seis tesoros no-Gizmo dejan de salir cuando el perfil los consigue; Gizmos se pueden repetir.
- Modos normal, Treasure Hours estándar, sesión especial y multiplicadores manuales.
- Estadísticas y probabilidad acumulada, clasificación local y exportación JSON.
- Editor manual de recompensas semanales.
- Guardado local y caché PWA.

## Instalar en Android
1. Extrae el ZIP.
2. Publica los tres archivos (`index.html`, `manifest.webmanifest`, `sw.js`) en un hosting estático HTTPS (por ejemplo GitHub Pages).
3. Abre la URL en Chrome Android.
4. Menú ⋮ > Instalar aplicación / Añadir a pantalla de inicio.

Abrir directamente el HTML permite probarlo, pero la instalación PWA y el modo offline requieren HTTPS o localhost.

## Probabilidades de referencia del evento Treasure Hunters (noviembre 2026)
- Traje dorado semanal: 1/1.562.500.
- Pirate Shop Access: 1/137.500.
- Vehículo y diseño semanal: 1/7.813.
- Pico o accesorio mochilero: 1/568.
- Jam Track semanal: 1/391.
- Pantalla de carga semanal: 1/272.
- Cualquier Gizmo: 1/127.

Multiplicadores de referencia publicados para Treasure Hours estándar: traje 7,5x; Pirate Shop Access 1,5x; vehículo 10x. Una sesión especial publicada utilizó 10x para traje, 2x para Pirate Shop Access y 10x para vehículo. Los demás premios no muestran multiplicador en esos anuncios. No asumir que futuras sesiones usarán los mismos multiplicadores.

Los objetos únicos se modelan como no repetibles; Gizmos sí pueden repetirse. Los cálculos son una simulación de probabilidad por cofre y no un emulador interno de Epic. El nivel de cuenta no cambia la suerte.

## Fuentes de consulta
- Fortnite Status / Epic Games: anuncio de probabilidades publicado el 7 de noviembre de 2026 (resumido por medios y guías de seguimiento).
- https://fortnitepiratetoken.wiki/treasure-hunters-chest-rewards/
- https://hudwire.com/fortnite-treasure-drop-rates/
- https://www.vice.com/en/article/fortnite-treasure-hours-schedule/

## Limitaciones
- No se conecta a Epic Games ni requiere credenciales.
- No otorga cosméticos, monedas, tokens ni acceso a Pirate Shop.
- El catálogo semanal es editable manualmente; no se descarga automáticamente porque no hay una API pública oficial garantizada para ese catálogo.
- Los nombres de la semana 2 son marcadores editables cuando no hay confirmación oficial clara.
- Los datos se guardan en el almacenamiento del navegador; borrar los datos del sitio puede borrarlos. Exporta el JSON para conservar una copia.
- Proyecto de aficionados no oficial. Fortnite y sus activos pertenecen a Epic Games.
