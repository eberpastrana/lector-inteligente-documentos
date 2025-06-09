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

## 📬 Contacto

Para consultas, sugerencias o colaboraciones:  
📧 eberpastrana@gmail.com

---
