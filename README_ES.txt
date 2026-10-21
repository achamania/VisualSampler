VisualSampler v2.0.0 FREE
for SP-404MK2
============================================================

Sample Your City. Remix Your Reality.

【1. Qué es VisualSampler】

VisualSampler es un sampler visual para macOS que permite interpretar
imágenes estáticas con el Roland SP-404MKII.

Toma muestras de paisajes urbanos y fotos cotidianas como lo haces con la música.
Usa los 16 PAD para cambiar de imagen y disfrutar de la expresión visual en tiempo real.

Añade tus fotos favoritas y toca los PAD.
Convierte tu vida cotidiana en muestras visuales.

【2. Requisitos del sistema】

・Sistema operativo compatible: macOS (mínimo del entorno incluido: 11.0; comprobación por versiones de macOS aún incompleta)
・Mac compatible: Mac con Apple Silicon (serie M)
・Controlador: Roland SP-404MKII
・Conexión: USB MIDI
・Creado con Processing
・La aplicación distribuida incluye un entorno de ejecución de Java (normalmente no requiere instalación adicional)

Nota: Esta versión es exclusiva para Mac con Apple Silicon. No es compatible con Mac Intel ni Windows.

【3. Ubicación e inicio de la aplicación】

1. Descomprime el ZIP de distribución.
2. Conecta el SP-404MKII al Mac por USB y enciéndelo.
3. Comprueba los ajustes MIDI del SP-404MKII (véase abajo).
4. Abre VisualSampler.app.
5. Pulsa un PAD del SP-404MKII para pasar de la pantalla de inicio a las imágenes y cambiarlas.

Ajustes MIDI obligatorios del SP-404MKII:
  SHIFT + PAD 13（UTILITY）→ SYSTEM → MIDI
  ・MIDI Mode：A
  ・PAD Note Out：ON

Nota: Ambos ajustes son necesarios para controlar VisualSampler.
  Si MIDI Mode está en B, la asignación de notas/canales MIDI de los PAD
  difiere de la prevista por VisualSampler y el control no funciona correctamente.
  Si PAD Note Out está en OFF, las operaciones de los PAD no envían señales MIDI.
Nota: VisualSampler no requiere un ajuste específico de
  MIDI EXT Src（TOGGLE / GATE / THROUGH）.

Colocar Banks junto a VisualSampler.app facilita la organización.
Si al iniciar se solicita su ubicación, selecciona la carpeta principal «Banks», que contiene BankA y BankB.
Se da prioridad a una carpeta Banks válida situada junto a la aplicación. Si no está disponible, se comprueba la ubicación guardada en ver2.
La ubicación elegida se guarda por separado de ver1 y se utiliza en los siguientes inicios.
Si ya no está disponible, volverá a aparecer el selector de carpetas.
Si cancelas o eliges una carpeta incorrecta, pulsa R en la aplicación para intentarlo de nuevo.
Banks/BankA y Banks/BankB deben contener, cada una, imágenes numeradas del 01 al 16.

Ejemplo de estructura correcta:

VisualSampler_v2.0.0_macOS_AppleSilicon/
├── VisualSampler.app
├── Banks/
│   ├── BankA/
│   │   ├── 01.jpg
│   │   ├── 02.jpg
│   │   └── ... 16.jpg
│   └── BankB/
│       ├── 01.jpg
│       ├── 02.jpg
│       └── ... 16.jpg
├── README_JP.txt
├── README_EN.txt
├── README_ES.txt
├── README_ZH_CN.txt
└── README_KO.txt

Nota: Los nombres de las carpetas son «Banks», «BankA» y «BankB».
  No los cambies por «BANK_A», «BANK_B» u otros nombres.
Nota: No muevas Banks al interior de .app.
【Primer inicio: Privacidad y seguridad】

Esta versión no está firmada con Developer ID ni ha sido notarizada por Apple.
Por ello, macOS puede advertir que Apple no puede verificar su seguridad al abrirla por primera vez.
Sigue estos pasos solo si confías en la procedencia y has comprobado que el archivo no ha sido alterado.

