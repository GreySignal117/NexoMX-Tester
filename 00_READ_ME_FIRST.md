# Empieza aquí · SUA-1

## ✅ Antes de empezar

Esta es una prueba pública de NexoMX para evaluación. Usa sólo los archivos sintéticos incluidos. No agregues datos reales, contraseñas, secretos ni información privada.

Necesitas Windows de 64 bits. No necesitas instalar Python ni descargar componentes adicionales.

## 📦 Descarga

En la página oficial de GitHub de NexoMX, abre `release-assets`, selecciona `NexoMX_v2.4.0_SUA1-T01.zip` y pulsa **Download raw**. Descarga también `SHA256SUMS.txt` desde la página principal del repositorio. Guarda ambos archivos en una carpeta fácil de encontrar, por ejemplo Descargas. No descargues copias de sitios desconocidos.

## 🔐 Verifica el archivo

Abre `SHA256SUMS.txt`. En PowerShell, dentro de la carpeta donde descargaste el ZIP, ejecuta:

```powershell
Get-FileHash .\NexoMX_v2.4.0_SUA1-T01.zip -Algorithm SHA256
```

El valor debe coincidir con el que aparece en `SHA256SUMS.txt`. Si no coincide, no continúes y avisa a Product.

## 📂 Extrae

Haz clic derecho al ZIP y elige **Extraer todo**. Puedes extraerlo en Descargas o Escritorio.

## ⚙️ Primera configuración

Dentro de la carpeta extraída, haz doble clic en `SETUP_NEXOMX_TEST.cmd` y sigue las instrucciones. Crearás tu propio usuario y contraseña local. Nadie te debe proporcionar una contraseña compartida.

## ▶️ Inicia NexoMX

Haz doble clic en `START_NEXOMX_TEST.cmd`. El navegador abrirá NexoMX en `http://127.0.0.1:5066`.

## 🌐 Abre NexoMX

Inicia sesión con el usuario y contraseña que acabas de crear. La aplicación sólo se abre en tu equipo; no necesitas cambiar Firewall ni compartir tu red.

## 🧪 Haz la prueba

Lee `03_SUA1_TEST_MISSION.md`. Intenta completar la misión sin buscar una guía paso a paso: queremos conocer qué tan fácil resulta descubrir el flujo.

## 🐛 Si algo falla

Usa `04_REPORT_A_BUG.md`. No incluyas contraseñas, claves de sesión, datos privados ni capturas que los muestren.

## 🧹 Cómo resetear

Haz doble clic en `RESET_NEXOMX_TEST.cmd`. Te pedirá confirmar antes de eliminar los datos sintéticos locales. Después debes ejecutar el setup de nuevo.

## 🗑 Cómo eliminar todo

Primero ejecuta `STOP_NEXOMX_TEST.cmd`. Luego elimina la carpeta extraída y `C:\NexoMX-SUA1`. Consulta `06_RESET_OR_UNINSTALL.md`.
