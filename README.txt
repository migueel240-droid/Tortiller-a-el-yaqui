TORTILLERÍA OBREGÓN — PAQUETE INICIAL DE APLICACIÓN WEB
=====================================================

Incluye:
- index.html: pantalla principal
- styles.css: diseño azul, blanco y amarillo adaptable a teléfono
- app.js: ventas, ticket con varios productos, inventario, cargas, devoluciones, balances, productos, repartidores y respaldos
- manifest.json y sw.js: instalación tipo PWA y caché para uso sin conexión después de la primera carga

IMPORTANTE — ALCANCE DE ESTA VERSIÓN
1. Los datos se guardan en el navegador del dispositivo (localStorage).
2. La opción de repartidor sirve como selector de vista para pruebas; NO es una autenticación segura.
3. Todavía NO hay sincronización real entre teléfonos. Para que el administrador reciba automáticamente las ventas hechas por otros teléfonos se necesita un backend/servidor y cuentas de usuario.
4. Las existencias del almacén y las de repartidores son movimientos separados. Revisa los movimientos y descarga respaldos JSON con frecuencia.
5. El paquete es una aplicación web/PWA, NO un SDK nativo de Android ni un APK.

CÓMO PROBARLA
- Descomprime el ZIP.
- Para probar localmente, abre index.html en un navegador compatible. Algunas funciones offline/PWA solo se activan cuando se publica por HTTPS.
- Para instalarla como app: publícala en un sitio HTTPS (por ejemplo GitHub Pages) y abre el enlace en Chrome Android; menú ⋮ > Añadir a pantalla principal / Instalar.
- Descarga un respaldo desde Productos > Respaldo y recuperación.

Siguiente etapa recomendada:
- Configurar cuentas seguras para administrador y repartidores.
- Sincronización central con resolución de conflictos.
- Inventario y cortes auditables entre dispositivos.
