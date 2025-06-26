# lector-inteligente-documentos
Proyecto final - IA aplicada a lectura, resumen y visualización de documentos con ChatGPT y DALL·E

# 📄 Lector Inteligente de Documentos con Generación de Resúmenes y Visualizaciones

### Proyecto Final – Curso de Generación de Prompts con Inteligencia Artificial  
**Autor:** Ricardo Eber Pastrana  
**Comisión:** 84185  

---

## 🧠 Introducción

En el área de control de negocio con proveedores, el análisis de contratos, normas técnicas y documentos funcionales es una tarea crítica pero demandante. Estos documentos suelen ser extensos, técnicos y requieren precisión al momento de identificar requisitos clave. 

Este proyecto propone una solución basada en Inteligencia Artificial que automatice la lectura, análisis y comprensión de estos documentos mediante resúmenes automáticos y visualizaciones generadas a partir de texto.

---

## ⚙️ Presentación del problema

Actualmente, el análisis manual de documentos complejos implica un esfuerzo considerable, lo cual puede derivar en:

- Errores humanos.
- Tiempos excesivos de revisión.
- Dificultades para detectar relaciones conceptuales clave.

Frente a esta necesidad, se busca desarrollar una herramienta inteligente que automatice y agilice este proceso.

---

## 💡 Propuesta de solución

La solución es un sistema basado en IA que:

1. Genera **resúmenes automáticos** de documentos (modelo texto → texto).
2. Produce **check-lists visuales** para verificar cumplimiento de requisitos (modelo texto → imagen).
3. Construye **mapas mentales** a partir de documentos técnicos (modelo texto → imagen).

---

## 🛠️ Tecnologías y herramientas utilizadas

- **OpenAI ChatGPT (GPT-4)** – para resumen de texto y análisis semántico.
- **OpenAI DALL·E** – para generación de imágenes desde texto.
- **Python + Jupyter Notebook** – entorno de desarrollo y demostración.

---

## 🧾 Ejemplos de prompts

- **Resumen de documento:**

Lee el siguiente documento y genera un resumen claro en no más de 10 líneas, enfocándote en los puntos clave y técnicos más importantes.


- **Check-list visual:**

Lee el siguiente contrato y genera una imagen tipo check-list visual que represente si se cumplen los siguientes requisitos: [lista de requisitos].


- **Mapa mental:**

A partir del siguiente texto técnico, genera un mapa mental en formato imagen que resuma los conceptos principales y cómo se relacionan entre sí.


---

## ✅ Objetivos

- Automatizar la lectura y resumen de documentos extensos y técnicos.
- Detectar visualmente el cumplimiento de requisitos en contratos.
- Mejorar la comprensión conceptual de documentos funcionales mediante mapas mentales.

---

## 🔬 Metodología

1. Cargar el documento (PDF o texto).
2. Extraer el texto relevante.
3. Aplicar prompts con modelos de lenguaje (ChatGPT) y de generación de imágenes (DALL·E).
4. Mostrar resultados visuales y textuales en un Jupyter Notebook.

---

## 📈 Justificación de viabilidad

El proyecto es viable técnica y logísticamente, ya que:

- Se cuenta con documentación real para probar.
- Las herramientas (OpenAI, Python, Jupyter) son accesibles dentro del marco del curso.
- Existen desafíos previstos como:
- Confidencialidad de ciertos documentos.
- Alta complejidad técnica en algunos textos.

Pero estos desafíos son manejables y no impiden la ejecución del proyecto.

---

## 📁 Contenidos del repositorio

📦 lector-inteligente-documentos
├── README.md
├── PoC_Lector_Inteligente.ipynb
├── /docs
│ ├── documento_funcional_ejemplo.pdf
│ └── contrato_modelo.pdf


---

## 🚀 Cómo ejecutar la PoC

1. Clonar el repositorio.
2. Instalar las dependencias necesarias (PyMuPDF, openai).
3. Ejecutar el notebook `PoC_Lector_Inteligente.ipynb`.
4. Seguir las celdas para cargar un documento y generar el resumen y visualizaciones.

