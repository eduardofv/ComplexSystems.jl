# Una implementación del modelo epidemiológico COVID-19 publicado por CDMX

Este es un fork del modelo implementado por [@ollin18](https://github.com/ollin18/ComplexSystems.jl/blob/master/examples/CDMX_model.ipynb) en Julia. Yo lo he reimplementado en Python para entender cómo funciona el modelo y cómo se desarrolla el código de un modelo de este tipo. También para aprender un poco de Julia.

Implementa el [modelo publicado por el gobierno de la Ciudad de México](https://modelo.covid19.cdmx.gob.mx/modelo-epidemico) con los parámetros que han publicado hasta hoy.

### Archivos

- Mi [modelo Python](CDMX_py.ipynb) con explicación tal como lo he entendido.
- [Modelo Julia original](examples/CDMX_model.ipynb) con mis cambios para comprender su funcionamiento
- [Archivo de los documentos publicados por CDMX](cdmx_archive/) con la definición del modelo y parámetros a la fecha en que se implentó este modelo. Guardo esta copia en PDF por si cambia la publicación.

### Muestra de las gráficas generadas:

!(modelo)[img/modelo-1.png]

!(modelo2)[img/modelo-2.png]

### Modelo

!(modelo)[img/variables.png]

!(modelo)[img/ecuaciones.png]
