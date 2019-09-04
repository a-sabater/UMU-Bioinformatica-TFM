# UMU-Bioinformatica-TFM


Información referente al TFM realizado para el Máster de Bioinformática de la Universidad de Murcia. 


Título: Uso de organismos modelo en el descubrimiento de nuevos genes relacionados con el Parkinson Juvenil.  
Autor: Ana Sabater Aguado.  
Director: Juan Botía Blaya.  
Curso: 2018-2019.  


El primer paso del método se corresponde con el R Markdown TFM-Caracterización.Rmd. En él se utiliza una lista de genes conocidos como causantes de la Enfermedad de Parkinson (EP) para extraer los términos fenotípicos. La caracterización de los genes se realizó manualmente a partir de los términos extraídos en este script.


El segundo paso del método se corresponde con el R Markdown TFM-Evaluación.Rmd. En él se utilizan tres conjuntos de genes: una lista de genes conocidos como causantes de EP, una lista de genes predichos mediante machine learning como causantes de EP y 1000 conjuntos de genes tomados de forma aleatoria. Se busca calcular el número de asociaciones gen-fenotipo relevante para el EP y calcular un p-valor empírico que indique si los genes predichos presentan una mejor caracterización, tanto mediante términos HP como MP relevantes para Parkinson, de lo que se esperaría por azar.
