# Planificación Temporal del TFG
## Aplicación de Voissnet a Señales Sísmicas Volcánicas de Tenerife

**Periodo:** Octubre 2025 - Junio 2026

---

## Fase 1: Familiarización y Fundamentos (Octubre - Noviembre)

### Octubre 2025
**Objetivos:**
- Comprender los fundamentos de sismología volcánica
- Familiarizarse con los datos sísmicos de Tenerife
- Revisar la arquitectura de Voissnet

**Tareas:**
- [ ] Revisar la documentación de Voissnet (https://github.com/darren-tpk/voiss-net)
- [ ] Estudiar los fundamentos de redes neuronales para clasificación de señales sísmicas
- [ ] Investigar las características de los volcanes de Tenerife (Teide, sistema volcánico)
- [ ] Contactar con el IGN (Instituto Geográfico Nacional) u otras fuentes de datos sísmicos
- [ ] Revisar literatura científica sobre clasificación de señales sísmicas volcánicas

**Entregables:**
- Resumen de la arquitectura de Voissnet
- Informe sobre el contexto volcánico de Tenerife
- Lista de fuentes de datos disponibles

### Noviembre 2025
**Objetivos:**
- Comprender los estándares de datos sísmicos
- Configurar el entorno de desarrollo
- Obtener acceso a los datos

**Tareas:**
- [ ] Estudiar los formatos de datos sísmicos (MiniSEED, SAC, ASDF)
- [ ] Aprender a usar herramientas como ObsPy para procesamiento de datos sísmicos
- [ ] Configurar entorno Python con las dependencias de Voissnet
- [ ] Obtener datasets de prueba de señales sísmicas de Tenerife
- [ ] Familiarizarse con las estaciones sismográficas de Tenerife

**Entregables:**
- Documento sobre estándares y formatos de datos sísmicos
- Entorno de desarrollo configurado y funcional
- Primeros datasets descargados y verificados

---

## Fase 2: Procesamiento y Análisis de Datos (Diciembre - Enero)

### Diciembre 2025
**Objetivos:**
- Explorar y analizar los datos sísmicos de Tenerife
- Implementar pipeline de preprocesamiento

**Tareas:**
- [ ] Cargar y visualizar señales sísmicas usando ObsPy
- [ ] Analizar características de las señales (frecuencia, amplitud, duración)
- [ ] Identificar tipos de eventos sísmicos en los datos (tremor, LP, VT, etc.)
- [ ] Implementar filtrado y normalización de señales
- [ ] Crear scripts de preprocesamiento de datos

**Entregables:**
- Notebook con análisis exploratorio de datos
- Pipeline de preprocesamiento documentado
- Visualizaciones de diferentes tipos de eventos sísmicos

### Enero 2026
**Objetivos:**
- Construir dataset etiquetado para entrenamiento
- Establecer métricas de evaluación

**Tareas:**
- [ ] Etiquetar señales sísmicas según categorías de Voissnet
- [ ] Adaptar taxonomía de eventos para el contexto de Tenerife
- [ ] Dividir dataset en conjuntos de entrenamiento, validación y test
- [ ] Implementar aumento de datos (data augmentation) si es necesario
- [ ] Definir métricas de evaluación (accuracy, F1-score, matriz de confusión)

**Entregables:**
- Dataset etiquetado y dividido
- Documento de taxonomía de eventos adaptada
- Protocolo de evaluación definido

---

## Fase 3: Adaptación e Implementación de Voissnet (Febrero - Marzo)

### Febrero 2026
**Objetivos:**
- Adaptar Voissnet a los datos de Tenerife
- Realizar primeras pruebas de entrenamiento

**Tareas:**
- [ ] Clonar y comprender el código fuente de Voissnet
- [ ] Adaptar la arquitectura a las características de los datos locales
- [ ] Configurar hiperparámetros iniciales
- [ ] Implementar data loaders para los datos de Tenerife
- [ ] Realizar entrenamientos preliminares con subconjuntos de datos

**Entregables:**
- Código de Voissnet adaptado
- Configuración de hiperparámetros documentada
- Resultados preliminares de entrenamiento

### Marzo 2026
**Objetivos:**
- Optimizar el modelo
- Realizar entrenamiento completo

**Tareas:**
- [ ] Ajustar hiperparámetros (learning rate, batch size, etc.)
- [ ] Entrenar el modelo con el dataset completo
- [ ] Implementar técnicas de regularización si hay overfitting
- [ ] Validar el modelo con el conjunto de validación
- [ ] Realizar análisis de errores y casos problemáticos

**Entregables:**
- Modelo entrenado y guardado
- Gráficas de entrenamiento (loss, accuracy)
- Análisis de rendimiento del modelo

---

## Fase 4: Evaluación y Experimentación (Abril)

### Abril 2026
**Objetivos:**
- Evaluar el modelo exhaustivamente
- Realizar experimentos comparativos

**Tareas:**
- [ ] Evaluar el modelo en el conjunto de test
- [ ] Generar matrices de confusión y métricas detalladas
- [ ] Comparar con métodos baseline o tradicionales
- [ ] Realizar ablation studies (importancia de componentes del modelo)
- [ ] Analizar casos de éxito y fracaso del modelo
- [ ] Visualizar embeddings o representaciones aprendidas

**Entregables:**
- Informe completo de evaluación
- Comparativas con otros métodos
- Análisis cualitativo de resultados

---

## Fase 5: Documentación y Redacción (Mayo - Junio)

### Mayo 2026
**Objetivos:**
- Redactar la memoria del TFG
- Preparar visualizaciones y figuras

**Tareas:**
- [ ] Escribir introducción y estado del arte
- [ ] Documentar la metodología empleada
- [ ] Describir los experimentos realizados
- [ ] Redactar sección de resultados
- [ ] Crear figuras, tablas y gráficas de calidad
- [ ] Discutir limitaciones y trabajo futuro

**Entregables:**
- Borrador completo de la memoria
- Figuras y tablas finalizadas
- Código bien documentado y organizado

### Primera quincena de Junio 2026
**Objetivos:**
- Finalizar la memoria
- Preparar la presentación

**Tareas:**
- [ ] Revisar y corregir la memoria
- [ ] Incorporar feedback del tutor
- [ ] Preparar presentación (slides)
- [ ] Preparar repositorio GitHub con código y documentación
- [ ] Crear README detallado del proyecto
- [ ] Preparar demo o notebook interactivo

**Entregables:**
- Memoria final del TFG
- Presentación preparada
- Repositorio público completo

### Segunda quincena de Junio 2026
**Objetivos:**
- Defender el TFG

**Tareas:**
- [ ] Ensayar la presentación
- [ ] Preparar respuestas a posibles preguntas del tribunal
- [ ] Defensa del TFG

**Entregables:**
- Defensa exitosa del TFG

---

## Recursos Necesarios

### Software y Herramientas
- Python 3.8+
- PyTorch / TensorFlow (según implementación de Voissnet)
- ObsPy para procesamiento de señales sísmicas
- Jupyter Notebooks para análisis
- Git/GitHub para control de versiones
- LaTeX para redacción de memoria

### Datos
- Registros sísmicos de estaciones de Tenerife
- Catálogos de eventos sísmicos del IGN
- Posibles datasets de referencia (si existen)

### Bibliografía Clave
- Paper original de Voissnet
- Artículos sobre clasificación de señales sísmicas volcánicas
- Documentación técnica de sismología volcánica
- Estudios previos sobre el sistema volcánico de Tenerife

---

## Hitos Principales

| Mes | Hito |
|-----|------|
| Noviembre | Entorno configurado y datos adquiridos |
| Enero | Dataset etiquetado completo |
| Marzo | Modelo Voissnet entrenado |
| Abril | Evaluación completa finalizada |
| Mayo | Borrador de memoria completo |
| Junio | Defensa del TFG |

---

## Riesgos y Mitigación

### Riesgos Identificados
1. **Dificultad para obtener datos**: Los datos sísmicos pueden tener restricciones de acceso
   - *Mitigación:* Contactar con IGN y otras instituciones con antelación

2. **Calidad de los datos**: Los datos pueden tener ruido o estar incompletos
   - *Mitigación:* Planificar tiempo suficiente para limpieza de datos

3. **Adaptación de Voissnet**: La arquitectura puede requerir modificaciones significativas
   - *Mitigación:* Comenzar con implementación base y adaptar gradualmente

4. **Tiempo insuficiente**: Las tareas pueden tomar más tiempo del estimado
   - *Mitigación:* Comenzar temprano y mantener comunicación regular con el tutor

5. **Problemas técnicos**: Dificultades con recursos computacionales para entrenamiento
   - *Mitigación:* Explorar alternativas como Google Colab, recursos universitarios

---

## Notas Adicionales

- **Reuniones con el tutor:** Se recomienda mantener reuniones quincenales para seguimiento
- **Documentación continua:** Documentar el trabajo desde el inicio para facilitar la redacción final
- **Control de versiones:** Usar Git desde el principio para mantener historial del código
- **Backup:** Mantener copias de seguridad regulares de datos y código

---

*Última actualización: Octubre 2025*
