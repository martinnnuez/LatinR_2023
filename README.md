<p align="center">
    <img width="500" src="https://latin-r.com/img/logo.png" alt="Latin R">
</p>

# **Análisis de contaminantes atmosféricos con R**

## [LatinR 2023](https://latin-r.com/)

* Conferencia Latinoamericana sobre Uso de R en Investigación + Desarrollo

***Edición 2023*** 

Comparto mi trabajo títulado: **"Análisis de contaminantes atmosféricos con R"**, presentado durante los [LatinR](https://latin-r.com/) desarrollados desde el 18 al 20 de octubre de 2023 en la Facultad de Ciencias Económicas y de Administración de la Universidad de la República Oriental del Uruguay en Montevideo, Uruguay.

### Resumen

La Organización Mundial de la Salud (OMS) estima que nueve de cada diez personas respiran aire con altos niveles de contaminante y como resultado siete millones mueren cada año en el mundo por causas relacionadas. El material particulado fino, partículas con un diámetro menor o igual a 2.5 micrómetros (PM2.5), es considerado uno de los contaminantes atmosféricos de mayor nocividad dada su capacidad de penetrar la barrera pulmonar y pasar al torrente sanguíneo, causando enfermedades cardiovasculares, respiratorias y cáncer. La presencia de estas partículas en la atmósfera tiene un impacto significativo en diversos aspectos que influyen en la vida humana, abarcando desde la salud hasta los ecosistemas y el clima. El propósito de este trabajo es demostrar la aplicabilidad de R en el análisis de datos de contaminantes atmosféricos. Específicamente, se centra en la concentración de PM2.5, basándome en mi experiencia personal durante el desarrollo de mi tesis de doctorado. Mi investigación se centró en el estudio de series temporales de concentración de PM2.5, explorando su correlación con variables meteorológicas y satelitales, además de crear modelos predictivos para su concentración.  A lo largo de todo el proceso de investigación, R desempeñó un papel transversal y fundamental, abarcando desde la obtención de datos satelitales hasta la redacción final de la tesis. La fortaleza de R en este contexto se sustenta no solo en ser una plataforma de código abierto, sino también en contar con una comunidad activa que desarrolla soluciones para desafíos comunes. En primera instancia la librería KrigR me permitió descargar y preprocesar variables satelitales almacenadas en el Servicio de Cambio Climático de Copernicus (C3S), específicamente obtenidas a partir del procedimiento de reanálisis (ERA5) del Centro Europeo de Pronósticos Meteorológicos a Plazo Medio (ECMWF). Una vez obtenidos los datos, aproveche las funcionalidades de los paquetes tidyverse y lubridate para importar, limpiar, manipular y visualizar la información (ggplot2). Asimismo, exploré visualizaciones más avanzadas mediante el uso del paquete openair, diseñado especialmente para analizar datos de calidad del aire. s relevante señalar que gran parte del análisis de series temporales se llevó a cabo gracias a una variedad de paquetes, entre los que se destacan TSstudio, tseries, uroot, forecast y xts. Finalmente, el modelado predictivo fue llevado a cabo por medio de la implementación de los frameworks de tidymodels, caret y tensorflow, permitiéndome crear y comparar diferentes modelos predictivos. Cabe destacar que también aproveche las funcionalidades provistas por la librería thesisdown para redactar el documento final de la tesis. En resumen, mi objetivo es destacar y comunicar la versatilidad de R para abordar una amplia gama de desafíos presentes transversales en mi investigación doctoral, con la esperanza de inspirar a otros investigadores a abordar sus propios problemas utilizando esta poderosa herramienta.

Palabras clave:  contaminación atmosférica, análisis de datos, series temporales, material particulado fino, variables meteorológicas, modelo predictivo

[Tesis doctorado](https://github.com/martinnnuez/Tesis-Doctorado)