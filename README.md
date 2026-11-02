# Análisis estadístico de series temporales ambientales para la conservación preventiva

## Descripción del proyecto

Este proyecto se desarrolla en el marco de la Licenciatura en Ciencia de Datos de la Universidad Nacional de San Martín (UNSAM), en colaboración con el Centro de Estudios sobre Patrimonios y Ambiente (CEPyA), de la Escuela de Arte y Patrimonio.

El trabajo da continuidad al Trabajo Final Integrador de Scoccimarro (2024), desarrollado a partir del monitoreo ambiental de la Reserva Infanta Isabel del Museo de Artes Plásticas Eduardo Sívori entre el 29 de diciembre de 2022 y el 4 de enero de 2024. A partir de las mediciones de temperatura (T) y humedad relativa (HR) registradas por sensores interiores, junto con los datos meteorológicos exteriores provistos por el Servicio Meteorológico Nacional (SMN), se realizó una primera caracterización del comportamiento ambiental de la reserva mediante estadísticas descriptivas, medias móviles, análisis de fluctuaciones y comparaciones entre las condiciones interiores y exteriores.

Sobre esta base, el presente proyecto propone profundizar el análisis estadístico de las series temporales, incorporando herramientas que permitan estudiar su estructura temporal, identificar anomalías y caracterizar la persistencia y duración de las fluctuaciones. Además, se busca analizar la dinámica entre las condiciones ambientales interiores y exteriores.

## Objetivos

### Objetivo general

Caracterizar la dinámica temporal de las condiciones ambientales de la Reserva Infanta Isabel del Museo de Artes Plásticas Eduardo Sívori y estudiar su relación con las condiciones meteorológicas exteriores, con especial interés en la identificación de anomalías y en la respuesta temporal del ambiente interior frente a variaciones externas.

### Objetivos específicos

1. Caracterizar las series temporales ambientales de los distintos puntos de medición de la reserva, identificando patrones temporales, fluctuaciones, anomalías y eventos relevantes.

2. Analizar la dinámica entre las condiciones ambientales interiores y exteriores, con especial atención a la inercia térmica, al comportamiento de la humedad relativa y a la relación con variables meteorológicas externas.

## Organización del repositorio

El repositorio contiene los notebooks de procesamiento, análisis y documentación metodológica, organizados según las etapas del proyecto.

| Archivo | Contenido |
|---|---|
| `notebooks/01_preprocesamiento_y_auditoria.ipynb` | Preprocesamiento, auditoría y preparación de las series temporales. |
| `notebooks/02_objetivo1_caracterizacion_temporal.ipynb` | Caracterización temporal de las series (objetivo 1). |
| `notebooks/02b_objetivo1_metodologia_anomalias.ipynb` | Desarrollo y documentación metodológica complementaria del objetivo 1. |
| `notebooks/03_objetivo2.ipynb` | Análisis de la dinámica interior-exterior (objetivo 2). |

## Entorno de trabajo

El análisis se desarrolla en **Python**, utilizando **Jupyter Notebook** y librerías de análisis estadístico y series temporales.

Para instalar las dependencias desde la raíz del repositorio:

```bash
pip install -r requirements.txt
```

Una vez configurado el entorno Jupyter, los notebooks pueden abrirse desde el directorio `notebooks/`.

## Datos y reproducibilidad

El proyecto utiliza mediciones de temperatura y humedad relativa obtenidas mediante sensores interiores HOBO, junto con registros meteorológicos exteriores del Servicio Meteorológico Nacional (SMN).

Por el momento, el repositorio contiene únicamente el código y la documentación metodológica. La publicación de los datos originales, las series procesadas y los resultados queda sujeta a la autorización de los responsables del proyecto. Los procedimientos de preparación y análisis se encuentran documentados en los notebooks, con el propósito de mantener la trazabilidad de las transformaciones realizadas y facilitar la reproducción del trabajo una vez disponibles los datos.

## Antecedente principal

Scoccimarro, M. (2024). *Implementación de un sistema de monitoreo ambiental orientado al diseño de estrategias sostenibles para la conservación preventiva de colecciones patrimoniales: Caso de estudio: Reserva Infanta Isabel del Museo de Artes Plásticas Eduardo Sívori* [Trabajo Final Integrador, Universidad Nacional de San Martín]. [Repositorio Institucional UNSAM](https://ri.unsam.edu.ar/handle/123456789/3274)
