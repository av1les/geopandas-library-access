This jupyter notebook was developed as a part of my learning journey with geospatial Python libraries.
My main objective was to test my own ability to manipulate, analyze, and visualize geospatial data.
This notebook has three goals:  
**(1)** create a categorical map of Los Angeles County that demonstrates which 
zip codes have public libraries and which zip codes do not, while showcasing the distribution of public libraries
as points.  
**(2)** Conduct a nearest neighbor analysis for zip codes that do not contain a public library. Essentially,
the question that I wanted to answer is, *"for someone living in the geographic center of this zip code, which public library
is their closest option?"*   
**(3)** Use the nearest neighbor dataset to take a magnified look at neighborhoods with 
high population densities and clusters of zip codes with no public libraries. Determine if the nearest neighbor
distance is disproportionate, and use advanced plotting techniques *(i.e. subplotting, basemap importing)* to visualize.

  
Data on public libraries was collected from LAPL, LACL, and the Southern California Library Cooperative.

  
Zip code data was recovered from the LA City GeoHub: https://geohub.lacity.org/datasets/lacounty::la-county-zip-codes/about
