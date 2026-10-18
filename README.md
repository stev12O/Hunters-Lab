# Hunters Lab — v1.0.0

Estudio de escritorio para generación y escalado masivo de imágenes y videos con IA (**Google Flow: Veo 3.1, Omni Flash, Nano Banana Pro / 2 / Lite**) para **Windows** y **macOS**.

---

## Descarga Oficial (v1.0.0)

| Tu equipo | Descarga Directa | Notas |
| :--- | :--- | :--- |
| **Windows 10 / 11 (64-bit)** | [**Descargar Windows (.exe)**](https://github.com/stev12O/Hunters-Lab/releases/latest/download/HuntersLab_Setup_v1.0.0.exe) | Para cualquier PC con Windows 10 u 11 |
| **Mac (M1 / M2 / M3 / M4)** | [**Descargar macOS ARM (.dmg)**](https://github.com/stev12O/Hunters-Lab/releases/latest/download/HuntersLab-mac-arm64.dmg) | Macs con chip Apple Silicon (finales de 2020 en adelante) |
| **Mac Intel** | [**Descargar macOS Intel (.dmg)**](https://github.com/stev12O/Hunters-Lab/releases/latest/download/HuntersLab-mac-intel.dmg) | Macs con procesador Intel (anteriores a 2020) |

> **¿No estás seguro de qué chip tiene tu Mac?** Haz clic en el icono de Apple arriba a la izquierda → **Acerca de este Mac**:
> - Si dice **Chip: Apple M1 / M2 / M3 / M4** → descarga **macOS ARM**.
> - Si dice **Procesador: Intel** → descarga **macOS Intel**.

---

## Instrucciones de Instalación

### En Windows
1. Abre el instalador descargado **`HuntersLab_Setup_v1.0.0.exe`**.
2. Si aparece la ventana azul de Windows SmartScreen (*"Windows protegió su PC"*): haz clic en **Más información** → **Ejecutar de todas formas**.
3. Acepta los permisos de administrador y sigue el asistente hasta finalizar.
4. Abre **Hunters Lab** desde el acceso directo del Escritorio o el Menú Inicio.

### En macOS
1. Abre el archivo **`.dmg`** descargado y **arrastra el icono de Hunters Lab a la carpeta Applications**.
2. Ve a la carpeta **Applications**, haz **clic derecho** (o mantén presionado `Control` + clic) sobre **Hunters Lab** → selecciona **Abrir (Open)** → confirma **Abrir**.
3. Si macOS muestra un aviso de que no se puede abrir porque proviene de un desarrollador no identificado, abre la aplicación **Terminal**, pega el siguiente comando y presiona `Enter`:

```bash
xattr -dr com.apple.quarantine "/Applications/Hunters Lab.app"
```

Después de ejecutar ese comando la primera vez, **Hunters Lab** abrirá normalmente desde `Applications` o Launchpad.

---

## Dónde se guardan tus archivos

| Contenido | Windows | macOS |
| :--- | :--- | :--- |
| **Salidas (imágenes y videos)** | `%USERPROFILE%\Documents\Hunters Lab\output` | `~/Documents/Hunters Lab/output` |
| **Configuración, sesiones y cuentas** | `%APPDATA%\Hunters Lab` | `~/Library/Application Support/Hunters Lab` |
