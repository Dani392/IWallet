# Política de Privacidad de IWallet

**Última actualización:** 02/11/2026

IWallet ("la app") es una aplicación de control personal de ingresos y gastos desarrollada por Dani ("el desarrollador"). Esta política explica qué información trata la app, a dónde va y qué opciones tienes. English version: [PRIVACY_POLICY.md](PRIVACY_POLICY.md).

## 1. Datos guardados en tu dispositivo

Todos tus datos financieros (movimientos, categorías, conceptos, límites, notas), tus ajustes y tu PIN de acceso se guardan **solo en tu dispositivo**, en el almacenamiento privado de la app. La app no tiene cuentas de usuario ni un servidor del desarrollador donde se almacenen tus datos financieros. El desarrollador no puede verlos.

* **PIN de acceso:** se guarda como hash (SHA-256), no en texto plano.
* **Clave API de Gemini (opcional):** si introduces tu propia clave, se guarda localmente en tu dispositivo.
* **Copias de seguridad:** la app desactiva la copia de seguridad automática de Android. La app no copia tus datos a Google Drive. Si desinstalas la app, el sistema operativo elimina sus datos locales. Puedes exportar tus movimientos a CSV en cualquier momento. Puedes borrar cualquier movimiento desde la pestaña Global deslizándolo; los movimientos borrados van a la Papelera (Ajustes > Papelera), donde puedes restaurarlos o eliminarlos definitivamente, y se eliminan automáticamente a los 7 días. Las categorías y los conceptos se pueden editar o borrar desde Ajustes. Para eliminar todos los datos de una vez, desinstala la app o borra su almacenamiento en los ajustes de Android.

## 2. Permisos

* **Cámara / galería (mediante el selector del sistema):** para hacer o elegir una foto de un ticket.
* **Micrófono:** para introducir movimientos por voz.
* **Internet:** para las funciones opcionales descritas a continuación.

## 3. Funciones que envían datos fuera de tu dispositivo

**a) Lectura de tickets con IA en la nube (opcional, desactivada por defecto).** Por defecto los tickets se leen localmente en tu dispositivo con Google ML Kit y la imagen no sale de tu teléfono. Si decides introducir tu propia clave API de Google Gemini en Ajustes, la imagen del ticket se envía a la API de Gemini de Google para extraer comercio, fecha e importe. Google lo trata según sus propios términos: https://policies.google.com/privacy. Si la petición a la nube falla, la app recurre a la lectura local y te avisa.

**b) Entrada por voz.** El reconocimiento de voz usa el servicio de reconocimiento de voz de tu dispositivo Android, proporcionado por Google, que según la configuración de tu dispositivo puede procesar el audio en servidores de Google. La app no guarda el audio; solo recibe el texto reconocido.

**c) Formulario "Avísame" / sugerencias (opcional).** Si abres el formulario sobre próximas funciones, puedes enviar:
* tu **correo electrónico** (solo si decides escribirlo),
* qué funciones futuras te interesan,
* una **sugerencia en texto libre**,
* el hecho de que has aceptado esta política.

Esta información se envía por HTTPS a un endpoint de Google Apps Script y se guarda en una hoja de Google Sheets privada a la que **solo accede el desarrollador**. Finalidad: avisarte cuando estén disponibles las funciones que elegiste y mejorar la app. Base legal: tu consentimiento (debes marcar la casilla de aceptación). Se conserva hasta el lanzamiento de las funciones o hasta que pidas su eliminación. Puedes retirar tu consentimiento y solicitar el borrado en cualquier momento escribiendo al correo de contacto. Te pedimos que no incluyas datos personales sensibles en la sugerencia.

## 4. Publicidad y seguimiento

La app no contiene publicidad ni herramientas de analítica o seguimiento, y el desarrollador no vende ni comparte tu información con anunciantes.

## 5. Tus derechos

Si estás en el Espacio Económico Europeo u otra región con leyes similares, tienes derecho a acceder, rectificar, suprimir o limitar el tratamiento de los datos descritos en el apartado 3c, y a retirar tu consentimiento. Contacta con el desarrollador en la dirección indicada abajo.

## 6. Menores

La app no está dirigida a menores de 13 años (o la edad mínima de tu país).

## 7. Cambios en esta política

Si la app cambia de forma que afecte a tus datos (por ejemplo, sincronización en la nube o planes de pago), esta política se actualizará y se cambiará la fecha de arriba.

## 8. Contacto

dsalcedocias@gmail.com
