# Datasets de Transcripción de Telediarios

<a href="https://datamarket.es">
  <img src="https://datamarket.es/static/core/img/banners/transcripcion-de-telediarios-banner.png">
</a>

## Descripción

Transcripción minutada de los telediarios de las principales cadenas de televisión. El minutado se ha realizado utilizando la __herramienta de transcripción y minutado con Inteligencia Artificial: El Minutador__.

Las características de este dataset son las siguientes:

* __Frecuencia de actualización__: actualizado cada 6 h
* __Volumen estimado__: todos los telediarios cada día
* __Histórico__: desde febrero de 2021

El dataset completo se puede adquirir en [DataMarket](https://datamarket.es/#transcripcion-de-telediarios-dataset), plataforma de referencia de datos externos en España. 

Este repositorio contiene los siguientes recursos:

* La documentación completa del dataset.
* Una muestra representativa del mismo disponible para su evaluación y uso gratuito.

## Muestra

La muestra se encuentra disponible para descarga en el siguiente [link](https://github.com/Data-Market/transcripcion-de-telediarios/blob/main/transcripcion-de-telediarios-sample.csv).

## Documentación
A continuación se muestran las columnas de las que consta el dataset junto con su descripción.

| nombre  | tipo     | descripción                                                     | ejemplo                                                                                                                          |
|---------|----------|-----------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------|
| date    | datetime | Fecha de emisión del informativo.                               | 2020-12-10                                                                                                                       |
| channel | str      | Cadena de TV donde se ha emitido el telediario correspondiente. | Telecinco                                                                                                                        |
| edition | str      | Edición del telediario: Matinal, Mediodía o Noche.              | Noche                                                                                                                            |
| text    | str      | Transcripción completa del informativo minutada.                | - 21:06 - Pedro Piqueras: Resulta sobrecogedor el incendio de esta nave en Badalona. Primero las víctimas, 3 muertos y más de 20 |
