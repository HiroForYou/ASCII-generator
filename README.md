# Generador ASCII ◖ᵔᴥᵔ◗ ♪ ♫

## Introducción

Se presentan algunos scripts python para generar caracteres ASCII, basados en este [repositorio](https://github.com/uvipen/ASCII-generator).  Con el código, podrás:
* **Dada la imagen de entrada, puede generar caracteres ASCII almacenado en formato de texto (.txt)**
* **Dada la imagen de entrada, puede generar caracteres ASCII almacenado en formatos de imagen (.png, .jpg, ...). En cada formato, hay 2 opciones: fondo negro y caracteres blancos, o viceversa**
* **Dado un video de entrada, puede generar arte ASCII almacenado en formatos de video (.avi, .mp4, ...)**
* **Las salidas de video/imagen pueden estar en formato de escala de grises o color. Depende totalmente de usted**

## Video a video
Ejecutando el script **video2video_color.py** o **video2video.py** con diferentes valores para *background* y *mode*.

## Imagen a texto
Ejecutando el script **img2txt.py** con diferentes valores para *mode*, obtendremos un archivo de texto ASCII.

## Imagen a imagen
Ejecutando el script **img2img_color.py** o **img2img.py** con diferentes valores para *background* y *mode*, obtenemos las siguientes salidas:
<p align="center">
  <img src="demo/input.jpg" width=400><br/>
  <i>Imagen de entrada</i>
</p>

<p align="center">
  <img src="demo/output_100.jpg" width=400><br/>
  <i>Imagen de salida ASCII</i>
</p>


## Requerimientos

* **python 3.6**
* **cv2**
* **PIL** 
* **numpy**
