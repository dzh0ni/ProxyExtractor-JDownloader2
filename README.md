﻿![logo](https://multianime.com.mx/wp-content/uploads/2020/08/anime-404-gomen-.jpg)

# Extractor de Proxies para JDownloader 2 :octocat: 

## :information_source: Descripción
Extractor de Proxies para [JDownloader 2](https://jdownloader.org/es/download/index) es una herramienta eficiente diseñada en PowerShell y Bash para automatizar la extracción y conversión de listas de proxies, haciéndolas compatibles con JDownloader 2. Este script simplifica el proceso de gestionar grandes volúmenes de proxies, transformándolos en un formato que JDownloader puede utilizar directamente, permitiendo la descarga más rápida y anónima a través de proxies.

Para obtener listas de proxies actualizadas y confiables, se recomienda extraerlas de sitios como:
- [hmy.name - Lista de Proxies](https://hmy.name/proxy-list/)
- [hide.mn - Lista de Proxies](https://hide.mn/es/proxy-list/)

Estas fuentes proporcionan una amplia gama de proxies que puedes transformar y cargar fácilmente en JDownloader 2 con este script, optimizando tu experiencia de descarga con mayor privacidad y anonimato.

### :computer: Instalación

### En Windows:

![logo](https://github.com/dzh0ni/ProxyExtractor-JDownloader2/blob/main/Imagenes/ProxyExtractor-JDownloader2-Windows.png)

Para instalar y ejecutar el script Extractor de Proxies para JDownloader 2, sigue estos pasos:

1. Descarga el archivo ZIP del repositorio:

   [Descargar el repositorio](https://github.com/dzh0ni/ProxyExtractor-JDownloader2/archive/refs/heads/main.zip)

2. Extrae el contenido del archivo ZIP:

   Descomprime el archivo descargado en una carpeta de tu elección. Esto creará una carpeta con todos los archivos necesarios.

## :rocket: Modo de Uso

Sigue estos pasos para ejecutar el script.

1. Navega al directorio del script Windows.

   Navega hasta la carpeta donde descomprimiste el archivo ZIP. 

2. Ejecuta el script:

   Dentro de la carpeta descomprimida, haz doble clic en el siguiente archivo para ejecutar el script:

   - `RunGetProxies_JDownloader.cmd` 

3. **Visualiza los resultados:**

   - El script mostrará el progreso y resultados en la consola.
   - Los proxies se guardarán en un archivo de texto llamado `proxies.txt` y en el formato para JDownloader 2 en `proxies_jdownloader.txt`.

### En Linux:

![logo](https://github.com/dzh0ni/ProxyExtractor-JDownloader2/blob/main/Imagenes/ProxyExtractor-JDownloader2-Linux.png)

```bash
sudo rm -rf ProxyExtractor-JDownloader2
sudo git clone https://github.com/dzh0ni/ProxyExtractor-JDownloader2.git
sudo chmod +x ProxyExtractor-JDownloader2/Linux/*
cd ProxyExtractor-JDownloader2/Linux
ls -ltha
```

1. Navega al directorio del script Linux:

  Accede a la carpeta donde descargaste el script.

## :rocket: Modo de Uso

2. Ejecuta el script:

  Abre una terminal y ejecuta el script usando el siguiente comando:

```bash
./Proxies_JDownloader.sh
```

3. Visualiza los resultados:
   - El script mostrará el progreso y resultados en la consola.
   - Los proxies se guardarán en un archivo de texto llamado proxies.txt y en el formato para JDownloader 2 en proxies_jdownloader.txt.

## :mag: Ejemplo de Salida

El archivo proxies.txt contendrá entradas en el siguiente formato:

```plaintext
46.46.56.64:1080
195.98.77.179:1080
192.111.134.10:4145
89.145.162.81:1080
67.201.33.10:25283
```

El archivo proxies_jdownloader.txt contendrá entradas en el siguiente formato:

```plaintext
socks5://46.46.56.64:1080
socks5://195.98.77.179:1080
socks5://192.111.134.10:4145
socks5://89.145.162.81:1080
socks5://67.201.33.10:25283
```

## :star2: Contribuciones

Las contribuciones son bienvenidas. Si tienes ideas para mejorar este proyecto o encuentras 
algún problema, siéntete libre de abrir un pull request o issue.

## :bookmark_tabs: Notas
Este script permite la conversión de proxies para su uso en JDownloader 2 de manera automatizada y sencilla.

- Extracción Automática: Procesa automáticamente proxies desde un archivo de texto.
- Conversión de Formato: Convierte proxies al formato requerido por JDownloader 2.
- Soporte para Windows y Linux: Incluye scripts para ambos sistemas operativos.

## :star2: Características 

- Automatización: Simplifica la conversión y gestión de proxies para JDownloader 2.
- Organización: Agrupa funcionalidades relacionadas para un acceso rápido y eficiente.
- Actualización: Incluye funciones para mantener el script actualizado.

## :hammer_and_wrench: Requisitos 

- Sistema Operativo: Windows o Linux
- Dependencias: PowerShell (para Windows) o Bash (para Linux)

## :memo: Personalización

Puedes ajustar los comandos y configuraciones del script según tus necesidades modificando el 
archivo `GetProxies_JDownloader.ps1` en Windows y `Proxies_JDownloader.sh` en Linux

## :open_file_folder: Estructura del Repositorio

| Icono            | Nombre              | Descripción                                |
|------------------|---------------------|--------------------------------------------|
| :file_folder:    | imágenes            | Carpeta para imágenes                      |
| :file_folder:    | Linux               | Carpeta principal para ejecutar en Linux   |
| :file_folder:    | Windows             | Carpeta principal para ejecutar en Windows |
| :page_facing_up: | .gitattributes      | Archivo para configuración de Git          |
| :page_facing_up: | LICENSE             | Archivo de licencia                        |
| :book:           | README.md           | Archivo de documentación principal         |

## :star2: Contribuciones

Las contribuciones son bienvenidas. Si tienes ideas para mejorar este script o encuentras algún problema, siéntete libre de abrir un *pull request* o *issue*.

## :warning: Advertencias

- Uso Responsable: Este script está diseñado para ser utilizado en dispositivos y redes que te pertenecen o para las que tienes permiso de uso. No lo utilices para actividades no autorizadas.

## :email: Contacto 
* :busts_in_silhouette: **dZh0ni**: [Telegram](https://t.me/dZh0ni_Dev) - Desarrollador Proxy Extractor JDownloader 2
