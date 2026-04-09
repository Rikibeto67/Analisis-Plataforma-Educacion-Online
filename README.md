📊 Proyecto de Ciencia de Datos – Análisis Exploratorio y Predictivo
👤 Autor
Richard Sepúlveda Martínez  
👨‍💼 Ingeniero Civil Industrial mención Informática (PMP®) | 🎓 Docente en Gerencia de Proyectos | 📈 En formación en Ciencia de Datos

📌 Introducción
Este proyecto corresponde a un ciclo completo de análisis que parte desde la exploración y preparación de datos hasta la construcción, optimización y evaluación de modelos predictivos, incluyendo el procesamiento a escala con Apache Spark.

Caso de estudio: EduTech Analytics, una plataforma de educación en línea que ofrece cursos de tecnología y ciencia de datos. La empresa recopiló información de 500 estudiantes durante el último año académico y necesita desarrollar un sistema integral de análisis que permita:

🔮 Predecir la probabilidad de que un estudiante complete exitosamente un curso.

⭐ Estimar el puntaje de satisfacción final que otorgará cada estudiante.

📊 Identificar patrones de comportamiento que influyen en el éxito académico.

🎯 Generar recomendaciones basadas en datos para mejorar la retención estudiantil.

📂 Dataset
Nombre: estudiantes_edutech.csv

Formato: CSV

Columnas principales:

nombre, edad, genero, pais

horas_estudio_semanal, sesiones_totales, tareas_completadas, tareas_totales

participacion_foros, promedio_evaluaciones, horario_estudio

nivel_educacion, experiencia_previa, monto_inversion

curso_completado, puntaje_satisfaccion

⚙️ Metodología
1. Análisis Exploratorio y Visualización
   Limpieza de datos (valores nulos, duplicados).
   Estadística descriptiva (medias, medianas, distribuciones).
   Visualización (gráficos de barras, histogramas, correlaciones).
2. Preparación de Datos y Feature Engineering
   Normalización y creación de variables derivadas.
3. Modelado Predictivo con Machine Learning
   Modelos de clasificación (Logistic Regression, Random Forest).
   Modelos de regresión para satisfacción.
3. Procesamiento con Apache Spark MLlib
   Escalabilidad y paralelización de cálculos.
4. Inferencia Estadística
   Pruebas de hipótesis y validación de resultados.
5. Entrega Final y Reflexión
   Documentación y conclusiones.

📈 Resultados
La satisfacción promedio se situó entre 5.21 y 5.51 (IC 95%).

Se comprobó estadísticamente que los estudiantes que completan el curso tienen un nivel de satisfacción significativamente mayor (t = 11.49, p < 0.001).

Variables críticas:

⏱️ Horas de estudio semanal

💬 Participación en foros

📑 Promedio de evaluaciones

Estas variables influyen directamente en la probabilidad de completar el curso.

✅ Conclusiones
Este proyecto demuestra la aplicación de técnicas de ciencia de datos para:

Analizar y visualizar información educativa.

Construir modelos predictivos que apoyen la toma de decisiones.

Identificar factores clave de éxito académico y satisfacción estudiantil.

El análisis exploratorio es esencial antes de aplicar modelos predictivos, y el uso de Spark MLlib asegura escalabilidad para grandes volúmenes de datos.

🚀 Reproducibilidad
Para ejecutar este proyecto:

Abrir el archivo prueba_fundamentos_v1.ipynb en Google Colab.

Subir el archivo de entrada estudiantes_edutech.csv a la carpeta de Colab.

Instalar dependencias:

bash
pip install pandas seaborn matplotlib scikit-learn pyspark
Ejecutar las celdas en orden para reproducir el análisis completo.

🔗 Contacto
📧 Email: richardsepulvedam@gmail.com

🌐 LinkedIn: https://www.linkedin.com/in/richard-sep%C3%BAlveda-mart%C3%ADnez-341ba722/

🐙 GitHub: https://github.com/Rikibeto67
