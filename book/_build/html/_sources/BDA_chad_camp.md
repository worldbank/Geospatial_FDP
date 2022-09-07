# Baseline data assessment and report for Chad camps

## Quantitative assessment of OpenStreetMap (OSM) completeness

The OSM completeness of buildings and highways data is different in each of the refugee camps: 
- 3 camps had high coverage of buildings and highways
- 15 camps have partial or low coverage of buildings and highways
- 4 camps did not have data of buildings and highways.

Although 3 camps had high data coverage, the baseline data assessment showed us that approximately 70% of the data has low quality, due to a) mismatch between the data and the baseline satellite imagery or b) the buildings were mapped with old imagery and need to be re-aligned.

```{figure} docs/images/BDA_chad_camp/chad_camp_img1.png
Buildings and highways that need to be aligned to the Maxar Premiun imagery (most current imagery in this location)
```

Some other issues that need to be fixed are; misaligned highways, inaccurate buildings and highways, etc.

```` {tabbed} Misaligned highways
```{figure} docs/images/BDA_chad_camp/chad_camp_img2.png
Misaligned highways
```
````
```` {tabbed} Misaligned and inaccurate buildings
```{figure} docs/images/BDA_chad_camp/chad_camp_img3.png
Misaligned and inaccurate buildings
```
````

The tables below (table 1 and table 2) summarize the method for our assessment of data quality and coverage
| **Levels**  | **Description**                                                   |
| ----------- | ----------------------------------------------------------------- |
| **High**    | Approximately more than 70% of buildings/highways were mapped     |
| **Partial** | Approximately between 30% - 70% of buildings/highways were mapped |
| **Low**     | Approximately less that 30% of buildings/highways were mapped     |
| **Nothing** | None building/highway mapped                                      |

**Table 1: OSM data coverage levels**

| **Levels** | **Description**                                                                                                                                                                                 |
| ---------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Good**   | Buildings/highways mapped match with the current imagery and have the correct shape.                                                                                                            |
| **Medium** | Some areas of the refuge have buildings/highways with good quality and other areas have buildings/highways with low quality.                                                                    |
| **Low**    | Buildings/highways mapped do not match with the current imagery, have wrong shape, several buildings were mapped as only one building, and the data has different issues that need to be fixed. |

**Table 2: OSM data quality levels**

According to the summary table of data quality (table 3), there are 3 camps without buildings, 8 camps with less than 500 buildings and 11 camps with more than a thousand buildings. Concerning highways, there is 1 refuge without highways mapped, 14 camps with less than 30 km of highways, and 7 camps with more than 36 km of highways.

| **N°** | **Camps**         | **OSM data coverage**                   | **OSM data quality**                  | **Total buildings** | **Total highway Length** |
| ------ | ----------------- | --------------------------------------- | ------------------------------------- | ------------------- | ------------------------ |
| 1      | Amboko Camp       | Buildings: Partial<br>Highways: High    | Buildings: Low<br>Highways: Low       | 1,813               | 8.051 km                 |
| 2      | Amnabak           | Buildings: Low<br>Highways: Low         | Buildings: Medium<br>Highways: -      | 398                 | 1.472 km                 |
| 3      | Belom             | Buildings: Partial<br>Highways: High    | Buildings: Medium<br>Highways: Medium | 4,450               | 27.338 km                |
| 4      | Bredjing Camp     | Buildings: Low<br>Highways: Low         | Buildings: Low<br>Highways: Low       | 34                  | 14.743 km                |
| 5      | Daha 1 Village    | Buildings: Low<br>Highways: Low         | Buildings: Low<br>Highways: Medium    | 222                 | 6.035 km                 |
| 6      | Dembo             | Buildings: Partial<br>Highways: High    | Buildings: Low<br>Highways: Low       | 2,324               | 41.02 km                 |
| 7      | Diba Village      | Buildings: Nothing<br>Highways: Low     | Buildings: -<br>Highways: Medium      | 0                   | 0.455 km                 |
| 8      | Djabal Camp       | Buildings: Partial<br>Highways: High    | Buildings: Medium<br>Highways: Medium | 4,884               | 49.163 km                |
| 9      | Doholo Camp       | Buildings: High<br>Highways: Low        | Buildings: Good<br>Highways: Medium   | 2,037               | 3.314 km                 |
| 10     | Dosseye Camp      | Buildings: Partial<br>Highways: Partial | Buildings: Low<br>Highways: Low       | 1,503               | 36.14 km                 |
| 11     | Farchana          | Buildings: Low<br>Highways: Partial     | Buildings: Low<br>Highways: Low       | 7                   | 37.94 km                 |
| 12     | Gaga Camp         | Buildings: Low<br>Highways: Low         | Buildings: Low<br>Highways: Low       | 18                  | 13.735 km                |
| 13     | Gondje Camp       | Buildings: Partial<br>Highways: High    | Buildings: Low<br>Highways: Low       | 1,168               | 38.339 km                |
| 14     | Goz Amir Camp     | Buildings: Low<br>Highways: Low         | Buildings: Low<br>Highways: Low       | 133                 | 25.83 km                 |
| 15     | Iridimi           | Buildings: High<br>Highways: High       | Buildings: Good<br>Highways: Medium   | 8,213               | 20.555 km                |
| 16     | Kounoungou Camp   | Buildings: Low<br>Highways: Low         | Buildings: Low<br>Highways: Low       | 34                  | 7.95 km                  |
| 17     | Mile Camp         | Buildings: High<br>Highways: Partial    | Buildings: Medium<br>Highways: Low    | 5,343               | 21.314 km                |
| 18     | Moyo              | Buildings: Low<br>Highways: Nothing     | Buildings: Low<br>Highways: -         | 7                   | 0.0 km                   |
| 19     | Oure Cassoni Camp | Buildings: High<br>Highways: High       | Buildings: Low<br>Highways: Low       | 8,623               | 37.673 km                |
| 20     | Touloum           | Buildings: High<br>Highways: High       | Buildings: Medium<br>Highways: Medium | 7,832               | 53.97 km                 |
| 21     | Treguine Camp     | Buildings: Nothing<br>Highways: Partial | Buildings: -<br>Highways: Medium      | 0                   | 19.522 km                |
| 22     | Vom village       | Buildings: Nothing<br>Highways: Low     | Buildings: -<br>Highways: Low         | 0                   | 1.909 km                 |

