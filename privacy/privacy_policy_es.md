# Política de Privacidad — BabyCare+

**Última actualización:** 13 de septiembre de 2026

Esta Política de Privacidad describe cómo la aplicación **BabyCare+** ("nosotros", "la app") recopila, utiliza y protege la información de los usuarios. Al instalar y utilizar la app, usted acepta las prácticas descritas en este documento.

---

## 1. Quiénes somos

- **Responsable del tratamiento:** Murilo Chechá
- **Email de contacto:** muchecha@gmail.com
- **App:** BabyCare+
- **Plataforma:** Android (Google Play Store)

---

## 2. Edad mínima

BabyCare+ está destinada exclusivamente a **adultos mayores de 18 años** (padres, madres o cuidadores). La app **no está destinada a ser utilizada por niños**. No recopilamos intencionalmente datos de menores de 18 años.

En particular, no nos dirigimos a menores de 13 años y no recopilamos intencionalmente datos personales de menores de 13 años. Si tomamos conocimiento de que hemos recopilado datos personales de un menor de 13 años sin verificación del consentimiento parental, tomaremos medidas para eliminar esa información de nuestros servidores.

---

## 3. Datos que recopilamos

### 3.1 Datos que el usuario proporciona directamente
- **Cuenta:** email, nombre y foto de perfil obtenidos a través de Google Sign-In.
- **Datos del bebé:** nombre, sexo, fecha de nacimiento, foto, relación familiar (madre, padre, niñera, etc.), color del marco.
- **Registros de actividad:** sueño, lactancia, biberón, sólidos, pañal, baño, llanto, hospital, notas, fotos del diario, etc.
- **Mediciones:** peso, altura, perímetro cefálico, temperatura.
- **Salud:** vacunas administradas, medicamentos (píldoras) tomados.
- **Miembros de la familia:** invitaciones enviadas/aceptadas entre cuidadores que comparten el cuidado del mismo bebé.
- **Recordatorios:** horarios y mensajes personalizados de notificaciones configuradas por el usuario.

### 3.2 Datos recopilados automáticamente
- **Identificadores publicitarios (Google Ad ID)** y dirección IP, recopilados por el SDK de Google Mobile Ads para servir publicidad.
- **Registros de errores** anonimizados, para diagnosticar bugs.

### 3.3 Datos que **no** recopilamos
- Localización GPS.
- Contactos del dispositivo.
- Historial de llamadas o SMS.
- Micrófono.

---

## 4. Cómo almacenamos los datos

- **Backend:** los datos se almacenan en [Supabase](https://supabase.com), una plataforma de base de datos PostgreSQL con cifrado en reposo (AES-256) y en tránsito (TLS 1.2+).
- **Localización de los servidores:** UE/EE.UU. (según la región del proyecto Supabase).
- **Acceso:** solo el usuario autenticado y los miembros que él haya invitado explícitamente a la "familia" del bebé pueden acceder a los datos de ese bebé. Aplicamos Row Level Security (RLS) en Supabase para garantizar este aislamiento.
- **Caché local:** algunos datos se guardan localmente en el dispositivo a través de SharedPreferences y SQLite para funcionamiento sin conexión.

---

## 5. Cómo utilizamos los datos

- Mostrar la línea de tiempo de actividades del bebé.
- Sincronizar datos entre dispositivos del mismo cuidador y entre cuidadores invitados.
- Enviar notificaciones locales basadas en los recordatorios configurados por el usuario (estas notificaciones **no** salen del dispositivo).
- Servir publicidad (banner e intersticial) a través de Google AdMob — necesario para mantener la versión gratuita.

No vendemos, alquilamos ni compartimos sus datos personales con terceros con fines de marketing.

---

## 6. Compartir datos con terceros

| Servicio | Propósito | Datos compartidos |
|---|---|---|
| **Supabase** | Almacenamiento de datos | Todos los datos de la cuenta y del bebé |
| **Google Sign-In** | Autenticación | Email, nombre, foto de perfil |
| **Google AdMob** | Publicidad | Ad ID, IP, datos técnicos del dispositivo |

Enlaces a las políticas de privacidad de los terceros:
- Supabase: https://supabase.com/privacy
- Google: https://policies.google.com/privacy

---

## 7. Sus derechos (LGPD / RGPD)

Tiene derecho a:
- **Acceder** a los datos que tenemos sobre usted.
- **Rectificar** datos incorrectos.
- **Eliminar** su cuenta y todos los datos asociados.
- **Exportar** sus datos en un formato legible.
- **Oponerse** al tratamiento, retirando su consentimiento en cualquier momento.

Para ejercer cualquiera de estos derechos, envíe un email a **muchecha@gmail.com** con la frase "Solicitud LGPD/RGPD" en el asunto y el email asociado a la cuenta. Respondemos en hasta 30 días.

---

## 8. Eliminación de cuenta

Puede eliminar su cuenta de dos formas:

1. **Dentro de la app:** vaya a *Ajustes → Eliminar cuenta*. La eliminación es inmediata y borra permanentemente su cuenta, los bebés que registró, actividades, recordatorios y fotos asociadas. Si es dueño de un bebé compartido con otros miembros de la familia, debe eliminarlos antes de poder eliminar la cuenta, para no borrar su historial sin aviso.
2. **Por email:** enviando un mensaje a **muchecha@gmail.com** con el asunto "Eliminar cuenta", incluyendo el email de la cuenta. Confirmaremos la eliminación en hasta **15 días hábiles**.

---

## 9. Cookies y tecnologías similares

La app utiliza almacenamiento local (SharedPreferences, SQLite) únicamente con fines de funcionamiento sin conexión y caché. No utilizamos cookies de seguimiento de terceros más allá de lo necesario por el SDK de Google AdMob.

---

## 10. Seguridad

Adoptamos medidas técnicas y organizativas adecuadas para proteger los datos personales:
- Comunicación cifrada (HTTPS/TLS).
- Autenticación OAuth2 a través de Google.
- Row Level Security en Supabase para garantizar el aislamiento entre usuarios.
- Acceso al backend restringido por claves API.

A pesar de estas medidas, ningún sistema es 100% seguro. En caso de incidente de seguridad que afecte sus datos, lo comunicaremos en un plazo de 72 horas conforme a la ley.

---

## 11. Cambios en esta política

Nos reservamos el derecho de actualizar esta Política. Cambios significativos se notificarán a través de la app y/o email. Continuar usando la app después de una actualización constituye aceptación de la nueva versión.

---

## 12. Contacto

Para cualquier cuestión sobre esta Política de Privacidad o sobre el tratamiento de sus datos:

**Email:** muchecha@gmail.com
