# LDA TopicModeling & pyspark

El presente repositorio se refiere a un curso sobre **Latent Dirichlet Allocation(LDA)**, impartido en colaboración con el [Colegio de Matemáticas Bourbaki](https://www.colegio-bourbaki.com/) 

En este repositorio se hace uso de *aprendizaje no supervizado* utilizando LDA para obtener los temas de una base de datos de más de un millón de encabezados de noticias.
La base de datos utilizada esta disponibles en [Kaggle](https://www.kaggle.com/therohk/million-headlines)

La implementación está hecha en Python, en un notebook de Jupyter en Google Colaboratory, utilizando pySpark.

**PySpark** es la biblioteca de Python para usar *Apache Spark*, una importante solución de código abierto para computo distribuído que permite el procesamiento de grandes volúmenes de información. Spark, desarrollado originalemnete en los laboratorioa AMPLab de Berkeley California y donado más tarde a la Apache Software Foundation, mejora el paradigma de computación en clúster MapReduce al realizar el procesamiento de información en memoria, ganando velocidad y facilitando la implementación de algoritmos de aprendizaje de máquinas, la transformación y consulta de grandes volúmenes de información, así como el procesamiento de datos en tiempo real de forma escalable.

Apache Spark requiere un gestor de clúster (manager) y un sistema de almacenamiento distribuido, pero igualmente se puede utilizar en una única máquina distribuyendo la ejecución en cada nucleo del CPU.
