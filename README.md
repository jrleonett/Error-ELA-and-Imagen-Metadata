# Análisis de metadatos y Error de ELA en imágenes digitales

![Licencia](https://img.shields.io/badge/Licencia-GNU%20GPL%20v3-blue)
![GitHub](https://img.shields.io/badge/Python-3.8%2B-green)
![GitHub](https://img.shields.io/badge/Estado-Activo-brightgreen)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)

Este programa es una herramienta de computación forense diseñado para analizar imágenes en busca de evidencia de manipulación o edición. Utiliza la técnica de Error Level Analysis (ELA) para detectar áreas de una imagen de formatos `.JPG` o `.PNG` que han sido modificadas o alteradas. Además, realiza un análisis exhaustivo de los metadatos de la imagen, incluyendo la fecha de creación, la última modificación y el software utilizado para editarla.

Este programa fué desarrollado por **José R. Leonett** para los peritos forenses digitales, analistas forenses o cualquier persona interesada en verificar la autenticidad de imágenes digitales.

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

# **Interfaz gráfica con Gradio en huggingface**
- Interfaz amigable para cargar y analizar imágenes.
- Muestra los resultados del análisis de ELA (Error Level Analysis) y metadatos en tiempo real.
- Disponible en Hugging Face Spaces para uso público.
- 👉 **Pruébalo aquí**: [https://huggingface.co/spaces/leonett/error-ela](https://huggingface.co/spaces/leonett/error-ela)

<p align="center">
  <img src="https://github.com/jrleonett/Error-ELA-and-Imagen-Metadata/blob/main/huggifaces.png"/>
</p>

<p align="center">
  <a href="https://huggingface.co/spaces/leonett/error-ela">
    <img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Open in Hugging Face" width="150"/>
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
- - Este proyecto está bajo la licencia GNU General Public License v3.0. Consulta el archivo LICENSE para más detalles.
