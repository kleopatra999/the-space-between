# space-between
thoughts about visualizing the space between buildings

[rationale](https://medium.com/@saikofish/the-space-between-78ac42fea728).

## places with datas

- [Chicago](https://data.cityofchicago.org/Transportation/Boundaries-Curb-Lines/5gv8-ktcg)
- [Pittsburgh](http://pittsburghpa.gov/dcp/gis/gis-data-new) planimetric data and transportation datasets have street curbs
- [Philadelphia](http://www.pasda.psu.edu/uci/MetadataDisplay.aspx?entry=PASDA&file=PhiladelphiaCurbEdges201201.xml&dataset=169)
- [San Francisco](https://data.sfgov.org/Geographic-Locations-and-Boundaries/City-curbs-and-islands-Zipped-Shapefile-Format-/nvxg-zay4?)
- [Washington, D.C.](http://opendata.dc.gov/datasets/e8299c86b4014f109fedd7e95ae20d52_61) (Roads dataset contains shape area layer). Also valuable: [sidewalks](http://opendata.dc.gov/datasets/2347fa1f3fd9412dbf11aa6441ddca8b_83)
- **New York City** 
    - [Pavement Edges](https://data.cityofnewyork.us/Environment/New-York-City-Pavement-Edges/x9uq-u3qs). Aka curblines.
    - [Sidewalk Features](https://data.cityofnewyork.us/City-Government/Sidewalk-Features/vfx9-tbb6). This is the area for sidewalks (curblines + inside edge of sidewalk).
    - [Roadbed](https://data.cityofnewyork.us/City-Government/Roadbed/xgwd-7vhd). This contains shapes of the asphalt area. There are separate shapes for each leg of road and intersection.
    - Extra credit:
      - [TreeKit street trees and tree beds](http://treekit.org/map/). Super complete street tree information for some neighbourhoods.
      - [NYC Parks Tree Map](https://tree-map.nycgovparks.org/#treeinfo-183882). NYC Parks official dataset. This is live data.
    - Examples: [NYCityMap](http://maps.nyc.gov/doitt/nycitymap/?z=8&p=990753,205789&c=GISBasic).
- **Cambridge, Mass.**
    - [Curbs](https://github.com/cambridgegis/cambridgegis_data/blob/master/Basemap/Curbs/BASEMAP_Curbs.geojson). Non-continuous lines, probably where curb cuts are.
    - [Sidewalks](https://github.com/cambridgegis/cambridgegis_data/blob/master/Basemap/Sidewalks/BASEMAP_Sidewalks.geojson).
    - [Roads](https://github.com/cambridgegis/cambridgegis_data/blob/master/Basemap/Roads/BASEMAP_Roads.geojson). Polygons!
- **Santa Monica, Calif.**
    - [Curbs](https://github.com/CityofSantaMonica/GIS/blob/master/streets/right-of-way.geojson). Non-continuous curb lines.
    - [Right of way](https://github.com/CityofSantaMonica/GIS/blob/master/streets/right-of-way.geojson). A single polygon representing the asphalt area.
- **Virginia Beach, Va.**
    - [Road edges](http://gis.data.vbgov.com/datasets/6f4d45b4c360453da268ee4f8d1a963e_0).
- **Milwaukee, Wis.**
    - [Topo/planimetric data download](http://mclio.maps.arcgis.com/apps/SimpleViewer/index.html?appid=9d71b12ae08440b7af1d092a64b22cb3). Select a square mile area, then select a Topo/Planimetric download, which includes curb edges and more (e.g. tree beds, sidewalks). Formats: DWG, GeoDatabase. 
- **Raleigh, N.C. (Wake County)**
    - [Road edge](http://data.wake.opendata.arcgis.com/datasets/d2ade1af34a9478a848f117500a176f0_25). Data exists (and is [rendered on the GIS portal](http://maps.raleighnc.gov/iMAPS/index.html)) but the download seems broken.

### hall of shame

- **Nashville, Tenn.** will [sell you planimetric data for $500](http://www.nashville.gov/Planning-Department/Mapping-and-GIS/Map-and-Data-Sales.aspx). You can see the data in their GIS portal base maps, but attempting to access the inferred ESRI endpoint that would house this information will cause its server to refuse to connect you to it.
