# Transcripción de Telediarios

Transcripción minutada de los telediarios de las principales cadenas de televisión. El minutado se ha realizado utilizando la herramienta de transcripción y minutado con Inteligencia Artificial: [El Minutador](https://elminutador.es/). Este dataset se puede adquirir en [Data Market](https://datamarket.es/#transcripcion-de-telediarios-dataset), plataforma de referencia de datos externos en España. Puede consultar nuestro catálogo de datos en la siguiente url: [datamarket.es](https://datamarket.es/)

A continuación se muestran las columnas de las que consta el dataset en el formato __nombre_columna__: __ejemplo_columna__, donde ejemplo_columna representa posibles valores que se pueden encontrar en dicha columna.

| nombre  | tipo     | descripción                                                     | ejemplo                                                                                                                          |
|---------|----------|-----------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------|
| date    | datetime | Fecha de emisión del informativo.                               | 2020-12-10                                                                                                                       |
| channel | str      | Cadena de TV donde se ha emitido el telediario correspondiente. | Telecinco                                                                                                                        |
| edition | str      | Edición del telediario: Matinal, Mediodía o Noche.              | Noche                                                                                                                            |
| text    | str      | Transcripción completa del informativo minutada.                | - 21:06 - Pedro Piqueras: Resulta sobrecogedor el incendio de esta nave en Badalona. Primero las víctimas, 3 muertos y más de 20 |
