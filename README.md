# Fires in the Paraná River Delta
Analysis of thermal hotspots during the fire events in the Paraná River Delta

## Author
Natalia Morandeira (nmorandeira@unsam.edu.ar, Assistant Researcher CONICET, 3iA-UNSAM)

## Collaborators
Patricia Kandus and Priscilla Minotti (*Instituto de Investigación e Ingeniería Ambiental, Universidad Nacional de San Martín*, Buenos Aires, Argentina) 
collaborated with the ecological analysis of the wildifire situation. Priscilla Minotti contributed with code.

## License
Please refer to: https://github.com/nmorandeira/Fires_ParanaRiverDelta/blob/master/LICENSE.md

## Abstract 

Wildfires can be monitored and analyzed using thermal hotspots records derived from satellite data. In 2020, the Paraná River floodplain (Argentina) is suffering from a severe drought, and thousands of hotspots —probably active fires— are daily reported by the Fire Information for Resource Management System (FIRMS-NASA). FIRMS-NASA products are provided in several spatial objects (shapefiles): recent and archive records from several sensors. I aimed to handle these data, analyze the number of hotspots during 2020, and compare the disaster with previous years' situation. I had to reproduce the analyses and plots several times, because I was asked by journalists and also because I share information on my social networks. The main used libraries are sf, tidyverse, spdplyr, ggplot2 and RMarkDown. This workflow can be used to analyze hotspot data in any other interest area.

## Links of published articles, interviews and talks during 2020

The data analysis and plots were included in several publications that aimed to spread what is happening in the Paraná River Delta, and also on periodistic interviews and talks. These articles and talks include information generated with this R script:

* June 25 - [El Delta en llamas](http://www.unsam.edu.ar/tss/el-delta-en-llamas/) (translated "Delta on flames"), published by *Agencia TSS* and authored by Patricia Kandus, Natalia Morandeira and Priscilla Minotti.
* June 25 - [El Delta en llamas. Incendios en las islas del Bajo Paraná](https://noticias.unsam.edu.ar/2020/06/25/el-delta-en-llamas-incendios-en-las-islas-del-bajo-parana/) (translated "Delta on flames. Fires at the islands of the Lower Paraná"), published by *Noticias UNSAM* and authored by Patricia Kandus, Natalia Morandeira and Priscilla Minotti.
* July 29 - [The Parched Paraná River](https://earthobservatory.nasa.gov/images/147031/the-parched-parana-river), published by *NASA Earth Observatory*, authored by Adam Voiland.
* July 30 - [Fires in the Paraná Islands](https://radiocut.fm/audiocut/incendios-en-islas-del-parana-natalia-morandeira-conicet-unsam/), radio interview to Natalia Morandeira in *AM RadioDos*, by Sergio Roulier.
* July 31 - [Talk on the Paraná River Delta fires](https://twitter.com/SumemosOK/status/1289228703243751424?s=20), at Plataforma Sumemos (Rosario, Argentina)
* July 31 - Fires & the Paraná River Delta; radio interview at *Radio Arroba* by RepasadosOK.
* August 4 - [Twitter thread of the Universidad Nacional de San Martín](https://twitter.com/unsamoficial/status/1290764808304852993?s=20)
* August 6 - [Incendios en los humedales del Delta: el riesgo que corren las familias isleñas y el daño que se genera en el ecosistema](https://www.bigbangnews.com/actualidad/incendios-en-los-humedales-del-delta-el-riesgo-que-corren-las-familias-islenas-y-el-dano-que-se-genera-en-el-ecosistema-202087165400) (translated "Fire in the Delta wetlands: island habitants in risk and damages to the ecosystem"), published by *BigBangNews*, authored by Agustina Acciardi. 
* August 10 - [Rodeados de fuego](http://www.hamartia.com.ar/2020/08/10/rodeados-fuego/) (translated "Surrounded by fire"), published by *Revista Hamartia*, authored by Natalia Morandeira.
* August 12 - [Up in smoke? Argentina's delta blaze sparks worry - and legal action](https://news.trust.org/item/20200811145310-yr272/), published by *Thomson Reuters Foundation*, authored by Marcela Valente.
* August 13 - [Incendios en el Delta: isleñxs y humedales en peligro](http://noticias.unsam.edu.ar/2020/8/13/incendios-en-el-delta-islenxs-y-humedales-en-peligro/) (translated "Fires in the Delta: island inhabitants and wetlands in danger"), published by *Noticias UNSAM*, authored by Solana Camaño.
* August 14 - [Ecología: la pandemia, el ambiente y un futuro incierto](https://chequeado.com/el-explicador/ecologia-la-pandemia-el-ambiente-y-un-futuro-incierto/) (translated: "Ecology: the pandemia, the environment and an uncertain future"), published by *Chequeado*, authored by Fabricio Ballarini, Juan Eduardo Bonnin, Florencia Curzel and Luciana Peirone Cappri.
* August 24 - [Que la ciencia te acompañe. En la penumbra de un suave interior](https://www.cenital.com/entre-la-penumbra-de-un-suave-interior/) (translated: "May science be with you. In the gloom of a soft interior"), newsletter published by *Cenital*, authored by Agostina Mileo.

# Última actualización / Last update 
## Fecha 23/08/2020 / Date: 08/23/2020
### En castellano (In Spanish, English below)
El número de focos VIIRS registrados durante este año en el Delta del Paraná es **24708**, hasta el **23/08/2020**

![Focos diarios](https://github.com/nmorandeira/Fires_ParanaRiverDelta/blob/master/output/Focos_diario_2020-08-23.png)

![Focos diarios y acumulados](https://github.com/nmorandeira/Fires_ParanaRiverDelta/blob/master/output/Focos_acumulados_2020-08-23.png)


### In English (en inglés, en castellano arriba)
The number of VIIRS hotspots recorded during this year in the Paraná River Delta is **24708**, up to **2020-08-23**.

![Daily hotspots](https://github.com/nmorandeira/Fires_ParanaRiverDelta/blob/master/output/Hotspot_daily_2020-08-23.png)

![Daily and cummulative hotspots](https://github.com/nmorandeira/Fires_ParanaRiverDelta/blob/master/output/Hotspot_cum_2020-08-23.png)

