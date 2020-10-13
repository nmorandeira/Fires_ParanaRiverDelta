# Incendios en el Delta del Paraná / Fires in the Paraná River Delta
ES: Análisis de focos de calor durante los incendios del Delta del Paraná en 2020

EN: Analysis of thermal hotspots during the fire events in the Paraná River Delta en 2020

## Autora / Author
Natalia Morandeira (nmorandeira@unsam.edu.ar, Investigadora/Researcher CONICET, 3iA-UNSAM)

## Colaboradoras / Collaborators
Patricia Kandus & Priscilla Minotti (*Instituto de Investigación e Ingeniería Ambiental, Universidad Nacional de San Martín*, Buenos Aires, Argentina)

ES: PK y PM colaboraron con el análisis ecológicos de los incendios. PM contribuyó con código de R. 

EN: PK and PM collaborated with the ecological analysis of the wildifire situation. PM contributed with R code.

## Licencia / License
Por favor referirse a / Please refer to: https://github.com/nmorandeira/Fires_ParanaRiverDelta/blob/master/LICENSE.md

## Resumen / Abstract 
### Versión en castellano:
Los incendios de áreas naturales pueden ser monitoreados y analizados utilizando registros de focos de calor térmico derivados de datos satelitales. En 2020, una sequía severa afecta a la planicie de inundación de Argentina y cientos de focos de calor —probablemente incendios activos— son informados a diario por el servicio Fire Information for Resource Management System (FIRMS-NASA). Los productos FIRMS-NASA son provistos en múltiples objetos espaciales (_shapefiles_): registros actuales y de archivo de varios sensores remotos. El objetivo es procesar estos datos, analizar la cantidad de focos de calor durante 2020 y compararlos con los incendios de años anteriores. Con R, realicé códigos e informes reproducibles, lo que me facilita repetir los análisis y gráficos muchas veces, para mi propio conocimiento y también para difundir en redes sociales y ante la consultaq de periodistas. Las principales librerías de R utilizadas son sf, tidyverse, spdplyr, ggplot2 y RMarkDown. Este flujo de trabajo puede ser utilizado para analizar focos de calor en cualquier otro área de interés.

### English version:
Wildfires can be monitored and analyzed using thermal hotspots records derived from satellite data. In 2020, the Paraná River floodplain (Argentina) is suffering from a severe drought, and thousands of hotspots —probably active fires— are daily reported by the Fire Information for Resource Management System (FIRMS-NASA). FIRMS-NASA products are provided in several spatial objects (shapefiles): recent and archive records from several sensors. I aimed to handle these data, analyze the number of hotspots during 2020, and compare the disaster with previous years' situation. I had to reproduce the analyses and plots several times, because I was asked by journalists and also because I share information on my social networks. The main used libraries are sf, tidyverse, spdplyr, ggplot2 and RMarkDown. This workflow can be used to analyze hotspot data in any other interest area.

# Última actualización / Last update 
## Fecha 04/10/2020 / Date: 10/04/2020
### En castellano (In Spanish, English below)
El número de focos VIIRS registrados durante este año en el Delta del Paraná es **33.956**, hasta el **04/10/2020**

