<div align="center">

# Midnight Suite

**Las herramientas de vídeo de Midnight Group para festivales y rodajes · by Puig**

### [⬇︎ Descargar para Mac](https://github.com/paupuig92/midnight-suite/releases/latest/download/Midnight-Suite.dmg)

Mac con chip Apple (M1 o posterior) · macOS 14 o posterior · se actualiza sola · versión actual: **4.0**

[Instalación](#instalación) · [Requisitos](#requisitos) · [Herramientas](#herramientas) · [Seguridad](#seguridad) · [Ayuda](#ayuda) · [Novedades](#novedades)

<img src="docs/img/01-inicio.jpg" alt="Inicio de Midnight Suite" width="100%">

</div>

Una app para Mac con todo lo que hace falta en un rodaje o en un festival: copiar tarjetas sin riesgo, preparar los discos, sincronizar las cámaras, subtitular, comprimir y mucho más. No hace falta saber de códecs ni usar la terminal: arrastras el archivo, pulsas un botón y listo.

| 🔒 Todo pasa en tu Mac | 🛡️ El original no se toca | 🔄 Se actualiza sola |
|---|---|---|
| Tus vídeos no se suben a internet. | Cada herramienta crea un archivo nuevo. | Sale un aviso y se instala con un clic. |

## Instalación

Unos 5 minutos, y solo una vez.

1. **Comprueba tu Mac.** Menú Apple › **Acerca de este Mac**: tiene que poner chip Apple (M1, M2, M3…) y macOS 14 o posterior.
2. **Descarga** [Midnight-Suite.dmg](https://github.com/paupuig92/midnight-suite/releases/latest/download/Midnight-Suite.dmg). El enlace siempre baja la última versión.
3. **Haz doble clic en el .dmg** y arrastra el icono de Midnight Suite a la carpeta **Aplicaciones**. Después, expulsa el disco ⏏︎.
4. **Ábrela desde Aplicaciones.** La primera vez, el Mac avisa de que no puede comprobar la app. Es normal ([por qué](#seguridad)) y solo pasa una vez:
   - **macOS 15 o posterior:** ve a **Ajustes del Sistema › Privacidad y seguridad**, baja hasta el final, pulsa **Abrir igualmente** y confirma. Vuelve a abrir la app.
   - **macOS 14:** en Aplicaciones, clic derecho sobre la app › **Abrir** › **Abrir**.
5. **«Antes de empezar».** Pulsa **Activar los avisos** e **Instalar lo que falta**. La primera vez que copies una tarjeta, pulsa **Permitir** o el DIT no podrá leerla.

> [!WARNING]
> **No pulses «Trasladar a la papelera»** en el aviso del paso 4. Ciérralo con el otro botón.

> [!TIP]
> Los complementos incluyen el modelo de los Subtítulos (hasta 1,6 GB) y Gyroflow (unos 90 MB). Mejor instalarlos con buena conexión, antes de salir de la oficina.

> [!TIP]
> **¿Portátil solo para el festival?** En **Ajustes › Herramientas visibles** elige el perfil **Festival**: la barra lateral deja solo lo que hace falta para el DIT.

<details>
<summary><b>Si algo no va bien</b></summary>

- **No aparece «Abrir igualmente».** Intenta abrir la app, cierra el aviso y, justo después, ve a Privacidad y seguridad. En macOS 15 o posterior, el clic derecho › Abrir ya no sirve.
- **He pulsado «Trasladar a la papelera».** No pasa nada: vuelve a descargar el .dmg y repite desde el paso 3.
- **Pide moverla a Aplicaciones.** Pulsa **Moverla a Aplicaciones**, o ciérrala y arrástrala tú (si pregunta, **Reemplazar**). Las actualizaciones solo se instalan si la app está ahí.
- **Una herramienta tiene un punto amarillo o rojo.** Le falta un complemento, un permiso o memoria. Haz clic en el punto y se abre el Ajuste que lo arregla.
- **Gyroflow de la App Store.** No sirve: instálalo desde el propio Estabilizador.

</details>

## Requisitos

| | |
|---|---|
| **Mac** | Solo chip Apple (M1 o posterior). Intel no es compatible. |
| **Sistema** | macOS 14 o posterior. El **Upscaler** necesita **macOS 26**. |
| **Memoria** | Con 8 GB funcionan todas, una pesada cada vez. Con 16 GB o más, varias a la vez. |
| **Idioma** | Castellano y catalán (**Ajustes › General › Idioma**). |

<details>
<summary><b>Qué pide cada herramienta</b></summary>

| Herramienta | RAM mínima | Para varias a la vez | Además necesita |
|---|---|---|---|
| DIT · Discos · Comparador · Info de clips | 4 GB | 8 GB | — |
| Sincronizar | 4 GB | 8 GB | ffmpeg (se instala solo) |
| Separar clips | 4 GB | 8 GB | Espacio libre: tanto como el máster |
| Conversor | 4 GB | 8 GB | ffmpeg |
| Downloader | 4 GB | 8 GB | yt-dlp, deno y ffmpeg |
| Subtítulos | 8 GB | 16 GB | ffmpeg · modelo de Whisper (hasta 1,6 GB) · 3 GB libres para los modelos |
| Compresor | 8 GB | 16 GB | ffmpeg recomendado · DaVinci Resolve o Blackmagic RAW Player (gratuitos) para BRAW · 50 GB libres recomendados |
| Reparador | 8 GB | 16 GB | ffmpeg (se instala solo) |
| Estabilizador | 8 GB | 16 GB | Gyroflow · 50 GB libres recomendados |
| Upscaler | 8 GB | 16 GB | macOS 26 · M3 o un Pro/Max/Ultra recomendado · 50 GB libres recomendados |
| Audio | 8 GB | 16 GB | Modelo de voz y música (se descarga solo la primera vez) |

**Semáforo de memoria:** 🟢 todo normal · 🟡 una sola herramienta cada vez · 🔴 no empieza ninguna (cierra otras apps).
**Modo boost ⚡:** da toda la potencia a una sola herramienta; las demás esperan en la cola.
**Interfaz ligera:** en **Ajustes › Apariencia**, sin cristal ni animaciones, para gastar menos batería.

</details>

## Herramientas

Están agrupadas como en la barra lateral de la app: **Rodaje** (en el festival), **Edición** (para Final Cut y DaVinci) y **Taller** (el resto, en la oficina). Novedades, Guía, Acerca de y Nivel están abajo del todo.

> [!CAUTION]
> **Nunca borres una tarjeta** hasta que el DIT diga **«Ya puedes borrarla»**.

### 🎬 Rodaje

<table>
<tr>
<td width="50%" valign="top">
<img src="docs/img/02-dit.jpg" alt="DIT" width="100%"><br>
<b>💾 DIT</b><br>
Copia las tarjetas a uno o varios discos y comprueba que cada copia es idéntica.
<details><summary><b>Cómo se usa</b></summary>

1. Pon la tarjeta en el lector. Aparece sola a la izquierda.
2. Arrastra a la derecha los discos donde quieres guardarla.
3. Pulsa **Copiar y verificar** y espera el aviso verde **«Ya puedes borrarla»**.

</details>
</td>
<td width="50%" valign="top">
<img src="docs/img/18-discos.jpg" alt="Discos" width="100%"><br>
<b>🗄️ Discos</b><br>
Los discos conectados de un vistazo: qué tienen, cuánto espacio queda, su salud y su velocidad.
<details><summary><b>Cómo se usa</b></summary>

1. Conecta los SSD. Salen solos, con su formato y el espacio libre.
2. **Prueba de velocidad** te dice si un disco sirve para el DIT. **Primeros auxilios** busca errores y los repara.
3. **Formatear…** deja un SSD listo para el festival (exFAT, se lee en Mac y Windows). Hay que escribir el nombre para confirmar, y nunca deja tocar el disco interno, un NAS, un disco que esté usando el DIT ni uno con copias del DIT de las últimas 24 h.

</details>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<img src="docs/img/04-info-de-clips.jpg" alt="Info de clips" width="100%"><br>
<b>ℹ️ Info de clips</b><br>
Muestra cámara, ISO, timecode y audio de cada clip, y avisa de lo que falla antes de editar.
<details><summary><b>Cómo se usa</b></summary>

1. Arrastra los clips o la carpeta de la tarjeta.
2. Mira la **tabla**: en amarillo, lo que no coincide con el resto.
3. Pulsa un clip para ver el detalle, o **Analizar todo**. Con **Exportar** sacas JSON, CSV o PDF.

</details>
</td>
<td width="50%" valign="top">
<img src="docs/img/03-comparador.jpg" alt="Comparador" width="100%"><br>
<b>🔍 Comparador</b><br>
Dice si dos carpetas tienen exactamente los mismos archivos.
<details><summary><b>Cómo se usa</b></summary>

1. **A**: la carpeta original (por ejemplo, la tarjeta).
2. **B**: la copia que quieres comprobar.
3. Pulsa **Comparar**: rojo, falta o está mal; amarillo, tamaño distinto; verde, bien. El ✅ verde solo sale si marcas **Verificar el contenido (checksum)**. Si el disco lleva el informe del DIT, lo usa para comprobarlo desde cualquier Mac.

</details>
</td>
</tr>
</table>

<details>
<summary><b>Lo esencial del DIT</b></summary>

- La tarjeta se lee una sola vez y se escribe en todos los discos a la vez, con checksum xxHash64 (y MD5 si lo activas).
- Antes de dar la tarjeta por buena, comprueba que cada clip se abre de verdad.
- Con dos discos o más, «Ya puedes borrarla» solo sale cuando hay **dos copias verificadas en dos discos distintos**. Dos particiones del mismo SSD cuentan como uno.
- Nunca sobrescribe nada. Si algo no se ha podido copiar o leer, lo dice y la tarjeta **no** se da por buena.
- Si el lector deja de responder o sacas un disco a media copia, se detiene y avisa: «NO formatees la tarjeta».
- Copiar a un NAS por red (SMB) también es seguro: al terminar cada clip, comprueba que el NAS lo deja leer.
- Cada copia genera un informe PDF sellado, con los archivos, sus checksums y una miniatura de cada clip. También se guarda en cada disco.
- **«¿Listo para el festival?»** mira si tienes 2 discos y su formato, y puede probarlos.

</details>

### ✂️ Edición

<table>
<tr>
<td width="50%" valign="top">
<img src="docs/img/19-sincronizar.jpg" alt="Sincronizar" width="100%"><br>
<b>🎚️ Sincronizar</b><br>
Sincroniza todas las cámaras de una noche con el audio bueno, y te lo deja montado en DaVinci o Final Cut. En sets de DJ, también corta la multicámara siguiendo la música.
<details><summary><b>Cómo se usa</b></summary>

1. **Añadir carpeta** de cada cámara y la del audio bueno (la grabadora o la mesa). Con una Zoom, une Tr1 y Tr2 en un WAV estéreo sin pérdida, sin tocar los originales.
2. Pulsa **Sincronizar**. Coloca cada clip por timecode, hora de grabación y sonido (precisión de ±½ fotograma) y te dice cuánto falta. Aguanta clips de 5 a 12 h.
3. Revisa la línea de tiempo (Espacio para escuchar, M/S para mute/solo). Los clips dudosos salen marcados. Después, **Abrir en DaVinci** (multicámara a la hora real, o con **Cortes automáticos**: Tranquilo, Normal, Bestia o Automático) o **Abrir en Final Cut**.

</details>
</td>
<td width="50%" valign="top">
<img src="docs/img/10-subtitulos.jpg" alt="Subtítulos" width="100%"><br>
<b>💬 Subtítulos</b><br>
Subtítulos automáticos para Final Cut, DaVinci y Premiere. En Final Cut, con la animación <b>Midnight Sub v1</b>: cada palabra aparece cuando se dice, 100 % editable.
<details><summary><b>Cómo se usa</b></summary>

1. Arrastra el **proyecto** desde Final Cut (o cualquier vídeo o audio) y elige el programa: Final Cut, DaVinci o Premiere.
2. Elige el idioma (**Automático, catalán, castellano o inglés**) y pulsa **Analizar el audio**. Corrige lo que haga falta: las palabras dudosas salen en naranja.
3. Ajusta el estilo (letra, tamaño, color, posición, 1–2 líneas) con la vista previa en directo y pulsa **Abrir en Final Cut**: crea el proyecto e instala la plantilla solo. Para DaVinci y Premiere, SRT o TXT.

</details>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<img src="docs/img/12-separar-clips.jpg" alt="Separar clips" width="100%"><br>
<b>✂️ Separar clips</b><br>
Corta el máster de Final Cut en un archivo por clip, con su nombre y su timecode.
<details><summary><b>Cómo se usa</b></summary>

1. En Final Cut, exporta el proyecto en **ProRes** y el **XML** (Archivo › Exportar XML…).
2. Arrastra el XML y el máster a la ventana.
3. Pulsa **Separar**. Los clips salen en «Clips separados», junto al máster.

</details>
</td>
<td width="50%" valign="top">
</td>
</tr>
</table>

### 🛠️ Taller

<table>
<tr>
<td width="50%" valign="top">
<img src="docs/img/05-compresor.jpg" alt="Compresor" width="100%"><br>
<b>🗜️ Compresor</b><br>
Vídeos y fotos que ocupan mucho menos sin que se note, también BRAW y vídeos con transparencia.<br>
<sub>BRAW necesita DaVinci Resolve o Blackmagic RAW Player (gratuitos).</sub>
<details><summary><b>Cómo se usa</b></summary>

1. Arrastra vídeos o fotos.
2. Elige la calidad o el peso máximo (por ejemplo, 500 KB para una web). Haz clic en un clip para darle sus propios ajustes.
3. Pulsa **Comprimir**. Si algo no cuadra (duración, pistas de audio, timecode), la fila te avisa en naranja.

</details>
</td>
<td width="50%" valign="top">
<img src="docs/img/06-conversor.jpg" alt="Conversor" width="100%"><br>
<b>🔁 Conversor</b><br>
Cambia el tipo de archivo: MKV a MP4, vídeo a GIF, HEIC a JPG…
<details><summary><b>Cómo se usa</b></summary>

1. Arrastra los archivos.
2. Elige el formato (pestañas **Vídeo**, **Audio** o **Fotos**).
3. Pulsa **Convertir**. Si pone **«Sin recodificar»**, tarda segundos y no pierde calidad.

</details>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<img src="docs/img/09-reparador.jpg" alt="Reparador" width="100%"><br>
<b>🩹 Reparador</b><br>
Intenta arreglar vídeos y audios que no se abren, y te dice antes si se pueden salvar.
<details><summary><b>Cómo se usa</b></summary>

1. Arrastra el archivo (o una carpeta). La app te dice qué le pasa y si se puede salvar.
2. Si puedes, añade un **clip bueno de la misma cámara** como referencia.
3. Pulsa **Reparar**. Se crea una copia arreglada (`nombre_reparado`).

</details>
</td>
<td width="50%" valign="top">
<img src="docs/img/08-estabilizador.jpg" alt="Estabilizador" width="100%"><br>
<b>🚁 Estabilizador</b><br>
Estabiliza clips de dron, GoPro, Insta360 y cámaras de acción con su giroscopio.<br>
<sub>Usa Gyroflow: se instala con un botón, unos 90 MB.</sub>
<details><summary><b>Cómo se usa</b></summary>

1. Arrastra clips o carpetas. La app mira cuáles llevan datos del giroscopio (los que no, se pueden **Analizar la imagen**).
2. Elige el códec, el tamaño, la suavidad y el recorte.
3. Pulsa **Estabilizar** y verás cuánto falta. Con **Dos clips a la vez** va casi el doble de rápido.

</details>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<img src="docs/img/07-upscaler.jpg" alt="Upscaler" width="100%"><br>
<b>✨ Upscaler</b><br>
Hace vídeos y fotos más grandes y nítidos con IA.<br>
<sub>Necesita macOS 26.</sub>
<details><summary><b>Cómo se usa</b></summary>

1. Arrastra vídeos o fotos (pestaña **Vídeo** o **Fotos**).
2. Elige cuánto más grande (×2, ×4 o un tamaño concreto) y el **Estilo**: **Natural** (la IA de Apple, sin cambiar el aspecto) o **Limpio** (quita compresión y ruido, ideal para clips de IA).
3. Pulsa **Ampliar**. La app te dice antes cuánto tardará.

</details>
</td>
<td width="50%" valign="top">
<img src="docs/img/11-audio.jpg" alt="Audio" width="100%"><br>
<b>🎙️ Audio</b><br>
Limpia una voz, la deja como de estudio, la separa de la música o une Tr1 y Tr2 en estéreo. Sin internet y sin perder calidad (32 bits float se queda en 32 float).
<details><summary><b>Cómo se usa</b></summary>

1. Arrastra audios o vídeos (WAV, MP3, MP4, MOV…).
2. Elige **Limpieza de voz**, **Voz de estudio**, **Voz y música** o **Unir L/R**.
3. Pulsa el botón. Con 🎧 escuchas 5 s de prueba antes y después.

</details>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<img src="docs/img/13-downloader.jpg" alt="Downloader" width="100%"><br>
<b>⬇️ Downloader</b><br>
Descarga vídeo o música de YouTube, Instagram, TikTok, SoundCloud, Vimeo y más, también carruseles de fotos.<br>
<sub>Instagram y algunos vídeos piden iniciar sesión.</sub>
<details><summary><b>Cómo se usa</b></summary>

1. Pega el enlace en la caja.
2. Elige **vídeo** o **solo el audio** (entero o un trozo). En un carrusel, una diapositiva o todas.
3. Pulsa **Descargar**. Para Instagram, ten tu cuenta abierta en Chrome o Safari: la app usa esa sesión sola. Si un SoundCloud tiene DRM, te propone la misma canción de YouTube.

</details>
</td>
<td width="50%" valign="top">
</td>
</tr>
</table>

### Y además

<table>
<tr>
<td width="50%" valign="top">
<img src="docs/img/14-historial.jpg" alt="Historial" width="100%"><br>
<b>📋 Historial</b><br>
Todo lo que ha hecho la app, con informes en PDF y «¿Dónde está este clip?». Cada trabajo guarda una ficha con el Mac, el clip, los ajustes y el error real si falla.
<details><summary><b>Cómo se usa</b></summary>

**Copias del DIT** con su informe PDF · **Todas las herramientas**: trabajos y horas de cada una · **¿Dónde está este clip?** · **Copiar para Claude**: la ficha de un trabajo (o de todos los filtrados), lista para pegar y saber qué ha pasado.

</details>
</td>
<td width="50%" valign="top">
<p align="center"><img src="docs/img/17-barra-de-menus.jpg" alt="Barra de menús" width="70%"></p>
<b>🪽 Barra de menús</b><br>
Los trabajos en curso, «Volcar» para tarjetas nuevas y acceso rápido a las herramientas.
</td>
</tr>
<tr>
<td width="50%" valign="top">
<img src="docs/img/20-nivel.jpg" alt="Nivel" width="100%"><br>
<b>🏆 Nivel</b><br>
Ganas puntos usando la app: 10 niveles, insignias (y alguna sorpresa escondida 🕵️), horas por herramienta y tu año.
</td>
<td width="50%" valign="top">
<img src="docs/img/15-guia.jpg" alt="Guía" width="100%"><br>
<b>📖 Guía y Novedades</b><br>
Cada herramienta con sus pasos y un buscador (menú <b>Ayuda</b>, ⌘?, o el botón <b>?</b> de cada herramienta), y la historia completa de la app, versión a versión.
</td>
</tr>
</table>

## Actualizaciones

No hace falta volver a esta página. Cuando hay una versión nueva, sale un aviso en la app: pulsa **Actualizar** y se cierra, se actualiza y se vuelve a abrir. También puedes buscarla en **Midnight Suite › Buscar actualizaciones…**

Si hay una copia del DIT o una herramienta trabajando, la app espera a que termine.

## Seguridad

El Mac avisa la primera vez porque la app **no está notarizada por Apple** (hace falta una cuenta de desarrollador de pago). Esto es lo que sí tiene:

- **Actualizaciones firmadas** (Ed25519). La app solo descarga versiones de este GitHub y no instala nada que no esté firmado por Puig.
- **Comprueba que es la original** firmada por Midnight.
- **Vuelta atrás automática** si una versión nueva no arranca.
- **Informes del DIT sellados**: si alguien los cambia, se nota.
- **Complementos y programas externos comprobados** antes de usarlos.
- **Herramientas pesadas en un proceso aparte:** si una falla, la app y las copias del DIT siguen funcionando.

Descarga la app **solo desde esta página** o desde el enlace que te pase Puig.

## Ayuda

**¿Se sube algo a internet?** Tus vídeos, no. La app se conecta para buscar actualizaciones, descargar complementos y, en el Downloader, bajar lo que le pidas.

**¿Algo ha fallado?** Abre el **Historial**, elige lo que ha fallado, pulsa **Copiar para Claude** (o **Copiar el detalle**) y envíaselo a Puig. Si la app se cerró sola, al abrirla te propone crear un paquete de diagnóstico.

## Novedades

**4.0**
- **Historial con ficha de cada trabajo** y botón **«Copiar para Claude»** para saber qué ha pasado.
- **Niveles más fáciles** y alguna sorpresa escondida. **Guía** al día con todas las herramientas.

**3.9**
- **Barra lateral nueva:** Rodaje, Edición, Taller e Historial, todo a la vista.
- **Sincronizar:** estéreo de la Zoom (Tr1 + Tr2) sin pérdida y **Cortes automáticos** para sets de DJ.
- **Audio sin pérdida:** «Unir L/R», 32 bits float y timecode conservados.
- **DIT más estricto:** las 2 copias tienen que ser en 2 discos distintos.

**Antes, en la 3.x**
- **Subtítulos** con Midnight Sub v1 para Final Cut (3.8), **Discos** (3.6), **Sincronizar** (3.5) y **Nivel** (3.7).

La historia completa está en la app: menú **Midnight Suite › Novedades**.

---

<div align="center">

**Midnight Suite** · © Midnight Group · by Puig

</div>