1. Descomprime el ZIP e intenta abrir VisualSampler.app una vez.
2. Si Apple advierte que no puede comprobar si contiene software malicioso, cierra el aviso.
3. Abre Ajustes del Sistema desde el menú Apple.
4. Selecciona Privacidad y seguridad y desplázate hasta Seguridad.
5. Junto al aviso de bloqueo de VisualSampler, pulsa Abrir igualmente (Open Anyway).
6. Revisa cualquier solicitud de autenticación o confirmación y, si deseas continuar, selecciona Abrir.
7. Cuando se inicie la aplicación, selecciona Banks si se solicita.

Normalmente, el permiso queda guardado y después basta con hacer doble clic.
Una actualización puede solicitar el permiso de nuevo.
Si no aparece Abrir igualmente, revisa esta pantalla justo después de intentar abrir la aplicación.
La opción puede no estar disponible en un Mac administrado por una empresa o centro educativo.

Si el aviso indica que la aplicación está dañada, dañará el Mac o contiene malware detectado,
no continúes solo con estos pasos: comprueba la fuente oficial y el archivo descargado.
Si la aplicación no responde, ciérrala y comprueba de nuevo en lugar de abrirla repetidamente.

Instrucciones oficiales de Apple:
https://support.apple.com/ja-jp/102445

【4. Acerca de los BANK】

VisualSampler v2.0.0 FREE solo permite usar BANK A y BANK B.
Puedes asignar 16 imágenes a cada BANK, hasta un total de 32 imágenes.

BANK A: 16 imágenes incluidas (3 HEIC + 13 JPG)
BANK B: 16 imágenes incluidas (PNG)

Las imágenes colocadas en BANK C o posteriores no se cargan ni se muestran en la versión FREE.
Está previsto ampliar el número de BANK disponibles en una futura versión VisualSampler PRO.
Nota: Las especificaciones y la fecha de lanzamiento de PRO no están definidas y pueden cambiar.

【5. Usar tus propias imágenes】

1. Cierra VisualSampler.
2. Abre Banks/BankA o Banks/BankB.
3. Haz una copia de seguridad de las imágenes existentes y sustitúyelas por las que prefieras.
4. Reinicia VisualSampler y comprueba el resultado.

Formatos de imagen compatibles:
  .jpg   (prioridad 1)
  .jpeg  (prioridad 2)
  .png   (prioridad 3)
  .heic  (prioridad 4)
  .heif  (prioridad 5)

Las imágenes HEIC/HEIF se cargan respetando la orientación de la toma. No se modifican los archivos originales.
No se admiten archivos de vídeo ni la parte de vídeo de Live Photos.

Las extensiones no distinguen entre mayúsculas y minúsculas.

Reglas para los nombres de archivo:
・Deben empezar por «01» a «16», correspondientes a PAD 01–16.
・Puedes usar solo el número o «número_nombre libre».
・Ejemplos: 01.jpg / 01_tokyo.jpg / 16_night.png
・Los nombres sin un guion bajo justo después del número,
  como «01tokyo.jpg», no se reconocen.

Prioridad si hay varios archivos para el mismo número de PAD:
  1. Extensión: .jpg → .jpeg → .png → .heic → .heif
  2. Si tienen la misma extensión, el nombre más corto sin contar la extensión
  3. Si tienen la misma longitud, orden alfabético del nombre (sin distinguir mayúsculas y minúsculas)

Ejemplo: Si existen 01.jpg / 01_city.jpg / 01_tokyo.png,
         se carga 01.jpg.

Para evitar confusiones, se recomienda un solo archivo de imagen por número de PAD.

【6. Relaciones de aspecto y tamaños de imagen recomendados】

La relación de aspecto inicial es 3:4. Haz clic izquierdo en la imagen para recorrer:
  3:4 → 4:3 → 9:16 → 16:9 → 3:4

