VisualSampler v1.0.1 FREE
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
5. Pulsa los PAD del SP-404MKII para cambiar de imagen.

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
La ubicación elegida se guarda y se utiliza en los siguientes inicios.
Si ya no está disponible, volverá a aparecer el selector de carpetas.
Si cancelas o eliges una carpeta incorrecta, pulsa R en la aplicación para intentarlo de nuevo.
Banks/BankA y Banks/BankB deben contener, cada una, imágenes numeradas del 01 al 16.

Ejemplo de estructura correcta:

VisualSampler_v1.0.1_macOS_AppleSilicon/
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

VisualSampler v1.0.1 FREE solo permite usar BANK A y BANK B.
Puedes asignar 16 imágenes a cada BANK, hasta un total de 32 imágenes.

BANK A: 16 fotos de escenas cotidianas de Tokio (incluidas inicialmente)
BANK B: 16 imágenes de estilo manga en dos colores basadas en las fotos de BANK A (incluidas inicialmente)

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

Las extensiones no distinguen entre mayúsculas y minúsculas.

Reglas para los nombres de archivo:
・Deben empezar por «01» a «16», correspondientes a PAD 01–16.
・Puedes usar solo el número o «número_nombre libre».
・Ejemplos: 01.jpg / 01_tokyo.jpg / 16_night.png
・Los nombres sin un guion bajo justo después del número,
  como «01tokyo.jpg», no se reconocen.

Prioridad si hay varios archivos para el mismo número de PAD:
  1. Extensión: .jpg → .jpeg → .png
  2. Si tienen la misma extensión, el nombre más corto sin contar la extensión
  3. Si tienen la misma longitud, orden alfabético del nombre (sin distinguir mayúsculas y minúsculas)

Ejemplo: Si existen 01.jpg / 01_city.jpg / 01_tokyo.png,
         se carga 01.jpg.

Para evitar confusiones, se recomienda un solo archivo de imagen por número de PAD.

【6. Proporción y tamaño recomendados de las imágenes】

El tamaño de ventana de referencia es 768 × 1024 px (ancho:alto = 3:4).
Si preparas imágenes para la proporción de la pantalla, usa como guía el formato vertical 3:4.

Tamaños sugeridos: aproximadamente 768 × 1024 px o 1536 × 2048 px.
Nota: Son orientaciones para preparar las imágenes, no requisitos obligatorios.
Nota: El recorte, los márgenes y la deformación pueden variar según
  el modo de visualización. Comprueba cómo se muestran realmente.

Cuanto mayores sean el tamaño del archivo o la resolución, más tiempo
puede llevar cargar las imágenes de los BANK al iniciar la aplicación.
Si el paso de la pantalla de inicio a la pantalla principal tarda demasiado,
reduce o comprime las imágenes a un tamaño adecuado.

【7. Cambiar el tamaño de ventana con el teclado del Mac】

Shift + 1 ：384 × 512 px（50%）
Shift + 2 ：576 × 768 px（75%）
Shift + 3 ：768 × 1024 px（100%）

Nota: Estos atajos cambian el tamaño de la ventana de la aplicación,
  no el tamaño de los archivos de imagen.
Nota: El funcionamiento puede variar según la distribución del teclado y los ajustes de entrada.

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

VisualSampler v1.0.1 FREE
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

【Cambios y comprobaciones de v1.0.1】
・Corregida la búsqueda de Banks externos cuando macOS ejecuta una aplicación descargada en una ubicación aislada (App Translocation).
・Añadidos el selector de Banks, el guardado de su ubicación y la posibilidad de volver a seleccionarla.
・Actualizado el icono de la aplicación.
・Java incluido; normalmente no hace falta instalar Processing ni otro entorno Java.

El 15 de octubre de 2026, en el Mac Apple Silicon usado para el desarrollo, se comprobaron la descarga
desde GitHub, el permiso de inicio de macOS, la carga y recuperación de Banks y el funcionamiento físico de MIDI/BANK/FX/CTRL.
También se verificaron las 32 imágenes y el procesamiento de PAD mediante pruebas automatizadas.
No se han probado otros Mac, el uso prolongado ni todas las combinaciones de parámetros.
La pantalla de inicio existente muestra Ver. 1.00, pero este paquete es v1.0.1.
