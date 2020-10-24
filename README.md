# Relationship-between-a-wildfire-size-and-its-cause
A decision tree is constructed to help analyze two datasets containing wildfire data statistics in order to determine if a wildfire cause have an effect on its size. The data is available on the California Fire Protection Department website (https://www.fire.ca.gov/media/10060/2016_redbook_final.pdf).

Among all the available datasets, only two were selected as they seemed to be the most appropriate for the study:
1) Wildfire cause by county
This dataset gives an idea of the most frequent causes of wildfire in each country in California. Twelve (12) causes (arson, campfire, debris burning, vehicle, undetermined, electrical power, smoking, equipment use, Playing-with-fire, lightning, railroad and miscellaneous) have been identified and the dataset lists the number of fires according to their origin.
2) Wildfire size by county
Each fire that occurs is classified according to its size. Seven (7) size categories are defined in the dataset:
1) 0-0.25 acres 2) 0.26-99 acres 3) 10-99 acres 4) 100-299 acres 5) 300-999 acres 6) 1000-4999 acres and 7) 5000+ acres

#Data processing
- The first data preparation step consisted in merging both datasets based on one common variable (county).
- Fire causes were categorized (numerical label assigned to each cause) so that they can be used as a predictor in the model.
- The majority of fires across all counties have a size less or equal to 0.25 acres, therefore the study only focus on this size category.
- Records that have no fire of size less or equal to 0.25 acres have been removed from the initial dataset.