Dimensiones internas de renderizado:
  3:4  : 768 × 1024 px
  4:3  : 1024 × 768 px
  9:16 : 576 × 1024 px
  16:9 : 1024 × 576 px

Las imágenes conservan sus proporciones originales y llenan el formato seleccionado.
Las partes que sobresalen se recortan tomando el centro como referencia.
Si la ventana tiene proporciones distintas a las de la salida visual, el espacio sobrante queda negro.

Al cambiar de formato, aparece en verde una etiqueta en japonés, como «アスペクト比 4:3»,
en la esquina superior derecha de la imagen. Desaparece al cabo de unos dos segundos.
Los mismos controles y la misma indicación funcionan a pantalla completa.

Para controlar mejor el encuadre, prepara las imágenes con la proporción que quieras usar.
Ejemplos: 768 × 1024 px para 3:4, 1024 × 576 px para 16:9, o múltiplos enteros de estos tamaños.
Son recomendaciones, no dimensiones obligatorias.

Las imágenes grandes y un número elevado de archivos HEIC/HEIF pueden alargar la carga inicial.
Si el inicio o el funcionamiento son lentos, reduce la resolución de las imágenes y prueba de nuevo.

【7. Ventana y pantalla completa】

La versión 2 utiliza una sola ventana de visualización desde el inicio.
No es necesario hacer clic derecho para abrir otra ventana de presentación.

• Arrastra un borde o una esquina de la ventana para ajustar el tamaño.
• Usa el botón verde de la esquina superior izquierda para entrar en pantalla completa de macOS.
  Según la versión de macOS, selecciona «Usar pantalla completa» en su menú.
• Para salir de pantalla completa, lleva el puntero al borde superior y utiliza el botón verde.
• Haz clic izquierdo para recorrer las cuatro proporciones tanto en ventana como a pantalla completa.
• Usa el botón rojo para salir de la aplicación.

Al cambiar el tamaño de la ventana, se conserva la proporción visual seleccionada.
La imagen no se estira ni se deforma para llenar toda la ventana.

【8. Efectos visuales】

Efectos incluidos:
・GLITCH    : Ruido digital y distorsiones de la imagen
・CRT       : Apariencia de televisión de tubo de rayos catódicos
・PIXELATE  : Apariencia de píxeles gruesos
・RGB SPLIT : Apariencia creada al desplazar los colores RGB

Controles del SP-404MKII:
・CTRL 1: Seleccionar el efecto
・CTRL 2 / CTRL 3: Ajustar el efecto seleccionado
・Pulsar EXT SOURCE dos veces: Restablecer los efectos

Nota: La apariencia y los ajustes varían según el efecto seleccionado.

【9. Solución de problemas】

Si las imágenes no aparecen:
・Selecciona la carpeta principal Banks, no BankA ni BankB por separado.
・Pulsa R en la pantalla de instrucciones para elegir de nuevo.
・Comprueba que la ubicación guardada de Banks exista y sea legible.
・Comprueba que los nombres «Banks/BankA» y «Banks/BankB» sean correctos.
・Comprueba que las imágenes cumplan las reglas de nombres 01–16 y usen formatos compatibles.
・Comprueba que no hayas colocado las imágenes en BANK C o posteriores.
・Comprueba que hayas reiniciado la aplicación después de sustituir las imágenes.

Si la aplicación tarda en iniciar:
・Reduce la resolución o el tamaño de los archivos y vuelve a intentarlo.

Si no puedes controlar la aplicación con el SP-404MKII:
・Comprueba la conexión USB y que el controlador esté encendido.
・Comprueba «MIDI Mode：A» en SYSTEM → MIDI.
・Comprueba «PAD Note Out：ON» en la misma pantalla.
・Reinicia la aplicación y vuelve a comprobarlo.

