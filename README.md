<p align="center">
  <img src="assets/logo.jpg" width="160" alt="Hunters Lab — Digital Hunters">
</p>

<h1 align="center">Hunters Lab</h1>

<p align="center"><b>Automatización de la generación de imágenes y videos mediante IA para creadores.</b></p>
<p align="center">Generación y escalado masivo por lotes con <b>Google Flow (Veo 3.1, Omni Flash, Nano Banana Pro, Nano Banana 2 y Nano Banana 2 Lite)</b> desde una única aplicación de escritorio para <b>Windows</b> y <b>macOS</b>.</p>

<p align="center">
  <a href="https://github.com/stev12O/Hunters-Lab/releases/latest/download/HuntersLab_Setup_v1.1.12.exe"><img alt="Descargar para Windows" src="https://img.shields.io/badge/DESCARGAR%20WINDOWS-0078D6?style=for-the-badge&logo=windows&logoColor=white"></a>&nbsp;
  <a href="https://github.com/stev12O/Hunters-Lab/releases/latest/download/HuntersLab-mac-arm64.dmg"><img alt="Descargar para macOS Apple Silicon" src="https://img.shields.io/badge/DESCARGAR%20MACOS-APPLE%20SILICON-000000?style=for-the-badge&logo=apple&logoColor=white"></a>&nbsp;
  <a href="https://github.com/stev12O/Hunters-Lab/releases/latest/download/HuntersLab-mac-intel.dmg"><img alt="Descargar para macOS Intel" src="https://img.shields.io/badge/DESCARGAR%20MACOS-INTEL-555555?style=for-the-badge&logo=apple&logoColor=white"></a>
</p>

<p align="center">
  <a href="https://digitalhunterflow.online"><img alt="Sitio Web Oficial" src="https://img.shields.io/badge/Sitio%20Web-Visitar-2563EB?style=flat-square&logo=googlechrome&logoColor=white"></a>&nbsp;
  <a href="https://chat.whatsapp.com/D43zvYG30gj3YhH0WWkD38"><img alt="Comunidad de WhatsApp" src="https://img.shields.io/badge/WhatsApp-Unirse%20a%20la%20Comunidad-25D366?style=flat-square&logo=whatsapp&logoColor=white"></a>&nbsp;
  <a href="https://github.com/stev12O/Hunters-Lab/releases/latest"><img alt="Última Versión" src="https://img.shields.io/github/v/release/stev12O/Hunters-Lab?style=flat-square&label=Versi%C3%B3n&color=CCFF00"></a>
</p>

---

## ¿Qué es Hunters Lab?

**Hunters Lab** es una aplicación de escritorio para **Windows** y **macOS** que convierte la generación de imágenes y videos mediante IA en un proceso por lotes repetible y automatizado. Simplemente pega una lista de indicaciones (o importa tus archivos `.txt`, `.xlsx` o `.json`), elige un modelo y pulsa **Generar**: la aplicación gestiona tus cuentas, sincroniza las solicitudes en paralelo, renueva sesiones automáticamente, reintenta las que fallan y guarda todos los resultados ordenados en la carpeta correspondiente. Sin scripts, sin pestañas manuales del navegador, sin línea de comandos.

Diseñado para quienes generan grandes volúmenes de producción: creadores de contenido, operadores de canales automatizados, equipos creativos de publicidad y agencias que gestionan la producción con IA a gran escala.

---

## Características

