---
title: NotePatch Política de Privacidad
---

# NotePatch — Política de Privacidad

**Fecha de vigencia:** 2026-04-07
**Última actualización:** 2026-04-11

Esta Política de Privacidad describe cómo NotePatch ("nosotros" o "la app") gestiona la información cuando usas la aplicación NotePatch para iOS.

## Nuestra postura sobre la privacidad

NotePatch está diseñado para ser **privado por defecto**. Las funciones principales — escaneo, recorte, máscara e impresión — funcionan completamente sin conexión y sin cuenta. No recopilamos, transmitimos ni compartimos datos personales a menos que elijas usar una función que lo requiera.

## Información que NO recopilamos

- **No** recopilamos identificadores personales (nombre, correo, teléfono, ID de cuenta).
- **No** recopilamos identificadores de dispositivo (IDFA, IDFV, ID publicitario).
- **No** rastreamos tu uso de la app.
- **No** utilizamos servicios de analítica, informes de errores ni telemetría.
- **No** incluimos SDKs de publicidad ni de seguimiento.
- **No** accedemos a tus contactos, calendario, ubicación, micrófono ni a datos ajenos a las funciones principales.

## Información que proporcionas a la app (solo almacenamiento local)

Para funcionar, NotePatch necesita acceso a ciertas funciones del dispositivo. Todos los datos permanecen exclusivamente en tu dispositivo:

| Permiso | Para qué se necesita | Destino de los datos |
|---------|---------------------|---------------------|
| **Cámara** | Escanear notas manuscritas o páginas con el escáner de documentos | Se procesan en el dispositivo. Nunca se suben. |
| **Fototeca (lectura)** | Importar fotos y capturas existentes para crear parches | Solo se referencia el identificador del recurso en la fototeca. |
| **Fototeca (escritura)** | (Opcional) Guardar parches procesados en la fototeca | Solo ocurre cuando tú inicias la exportación. |
| **Impresora (AirPrint)** | Enviar el PDF generado a una impresora cercana por red local | Solo se envía a la impresora que selecciones. |

## Reconocimiento de texto con IA de Smart Text (función Pro)

NotePatch ofrece dos modos de reconocimiento de texto:

### OCR en dispositivo (gratuito)

El OCR en dispositivo utiliza el framework Vision de Apple para extraer texto de imágenes. Todo el procesamiento ocurre localmente. **No se transmite ningún dato.**

### Reconocimiento IA (solo Pro)

Cuando eliges el reconocimiento IA, la imagen seleccionada se envía a una API en la nube segura de terceros para la extracción de texto.

- **Qué se envía:** Únicamente la imagen que seleccionaste para el reconocimiento.
- **Cómo se procesa:** La imagen se usa exclusivamente para la extracción de texto.
- **Retención de datos:** El proveedor de la API **no almacena, no registra ni usa la imagen para entrenar modelos**.
- **Cuándo ocurre:** Solo cuando pulsas la opción de reconocimiento IA. Nunca ocurre de forma automática ni en segundo plano.

La app no realiza ninguna otra solicitud de red. NotePatch funciona con normalidad en modo avión — el reconocimiento IA simplemente muestra un mensaje de sin conexión.

## Suscripción y facturación

Las suscripciones a NotePatch Pro las gestiona íntegramente Apple a través de la App Store. No recopilamos ni tenemos acceso a tu información de pago, datos de tarjeta de crédito ni Apple ID.

## Cómo almacenamos tus datos

- Todas las notas, parches, historial de edición y preferencias se almacenan **solo en tu dispositivo**, usando los frameworks de almacenamiento local de Apple (SwiftData y UserDefaults).
- Los datos solo salen de tu dispositivo cuando:
  - Imprimes en una impresora que hayas seleccionado (enviado solo por red local).
  - Compartes un PDF usando la función de compartir de iOS.
  - Usas el reconocimiento IA (Pro), que envía la imagen seleccionada a una API en la nube.

## Privacidad infantil

NotePatch no recopila intencionadamente información de ninguna persona, incluidos menores de 13 años. La app es apta para el público general.

## Tus derechos

Dado que NotePatch no recopila ni almacena datos personales de nuestra parte, no hay datos que podamos acceder, exportar, corregir o eliminar. Eliminar la app de tu dispositivo borra todo el contenido de NotePatch almacenado localmente.

## Cambios en esta política

Si cambiamos la forma en que la app gestiona los datos, actualizaremos esta política con una nueva fecha de "Última actualización". Los cambios importantes se reflejarán en las notas de actualización de la App Store.

## Contacto

Si tienes preguntas sobre esta política de privacidad, contacta con nosotros en:

**Correo electrónico:** ai.neocai@gmail.com

---

*Las funciones principales de NotePatch son completamente offline y privadas. Los datos solo salen de tu dispositivo cuando eliges imprimir, compartir o usar el reconocimiento IA.*

[← Volver a NotePatch](./) · [foxineo Legal](../)
