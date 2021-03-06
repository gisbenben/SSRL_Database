# List of sources

1. 2011 Census boundary files (cartographic and digital):
https://www12.statcan.gc.ca/census-recensement/2011/geo/bound-limit/bound-limit-2011-eng.cfm
2. Natural resources canada geodata:
https://www.nrcan.gc.ca/earth-sciences/geography/topographic-information/free-data-geogratis/download-directory-documentation/17215 or ftp: http://ftp.geogratis.gc.ca/pub/nrcan_rncan/

  2.1 CanVec Multi-scale data: CanVec is a digital cartographical reference product produced by Natural Resources Canada. It originates from the best available data sources covering Canadian territory, offers quality topographical information in vector format and complies with international geomatics standards. CanVec is a multi-source product coming mainly from the National Topographic Data Base (NTDB), the Mapping the North process conducted by the Canada Center for Mapping and Earth Observation (CCMEO), the Atlas of Canada data, the GeoBase initiative and the data update using satellite imagery coverage (e.g. Landsat 7, Spot, Radarsat, etc). CanVec contains more than 60 topographical features organized into 8 themes: Transport Features, Administrative Features, Hydro Features, Land Features, Man-Made Features, Elevation Features, Resource Management Features and Toponymic Features. http://ftp.geogratis.gc.ca/pub/nrcan_rncan/vector/canvec/

  2.2 Atlas_of_Canada at multi-scale: http://ftp.geogratis.gc.ca/pub/nrcan_rncan/vector/framework_cadre/
  Atlas_of_Canada_1M: The Atlas of Canada 1,000,000 National Frameworks data are a set of integrated base map layers which form the Atlas of Canada 1,000,000 National Frameworks Data collection. These data have been compiled at a scale of 1:1,000,000 with the primary goal being to indicate correct relative positioning with other frameworks layers rather than absolute positional accuracy. It was compiled to be used for atlas large scale (1:1,000,000 to 1:4,000,000) mapping. http://ftp.geogratis.gc.ca/pub/nrcan_rncan/vector/framework_cadre/Atlas_of_Canada_1M/

3. Aboriginal data (treaty, first nation, inuit, Community Well-Being Index and etc.):
http://open.canada.ca/maps/dataset?organization=aandc-aadnc

  3.1 First Nation:  http://open.canada.ca/maps/dataset/b6567c5c-8339-4055-99fa-63f92114d9e4
  3.2 Inuit Communities: http://open.canada.ca/maps/dataset/2bcf34b5-4e9a-431b-9e43-1eace6c873bd
  3.3 Treaty:
	 - post-1975: http://open.canada.ca/maps/dataset/be54680b-ea62-46f3-aaa9-7644ed970aef
	 - pre-1975: http://open.canada.ca/maps/dataset/f281b150-0645-48e4-9c30-01f55f93f78e

4. Provincial Norths by Census Divisions:
    Instruction provided by "International Centre for Northern Governance and Development (ICNGD)"

    -	Northern British Columbia (CD Bulkley-Nechako Regional District, Cariboo Regional District, Central Coast Regional District, Fraser Fort George Regional District, Kitimat-Stikine Regional District, Northern Rockies Regional District, Peace River Regional District, and Skeena-Queen Charlotte Regional District, and Stikine Region),
    -	Northern Alberta (CD 16-19),
    -	Northern Saskatchewan (CD 18),
    -	Northern Manitoba (CD 19, 21-23),
    -	Northern Ontario (CD Algoma, Cochrane, Greater Sudbury, Kenora, Manitoulin, Nipissing, Parry Sound, Rainy River, Sudbury, Thunder Bay, Timiskaming),
    -	Northern Quebec (Nord du Quebec CD),
    -	Labrador (CD 10 and 11)

    ```sql
    2011-CDUID IN( '1010','1011','3557','3556','3553','3560','3551','3548','3549','3559','3552','3558','3554','4619','4621','4622','4623','4718','4816','4817','4819','4818','5951','5941','5945','5953','5949','5959','5955','5947','5957','2499')
    ```
5. Northern_Canada_2011:
http://geogratis.gc.ca/api/en/nrcan-rncan/ess-sst/ed9208a8-54dd-516a-9e63-68bc0be258f7.html (shp/fgd download links have been removed)