| Espacio de trabajo | Lo que hace |
| :--- | :--- |
| **Flow Imagen** | Conversión masiva por lotes de texto a imagen e imagen a imagen en Google Labs Flow: **Nano Banana Pro**, **Nano Banana 2** y **Nano Banana 2 Lite**. Soporta de 1 a 4 salidas por prompt, 5 relaciones de aspecto (`16:9`, `9:16`, `4:3`, `3:4`, `1:1`), imágenes de referencia por fila y escalado nativo a **1K, 2K y 4K**. |
| **Flow Vídeo — Texto / Fotograma a Vídeo** | Generación de video por lotes con **Veo 3.1 Fast**, **Veo 3.1 Lite**, **Veo 3.1 Quality** y **Omni Flash**. Soporta Texto a Vídeo (T2V), Imagen inicial a Vídeo (I2V) e Interpolación de fotograma Inicial + Final (con modos de emparejamiento automático: *Solo imagen inicial*, *1 Inicio - N Fin*, *N Inicio - 1 Fin*, *Cadena 1:2→2:3* y *Pares 1:2→3:4*), duraciones de `4s`, `6s`, `8s`, `10s` y escalado nativo a **720p, 1080p y 4K**. |
| **Flow Vídeo — Ingredientes a Vídeo** | Creación de videos manteniendo coherencia de personajes, objetos y estilo mediante imágenes de referencia combinadas y menciones directas en el prompt. |
| **Flow Vídeo — Cadena de Escenas** | Producción secuencial continua donde cada escena toma automáticamente el último fotograma renderizado de la escena anterior para enlazar historias completas sin cortes bruscos. |
| **Biblioteca de Personajes (`@nombre`)** | Conecta tu carpeta de imágenes de referencia y llama a cualquier personaje directamente dentro de tus prompts escribiendo `@nombre`, con resaltado en vivo y caché inteligente en 2 niveles (sin volver a subir imágenes repetidas). |
| **Gestor de Cola y Sesiones** | Añade múltiples lotes con diferentes modelos, aspectos o resoluciones a la cola de trabajo. Controla **Ejecutar / Pausar / Detener** de forma independiente, edita tareas en espera y recupera automáticamente tus sesiones previas al abrir la app. |
| **Pool Multi-Cuenta Inteligente** | Conecta múltiples cuentas de Google Flow (Free, Pro o Ultra), rotación automática de cuentas y proyectos, renovación automática de sesión en segundo plano y pausa selectiva cuando una cuenta agota su cuota diaria (reactivándose sola a medianoche). |

---

## Instalación

### Paso 1 — Elige la versión correcta para tu equipo

