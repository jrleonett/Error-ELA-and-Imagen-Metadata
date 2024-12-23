# Error-ELA-and-Imagen-MetadataImagen
Este programa es una herramienta de computación forense diseñada para analizar imágenes en busca de evidencia de manipulación o edición. Utiliza técnicas avanzadas como el Error Level Analysis (ELA) para detectar áreas de una imagen que han sido modificadas o alteradas. Además, realiza un análisis exhaustivo de los metadatos de la imagen, incluyendo la fecha de creación, la última modificación y el software utilizado para editarla.

El programa es ideal para peritos forenses digitales, analistas de seguridad y cualquier persona interesada en verificar la autenticidad de imágenes digitales.

![image](https://drive.google.com/uc?export=view&id=1Zw_phPfCXatYYoEQS9CRYWPFB48fxTBT)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1lm9JrLej9Hl1wmHz5W-hrKvel5DmXF11#scrollTo=_JQu9bGiVt75)

----

# Funcionalidades principales

01.- Error Level Analysis (ELA):

Detecta áreas de una imagen que han sido modificadas o editadas.
Muestra la imagen original junto con la imagen de ELA para comparar las diferencias.
Ajusta el brillo y el contraste para resaltar las áreas modificadas.
Ajusta el brillo y el contraste para resaltar las áreas modificadas.
02.- Análisis de metadatos:

Extrae y muestra información detallada de los metadatos de la imagen, como:

Fecha y hora de la captura.

Fabricante y modelo de la cámara.

Software utilizado para editar la imagen.

Coordenadas GPS (si están disponibles).

03.- Verificación de manipulación:

Analiza si la imagen ha sido manipulada o alterada en función de los metadatos y el ELA.
Proporciona razones específicas si se detecta manipulación.
04.- Exportación de resultados: Guarda los resultados del análisis en un archivo ZIP que incluye:

*A rchivo de texto con los metadatos y el análisis de manipulación.

Imagen original.
Imagen con ELA.
Cómo usar el programa Configuración del entorno:

Ejecuta la primera celda del programa para configurar el entorno y crear la carpeta EVIDENCIA.

Coloca tu archivo de imagen (.png o .jpg) en la carpeta EVIDENCIA.

Procesamiento de la imagen:

Ejecuta la segunda celda para procesar la imagen y realizar el análisis de ELA.

El programa mostrará la imagen original y la imagen con ELA en una figura.

Resultados:

Los resultados del análisis se guardarán en un archivo ZIP en la carpeta EVIDENCIA.

El archivo ZIP incluirá:

Archivo de texto con los metadatos y el análisis de manipulación.

Imagen original.

Imagen con ELA.



---
# Cómo Citar Este Trabajo
Usa la siguiente entrada BibTeX si utilizas este trabajo en tu investigación:
```bash
@article{joséRLeonett,
  title={Análisis Error de ELA y Matadatos en Imágenes},
  author={José R. Leonett},
  year={2024}
}
```

**Licencia**
- Este proyecto está bajo la licencia MIT. Consulta el archivo LICENSE para más detalles.
