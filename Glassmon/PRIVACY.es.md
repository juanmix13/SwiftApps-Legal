# Política de Privacidad — Glassmon

**Última actualización:** Octubre 2026
**Nombre de la app:** Glassmon
**Desarrollador:** Juan Miguel Durán — juanmix13@hotmail.com

---

## 1. Resumen en lenguaje sencillo

**Glassmon no recopila, almacena, vende ni comparte ningún dato personal, y no envía ningún dato al desarrollador ni a terceros.** Las métricas del sistema que muestra la app — uso de CPU, memoria, nivel de batería, almacenamiento y velocidad de red — se leen localmente en tiempo real y nunca salen de su dispositivo. No hay cuenta, no hay servidor, no hay analítica, no hay red publicitaria y no hay SDK de terceros.

La única excepción es la tarjeta Network Tools, que usted usa de forma voluntaria: para medir la latencia o resolver un nombre, su dispositivo se conecta al host que usted indica, igual que haría un navegador. Ese host (y su resolvedor DNS) puede ver la dirección IP de su conexión. Glassmon no recibe ni guarda esa información.

Si desinstala la app, no queda nada en ningún sitio.

---

## 2. Información que maneja la app

| Información | Finalidad | Almacenamiento | ¿Sale del dispositivo? |
|---|---|---|---|
| Uso de CPU | Mostrar tarjeta CPU | Solo en memoria | **No** |
| Uso de RAM | Mostrar tarjeta Memoria | Solo en memoria | **No** |
| Nivel y estado de batería | Mostrar tarjeta Batería | Solo en memoria | **No** |
| Capacidad de almacenamiento | Mostrar tarjeta Almacenamiento | Solo en memoria | **No** |
| Contadores de interfaz de red | Mostrar velocidad de red | Solo en memoria | **No** |
| Host o dominio que usted escribe (Network Tools) | Medir latencia y resolver DNS | Solo en memoria | **Solo hacia el host que usted indica** |

---

## 3. Lo que la app NO recopila

- Identificadores personales (nombre, email, Apple ID, IDFA)
- Datos de ubicación
- Datos de salud de HealthKit
- Registros de errores o telemetría
- Cookies o identificadores publicitarios
- Identificadores de dispositivo de ningún tipo

---

## 4. Servicios de terceros

Glassmon no integra ningún SDK de terceros. No hay Firebase, Google Analytics, Meta SDK, AdMob ni servicio de reporte de errores. La app usa únicamente los frameworks públicos de iOS de Apple.

Glassmon solo realiza peticiones de red cuando usa la tarjeta Network Tools, y únicamente hacia el host o dominio que usted escribe (`apple.com` por defecto). La prueba de latencia abre una conexión TCP a ese host por el puerto 443, y la consulta DNS pide a su resolvedor DNS configurado que resuelva el nombre introducido. Glassmon no envía ningún dato a servidores del desarrollador y no almacena los hosts introducidos ni los resultados.

---

## 5. Menores

Glassmon tiene clasificación 4+ y es apta para todas las edades. No recopila datos de nadie, incluidos menores de 14 años.

---

## 6. El papel de Apple

Cuando descarga la app desde el App Store, Apple puede recibir información anónima estándar sobre la descarga. Esto se rige por la política de privacidad de Apple. La ficha del App Store refleja **"Sin recopilación de datos"**.

---

## 7. Sus derechos según el RGPD

Dado que la app no recopila datos personales, no existe ningún conjunto de datos sobre el que ejercer los derechos del RGPD. Para cualquier consulta, contacte con el desarrollador en el email indicado. También puede dirigirse a la autoridad española de protección de datos: [aepd.es](https://www.aepd.es).

---

## 8. Contacto

**Juan Miguel Durán**
Email: **juanmix13@hotmail.com**
GitHub Issues: **https://github.com/juanmix13/SwiftApps-Legal/issues**