Descarga la última versión desde **[Releases](https://github.com/stev12O/Hunters-Lab/releases/latest)** o directamente desde la siguiente tabla según tu sistema operativo:

| Tu equipo | Descarga Directa | Notas |
| :--- | :--- | :--- |
| **Windows 10 / 11 (64-bit)** | [**Descargar Windows (.exe)**](https://github.com/stev12O/Hunters-Lab/releases/latest/download/HuntersLab_Setup_v1.1.12.exe) | Para cualquier PC con Windows 10 u 11 |
| **Mac con chip Apple (M1 / M2 / M3 / M4)** | [**Descargar macOS ARM (.dmg)**](https://github.com/stev12O/Hunters-Lab/releases/latest/download/HuntersLab-mac-arm64.dmg) | Macs con chip Apple Silicon (finales de 2020 en adelante) |
| **Mac con chip Intel** | [**Descargar macOS Intel (.dmg)**](https://github.com/stev12O/Hunters-Lab/releases/latest/download/HuntersLab-mac-intel.dmg) | Macs con procesador Intel (anteriores a 2020) |

**¿No sabes qué chip tiene tu Mac?** Haz clic en el menú de Apple (arriba a la izquierda) → **Acerca de este Mac (About This Mac)**:
- Si aparece **Chip: Apple M1 / M2 / M3 / M4** → descarga la versión **macOS ARM (`arm64`)**.
- Si aparece **Procesador: Intel** → descarga la versión **macOS Intel (`intel`)**.

---

### Paso 2 — Instalar

<details open>
<summary><b>En Windows</b></summary>

1. Abre el instalador descargado **`HuntersLab_Setup_v1.1.12.exe`**.
2. Si aparece la ventana de Windows SmartScreen (*"Windows protegió su PC"*): haz clic en **Más información** → **Ejecutar de todas formas**. *(La aplicación aún no cuenta con firma comercial de Microsoft, por lo que Windows muestra este aviso preventivo).*
3. Acepta los permisos de administrador y sigue el asistente de instalación hasta finalizar.
4. Abre **Hunters Lab** desde el **Menú Inicio** o el acceso directo en tu **Escritorio**.

</details>

<details open>
<summary><b>En macOS</b></summary>

1. Abre el archivo **`.dmg`** descargado y **arrastra el icono de Hunters Lab a la carpeta Applications**.
2. Ve a la carpeta **Applications**, haz **clic derecho** (o mantén presionado `Control` + clic) sobre **Hunters Lab** → selecciona **Abrir (Open)** → confirma **Abrir**.
3. Si macOS muestra un aviso indicando que la aplicación no se puede abrir o está dañada, abre la aplicación **Terminal**, pega el siguiente comando y presiona `Enter`:
   ```bash
   xattr -dr com.apple.quarantine "/Applications/Hunters Lab.app"
   ```
   Después de ejecutarlo la primera vez, **Hunters Lab** abrirá normalmente como cualquier otra aplicación.

</details>

---

### Paso 3 — Inicia sesión y elige un plan

1. **Inicia sesión con tu cuenta de Google** al abrir la aplicación.
2. En la barra superior verás la insignia de tu plan activo (**BASIC / PRIME / ELITE**). Puedes gestionar o mejorar tu suscripción directamente desde la aplicación (**PayPal / Tarjeta, Binance Pay o WhatsApp**) o desde nuestro sitio oficial **[digitalhunterflow.online](https://digitalhunterflow.online)**.
3. **Actualización automática integrada**: Cada vez que se publica una nueva versión en GitHub Releases, la aplicación te avisa en la esquina superior derecha para descargarla e instalarla con un solo clic.

---

## Primer uso

1. **Abre Hunters Lab e inicia sesión con Google.**
2. **Conecta tus cuentas de Google Flow**:
   - Haz clic en **Cuentas** (o en el icono de **Configuración**) en la barra superior.
   - Pulsa **Añadir cuenta (Login Chrome)** para iniciar sesión en el navegador o importa tus sesiones.
   - El encabezado te mostrará en vivo cuántas cuentas tienes activas y sus créditos disponibles.
3. **Elige tu modo de trabajo (`Flow Imagen` o `Flow Vídeo`)**:
   - Escribe o pega tus prompts a la izquierda (o impórtalos desde `.txt` / `.xlsx`), selecciona el modelo, la proporción y la resolución, y pulsa **Generar** o **Añadir a la cola**.
   - Monitorea el progreso en tiempo real desde la barra de estado (*En curso · En cola · Completados · Fallidos*) y revisa o reintenta cualquier fila directamente desde la tabla.

---

## Dónde se guardan tus archivos

| Contenido | Windows | macOS |
| :--- | :--- | :--- |
| **Resultados (imágenes y videos)** | `%USERPROFILE%\Documents\Hunters Lab\output` | `~/Documents/Hunters Lab/output` |
| **Referencias / Biblioteca de personajes** | `%USERPROFILE%\Documents\Hunters Lab\reference_image` | `~/Documents/Hunters Lab/reference_image` |
| **Configuración, sesiones y cuentas** | `%APPDATA%\Hunters Lab` | `~/Library/Application Support/Hunters Lab` |

Cada lote o tarea en cola crea su propia subcarpeta ordenada dentro de `output` (puedes cambiar la carpeta de salida en cualquier momento desde Configuración). Tus ajustes, listas de prompts, sesiones y cuentas se guardan automáticamente y se restauran la próxima vez que abras la aplicación.

---

## Solución de problemas

- **Aparece `"0 cuentas activas"` al intentar generar**: Entra a **Configuración → Gestor de Cuentas**, verifica que al menos una cuenta tenga activada la casilla de **Imagen** o **Vídeo**, o pulsa **Actualizar todo** para renovar las sesiones expiradas.
- **Windows bloquea el instalador con *"Windows protegió su PC"***: Haz clic en **Más información → Ejecutar de todas formas**.
- **macOS indica que la aplicación *"no se puede abrir"* o *"está dañada"***: Abre la **Terminal** y ejecuta `xattr -dr com.apple.quarantine "/Applications/Hunters Lab.app"`.
- **¿Necesitas ayuda o soporte directo?**: Únete a nuestra **[Comunidad Oficial de WhatsApp](https://chat.whatsapp.com/D43zvYG30gj3YhH0WWkD38)** o visita **[digitalhunterflow.online](https://digitalhunterflow.online)**.

