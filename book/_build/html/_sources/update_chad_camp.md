# Post-update OSM data report

In this project We focused on the mapping and improving of buildings and roads in 21 camps of Chad. Also, We added water bodies like rivers and streams but in less quantity since these features were not found in all the camps.

The mapping was done following the good practices of OSM mapping, mainly during the validation and improvement of the existing data on the map added by other mappers from the OSM community.

## Mapping Tools:

The tools used in the mapping were:

- [OpenStreetMap](https://www.openstreetmap.org/): A collaborative project to create free and editable maps. All the data were updated directly here.
- [JOSM](https://josm.openstreetmap.de/): The OpenStreetMap editor used by the DevSeed data team to do editions easier and faster.
- [Tasking Manager](https://github.com/hotosm/tasking-manager): A tool that allows us the dividing the Camps into small areas, so each mapper can select a task and avoid conflicts during the mapping.

![Mapping workflow with JOSM editor and a Tasking Manager](docs/images/update_chat/post_update_chad_camp_1.gif)
**Figure 1 - Mapping workflow with JOSM editor and a Tasking Manager**

## Validating existing OSM data

Previous to the mapping process we found data added by other mappers from the OSM community and most of this data was added trough projects from [Humanitarian OpenStreetMap Team](https://www.hotosm.org/).

Some of these data had good quality but in most of the camps they had to be improved in order to align them to the most current imagery and improve the buildings and roads shapes.

<div style="display: inline-block">
  <div style="float: left; width: 49%;  padding: 2px;">

![Data previous to the updating](docs/images/update_chat/post_update_chad_camp_2.png)

**Figure 2 - Data previous to the updating**

  </div>
  <div style=" float: right; width: 49%;  padding: 2px;">

![Data after to the updating](docs/images/update_chat/post_update_chad_camp_3.png)

**Figure 3 - Data after to the updating**

  </div>
</div>

Although a most current imagery was selected for the mapping of a camp, based on an evaluation of the different imagery and the area of the camp, We found editions that did not match with any satellite imagery and according to their source they were added by local knowledge. These editions were not changed and they were left as they were found.

![Buildings and highways added by local knowledge](docs/images/update_chat/post_update_chad_camp_4.png)
**Figure 4 - Buildings and highways added by local knowledge**

## Mapping of camps without data

There were camps that did not have any data or the coverage of the existing data was very low. On those camps, We added all the buildings and all types of roads visible on the satellite imagery.

![Comparison of the Pre-update data VS Post-update data in Treguine Camp](docs/images/update_chat/post_update_chad_camp_5.gif)
**Figure 5 - Comparison of the Pre-update data VS Post-update data in Treguine Camp**

## Challenges in the mapping

The main difficulty during the mapping was the low quality of the satellite imagery, which was more notable in some camps where the density of the buildings was high or in areas with a lot of trees which did difficult to recognize and map all the buildings.

We found these cases, mostly in Maxar imagery, while in Bing imagery was easier to recognize and map the buildings, however, since Bing is older than Maxar, We mapped the features with Maxar imagery.

<div style="display: inline-block">
  <div style="float: left; width: 49%;  padding: 2px;">

![Maxar imagery with trees](docs/images/update_chat/post_update_chad_camp_6.png)

**Figure 6 - Maxar imagery with trees**

  </div>
  <div style=" float: right; width: 49%;  padding: 2px;">

![Bing imagery](docs/images/update_chat/post_update_chad_camp_7.png)

**Figure 7 - Bing imagery**

  </div>
</div>

![Trees covering buildings in the area](docs/images/update_chat/post_update_chad_camp_8.png)

**Figure 8 - Trees covering buildings in the area**

## Post-update stats

At the end of the mapping, the Data team completed the mapping of 21 from the 22 camps.
In the below table We can see the final stats of buildings and roads added/improved per each of the camps that were mapped by DevSeed Data Team.

<table class="colwidths-auto table" >
  <thead>
    <tr class="row-odd">
      <th rowspan="2" class="head">
        <p><strong>N??</strong></p>
      </th>
      <th rowspan="2" class="head">
        <p><strong>Camps</strong></p>
      </th>
      <th rowspan="2" class="head">
        <p><strong>Most current imagery</strong></p>
      </th>
      <th colspan="2" class="head">
        <p><strong>Total buildings </strong></p>
      </th>
      <th colspan="2" class="head">
        <p><strong>Total highway Length </strong></p>
      </th>
      <th rowspan="2" class="head">
        <p><strong>OSM link</strong></p>
      </th>
    </tr>
    <tr class="row-even">
      <th class="head">
        <p><strong>Previous mapping</strong></p>
      </th>
      <th class="head">
        <p><strong>After mapping</strong></p>
      </th>
      <th class="head">
        <p><strong>Previous mapping</strong></p>
      </th>
      <th class="head">
        <p><strong>After mapping</strong></p>
      </th>
    </tr>
  </thead>
  <tbody>
  <tr class="row-odd">
    <td><p>01</p></td>
    <td><p>Amboko Camp</p></td>
    <td><p>Maxar Premium</p></td>
    <td><p>1,813</p></td>
    <td><p>3,368</p></td>
    <td><p>8.051 km</p></td>
    <td><p>14.326 km</p></td>
    <td><p><a class="reference external" href="https://www.openstreetmap.org/way/197262638">https://www.openstreetmap.org/way/197262638</a></p></td>
  </tr>
  <tr class="row-even">
    <td><p>02</p></td>
    <td><p>Amnabak</p></td>
    <td><p>Maxar Premium</p></td>
    <td><p>398</p></td>
    <td><p>6,896</p></td>
    <td><p>1.472 km</p></td>
    <td><p>50.837 km</p></td>
    <td><p><a class="reference external" href="https://www.openstreetmap.org/way/462577820">https://www.openstreetmap.org/way/462577820</a></p></td>
  </tr>
  <tr class="row-odd">
    <td><p>03</p></td>
    <td><p>Belom</p></td>
    <td><p>Maxar Premium</p></td>
    <td><p>4,450</p></td>
    <td><p>9,598</p></td>
    <td><p>27.338 km</p></td>
    <td><p>70.768 km</p></td>
    <td><p><a class="reference external" href="https://www.openstreetmap.org/way/229227293">https://www.openstreetmap.org/way/229227293</a></p></td>
  </tr>
  <tr class="row-even">
    <td><p>04</p></td>
    <td><p>Bredjing Camp</p></td>
    <td><p>Maxar Premium</p></td>
    <td><p>34</p></td>
    <td><p>11,195</p></td>
    <td><p>14.743 km</p></td>
    <td><p>34.452 km</p></td>
    <td><p><a class="reference external" href="https://www.openstreetmap.org/way/462543665">https://www.openstreetmap.org/way/462543665</a></p></td>
  </tr>
  <tr class="row-odd">
    <td><p>05</p></td>
    <td><p>Daha 1 Village</p></td>
    <td><p>Bing Aerial</p></td>
    <td><p>222</p></td>
    <td><p>1,821</p></td>
    <td><p>6.035 km</p></td>
    <td><p>25.328 km</p></td>
    <td><p><a class="reference external" href="https://www.openstreetmap.org/way/618226171">https://www.openstreetmap.org/way/618226171</a><br><a class="reference external" href="https://www.openstreetmap.org/way/606743679">https://www.openstreetmap.org/way/606743679</a></p></td>
  </tr>
  <tr class="row-even">
    <td><p>06</p></td>
    <td><p>Dembo</p></td>
    <td><p>Maxar Premium</p></td>
    <td><p>2,324</p></td>
    <td><p>3,701</p></td>
    <td><p>41.02 km</p></td>
    <td><p>34.722 km</p></td>
    <td><p><a class="reference external" href="https://www.openstreetmap.org/way/597226998">https://www.openstreetmap.org/way/597226998</a></p></td>
  </tr>
  <tr class="row-odd">
    <td><p>07</p></td>
    <td><p>Diba Village</p></td>
    <td><p>Maxar Premium</p></td>
    <td><p>0</p></td>
    <td><p>468</p></td>
    <td><p>0.455 km</p></td>
    <td><p>3.792 km</p></td>
    <td><p><a class="reference external" href="https://www.openstreetmap.org/way/594095129">https://www.openstreetmap.org/way/594095129</a></p></td>
  </tr>
  <tr class="row-even">
    <td><p>08</p></td>
    <td><p>Djabal Camp</p></td>
    <td><p>Maxar Premium</p></td>
    <td><p>4,884</p></td>
    <td><p>9,259</p></td>
    <td><p>49.163 km</p></td>
    <td><p>56.947 km</p></td>
    <td><p><a class="reference external" href="https://www.openstreetmap.org/way/881919013">https://www.openstreetmap.org/way/881919013</a></p></td>
  </tr>
  <tr class="row-odd">
    <td><p>09</p></td>
    <td><p>Doholo Camp</p></td>
    <td><p>Maxar Premium</p></td>
    <td><p>2,037</p></td>
    <td><p>2,218</p></td>
    <td><p>3.314 km</p></td>
    <td><p>45.76 km</p></td>
    <td><p><a class="reference external" href="https://www.openstreetmap.org/way/755468804">https://www.openstreetmap.org/way/755468804</a></p></td>
  </tr>
  <tr class="row-even">
    <td><p>10</p></td>
    <td><p>Dosseye Camp</p></td>
    <td><p>Maxar Premium</p></td>
    <td><p>1,503</p></td>
    <td><p>4,781</p></td>
    <td><p>36.14 km</p></td>
    <td><p>81.961 km</p></td>
    <td><p><a class="reference external" href="https://www.openstreetmap.org/way/345244949">https://www.openstreetmap.org/way/345244949</a></p></td>
  </tr>
  <tr class="row-odd">
    <td><p>11</p></td>
    <td><p>Farchana</p></td>
    <td><p>Maxar Premium</p></td>
    <td><p>7</p></td>
    <td><p>7,524</p></td>
    <td><p>37.94 km</p></td>
    <td><p>54.718 km</p></td>
    <td><p><a class="reference external" href="https://www.openstreetmap.org/way/251885724">https://www.openstreetmap.org/way/251885724</a></p></td>
  </tr>
  <tr class="row-even">
    <td><p>12</p></td>
    <td><p>Gaga Camp</p></td>
    <td><p>Maxar Premium</p></td>
    <td><p>18</p></td>
    <td><p>11,647</p></td>
    <td><p>13.735 km</p></td>
    <td><p>67.895 km</p></td>
    <td><p><a class="reference external" href="https://www.openstreetmap.org/way/462564704">https://www.openstreetmap.org/way/462564704</a></p></td>
  </tr>
  <tr class="row-odd">
    <td><p>13</p></td>
    <td><p>Gondje Camp</p></td>
    <td><p>Maxar Premium</p></td>
    <td><p>1,168</p></td>
    <td><p>2,273</p></td>
    <td><p>38.339 km</p></td>
    <td><p>43.807 km</p></td>
    <td><p><a class="reference external" href="https://www.openstreetmap.org/way/883703067">https://www.openstreetmap.org/way/883703067</a></p></td>
  </tr>
  <tr class="row-even">
    <td><p>14</p></td>
    <td><p>Goz Amir Camp</p></td>
    <td><p>Maxar Premium</p></td>
    <td><p>133</p></td>
    <td><p>22,318</p></td>
    <td><p>25.83 km</p></td>
    <td><p>138.422 km</p></td>
    <td><p><a class="reference external" href="https://www.openstreetmap.org/way/199347779">https://www.openstreetmap.org/way/199347779</a></p></td>
  </tr>
  <tr class="row-odd">
    <td><p>15</p></td>
    <td><p>Iridimi</p></td>
    <td><p>Maxar Premium</p></td>
    <td><p>8,213</p></td>
    <td><p>12,486</p></td>
    <td><p>20.555 km</p></td>
    <td><p>64.854 km</p></td>
    <td><p><a class="reference external" href="https://www.openstreetmap.org/way/198678903">https://www.openstreetmap.org/way/198678903</a><br>(This camp includes different boundaries. One of them is the above boundary.)</p></td>
  </tr>
  <tr class="row-even">
    <td><p>16</p></td>
    <td><p>Kounoungou Camp</p></td>
    <td><p>Maxar Premium</p></td>
    <td><p>34</p></td>
    <td><p>7,078</p></td>
    <td><p>7.95 km</p></td>
    <td><p>40.216 km</p></td>
    <td><p><a class="reference external" href="https://www.openstreetmap.org/way/462573532">https://www.openstreetmap.org/way/462573532</a></p></td>
  </tr>
  <tr class="row-odd">
    <td><p>17</p></td>
    <td><p>Mile Camp</p></td>
    <td><p>Maxar Premium</p></td>
    <td><p>5,343</p></td>
    <td><p>6,910</p></td>
    <td><p>21.314 km</p></td>
    <td><p>57.652 km</p></td>
    <td><p><a class="reference external" href="https://www.openstreetmap.org/way/462585747">https://www.openstreetmap.org/way/462585747</a></p></td>
  </tr>
  <tr class="row-even">
    <td><p>18</p></td>
    <td><p>Moyo</p></td>
    <td><p>Maxar Premium</p></td>
    <td><p>7</p></td>
    <td><p>1,627</p></td>
    <td><p>0.0 km</p></td>
    <td><p>33.172 km</p></td>
    <td><p><a class="reference external" href="https://www.openstreetmap.org/way/213159627">https://www.openstreetmap.org/way/213159627</a></p></td>
  </tr>
  <tr class="row-odd">
    <td><p>19</p></td>
    <td><p>Oure Cassoni Camp</p></td>
    <td><p>Maxar Premium</p></td>
    <td><p>8,623</p></td>
    <td><p>20,245</p></td>
    <td><p>37.673 km</p></td>
    <td><p>80.44 km</p></td>
    <td><p><a class="reference external" href="https://www.openstreetmap.org/way/198231230">https://www.openstreetmap.org/way/198231230</a></p></td>
  </tr>
  <tr class="row-even">
    <td><p>20</p></td>
    <td><p>Touloum</p></td>
    <td><p>Maxar Premium</p></td>
    <td><p>7,832</p></td>
    <td><p>9,672</p></td>
    <td><p>53.97 km</p></td>
    <td><p>92.742 km</p></td>
    <td><p><a class="reference external" href="https://www.openstreetmap.org/way/462580702">https://www.openstreetmap.org/way/462580702</a></p></td>
  </tr>
  <tr class="row-odd">
    <td><p>21</p></td>
    <td><p>Treguine Camp</p></td>
    <td><p>Maxar Premium</p></td>
    <td><p>0</p></td>
    <td><p>11,962</p></td>
    <td><p>19.522 km</p></td>
    <td><p>42.235 km</p></td>
    <td><p><a class="reference external" href="https://www.openstreetmap.org/way/462543655">https://www.openstreetmap.org/way/462543655</a></p></td>
  </tr>
  <tr class="row-even">
    <td><p>22</p></td>
    <td><p>Vom village</p></td>
    <td><p>Maxar Premium</p></td>
    <td><p>0</p></td>
    <td><p>1,275</p></td>
    <td><p>1.909 km</p></td>
    <td><p>9.251 km</p></td>
    <td><p><a class="reference external" href="https://www.openstreetmap.org/way/594095131">https://www.openstreetmap.org/way/594095131</a></p></td>
  </tr>
</tbody>
</table>

Since We completed the hours of the project, We were unable to map and validate the data of ???Kounoungou Camp???, however, this was mapped by the community and now it presents more data compared to what was found in the pre-update report.