Si aparece otra imagen en lugar del HEIC:
• Los archivos JPG/JPEG/PNG con el mismo número de PAD tienen prioridad.
• Para usar el HEIC, mueve fuera de Banks los archivos de otros formatos con ese número.

Si la proporción o el encuadre no son los esperados:
• Haz clic izquierdo para seleccionar la relación de aspecto deseada.
• Las imágenes que no coincidan con el formato se recortan desde el centro.
• Los bordes negros debidos a una proporción distinta de la ventana son normales.

【10. Notas de uso y marcas comerciales】

VisualSampler es un software de creación independiente.
Puede no funcionar correctamente en determinados entornos.
En la medida permitida por la ley, el creador no asume responsabilidad
por los daños derivados del uso de este software.

Al sustituir imágenes, respeta los derechos de autor, de imagen y otros derechos.
Ten también en cuenta los derechos de los materiales al transmitir en directo o publicar videos.

VisualSampler es una creación independiente sin relación con Roland Corporation.
No ha sido desarrollado, aprobado ni patrocinado por dicha empresa.
Roland y SP-404MKII son marcas comerciales o marcas registradas de Roland Corporation.

【11. Credits / Información del creador】

VisualSampler v2.0.0 FREE
Created by：achamania
Concept / Design / Development：achamania

© 2026 achamania. All rights reserved.

YouTube：achamania
https://www.youtube.com/@achamania

X（Twitter）：@achamania
https://x.com/achamania

Consulta las redes sociales anteriores para ver demostraciones y actividades creativas.

【12. Message from achamania】

¡Muéstrame tus creaciones!

Si creas y publicas un video con VisualSampler,
¡cuéntamelo en los comentarios de mi canal de YouTube!

Actuaciones en directo, videos musicales, obras visuales con paisajes urbanos…
Cualquier forma de usarlo es bienvenida.

¡Tengo muchas ganas de ver lo que creas con VisualSampler!

Show me what you've sampled!

YouTube：https://www.youtube.com/@achamania

Sample Your City. Remix Your Reality.

【Cambios de v2.0.0】

• Compatibilidad con imágenes estáticas HEIC/HEIF, además de JPG/JPEG/PNG.
• Aplicación automática de la orientación de las fotos HEIC/HEIF.
• Cambio con clic izquierdo entre 3:4, 4:3, 9:16 y 16:9.
• Indicador verde de proporción, inspirado en televisores, en la esquina superior derecha.
• Una sola ventana de visualización y pantalla completa mediante el botón verde del Mac.
• Conservación de la proporción visual al cambiar el tamaño, con bordes negros en el espacio sobrante.
• Preferencias de Banks separadas de ver1 y prioridad para Banks junto a la aplicación.
• Pantalla de inicio actualizada a «Ver. 2.0.0».
• Imágenes de BANK A/B actualizadas; BANK A incluye tres fotos HEIC.
• Se mantienen las operaciones de BANK A/B, los PAD y los cuatro efectos de ver1.
• Esta versión no incluye vídeos, nuevos efectos ni compatibilidad con Windows.

La pantalla de inicio, el título de ventana, el README y la información de la aplicación usan el número 2.0.0.

【Estado de las comprobaciones】

Durante el desarrollo se comprobaron, en el Mac de desarrollo, la visualización y orientación HEIC,
las cuatro proporciones y los efectos. La implementación de una sola ventana se comprobó con una copia de prueba:
número de ventanas, renderizado tras el inicio, cuatro proporciones, efectos y entrada y salida de pantalla completa.

El 2026-10-21 se comprobaron el inicio de la aplicación candidata, Java incluido, la validación de firma,
la carga de las 32 imágenes y la detección de los puertos MIDI del SP-404MKII. Con Java incluido se comprobaron
también la carga y orientación HEIC, cuatro proporciones, efectos, una sola ventana y los cambios de pantalla completa.
Antes de publicar está prevista una prueba manual de la versión descargada.
No se han probado otros Mac, Windows, el uso prolongado ni todas las combinaciones de parámetros.