![Focos diarios](https://github.com/nmorandeira/Fires_ParanaRiverDelta/blob/master/output/Focos_diario_2020-10-04.png)

![Focos diarios y acumulados](https://github.com/nmorandeira/Fires_ParanaRiverDelta/blob/master/output/Focos_acumulados_2020-10-04.png)


### In English (en inglés, en castellano arriba)
The number of VIIRS hotspots recorded during this year in the Paraná River Delta is 
**33,956**, up to **2020/10/04**.

![Daily hotspots](https://github.com/nmorandeira/Fires_ParanaRiverDelta/blob/master/output/Hotspot_daily_2020-10-04.png)

![Daily and cummulative hotspots](https://github.com/nmorandeira/Fires_ParanaRiverDelta/blob/master/output/Hotspot_cum_2020-10-04.png)


## Links a artículos publicados, entrevistas y charlas durante 2020
## Links of published articles, interviews and talks during 2020

ES: Los análisis de datos y gráficos fueron incluidos en varias publicaciones que tuvieron por objetivo difundir la situación del Delta del Paraná. También, esta información fue mencionada en entrevistas periodísticas y charlas. Los siguientes artículos y charlas incluyen información derivada del código de R incluido en este repositorio.

EN: The data analysis and plots were included in several publications that aimed to spread what is happening in the Paraná River Delta, and also on periodistic interviews and talks. These articles and talks include information generated with the R script included in this repository.

* June 25 - [El Delta en llamas](http://www.unsam.edu.ar/tss/el-delta-en-llamas/) (translated "Delta on flames"), published by *Agencia TSS* and authored by **Patricia Kandus, Natalia Morandeira** and **Priscilla Minotti**.
* June 25 - [El Delta en llamas. Incendios en las islas del Bajo Paraná](https://noticias.unsam.edu.ar/2020/06/25/el-delta-en-llamas-incendios-en-las-islas-del-bajo-parana/) (translated "Delta on flames. Fires at the islands of the Lower Paraná"), published by *Noticias UNSAM* and authored by **Patricia Kandus, Natalia Morandeira** and **Priscilla Minotti**.
* July 29 - [The Parched Paraná River](https://earthobservatory.nasa.gov/images/147031/the-parched-parana-river), published by *NASA Earth Observatory*, authored by Adam Voiland.
* July 30 - [Fires in the Paraná Islands](https://radiocut.fm/audiocut/incendios-en-islas-del-parana-natalia-morandeira-conicet-unsam/), radio interview to Natalia Morandeira in *AM RadioDos*, by Sergio Roulier.
* July 31 - [Talk on the Paraná River Delta fires](https://twitter.com/SumemosOK/status/1289228703243751424?s=20), at Plataforma Sumemos (Rosario, Argentina)
* July 31 - Fires & the Paraná River Delta; radio interview at *Radio Arroba* by RepasadosOK.
* August 4 - [Twitter thread of the Universidad Nacional de San Martín](https://twitter.com/unsamoficial/status/1290764808304852993?s=20)
* August 6 - [Incendios en los humedales del Delta: el riesgo que corren las familias isleñas y el daño que se genera en el ecosistema](https://www.bigbangnews.com/actualidad/incendios-en-los-humedales-del-delta-el-riesgo-que-corren-las-familias-islenas-y-el-dano-que-se-genera-en-el-ecosistema-202087165400) (translated "Fire in the Delta wetlands: island habitants in risk and damages to the ecosystem"), published by *BigBangNews*, authored by Agustina Acciardi. 
* August 10 - [Rodeados de fuego](http://www.hamartia.com.ar/2020/08/10/rodeados-fuego/) (translated "Surrounded by fire"), published by *Revista Hamartia*, authored by **Natalia Morandeira**.
* August 11 - [Up in smoke? Argentina's delta blaze sparks worry - and legal action](https://news.trust.org/item/20200811145310-yr272/), published by *Thomson Reuters Foundation*, authored by Marcela Valente.
* August 13 - [Incendios en el Delta: isleñxs y humedales en peligro](http://noticias.unsam.edu.ar/2020/8/13/incendios-en-el-delta-islenxs-y-humedales-en-peligro/) (translated "Fires in the Delta: island inhabitants and wetlands in danger"), published by *Noticias UNSAM*, authored by Solana Camaño.
* August 14 - [Ecología: la pandemia, el ambiente y un futuro incierto](https://chequeado.com/el-explicador/ecologia-la-pandemia-el-ambiente-y-un-futuro-incierto/) (translated: "Ecology: the pandemia, the environment and an uncertain future"), published by *Chequeado*, authored by Fabricio Ballarini, Juan Eduardo Bonnin, Florencia Curzel and Luciana Peirone Cappri.
* August 24 - [Que la ciencia te acompañe. En la penumbra de un suave interior](https://www.cenital.com/entre-la-penumbra-de-un-suave-interior/) (translated: "May science be with you. In the gloom of a soft interior"), newsletter published by *Cenital*, authored by Agostina Mileo.
* August 24 [Incendios en bosques y humedales: un ecocidio fuera de control](http://cosecharoja.org/incendios-en-bosques-y-humedales-un-ecocidio-fuera-de-control/) (translated: "Fires in forests and wetlands: an out of control ecocide"), published by *Cosecha Roja*, authored by Matías Máximo.
* August 27 - [Los incendios asfixian el centro y norte de Argentina](https://elpais.com/internacional/2020-08-27/los-incendios-asfixian-el-centro-y-norte-de-argentina.html) (translated: "Fires suffocate central and northern Argentina"), published by *El País*, authored by Georgina Zerega.
* August 28 - [Ecocidio en el Delta: un cementerio de animales carbonizados](http://cosecharoja.org/ecocidio-en-el-delta-un-cementerio-de-animales-carbonizados/) (translated: "Ecocide in the Delta: a charred animal graveyard"), published by *Cosecha Roja*, authored by Matías Máximo.
* September 02 - [Argentina's wetlands under assault by worst fires in more than a decade](https://www.reuters.com/article/us-argentina-environment/argentinas-wetlands-under-assault-by-worst-fires-in-more-than-a-decade-idUSKBN25T35V), published by *Thomson Reuters*, authored by Cassandra Garrison and Maximilian Heath.
* September 04 - [Natalia Morandeira: “En lo que va del año se registraron 25 mil focos de incendios”](https://defonline.com.ar/natalia-morandeira-en-lo-que-va-del-ano-se-registraron-25-mil-focos-de-incendios/) (translated: "Natalia Morandeira: 'So far this year, 25 thousand fire hotspots were recorded'"), published by *DEF*, authored by Patricia Fernández Mainardi.
* September 15 - [Bajo Paraná: un territorio amenazado por el fuego](https://youtu.be/I_XH_7TfQuM?t=2778) (translated: "Lower Paraná River: a fire-threatened territory"), lecture by Patricia Kandus in *Instituto de Investigación e Ingeniería Ambiental, UNSAM".
* October 6 - [Entre Ríos es la provincia con más focos de incendios](https://www.perfil.com/noticias/ecologia/entre-rios-es-la-provincia-con-mas-foco-de-incendios.phtml) (translated: "Entre Ríos is the province with the highest number of fire hotspots"), published by *Perfil*, authored by **Natalia Morandeira**.
* October 9 - [Al rojo vivo: mapa argentino de los incendios](https://www.clarin.com/revista-enie/ideas/rojo-vivo-mapa-argentino-incendios_0_YhGanTZLF.html)(translated: "Red hot: Argentine map of fires"), published by *Revista Ñ*, authored by Lucía Dozo.
