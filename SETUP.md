# Configuración del ambiente

## Objetivo

Preparar una cuenta de laboratorio para ejecutar las cuatro prácticas en Outlook clásico, nuevo Outlook u Outlook en la Web con M365 Copilot (Basic), con acceso estándar.

## 1. Confirmar la cuenta y la licencia

1. Inicie sesión con una cuenta profesional o educativa.
2. Confirme que la cuenta tiene una suscripción elegible de Microsoft 365. Para este curso se utilizará **M365 Copilot (Basic)**, identificado en la interfaz como acceso básico o estándar, sin requerir la experiencia Premium.
3. Confirme que el buzón principal está alojado en **Exchange Online**.
4. Confirme que la cuenta aparece en Microsoft Entra ID.
5. Abra Outlook y busque el botón **Copilot** o **Copilot Chat**.

> **Comprobación:** al abrir Copilot Chat debe aparecer un cuadro para escribir indicaciones dentro de Outlook.

> **Importante:** Microsoft distingue entre Copilot Chat incluido en suscripciones elegibles y el complemento Microsoft 365 Copilot. Las prácticas están diseñadas para funcionar con M365 Copilot (Basic) y ofrecen alternativas cuando un botón especializado no está disponible.

## 2. Preparar Outlook

### Outlook clásico para Windows

1. Actualice Microsoft 365 Apps a una versión admitida.
2. Abra Outlook clásico con la cuenta de laboratorio.
3. Cree una carpeta llamada `LAB_COPILOT_OUTLOOK`.
4. Cree una categoría llamada `Laboratorio Copilot`.
5. Verifique que Copilot Chat esté visible.

### Nuevo Outlook para Windows

1. Abra nuevo Outlook con la cuenta de laboratorio.
2. Cree una carpeta llamada `LAB_COPILOT_OUTLOOK`.
3. Cree una categoría llamada `Laboratorio Copilot`.
4. Verifique que Copilot Chat esté visible.
5. Confirme que existe una opción de importación de archivos `.eml` en Configuración. La ubicación puede mostrarse como **Configuración > General > Importar** o **Configuración > Archivos > Importar**, según la compilación.

### Outlook en la Web

1. Abra Outlook en la Web con la cuenta de laboratorio.
2. Cree una carpeta llamada `LAB_COPILOT_OUTLOOK`.
3. Cree una categoría llamada `Laboratorio Copilot`.
4. Verifique que Copilot Chat esté visible.
5. Confirme que puede arrastrar un archivo `.eml` al panel de lectura para abrirlo.

## 3. Preparar los archivos del curso

1. Descargue y extraiga el repositorio completo.
2. Mantenga la estructura de carpetas sin cambiar los nombres.
3. Use los archivos de `Allfiles` únicamente con cuentas de laboratorio.
4. No reemplace los datos ficticios por información real o sensible.

## 4. Cargar archivos `.eml`

### Ruta A. Outlook clásico

1. Abra la carpeta `LAB_COPILOT_OUTLOOK`.
2. Desde el Explorador de archivos, arrastre los `.eml` a la lista de mensajes de la carpeta.
3. Si el arrastre no funciona, abra cada `.eml` y reenvíelo a su propia cuenta de laboratorio con el mismo asunto.

> **Comprobación:** el mensaje debe aparecer dentro del buzón principal para que Copilot pueda usar el contexto del correo.

### Ruta B. Nuevo Outlook

1. Abra **Configuración**.
2. Busque **Importar**.
3. Seleccione la carpeta que contiene los `.eml` de la práctica.
4. Seleccione la cuenta y la carpeta `LAB_COPILOT_OUTLOOK` como destino.
5. Ejecute la importación.

> **Nota:** la importación masiva del nuevo Outlook solo procesa archivos `.eml` ubicados en el nivel superior de la carpeta seleccionada.

### Ruta C. Outlook en la Web

1. Arrastre un `.eml` al panel de lectura para abrirlo.
2. Para que el mensaje quede dentro del buzón, use **Reenviar** y envíelo a su propia cuenta de laboratorio.
3. Conserve el asunto original para facilitar la agrupación de conversaciones.

## 5. Ruta de respaldo con archivos adjuntos

Los archivos `.docx` y el `.xlsx` de respaldo reproducen íntegramente la información de los `.eml`. Cuando la importación de correo no sea posible:

1. Abra Copilot Chat en Outlook.
2. Adjunte el `.docx` o `.xlsx` de respaldo indicado en la guía.
3. Use el prompt incluido en la misma guía.
4. No adjunte simultáneamente el `.eml`, el `.docx` y el `.xlsx`; seleccione una sola ruta.
5. Verifique que Copilot indique que está usando el archivo adjunto como contexto.

## 6. Validar Copilot Chat

Copie este prompt de prueba:

```text
Indica qué aplicación estoy usando y confirma si puedes ayudarme a redactar correos, resumir mensajes y administrar reuniones desde Outlook. No realices ninguna acción todavía.
```

> **Comprobación:** Copilot debe responder sin intentar enviar mensajes ni modificar el calendario.

## 7. Problemas frecuentes

| Situación | Acción recomendada |
| --- | --- |
| No aparece Copilot Chat | Cierre sesión, vuelva a iniciar, compruebe licencia, directivas y asignación de la cuenta. |
| No aparece Borrador, Entrenamiento o Resumir | Use la ruta mediante Copilot Chat incluida en la guía. |
| El correo `.eml` se abre, pero Copilot no lo encuentra | Reenvíelo a su cuenta de laboratorio para incorporarlo al buzón, o use el `.docx` de respaldo. |
| Los mensajes no se agrupan como conversación | Active la vista de conversación y confirme que mantienen el mismo asunto. |
| Programar desde el hilo no aparece en Outlook clásico | Use Copilot Chat para crear la reunión. Esta función especializada no está disponible en Outlook clásico. |
| Prepararse para una reunión no aparece | Use el contexto y el prompt de preparación incluidos en la guía. |
| Copilot agrega datos no proporcionados | Detenga la acción, compare con el escenario y solicite una versión que use únicamente la información suministrada. |

## 8. Limpieza general

Al terminar el curso:

1. Elimine los correos de laboratorio.
2. Elimine las reglas creadas durante la práctica.
3. Elimine la categoría `Laboratorio Copilot` si no se utilizará después.
4. Cancele las reuniones de prueba.
5. Elimine la carpeta `LAB_COPILOT_OUTLOOK` cuando esté vacía.

## Referencias oficiales

- https://learn.microsoft.com/es-es/microsoft-365/copilot/microsoft-365-copilot-chat-requirements
- https://learn.microsoft.com/es-es/microsoft-365/copilot/microsoft-365-copilot-minimum-requirements
- https://support.microsoft.com/es-ES/Outlook/mail/open-eml-msg-and-oft-files-in-new-outlook-and-outlook-on-the-web
- https://support.microsoft.com/es-ES/Outlook/bulk-import-eml-files-in-new-outlook
- https://support.microsoft.com/es-ES/Outlook/getstarted/feature-comparison-between-new-outlook-and-classic-outlook
