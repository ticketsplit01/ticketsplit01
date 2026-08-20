# Política de Privacidad de TicketSplit

**Última actualización:** 20 de agosto de 2026

Esta Política de Privacidad describe cómo TicketSplit ("la App", "nosotros") recopila, usa y protege la información cuando usas nuestra aplicación móvil.

Al usar TicketSplit, aceptas las prácticas descritas en este documento.

---

## 1. Resumen rápido

- **No creas una cuenta.** No pedimos email, contraseña ni nombre real.
- **La foto del recibo nunca sale de tu teléfono.** El reconocimiento de texto ocurre completamente en tu dispositivo.
- **Los datos de cada mesa se borran automáticamente a las 24 horas.**
- **Mostramos anuncios** a través de Google AdMob para mantener la app gratuita.
- **Los nombres que escribes** para identificar a cada persona en la mesa se guardan temporalmente para que la cuenta se pueda dividir; pueden ser apodos, no tienen que ser tu nombre real.

---

## 2. Información que recopilamos

### 2.1 Información que tú ingresas
Cuando usas TicketSplit, la app guarda temporalmente:
- El subtotal, impuesto, propina y los artículos de la cuenta que ingresas o escaneas.
- Los nombres o apodos que escribes para identificar a cada persona o pareja en la mesa.
- El estado/jurisdicción fiscal que seleccionas (ej. Puerto Rico) y las tasas de impuesto asociadas.

Esta información se almacena en nuestra base de datos (Google Firebase / Cloud Firestore) asociada a un código de mesa, y **se elimina automáticamente 24 horas después de crearse la mesa**.

### 2.2 Fotos de recibos
Si usas la función de escanear recibo, la foto se procesa **enteramente en tu dispositivo** usando Google ML Kit (reconocimiento de texto on-device). **La imagen nunca se sube a nuestros servidores ni a servidores de terceros.** La foto se guarda temporalmente en la memoria caché de tu teléfono mientras se procesa y luego se descarta.

### 2.3 Identificadores de dispositivo y anónimos
- Usamos **Firebase Authentication en modo anónimo**: a tu teléfono se le asigna un identificador aleatorio para poder sincronizar la mesa entre los distintos participantes. Este identificador no está vinculado a tu nombre, email ni ninguna otra información personal identificable.
- Para efectos de publicidad, Google AdMob puede recopilar el **identificador de publicidad de tu dispositivo** y datos de interacción con anuncios (impresiones, clics), conforme a su propia política de privacidad.

### 2.4 Datos de diagnóstico y fallos
Usamos **Firebase Crashlytics** para recibir reportes automáticos si la app falla, y **Firebase App Check** para verificar que las solicitudes a nuestra base de datos provienen de una instalación legítima de la app. Estos servicios pueden recopilar información técnica del dispositivo (modelo, versión de sistema operativo, registros de fallos) pero no información personal identificable.

### 2.5 Lo que NO recopilamos
No recopilamos ni almacenamos: tu nombre legal, dirección de correo electrónico, número de teléfono, ubicación GPS, contactos, información de pago, ni ningún dato bancario o de tarjetas de crédito.

---

## 3. Cómo usamos la información

Usamos la información descrita arriba únicamente para:
- Permitir que varias personas en la misma mesa vean y editen la cuenta en tiempo real.
- Calcular correctamente subtotales, impuestos, propina y el monto que corresponde a cada persona.
- Mostrar anuncios para mantener la app gratuita.
- Detectar y corregir errores técnicos (fallos, bugs).
- Prevenir abuso o acceso fraudulento a nuestra base de datos.

No vendemos tu información a terceros. No usamos la información de las mesas con fines distintos a los descritos aquí.

---

## 4. Servicios de terceros

TicketSplit utiliza los siguientes servicios de terceros, cada uno con su propia política de privacidad:

| Servicio | Propósito | Política de privacidad |
|---|---|---|
| Google Firebase (Firestore, Authentication) | Sincronización de datos de la mesa | https://firebase.google.com/support/privacy |
| Firebase Crashlytics | Reportes de fallos | https://firebase.google.com/support/privacy |
| Firebase App Check / Google Play Integrity | Seguridad y prevención de abuso | https://firebase.google.com/support/privacy |
| Google AdMob | Publicidad dentro de la app | https://policies.google.com/technologies/ads |
| Google ML Kit | Reconocimiento de texto (100% en el dispositivo) | https://developers.google.com/ml-kit |
| Google User Messaging Platform (UMP) | Consentimiento de anuncios (usuarios en EEE/Reino Unido) | https://policies.google.com/privacy |

