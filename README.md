# Bot Conversor de Audio y Video para Telegram

Este es un bot de Telegram diseñado para convertir archivos de audio y video a formato MP3. Es útil para extraer la pista de audio de videos o para estandarizar archivos de música a un formato universal.

## ✨ **Características Principales**

* **Conversión Rápida**: Simplemente envía un archivo de audio (como WAV, FLAC, M4A) o un video (como MP4, MKV) y el bot lo convertirá automáticamente a MP3.
* **Modo Interactivo (`/live`)**: Personaliza tus conversiones con el comando `/live`. El bot te guiará para que establezcas el **título**, el **artista** y decidas si quieres incrustar una **carátula** antes de enviar el archivo.
* **Gestión de Mensajes**: Para mantener el chat limpio, el bot elimina automáticamente los mensajes de la conversación interactiva y los archivos temporales una vez que la conversión finaliza.
* **Retroalimentación en Tiempo Real**: El mensaje de estado de la conversión se actualiza en vivo para mostrar el tiempo transcurrido y el resultado final (éxito o fallo), eliminándose después de 10 segundos.
* **Manejo de Errores**: Detecta y notifica si el archivo es demasiado grande (supera el límite de 50MB de Telegram).

## 🚀 **Cómo usar el bot**

1.  **Conversión Rápida**: Envía un archivo de audio o video directamente al chat. El bot lo procesará con la configuración predeterminada.
2.  **Conversión Personalizada**:
    * Envía el comando `/live` para iniciar una nueva sesión de conversión.
    * El bot te pedirá el título de la canción.
    * Luego, te pedirá el nombre del artista (o puedes escribir `default` para usar el predeterminado).
    * Finalmente, te preguntará si deseas incrustar una carátula (`si` o `no`).
    * Una vez que respondas, envía el archivo de audio o video que deseas convertir.

### **Comandos**

* `/start`: Inicia la conversación con el bot.
* `/live`: Activa el modo de conversión interactiva para personalizar el audio.
* `/help`: Muestra una guía de uso detallada.

## ⚙️ **Requisitos**

Para ejecutar este bot, necesitas tener instalados:

* **Python 3.8 o superior**
  ---
  `pkg install python o apt install python`
* **`ffmpeg`**
  ---
  `pkg install ffmpeg` **OJO, termux debería de ya tenerlo instalado**
  ---
También es necesario que instales las dependencias de Python listadas en el archivo `requirements.txt`:
pip -r requirements.txt
---
**Desarrollado para dispositivos termux con version 1.119**

---
# Hecho Por elmendezz 💦


