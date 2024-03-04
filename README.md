## An avanced framework for semantic querying of the dynamic world dataset

## What is the 'Dynamic World'?
This is a LULC dataset provided by Google and the World Resources Institute. The Dynamic World dataset offers near real-time global Sentinel-2 land use/land cover (LULC) mapping, generated using a Fully Convolutional Neural Network (FCNN).

<img width="394" alt="image" src="https://github.com/lisahligono/sem4dw/assets/72496335/23aaf634-191d-4941-8dd7-ddb2e6a69f23">

Index
Name
Description
Color
0
Water
Estimated probability of complete coverage by water
#419bdf
1
Trees
Estimated probability of complete coverage by trees
#397d49
2
Grass
Estimated probability of complete coverage by grass
#88b053
3
Flooded vegetation
Estimated probability of complete coverage by flooded vegetation
#7a87c6
4
Crops
Estimated probability of complete coverage by crops
#e49635
5
Shrub and scrub
Estimated probability of complete coverage by shrub and scrub
#dfc35a
6
Built
Estimated probability of complete coverage by built
#c4281b
7
Bare
Estimated probability of complete coverage by bare
#a59b8f
8
Snow and ice
Estimated probability of complete coverage by snow and ice
#b39fe1
<img width="660" alt="image" src="https://github.com/lisahligono/sem4dw/assets/72496335/9fbf7b28-5497-4819-8133-8a9f5894a8c6">



## Objective
The main objective of this project is to showcase how semantic querying can enhance the analysis of the Dynamic World dataset beyond simple mode-based temporal reduction. By employing semantic querying techniques, users can perform more complex spatial and temporal analysis, unlocking new insights and possibilities for utilizing the dataset.

## Methodology

Semantic Earth Observation (EO) Data Cube: The project builds upon the concept of semantic EO data cubes, which provide categorical information for each observation, enabling users to query data based on semantics.
Implementation: The project utilizes the semantique Python package for semantic querying of the Dynamic World dataset. Semantique is a generic tool designed for querying various types of image categorization data.

Implementation Steps:

Establish connection to the Dynamic World dataset via Google Earth Engine (GEE).
Utilize the semantique Python package for semantic querying.
Define layout, mapping, and query recipe for the semantic querying process.
Perform analysis on the selected area (e.g., Lake Baringo) to study water dynamics using semantic querying techniques.
Visualize the results to identify temporal and spatial patterns in surface water dynamics.
Results:
The project demonstrates the effectiveness of semantic querying in analyzing the Dynamic World dataset. By employing semantic querying techniques, users can gain deeper insights into temporal and spatial dynamics of land cover classes, beyond simple mode-based classification.

## Future Directions:

Integration of semantic querying framework directly into Google Earth Engine for seamless analysis.
Handling probabilities in classification to enhance accuracy and reliability of results.
Testing the dataset and semantic querying approach in various applications to explore its full potential.
