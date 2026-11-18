# TraceLab
### Sistema interactivo de memoria visual mediante procesamiento digital de imágenes y visión computacional

**Asignatura:** Procesamiento Digital de Imágenes  
**Profesor:** Nicolás Llanos Neuta  
**Proyecto:** TraceLab  
**Estado:** En desarrollo

---

## 1. Descripción del proyecto

TraceLab es un sistema interactivo que busca evaluar la memoria visual y la capacidad de reproducción de imágenes mediante técnicas de procesamiento digital de imágenes y visión computacional.

La aplicación propone una experiencia en la que el usuario observa una imagen de referencia, intenta reproducirla mediante un dibujo y posteriormente carga una fotografía o imagen de su creación. El sistema procesa ambas imágenes y calcula un porcentaje de similitud visual, permitiendo identificar coincidencias y diferencias entre la referencia original y el dibujo realizado.

El sistema contempla dos modalidades de trabajo: mandalas y siluetas, además de diferentes niveles de dificultad.

### 1.1 Problemática

La memoria visual y la percepción de formas son capacidades importantes en la interpretación y reproducción de expresiones gráficas presentes en el arte y la cultura.

Sin embargo, no siempre se dispone de herramientas interactivas que permitan comparar de manera cuantitativa una imagen observada previamente con una reproducción realizada por una persona.

Esta situación plantea la necesidad de desarrollar una solución tecnológica que permita analizar las semejanzas y diferencias entre imágenes, utilizando técnicas de procesamiento digital de imágenes y visión computacional.

### 1.2 Justificación

El desarrollo de TraceLab permite integrar los conocimientos adquiridos en la asignatura de Procesamiento Digital de Imágenes mediante una aplicación práctica e interactiva.

El proyecto busca aprovechar técnicas de análisis visual para comparar dibujos e imágenes de referencia, ofreciendo resultados cuantitativos y representaciones visuales que faciliten la interpretación del desempeño del usuario.

Además, permite explorar la aplicación de estas tecnologías en el análisis de representaciones gráficas relacionadas con el arte, los patrones geométricos y las formas visuales.

### 1.3 Objetivo general

Diseñar e implementar un sistema interactivo basado en procesamiento digital de imágenes y visión computacional que permita evaluar la similitud visual entre imágenes de referencia y dibujos realizados por los usuarios, mediante una experiencia de memoria visual con mandalas y siluetas.

### 1.4 Objetivos específicos

- Identificar y preparar imágenes de referencia correspondientes a las modalidades de mandalas y siluetas.
- Implementar técnicas de procesamiento digital de imágenes para preparar y analizar las imágenes de entrada.
- Desarrollar un método de comparación que permita medir la similitud entre la imagen original y la reproducción realizada por el usuario.
- Diseñar una interfaz gráfica interactiva que permita seleccionar modalidades, niveles de dificultad, visualizar imágenes y cargar dibujos.
- Evaluar el desempeño del sistema mediante pruebas experimentales y métricas cuantitativas.
- Documentar la arquitectura, implementación, resultados y funcionamiento de la solución desarrollada.

### 1.5 Solución propuesta

Se propone TraceLab, una aplicación desarrollada en Python mediante Streamlit, que permite:

1. Seleccionar una modalidad: mandalas o siluetas.
2. Elegir un nivel de dificultad: fácil, intermedio o difícil.
3. Observar una imagen de referencia durante un tiempo determinado.
4. Reproducir la imagen mediante un dibujo.
5. Cargar una fotografía o imagen de la reproducción.
6. Procesar y comparar las dos imágenes.
7. Obtener un porcentaje de similitud y una visualización de las diferencias encontradas.

---

## 2. Arquitectura del sistema

**Estado: Pendiente de documentación y diagrama definitivo.**

En este apartado se incorporará el diagrama de arquitectura completo del sistema, identificando los módulos, sus conexiones y el flujo de información desde la entrada de las imágenes hasta la presentación de resultados.

**Espacio para el diagrama de arquitectura:**

[INSERTAR AQUÍ EL DIAGRAMA DE ARQUITECTURA]

Componentes por documentar:
- Entrada y selección de imágenes.
- Interfaz gráfica.
- Preprocesamiento.
- Comparación de imágenes.
- Cálculo de métricas.
- Visualización de resultados.

---

## 3. Metodología

**Estado: En construcción.**

Se documentarán las etapas metodológicas del proyecto:

1. Adquisición y organización de los datos.
2. Preparación y preprocesamiento de imágenes.
3. Implementación de técnicas de procesamiento digital de imágenes.
4. Desarrollo del método de comparación visual.
5. Integración con la interfaz gráfica.
6. Pruebas y evaluación del desempeño.

**Técnicas y métodos implementados:** completar con la descripción técnica definitiva del notebook.

