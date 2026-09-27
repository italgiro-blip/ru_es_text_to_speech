🇷🇺 Traductor Ruso B1 — Pro
Traductor bidireccional Español ⇄ Ruso pensado para estudiantes de nivel B1. Incluye traducción automática, pronunciación con voz nativa, dictado por voz, análisis gramatical y lectura en alfabeto español.

✨ Características
🔄 Traducción bidireccional: Español ➔ Ruso y Ruso ➔ Español.

🔤 Lectura en alfabeto español: el ruso se muestra transliterado (ej. Привет → privét) para que puedas leerlo sin saber cirílico.

🈳 Cirílico original visible: debajo de cada traducción se muestra el texto real en cirílico.

🔊 Síntesis de voz (TTS): reproduce la traducción con voz nativa y control de velocidad (0.7x – 1.0x).

🎙️ Dictado por voz (STT): reconoce tu voz en español o ruso según la dirección elegida.

📚 Análisis gramatical B1: consejos sobre casos, aspecto verbal y verbos de movimiento.

💾 Caché local: las traducciones repetidas se recuperan al instante desde localStorage.

📖 Diccionario local: frases comunes (saludos, cortesía) traducidas con precisión manual.

🕓 Historial reciente: se guardan las últimas 3 traducciones.

📋 Copiar al portapapeles: un clic para copiar el resultado.

🎨 Interfaz moderna con Tailwind CSS, responsive y sin dependencias externas pesadas.

🚀 Uso
Descarga o copia el archivo index.html.

Ábrelo en Google Chrome o Microsoft Edge (necesarios para el reconocimiento de voz).

Selecciona la dirección de traducción:

Español ➔ Ruso (con lectura en español)

Ruso ➔ Español

Escribe, pega o dicta una frase.

Pulsa Traducir y Analizar.

Lee el resultado, escúchalo con 🔊 y revisa los consejos gramaticales.

🧠 Cómo funciona la transliteración
La función transliterarRuso() convierte el cirílico al alfabeto español siguiendo reglas fonéticas aproximadas:

Cirílico	Lectura en español	Ejemplo
а / э	a / e	мама → mama
е	ye	есть → yest'
ё	yo	ёлка → yolka
ж	zh	жена → zhiená
х	j (jota suave)	хорошо → jarashó
ц	ts	цена → tsiená
ч	ch	час → chas
ш	sh	школа → shkola
щ	shch	щи → shchi
ы	y	мы → my
ь / ъ	(no se pronuncia)	—
ю	yu	юг → yug
я	ya	я → ya
⚠️ Nota: es una lectura orientativa, no una transcripción IPA. No aplica reducción vocálica ni ensordecimiento final (por ejemplo, хорошо se lee idealmente jarashó, aunque la transliteración base da joroshó). Para nivel B1 es más que suficiente.

🎧 Sobre el audio
El TTS siempre recibe el texto en cirílico real, no la transliteración, para que la voz rusa lo pronuncie correctamente.

Si tu sistema no tiene voz rusa instalada:

Windows: instala el paquete de idioma ruso en Configuración → Hora e idioma → Voz.

macOS: añade la voz Milena en Ajustes → Accesibilidad → Contenido leído → Voces del sistema.

Android: añade ruso en Ajustes → Sistema → Idiomas → Salida de texto a voz.

🎙️ Sobre el dictado por voz
Funciona solo en Chrome y Edge (usa la Web Speech API).

El idioma de reconocimiento cambia automáticamente según la dirección:

ES ➔ RU → dicta en español.

RU ➔ ES → dicta en ruso.

Requiere conexión a internet (el reconocimiento se hace en la nube de Google).

🌐 Servicio de traducción
El traductor usa el endpoint público de Google Translate:

text
https://translate.googleapis.com/translate_a/single?client=gtx&sl=...&tl=...&dt=t&q=...
✅ No requiere API key.

⚠️ Es un endpoint no oficial: puede cambiar o bloquearse sin aviso.

🔁 Si falla, puedes sustituirlo por:

LibreTranslate (https://libretranslate.com/translate)

MyMemory (https://api.mymemory.translated.net/get)

DeepL API Free (requiere key)