---

## 📌 Entrega Final – Consignas Resueltas
## 🧪 Metodología
El proyecto se lleva a cabo mediante los siguientes procedimientos:

- Carga y extracción del texto: se utiliza PyMuPDF para extraer el contenido de documentos PDF cargados desde una carpeta local.
- Preprocesamiento: se recorta el texto a los primeros 3000 caracteres para optimizar el uso de tokens.
- Generación de resumen: se utiliza un prompt bien definido con el modelo GPT-4 para obtener un resumen claro y enfocado.
- Generación visual: se solicita a DALL·E una imagen representativa (ej. check-list o mapa mental) a partir del texto.
- Presentación: los resultados se presentan de manera clara y reproducible en un Jupyter Notebook.
- Justificación: Esta metodología asegura claridad, eficiencia y sostenibilidad. Se basa en herramientas accesibles y potentes que permiten escalar la solución a casos reales.

## ⚙️ Herramientas y tecnologías
- Herramientas utilizadas:

1.Python 3 + Jupyter Notebook

2.OpenAI API: ChatGPT (GPT-4) y DALL·E

3.PyMuPDF para manejo de PDFs

- Técnicas de fast prompting:

1.Prompts claros y específicos: delimitan el tipo de salida esperada (longitud, foco temático, formato visual).

2. Chaining lógico de prompts: cada función (resumen, imagen) tiene su propio prompt, evitando ambigüedad.

3.Optimización del contexto: se limita el texto enviado al modelo para mejorar performance.

4.Estilo instructivo en los prompts: se utiliza lenguaje directo e imperativo ("Genera...", "Lee el siguiente documento...").


## ✅ Conclusiones
Se logró automatizar el análisis de documentos con una interfaz clara y accesible.

Los objetivos de generar resúmenes útiles y visualizaciones relevantes se cumplieron satisfactoriamente.

El proyecto es viable, escalable y puede adaptarse fácilmente a casos reales del entorno corporativo.

Futuras mejoras podrían incluir:

1.Clasificación automática de tipo de documento.
2.Personalización de prompts según área o industria.
3.Evaluación por múltiples modelos para validar precisión.

## 🎨 Prompt texto-imagen:

1. Crea una imagen escena dividida en dos mitades. A la izquierda, una persona abrumada y estresada en una oficina desordenada, rodeada de montañas de papeles, contratos y documentos técnicos esparcidos por todos lados. El ambiente es caótico y con colores apagados. A la derecha, la misma persona sonriente, en un escritorio ordenado y moderno, utilizando un lector de documentos inteligente con aspecto tecnológico (pantalla futurista, interfaz limpia). Todo está organizado digitalmente, con iconos de resúmenes, visualizaciones y check-lists. El entorno es luminoso, limpio y tecnológico.


![ChatGPT Image 26 jun 2025, 20_12_52](https://github.com/user-attachments/assets/51b24778-cac5-4762-ae26-e3c2bab0226c)

2.Crea una imagen super realista escena dividida en dos mitades. A la izquierda, una persona abrumada y estresada en una oficina desordenada, rodeada de montañas de papeles, contratos y documentos técnicos esparcidos por todos lados. El ambiente es caótico y con colores apagados. A la derecha, la misma persona sonriente, en un escritorio ordenado y moderno, utilizando un lector de documentos inteligente con aspecto tecnológico (pantalla futurista, interfaz limpia), que diga "Lector de documentos ingeligente" en la pantalla. Todo está organizado digitalmente, con iconos de resúmenes, visualizaciones y check-lists. El entorno es luminoso, limpio y tecnológico.

![ChatGPT Image 26 jun 2025, 20_45_33](https://github.com/user-attachments/assets/95f3737f-3e97-4c08-ba72-b44396e8fee0)


## 📬 Contacto

Para consultas, sugerencias o colaboraciones:  
📧 eberpastrana@gmail.com

---
