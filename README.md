Land Sold by the Philadelphia Housing Authority from 2010-2022

## DATA SOURCES:

This map was created using the ["Real Estate Transfers"](https://www.opendataphilly.org/dataset/real-estate-transfers) and ["Census Blocks"](https://www.opendataphilly.org/dataset/census-blocks) data sets, both collated by the City of Philadelphia and housed on OpenDataPhilly.

The dataset is available ...
<!-- Would you make the edited dataset available for others to use? You created a new dataset that consists of points across multiple years, could this be posted as a dataset link? -->
 

## MAP AVAILABILITY:

The final map <a href="https://sidef1270.github.io/pha_property_sold/" target="_blank">can be viewed online</a> and this README documentation provides additional information about the process used to create the map.

## DESCRIPTION:

This map represents the spatial layout of all property that the Philadelphia Housing Authority (PHA) transfered or sold between 2010 and the present. The housing authority is the largest provider of public housing in the city of Philadelphia and in the last few decades has often been under scrutiny for corruption, budgetary decisions, housing safety, and furthering gentrification. The PHA funds itself through a combination of federal support, private partnerships, and by buying and selling land in order to create profit. 

From 2010 to the present they have sold approximately 3,600 properties and purchased around 2,700. In recent years they have particularly been criticized by activists and housing advocates for selling off or keeping property vacant to support exorbitant overhead while thousands of people sit on housing waiting lists that have been closed for years. 

I created this map to better understand where the PHA is buying and selling property, and to whom. This map suggests that the distribution of property purchsed is highly concentrated in the Center City downtown area, which is both in close proximity to local social services and, as one of the most expensive areas in the city, generally outside of the communities in which low income tenants live. The spatial distribution of purchases, while also most dense in Center City, is significantly more spread out and includes a number of neighboring areas, like West and South Philadelphia and the neighborhood surrounding Temple University, which have been rapidly gentrifying in the last decade. 

## MAP-MAKING PROCESS: 

Data for all real estate transfers in the city of Philadelphia is collected in real estate transfer datasets by year in both csv and shapefiles. In order to create this map, I used the census blocks shapefile to create my basemap and downloaded real estate data shapefiles by year from 2010 to the present. Each annual dataset was filtered to only include datapoints which included the PHA as one of or the sole "grantor" or "grantee" of the property to an individual, organization, or agency other than themselves (meaning instances where the PHA sold or transferred property ownership to another entity, or vice versa). Each annual dataset was then merged together to create two collated layers of PHA property sales and purchases from 2010 to the present. In order to represent the spatial distribution of property sales, I formatted these layer as heatmaps in order to represent areas of the city where sales were most concentrated.

<!-- Were the heatmaps created in QGIS? Were there any particular settings used to generate the heatmap? -->