**Table 3: Summary per refuge of the OSM data completeness**



## Quality and currency of available imagery in base maps

There are different satellite imagery basemaps available in the JOSM editor for the mapping process; Bing aerial imagery, Esri World Imagery, ESRI Clarity, Maxar Premium, Mapbox Satellite. From the baseline data assessment, we found that the imageries most used in the previous mappings were Maxar Premium and Bing aerial imagery.

The dates of the images are unknown, so to know which of them is the most current, we did a comparison between them and one of the signs that one imagery is the most recent is that it shows buildings and/or highways in areas where the other imagery only shows an empty field.

````{tabbed} Old imagery
```{figure} docs/images/BDA_chad_camp/chad_camp_img4.png
Bing aerial imagery (old imagery)
```
````
````{tabbed} New imagery
```{figure} docs/images/BDA_chad_camp/chad_camp_img5.png

Maxar premium (current imagery)
```
````

In most cases the baseline OSM data aligned with Bing imagery, but since the most current imagery in almost all camps is Maxar, we are going to align the existing data to Maxar.

| **Levels** | **Description**                                                                                                        |
| ---------- | ---------------------------------------------------------------------------------------------------------------------- |
| **High**   | Imagery does not loses its resolution                                                                 |
| **Medium** | Imagery loses its resolution but we can differentiate the buildings and highways for mapping |
| **Low**    | Imagery loses its resolution but is difficult to differentiate the buildings for mapping              |

**Table 4: Imagery quality levels were classified according to their resolution**

