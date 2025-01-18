# Análisis de metadatos y Error de ELA en imágenes digitales
Este programa es una herramienta de computación forense diseñado para analizar imágenes en busca de evidencia de manipulación o edición. Utiliza la técnica de Error Level Analysis (ELA) para detectar áreas de una imagen de formatos `.JPG` o `.PNG` que han sido modificadas o alteradas. Además, realiza un análisis exhaustivo de los metadatos de la imagen, incluyendo la fecha de creación, la última modificación y el software utilizado para editarla.

Este programa fué desarrollado por **José R. Leonett** para los peritos forenses digitales, analistas forenses o cualquier persona interesada en verificar la autenticidad de imágenes digitales.

![image](https://drive.google.com/uc?export=view&id=1Zw_phPfCXatYYoEQS9CRYWPFB48fxTBT)

<p align="center">
  <a href="https://colab.research.google.com/drive/19Xdff7WpNvjNQfAcYEv6u-wI28pzBNk7#scrollTo=m-lBAEqvbRUA&line=1&uniqifier=1">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
  </a>
</p>

----

# Funcionalidades principales.

**01.- Error Level Analysis (ELA):**

* Detecta áreas de una imagen que han sido modificadas o editadas.
* Muestra la imagen original junto con la imagen de ELA para comparar las diferencias.
* Ajusta el brillo y el contraste para resaltar las áreas modificadas.


**02.- Análisis de metadatos:**
* Extrae y muestra información detallada de los metadatos de la imagen, como:
   - Fecha y hora de la captura.
   - Fabricante y modelo de la cámara.
   - Software utilizado para editar la imagen.
   - Coordenadas GPS (si están disponibles).

**03.- Verificación de manipulación:**
* Analiza si la imagen ha sido manipulada o alterada en función de los metadatos y el ELA.
* Proporciona razones específicas si se detecta manipulación.

**04.- Análisis de información en pantalla (COLAB):**
* Todos los metadatos y el análisis de manipulación.
* La imagen original.
* La imagen con el análisis de ELA.

# **Interfaz gráfica con Gradio**.
* Interfaz amigable para cargar y analizar imágenes.
* Muestra los resultados del análisis de ELA y metadatos en tiempo real.
* Genera enlaces públicos para compartir el análisis (usando Gradio y ngrok).

<p align="center">
  <img src="https://github.com/jrleonett/Error-ELA-and-Imagen-MetadataImagen/raw/main/congradio02.png"/>
</p>

<p align="center">
  <a href="https://colab.research.google.com/drive/1R_2gv2seXsYQ5LqTGRXowzZKzUvH2CYM#scrollTo=9c2sZjfmuFEc">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
  </a>
</p>

---
# Cómo usar el programa
**Configuración del entorno:**
* Ejecuta la primera celda del programa para instalar las dependencias necesarias.
* El programa generará automáticamente un enlace público para acceder a la interfaz de Gradio.

**Uso de la interfaz de Gradio:**
* Sube una imagen (`.JPG` o `.PNG`) a través de la interfaz de Gradio.
* El programa procesará la imagen y mostrará:
   - La imagen original.
   - La imagen con el análisis de ELA.
   - Los metadatos y el análisis de manipulación.

**Resultados:**
* Los resultados del análisis se mostrarán directamente en la interfaz de Gradio.
* También puedes acceder a los resultados a través de los enlaces públicos generados por Gradio y ngrok.

**El archivo ZIP para Colab incluirá:**
   * Un archivo de texto con los metadatos y el análisis de manipulación.
   * La imagen original analizada.
   * La imagen con análisis de ELA.

---
# Cómo citar este trabajo.
Usa la siguiente entrada BibTeX si utilizas este trabajo en tu investigación:
```bash
@article{joséRLeonett,
  title={Análisis Error de ELA y Matadatos en imágenes digitales},
  author={José R. Leonett},
  year={2024}
}
```

**Licencia.**
- Este proyecto está bajo la licencia MIT. Consulta el archivo LICENSE para más detalles.
