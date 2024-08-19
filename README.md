# The SCENARIO ATHENS
It is an experimental scenario developed in the Athens, Greece downtown area. The scenario is useful for testing first/last mile transport systems, e.g., e-bikes, e-scooters, etc. Most of the trip distances do not exceed the 10 km. The study area includes Athens’ commercial triangle where shops, hotels, restaurants, etc. are concentrated. In addition, Ministries and Public Services can be found around Syntagma Square and Panepistimiou Avenue. The road network mostly consists of narrow (one way) streets and pedestrianized zones, which hinder the use of private cars. As an alternative, there are six metro sta-tions and two tram stations, which support the trips from/to the city center of Athens making public transport as the most efficient and therefore attractive option for accessing to the study area. 

There is an online map of [The SCENARIO ATHENS](https://lotentua.github.io/The_Scenario_Athens). Please click on the links to see their attributes.

The road network consist of 257 nodes and 400 links!

It is an experimental scenario for potential users of [Psafechoices](https://github.com/lotentua/Perceived_safety_choices/tree/main/Psafechoices) package

For simplicity, only nine external zones are specified, i.e., node 1000, 2000, 3000, 4000, 5000, 6000, 7000, 8000 and 9000. These zones are connected with the established road network via a single uni-directional link. In the scenario, a buffer zone of 1500 meters has been created. We have established some depots around it to perform some optimization experiments.

The spatial data that describe road infrastructure have been collected in a standarized format. In the [shapefile](https://github.com/lotentua/Perceived_safety_choices/tree/main/scenario_athens/shapefiles) folder, there are .qml files  with the respective styles. In QGIS, spatial data are imported using a dropdown menu. Please respect it, otherwise the [Psafechoices](https://github.com/lotentua/Perceived_safety_choices/tree/main/Psafechoices) package cannot be used to process the spatial data. Attention, use the SNAPPING tool in QGIS, so that the start/end point of a link will have the same coordinates with the respective node.

We strongly recommend to download our shapefiles before starting to develope your own plans.

<img src="https://github.com/lotentua/Perceived_safety_choices/assets/121678451/2bd4a5aa-6483-4e37-aa35-5d66b6832f95" height="650">

**Main assumptions behind this experimental network are:**
1) Pedestrianized streets have been excluded. Some exceptions to this are Aiolou Street and the route from Dion. Aeropagitou and Apost. Pavlou Streets, which comprise a wide, 1.38 km long pedestrianized route that connects the Acropolis of Athens with the Ancient Market.

2) E-bikes and e-scooters as flexible modes can enter in all links of the network.

3) E-bikes and e-scooter fully respect the directions of the links - especially in the inner road network where many one-way liks can be found.

4) In the developed network, there are no cycle lanes with the exemption of Vas. Olgas and Panepistimiou Avenues where pop-up cycle lanes were established in May 2020. Double links have been designed there, as cycle lane are unidirectional and Panepistimiou is one-way for cars.
  
**Papers that used [The SCENARIO ATHENS](https://lotentua.github.io/The_Scenario_Athens):**

Tzouras, P.G., Mitropoulos, L., Koliou, K., Stavropoulou, E., Karolemeas, C., Antoniou, E., Karaloulis, A., Mitropoulos, K., Vlahogianni, E.I., Kepaptsoglou, K., 2023. Describing Micro-Mobility First/Last-Mile Routing Behavior in Urban Road Networks through a Novel Modeling Approach. Sustainability 15, 3095. https://doi.org/10.3390/su15043095

Tzouras, P.G., Mitropoulos, L., Karolemeas, C., Stravropoulou, E., Vlahogianni, E.I., Kepaptsoglou, K., 2024. Agent-based simulation model of micro-mobility trips in heterogeneous and perceived unsafe road environments. Journal of Cycling and Micromobility Research 2, 100042. https://doi.org/10.1016/j.jcmr.2024.100042