| **N°** | **Camps**         | **Most current imagery** | **Imagery quality** | **Imagery screenshot**                             |
| ------ | ----------------- | ------------------------ | ------------------- | -------------------------------------------------- |
| 1      | Amboko Camp       | Maxar Premium            | Medium              | <div style="width: 80%;">  ![](docs/images/BDA_chad_camp/chad_camp_img8.png) </div>  |
| 2      | Amnabak           | Maxar Premium            | Low                 | <div style="width: 80%;">  ![](docs/images/BDA_chad_camp/chad_camp_img9.png)  </div> |
| 3      | Belom             | Maxar Premium            | Low                 | <div style="width: 80%;">  ![](docs/images/BDA_chad_camp/chad_camp_img10.png)  </div>|
| 4      | Bredjing Camp     | Maxar Premium            | Low                 | <div style="width: 80%;">  ![](docs/images/BDA_chad_camp/chad_camp_img11.png)  </div>|
| 5      | Daha 1 Village    | Bing Aerial              | Medium              | <div style="width: 80%;">  ![](docs/images/BDA_chad_camp/chad_camp_img12.png)  </div>|
| 6      | Dembo             | Maxar Premium            | Low                 | <div style="width: 80%;">  ![](docs/images/BDA_chad_camp/chad_camp_img13.png)  </div>|
| 7      | Diba Village      | Maxar Premium            | Low                 | <div style="width: 80%;">  ![](docs/images/BDA_chad_camp/chad_camp_img14.png)  </div>|
| 8      | Djabal Camp       | Maxar Premium            | Low                 | <div style="width: 80%;">  ![](docs/images/BDA_chad_camp/chad_camp_img15.png)  </div>|
| 9      | Doholo Camp       | Maxar Premium            | Medium              | <div style="width: 80%;">  ![](docs/images/BDA_chad_camp/chad_camp_img16.png)  </div>|
| 10     | Dosseye Camp      | Maxar Premium            | Medium              | <div style="width: 80%;">  ![](docs/images/BDA_chad_camp/chad_camp_img17.png)  </div>|
| 11     | Farchana          | Maxar Premium            | Low                 | <div style="width: 80%;">  ![](docs/images/BDA_chad_camp/chad_camp_img18.png)  </div>|
| 12     | Gaga Camp         | Maxar Premium            | Low                 | <div style="width: 80%;">  ![](docs/images/BDA_chad_camp/chad_camp_img19.png)  </div>|
| 13     | Gondje Camp       | Maxar Premium            | Medium              | <div style="width: 80%;">  ![](docs/images/BDA_chad_camp/chad_camp_img20.png)  </div>|
| 14     | Goz Amir Camp     | Maxar Premium            | Low                 | <div style="width: 80%;">  ![](docs/images/BDA_chad_camp/chad_camp_img21.png)  </div>|
| 15     | Iridimi           | Maxar Premium            | Low                 | <div style="width: 80%;">  ![](docs/images/BDA_chad_camp/chad_camp_img22.png)  </div>|
| 16     | Kounoungou Camp   | Maxar Premium            | Low                 | <div style="width: 80%;">  ![](docs/images/BDA_chad_camp/chad_camp_img23.png)  </div>|
| 17     | Mile Camp         | Maxar Premium            | Low                 | <div style="width: 80%;">  ![](docs/images/BDA_chad_camp/chad_camp_img24.png)  </div>|
| 18     | Moyo              | Maxar Premium            | Low                 | <div style="width: 80%;">  ![](docs/images/BDA_chad_camp/chad_camp_img25.png)  </div>|
| 19     | Oure Cassoni Camp | Maxar Premium            | Low                 | <div style="width: 80%;">  ![](docs/images/BDA_chad_camp/chad_camp_img26.png)  </div>|
| 20     | Touloum           | Maxar Premium            | Low                 | <div style="width: 80%;">  ![](docs/images/BDA_chad_camp/chad_camp_img27.png)  </div>|
| 21     | Treguine Camp     | Maxar Premium            | Low                 | <div style="width: 80%;">  ![](docs/images/BDA_chad_camp/chad_camp_img28.png)  </div>|
| 22     | Vom village       | Maxar Premium            | Low                 | <div style="width: 80%;">  ![](docs/images/BDA_chad_camp/chad_camp_img29.png)  </div>|

**Table 5: Summary per refuge of the most current imagery and its quality**

According to table 5, most camps have poor quality imagery, so in total there are 17 camps with poor quality imagery and 5 camps with medium quality imagery. And the most current imagery is Maxar Premium.

## Pre-improvement Maps
``` {tabbed} Selected AOIs
![Overview](docs/images/TCD_Camps_Overview.png)
```
``` {tabbed} Amboko
![Overview](docs/images/TCD_Camps/output_13.png)
```
``` {tabbed} Amnabak
![Overview](docs/images/TCD_Camps/output_1.png)
```
``` {tabbed} Bekourou
![Overview](docs/images/TCD_Camps/output_14.png)
```
``` {tabbed} Belom
![Overview](docs/images/TCD_Camps/output_15.png)
```
``` {tabbed} Bredjing
![Overview](docs/images/TCD_Camps/output_7.png)
```
``` {tabbed} Daha 1
![Overview](docs/images/TCD_Camps/output_16.png)
```
``` {tabbed} Dembo
![Overview](docs/images/TCD_Camps/output_17.png)
```
``` {tabbed} Diba (Vom)
![Overview](docs/images/TCD_Camps/output_18.png)
```
``` {tabbed} Djabal
![Overview](docs/images/TCD_Camps/output_8.png)
```
``` {tabbed} Doholo
![Overview](docs/images/TCD_Camps/output_19.png)
```
``` {tabbed} Dosseye
![Overview](docs/images/TCD_Camps/output_20.png)
```
``` {tabbed} Farchana
![Overview](docs/images/TCD_Camps/output_2.png)
```
``` {tabbed} Gaga
![Overview](docs/images/TCD_Camps/output_9.png)
```
``` {tabbed} Gondje
![Overview](docs/images/TCD_Camps/output_21.png)
```
``` {tabbed} Goz Amir
![Overview](docs/images/TCD_Camps/output_3.png)
```
``` {tabbed} Iridimi
![Overview](docs/images/TCD_Camps/output_10.png)
```
``` {tabbed} Kounoungou
![Overview](docs/images/TCD_Camps/output_4.png)
```
``` {tabbed} Mile
![Overview](docs/images/TCD_Camps/output_11.png)
```
``` {tabbed} Moyo
![Overview](docs/images/TCD_Camps/output_22.png)
```
``` {tabbed} N'Djamena
![Overview](docs/images/TCD_Camps/output_23.png)
```
``` {tabbed} Oure Cassoni
![Overview](docs/images/TCD_Camps/output_5.png)
```
``` {tabbed} Treguine
![Overview](docs/images/TCD_Camps/output_6.png)
```
``` {tabbed} Touloum
![Overview](docs/images/TCD_Camps/output_12.png)
```