---

## 5. Retención y eliminación de datos

Los datos de cada mesa (subtotal, items, nombres de participantes) se eliminan automáticamente **24 horas** después de creada la mesa. Este teléfono también guarda localmente, por hasta 24 horas, una lista de "mesas recientes" para que puedas volver a entrar sin recordar el código; puedes borrar esta lista desde el propio dispositivo.

Los reportes de fallos y datos de diagnóstico se conservan conforme a las políticas de retención estándar de Firebase Crashlytics.

---

## 6. Tus derechos

Dependiendo de tu ubicación, puedes tener derecho a solicitar acceso, corrección o eliminación de tu información. Dado que TicketSplit no crea cuentas de usuario ni vincula datos a tu identidad, la forma más simple de eliminar la información de una mesa es esperar a que expire automáticamente (24 horas) o dejar de compartir el código de esa mesa.

Si tienes alguna solicitud relacionada con tus datos, contáctanos usando la información en la sección 9.

---

## 7. Privacidad de menores

TicketSplit no está dirigida a niños menores de 13 años y no recopilamos intencionalmente información de menores de 13 años. Si eres padre o madre y crees que tu hijo nos ha proporcionado información sin tu consentimiento, contáctanos para eliminarla.

---

## 8. Cambios a esta política

Podemos actualizar esta Política de Privacidad ocasionalmente. Si hacemos cambios importantes, actualizaremos la fecha al inicio de este documento. Te recomendamos revisar esta página periódicamente.

---

## 9. Contacto

Si tienes preguntas sobre esta Política de Privacidad, puedes escribirnos a:

**Correo:** ticketsplit01@gmail.com

---

<br>

# TicketSplit — Privacy Policy (English)

**Last updated:** August 20, 2026

This Privacy Policy explains how TicketSplit ("the App", "we") collects, uses, and protects information when you use our mobile app. By using TicketSplit, you agree to the practices described here.

## Quick summary
- **No account required.** We don't ask for email, password, or your real name.
- **Receipt photos never leave your phone.** Text recognition happens entirely on-device.
- **Table data is automatically deleted after 24 hours.**
- **We show ads** through Google AdMob to keep the app free.
- **Names you type** to identify each person at the table are stored temporarily so the bill can be split; they can be nicknames, not necessarily your real name.

## Information we collect
**Information you enter:** bill subtotal, tax, tip, items, and the names/nicknames you type for each participant, plus your selected tax state/jurisdiction. Stored in Google Firebase / Cloud Firestore under a table code and **automatically deleted 24 hours after the table is created**.

**Receipt photos:** processed **entirely on your device** using Google ML Kit on-device text recognition. **The image is never uploaded to our servers or any third party.** It's temporarily cached during processing and then discarded.

**Anonymous device identifiers:** we use **Firebase Authentication in anonymous mode** to assign your device a random identifier so the table can sync between participants — not linked to your name, email, or other personally identifiable information. For advertising, Google AdMob may collect your device's **advertising identifier** and ad interaction data, per its own privacy policy.

**Diagnostics:** we use **Firebase Crashlytics** for crash reports and **Firebase App Check** to verify requests come from a legitimate install of the app. These may collect technical device information but not personally identifiable information.

**What we do NOT collect:** your legal name, email address, phone number, GPS location, contacts, payment information, or any banking/card data.

## How we use information
Only to: sync a table's bill in real time between participants, calculate subtotal/tax/tip/per-person totals correctly, show ads to keep the app free, detect and fix bugs, and prevent abuse of our database. We do not sell your information to third parties.

## Third-party services
Google Firebase (Firestore, Authentication), Firebase Crashlytics, Firebase App Check / Google Play Integrity, Google AdMob, Google ML Kit, and Google User Messaging Platform (UMP) — see section 4 above for each service's privacy policy link (same services apply in English).

## Data retention
Table data is automatically deleted **24 hours** after creation. Your device also locally stores, for up to 24 hours, a "recent tables" list so you can return without remembering the code; you can clear this from your device.

## Your rights
Since TicketSplit doesn't create user accounts or link data to your identity, the simplest way to remove a table's information is to let it expire automatically (24 hours) or stop sharing that table's code. For any data-related request, contact us below.

## Children's privacy
TicketSplit is not directed at children under 13 and we do not knowingly collect information from children under 13.

## Changes to this policy
We may update this Privacy Policy occasionally. We'll update the date at the top of this document for material changes.

## Contact
Questions about this Privacy Policy? Email us at: **ticketsplit01@gmail.com**
