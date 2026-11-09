# Política de Privacidad de IWallet

**Última actualización:** 09/11/2026

IWallet ("la app") es una aplicación de control personal de ingresos y gastos desarrollada por Dani ("el desarrollador"). Esta política explica qué información trata la app, a dónde va y qué opciones tienes. English version: [PRIVACY_POLICY.md](PRIVACY_POLICY.md).

## 1. Datos guardados en tu dispositivo

Todos tus datos financieros (movimientos, categorías, conceptos, límites, notas), tus ajustes y tu PIN de acceso se guardan **solo en tu dispositivo**, en el almacenamiento privado de la app. La app no tiene cuentas de usuario ni un servidor del desarrollador donde se almacenen tus datos financieros. El desarrollador no puede verlos.

* **PIN de acceso:** se guarda como hash (SHA-256), no en texto plano.
* **Clave API de Gemini (opcional):** si introduces tu propia clave, se guarda localmente en tu dispositivo.
* **Copias de seguridad:** la app desactiva la copia de seguridad automática de Android. La app no copia tus datos a Google Drive. Si desinstalas la app, el sistema operativo elimina sus datos locales. Puedes exportar tus movimientos a CSV en cualquier momento. Puedes borrar cualquier movimiento desde la pestaña Global deslizándolo; los movimientos borrados van a la Papelera (Ajustes > Papelera), donde puedes restaurarlos o eliminarlos definitivamente, y se eliminan automáticamente a los 7 días. Las categorías y los conceptos se pueden editar o borrar desde Ajustes. Para eliminar todos los datos de una vez, consulta el apartado 6.

## 2. Permisos

* **Cámara / galería (mediante el selector del sistema):** para hacer o elegir una foto de un ticket.
* **Micrófono:** para introducir movimientos por voz.
* **Internet:** para las funciones opcionales descritas a continuación.

## 3. Funciones que envían datos fuera de tu dispositivo

**a) Lectura de tickets con IA en la nube (opcional, desactivada por defecto).** Por defecto los tickets se leen localmente en tu dispositivo con Google ML Kit y la imagen no sale de tu teléfono. Si decides introducir tu propia clave API de Google Gemini en Ajustes, la imagen del ticket se envía a la API de Gemini de Google para extraer comercio, fecha e importe. Google lo trata según sus propios términos: https://policies.google.com/privacy. Si la petición a la nube falla, la app recurre a la lectura local y te avisa.

**b) Entrada por voz.** El reconocimiento de voz usa el servicio de reconocimiento de voz de tu dispositivo Android, proporcionado por Google, que según la configuración de tu dispositivo puede procesar el audio en servidores de Google. La app no guarda el audio; solo recibe el texto reconocido.

**c) Formulario "Próximamente" (opcional).** Si abres el formulario "Próximamente" sobre próximas funciones, puedes enviar:
* tu **correo electrónico** (solo si decides escribirlo),
* qué funciones futuras te interesan,
* una **sugerencia en texto libre**,
* el hecho de que has aceptado esta política.

Esta información se envía por HTTPS a un endpoint de Google Apps Script y se guarda en una hoja de Google Sheets privada a la que **solo accede el desarrollador**. Finalidad: avisarte cuando estén disponibles las funciones que elegiste y mejorar la app. Base legal: tu consentimiento (debes marcar la casilla de aceptación). Se conserva hasta el lanzamiento de las funciones o hasta que pidas su eliminación. Puedes retirar tu consentimiento y solicitar el borrado en cualquier momento escribiendo al correo de contacto. Te pedimos que no incluyas datos personales sensibles en la sugerencia.

## 4. Publicidad y seguimiento

La app no contiene publicidad ni herramientas de analítica o seguimiento, y el desarrollador no vende ni comparte tu información con anunciantes.

## 5. Tus derechos

Si estás en el Espacio Económico Europeo u otra región con leyes similares, tienes derecho a acceder, rectificar, suprimir o limitar el tratamiento de los datos descritos en el apartado 3c, y a retirar tu consentimiento. Contacta con el desarrollador en la dirección indicada abajo.

## 6. Cómo eliminar tus datos

**Datos en tu dispositivo** (movimientos, pendientes, categorías, conceptos, límites, ajustes, PIN). Puedes borrarlos tú mismo en cualquier momento:

1. Entra en **Ajustes > Copia de seguridad y datos > Empezar de cero** y confirma escribiendo BORRAR. Se borran todos los movimientos, los pendientes y la papelera. Las categorías, los conceptos, los límites, los ajustes, tu PIN y tu clave de Gemini se conservan; puedes editarlos o borrarlos desde Ajustes.
2. O desinstala la app, o borra su almacenamiento en los ajustes de Android, para eliminarlo todo.

El desarrollador no puede ver ni borrar estos datos, porque nunca salen de tu dispositivo.

**Datos que enviaste con el formulario "Próximamente"** (correo electrónico, funciones elegidas, texto de la sugerencia). Para pedir su eliminación, escribe a dsalcedocias@gmail.com con el asunto "Borrar mis datos de IWallet", desde el correo que usaste en el formulario (o indícalo en el mensaje). Se eliminarán de la hoja privada de Google en un plazo de 30 días y recibirás una confirmación por correo. Si no pides nada, se conservan hasta el lanzamiento de las funciones que elegiste.

**Fotos de tickets enviadas a Gemini** (solo si introduces tu propia clave de Gemini). IWallet no las conserva: la app borra la foto de su caché después de procesarla. La copia enviada a la API de Gemini de Google se trata según los términos de Google: https://policies.google.com/privacy.

**Voz.** IWallet no guarda el audio. El reconocimiento de voz lo hace el servicio de voz de Android de tu dispositivo, según los ajustes de tu dispositivo y de tu cuenta de Google.

## 7. Menores

La app no está dirigida a menores de 13 años (o la edad mínima de tu país).

## 8. Cambios en esta política

Si la app cambia de forma que afecte a tus datos (por ejemplo, sincronización en la nube o planes de pago), esta política se actualizará y se cambiará la fecha de arriba.

## 9. Contacto

dsalcedocias@gmail.com
