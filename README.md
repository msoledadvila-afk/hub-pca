# Hub PCA™ · Talento Impulsa Consulting

Centro de trabajo de la consultora para el Modelo PCA™ — Productividad Consciente Aumentada: reúne por cliente los resultados del diagnóstico, las notas de cada sesión y la evolución en el tiempo.

**Estado:** Producción · uso interno (acceso restringido con cuenta de Google)
**App:** [msoledadvila-afk.github.io/hub-pca](https://msoledadvila-afk.github.io/hub-pca/)

## Qué hace

- Ficha por cliente con los resultados del diagnóstico
- Notas del consultor y datos de cada sesión
- Evolución por categoría entre sesiones y registro de logros concretos del cliente
- Importación de clientes desde el Dashboard de Talento Impulsa

## Lugar en el Modelo PCA™

El Modelo PCA™ trabaja en tres momentos: Ordenar → Delegar → Sostener. El Hub acompaña el momento Sostener: deja registro de cada avance para medir la evolución del cliente.

> Los objetivos del Modelo PCA™ son recuperar entre 5 y 10 horas semanales y tener respuesta en 48 a 72 h. Son objetivos de trabajo, no resultados garantizados.

## Stack

| Capa | Tecnología |
| --- | --- |
| Frontend | React 18 + Babel en el navegador, archivo único |
| Datos | Firebase Firestore (Compat SDK) |
| Acceso | Firebase Auth con Google, limitado a cuentas autorizadas |
| Hosting | GitHub Pages |

## Seguridad

La `apiKey` de Firebase que aparece en el código es pública por diseño. La protección está en las Reglas de Firestore, que solo permiten cuentas autorizadas con email verificado, y en los dominios autorizados del proyecto.

## Licencia

© 2026 Talento Impulsa Consulting. Todos los derechos reservados. Código visible solo como referencia; no se autoriza su reutilización comercial.

---

**Talento Impulsa Consulting** · [talentoimpulsa.com.ar](https://talentoimpulsa.com.ar)
hola@talentoimpulsa.com.ar · presupuestos@talentoimpulsa.com.ar
