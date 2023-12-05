# Planned revisions to the reanalysis of Reproduction of Kang et al. 2020 

Author: Isaiah, Bennett

## Analysis

1. Write section in the beginning that talks about the original study design and the original reproduction. 

2.  Change the speed limits used in the network analysis to use speed limits by road type from the osmnx network instead of a default 35mph for missing speed limit values.

3. Reaggregate accessibility results into hexagons through an area weighted reaggregation (AWR) instead of by the 50% benchmark. 

4. Write discussion/conclusions sections.

## Results

1. New markdown paragraph

2. This implementation would alter the road network speed limit values replacing unknown values with more accurate inferred values by their specific road type. 

3. Instead of their current aggregation technique, the hope with AWR is to make the hexagons more accurately represent every slice of catchment area that they overlap eliminating any uncertainty made by generalizing a 50% threshold. 

4. New markdown paragraph discussing study results


## Discussion

1. Adds more background context while helping track the provenance of the different versions of the study, so that the reader can see each step that has been made to improve reproducibility 

2. Strengthens results of the study by improving the methods used to navigate missing data.

3.  Removes uncertainty by making sure that every slice of the hospital catchment areas are weighted into the final hexagon grid. 

4. Interprets results and describes areas of further uncertainty or room for improvement.
