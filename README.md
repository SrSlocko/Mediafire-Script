
# Mediafire Downloader Script 2023

## Descripción

Este script, desarrollado por SrSlocko, es una herramienta que te permite descargar archivos de Mediafire proporcionando enlaces de descarga de Mediafire. Además, ofrece funcionalidades adicionales, como la detección automática de la herramienta de descarga (wget o curl), la comprobación de la disponibilidad de la conexión a Internet y opciones para descargar automáticamente archivos o mostrar las URL de descarga.

Ten en cuenta que actualmente el script no es capaz de atrapar enlaces de carpetas y descargar todo el contenido de forma automática. Sin embargo, este script es una herramienta útil para descargar archivos individuales de Mediafire de manera eficiente.

## Compatibilidad

- **Sistemas Operativos**: Este script es compatible con sistemas operativos basados en Linux, como Ubuntu, Debian, CentOS, Fedora, y otros. También es compatible con Windows utilizando WSL (Windows Subsystem for Linux). Se requiere acceso a Internet en ambos casos.

## Requisitos

Antes de utilizar esta herramienta, asegúrate de cumplir con los siguientes requisitos:

- Uno de los siguientes programas de descarga debe estar instalado en tu sistema:
  - 'wget'
  - 'curl'

Si no tienes ninguno de estos programas instalados, el script te proporcionará una advertencia.

## Uso

Para utilizar el script, sigue estos pasos:

1. Clona o descarga el repositorio a tu sistema local.

2. Abre una terminal y navega al directorio donde se encuentra el script.

3. Ejecuta el script en la línea de comandos de la siguiente manera:

bash
./mediafire_downloader.sh [opciones] URL1 URL2 ...

Donde [opciones] puede ser:

-n o --no-download: Evita la descarga automática y muestra las URL de descarga en su lugar.
Por ejemplo, para descargar un archivo desde Mediafire, puedes ejecutar el script de la siguiente manera:

bash
./mediafire.sh https://www.mediafire.com/file/ejemplo12345/archivo.zip
El script detectará automáticamente la herramienta de descarga adecuada y comenzará la descarga del archivo.


Notas
El script verifica si las URL proporcionadas son válidas y ofrece mensajes de error si no lo son.
Si la URL proporcionada es una URL de identificación de Mediafire, el script la convierte en una URL de descarga.
El script utiliza wget o curl para obtener las URLs de descarga de Mediafire y las descarga automáticamente si no se utiliza la opción -n.
Ten en cuenta que la funcionalidad para descargar carpetas completas desde Mediafire aún no se ha implementado y está en investigación.

Esperamos que este script te sea de utilidad para tus necesidades de descarga desde Mediafire. Si tienes sugerencias de mejoras o encuentras problemas, no dudes en contribuir al repositorio o contactar a SrSlocko.

¡Disfruta de tu herramienta de descarga de Mediafire!