---

## 4. Implementación

**Estado: En desarrollo.**

El proyecto utiliza Python como lenguaje principal.

### Tecnologías identificadas

- Python.
- Streamlit: desarrollo de la interfaz gráfica.
- Pillow (PIL): manejo y visualización de imágenes.
- Pandas: organización y consulta de datos.
- NumPy: operaciones numéricas y procesamiento de imágenes.
- Matplotlib: visualización de resultados experimentales.

### Organización del código

| Archivo | Función |
|---|---|
| app.py | Interfaz gráfica de TraceLab. |
| procesamiento.py | Funciones y configuración del procesamiento. |
| comparador.py | Comparación de imágenes y generación de resultados. |
| Notebook principal | Desarrollo experimental y pruebas. |

*La ubicación definitiva de los módulos se actualizará cuando se organice el código fuente.*

---

## 5. Datos

**Estado: Pendiente de documentación completa.**

El sistema trabaja con imágenes de referencia correspondientes a dos modalidades:

- Mandalas.
- Siluetas.

Se documentarán:
- Procedencia del conjunto de datos.
- Cantidad de imágenes.
- Características y formatos.
- Distribución de entrenamiento, validación y retos, si corresponde.
- Ejemplos visuales.
- Enlace de acceso al conjunto de datos.

**Enlace del conjunto de datos:** [PENDIENTE]

**Ejemplos de imágenes:** [INSERTAR EVIDENCIAS]

---

## 6. Interfaz gráfica de usuario

La interfaz gráfica fue desarrollada utilizando Streamlit.

Actualmente contempla las siguientes funcionalidades:

- Pantalla de bienvenida.
- Selección de modalidad.
- Selección del nivel de dificultad.
- Visualización temporal de la imagen de referencia.
- Carga de dibujos realizados por el usuario.
- Análisis de similitud visual.
- Visualización de la imagen original, reproducción y mapa de diferencias.
- Presentación de métricas e interpretación de resultados.

**Evidencias visuales:**

[INSERTAR CAPTURA DE LA PANTALLA DE INICIO]

[INSERTAR CAPTURA DE LA SELECCIÓN DE MODALIDAD]

[INSERTAR CAPTURA DEL PROCESO DE COMPARACIÓN]

[INSERTAR CAPTURA DE LOS RESULTADOS]

**Enlace de acceso a la aplicación:** [PENDIENTE DE DEFINIR URL ESTABLE]

---

## 7. Resultados y evaluación

**Estado: Pendiente de consolidación de resultados experimentales.**

En esta sección se incorporarán las pruebas realizadas con datos reales y las métricas utilizadas para evaluar el desempeño del sistema.

Se incluirán:
- Resultados cuantitativos.
- Métricas de evaluación.
- Tablas y gráficas comparativas.
- Ejemplos de imágenes procesadas.
- Análisis de coincidencias y diferencias.
- Limitaciones identificadas.

[INSERTAR TABLAS DE RESULTADOS]

[INSERTAR GRÁFICAS DE EVALUACIÓN]

[INSERTAR EJEMPLOS VISUALES]

---

## 8. Conclusiones

**Estado: Pendiente de completar después de la evaluación final.**

Se presentarán las conclusiones obtenidas a partir de los resultados experimentales, considerando:

- Cumplimiento de los objetivos.
- Desempeño del sistema.
- Aportes del procesamiento digital de imágenes.
- Limitaciones encontradas.
- Posibles mejoras y trabajos futuros.

---

## 9. Instalación y ejecución

### Requisitos

- Python 3.
- pip.
- Dependencias del proyecto.

### Instalación

Clonar el repositorio:

```bash
git clone https://github.com/marianaarengif/Tracelab-procesamiento-de-imagenes.git
cd Tracelab-procesamiento-de-imagenes
```

Instalar las dependencias (cuando esté disponible el archivo):

```bash
pip install -r requirements.txt
```

### Ejecución

Cuando se encuentre organizada la estructura definitiva:

```bash
streamlit run app/app.py
```

*La ruta de ejecución se actualizará según la organización final de los archivos.*

---

## 10. Video demostrativo

**Estado: Pendiente.**

[INSERTAR ENLACE AL VIDEO DEMOSTRATIVO DE MÁXIMO 3 MINUTOS]

---

## 11. Autores

**Integrantes del equipo:**

- Maria Jose Asprilla Medina
- Mariana Rengifo Quintero


**Docente:** Nicolás Llanos Neuta  
**Asignatura:** Procesamiento Digital de Imágenes.

---

## 12. Estado del proyecto

TraceLab se encuentra en desarrollo. La interfaz gráfica y las funcionalidades principales de interacción están implementadas. Se continúa trabajando en la consolidación de la documentación técnica, arquitectura, metodología y evaluación experimental del sistema.
