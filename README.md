# Proyecto de Análisis de Text Mining

Este proyecto tiene como objetivo realizar un análisis de Text Mining aplicado a la transcripción de un discurso utilizando técnicas estadísticas. El código y el análisis se encuentran en el archivo [Milei_SpeechToText_Statics_Analysis.ipynb](https://colab.research.google.com/github/sebasruggero/TextAnalytics/blob/main/Milei_SpeechToText_Statics_Analysis.ipynb), que fue generado automáticamente por Colaboratory.

### Información General

- **Autor:** Lic. Sebastian Ruggero
- **Tema de Análisis:** Speech to Text and Text Analytics
- **Fuente de Análisis:** [Video - Entrevista realizada por Esteban Trebuc a Javier Milei - 8 ago 2023](https://www.youtube.com/watch?v=-FeSfqRIKxU&t=13s)

### Pasos del Algoritmo

1. **Preparación del Entorno y Configuración de Librerías:**
   - Instalación de librerías como OpenAI, ffmpeg, webvtt-py, pandas, numpy, matplotlib, nltk, y wordcloud.
   - Montaje del drive para acceder a los datos.

2. **Conversión de Audio a Texto:**
   - Utilización de la API Whisper para convertir el audio del discurso a texto.

3. **Carga de Datos:**
   - Extracción de datos a partir de archivos de subtítulos VTT.

4. **Análisis de Sentimientos y Visualización:**
   - Utilización de la librería NLTK para realizar análisis de sentimientos.
   - Visualización de los resultados a lo largo del tiempo.

5. **Limpieza de Texto:**
   - Conversión del texto a minúsculas.
   - Eliminación de palabras vacías y personalizadas.

6. **Nube de Palabras:**
   - Generación y visualización de una nube de palabras representativa del discurso.

7. **Análisis de Concordancia:**
   - Identificación y análisis de concordancias de una palabra específica ("Argentina").

8. **Análisis de Bigramas y Visualización:**
   - Identificación y conteo de bigramas (pares de palabras).
   - Visualización de los bigramas más frecuentes.

### Referencias y Fuentes Adicionales

1. [Text Mining Infrastructure in R](https://www.researchgate.net/publication/26539008_Text_Mining_Infrastructure_in_R)
2. [Using Text Mining Techniques for Extracting Information from Research Articles](https://www.researchgate.net/publication/321150349_Using_Text_Mining_Techniques_for_Extracting_Information_from_Research_Articles)
3. [Text Mining: Approaches and Applications](https://www.researchgate.net/publication/265568331_Text_Mining_Approaches_and_Applications)
4. [Text as Data](https://web.stanford.edu/~gentzkow/research/text-as-data.pdf)

### Instrucciones para Ejecutar el Código

- Abre el archivo [Milei_SpeechToText_Statics_Analysis.ipynb](https://colab.research.google.com/github/sebasruggero/TextAnalytics/blob/main/Milei_SpeechToText_Statics_Analysis.ipynb) en Colaboratory para reproducir el análisis.
- Asegúrate de tener las bibliotecas y dependencias instaladas según las instrucciones del código.

**Nota:** Algunas secciones del código pueden requerir configuraciones adicionales y acceso a recursos específicos. Asegúrate de seguir las instrucciones y tener los permisos necesarios.
