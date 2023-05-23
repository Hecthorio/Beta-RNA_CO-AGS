# Beta-RNA_CO-AGS
Este repositorio contiene la versión beta de una propuesta de modelos de pronóstico de calidad del aire (CO)

El modelo que se encuentra en este repositorio (modelo_CO_Ags.h5) fue diseñado en Keras y se trata de un modelo de red neuronal (MLP).

Los parámetros de entrada al modelo son Día, Hora y Concentracion(t-1), y se describen a continuación

* El parámetro Día, está definido como una variable discreta {lunes = 0, martes = 1, ..., domingo = 6}
* El parámetro Hora, está definido como una variable discreta {0,1,2,3,...,23}
* El parámetro Concentracion(t-1), está definido como una variable continua para valores C(t-1)>= 0. Las unidades de este parámetro deben ser ppm.
