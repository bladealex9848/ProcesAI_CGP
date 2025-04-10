# ProcesAI CGP 📘

![Logo de ProcesAI CGP](https://raw.githubusercontent.com/bladealex9848/ProcesAI_CGP/main/logo.png)

[![Version](https://img.shields.io/badge/versión-1.0.0-darkgreen.svg)](https://github.com/bladealex9848/ProcesAI_CGP)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![Streamlit](https://img.shields.io/badge/Streamlit-1.30.0-ff4b4b.svg)](https://streamlit.io/)
[![OpenAI](https://img.shields.io/badge/OpenAI_API-v2-00C244.svg)](https://platform.openai.com/)
[![Licencia](https://img.shields.io/badge/Licencia-MIT-yellow.svg)](LICENSE)
[![Visitantes](https://api.visitorbadge.io/api/visitors?path=https%3A%2F%2Fprocesai.streamlit.app&label=Visitantes&labelColor=%235d5d5d&countColor=%231e7ebf&style=flat)](https://procesai.streamlit.app)

## 📘 Descripción

ProcesAI CGP es un asistente virtual especializado en el Código General del Proceso y la Teoría General del Proceso en Colombia, desarrollado con Streamlit y la API de OpenAI. Su base de conocimiento incluye la Ley 1564 de 2012 (Código General del Proceso) y los fundamentos doctrinales de la teoría procesal colombiana.

Este asistente está diseñado para proporcionar información precisa y actualizada sobre el derecho procesal colombiano a abogados, jueces, estudiantes de derecho y cualquier persona interesada en comprender los procedimientos judiciales en Colombia, facilitando el acceso y comprensión de esta compleja normativa.

## 🔍 Funcionalidades Principales

### 1. Código General del Proceso
- **Artículos Específicos**: Información detallada sobre cualquier artículo de la Ley 1564 de 2012
- **Interpretación Normativa**: Explicación contextualizada de las disposiciones del CGP
- **Modificaciones y Vigencia**: Información sobre reformas y estado actual de las normas
- **Análisis Sistemático**: Relación entre diferentes artículos y secciones del Código

### 2. Procedimientos Judiciales
- **Procesos Declarativos**: Información sobre procesos verbales y verbales sumarios
- **Procesos Ejecutivos**: Explicación sobre cobro de obligaciones y ejecución de títulos
- **Procesos de Familia**: Detalles sobre trámites en asuntos familiares
- **Procesos de Insolvencia**: Información sobre reorganización y liquidación patrimonial

### 3. Aspectos Procesales Fundamentales
- **Competencia y Jurisdicción**: Explicación sobre reglas de asignación de procesos
- **Actos Procesales**: Información sobre demandas, contestaciones, audiencias y providencias
- **Medidas Cautelares**: Tipos, requisitos y procedimientos para su solicitud
- **Términos y Plazos**: Cómputos de términos procesales y prórrogas

### 4. Recursos y Medios de Impugnación
- **Recursos Ordinarios**: Información sobre reposición, apelación y súplica
- **Recursos Extraordinarios**: Explicación sobre casación y revisión
- **Nulidades Procesales**: Causales, oportunidad y trámite de las nulidades
- **Control de Legalidad**: Mecanismos de saneamiento del proceso

### 5. Análisis de Documentos
- **Procesamiento Avanzado**: Análisis de documentos jurídicos mediante tecnología especializada
- **Evaluación Procesal**: Análisis preliminar de casos desde la perspectiva procesal
- **Identificación de Elementos Clave**: Detección de aspectos relevantes en expedientes
- **Sugerencias Normativas**: Referencias a artículos aplicables del CGP y jurisprudencia

## 🚀 Instalación

### Requisitos Previos
- Python 3.8 o superior
- Pip (administrador de paquetes de Python)
- Cuenta en OpenAI con acceso a la API
- Asistente ProcesAI CGP configurado en OpenAI

### Pasos de Instalación

1. **Clonar el repositorio**
   ```bash
   git clone https://github.com/bladealex9848/ProcesAI_CGP.git
   cd ProcesAI_CGP
   ```

2. **Crear un entorno virtual (recomendado)**
   ```bash
   python -m venv venv
   
   # En Windows
   venv\Scripts\activate
   
   # En macOS/Linux
   source venv/bin/activate
   ```

3. **Instalar las dependencias**
   ```bash
   pip install -r requirements.txt
   ```

4. **Configurar credenciales**

   **Opción A: Usando variables de entorno**
   ```bash
   # En Windows
   set OPENAI_API_KEY=tu-api-key-aqui
   set ASSISTANT_ID=tu-assistant-id-aqui
   
   # En macOS/Linux
   export OPENAI_API_KEY=tu-api-key-aqui
   export ASSISTANT_ID=tu-assistant-id-aqui
   ```

   **Opción B: Usando archivo secrets.toml**
   
   Crea un archivo `.streamlit/secrets.toml` con el siguiente contenido:
   ```toml
   OPENAI_API_KEY = "tu-api-key-aqui"
   ASSISTANT_ID = "tu-assistant-id-aqui"
   ```

## ⚙️ Uso

### Iniciar la Aplicación

```bash
streamlit run app.py
```

Esto lanzará la aplicación y abrirá automáticamente una ventana del navegador en `http://localhost:8501`.

### Funcionalidades del Asistente

1. **Consultas sobre el CGP**
   - Pregunta sobre artículos específicos o instituciones procesales
   - Ejemplo: "¿Qué establece el artículo 90 del CGP sobre la interrupción de la prescripción?"

2. **Información sobre Procedimientos**
   - Consulta sobre tipos de procesos y sus trámites
   - Ejemplo: "¿Cuál es el procedimiento para un proceso verbal sumario de mínima cuantía?"

3. **Consultas sobre Recursos**
   - Obtén información sobre medios de impugnación y sus requisitos
   - Ejemplo: "¿Cuáles son los requisitos para interponer un recurso de casación civil?"

4. **Análisis de Documentos**
   - Sube documentos para recibir un análisis desde la perspectiva procesal
   - El asistente puede procesar demandas, recursos o providencias judiciales

5. **Referencia Normativa**
   - Solicita información sobre normativa específica o jurisprudencia relevante
   - Ejemplo: "¿Qué ha dicho la Corte Suprema sobre la carga dinámica de la prueba?"

## ⚠️ Limitaciones

- ProcesAI CGP proporciona información general y no constituye asesoramiento legal personalizado
- La información se basa en el conocimiento disponible hasta octubre de 2023
- Para casos específicos, siempre es recomendable consultar con un abogado especializado
- El análisis de documentos es preliminar y no reemplaza la revisión profesional

## 📊 Escenarios de Uso

### 1. Abogados Litigantes
- Consulta rápida de artículos del CGP en medio de audiencias
- Verificación de términos y requisitos procesales
- Análisis preliminar de documentos judiciales

### 2. Jueces y Funcionarios Judiciales
- Referencia normativa para fundamentación de decisiones
- Consulta sobre precedentes jurisprudenciales
- Verificación de procedimientos especiales

### 3. Estudiantes de Derecho
- Apoyo en el estudio del derecho procesal
- Comprensión de conceptos y procedimientos
- Preparación para exámenes y trabajos académicos

## 👥 Contribuciones

Las contribuciones son bienvenidas. Para contribuir al desarrollo de ProcesAI CGP:

1. Realiza un fork del repositorio
2. Crea una nueva rama (`git checkout -b feature/nueva-funcionalidad`)
3. Implementa tus cambios
4. Envía un pull request

## 📝 Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más detalles.

## 🙏 Agradecimientos

- **OpenAI** por proporcionar la tecnología que impulsa el asistente
- **Streamlit** por facilitar el desarrollo de interfaces intuitivas
- **Comunidad jurídica colombiana** por su contribución al derecho procesal

## 👤 Autor

Creado con ❤️ por [Alexander Oviedo Fadul](https://github.com/bladealex9848)

[GitHub](https://github.com/bladealex9848) | [Website](https://alexanderoviedofadul.dev/) | [LinkedIn](https://www.linkedin.com/in/alexander-oviedo-fadul/) | [Instagram](https://www.instagram.com/alexander.oviedo.fadul) | [Twitter](https://twitter.com/alexanderofadul) | [Facebook](https://www.facebook.com/alexanderof/) | [WhatsApp](https://api.whatsapp.com/send?phone=573015930519&text=Hola%20!Quiero%20conversar%20contigo!%20)

---

## 💼 Mensaje Final

ProcesAI CGP busca democratizar el acceso a la información sobre derecho procesal en Colombia, facilitando la comprensión de conceptos jurídicos complejos. Aunque este asistente proporciona información valiosa, recuerda que cada caso judicial es único y puede requerir orientación profesional personalizada.

*"El conocimiento de las reglas procesales es fundamental para garantizar el acceso efectivo a la justicia y el debido proceso como pilares del Estado Social de Derecho."*