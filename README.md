#D3 Presentation Notes

March 5, 2015

###[LIVE PROJECT WEBSITE](http://stat4701-edav-d3.github.io/)
####[The GitHub Project Website Repo](https://github.com/stat4701-edav-d3/stat4701-edav-d3.github.com)
####[The GitHub Project Folder](https://github.com/stat4701-edav-d3/d3-presentation)
#####[The GitHub Organization](https://github.com/stat4701-edav-d3)

##TNoda

[TNoda code and blog post](http://www.tnoda.com/blog/2013-12-07)

##Flu

* [Google Flu Trends](https://www.google.org/flutrends/us/#US)

	* [Data](https://www.google.org/flutrends/us/data.txt) dms_note: might be one of the better/most easily accessible data source. 

* [Centers for Disease Control and Prevention](http://www.cdc.gov/flu/index.htm)

	* [Vaccination Coverage](http://www.cdc.gov/flu/fluvaxview/reports/reporti1314/trends/index.htm) dms_note: might be best source for vaccination information. 
	* [Flu activity](http://www.cdc.gov/flu/weekly/fluactivitysurv.htm) dms_note: by state at its finest geographic level it appears at first look. I'll try and dig a little on this. I'm not that well-versed in the different strains of flu so might be useful for that. 
	* [FluView](http://gis.cdc.gov/grasp/fluview/main.html)

* [Flu Near You - partnership between HealthMap (healthmap.org) at Boston Children’s Hospital, the American Public Health Association (APHA, apha.org) and the Skoll Global Threats Fund (skollglobalthreats.org)](https://flunearyou.org) dms_note: not sure how I feel about this site yet. Not sure how many users/contributing data it has. 

* [California Immunization Rates for School children](http://www.cdph.ca.gov/programs/immunize/pages/immunizationlevels.aspx)

####[IPython Notebook importing data markdown file](https://github.com/stat4701-edav-d3/d3-presentation/blob/master/01-read-in-source-data-for-all-sources.md)

##D3 

* [D3js.org](http://d3js.org/)

* [Mike Bostocks' Blocks](http://bl.ocks.org/mbostock)
	* [Let's Make a Map](http://bost.ocks.org/mike/map/)
	* [Choropleth](http://bl.ocks.org/mbostock/4060606)

* [Interactive Map with d3.js - ogr documentation for converting shapefiles](http://www.tnoda.com/blog/2013-12-07) dms_note: most likely we'll have to use ogr to convert a shapefile to d3. 

		ogr2ogr -f GeoJSON countries.json ne_10m_admin_0_countries_lakes.shp

* [Derek Watkins Website](http://dwtkns.com/portfolio/)

	* [NY Times - Norway the Slow Way - Pencil sketching Derek Watkins](http://www.nytimes.com/interactive/2014/09/19/travel/reif-larsen-norway.html?_r=0)
	* [Derek Watkins Bl.ocks](http://bl.ocks.org/dwtkns)
	
##RMaps & Leaflet
* [RMaps](http://rmaps.github.io/)
* [DataMaps](http://datamaps.github.io/)


##Markdown Presentations


* [This is CartoDB's Odyssey.js thing for presentations, its not in D3 but it would be really cool to use after showing D3](http://cartodb.github.io/odyssey.js/)
	* [Testing one in our repo](http://htmlpreview.github.io/?https://github.com/stat4701-edav-d3/d3-presentation/blob/master/odyssey/odyssey.html)
